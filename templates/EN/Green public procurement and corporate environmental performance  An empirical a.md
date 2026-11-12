# Green public procurement and corporate environmental performance  An empirical a

## Page 1

Green public procurement and corporate environmental
performance: An empirical analysis based on data from green
procurement contracts
Suyi Zheng a,b,*, Jiandong Wen a,b
a Economics and Management School, Wuhan University, Wuhan, 430072, China
b Center for Economic Development Research, Wuhan University, Wuhan, 430072, China
A R T I C L E I N F O
Keywords:
Green public procurement
Corporate environmental performance
Demand-side policy
Environmental incentive effect
A B S T R A C T
Green public procurement (GPP) is regarded as a vital tool for achieving energy conservation and
emission reduction. This policy aims to guide enterprises towards cleaner production by creating
market demand for green products on the demand side. However, it remains unclear whether GPP
can genuinely improve corporate environmental performance. This study reviews relevant policy
documents and constructs a wordlist of “green procurement contract" using the Word2vec model.
By employing text analysis, we identify public procurement contracts that meet green standards.
Subsequently, we match these contracts with data from China’s A-share-listed companies to
empirically test the impact of GPP contracts on corporate environmental performance. The
findings reveal that GPP significantly enhances corporate environmental performance, primarily
through conceptual governance effects, source governance effects, terminal governance effects,
and supervision governance effects. Heterogeneity analysis indicates that this environmental
incentive effect is particularly significant among non-state-owned enterprises and small and
medium-sized enterprises. Additionally, the effect is more pronounced in regions with high
government environmental awareness and moderate environmental enforcement intensity.
Further analysis shows that GPP also improves corporate social responsibility performance and
promotes corporate ESG performance, thereby fostering sustainable development. Moreover, the
study points out that increasing the transparency of information disclosure, enhancing procure-
ment efficiency, and maintaining the stability of procurement relationships all contribute to
strengthening the environmental performance incentive effect of GPP. This article helps to deepen
the understanding of the “proactive government” promoting the development of green economy
and also provides theoretical reference for the breakthrough of corporate green transformation
under the target of “dual carbon.”
1. Introduction
In recent years, global ecological and environmental problems have become increasingly prominent, and the concept of green and
sustainable development has received widespread attention from governments (Drempetic et al., 2020). Although China has made
remarkable achievements in economic construction, it has also brought about serious resource and environmental problems. As a
* Corresponding author. Economics and Management School, Wuhan University, Wuhan, 430072, China.
E-mail addresses: zhengsuyi@whu.edu.cn (S. Zheng), jdwen@whu.edu.cn (J. Wen).
Contents lists available at ScienceDirect
International Review of Economics and Finance
journal homepage: www.elsevier.com/locate/iref
https://doi.org/10.1016/j.iref.2024.103578
Received 4 July 2024; Received in revised form 24 August 2024; Accepted 31 August 2024
International Review of Economics and Finance 96 (2024) 103578
Available online 5 September 2024
1059-0560/© 2024 Elsevier Inc. All rights are reserved, including those for text and data mining, AI training, and similar technologies.


## Page 2

major carbon emitter, China’s environmental governance issues are particularly noteworthy (Ren et al., 2023). As the main agent of
market economic activities, enterprises have generated significant negative externalities on the natural environment while trans-
forming various resources into corporate value. Thus, the importance of corporate roles in environmental protection and pollution
reduction cannot be overstated (He et al., 2016). Against the backdrop of the “dual-carbon” target, studying how to enhance corporate
environmental performance holds significant theoretical and practical value.
As rational economic agents, enterprises always aim at profit maximization (Friedman, 1989). Environmental governance, how-
ever, does not provide immediate economic returns, leaving companies with little intrinsic motivation to improve their environmental
performance. This necessitates external regulation and incentive measures. Governments worldwide have implemented various
environmental policies to guide and supervise companies in addressing pollution issues, such as emission charges, clean production
standards, environmental protection laws, environmental taxes, green credit policies, low-carbon city pilot policies, and more (Fang
et al., 2021; Li et al., 2024; Sun et al., 2019, 2023; Xu et al., 2023; Zhao et al., 2022). Many scholars have focused their research on the
“Porter Hypothesis” (Porter & Linde, 1995), suggesting that stringent environmental regulations can drive technological innovation in
firms and exert effective regulatory pressure, thus becoming a crucial driver for corporate green transformation and enhanced
environmental performance (Chang, 2011; Liao, 2018; Lin & Chen, 2020). Leiter et al. (2011) posited that strict environmental
regulations, such as environmental taxes, encourage firms to invest in emission reduction technologies, although the positive impact of
environmental regulation diminishes with more stringent constraints. Yu et al. (2022) found that carbon emission trading markets,
which leverage market mechanisms, represent a significant practical exploration for achieving energy savings and emission re-
ductions, effectively improving corporate environmental performance. Han et al. (2021) further classified environmental regulation
into three types: command-and-control regulation, market incentive regulation, and informal regulation, and found that all three types
of environmental regulation can promote enterprises to improve their environmental performance.
Among numerous policy tools, it should be noted that public procurement is an effective means of guiding and precisely regulating
corporate behavior. As an important part of national financial expenditure, public procurement can serve as both a macroeconomic
regulatory tool and an industry leader at the microeconomic level (Barro & Redlick, 2011; Bleda & Chicot, 2020; Obwegeser & Müller,
2018). With the increasing concern about pollutant emissions in industrial production, green public procurement (GPP) has been
implemented in many developed countries and is regarded as an important policy tool to realize energy savings and emission reduction
(Krieger & Zipperer, 2022). For example, Germany’s Blue Angel eco-labeling system mandates that government agencies prioritize the
procurement of eco-labeled products. In comparison, China’s GPP system was established later but has developed rapidly. The Cleaner
Production Promotion Law of the People’s Republic of China, issued in 2003, emphasized that “governments at all levels should
prioritize the procurement of products that are energy-saving, water-saving, and conducive to environmental and resource protection,”
which fully affirmed the environmental governance function of public procurement from the legal level. “The Implementation
Opinions on Government Procurement of Energy-Saving Products”, issued in 2004, required public institutions to give priority to
energy-saving products in procurement. In recent years, the Ministry of Finance has continuously improved GPP policies, forming two
main categories of product lists: energy-saving and environmentally labeled products, and promoting the application of green pro-
curement standards in fields such as building materials, express packaging, product packaging, and data centers.
Unlike traditional environmental regulation, GPP provide market demand for green products by setting up clear green bidding
requirements, guiding enterprises to clean production on the demand side, and then driving the green transformation and upgrading of
industries. At present, existing studies in the field of GPP are mainly based on case studies, focusing on GPP policies, influencing factors
of policy implementation, environmental standards, and barriers to promotion (Nissinen et al., 2009; McMurray et al., 2014; Igarashi
et al., 2015; Rosell, 2021; Sparrevik et al., 2018; Ye et al., 2022). Research on the effectiveness of GPP implementation is relatively
limited. In recent years, some scholars have attempted to quantitatively analyze the actual impact of GPP on environmental sus-
tainability and corporate innovation behavior. The limited research primarily focuses on the effects of GPP on environmental output,
green market demand, and corporate green innovation capabilities (Cerutti et al., 2016; Krieger & Zipperer, 2022; Lindstr¨om et al.,
2020; Simcoe & Toffel, 2014; Zhang & Jiang, 2022). However, there is currently a lack of literature that deeply explores the role of GPP
policies in improving corporate environmental performance. GPP, as an important means of regulating macroeconomic operations and
protecting the environment, are primarily aimed at achieving environmental governance effects and promoting industrial green
transformation. However, the green innovation activities of enterprises are not equivalent to the environmental governance effect of
enterprises, and it is not clear whether GPP policy can really improve the environmental performance of enterprises. The purpose of
this paper is to explore whether and how GPP can enhance corporate environmental performance, attempting to achieve a compre-
hensive understanding of the micro-environmental governance effects of GPP.
Specifically, this paper used crawler technology to obtain public procurement contract data from the China Government Pro-
curement Network from 2015 to 2021. Further, by combing the list of green public procurement items and related documents of GPP
policy, this paper constructed a word list of “green procurement contract” using the Word2Vec model. Finally, through text analysis,
this paper successfully identified green procurement contracts and matched them with data from Chinese A-share listed companies to
empirically test the impact of GPP contracts on corporate environmental performance. This study finds that GPP significantly promotes
the improvement of corporate environmental performance, and this effect mainly stems from green procurement contracts rather than
general public procurement contracts. Further mechanism analysis shows that GPP enhances corporate environmental performance
through conceptual governance effects, source governance effects, terminal governance effects, and supervision governance effects.
Heterogeneity analysis indicates that the environmental incentive effects of GPP are particularly significant in non-state-owned en-
terprises, small and medium-sized enterprises and heavy-polluting enterprises. Meanwhile, the effect on improving environmental
performance is more pronounced in regions with high governmental environmental attention and moderate environmental enforce-
ment intensity. In further analysis, this paper also finds that GPP not only improves corporate environmental performance but also
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
2


## Page 3

significantly enhances corporate social responsibility performance, and promotes ESG (environmental, social, and governance) per-
formance, driving companies towards sustainable development. Additionally, this paper explores how to further strengthen the impact
of GPP from the perspective of the policy itself. It has been found that enhancing the transparency of procurement information,
improving the efficiency of procurement, and maintaining the stability of procurement relationships all contribute to enhancing the
environmental performance incentives of GPP.
The main contributions of this article include the following three points. First, this paper identifies green procurement contracts by
combining green procurement project lists and relevant policy documents through text analysis, thereby creating a foundation for
accurately evaluating the effects of GPP policy. Few empirical studies on Chinese data in the existing literature distinguish green public
procurement from general public procurement. However, there are significant differences in goals and functions between public
regular procurement and green procurement, and conflating the two could lead to biased evaluation results. Although a few studies
have approached this from the perspective of the green procurement list system (Zhang & Jiang, 2022), this system only covers a
portion of green procurement products, which could result in measurement errors when assessing GPP policy. Therefore, this paper
draws on the idea of Krieger and Zipperer (2022) to construct a word list of “green procurement contracts,” which can effectively
identify GPP contracts and accurately estimate the effect of GPP on corporate environmental performance. Moreover, in the robustness
test, this paper finds that this effect mainly comes from green procurement contracts rather than general procurement contracts, which
further illustrates the necessity of identifying green procurement contracts.
Secondly, from the perspective of green public procurement, this article provides useful supplements to the driving factors for
improving corporate environmental performance at the macro-policy level. Many scholars have focused on the “Porter Hypothesis,”
paying attention to the impact of external environmental regulations on corporate green transformation and environmental perfor-
mance improvement (Fang et al., 2021; Li et al., 2024; Sun et al., 2019, 2023; Xu et al., 2023; Zhao et al., 2022). However, little
literature has paid attention to the driving force of GPP as an important environmental policy tool. Unlike traditional environmental
regulations, GPP is a policy tool that is both clear and mandatory, as well as flexible, which balances government will and market
mechanisms. Therefore, by accurately identifying GPP policy, this paper examines the role of GPP in improving corporate environ-
mental performance and the inherent influence mechanism, which not only provides a practical way for enterprises to achieve sus-
tainable development but also emphasizes the key role of “active government” in incentivizing corporate environmental governance.
Thirdly, based on fully clarifying the impact of GPP policy on corporate environmental performance, this article further explores
the improvement direction of policy implementation effects, providing theoretical support for the increasing improvement of GPP
policy. The existing literature mainly provides rich qualitative discussions on GPP (Nissinen et al., 2009; McMurray et al., 2014;
Igarashi et al., 2015; Rosell, 2021; Sparrevik et al., 2018; Ye et al., 2022). However, quantitative research is still insufficient. This
article not only enriches the relevant research on the implementation effect of GPP, but also explores in depth how to better achieve the
role of improving corporate environmental performance in the policy implementation process. This article focuses on three aspects of
transparency of procurement information disclosure, procurement efficiency, and stability of procurement relationships. By enhancing
the effectiveness of policies themselves, it provides strong theoretical support for the continuous improvement of GPP policies in order
to maximize their policy dividends.
The remainder of this paper is organized as follows: The relevant studies and hypothesis development are covered in Section 2. The
data and methodology are introduced in Section 3. The empirical results are shown in Section 4. Section 5 offers the mechanism tests
and heterogeneity effect. Section 6 offers an additional discussion. The policy recommendations and conclusions are presented in
Section 7.
2. Relevant studies and hypothesis development
Due to the negative externalities of environmental pollution and the positive externalities of corporate environmental re-
sponsibility, the costs and uncertainties associated with improving environmental performance conflict with the goal of profit
maximization for firms. According to Campbell (2007), firms face a conflict between resource allocation and externalities when
balancing social responsibility and the pursuit of profit maximization. It is difficult to fundamentally solve the market failure problem
caused by externalities by relying only on market. In this context, active government intervention is necessary, utilizing macroeco-
nomic regulation, market supervision, and other functions to provide effective guidance for firms to improve their environmental
governance performance (Castells & Mohnen, 2015). As a demand-side fiscal policy, GPP can guide and drive more policies and social
funds to support green and low-carbon development through clear green bidding requirements, the creation of green market demand,
and the establishment of an effective regulatory mechanism. This demand-side pressure forces enterprises to undergo green trans-
formation and upgrading, and thus promote the improvement of their environmental performance.
On the one hand, GPP provides a wider market demand for green products and environmental services with its large purchase scale
and strong market influence (Czarnitzki et al., 2020), promoting green innovation and green production in enterprises through market
mechanisms (Kou et al., 2024; Krieger & Zipperer, 2022). This significantly improved the corporate environmental performance.
Meanwhile, through its strong purchasing demonstration effect, GPP can not only drive the low-carbon consumption concept of the
whole society, but also guide and drive more policies and social funds to support green and low-carbon development. This prompts
enterprises to choose environmentally friendly production models, thereby further improving their environmental performance.
On the other hand, GPP sets specific environmental standards and clear breach of contract responsibilities through procurement
contracts, which subject enterprises to stricter government supervision, forcing supplier enterprises to reduce pollution emissions and
improve environmental performance in the production process. For example, the “Green Data Center Government Procurement Re-
quirements Standard” issued in 2021 requires purchasers to include green requirements for data center design, information products
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
3


