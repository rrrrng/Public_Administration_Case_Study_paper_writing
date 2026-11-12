# Public Administration Review - 2025 - Picavet - Human Machine Collaboration for 

## Page 1

Public Administration Review, 2026; 86:299–310
https://doi.org/10.1111/puar.70048
299
Public Administration Review
PRACTICALLY SPEAKING
Human–Machine Collaboration for Strategy Foresight:
The Case of Generative AI
Marc E. B. Picavet1  |  Peter Maroni2  |  Amardeep Sandhu3  |  Kevin C. Desouza1
1School of Management, Faculty of Business and Law, Queensland University of Technology (QUT), Brisbane, Queensland, Australia  |  2Customer and
Digital Group, Queensland Government, Brisbane, Queensland, Australia  |  3Lemonade Labs Limited, Brisbane, Queensland, Australia
Correspondence: Marc E. B. Picavet (marc.bardapicavet@qut.edu.au)
Received: 24 March 2025  |  Revised: 29 September 2025  |  Accepted: 13 October 2025
Keywords: design science | generative artificial intelligence | large language models | public innovation | strategic foresight
ABSTRACT
Generating strategic foresight for public organizations is a resource-­intensive and non-­trivial effort. Strategic foresight is es-
pecially important for governments, which are increasingly confronted by complex and unpredictable challenges and wicked
problems. With advances in machine learning, information systems can be integrated more creatively into the strategic foresight
process. We report on an innovative pilot project conducted by an Australian state government that leveraged generative arti-
ficial intelligence (AI), specifically large language models, for strategic foresight using a design science approach. The project
demonstrated AI's potential to enhance scenario generation for strategic foresight, improve data processing efficiency, and sup-
port human decision-­making. However, the study also found that it is essential to balance AI automation with human expertise
for validation and oversight. These findings highlight the importance of iterative design to develop robust AI tools for strategic
foresight which, alongside stakeholder engagement and process transparency, build trust and ensure practical relevance.
1   |   Introduction
Designing public policy requires organizations to have strategic
foresight. Strategic foresight focuses on visualizing the future
and then exploring multiple plausible future scenarios. It is a
highly information-­intensive process, defined as “an image, an
insight, a picture, a concept” of the future at least 5 years beyond
the present (Coates 2010, 1428). These future-­oriented images
or scenarios help public sector organizations anticipate policy
challenges and opportunities, enabling them to adapt their strat-
egies proactively. However, strategic foresight is not quantitative
in nature; it does not aim to predict the future, and it is not lim-
ited to a specific future date (Coates 2010; Wilner and Roy 2020).
Strategic foresight is especially important for governments as
the public sector increasingly faces complex, unpredictable, and
wicked problems. In response, multiple innovative initiatives
involving strategic foresight have been put in place or tested
recently (Pólvora and Nascimento 2021; Wilner and Roy 2020).
For example, Singapore's government adopted a foresight ap-
proach and institutionalized its practices in the public service
with the purpose of thinking ahead, anticipating change, and
staying relevant (Choo and Fergnani 2022). More recently, the
European Parliament's Scientific Foresight Unit commissioned
a foresight exercise to engage policymakers using illustrations of
possible futures to better understand the challenges ahead and
identify key drivers of change (Puerta Pereira et al. 2025).
However, research has shown that strategic foresight is not with-
out its challenges (Schmidthuber and Wiener 2021). When fore-
sight activities rely solely on in-­house expertise, for example, it
can constrain the diversity of perspectives and limit the genera-
tion of innovative or creative scenarios. This is due to internal bi-
ases and often results in a narrow, shortsighted perspective that
weakens the usefulness of foresight exercises (Schmidthuber
and Wiener 2021). Mitigation can be done by hiring specialized
consultancies, but the scale and complexity of available data
today make it difficult for any single organization to fully grasp
© 2025 American Society for Public Administration.


## Page 2

300
Public Administration Review, 2026
emerging trends and possibilities. Additionally, for public orga-
nizations with budget constraints, hiring external consultants
can be expensive. Finally, the natural human tendency to prior-
itize immediate concerns over long-­term planning adds another
layer of difficulty to strategic foresight (Linstone 2010).
Generative AI1 and large language models (LLMs) in particu-
lar present an opportunity to enhance strategic foresight. These
models can process and analyze amounts of data far beyond
the scope of unaided human capability. With it, organizations
can create a broader range of strategic foresight scenarios with
greater depth and nuance, incorporating insights from more
sources. This approach addresses the limitations of traditional
foresight methods, particularly reliance on biased internal ca-
pabilities, expensive consultancies, and the challenges of data
complexity (Schmidthuber and Wiener 2021).
Against this backdrop, we collaborated with a public organi-
zation on an innovative project to embed and leverage LLMs
within their strategic foresight process. This approach was then
validated and evaluated using an iterative process. Given the
constructivist nature of the project, we employed a design sci-
ence research methodology where evaluation and feedback were
used to improve the process and the scenarios created.
The remainder of the article is organized as follows. The next
section provides an overview of strategic foresight and LLMs.
Following this, methodological details are covered. Peffers
et al.'s (2007) design science framework is then used for the con-
ceptual development of the strategic foresight tool and to report
the findings. The article closes with a discussion of key findings,
implications, and areas for future research.
2   |   Theory
Strategic foresight matters for public organizations for several
reasons. First, they must account for multiple objectives beyond
economic returns. Second, they must consider and include a di-
verse range of stakeholders. Third, they must design policy for
the long term due to the high costs of political and policy pro-
cesses (Monteiro and Dal Borgo 2023). We begin by briefly cov-
ering the role of strategic foresight in the public sector.
2.1   |   Strategic Foresight in the Public Sector
The use of strategic foresight in government is not new. In 1945,
a committee of the United States Army Air Forces was tasked
with looking at aviation advances over the next 20 years. The
committee established Project RAND, which issued a strategic
foresight report in 1946 on the potential design, performance,
and use of satellites. Within only 10 years, the first US satellite
was launched. This illustrates how strategic foresight can lead to
potentially groundbreaking advances. During the 1950s, RAND
pioneered the use of foresight methods that are still used today,
such as the Delphi process (Linstone 2010; RAND 2024).
Government use of strategic foresight has expanded in recent
years. Prominent examples include The Horizon Scanning
Centre in the United Kingdom (Delaney and Osborne  2013)
and Policy Horizons Canada (Wilner and Roy  2020). Beyond
these, Australia, Brazil, Chile, Finland, France, New Zealand,
the Netherlands, Singapore, South Korea, and the United
Arab Emirates have all implemented foresight initiatives in
various forms (Choo and Fergnani  2022; Dufva et  al.  2015;
Habegger 2010; Kim et al. 2019; Pólvora and Nascimento 2021).
Schmidt (2015) estimated that approximately 20 countries had
established ongoing foresight functions in their government and
predicted that this number would continue to increase.
Despite this momentum, strategic foresight remains unevenly
institutionalized across different national contexts. In the US,
for example, Greenblott et al. (2019) noted that while its use was
increasing, foresight remained “underdeveloped and fragile”
(264), with greater adoption in intelligence and defense agencies
than in civilian ones. In contrast, the Canadian foresight eco-
system has shown signs of maturation. For instance, Wilner and
Roy  (2020) observed growing demand among Canadian gov-
ernment departments for foresight training and tools, as well as
increased collaboration with scholars. Indeed, Policy Horizons
Canada, the Canadian Government's center of excellence in
foresight, was created to support the development of future-­
oriented policies. It assists various public organizations by
applying foresight methods outside typical political and bureau-
cratic constraints and by publishing reports on future challenges
and opportunities from 15 to 20 years ahead (Horizons 2024).
In Australia, strategic foresight has been conducted since the early
2000s through the Australia New Zealand Horizon Scanning
Network. In 2005, the Australasian Joint Agencies Scanning
Network was created to pool all agency resources to use stra-
tegic foresight methods (Delaney and Osborne  2013). With the
emergence of new tools and capabilities for strategic foresight,
some Australian state agencies and departments started to exper-
iment with new approaches. For example, the New South Wales
(NSW) Trend Atlas is a digital self-­service platform started in
2023 that supports NSW Government planning for future uncer-
tainties through combining automation and human interaction
Evidence for Practice
•	 Integrating generative AI into strategy design can
considerably enhance the efficiency and depth of sce-
nario generation for strategic foresight exercises, al-
lowing organizations to process vast amounts of data
and overcome the limitations of traditional foresight
methods.
•	 In human–machine collaborations, while generative
AI excels at automating data processing and gener-
ating outputs, human expertise remains crucial for
validating outputs and providing context-­specific
insights.
•	 An iterative design science approach with continuous
feedback and refinement is essential for developing ro-
bust AI-­driven tools for public organizations.
•	 Engaging stakeholders throughout the development
process through workshops and regular communica-
tion fosters trust in AI tools and ensures that the final
product meets the practical needs of its users.


