# 生图 API 配置

本项目把机制图生成 API 与 Codex API 分开配置。不要把真实 API key 写入可提交文件。

## 配置文件

提交到仓库的是示例文件：

```text
config/image-generation.example.json
```

用户本地可复制为：

```text
config/image-generation.local.json
```

`image-generation.local.json` 已加入 `.gitignore`，用于保存个人 endpoint、模型和环境变量名。推荐格式：

```json
{
  "endpoint": "https://api.openai.com/v1/images/generations",
  "api_key_env": "IMAGE_API_KEY",
  "model": "gpt-image-2",
  "size": "1536x1024",
  "n": 1,
  "response_format": "url"
}
```

## API Key

推荐把密钥放入环境变量，而不是配置文件：

```powershell
$env:IMAGE_API_KEY = "<your image API key>"
```

请求时读取 `api_key_env` 指向的环境变量，并作为 Bearer token：

```http
Authorization: Bearer <value of IMAGE_API_KEY>
```

若用户坚持把 key 写入本地配置，可使用 `api_key` 字段，但只允许写在 `config/image-generation.local.json`，不要写入 example、SKILL.md、references 或 templates。

## 读取优先级

1. 用户在当前任务中明确给出的 endpoint、model、size、key env 名称。
2. `config/image-generation.local.json`。
3. 环境变量：
   - `IMAGE_API_ENDPOINT`
   - `IMAGE_API_KEY`
   - `IMAGE_API_MODEL`
   - `IMAGE_API_SIZE`
4. `config/image-generation.example.json` 中的默认值。

## 默认请求

```http
POST https://api.openai.com/v1/images/generations
Authorization: Bearer <IMAGE_API_KEY>
Content-Type: application/json
```

```json
{
  "model": "gpt-image-2",
  "prompt": "<confirmed image-generation-prompt>",
  "size": "1536x1024",
  "n": 1
}
```

如果服务返回 URL，保存或交付该 URL；如果返回 base64，解码为图片文件。若服务字段与 OpenAI-compatible 格式不同，以用户实际服务文档为准。