## Page 4

and supporting equipment, and operations and maintenance in procurement documents. The procurement contracts must specify
random inspections, energy consumption monitoring, and liability for breach of contract during the acceptance process. These pro-
visions ensure that enterprises must use technologies and equipment that meet green standards in the design and operation of data
centers. The government will conduct random inspections and energy consumption monitoring to assess the environmental perfor-
mance of enterprises and supervise whether their actual operations meet environmental requirements. Enterprises that fail to meet the
required green standards will face serious consequences from contractual default, including financial penalties and market access
restrictions. This clear liability motivates enterprises to pay more attention to the improvement of their environmental performance
during the production and operation processes in order to avoid the economic loss and reputation damage due to breaches. Therefore,
this paper proposes the following hypothesis.
Hypothesis 1.
Green public procurement promotes the improvement of corporate environmental performance.
Corporate management behavior is greatly influenced by the executive team (Bertrand & Schoar, 2003). Facing the pressure of
short-term performance evaluations, management may reduce investment in environmental governance activities for their own
short-term benefits, adopting short-sighted behaviors (Smulowitz et al., 2023).
Based on signaling theory, GPP send clear environmental signals, setting benchmarks for environmentally friendly products for
companies and consumers, which play a leading and demonstrative role in enhancing environmental awareness (Simcoe & Toffel,
2014), thus facilitating the change of the original governance concepts of enterprise management. For example, the Ministry of Finance
has corresponding environmental requirements for green data centers, green building materials, green commodity packaging, and
green courier packaging, accompanied by prescribed testing methods. These measures put clear requirements on suppliers’ green
production capacity and environmental performance. On the one hand, corporate management will feel the policy pressure and
changes in market demand, and then adjust their business strategies to focus more on the long-term benefits of improving environ-
mental performance. Policy pressure prompts management to recognize the potential long-term risks and losses of neglecting envi-
ronmental governance, thus placing greater emphasis on environmental investment in strategic decisions. On the other hand, the
specific bidding requirements of GPP make management more confident in the direction of low-carbon development, helping to
enhance their willingness to protect the environment. Clear policy requirements and testing standards provide professional guidance
for management, helping them formulate and implement green transition strategies, thereby improving corporate environmental
performance.
In addition, considering information about GPP is available throughout the whole process, enterprises that have been awarded
green procurement contracts will be closely watched by the media and investors, and their environmental behavior will be monitored
and paid attention to by external stakeholders. On the one hand, public and media attention, as a typical informal institutional tool,
will create a powerful public opinion effect. On the other hand, stakeholders are the primary source of resources for companies and
have a significant impact on corporate development decisions. Stakeholders place higher expectations on the performance of corporate
environmental responsibility, which creates a kind of pushback mechanism that prompts enterprises to be more proactive in meeting
the government’s environmental protection requirements in order to fulfill stakeholders’ expectations (Bertels & Peloza, 2008). Under
this pressure, corporate management will place greater importance on the opinions of shareholders, customers, employees, and the
public, considering environmental factors more in their decisions (Clarkson et al., 2008), thereby striving to improve corporate
environmental performance. Therefore, this paper proposes the following hypothesis.
Hypothesis 2.
GPP promotes corporate environmental performance through conceptual governance effects, especially by enhancing
management’s environmental protection concepts.
GPP, as an important tool of demand-side innovation policy, has great potential to drive corporate innovation in green technologies
(Krieger & Zipperer, 2022). On the one hand, GPP can reduce information asymmetry with potential suppliers in terms of innovation
needs by specifying bidding requirements (Krieger & Zipperer, 2022). For example, the dynamic adjustment of the procurement list
system for energy-saving products and environmentally labeled products in each period provides clear direction and prospect guidance
for green innovation, which helps to reduce the uncertainty of research and development.
On the other hand, given the large scale of public procurement, green procurement can be viewed as a mechanism to provide a
minimum market size for green products and in the process share the cost of research and development for low-carbon green products
(Czarnitzki et al., 2020). This approach lowers product prices, stimulating consumer demand for green products and subsequently
shifting market demand towards greener options. Simcoe and Toffel (2014) showed that the mandatory green building standards
imposed on public buildings in California have stimulated the demand for green buildings in the private sector. Thus, facing the
stimulation of green market demand, companies enhance their green innovation capabilities, thereby improving their technological
level (Bleda & Chicot, 2020). Through market mechanisms, the government drives companies towards green technological innovation,
especially in technology-intensive industries, where the government often acts as an early and key buyer (Orsatti et al., 2020).
As companies continuously improve their green technology levels, they can effectively enhance resource utilization efficiency and
reduce environmental damage, thereby improving their environmental performance. Thus, GPP will promote enterprises to enhance
their green technology innovation and achieve “source governance.” Therefore, this paper proposes the following hypothesis.
Hypothesis 3.
GPP promotes corporate environmental performance through source governance effects, specifically by enhancing
corporate green innovation capabilities.
Generally speaking, corporate pollution emissions depend on both the process of pollutant generation and the treatment of pol-
lutants. The adoption of advanced or pollution-free production technologies can significantly reduce the generation of pollutants,
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
4


## Page 5

which is determined by green technological innovation in the production chain mentioned earlier. The treatment of pollutants, on the
other hand, is reflected in the process by which enterprises treat and purify pollutants before they are released into the environment.
This requires enterprises to increase investment in pollution treatment equipment and carry out harmless treatment of pollutants at the
terminal. GPP not only strengthens the willingness of enterprises to treat at the terminal of the process but also provides various
resource support for expanding environmental investment.
Firstly, the government sets strict environmental standards in the green procurement process, forcing companies to make signif-
icant investments in environmental technologies, equipment, and management systems (Igarashi et al., 2015). For example, companies
need to adopt low-pollution, high-efficiency technologies, use renewable energy, and reduce waste emissions. To meet these green
standards, companies must make substantial environmental investments to reduce pollutant emissions and improve resource utili-
zation efficiency (Lundberg & Marklund, 2013). At the same time, by conveying clear environmental signals, GPP guides market
expectations in the direction of environmental protection, prompting firms to have the confidence to make larger investments in
environmentally friendly technologies and equipment to meet market demand (Kadefors et al., 2021).
Secondly, GPP orders can bring more resources to enterprises and alleviate their financing constraints. According to the resource
slack theory, the extent to which a company invests in social responsibility activities depends on the abundance of its resources
(Waddock & Graves, 1997). GPP usually features large scale and stable procurement quantities, and as the largest single purchaser in
the market, the government typically does not default or go bankrupt (Dhaliwal et al., 2016). This enables suppliers to maintain more
stable operating cash flow levels, alleviating financing constraints and providing companies with more resources for environmental
investments. In addition, obtaining a GPP order is equivalent to obtaining an invisible endorsement from the government, which can
bring more external resources, such as loans from financial institutions and financial support from investors, and further promote the
firm’s environmental investment and environmental performance improvement. Therefore, this paper proposes the following
hypotheses.
Hypothesis 4.
GPP promotes corporate environmental performance through terminal governance effects, specifically by increasing
corporate environmental protection investment.
Compared to corporate clients, government clients typically impose stricter regulations on suppliers (Cohen et al., 2022). On the
one hand, government customers will require suppliers to consciously accept financial, audit, and social supervision, which aims to
ensure that suppliers are able to fulfill their commitments, including having sufficient financial resources to deliver the goods and
services specified in the contract (Samuels, 2021). On the other hand, GPP policies strictly review whether companies can provide
environmentally compliant green products and use a series of supervision mechanisms to ensure that companies consistently meet
environmental standards during production (Ghisetti, 2017). Thus, GPP strengthens regulation, becoming an external driving force for
companies to improve environmental performance (Zhang et al., 2022).
For example, the “Implementation Guide for Policies Supporting Green Building Materials to Enhance Building Quality through
Government Procurement” issued in 2023 requires lifecycle regulation of green buildings and materials, including design review,
public procurement, project construction, and completion inspection, ensuring compliance with the “Green Building and Green
Building Materials Government Procurement Requirements Standard.” The notification requires that “when green building materials
are delivered, the supervision unit must verify a series of quality certification documents, including indicator certification.” This
regulation makes companies more transparent in environmental management and information disclosure, reducing the probability of
environmental violations and thus improving their environmental performance. Additionally, the “Implementation Guide” further
requires that “after green building materials are delivered, samples should be randomly re-inspected according to relevant con-
struction project acceptance standards.” This compliance requirement forces supplier firms to adopt more environmentally friendly
business practices to ensure that their products comply with the environmental standards of green procurement orders, thus improving
their overall environmental performance.
Hypothesis 5.
GPP promotes corporate environmental performance through supervision governance effects, specifically by
strengthening government oversight.
3. Data and methods
3.1. Sample selection and data sources
Considering that detailed public procurement contract information has been available in the China Government Procurement
Network since 2015, this paper selects A-share listed companies from 2015 to 2021 as the research sample. GPP data comes from the
China Government Procurement Network, corporate environmental performance data comes from the Huazheng ESG Rating Database
and CSMAR Database, and other firm-level data comes from the CSMAR Database and Wind Database. The original data were pro-
cessed as follows: (1) Excluding companies in the financial industry; (2) Excluding ST and *ST companies; (3) Excluding samples with
missing key variables; (4) Excluding companies with data for only one year. Finally, this paper obtains 22,257 firm-year observations.
To avoid the influence of extreme values, continuous variables were winsorized at the 1% level.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
5