## Page 3

301
Public Administration Review, 2026
(Normoyle  2023). The output is trend cards for specific topics,
with trend description, domain involved, potential indicators, and
sources (see Supporting Information: Appendix A).
In 2023, the Australian government's Policy Project and
Taskforce Office (PPTO) was tasked to help the Department of
the Prime Minister and Cabinet assess the impacts of climate
change. To do this, the PPTO developed scenarios that combined
future trends and implications of climate change, illustrating
how these factors could shape the policy landscape over the next
five to 10 years. The aim was to stimulate the department to ex-
plore the potential effects of climate change on their policy areas
and identify climate-­related risks, opportunities, and policy ac-
tions (Hartigan and Horobin 2023).
In summary, strategic foresight can help the public sector to
identify and anticipate how changes may unfold and adjust ac-
cordingly. This includes support in understanding disruptive
technologies (e.g., blockchain, AI, and nanotechnology) and
their implications for governments' socioeconomic and security
priorities (Wilner and Roy 2020). More broadly, incorporating
strategic foresight approaches also enriches the discourse be-
tween policy, planning, and intelligence by offering a wider con-
text and additional insights (Schmidt 2015).
Strategic foresight has also attracted scholarly attention. Cairns
and Wright  (2017), for example, developed a strategic foresight
framework that was adapted for this project. This framework was
chosen as it provides three methodologies for scenario planning
that contrast significantly with traditional forecasting and are
more specific for the public sector. The first methodology, intuitive
logics, challenges business-­as-­usual assumptions by identifying
main uncertainties and using it to develop multiple plausible fu-
tures rather than predicting a single one. The second methodology,
critical scenario method, brings explicit considerations of power,
ethics, and the moral consequences of decision-­making into sce-
nario creation. By incorporating an ethical and power dimension,
this method helps the public sector to stay focused on inclusive, re-
sponsible, and transparent policymaking for the future. The third
methodology, branching scenarios, emphasizes local agency by
showing how local actions (or inactions) can alter outcomes even
under macro-­level influences. This contrasts with conventional
scenarios that usually imply local conditions are solely determined
by broader global or national factors.
The present review on strategic foresight in the public sector
across multiple countries can be summarized as follows: (1) stra-
tegic foresight is established across governments, but unevenly
institutionalized; (2) the use of strategic foresight is needed to
shaping, constructing, implementing, and evaluating resilient
public policy for the future; (3) foresight benefits from central-
ization and entrepreneurial leadership; and (4) there are oppor-
tunities to embed digital technologies into strategic foresight,
but these have yet to be realized.
2.2   |   Generative AI and Strategy Design
The integration of generative AI into strategy design and plan-
ning is still in its early stages but rapidly gaining momentum
(Chui et  al.  2022; Finkenstadt et  al.  2024; Holmström and
Carroll  2024; Ritcher  2024). One of the key benefits of these
models is their ability to process and synthesize large amounts
of data, allowing organizations to gain insights that would
otherwise require extensive manual analysis (Holmström and
Carroll 2024). By enriching scenario generation and streamlin-
ing the decision-­making process, LLMs allow organizations to
better anticipate and respond to future uncertainties.
LLMs can improve strategic foresight by enabling organiza-
tions to create a broader range of creative scenarios with greater
depth and nuance, incorporating insights from numerous
sources. In this context, LLMs can address the limitations of
traditional strategic foresight methods, such as reliance on bi-
ased internal perspectives, expensive consultancies, and data
complexity challenges. Indeed, LLMs can democratize access
to high-­quality strategic foresight, enabling even small firms or
public organizations with limited resources to engage with it.
Furthermore, LLMs can autonomously identify patterns, trends,
and potential future developments that might be overlooked by
human analysts, providing a more comprehensive and data-­
driven base for scenario planning. They could also ensure that
strategic foresight is based on the most up-­to-­date and extensive
data available, leading to more robust and adaptive organiza-
tional strategies.
LLMs also facilitate simultaneous exploration of multiple stra-
tegic options, allowing a broader, more rigorous assessment of
potential risks and outcomes. The flexibility of these models in
generating creative and diverse scenarios makes them a valuable
tool in environments where traditional methods may be inade-
quate due to time, capital, resources, or analytical constraints
(Chui et al. 2022; Holmström and Carroll 2024).
However, the adoption of LLMs in strategic contexts brings no-
table challenges, particularly in terms of governance and ethical
considerations. The rapid industrialization of LLMs raises risks
associated with their widespread use, including the potential
for misuse and the concentration of power among a few large
technology companies. Leslie and Perini (2024) emphasize the
urgent need for a robust governance framework to manage these
risks and ensure that the benefits of LLMs are distributed equi-
tably across society.
In summary, this review on LLMs and strategy foresight indi-
cates that: (1) use of LLMs for strategic foresight is limited, given
their inherent risks and lack of transparency in output genera-
tion; (2) LLMs that can be leveraged for information processing
and synthesis during the strategic foresight process, which can
be very human-­intensive and does not scale across domains;
and (3) there are important governance considerations when
it comes to human–machine collaboration that need to be ad-
dressed to ensure that the strategic foresight process is robust.
3   |   Methods
3.1   |   Design Science Research Methodology
Public organizations are increasingly experimenting with de-
sign science through design labs and participatory methods, sig-
naling a shift toward a more creative and inclusive process in


## Page 4