## Page 6

3.2. Variable Definitions
3.2.1. Green public procurement
First, this paper scraped public procurement contract information from 2015 to 2021 from the China Government Procurement
Network, including contract name, project name, signing date, purchaser name, supplier name, contract amount, region, and more.
Next, this paper draws on the research approach of Krieger and Zipperer (2022) to construct a wordlist of “green procurement
contract”, successfully identifying green procurement contracts from public procurement contracts. This paper utilizes Python’s Jieba
lexical module to lexically separate the “item names” in the list of government energy-saving and environmentally labeled procure-
ment items, as well as the “product and service indexes” in the Statistical Classification of Energy-Saving and Environmentally Friendly
Clean Industries.1 Subsequently, this paper manually screens out the basic word list that is highly relevant to green procurement. In
order to further improve the wordlist, this paper screens out more policy documents related to green technology and low-carbon
environmental protection, such as the Green Technology Promotion Catalog, the Green Industry Guidance Catalog, the Patent Clas-
sification System for Green and Low-Carbon Technologies, and the Green Bonds Support Project Catalog. Using the Word2vec machine
learning method, the green procurement contract vocabulary was expanded, ultimately constructing a wordlist containing more than
300 green procurement-related terms such as “new energy buses”, “wastewater treatment”, “air pollution control”, and “coal--
to-electricity projects”. Finally, this paper filters public procurement contracts, and if the “contract name” or “project name” contains
any keywords in the wordlist, this paper defines it as a GPP contract.
Finally, this paper matched GPP contracts with listed companies. First, the “supplier name” in the GPP contracts was precisely
matched with the names of listed companies and their subsidiaries. For samples that could not be precisely matched, fuzzy matching
was performed. Given that certain phrases like “limited company,” “shares,” and “liability” do not aid in matching and may reduce the
efficiency and accuracy of fuzzy matching, these phrases were removed from the names of suppliers and listed companies. Based on
this, fuzzy matching was conducted, and the results were manually checked and summarized to count the number and amount of GPP
contracts obtained by listed companies each year. In the end, 816 listed companies were successfully matched with GPP contracts.
Fig. 1 shows the process of constructing Green Public Procurement.
In the benchmark regression, this paper uses the number of GPP contracts (gpp_n) obtained by listed companies in a certain year to
measure green public procurement, which is represented by the natural logarithm of the number of GPP contracts plus one. In the
robustness analysis, this paper further uses whether the company obtained a GPP contract (gpp_if) and the amount of GPP contracts
(gpp) for analysis. If the company obtained a GPP contract in a certain year, the gpp_if value is 1; otherwise, it is 0. This paper uses the
natural logarithm of the contract amount plus one to represent gpp.
3.2.2. Corporate environmental performance
To quantify corporate environmental performance, researchers currently primarily use data from a few official databases, such as
the KLD dataset, the EPI Index, and the Toxic Release Inventory (Clarkson et al., 2008; Walls et al., 2012). Regarding Chinese scholars,
the existing literature measures corporate environmental performance based on the following approaches: First, measuring through
single-dimensional indicators related to corporate environmental performance, such as whether a company has obtained environ-
mental certification or received environmental awards (King et al., 2005; Qi et al., 2012); second, using quantitative indicators such as
the pollution discharge fee rate on operating income, pollution discharge concentration, total pollution discharge, and environmental
capital expenditure as substitutes (Chang et al., 2015); third, evaluating corporate environmental performance through pollutant data
provided by third parties, with the current environmental performance indicators mostly sourced from major ESG databases (Xu &
Kim, 2022); fourth, measuring corporate environmental performance by quantitatively scoring the content disclosed in annual reports
and social responsibility reports (Lin et al., 2015; Zhang et al., 2023).
Considering, first, that single-dimensional indicators can hardly comprehensively measure corporate environmental performance,
as they only assess environmental achievements from one aspect; second, the available sample size for variables such as pollution
discharge concentration and total pollution discharge of listed companies is relatively small, with many missing values. Therefore, this
paper chooses to measure corporate environmental performance using both third-party environmental performance indicators and
quantitative scoring of the content disclosed by the companies themselves. Third-party rating agencies can usually conduct inde-
pendent and objective evaluations, reducing the “greenwashing” that may exist in corporate reports. The environmental performance
information disclosed by companies themselves is often more detailed and specific, reflecting the actual investment and achievements
in environmental protection. Combining these two data sources allows for a more scientific and systematic evaluation of corporate
environmental performance.
First, this paper uses environmental scoring data from the third-party HuazhengESG database to measure corporate environmental
performance. Currently, this rating has been widely used in both academia and industry, classifying corporate environmental per-
formance from low to high into nine levels: C, CC, CCC, B, BB, BBB, A, AA, and AAA, updated quarterly. In this paper, we refer to Lin
1 The selection of these three documents is primarily based on the following reasons: On one hand, the procurement list system for energy-saving
products and environmentally labeled products is a crucial tool in China’s GPP strategy, which mandates compulsory and preferential procurement
for products on the list. On the other hand, the “Statistical Classification of Energy-Saving and Environmentally Friendly Clean Industries” is
formulated under the guidance of policies aimed at promoting ecological civilization and green development. It is applicable across regions, de-
partments, and specialties for defining energy-saving, environmental protection, and clean industries in statistical monitoring and analysis.
Therefore, these documents can assist in better identifying green procurement contracts in this study..
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
6


## Page 7

et al. (2021), which assign corporate environmental scores from low to high as 1–9 and calculate the annual average, denoted as EnvP1.
Second, based on Zhang et al. (2023), this paper portrays corporate environmental performance in terms of specific scores for seven
refined variables: (1) having special environmental actions, scored 1 point; otherwise, 0 points; (2) receiving environmental honors or
awards, scored 1 point; otherwise, 0 points; (3) occurrence of environmental violations, scored −1 point; otherwise, 0 points; (4)
having an environmental management system, scored 1 point; otherwise, 0 points; (5) meeting pollutant discharge standards, scored 1
point; otherwise, 0 points; (6) disclosing environmental reports, scored 1 point; otherwise, 0 points; (7) disclosing social responsibility
reports, scored 1 point; otherwise, 0 points. The seven subdivided scores are summed up to get the total score of the enterprise for that
year, which is recorded as EnvP2.
3.2.3. Control variables
This paper selects the following control variables at the company level: firm size (size), measured by the natural logarithm of the
company’s total assets; firm age (age), measured by the number of years since the company’s establishment; return on assets (roa),
measured by the ratio of net profit to the average balance of total assets; leverage (lev), measured by the ratio of total liabilities to total
assets at the end of the year; growth capacity (tobinq), measured by the ratio of (market value of tradable shares + number of non-
tradable shares × net asset value per share + book value of liabilities) to total assets; book-to-market ratio (BM), measured by the
ratio of book value to total market value; proportion of independent directors (indep), measured by the ratio of independent directors to
the total number of directors.
3.3. Empirical model and descriptive statistics
To examine the impact of GPP on corporate environmental performance, this paper constructs the following two-way fixed effects
panel model:
EnvPi,t = β0 + β1gpp ni,t + θX + λf + λy + εi,t
(1)
where i represents firms, t represents years, EnvPi,t denotes corporate environmental performance, gpp ni,t denotes the number of green
public procurement orders, and θX represents a series of control variables affecting corporate environmental performance. In addition,
this paper controls for firm and year fixed effects and reports firm-level cluster robust standard errors in the regression.
Table 1 presents the descriptive statistics of the main variables. The minimum value of EnvP1 is 1 when the maximum value is 9,
Fig. 1. The process of constructing Green Public Procurement.
Table 1
Descriptive statistics.
(1)
(2)
(3)
(4)
(5)
N
mean
sd
Min
max
EnvP1
22,257
1.972
1.228
1
9
EnvP2
22,257
1.855
1.165
−1
6
gpp_n
22,257
0.0984
0.365
0
2.565
size
22,257
22.30
1.301
19.78
26.50
age
22,257
2.969
0.293
2.079
3.584
roa
22,257
0.0396
0.0721
−0.382
0.244
lev
22,257
0.418
0.202
0.0523
0.920
tobinq
22,257
2.144
1.522
0.799
16.65
BM
22,257
1.037
1.298
0.0514
11.04
indep
22,257
0.378
0.0540
0.308
0.600
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
7


## Page 8

and the standard deviation is 1.228, indicating considerable differences in environmental performance among different firms. The
mean value of EnvP1 is 1.972, reflecting the relatively low environmental performance level of Chinese firms, with considerable room
for improvement. The situation for the corporate environmental performance indicator EnvP2 is similar to that of EnvP1, indicating
that the two environmental performance indicators chosen in this paper can objectively and consistently reflect the environmental
management level of Chinese listed firms. Regarding the acquisition of GPP contracts by firms, the mean value of gpp_n is 0.0984, with
a standard deviation of 0.365, indicating significant differences among listed companies and their subsidiaries in obtaining GPP orders.
The descriptive statistics of other variables are also within reasonable ranges.
4. Empirical results
4.1. Benchmark regression
According to model (1), Table 2 reports the benchmark regression results of the impact of GPP orders on corporate environmental
performance. In this context, the dependent variables in columns (1) and (2) are the corporate environmental scores from the
HuazhengESG database (EnvP1), while the dependent variables in columns (3) and (4) are the corporate environmental performance
scores quantified from the content of corporate reports (EnvP2). Columns (1) and (3) control for firm fixed effects and time fixed effects
but do not consider the impact of control variables. The regression results show that the coefficients for gpp_n are 0.0849 and 0.0777,
respectively, which are significant at the 5% and 1% levels. This indicates that the number of GPP contracts obtained by firms is
significantly positively correlated with their environmental performance, suggesting that GPP encourage firms to improve their
environmental performance. Thus, Hypothesis 1 is preliminarily validated. Columns (2) and (4) further control for firm-level control
variables. The results show that even after considering other factors that may affect corporate environmental performance, the positive
effect of GPP on corporate environmental performance remains significant. Therefore, Hypothesis 1 is validated, demonstrating the
effectiveness of GPP as an environmental governance tool. Possible reasons are that GPP can promote corporate environmental
performance through conceptual governance effects, source governance effects, terminal governance effects, and supervision gover-
nance effects. The specific mechanisms will be examined in the subsequent analysis.
4.2. Robustness checks
4.2.1. Alternative measure of key variables
In the benchmark regression, this paper uses the natural logarithm of the number of GPP contracts obtained by listed companies
plus 1 (gpp_n) to measure the explanatory variable of GPP. This paper further uses the amount of GPP contracts (gpp) and whether a
company obtained GPP contracts (gpp_if) for robustness checks. Among these, gpp_if is a dummy variable where if a company obtained
GPP contracts in a certain year, it is assigned a value of 1; otherwise, it is 0. The regression results are shown in columns (1) and (2) of
Table 3; gpp is measured by the natural logarithm of the contract amount plus 1. The regression results are shown in columns (3) and
(4) of Table 3. The regression results show that the coefficients for gpp_if and gpp are significantly positive at least at the 5% level,
Table 2
Basic regression results.
(1)
(2)
(3)
(4)
EnvP1
EnvP1
EnvP2
EnvP2
gpp_n
0.0849**
0.0829**
0.0777***
0.0637***
(0.034)
(0.035)
(0.024)
(0.024)
size
0.0659**
0.3032***
(0.026)
(0.024)
age
0.2141
0.2044
(0.246)
(0.224)
roa
0.0161
−0.0939
(0.107)
(0.092)
lev
−0.2020***
−0.1527**
(0.077)
(0.070)
tobinq
−0.0017
0.0436***
(0.007)
(0.006)
BM
−0.0210*
−0.0407***
(0.011)
(0.012)
indep
−0.1659
0.1756
(0.184)
(0.176)
Constant
1.9636***
0.0304
1.8473***
−5.5697***
(0.003)
(0.876)
(0.002)
(0.835)
Firm FE
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
Observations
22,257
22,257
22,257
22,257
R-squared
0.7397
0.7401
0.7239
0.7291
Note: Robust standard errors are shown in parentheses, * represents p < 0.10, ** represents p < 0.05, and *** represents p < 0.01, the same below.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
8


## Page 9

indicating that regardless of the measurement method for the independent variable, the main conclusions remain unchanged.
In the baseline regression, this paper uses both environmental performance indicators provided by third-party institutions and
quantitative scoring of the content disclosed by companies themselves to measure corporate environmental performance. Considering
that there may be discrepancies in the ratings between different databases, this paper further uses environmental score data provided
by the Bloomberg database to measure the dependent variable of corporate environmental performance in the robustness check,
denoted as EnvP_Bloomb. The regression results, as shown in column (5) of Table 3, indicate that the coefficient for gpp_n remains
significantly positive at the 5% level, suggesting that the main conclusions remain unchanged.
4.2.2. Distinguishing green and non-green procurement
To ensure that the estimated results in this paper are driven by green public procurement rather than general public procurement,
this paper adjusts the baseline estimates. Specifically, this paper divides all public procurement orders obtained by listed companies
into green procurement contracts (gpp) and non-green procurement contracts (gp). If a company has obtained green procurement
contracts, gpp is assigned a value of 1; otherwise, it is 0. If a company has only obtained non-green procurement contracts, gp is assigned
a value of 1; otherwise, it is 0. After considering the impact of control variables and controlling for firm fixed effects and time fixed
effects, the regression results in columns (2) and (4) of Table 4 show that the coefficients for gpp are 0.0723 and 0.0711, respectively,
and are significant at least at the 5% level. This indicates that obtaining green procurement contracts significantly improves the
environmental performance of firms. In contrast, the coefficients for gp, although positive, are not significant. Compared to general
public procurement contracts, green procurement imposes higher environmental requirements on firms, effectively promoting their
investment in environmental protection and improvement in environmental performance. These findings emphasize the necessity and
importance of identifying green procurement contracts within public procurement contracts.
4.2.3. Adjustment of sample
First, we exclude the corporate samples from 2020. Considering that the COVID-19 pandemic in 2020 caused unprecedented
economic fluctuations globally, many companies faced production stoppages, logistics disruptions, and raw material shortages, which
could lead to abnormal behaviors in environmental investment and performance. Therefore, excluding the samples from 2020 for
regression can avoid the interference of special events and short-term fluctuations. The regression results are shown in columns (1) and
(2) of Table 5.
Second, we exclude samples from politically connected firms. Politically connected firms may enjoy special treatment in the policy
implementation process. For example, these firms may be more likely to obtain public procurement contracts, and they also have more
advantages in resource acquisition and financing. Thus, excluding these samples helps to more accurately assess the environmental
incentive effects of GPP. Specifically, if the chairman or general manager of a company has ever or currently held a position in the
central or local governments, courts, or procuratorates, the sample is considered politically connected. The results are shown in
columns (3) and (4) of Table 5.
Third, we exclude samples from firms with environmental certifications. Considering that GPP typically involves specific envi-
ronmental standards and technical requirements, companies with environmental certifications are more likely to obtain GPP contracts.
The results are shown in columns (5) and (6) of Table 5.
According to the regression results in Table 5, the coefficients of gpp_n remain significantly positive, indicating that even after
excluding some special samples, obtaining GPP contracts still significantly incentivizes firms to improve their environmental per-
formance. Therefore, the benchmark regression results of this paper are robust and reliable.
4.3. Endogeneity issues
The results of the benchmark regression may suffer from endogeneity problems caused by reverse causation and the omission of
Table 3
Robustness checks: Alternative measure of key variable.
(1)
(2)
(3)
(4)
(5)
EnvP1
EnvP2
EnvP1
EnvP2
EnvP_Bloomb
gpp_if
0.0644**
0.0652**
(0.032)
(0.025)
gpp
0.0133**
0.0098**
(0.006)
(0.004)
gpp_n
1.1369**
(0.529)
Constant
−0.0424
−5.6178***
−0.0145
−5.6061***
−96.6884***
(0.878)
(0.835)
(0.878)
(0.835)
(23.649)
Controls
YES
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
YES
Observations
22,257
22,257
22,257
22,257
6077
R-squared
0.7400
0.7291
0.7400
0.7291
0.7793
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
9


## Page 10

some important variables. On the one hand, GPP can enhance corporate environmental performance through conceptual governance
effects, source governance effects, terminal governance effects, and supervision governance effects. On the other hand, when enter-
prises have a better level of environmental performance, they tend to be more capable of providing products and services that satisfy
the green procurement standards, providing themselves with a competitive advantage in GPP, and thus are more likely to obtain GPP
orders. Therefore, this paper attempts to use instrumental variable methods and the staggered Difference-in-Differences method to
mitigate potential reverse causality issues. To address endogeneity issues arising from omitted important variables, this paper in-
troduces high-dimensional fixed effects. Additionally, to deal with potential sample selection bias in the model, this paper further
employs the Heckman two-stage estimation method.
4.3.1. Instrumental variable method
Referring to the method of Fisman and Svensson (2007), this paper uses the average number of GPP contracts in the same region
and industry (gpp_n_IV) as an instrumental variable for the number of GPP contracts (gpp_n) and estimates using two-stage least squares.
The rationale for choosing this indicator is that, on the one hand, the number of GPP contracts in the same region and industry is highly
correlated with the number of GPP contracts obtained by a single firm; on the other hand, the number of GPP contracts in the same
region and industry is unlikely to directly affect a firm’s environmental performance. Thus, the instrumental variable constructed in
this paper meets the requirements of relevance and exogeneity. The regression results for the instrumental variable are shown in
Table 6.
The first-stage regression results show that gpp_n_IV is significantly positively correlated with gpp_n at the 1% level, which is
consistent with expectations. Additionally, the Anderson canon. corr. LM and Cragg-Donald Wald F statistics are well above the critical
values, which indicates that the selected instrumental variable does not suffer from under-identification or weak instrument problems.
The second-stage regression results in columns (2) and (3) show that the regression coefficient of gpp_n remains significantly positive,
regardless of whether the dependent variable is EnvP1 or EnvP2. Therefore, the baseline conclusions of this paper still hold.
4.3.2. Staggered differences-in-differences
This paper will further address potential endogeneity issues by constructing a staggered DID model. The procurement list system for
energy-saving products and environmentally labeled products is a key approach in China’s GPP strategy. Products that meet the
technical requirements for energy conservation and environmental protection and are certified by authoritative institutions can be
included in the priority and mandatory procurement lists. From 2004 to 2018, the Ministry of Finance issued 24 catalogs of energy-
saving products procurement lists and 22 catalogs for environmental label products. This study will use the establishment of the
energy-saving and environmentally labeled product procurement list system as a quasi-natural experiment, analyzing the impact of
GPP policies on corporate environmental performance by examining the differences in corporate pollution intensity before and after
Table 4
Robustness checks: Distinguishing green and non-green procurement.
(1)
(2)
(3)
(4)
EnvP1
EnvP1
EnvP2
EnvP2
gpp
0.0757**
0.0723**
0.0906***
0.0711***
(0.034)
(0.034)
(0.028)
(0.027)
gp
0.0217
0.0194
0.0250
0.0146
(0.027)
(0.027)
(0.023)
(0.023)
Constant
1.9638***
−0.0379
1.8453***
−5.6144***
(0.004)
(0.878)
(0.004)
(0.835)
Controls
NO
YES
NO
YES
Firm FE
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
Observations
22,257
22,257
22,257
22,257
R-squared
0.7396
0.7400
0.7239
0.7291
Table 5
Robustness checks: Adjustment of sample.
(1)
(2)
(3)
(4)
(5)
(6)
EnvP1
EnvP2
EnvP1
EnvP2
EnvP1
EnvP2
gpp_n
0.0775**
0.0823***
0.0755*
0.0614**
0.1331***
0.0631**
(0.036)
(0.027)
(0.041)
(0.027)
(0.036)
(0.026)
Constant
−0.0380
−5.5910***
0.6282
−5.7827***
−0.4521
−3.7810***
(0.848)
(0.882)
(1.011)
(0.985)
(0.945)
(0.817)
Controls
YES
YES
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
YES
YES
Observations
18,173
18,173
16,264
16,264
16,388
16,388
R-squared
0.7393
0.7370
0.7460
0.7352
0.7447
0.7320
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
10


## Page 11

the release of these lists.
Due to the large number of missing values in data such as pollutant concentration and total pollutant discharge of listed companies,
in order to more intuitively reflect the environmental pollution situation of enterprises, this section will use data samples from the
Chinese Industrial Enterprise Database and Chinese Industrial Enterprise Pollution Database from 1998 to 2012 to more accurately
estimate the effectiveness of GPP in corporate environmental governance. The datasets were merged through repeated cross-matching
of enterprise organization codes and company names, and subsequently we processed the merged samples.2 Considering that industrial
SO2 is the main pollutant emission of enterprises (Antweiler et al., 2001), this article uses the proportion of SO2 emissions to the total
industrial output value as a proxy variable for the intensity of enterprise pollution emissions (Polint).
The core explanatory variable of this section, namely the identification of GPP policies, is mainly divided into the following three
steps: firstly, this article collects all the “Government Procurement List of Environmental Labeling Products” and “Government Pro-
curement List of Energy-saving Products” published from the Chinese Government Procurement Network between 2004 and 20123;
secondly, this paper identifies the industry mid-category codes corresponding to all the product items involved in the procurement
lists4; finally, this paper utilizes the industry mid-category codes belonging to each firm in the industrial enterprise database to
determine whether the firms are affected by the list system. Specifically, the experimental and control groups were divided according
to the criterion of “whether the industry to which the enterprise belongs is within the industry covered by the goods on the pro-
curement list”, that is, whether the industry to which the enterprise belongs is affected by the list system, and the year when the
industry to which the enterprise belongs first appears in the product items on the procurement list is taken as the time when the
enterprise is affected by the policy.
The control variables selected in this section include: firm size (size), measured by the natural logarithm of the company’s total
assets; leverage (lev), measured by the ratio of total liabilities to total assets; firm age (age), measured by the number of years since the
company’s establishment; scale of enterprise employees (labor), measured by the natural logarithm of all employees in the company;
state-owned enterprises (soe), defined as enterprises in which state-owned holding enterprises or collective capital accounts for 50% or
more of the paid up capital, with SOE = 1; otherwise, SOE = 0; export enterprise dummy variable (export), when the export delivery
value of the enterprise is greater than 0, export = 1; otherwise, export = 0.
Finally, this article constructs a staggered DID model to examine the impact of the establishment of the energy-saving and envi-
ronmentally labeled product procurement list system on the pollution emission intensity of enterprises, as shown in equation (2):
Polinti,t = β0 + β1didi,t + θX + λf + λy + εi,t
(2)
Table 6
Endogeneity issues: Instrumental variable method.
(1)
(2)
(3)
first-stage
second-stage
second-stage
gpp_n
EnvP1
EnvP1
gpp_n_IV
0.9542***
(0.020)
gpp_n
0.0598*
0.0998***
(0.033)
(0.032)
Controls
YES
YES
YES
Firm FE
YES
YES
YES
Year FE
YES
YES
YES
Observations
22,257
22,257
22,257
R-squared
0.0535
0.0763
Anderson canon. corr. LM
7992.426***
Cragg-Donald Wald F
14138***
2 This paper excludes the following samples: (1) samples with missing key indicators such as sales, number of employees, total assets, and net
fixed assets; (2) firms with fewer than 8 employees; (3) firms with total assets less than current assets, total assets less than net fixed assets, or
cumulative depreciation less than current depreciation; (4) firms with sales less than 5 million yuan; and (5) the business status of the enterprise is
“revoked,” “closed,” or other abnormal operating statuses. It should be noted that, considering that the data of industrial enterprises in 2010 may
have serious data quality problems, this paper excludes the sample of that year from the empirical test.
3 For the procurement list released in the first half of the year, this article considers the year of the list release as the policy implementation time;
for the procurement list released in the second half of the year, this article considers the year after the release of the list as the policy implementation
time.
4 This study extracts the product categories from each procurement list and sequentially searches for these category names in the “Classification
and Codes of National Economic Industries,” revised in 2002. By combining the detailed explanations of industry subcategories in the classification
code, this study identifies the corresponding industry middle category codes for each product category. For product categories that cannot be
directly retrieved from the “Classification and Codes of National Economic Industries,” this study retrieves the names of companies listed under
those product categories in the procurement lists, searches the Industrial Enterprise Database, and obtains the middle category codes for the in-
dustries to which these companies belong. Consequently, this study compiles a list of the middle category codes for all product categories involved in
the energy-saving and environmentally labeled product procurement lists from 2004 to 2012.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
11