302
Public Administration Review, 2026
public administration (van Buuren et al. 2020). Design science
allows managers to test and refine creative solutions, providing
the freedom to explore new possibilities within the typically
rigid and rule-­bound environment of governments (van Buuren
et al. 2020).
Design science was chosen for this research because it broad-
ens the range of possible solutions and encourages creativity,
learning, and experimentation (van Buuren et al. 2020). It also
provides a more agile and effective way to understand stake-
holders' challenges and develop prototypes for mutually ben-
eficial solutions (Fatima et al. 2022). Finally, it complements
qualitative research as both approaches work inductively
using emerging insights from data (Patton 2022). Design sci-
ence has recently gained traction in public administration
(Fatima et  al.  2022; Meier  2005; Romme and Meijer  2020;
Shangraw and Crow Shangraw Jr and Crow 1989; van Buuren
et al. 2020; Walker 2011) but remains a niche research meth-
odology in public administration research (Romme and
Meijer 2020).
We followed the design science approach of Peffers et al. (2007).
They proposed the following steps: (1) identifying a problem; (2)
defining the objectives of a solution; (3) designing the tool; (4)
demonstrating the tool; (5) evaluating the effectiveness of the
tool; and (6) communicating the tool on relevant platforms as a
solution to the problem formulated in the first step.
3.2   |   The Project
The Queensland Government established the Futures and
Foresight team (FFT) in 2023 and tasked it with delivering stra-
tegic foresight with a focus on the digital landscape. The pilot
project ran for 6 months from January to June 2024. The project
team consisted of representatives from the FFT and a university
partner who made up the Evaluation and Enhancement Team
(EET). The FFT team for this project comprised a director (proj-
ect lead), an architecture and modeling lead, and a programmer
who worked on programming the LLM. The EET team con-
sisted of a professor (the lead advisor on the project, who has
taught strategic foresight units for over 7 years) and a postdoc-
toral research fellow (who was the rapporteur for all meetings
and conducted any necessary research and writing as the project
unfolded).
The overall process was broken down into the following steps:
(1) a large and diverse set of documents (reports, research pa-
pers, and articles, among others) were scanned to collect the
driving forces and trends that could impact the organization
and its broader operating ecosystem; (2) the driving forces
and trends were scrutinized for their veracity and analyzed
to identify connections and create informal clusters; (3) the
uncertainty and impact of each cluster were calibrated based
on plausible extreme outcomes; and (4) the clusters (two or
more) that had the greatest impact and uncertainty were jux-
taposed to generate imaginative plausible future scenarios
of what the organization's operating and strategic environ-
ments might look like over the next five to 10 years. Table 1
presents this process using the design science steps of Peffers
et al. (2007).
4   |   Findings
The following section outlines the findings of the pilot project,
structured around the design science research methodology.
Figure 1 summarizes this iterative process, illustrating the pro-
gression from initial problem definition through the iterative
cycles of design, testing, and refinement.
4.1   |   Identifying a Problem
The FFT was established to deliver strategic foresight for long-­
term planning to guide Queensland's digital policy. Early in
their work, the FFT recognized several challenges with exist-
ing foresight practices. Traditional scenario planning processes
were lengthy, often taking 12 to 18 months, highly reliant on
human input, disruptive to operations, and rarely updated.
These characteristics were incompatible with the rapid pace and
complexity of change in the digital policy environment.
The FFT then identified three specific, interrelated challenges:
(1) the difficulty of quickly processing and analyzing a large vol-
ume of data with limited personnel and budget; (2) the need to
translate trends from research into actionable insights; and (3)
the lack of an agile, repeatable, and evidence-­informed process
for scenario planning in fast-­changing environments.
Given this context, the FFT sought to explore whether LLMs
could help overcome these challenges. Rather than survey-
ing a wide range of tools, the team began with the practical
TABLE 1    |    Design science framework.
Problem identification
How to build a scalable and
reusable strategic foresight process
leverages LLMs in a way that is
practical, secure, and contextually
appropriate for the public sector
Solution objectives
A scalable, reusable, and
transparent strategic foresight
process with disciplined
human–machine collaboration
Tool design
Leveraged relevance. AI to
elicit driving forces, assess
links between driving forces
to create clusters, impact and
uncertainty analysis, and
plausible future generation
Demonstration
Workshop with stakeholders
to share details on the
prototype and the outputs.
Evaluation
Expert reviews of the LLM-­
infused solution, the process, and
the quality of scenario outputs
Communication
Presentation and communication
with the senior leadership,
academic workshops,
and other forums.


## Page 5