## Page 12

where i represents firms, t represents years, and didi,t is the key explanatory variable. Specifically, didi,t indicates whether the i-th firm is
affected by the procurement list system in the t-th year. If the industry to which the i-th firm belongs in the t-th year is covered by the
industries involved in the procurement list, then didi,t is assigned a value of 1 starting from the t-th year; otherwise, it is assigned a value
of 0. Polinti,t is the key dependent variable, representing the pollution intensity of the enterprise. Additionally, θX represents a series of
control variables. This paper controls for firm and year fixed effects and reports firm-level cluster robust standard errors in the
regression. The specific regression results are presented in Table 7.
Table 7 reports the impact of the establishment of the procurement list system on the SO2 emission intensity (Polint). Column (1)
does not consider the effects of control variables and fixed effects, while column (2) includes firm-level control variables on this basis,
and column (3) further controls for firm fixed effects and time fixed effects. According to Table 7, the regression coefficients of GPP
policy (didi,t) are significantly negative at the 1% level, indicating that the implementation of the procurement list system reduces the
pollution intensity of enterprises. On average, compared to enterprises not affected by the procurement list system, enterprises affected
by this system have reduced their SO2 emission intensity by 0.0704 units. This indicates that the procurement list system incentivizes
enterprises to take emission reduction measures to be included in the green procurement list. Therefore, after mitigating potential
endogeneity issues, the benchmark regression conclusion of this article still holds, that is, GPP encourages enterprises to improve their
environmental performance.
4.3.3. Heckman two-stage estimation
To address potential sample selection bias in the model, this paper further employs the Heckman two-stage estimation method. In
the first stage, we use the Logit model to estimate whether firms obtain GPP contracts as the dependent variable, which in turn yields
the inverse Mills ratio (IMR). In the second-stage regression, the explanatory and control variables are kept consistent with the baseline
regression model, while the calculated inverse Mills ratio (IMR) is added. The corresponding results are presented in columns (1) and
(2) of Table 8. The results show that the coefficient of gpp_n remains significantly positive after accounting for the sample self-selection
problem, verifying the robustness of the benchmark regression results.
4.3.4. High-dimensional fixed effect
In the benchmark regression, this paper has controlled for most representative variables that could potentially affect corporate
environmental performance and has also controlled for firm and time fixed effects. However, in order to exclude the impact of time-
varying unobservable factors at the regional and industry levels on corporate environmental performance, this paper further in-
troduces high-dimensional fixed effects to control for factors such as industry shocks and macro policy shocks that may be omitted from
the benchmark regression (1). Specifically, in the regression analyses in columns (3) and (5), this paper further introduces province-
year fixed effects. On this basis, the regression analyses in columns (4) and (6) further control for industry-year fixed effects. As can be
seen from the regression results in Table 8, the coefficients of gpp_n are significantly positive. This indicates that GPP can indeed
effectively promote the improvement of corporate environmental performance, further supporting the conclusions obtained earlier.
5. Mechanism test and heterogeneity analysis
5.1. Mechanism test
The benchmark regression results indicate that GPP can effectively promote corporate environmental performance. Based on the
previous theories and research hypotheses, this paper argues that the environmental governance role of GPP policy is mainly realized
through conceptual governance effect, source governance effect, terminal governance effect, and supervision governance effect. In the
following, this paper will further test these four mechanisms.
5.1.1. Conceptual governance effect
By conveying clear environmental signals and setting stringent environmental standards, GPP policy has prompted corporate
management to pay more attention to the long-term benefits of improved environmental performance, which will help to change
Table 7
Endogeneity issues: Staggered differences-in-differences.
(1)
(2)
(3)
Polint
Polint
Polint
did
−0.9941***
−0.9048***
−0.0704***
(0.015)
(0.014)
(0.024)
Constant
−1.1988***
2.1335***
2.3006***
(0.004)
(0.029)
(0.096)
Controls
NO
YES
YES
Firm FE
NO
NO
YES
Year FE
NO
NO
YES
Observations
334,615
334,615
334,615
R-squared
0.0136
0.1053
0.8611
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
12


## Page 13

traditional governance concepts. In addition, specific green standards and technical specifications enhance management’s confidence
in the direction of low-carbon and market prospects. As a result, management will consider environmental factors more in their
decision-making and actively promote environmental protection measures to improve the overall environmental performance of the
enterprise.
Referring to the ideas of related literature (Brown et al., 2017; Huang et al., 2024), this paper adopts the text analysis method to
analyze the frequency of terms related to “environmental protection” in the Management Discussion and Analysis (MD&A) section of
the annual reports of listed enterprises, which is used to measure the degree of management’s environmental protection awareness.
The higher the frequency of environmental terms in the MD&A, the greater the management team’s investment and focus on envi-
ronmental issues, indicating that management places more importance on environmental decisions. Specifically, this paper measures
management’s environmental awareness by taking the natural logarithm of the total frequency of environmental terms plus one,
denoted as lnenvir. Further, the paper also uses the ratio of the number of environmental terms to the total number of terms, denoted as
envir_total.
Columns (1) and (2) of Table 9 show the impact of GPP contracts on the environmental awareness of corporate management, with
the dependent variables being lnenvir and envir_total, respectively. The results show that the coefficients of gpp_n are 0.0227 and
0.0035, respectively, both significantly positive at the 10% level. The above results indicate that GPP significantly enhance the
environmental awareness of corporate management, thereby promoting corporate environmental performance. Therefore, Hypothesis
2 of this paper, the conceptual governance effect of GPP, is validated.
5.1.2. Source governance effect
GPP effectively reduce information asymmetry with potential suppliers on innovation needs through detailed bidding re-
quirements. At the same time, the large scale of public procurement can provide the minimum market demand for green products,
thereby sharing the R&D costs of green products. Through this market mechanism, GPP guide companies towards green technological
innovation, improve resource utilization efficiency, and reduce environmental damage, thereby significantly enhancing corporate
environmental performance.
This paper uses the total number of green patent applications (lngre_apl) to measure the quantity of corporate green innovation and
the total number of green invention patent applications (lngreinv_apl) to assess the quality of corporate green innovation. The total
number of green patent applications includes the total applications for green invention patents and green utility model patents. To
eliminate the right-skewed distribution problem of patent application data, this paper takes the natural logarithm of the number of
patent applications after adding 1.
Column (3) of Table 9 reports the impact of GPP contracts on the number of corporate green patent applications, with the coef-
ficient of gpp_n being 0.0808, significantly positive at the 1% level. Column (4) of Table 9 reports the impact of GPP contracts on the
Table 8
Endogeneity issues: Heckman two-stage estimation and high-dimensional fixed effect.
(1)
(2)
(3)
(4)
(5)
(6)
EnvP1
EnvP2
EnvP1
EnvP1
EnvP2
EnvP2
gpp_n
0.0832**
0.0623***
0.0797**
0.0692**
0.0717***
0.0714***
(0.035)
(0.024)
(0.034)
(0.034)
(0.024)
(0.024)
Constant
0.9584
−5.8099***
−0.0066
0.9397
−5.4832***
−5.1820***
(1.027)
(0.883)
(0.900)
(0.929)
(0.849)
(0.885)
Observations
22,052
22,052
22,257
22,257
22,257
22,257
R-squared
0.7399
0.7294
0.7430
0.7479
0.7329
0.7352
Controls
YES
YES
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
YES
YES
Year FE
YES
YES
NO
NO
NO
NO
Year#Province FE
NO
NO
YES
YES
YES
YES
Year#Industry FE
NO
NO
NO
YES
NO
YES
Table 9
Mechanism test: Conceptual governance effect and source governance effect.
(1)
(2)
(3)
(4)
lnenvir
envir_total
lngre_apl
lngreinv_apl
gpp_n
0.0227*
0.0035*
0.0808***
0.0880***
(0.012)
(0.002)
(0.022)
(0.022)
Constant
1.9846***
0.6187***
−8.8653***
−6.7846***
(0.320)
(0.060)
(0.618)
(0.587)
Controls
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
Observations
22,042
22,042
22,257
22,257
R-squared
0.7588
0.7794
0.8068
0.7922
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
13


## Page 14

total number of green invention patent applications, with the coefficient of gpp_n being 0.0880, significantly positive at the 1% level.
The above results indicate that GPP policy significantly promote corporate green innovation, not only increasing the quantity of green
technological innovations but also enhancing the quality of green innovations. Therefore, Hypothesis 3 of this paper, the source
governance effect of GPP, is validated. In other words, GPP, through clear environmental requirements and market orientation,
stimulate corporate investment and development in green technology, ultimately achieving improved resource utilization efficiency
and enhanced environmental performance.
5.1.3. Terminal governance effect
By setting strict environmental standards in green procurement, the government forces enterprises to invest heavily in environ-
mental technology. By conveying clear environmental signals, the government guides them to further increase their environmental
investment. Additionally, the large scale of GPP can alleviate companies’ financing constraints, providing them with more resources
for environmental investments, thereby enhancing their environmental performance.
Referring to Li and Lu (2016), this paper uses the expenditure data related to environmental protection in the
construction-in-progress accounts from listed companies’ annual reports. These expenditures are aggregated to calculate the com-
pany’s annual environmental investment, which is then standardized by the company’s operating revenue (envir_cost). Considering
data comparability, this paper uses the ratio of the green procurement contract amount to operating revenue (gpp_sales) as the
explanatory variable.
Column (1) of Table 10 shows the impact of GPP on corporate environmental investment, with the coefficient of gpp_sales being
0.0355, significantly positive at the 5% level. This indicates that GPP significantly drive the growth of corporate investments in
environmental technology, thereby validating Hypothesis 4 of this paper, which states that GPP has a significant terminal governance
effect.
5.1.4. Supervision governance effect
GPP policy not only requires enterprises to provide green products that meet specific environmental standards and performance
requirements, but also ensures compliance with environmental regulations through regular inspections and assessments and imposes
penalties on enterprises that do not meet the standards. Therefore, companies awarded GPP contracts face more frequent and stringent
supervision. This supervision mechanism encourages companies to increase investments in environmental technology and equipment,
continuously improve environmental measures, and enhance the level of environmental information disclosure, thereby improving
their environmental performance.
The theory of public regulation suggests that, given regulatory resources and regulatory attention, the geographic distance between
firms and regulated institutions becomes an important factor affecting the cost of regulation as well as the intensity of regulatory
attention. That is to say, the closer the geographical distance, the stricter the regulatory measures. Thus, this paper argues that,
compared to non-local and central governments, local governments have closer supervisory proximity to listed companies and stronger
oversight capabilities. Additionally, local governments have greater authority and direct influence over the allocation of resources and
administrative approvals for companies. Therefore, obtaining local GPP contracts means that companies will face stricter government
supervision. If the governance effect of government supervision indeed exists, then local GPP contracts will have a more significant
impact on improving corporate environmental performance.
Table 10
Mechanism test: Terminal governance effect and supervision governance effect.
(1)
(2)
(3)
(4)
envir_cost
EnvP1
EnvP1
EnvP1
gpp_sales
0.0355**
(0.018)
gpp_s1
0.0122***
(0.004)
gpp_d1
0.0024
(0.006)
gpp_s2
0.0113***
(0.004)
gpp_d2
0.0027
(0.007)
gpp_c
−0.0095
(0.007)
gpp_l
0.0102**
(0.004)
Constant
−1.2734***
−0.0444
−0.0335
−0.0338
(0.419)
(0.875)
(0.875)
(0.876)
Controls
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
Observations
20,042
22,257
22,257
22,257
R-squared
0.6285
0.7401
0.7401
0.7401
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
14


## Page 15

Thus, this paper differentiates the GPP orders obtained by listed companies into local contracts and non-local contracts, as well as
local contracts and central contracts. Specifically, first, based on whether the procuring entity and the company’s registered address
are in the same province, each GPP contract is identified as either a local contract (gpp_s1) or a non-local contract (gpp_d1). Second,
considering that some listed companies participate in public procurement bidding through their subsidiaries, this paper further
identifies each GPP contract as either a local contract (gpp_s2) or a non-local contract (gpp_d2) based on whether the procuring entity
and the subsidiary’s registered address are in the same province. Finally, through the identification of the procuring entity’s name,
each GPP contract is classified as either a central contract (gpp_c) or a local contract (gpp_l). The regression results in columns (2) to (4)
of Table 10 show that, compared to non-local contracts and central contracts, the positive impact of GPP policies on corporate
environmental performance mainly comes from local green contracts, and this effect is significant at least at the 5% level. Therefore,
Hypothesis 5 of this paper, which posits the supervision governance effect of GPP, is validated.
5.2. Heterogeneity analysis
In order to provide more targeted recommendations for policy formulation, this paper will further analyze the heterogeneous
impact of GPP on corporate environmental performance based on the characteristics of enterprise attributes and the region to which
the enterprise belongs.
5.2.1. Firm scale
Small and large enterprises exhibit significant differences in resources, capabilities, and strategies, so GPP may have varying
impacts on their environmental performance incentives and behaviors. This paper divides the sample into large enterprises and small
and medium-sized enterprises (SMEs) for subsample regression to examine the differences in the impact of GPP on corporate envi-
ronmental performance across different firm sizes. Specifically, if a company’s revenue exceeds the median revenue of its industry in a
given year, it is classified as a large enterprise (SIZE = 1); otherwise, it is classified as an SME (SIZE = 0).
The regression results are shown in Table 11, with column (1) presenting the results for large enterprises and column (2) for SMEs.
The results indicate that GPP orders significantly promote the environmental performance of SMEs, with significance at the 5% level.
Although GPP orders also have a positive effect on large enterprises, the effect is not significant, and the difference in coefficients
between the two groups is statistically significant. It suggests that GPP has a more significant incentivizing effect on SMEs’ envi-
ronmental performance. This aligns with China’s current emphasis on a fair and just public procurement environment to support the
healthy development of SMEs. The “Measures for the Administration of Government Procurement to Promote the Development of
SMEs” issued in 2020 explicitly stated that the share of SMEs in public procurement should be increased to support their compre-
hensive development. Against this backdrop, GPP can set mandatory provisions requiring bidding agencies to include a certain number
of SMEs in procurement projects to enhance policy fairness and encourage broader SME participation in market competition. Addi-
tionally, the environmental requirements explicitly stated in GPP create market competition pressure for SMEs. In order to obtain
orders and remain competitive, SMEs must improve their environmental performance. This pressure prompts SMEs to make more
environmental investments and technology upgrades to comply with the government’s environmental standards. In contrast, large
enterprises may already have strong environmental capabilities and market positions, and the incentive effect of GPP on them is
relatively small.
5.2.2. Firm ownership structure
Under China’s special institutional background, there are significant differences between state-owned enterprises (SOEs) and non-
state-owned enterprises (non-SOEs) in terms of governance structure, policy dependence, motivation for environmental responsibility,
and ability to acquire resources, which potentially leads to varying effects of GPP on environmental governance across enterprises with
different ownership attributes. Therefore, this study divides the sample into SOEs (SOE = 1) and non-SOEs (SOE = 0) based on
Table 11
Heterogeneity Analysis: Based on enterprise characteristics.
(1)
(2)
(3)
(4)
(5)
(6)
SIZE = 1
SIZE = 0
SOE = 1
SOE = 0
HPE = 1
HPE = 0
EnvP1
EnvP1
EnvP1
EnvP1
EnvP1
EnvP1
gpp_n
0.0376
0.1297**
0.0226
0.1184**
0.2624**
0.0654*
(0.043)
(0.053)
(0.046)
(0.050)
(0.133)
(0.036)
Constant
−2.9762*
3.4222***
−4.6152***
1.6207
0.5486
−0.1517
(1.561)
(1.076)
(1.781)
(1.046)
(1.873)
(1.015)
Controls
YES
YES
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
YES
YES
Observations
10,893
10,920
6752
15,432
6220
15,952
R-squared
0.7499
0.7436
0.7462
0.7426
0.7362
0.7461
Empirical p-value
0.009***
0.000***
0.000***
Note: The empirical p-value is used to test the significance of the difference in the ggp_n between the groups, which is obtained by Bootstrap self-
sampling 1000 times, as follows.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
15


## Page 16

ownership attributes.
The regression results are shown in Table 11, with column (3) presenting the results for SOEs and column (4) for non-SOEs. The
results indicate that GPP significantly positively impacts the environmental performance of non-SOEs at the 5% level, whereas the
effect on SOEs is not significant. This suggests that GPP have a more positive and direct impact on non-SOEs during implementation.
The reason for this difference may be that non-SOEs rely more on market and policy support for resource acquisition, and GPP orders
can provide them with more resources and market opportunities. At the same time, when facing market competition, non-SOEs may
improve their environmental performance as part of their competitive advantage and are therefore more willing to respond to GPP
policy and thus improve their environmental performance. SOEs, on the other hand, may have a relatively monopolistic position in the
market and, due to their special governance structure, may be subject to more administrative interventions, resulting in a relatively
small incentive effect of GPP orders.
5.2.3. Heavy-polluting firms and non-heavilly-polluting firms
Heavy-polluting firms are the main sources of various waste and pollutants. In the context of increasing social environmental
awareness, these enterprises not only face stricter government regulations but also bear higher reputational risks and the main re-
sponsibility for environmental governance. GPP forces heavy-polluting enterprises to improve their environmental performance under
contractual obligations by setting strict environmental standards. Moreover, enterprises that obtain green procurement orders will
receive more social and market attention. To avoid public criticism and negative reactions from the capital market, heavy-polluting
enterprises, compared to non-heavily polluting ones, are more motivated to increase environmental investments and promote
green transformation of production processes, thereby reducing pollutant emissions. In this study, the sample is divided into heavy-
polluting enterprises (HPE = 1) and non-heavily polluting enterprises (HPE = 0) based on the 14 polluting industries specified in
the “Classification Management List of Environmental Verification for Listed Companies” published by the Ministry of Environmental
Protection in 2008.
The regression results are shown in Table 11, where column (5) represents the regression results of heavy-polluting firms and
column (6) represents the regression results of non-heavily polluting firms. The results indicate that although GPP has significantly
promoted the environmental performance of both heavy-polluting and non-heavily polluting firms, comparing the magnitude and
significance of gpp_n reveals that GPP has a greater impact on the environmental performance of heavily polluting enterprises.
Moreover, the difference between the coefficients of the two groups is statistically significant. Compared to non-heavily polluting
firms, heavy-polluting enterprises, when faced with stringent environmental standards and regulatory requirements, need to take more
measures to reduce pollutant emissions in order to meet the requirements of green procurement contracts and remain competitive in
the market. As a result, they are likely to be more significantly impacted by the GPP policy.
5.2.4. Governmental environmental attention
Due to varying levels of governmental attention to environmental issues across different regions, the impact of GPP on corporate
environmental performance also differs. This study constructs a governmental environmental attention index based on the frequency
of terms related to environmental protection in prefectural government work reports. The sample is divided into two groups based on
the median level of governmental environmental attention in the regions where the enterprises are located: high governmental
environmental attention (Attention = 1) and low governmental environmental attention (Attention = 0), for grouped regression
analysis.
The regression results are shown in Table 12, with column (1) presenting results for enterprises in regions with high governmental
environmental attention, and column (2) for those in regions with low attention. The results indicate that GPP significantly positively
impact corporate environmental performance only in regions with high governmental environmental attention. This may be because
governments in regions with high environmental attention typically implement more environmental policies and incentives. These
policies may include tax incentives, financial subsidies, green technical support, and more, which help firms obtain more resources and
support in the green procurement process, and thus enhance their environmental performance more positively. Additionally, in regions
with high environmental attention, the public and market have a stronger awareness of environmental protection and pay more
Table 12
Heterogeneity Analysis: Based on regional characteristics.
(1)
(2)
(3)
(4)
(5)
Attention = 1
Attention = 0
EEI = 1
EEI = 2
EEI = 3
EnvP1
EnvP1
EnvP1
EnvP1
EnvP1
gpp_n
0.1623***
−0.0093
0.0216
0.1589***
0.0352
(0.047)
(0.047)
(0.062)
(0.057)
(0.069)
Constant
−0.7409
0.9245
−2.0297
−0.4915
0.9087
(1.262)
(1.193)
(1.504)
(1.801)
(1.644)
Controls
YES
YES
YES
YES
YES
Firm FE
YES
YES
YES
YES
YES
Year FE
YES
YES
YES
YES
YES
Observations
10,762
10,317
7534
7156
6535
R-squared
0.7601
0.7717
0.7698
0.7949
0.7836
Empirical p-value
0.000***
0.003***
0.009***
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
16


## Page 17