303
Public Administration Review, 2026
assumption that generative AI was already emerging as a prom-
ising technology that could support faster, more scalable fore-
sight work. All this pointed to a broader design problem: how
to build a scalable and reusable strategic foresight process that
could leverage LLMs in a way that would be practical, secure,
and contextually appropriate for the public sector. The pilot proj-
ect was therefore structured as a proof of concept to evaluate the
potential of human–machine collaboration.
4.2   |   Defining the Objectives of a Solution
As the FFT was a small team, they used emerging technol-
ogies to improve the speed and quality of strategic foresight.
Additionally, as the project lead noted, the FFT was formed
“just as breakthroughs in Chat GPT were occurring, and the
Queensland Government was building AI capability and im-
plementing Q-­Chat (a Queensland Government AI-­powered
assistant).” This timing created organizational synergies that
the FFT could use. Thus, the FFT explored how LLMs could be
embedded in a foresight process to “scale what a small human
team is capable of while bringing much more information into
the process” (project lead).
To achieve this, in January 2024 the FFT launched the
Collaborative Intelligence Pilot Project, aimed at trialing both
a scenario development methodology and the technologies that
could support it. The goal was to design and test a human–tech-
nology process that combined the analytical strengths of gen-
erative AI with the judgment of human experts. This trial had
two key elements: (1) proof of concept—the development of an
innovative, agile, and repeatable strategic foresight methodol-
ogy—and (2) proof of technology—the evaluation of emerging
technologies that could reliably support and enhance the sce-
nario development methodology.
To test both the methodology and technology, a focal issue was
selected at the outset for which future scenarios would be de-
veloped. The focal issue selected was digital trust, as defined by
the World Economic Forum (2025), and the focus question was
the following: What are the possible futures for digital trust out
to 2032, and what do they mean for the future of the Queensland
Government's digital service delivery?
4.3   |   Designing the Tool
A pilot project was then launched to assess and guide potential
full-­scale implementation. The FFT selected the Relevance AI
platform (https://​relev​anceai.​com), as it had already been tested
and approved by another state government department. This
platform offered a single interface to access multiple genera-
tive AI models, including ChatGPT, Claude, and Gemini. This
allowed the FFT to experiment with different models in one
place and compare their performance for specific tasks such
as organizing information, identifying trends, and generating
future scenarios. The FFT had a paid subscription to the plat-
form, which met the government's data security and privacy
standards. With this platform, the FFT then designed a strate-
gic foresight process for scenario development. This process was
adapted from Cairns and Wright (2017) and other best-­practice
methodologies to suit a technology-­augmented process. The sce-
nario development process had six main steps.
Each step involved collaboration between the FFT, LLMs, the
EET, and human subject matter experts (SMEs). The SMEs
were drawn from all levels of government, including officers,
senior officers, principal officers, directors, and executive direc-
tors. They came from different departments working in digital
identity, strategic foresight, digital policy, strategic policy, op-
erational policy, and AI risk and assurance. The steps were as
follows.
4.3.1   |   Scanning
Scanning was intended to extract high-­quality, current driv-
ing forces from a wide range of trusted and recognized digi-
tal sources and store them in a knowledge base to inform all
strategic foresight activities undertaken by the Queensland
Government. This process ensured a more consistent, evidence-­
based, and up-­to-­date baseline for the creation of strategic fore-
sight scenarios than traditional scenario planning activities.
Because this approach drew on a variety of expert opinions, re-
search findings, and industry reports, human biases were also
mitigated. Generative AI was used to process these source files
and identify the key driving forces, their attributes, and relation-
ships with each other.
4.3.2   |   Refinement
Because driving forces were collected from numerous docu-
ments and sources, duplicates often emerged. The refinement
step focused on eliminating these duplicates and identifying the
most relevant driving forces for the focal issue. These refined
forces were then used in the subsequent steps of the process.
4.3.3   |   Trend Analysis
The trend analysis applied LLMs to identify the most relevant
driving forces related to the focal issue. Cross-­impact analysis
and clustering algorithms were used to identify high-­level fac-
tors, which were subsequently validated by the SMEs. This ap-
proach replaced traditional manual clustering of driving forces
FIGURE 1    |    Design science research methodology.


## Page 6

304
Public Administration Review, 2026
by assessing the impact and uncertainty of high-­level factors
with LLMs and reducing bias through SME validation.
4.3.4   |   SME Validation
Collaboration and validation by human experts were central
to the pilot project. Although the FFT oversaw and conducted
internal validation at every step, validation by SMEs was the
primary collaboration point of the methodology. Workshops
with key stakeholders and SMEs (both internal and external)
validated previous results and introduced driving forces and
factors that had not been considered. This process focused
costly human resources on shorter, more efficient, and ef-
fective engagements, combining artificial and human intelli-
gence to mitigate biases.
4.3.5   |   Scenario Creation
Scenarios were created using generative AI based on the identi-
fied high-­level factors and plausible future developments of the
focal issue (see Supporting Information: Appendix B). The gen-
erative AI prompts used for scenario generation were the most
iterative part of the process and underwent reworking to ensure
they were fit for purpose.
4.3.6   |   Strategizing
The generated scenarios were used in a workshop on digital
trust by relevant government departments and working groups
to inform strategic discussions. The workshop also played a key
role in building confidence in the use of LLMs for strategic fore-
sight. By working through the scenarios, teams were able to test
assumptions, identify blind spots, and engage with uncertainty
in a structured and creative way. This process helped normal-
ize the use of AI tools in foresight activities and demonstrated
their value.
To ensure that each step in this process was technically sound
and fit-­for-­purpose, the FFT engaged in multiple design
iterations that are described in the next section. These iterations
involved close collaboration with a dedicated EET to refine the
underlying analytics, improve prompt design, and validate out-
puts. The iterative approach allowed for continuous learning
and adjustment.
4.4   |   Design Iterations
To design and validate the pilot, the FFT and EET held four it-
eration sessions of one to 2 h, conducted in person and online
(Figures  2 and 3). Two rounds of iterations took place before
the workshop to evaluate the effectiveness of the tool (see the
next section) and two afterwards. The EET team gave feedback,
provided technical advice for ongoing refinement, and reviewed
improvements. Each interaction was followed by internal dis-
cussions and emails.
In the initial iteration (Figure 2), the focus was on refining the
knowledge base of the driving forces, experimenting with the
clustering algorithm, and refining the analytics used for assess-
ing impact and uncertainty. The FFT and the EET worked to
improve the LLM's ability to categorize driving forces and gen-
erate meaningful insights. This stage lay a robust foundation for
subsequent refinements by ensuring that the underlying data
processing mechanisms were accurate and reliable. It also in-
volved a thorough examination of the quality of driving forces
and clusters to ensure they accurately represented the data and
could be used effectively in strategic foresight activities.
One of the issues that emerged in this iteration was a lack of
source documents with a specific focus on Queensland. As some
of the FFT members mentioned, “there's only limited good doc-
uments about the future of Queensland alone.” As a result, more
local and context-­specific driving forces were not present. It was
decided to involve SMEs in this stage, so their unique insights
into local driving forces relevant to Queensland were captured.
The second iteration (Figure 2) covered the same topics as the
first, with an added focus on prompt engineering, to enhance
the quality of extreme outcomes within each cluster. This
refinement aimed to improve the LLM's ability to generate
FIGURE 2    |    Design iterations before the workshop.


## Page 7

305
Public Administration Review, 2026
scenarios that considered a broader range of possibilities, thus
providing more comprehensive insights into potential future
developments.
In this second iteration, the FFT spent much of its time iterating
and testing prompts. In this exercise, it was noticed that each
prompt needed to be meticulously crafted to yield an accurate
output. According to the FFT's architecture and modeling lead,
they had to “change the prompt at very micro levels.” This com-
plexity was compounded by the need to manage multiple chain-­
of-­thought prompts. To address this, the project implemented
a control mechanism to facilitate the task of testing and com-
paring multiple prompt versions systematically and increase
robustness.
The architecture and modeling lead also mentioned that “the
more you are trying to do in a single prompt, the more variation
there is, and it's kind of harder to trace back and explain why
you got a certain result.” The solution for this was to break down
tasks into discrete steps, each with its own specific prompt. This
approach helped manage the generative nature of AI, which
often produces varied results with different prompts.
Finally, experimenting with different LLMs such as ChatGPT
3.5, ChatGPT 4.0, and Claude was important, because each LLM
demonstrated unique strengths and weaknesses depending on
the task. By leveraging the distinct capabilities of each LLM and
incorporating them in different parts of the architecture, it was
possible to address specific needs and optimize the overall pro-
cess. For each LLM, the FFT also monitored and tried different
response variability settings to balance the need for precision
and creativity in AI outputs for scenario creation. For example,
for tasks requiring high accuracy and consistency, such as ex-
tracting driving forces from source documents, the response
settings were configured to minimize variability and ensure
precise results. Conversely, to generate creative scenarios, the
response settings were configured to allow for more open-­ended
and diverse responses.
The second iteration ended once the tool could consistently
generate quality extreme outcomes of driving forces within
each cluster and overall cluster outcomes. After this phase, the
prototype was ready for a workshop with SMEs, which is de-
tailed in the next section.
In the third iteration (Figure 3), after the workshop, the tool's
effectiveness was evaluated. While the focus shifted to prompt
engineering for scenario writing, the knowledge base of the
driving forces continued to be refined. The goal was to enhance
the balance between specificity and creativity in the generated
scenarios. The team worked on the prompts to ensure that the
scenarios were sufficiently detailed and plausible while still al-
lowing for creative and unexpected outcomes. This iteration en-
sured that the tool could produce four future scenarios that were
not only consistent but also insightful for strategic decision-­
making. A new process for scenario generation proposed by the
EET was studied and evaluated but ultimately the FFT decided
to keep the process similar to the original proposal, primarily
due to time constraints within the trial.
The fourth iteration was about extending the coverage of the
driving forces within the knowledge base. This was achieved by
further refining prompt engineering, with a focus on ensuring
that the tool could capture a wide range of driving forces rele-
vant to the focal issue. The aim was to create an extensive data-
base that could support diverse and robust scenario generation.
An issue that was resolved in this iteration related to the dupli-
cation of driving forces. Because the LLM extracted the driv-
ing forces from multiple source documents, duplication was a
normal occurrence. However, de-­duplication, or the removal of
duplicates, is not easy because some driving forces might be dif-
ferent but refer to the same underlying concept. To address this,
the FFT devised a new method involving taxonomy. By catego-
rizing each item, they ensured that similar items were grouped
together, simplifying the de-­duplication process.
The taxonomy highlighted biases in the FFT's data, with a
stronger focus on economic driving forces rather than social
ones. Therefore, they also used the taxonomy to identify areas
with more or fewer driving forces and adjusted their document
sourcing accordingly. This not only helped to balance the data
but also provided complete traceability for the driving forces be-
hind each document. The fourth iteration also included a quality
FIGURE 3    |    Design iterations after the workshop.


## Page 8

306
Public Administration Review, 2026
check of the driving forces to ensure that they were well repre-
sented in the knowledge base and could be used effectively in
the scenario creation process.
4.5   |   Evaluating the Effectiveness of the Tool
To evaluate the methodology and scenarios, a two-­hour work-
shop was conducted with both teams and 47 potential users from
the Queensland Government in a hybrid format. These partici-
pants were identified as key experts or stakeholders for this ini-
tiative. The main objective was for these stakeholders to validate
and provide insights into the development of the scenarios.
The workshop focused on the future of digital trust up to 2032
and its potential implications for policy and strategy develop-
ment in the Queensland Government. Before presenting the re-
sults, each participant was asked to write down two to three key
driving forces related to digital trust in government from their
perspective, with a focus on the Queensland Government. Next,
the results of the clustering and high-­level factors from the stra-
tegic foresight tool were presented and participants were then
asked to use stickers to vote on the impact and uncertainty of
each high-­level factor.
The preliminary scenarios were then presented for feedback.
Participants were split into tables and online virtual groups to
discuss the scenarios and list feedback points. Each group then
presented their feedback to the wider group. Broader discussions
were held to clarify questions such as the following: What other
elements of the future scenarios would be useful for your work?
What details or specific perspectives could enrich the scenarios?
How could you use these scenarios in your work?
The evaluation highlighted several important areas for improve-
ment. Participants raised concerns about the choice of source
documents, noting that many were from consulting firms and
private sector organizations, which might have their own agen-
das. This led to questions about whether these sources could bias
the results and whether more scholarly or non-­profit sources
should be included to provide a balanced perspective. One im-
portant suggestion was to make the knowledge base more reus-
able and complete by including a broader range of documents
and focusing on key issues relevant to the state government or
public organizations. To address these concerns, efforts were
made to diversify the sources and ensure broader coverage and
an unbiased approach.
There was also feedback on how the initial framing and con-
text provided in the prompts could influence the outcomes, sug-
gesting that missing important contextual information early on
might impact the final scenarios. A suggested solution was to
detail all the driving forces in the knowledge base according to
specific criteria to better understand their influence. Another
recommendation was to use LLMs to classify the driving forces,
allowing for more insightful and meaningful classifications.
Some parts of the process were identified for re-­evaluation. It
was suggested that some steps could be eliminated or stream-
lined using LLMs. For instance, it was mentioned that the focal
issue entered and exited the process at several points. Another
proposal was to enhance exploration of extreme outcomes across
multiple dimensions with the LLMs instead of showing positive
versus negative extreme outcomes. For example, in a cluster
on “trustworthy sources,” considering who was trusted (estab-
lished sources like governments versus new digital platforms)
or legitimacy across societal levels or temporality (static versus
dynamic) could provide richer insights.
The evaluation also emphasized the importance of providing
sources and confidence levels to support impact and uncer-
tainty analyses, highlighting the most influential driving forces.
Moreover, it was suggested that scenarios could be improved by
adding temporal detail to show how driving forces within clus-
ters evolved over time and to better reflect the user's perspec-
tive. To deepen insights, it was suggested that LLMs should be
prompted to consider specific personas and constraints. Finally,
further testing of other focal issues was required to ensure that
the knowledge base had sufficient coverage and that the existing
prompt structures were reusable.
The pilot's effectiveness was further supported by some quanti-
tative outcomes, summarized in Table 2, which show improve-
ments in scale, efficiency, cost, and quality assurance achieved
using LLMs for strategic foresight.
4.6   |   Communicating the Tool
Communicating the tool to key stakeholders was a crucial step
in the project, aimed at both sharing the prototype and gath-
ering valuable feedback to refine the tool further. A dedicated
workshop was organized, bringing together 38 members of the
Futures and Foresight network, including SMEs, policymakers,
and other relevant stakeholders. The primary goal of this work-
shop was to present the prototype, ensuring that participants not
only understood the technical aspects of the generative AI tool
but also appreciated its potential impact on strategic foresight.
The workshop provided a platform for open dialogue and col-
laboration, where participants could express their views, ask
questions, and provide feedback on the prototype. During the
workshop, the prototype was presented in detail, with the FFT
team providing an overview of the design iterations and the ra-
tionale behind key decisions. The workshop demonstrated how
the integration of AI with human expertise could lead to more
robust and dynamic strategic planning.
Participants were encouraged to provide feedback on the pro-
totype, which was later used to refine the final version. In ad-
dition, the workshop aimed to build trust among the SMEs by
demonstrating the potential of generative AI to complement and
enhance their expertise rather than replacing it. By involving
the SMEs in this journey, the workshop sought to align their ex-
pectations with the capabilities of the tool, ensuring a smooth
transition into its practical application in strategic foresight
initiatives.
As a result of this process, from identifying the problem to
communicating the tool, the Queensland Government decided
to support an additional project, partnering with another gov-
ernment agency, to develop scenarios for the agency's use in


## Page 9

307
Public Administration Review, 2026
strategy and policy and to build on and refine the methodology.
The FFT decision to involve its leadership in the process and the
clear communication of progress and findings were crucial to
gaining their endorsement and commitment to expanding the
pilot project's scope.
5   |   Discussion
Collaboration with the Futures and Foresight team (FFT) con-
cluded after refining and scaling the tool, identifying new use
cases, and preparing for the next version's release. Several key
points were identified in human–machine collaboration efforts
for designing strategies in public organizations. These points
were used to develop key recommendations for public sector
practitioners when using LLMs for strategic foresight (Table 3).
First, LLMs have strong potential to make strategic foresight en-
gagements more effective and efficient. However, this must be
done carefully. As the design iterations progressed, it became
clear that while LLMs are very effective at automating data
processing, clustering and scenario generation, human exper-
tise is still needed for validating outputs and providing context-­
specific insights.
In this context, the key point was to determine when and how
humans should be involved in the foresight process. Strategic
decisions must balance “human-­in-­the-­loop” interactions,
where experts actively intervene, with “human-­over-­the-­loop”
supervision, where monitoring is enough. For instance, the
FFT involved SMEs in validating the driving forces and high-­
level factors identified by LLMs, ensuring that the base used for
scenario creation was accurate and, at the end, ensuring the sce-
narios were relevant. In contrast, data processing and clustering
relied on LLMs autonomy with human-­over-­the-­loop monitor-
ing, which reduced human workload. This balance ensured that
the foresight process benefited from the efficiency and scalabil-
ity of LLMs while retaining the nuanced understanding and
oversight that only human experts could provide.
Second, the iterative design science approach taken in this proj-
ect was another key insight. Each iteration involved a rigorous
process of experimenting with prompts and scenarios, allowing
for finetuning of the LLM prompts, verification of output qual-
ity, and incorporation of feedback from SMEs. These multiple
rounds of refinement and feedback not only led to a gradual
improvement and robustness in the quality of the scenarios
produced but also enhanced confidence in human–machine col-
laboration and in LLM's capabilities for strategic foresight.
For example, experimentation with diverse LLMs, such as
ChatGPT versions, Gemini, and Claude, showcased their vary-
ing strengths for specific tasks. No single model was optimal
for all tasks, but testing could align models to specific strategic
needs. Finetuning the response variability settings also rein-
forced that LLMs could be tailored to meet the diverse demands
of strategic foresight. Finally, the iterative design incorporated
a control mechanism that compared outputs across prompt
versions, pinpointing anomalies and optimizing results. By
establishing a clear benchmark, the FFT was able to measure
improvements in efficiency, creativity, and scenario quality for
each iteration. This transparent, traceable process provided ev-
idence that LLM's variability could be managed effectively, in-
creasing the trust of the FFT in the tool.
TABLE 2    |    Outcomes and implications for practice.
Evaluation dimension
Outcomes
Implications for practice
Data processing scale
The automated extraction of driving forces from
meta-­analysis documents was reduced by 95.2%
through AI-­driven semantic deduplication,
resulting in a set of unique themes.
Enables unprecedented
processing capacity compared
to manual methods.
Efficiency (staff hours)
An estimated 60%–70% reduction in staff hours
was achieved across scenario preparation and
creation, including upstream activities such
as data collection, analysis, and synthesis.
Considerable reduction in labor
resources and associated overheads.
Cost performance
Internal delivery costs of scenarios reduced
by approximately 60%, primarily due to
decreased staff hours and reduced reliance
on external consulting services.
Substantial budget savings and
improved return on investment
in foresight activities.
Quality assurance and validation
SMEs involved in validating AI outputs and
ensuring high quality of generated insights.
Maintains analytical rigor and
contextual accuracy despite
high levels of automation.
Scenario generation capacity
The scenario production capability doubled,
generating eight distinct scenarios, compared to
traditional practice of typically four scenarios.
Provides greater diversity and
depth of strategic insights,
enhancing preparedness.
Timeframe of analysis
Completed comprehensive analysis of thousands of
pages of policy documents within weeks instead of
traditional timeframes spanning several months.
Accelerates foresight cycles,
enabling timely strategic
decision-­making.


## Page 10

308
Public Administration Review, 2026
By systematically improving adaptability and accuracy, ad-
dressing inconsistencies, and generating creative, relevant
outputs, the iterative process fostered confidence in LLMs as
a reliable collaborator. The iterative design science approach
was, thus, a form of capability-­building, developing not only
human–machine technical capabilities but also the organiza-
tional capabilities to harness and direct LLM-­driven foresight
tools effectively. Iterative processes should be institutionalized
as mechanisms not only for improvement but also for confidence
and capability-­building in human–machine collaborations, en-
suring the reliability and scalability of LLM applications in pub-
lic management.
Third, ensuring transparency and accountability proved im-
portant for building trust in AI-­driven processes. For that, the
leadership and the SMEs were always kept in the loop and in-
formed. Furthermore, the stakeholders were brought along on the
development journey through the workshops. By building check-­in
points to involve the user community and ensuring clarity at each
stage of development, a sense of ownership and trust was created.
Stakeholder workshops and SME validation addressed concerns
over biases in source documents, particularly the overrepresen-
tation of economic perspectives over social drivers. By diversify-
ing source material to balance datasets, the FFT set a precedent
for incorporating fairness and inclusivity into AI systems. This
transparency not only built trust among users but also ensured
that outputs of the project were credible and actionable.
Fourth, traceability was critical to the process. The FFT used
a taxonomy system to trace AI-­suggested driving forces back to
their document sources. Ensuring that the outputs of the fore-
sight tool were explainable and that the processes leading to those
outputs could be traced were essential for maintaining trust and
TABLE 3    |    Recommendations for practitioners.
Recommendation
Description/rationale
Clearly define the focal issue and time
horizon
Identify a strategic challenge relevant to the organization and specify a meaningful
time frame for scenario exploration (e.g., 5–10 years). A clearly defined focus
ensures that the foresight exercise remains relevant and actionable.
Establish a structured foresight
process
Adopt or customize a structured strategic foresight method (e.g., Cairns
and Wright 2017) clearly outlining stages like scanning, analysis,
scenario development, and strategizing. Having a structured, repeatable
approach facilitates consistency, transparency, and accountability.
Select appropriate AI tools and
platforms
Choose an AI platform capable of integrating multiple generative AI
models (e.g., ChatGPT, Claude, and Gemini) within a single interface,
ensuring it meets the organization's security and privacy standards.
Platforms such as Relevance AI simplify the process of testing, comparing,
and applying different AI models efficiently and securely.
Define clear roles for human–machine
collaboration
Explicitly map out the responsibilities and interactions between human experts
and AI tools at each stage of the foresight process. Clearly defined roles ensure
effective integration of AI capabilities with human expertise, maintaining
quality, reducing biases, and facilitating informed decision-­making.
Pilot and iterate the foresight process
Conduct multiple small-­scale iterations to refine the foresight process,
AI prompts, analytical techniques, and scenario outputs. An iterative
approach allows organizations to rapidly identify and resolve issues,
enhance effectiveness, and build internal capability before scaling up.
Leverage AI for broad and creative
scenario generation
Use generative AI to explore a wider range of imaginative and diverse scenarios.
AI-­driven creative scenario development helps uncover unconventional risks, novel
opportunities, and challenges traditional assumptions, enriching strategic thinking.
Engage SMEs for validation and
contextualization
Actively involve subject matter experts (SMEs) in workshops and iterative
validations to critically assess and contextualize AI-­generated outputs. Human
validation enhances credibility, ensures scenarios align with organizational
realities, and mitigates the risk of relying excessively on automated outputs.
Use Scenarios to Inform Strategic
Conversations
Integrate the developed scenarios into strategic discussions with relevant teams
and working groups to build confidence in the foresight process and the use of
AI. Applying scenarios in real-­world contexts reinforces their value, promotes
organizational learning, and supports practical policy and strategy decisions.
Document insights and learnings
Continuously document successes, failures, and lessons learned throughout the
foresight process, creating a knowledge base for future initiatives. Documentation
encourages continuous improvement, institutionalizes foresight capabilities,
and provides guidance for subsequent strategic foresight activities.


## Page 11

309
Public Administration Review, 2026
accountability. This is particularly important in government con-
texts where decision-­making must be transparent and justifiable.
Fifth, a notable aspect of the project was the entrepreneurial
spirit demonstrated by the FFT. They acted as institutional en-
trepreneurs in the state government, overcoming traditional
bureaucratic barriers to introduce innovative foresight meth-
odologies. Their willingness to embrace uncertainty, leverage
emerging technologies, and build a coalition of supportive stake-
holders proved essential to the project's momentum. Indeed, it
was essential for the transition from a pilot project to a scalable
foresight tool, allied with a strong leadership engagement, to
showcase the utility of the tool through clear demonstrations
and aligning goals with strategic priorities.
Finally, in the generation of scenarios, one must be prepared for
LLM hallucinations. Initially, this was mitigated by employing
strict prompt structures and control mechanisms. However, it
was found that sometimes LLM hallucinations could bring the
creativity needed for imaginative and engaging scenarios (see
Supporting Information: Appendix C). In this regard, it is im-
portant to recognize that overly restrictive prompts could stifle
this. By finetuning prompts and response variability settings,
the FFT struck a balance between accuracy and creative ex-
ploration, ensuring scenarios were not only plausible but also
thought-­provoking and relevant for strategic foresight.
This case highlights the transformative potential of LLMs in
conducting strategic foresight. Traditional foresight methods
often suffer from time constraints, resource limitations and nar-
row perspectives. By integrating LLMs, the FFT expanded the
scope of scenario creation, processed vast datasets, and ensured
adaptability in rapidly evolving contexts. The foresight tool
bridged gaps in efficiency, scalability, and versatility, demon-
strating how LLMs can address wicked problems and enhance
strategic design for the public sector.
6   |   Future Research and Conclusions
As LLMs are integrated into strategic foresight, several areas
for future research emerge to improve the effectiveness and re-
liability of these tools. One area is the need to test prototypes
across a wider range of projects and contexts. While initial tri-
als have shown promise, particularly in the public sector with
projects such as this one, further validation across different in-
dustries and government agencies is required. This would en-
sure the robustness and adaptability of LLM-­driven foresight
tools in different environments and with different strategic
requirements.
Another promising area for research is the exploration of LLM
hallucinations as a tool for deliberately generating creative and
unconventional scenarios. Typically viewed as a limitation, the
ability of LLMs to produce hallucinations could be harnessed to
push the boundaries of traditional scenario planning. By explor-
ing how these creative outputs can be systematically incorpo-
rated into strategic foresight, organizations could develop more
innovative and diverse future scenarios that challenge existing
assumptions and stimulate new ways of thinking.
Transparency is one of the main contributors to trust in human–
machine collaborations and should be prioritized in the public
sector. In this regard, future research should develop methods
to enhance the transparency and explainability of LLMs used
in strategic foresight and in general. This includes creating
frameworks for documenting and communicating the decision-­
making processes of LLMs, ensuring that stakeholders can
understand and trust the outputs. Exploring ways to involve
stakeholders in the design process, such as through participa-
tory design and co-­creation, could help address transparency
concerns and build confidence in LLMs.
Research should also explore how LLMs can enhance the pub-
lic sector's ability to uphold and create public value through
strategic foresight. This involves exploring how human–ma-
chine collaboration can help proactively identify and priori-
tize emerging public needs and ensure that public services are
aligned with the evolving values and future expectations of the
community.
Finally, the changing landscape of elections poses a complex
challenge to strategic foresight for the public sector. Future re-
search should also focus on how LLMs can take that into ac-
count, including shifts in public sentiment and misinformation
campaigns, when generating possible future scenarios.
Conflicts of Interest
The authors declare no conflicts of interest.
Endnotes
1	Generative AI, or GenAI, refers to AI systems capable of producing orig-
inal content, such as text, images, video, audio, or software code, in re-
sponse to user prompts or instructions (Strycker and Scapicchio 2024),
while an LLM is a class of generative AI model specifically trained to
understand and generate human language. Examples include OpenAI's
Chat GPT and Google's Gemini. Our project focuses on leveraging LLMs.
References
Cairns, G., and G. Wright. 2017. Scenario Thinking: Preparing Your
Organization for the Future in an Unpredictable World. Springer
International Publishing.
Choo, E., and A. Fergnani. 2022. “The Adoption and Institutionalization
of Governmental Foresight Practices in Singapore.” Foresight 24, no. 1:
19–36. https://​doi.​org/​10.​1108/​FS-­​10-­​2020-­​0103.
Chui, M., R. Roberts, and L. Yee. 2022. Generative AI is Here: How
Tools Like ChatGPT Could Change Your Business. Quantum Black AI
by McKinsey. https://​www.​mckin​sey.​com/​capab​iliti​es/​quant​umbla​ck/​
our-­​insig​hts/​gener​ative​-­​ai-­​is-­​here-­​howto​ols-­​like-­​chatg​pt-­​could​-­​chang​
e-­​your-­​business.
Coates, J. F. 2010. “The Future of Foresight—A US Perspective.”
Technological Forecasting and Social Change 77, no. 9: 1428–1437.
https://​doi.​org/​10.​1016/j.​techf​ore.​2010.​07.​009.
Delaney, K., and L. Osborne. 2013. “Public Sector Horizon Scanning—
Stocktake of the Australasian Joint Agencies Scanning Network.”
Journal of Futures Studies 17, no. 4: 55–70.
Dufva, M., T. Könnölä, and R. Koivisto. 2015. “Multi-­Layered Foresight:
Lessons From Regional Foresight in Chile.” Futures 73: 100–111. https://​
doi.​org/​10.​1016/j.​futur​es.​2015.​08.​010.


## Page 12

310
Public Administration Review, 2026
Fatima, S., K. C. Desouza, C. Buck, and E. Fielt. 2022. “Public AI Canvas
for AI-­Enabled Public Value: A Design Science Approach.” Government
Information Quarterly 39, no. 4: 101722. https://​doi.​org/​10.​1016/j.​giq.​
2022.​101722.
Finkenstadt, D. J., J. Sotiriadis, P. Guinto, and T. Eapen. 2024.
“Contingency Scenario Planning Using Generative AI.” California
Management Review Insights. https://​cmr.​berke​ley.​edu/​2024/​01/​conti​
ngenc​y-­​scena​rio-­​plann​ing-­​using​-­​gener​ative​-­​ai/​.
Greenblott, J. M., T. O'Farrell, R. Olson, and B. Burchard. 2019.
“Strategic Foresight in the Federal Government: A Survey of Methods,
Resources, and Institutional Arrangements.” World Futures Review 11,
no. 3: 245–266. https://​doi.​org/​10.​1177/​19467​56718​814908.
Habegger, B. 2010. “Strategic Foresight in Public Policy: Reviewing the
Experiences of the UK, Singapore, and The Netherlands.” Futures 42,
no. 1: 49–58. https://​doi.​org/​10.​1016/j.​futur​es.​2009.​08.​002.
Hartigan, W., and A. Horobin. 2023. “Policy Fit for the Future: The
Australian Government Futures Primer.” National Security College.
https://​nsc.​anu.​edu.​au/​conte​nt-­​centre/​resea​rch/​polic​y-­​fit-­​futur​e-­​austr​
alian​-­​gover​nment​-­​futur​es-­​primer.
Holmström, J., and N. Carroll. 2024. “How Organizations Can Innovate
With Generative AI.” Business Horizons 68, no. 5: 559–573. https://​doi.​
org/​10.​1016/j.​bushor.​2024.​02.​010.
Horizons. 2024. “About Us.” https://​horiz​ons.​servi​ce.​canada.​ca/​en/​
about​-­​us/​index.​shtml#​history.
Kim, H., S.-­J. Ahn, and W.-­S. Jung. 2019. “Horizon Scanning in Policy
Research Database With a Probabilistic Topic Model.” Technological
Forecasting and Social Change 146: 588–594. https://​doi.​org/​10.​1016/j.​
techf​ore.​2018.​02.​007.
Leslie, D., and A. M. Perini. 2024. “Future Shock: Generative AI and the
International AI Policy and Governance Crisis.” AI Policy & Governance
24, no. 1: 1–15.
Linstone, H. A. 2010. “On Terminology.” Technological Forecasting and
Social Change 9, no. 77: 1426–1427.
Meier, K. J. 2005. “Public Administration and the Myth of Positivism:
The Antichrist's View.” Administrative Theory & Praxis 27, no. 4:
650–668.
Monteiro, B., and R. Dal Borgo. 2023. Supporting Decision Making with
Strategic Foresight: An Emerging Framework for Proactive and Prospective
Governments. OECD. https://​www.​oecd-­​ilibr​ary.​org/​gover​nance/​suppo​
rting​-­​decis​ion-­​makin​g-­​with-­​strat​egic-­​fores​ight_​1d78c​791-­​en.
Normoyle, K. 2023. The NSW Trend Atlas: Planning for the Unknown.
NSW Government. https://​www.​digit​al.​nsw.​gov.​au/​artic​le/​nsw-­​trend​
-­​atlas​-­​plann​ing-­​for-­​unknown.
Patton, M. Q. 2022. Qualitative Research & Evaluation Methods. 11th ed.
SAGE Publications Ltd.
Peffers, K., T. Tuunanen, M. A. Rothenberger, and S. Chatterjee. 2007.
“A Design Science Research Methodology for Information Systems
Research.” Journal of Management Information Systems 24, no. 3: 45–77.
https://​doi.​org/​10.​2753/​MIS07​42-­​12222​40302​.
Pólvora, A., and S. Nascimento. 2021. “Foresight and Design Fictions Meet
at a Policy Lab: An Experimentation Approach in Public Sector Innovation.”
Futures 128: 102709. https://​doi.​org/​10.​1016/j.​futur​es.​2021.​102709.
Puerta Pereira, J., P. van der Duin, V. Peter, et al. 2025. Evolution and/or
Disruption? Designing the Next Framework Programme for Research and
Innovation. European Parliamentary Research Service. https://​www.​
europ​arl.​europa.​eu/​stoa/​en/​docum​ent/​EPRS_​STU(2025)​765780.
RAND. 2024. “A Brief History of RAND.” https://​www.​rand.​org/​about/​
histo​ry.​html.
Ritcher, A. 2024. “Navigating Generative AI in Government. IBM
Center for The Business of Government.” https://​www.​busin​essof​gover​
nment.​org/​report/​navig​ating​-­​gener​ative​-­​ai-­​gover​nment​.
Romme, A. G. L., and A. Meijer. 2020. “Applying Design Science in
Public Policy and Administration Research.” Policy & Politics 48, no. 1:
149–165. https://​doi.​org/​10.​1332/​03055​7319X​15613​69998​1234.
Schmidt, J. M. 2015. “Policy, Planning, Intelligence and Foresight in
Government Organizations.” Foresight 17, no. 5: 489–511. https://​doi.​
org/​10.​1108/​FS-­​12-­​2014-­​0081.
Schmidthuber, L., and M. Wiener. 2021. “Aiming for a Sustainable
Future: Conceptualizing Public Open Foresight.” In Sustainable Public
Management, edited by L. Schmidthuber and M. Wiener, 84–109.
Routledge.
Shangraw, R. F., Jr., and M. M. Crow. 1989. “Public Administration as a
Design Science.” Public Administration Review 49, no. 2: 153–160.
Strycker, C., and M. Scapicchio. 2024. What is Generative AI? IBM.
https://​www.​ibm.​com/​think/​topics/​gener​ative​-­​ai.
van Buuren, A., J. M. Lewis, B. G. Peters, and W. Voorberg. 2020.
“Improving Public Policy and Administration: Exploring the Potential
of Design.” Policy & Politics 48, no. 1: 3–19. https://​doi.​org/​10.​1332/​
03055​7319X​15579​23042​0063.
Walker, R. M. 2011. “Globalized Public Management: An Interdisciplinary
Design Science?” Journal of Public Administration Research and Theory
21: i53–i59. https://​doi.​org/​10.​1093/​jopart/​muq064.
Wilner, A., and M. Roy. 2020. “Canada's Emerging Foresight Landscape:
Observations and Lessons.” Foresight 22, no. 5/6: 551–562. https://​doi.​
org/​10.​1108/​FS-­​03-­​2020-­​0027.
World Economic Forum. 2025. “Digital Trust.” https://​initi​atives.​wefor​
um.​org/​digit​al-­​trust/​home.
Supporting Information
Additional supporting information can be found online in the
Supporting Information section. Data S1: Supporting Information.
Biographies
Marc E. B. Picavet is a postdoctoral fellow in digital innovation
and governance at the Queensland University of Technology (QUT),
Australia. He holds a PhD in Public Administration and Government
from Fundação Getulio Vargas (Brazil) with a focus on innovation and
local governments. He has contributed to research on digital transfor-
mation and the use of artificial intelligence in local governments, re-
sulting in reports and articles for Brookings and the IBM Center for The
Business of Government.
Peter Maroni is a seasoned policy and strategy leader with experience
in futures thinking, strategic foresight, and portfolio management in a
variety of roles across Queensland Government. Peter has a passion for
building innovative capabilities that leverage emerging technologies and
high performing teams, supporting Queensland to harness opportunities
and prepare for challenges in a rapidly evolving world.
Amardeep Sandhu is a senior executive with over 20 years of experience
leading evidence-­based organizational transformations in Australasia.
He specializes in applying AI, advanced analytics, and computational
models for strategic foresight and performance improvement across pub-
lic and private sectors. His qualifications include an MBA, a Master's in
Computational & Behavioral Economics, and postgraduate studies in
Cognitive Neuroscience. He is a Fellow of the Royal Society of Arts (FRSA).
Kevin C. Desouza is Professor of Business, Technology and Strategy
in the School of Management at QUT Business School, Queensland
University of Technology, and a Nonresident Senior Fellow at the
Brookings Institution. He is the author or editor of 10 books and has
published more than 150 peer-­reviewed articles across disciplines in-
cluding information systems, public administration, political science,
technology management, and urban affairs. Additional information is
available at: http://www.kevindesouza.net.