attention to corporate environmental behavior. In this context, enterprises that actively respond to GPP can gain governmental support
and public and market recognition, making them more willing to improve their environmental performance. Therefore, only in regions
with strong environmental regulation do GPP policies send stronger market signals, more effectively encouraging enterprises to un-
dertake environmental responsibility.
5.2.5. Regional environmental enforcement intensity
Burby and Paterson (1993) argue that environmental regulations only pose significant risks to regulated entities when they
perceive a high likelihood of facing substantial fines or adverse consequences for non-compliance. In other words, environmental
regulations can only have a noticeable effect on environmental improvement in regions with strict enforcement. Therefore, differences
in environmental enforcement levels across regions may affect the effectiveness of GPP in environmental governance. This study
measures regional environmental enforcement intensity based on the number of environmental penalty cases, with more cases
indicating stricter enforcement. In this paper, the regional environmental protection enforcement strength is divided into three
strengths of low (EEI = 1), medium (EEI = 2), and high (EEI = 3) by three quartiles according to the year, respectively.
The regression results are shown in Table 12, with column (3) presenting results for regions with low enforcement, column (4) for
medium enforcement, and column (5) for high enforcement. The results show that GPP significantly positively impacts corporate
environmental performance only in regions with medium enforcement intensity, and the difference between ggp_n is statistically
significant.5 In regions with low enforcement, the execution and supervision of environmental regulations are lax, resulting in minimal
environmental pressure and penalty risk for enterprises, leading to insufficient motivation to improve environmental performance. In
regions with high enforcement, enterprises may already face stringent regulations, making the additional incentive effect of GPP
orders relatively limited, as these enterprises have already optimized their environmental measures in intense regulatory environments
and may allocate significant resources to dealing with penalties and compliance. Therefore, only in regions with medium enforcement
levels can enterprises better balance resource investment and environmental performance improvement, effectively responding to
GPP.
6. Further analysis
6.1. Impacts on corporate social responsibility and ESG performance
Given the behavioral consistency in corporate strategy (Cain & McKeon, 2016), companies that focus on environmental issues are
also likely to pay more attention to social responsibility issues. Additionally, the “Administrative Measures for Government Pro-
curement of Services” explicitly state that public procurement should select contractors based on the principles of both social and
economic benefits. This indicates that public procurement not only focuses on environmental performance but also values the social
responsibility commitments of suppliers. Dai et al. (2021) also emphasizes that corporate customers tend to establish supply chain
relationships with companies that engage in socially and environmentally responsible practices. Therefore, in addition to considering
the environmental governance effects of GPP, this paper will further examine the impact of GPP on corporate social responsibility
(CSR) and ESG performance.
Specifically, this paper uses the social responsibility score data provided by the HuazhengESG database to measure CSR and selects
the HuazhengESG rating as a proxy for corporate ESG performance. Similar to environmental performance, this paper assigns CSR and
ESG scores from 1 to 9, where ESG_q represents the annual average and ESG_y represents the year-end rating. The regression results are
shown in Table 13, where the dependent variable in column (1) is corporate social responsibility performance (CSR), column (2) is the
annual average ESG performance (ESG_q), and column (3) is the year-end ESG performance rating (ESG_y). It can be observed that GPP
orders significantly promote the improvement of corporate social responsibility performance and ESG performance. This indicates that
Table 13
Further analysis: Impacts on corporate social responsibility and ESG performance.
(1)
(2)
(3)
CSR
ESG_q
ESG_y
gpp_n
0.0684**
0.0810***
0.0762***
(0.034)
(0.025)
(0.028)
Constant
−9.2433***
−0.6157
−1.6647*
(1.351)
(0.913)
(0.946)
Controls
YES
YES
YES
Firm FE
YES
YES
YES
Year FE
YES
YES
YES
Observations
22,257
22,250
22,250
R-squared
0.7593
0.7231
0.6574
5 This paper conducts tests on the difference in regression coefficients between EEI=1 and EEI=2, as well as between EEI=2 and EEI=3. The
empirical p-value for the difference in regression coefficients between EEI=1 and EEI=2 is 0.003, which is significant at the 1% level. The empirical
p-value for the difference in regression coefficients between EEI=2 and EEI=3 is 0.009, also significant at the 1% level.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
17


## Page 18

GPP, by increasing the demand for green products and services, not only enhance corporate attention to environmental issues but also
guide companies to improve their practices in social responsibility and sustainable development, actively promoting green and low-
carbon development.
6.2. Enhancing the effectiveness of GPP
On the basis of confirming that GPP can promote enterprises to improve their environmental performance, this paper will explore
how to enhance the environmental performance incentive effect from the perspective of policy implementation. This paper analyzes
three aspects: the transparency of information disclosure, procurement efficiency, and the stability of supply and demand.
6.2.1. Transparency of information disclosure
Transparent information disclosure allows corporate environmental behaviors to be more easily monitored by the public, the
media, and relevant supervisory agencies. This transparency also increases corporate accountability, prompting more cautious efforts
toward environmental performance. This paper constructs a variable (Tran) to measure the transparency of GPP information
disclosure. This variable is based on the bid announcement information on the Chinese government procurement website, specifically
including key information such as contract name, contract number, project name, project number, signing time, purchaser, supplier,
contract amount, and more. If this information is missing or lack substantial details, such as the content being “none,” this information
is deemed to have substandard disclosure quality. This paper measures the transparency of GPP information by calculating the pro-
portion of information meeting disclosure quality standards to the total number of information that should be disclosed. The larger the
Tran value, the higher the transparency of information disclosure during the implementation of public procurement.
As shown in column (1) of Table 14, the regression coefficient of Tran is significantly positive at the 5% level. This indicates that the
higher the transparency of procurement information, the higher the environmental performance level of enterprises. This may be
because transparent information disclosure helps create a fair and competitive market environment, encouraging companies to
improve their environmental performance. Additionally, companies with strong political connections are more likely to obtain public
procurement. Therefore, transparent government procurement information helps reduce corruption and unfair competition, and a fair
business environment motivates companies to continuously improve their environmental performance.
6.2.2. Procurement efficiency
High procurement efficiency is one of the legislative goals of the “Government Procurement Law of the People’s Republic of China.”
Improving procurement efficiency has become a consistent focus for government authorities and academia (Wang et al., 2020). This
paper constructs a variable (effi) to measure the efficiency of GPP, calculated as the average interval between the start signing time and
the official announcement time of a GPP order. The longer the interval between the signing time and the announcement time, the lower
the efficiency of GPP. This paper only retains samples that obtained GPP orders within the sample period.
The regression results are shown in column (2) of Table 14. It can be seen that the regression coefficient of effi is significantly
negative at the 10% level, indicating that the lower the efficiency of GPP, the worse the effect of improving corporate environmental
performance. On the one hand, for supplier enterprises, a longer time interval will lead to the opacity of market information, which
makes enterprises feel that the public procurement process lacks efficiency and transparency, thus reducing their motivation to
participate in public procurement. Additionally, it increases the uncertainty of procurement outcomes for companies. During the
waiting period, companies might delay or reduce environmental investments, hindering continuous improvements in environmental
performance. On the other hand, for external stakeholders, the lag in information dissemination prevents timely understanding of
procurement details, weakening the ability of the public and media to supervise the procurement process, reducing external pressure
on companies’ environmental behaviors, and potentially diminishing their efforts in environmental performance. Therefore,
improving procurement efficiency can be achieved by advancing the electronic implementation of procurement projects and
Table 14
Further analysis: Enhancing the effectiveness of GPP.
(1)
(2)
(3)
EnvP1
EnvP1
EnvP1
tran
0.0628**
(0.031)
effi
−0.0004*
(0.000)
gpp_t
0.1073***
(0.018)
Constant
−0.0409
−5.8957
−2.7785***
(0.878)
(4.244)
(0.424)
Controls
YES
YES
YES
Firm FE
YES
YES
YES
Year FE
YES
YES
YES
Observations
22,257
1572
22,257
R-squared
0.7400
0.8062
0.1302
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
18


## Page 19

improving the internal contract signing process.
6.2.3. Stability of supply and demand
A stable procurement relationship can provide enterprises with long-term contracts and stable revenues, reduce their operational
uncertainty, and thus promote the continuous improvement of their environmental performance. In this paper, we construct the
stability variable (gpp_t) of supply and demand relationship, which is measured by the frequency number of public procurement orders
that enterprises have obtained in the sample period. The higher the value of gpp_t, the greater the continuity of policy support for the
company, and the more prominent the stability of the supply-demand relationship.
As shown in column (3) of Table 14, the regression coefficient of gpp_t is significantly positive at the 1% level. This indicates that the
more stable supply-demand relationship, the higher the company’s environmental performance. In other words, maintaining stable
procurement relationships, establishing long-term partnerships, and reducing frequent changes in suppliers can provide companies
with stable market expectations and financial support, thereby promoting continuous improvement in environmental performance.
7. Research conclusion and policy recommendation
Unlike traditional environmental regulation, GPP combines the advantages of command-and-control and market-based environ-
mental regulations, balancing government will with market mechanisms. It is an important policy for government departments to
implement their own responsibilities as participants in the market economy. By setting specific green procurement standards and
environmental requirements, GPP utilizes contract terms to force supplier companies to reduce pollution emissions and improve
environmental performance. In addition, the demonstration effect and moral influence of GPP have enhanced the overall environ-
mental awareness and action of society, becoming an important way to practice environmental protection.
This paper used crawler technology to obtain public procurement contract data from the China Government Procurement Network
from 2015 to 2021. Next, by reviewing relevant green procurement policy documents and using the Word2vec model, this paper
constructed a wordlist of “green procurement contract.” Finally, we used text analysis to identify GPP contracts, which were then
matched with data on Chinese A-share listed companies to empirically examine the impact of GPP contracts on corporate environ-
mental performance. This study finds that GPP significantly enhances corporate environmental performance. This conclusion remains
robust after a series of robustness tests and addressing endogeneity issues. Also, this paper demonstrates in the robustness tests that this
environmental incentive effect mainly stems from green procurement contracts rather than general public procurement contracts.
Further mechanism tests reveal that GPP improves environmental performance through four pathways: raising environmental
awareness among management, enhancing green innovation capabilities, increasing environmental investments, and strengthening
government supervision. Heterogeneity analysis indicates that GPP primarily improves environmental performance in non-state-
owned enterprises, small and medium-sized enterprises and heavy-polluting enterprises. Moreover, this improvement is more pro-
nounced in regions with high government environmental concern and moderate environmental enforcement intensity. Further
analysis shows that GPP also enhances corporate social responsibility performance and ESG performance, promoting sustainable
development. Finally, this study finds that increasing the transparency of procurement information, improving procurement effi-
ciency, and maintaining stable procurement relationships contribute to strengthening the environmental performance incentives of
GPP.
The conclusions of this study provide both theoretical and practical support for the development of GPP policies and offer sig-
nificant policy implications. First, there is a need to further expand the scale and scope of GPP. This study found that GPP can achieve
environmental governance effects at the micro level through contract regulation. However, there is still huge room for development in
green procurement. Currently, China’s GPP mainly covers energy-saving and environmental protection product categories, and green
building standards have been issued for engineering projects. However, corresponding work on service projects has not yet been
undertaken. GPP should consider expanding its scope to better leverage the policy’s environmental governance effects and promote
improvements in corporate environmental performance. Second, it is essential to develop differentiated GPP policies based on supplier
and regional characteristics. More specific and effective direction should be given through increased fiscal and tax incentives for state-
owned, large and non-heavily-polluting enterprises, as GPP policies have a substantial impact on the environmental performance of
SMEs, non-state-owned enterprises and heavy-polluting enterprises In addition, GPP should be combined with regional environmental
regulation efforts and enforcement. Regions with high government environmental attention provide good policy support and incentive
environments, while regions with medium environmental enforcement levels offer appropriate compliance pressure and innovation
space for enterprises. This combination helps to maximize the promotional effect of GPP policies on corporate environmental per-
formance. Thirdly, improve the transparency of GPP information and the efficiency of policy implementation, facilitating the
participation of all types of business entities in GPP activities. This study finds that increasing the transparency of procurement in-
formation, improving procurement efficiency, and maintaining stable procurement relationships contribute to strengthening the
environmental performance incentives of GPP. Therefore, it is necessary to improve the information disclosure system and promote the
electronic implementation of GPP projects. In addition, the efficiency of signing procurement contracts should be improved, and the
payment cycle for procurement funds should be shortened.
Author Statement
Conceptualization, S.Z.; methodology, S.Z.; software, S.Z.; validation, S.Z.; formal analysis, S.Z.; investigation, S.Z.; resources, S.Z.;
data curation, S.Z.; writing—original draft preparation, S.Z.; writing—review and editing, X.Y.; visualization, S.Z.; supervision, X.Y.;
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
19


## Page 20

project administration, X.Y.
All authors have read and agreed to the published version of the manuscript.
Data availability
Data will be made available on request.
References
Antweiler, W., Copeland, B. R., & Taylor, M. S. (2001). Is free trade good for the environment? The American Economic Review, 91(4), 877–908.
Barro, R. J., & Redlick, C. J. (2011). Macroeconomic effects from government purchases and taxes. Quarterly Journal of Economics, 126(1), 51–102.
Bertels, S., & Peloza, J. (2008). Running just to stand still? Managing CSR reputation in an era of ratcheting expectations. Corporate Reputation Review, 11, 56–72.
Bertrand, M., & Schoar, A. (2003). Managing with style: The effect of managers on firm policies. Quarterly Journal of Economics, 118(4), 1169–1208.
Bleda, M., & Chicot, J. (2020). The role of public procurement in the formation of markets for innovation. Journal of Business Research, 107, 186–196.
Brown, B. P., Mohan, M., & Boyd, D. E. (2017). Top management attention to trade shows and firm performance: A relationship marketing perspective. Journal of
Business Research, 81, 40–50.
Burby, R. J., & Paterson, R. G. (1993). Improving compliance with state environmental regulations. Journal of Policy Analysis and Management, 12(4), 753–772.
Cain, M. D., & McKeon, S. B. (2016). CEO personal risk-taking and corporate policies. Journal of Financial and Quantitative Analysis, 51(1), 139–164.
Campbell, J. L. (2007). Why would corporations behave in socially responsible ways? An institutional theory of corporate social responsibility. Academy of
Management Review, 32(3), 946–967.
Castells, P. A., & Mohnen, P. (2015). Sunk costs, extensive R&D subsidies and permanent inducement effects. The Journal of Industrial Economics, 63(3), 458–494.
Cerutti, A. K., Contu, S., Ardente, F., Donno, D., & Beccaro, G. L. (2016). Carbon footprint in green public procurement: Policy evaluation from a case study in the food
sector. Food Policy, 58, 82–93.
Chang, C. H. (2011). The influence of corporate environmental ethics on competitive advantage: The mediation role of green innovation. Journal of Business Ethics,
104, 361–370.
Chang, L., Li, W., & Lu, X. (2015). Government engagement, environmental policy, and environmental performance: Evidence from the most polluting Chinese listed
firms. Business Strategy and the Environment, 24(1), 1–19.
Clarkson, P. M., Li, Y., Richardson, G. D., & Vasvari, F. P. (2008). Revisiting the relation between environmental performance and environmental disclosure: An
empirical analysis. Accounting, Organizations and Society, 33(4–5), 303–327.
Cohen, D., Li, B., Li, N., & Lou, Y. (2022). Major government customers and loan contract terms. Review of Accounting Studies, 1–38.
Czarnitzki, D., Hünermund, P., & Moshgbar, N. (2020). Public procurement of innovation: Evidence from a German legislative reform. International Journal of
Industrial Organization, 71, Article 102620.
Dai, X., Li, Y., & Chen, K. (2021). Direct demand-pull and indirect certification effects of public procurement for innovation. Technovation, 101, Article 102198.
Dhaliwal, D., Judd, J. S., Serfling, M., & Shaikh, S. (2016). Customer concentration risk and the cost of equity capital. Journal of Accounting and Economics, 61(1),
23–48.
Drempetic, S., Klein, C., & Zwergel, B. (2020). The influence of firm size on the ESG score: Corporate sustainability ratings under review. Journal of Business Ethics, 167
(2), 333–360.
Fang, Z., Kong, X., Sensoy, A., Cui, X., & Cheng, F. (2021). Government’s awareness of environmental protection and corporate green innovation: A natural
experiment from the new environmental protection law in China. Economic Analysis and Policy, 70, 294–312.
Fisman, R., & Svensson, J. (2007). Are corruption and taxation really harmful to growth? Firm level evidence. Journal of Development Economics, 83(1), 63–75.
Friedman, J. H. (1989). Regularized discriminant analysis. Journal of the American Statistical Association, 84(405), 165–175.
Ghisetti, C. (2017). Demand-pull and environmental innovations: Estimating the effects of innovative public procurement. Technological Forecasting and Social Change,
125, 178–187.
Han, S., Pan, Y., Mygrant, M., & Li, M. (2021). Differentiated environmental regulations and corporate environmental responsibility: The moderating role of
institutional environment. Journal of Cleaner Production, 313, Article 127870.
He, Z. X., Xu, S. C., Shen, W. X., Long, R. Y., & Chen, H. (2016). Factors that influence corporate environmental behavior: Empirical analysis based on panel data in
China. Journal of Cleaner Production, 133, 531–543.
Huang, D., Cheng, J., Quan, X., & Wu, Y. (2024). Managerial attention to environmental protection and corporate green innovation. Review of Quantitative Finance and
Accounting, 1–35.
Igarashi, M., de Boer, L., & Michelsen, O. (2015). Investigating the anatomy of supplier selection in green public procurement. Journal of Cleaner Production, 108,
442–450.
Kadefors, A., Lingegård, S., Uppenberg, S., Alkan-Olsson, J., & Balian, D. (2021). Designing and implementing procurement requirements for carbon reduction in
infrastructure construction–international overview and experiences. Journal of Environmental Planning and Management, 64(4), 611–634.
King, A. A., Lenox, M. J., & Terlaak, A. (2005). The strategic use of decentralized institutions: Exploring certification with the ISO 14001 management standard.
Academy of Management Journal, 48(6), 1091–1106.
Kou, M., Zhang, L., Wang, H., Wang, Y., & Shan, Z. (2024). The heterogeneous impact of green public procurement on corporate green innovation. Resources,
Conservation and Recycling, 203, Article 107441.
Krieger, B., & Zipperer, V. (2022). Does green public procurement trigger environmental innovations? Research Policy, 51(6), Article 104516.
Leiter, A. M., Parolini, A., & Winner, H. (2011). Environmental regulation and investment: Evidence from European industry data. Ecological Economics, 70(4),
759–770.
Li, W., & Lu, X. (2016). Institutional interest, ownership type, and environmental capital expenditures: Evidence from the most polluting Chinese listed firms. Journal
of Business Ethics, 138, 459–476.
Li, S., Zheng, X., Liao, J., & Niu, J. (2024). Low-carbon city pilot policy and corporate environmental performance: Evidence from a quasi-natural experiment.
International Review of Economics & Finance, 89, 1248–1266.
Liao, Z. (2018). Environmental policy instruments, environmental innovation and the reputation of enterprises. Journal of Cleaner Production, 171, 1111–1117.
Lin, B., & Chen, X. (2020). Environmental regulation and energy-environmental performance—empirical evidence from China’s non-ferrous metals industry. Journal
of Environmental Management, 269, Article 110722.
Lin, Y., Fu, X., & Fu, X. (2021). Varieties in state capitalism and corporate innovation: Evidence from an emerging economy. Journal of Corporate Finance, 67, Article
101919.
Lin, H., Zeng, S. X., Ma, H. Y., & Chen, H. Q. (2015). How political connections affect corporate environmental performance: The mediating role of green subsidies.
Human and Ecological Risk Assessment: An International Journal, 21(8), 2192–2212.
Lindstr¨om, H., Lundberg, S., & Marklund, P. O. (2020). How Green Public Procurement can drive conversion of farmland: An empirical analysis of an organic food
policy. Ecological Economics, 172, Article 106622.
Lundberg, S., & Marklund, P. O. (2013). Green public procurement as an environmental policy instrument: Cost effectiveness. Environmental Economics, (4, Iss. 4),
75–83.
McMurray, A. J., Islam, M. M., Siwar, C., & Fien, J. (2014). Sustainable procurement in Malaysian organizations: Practices, barriers and opportunities. Journal of
Purchasing and Supply Management, 20(3), 195–207.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
20


## Page 21

Nissinen, A., Parikka-Alhola, K., & Rita, H. (2009). Environmental criteria in the public purchases above the EU threshold values by three Nordic countries: 2003 and
2005. Ecological Economics, 68(6), 1838–1849.
Obwegeser, N., & Müller, S. D. (2018). Innovation and public procurement: Terminology, concepts, and applications. Technovation, 74, 1–17.
Orsatti, G., Perruchas, F., Consoli, D., & Quatraro, F. (2020). Public procurement, local labor markets and green technological change. Evidence from US commuting
zones. Environmental and Resource Economics, 75, 711–739.
Porter, M. E., & Linde, C. V. D. (1995). Toward a new conception of the environment-competitiveness relationship. The Journal of Economic Perspectives, 9(4), 97–118.
Qi, G., Zeng, S., Li, X., & Tam, C. (2012). Role of internalization process in defining the relationship between ISO 14001 certification and corporate environmental
performance. Corporate Social Responsibility and Environmental Management, 19(3), 129–140.
Ren, X., Zeng, G., & Sun, X. (2023). The peer effect of digital transformation and corporate environmental performance: Empirical evidence from listed companies in
China. Economic Modelling, 128, Article 106515.
Rosell, J. (2021). Getting the green light on green public procurement: Macro and meso determinants. Journal of Cleaner Production, 279, Article 123710.
Samuels, D. (2021). Government procurement and changes in firm transparency. The Accounting Review, 96(1), 401–430.
Simcoe, T., & Toffel, M. W. (2014). Government green procurement spillovers: Evidence from municipal building policies in California. Journal of Environmental
Economics and Management, 68(3), 411–434.
Smulowitz, S. J., Cossin, D., & Lu, H. (2023). Managerial short-termism and corporate social performance: The moderating role of external monitoring. Journal of
Business Ethics, 188(4), 759–778.
Sparrevik, M., Wangen, H. F., Fet, A. M., & De Boer, L. (2018). Green public procurement–A case study of an innovative building project in Norway. Journal of Cleaner
Production, 188, 879–887.
Sun, J., Wang, F., Yin, H., & Zhang, B. (2019). Money talks: The environmental impact of China’s green credit policy. Journal of Policy Analysis and Management, 38(3),
653–680.
Sun, C., Zhan, Y., & Gao, X. (2023). Does environmental regulation increase domestic value-added in exports? An empirical study of cleaner production standards in
China. World Development, 163, Article 106154.
Waddock, S. A., & Graves, S. B. (1997). The corporate social performance–financial performance link. Strategic Management Journal, 18(4), 303–319.
Walls, J. L., Berrone, P., & Phan, P. H. (2012). Corporate governance and environmental performance: Is there really a link? Strategic Management Journal, 33(8),
885–913.
Wang, Q., Zhang, R., & Liu, J. (2020). Price/time/intellectual efficiency of procurement: Uncovering the related factors in Chinese public authorities. Journal of
Purchasing and Supply Management, 26(3), Article 100622.
Xu, Q., & Kim, T. (2022). Financial constraints and corporate environmental policies. Review of Financial Studies, 35(2), 576–635.
Xu, L., Yang, L., Li, D., & Shao, S. (2023). Asymmetric effects of heterogeneous environmental standards on green technology innovation: Evidence from China. Energy
Economics, 117, Article 106479.
Ye, M., Ma, Y., & Liu, J. (2022). Why do public sectors perform high-level green public procurement practice? A new insight with fsQCA approach. Journal of
Environmental Planning and Management, 65(14), 2719–2747.
Yu, X., Shi, J., Wan, K., & Chang, T. (2022). Carbon trading market policies and corporate environmental performance in China. Journal of Cleaner Production, 371,
Article 133683.
Zhang, Z., & Jiang, Y. (2022). Can green public procurement change energy efficiency? Evidence from a quasi-natural experiment in China. Energy Economics, 113,
Article 106244.
Zhang, W., Luo, Q., & Liu, S. (2022). Is government regulation a push for corporate environmental performance? Evidence from China. Economic Analysis and Policy,
74, 105–121.
Zhang, B., Wang, Y., & Sun, C. (2023). Urban environmental legislation and corporate environmental performance: End governance or process control? Energy
Economics, 118, Article 106494.
Zhao, A., Wang, J., Sun, Z., & Guan, H. (2022). Environmental taxes, technology innovation quality and firm performance in China—a test of effects based on the
Porter hypothesis. Economic Analysis and Policy, 74, 309–325.
S. Zheng and J. Wen
International Review of Economics and Finance 96 (2024) 103578
21

