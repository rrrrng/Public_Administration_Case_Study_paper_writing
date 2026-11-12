# qy_Re-Imagining the Epistemic Possibilities of GPT for Public Administration

## Page 1

Public Administration Review, 2026; 0:1–14
https://doi.org/10.1111/puar.70098
1
Public Administration Review
RESEARCH ARTICLE
OPEN ACCESS
Re-­Imagining the Epistemic Possibilities of GPT for Public
Administration Research in Competitive Settings
Yanto Chandra
|  Jianxiang Tan
Department of Public and International Affairs, Laboratory for Public Management and Policy (LAMP), Technology, Policy and Law Laboratory, City
University of Hong Kong, Hong Kong SAR, China
Correspondence: Yanto Chandra (ychandra@cityu.edu.hk)
Received: 1 September 2025  |  Revised: 3 February 2026  |  Accepted: 3 February 2026
Keywords: AI | GPT | public sector innovation
ABSTRACT
Innovation is desirable for the public sector. Yet understanding what and how some innovation projects survive and thrive in a
competitive landscape—or public sector innovation—is often challenging. The challenges not only rest in the invisibility of the
features of an innovation to human eyes but also in the lack of their accessibility for analysis. This study showcases a methodolog-
ical framework using a generative pre-­trained transformer (GPT) for scale development and synthetic data generation to measure,
predict, retrodict, and calibrate innovation outcomes using real-­world and synthetic data and a human-­in-­the-­loop process. This
study demonstrates the epistemic gains of the framework in predicting and manipulating competitive texts to simulate the past,
present, and possibly the future. The approach offers avenues for future research on a wide range of competitive phenomena
using large-­scale text analysis across the social sciences.
1   |   Introduction
For decades, public administration (PA) scholars around the
world have shown interest in innovation in the public sector
with the aim of improving the quality of governance and citi-
zens' wellbeing—a domain known as public sector innovation
(Andrews et al. 2021; Cinar et al. 2024; Criado et al. 2025; De
Vries et al. 2016; Demircioglu 2024; Zambrano-­Gutiérrez and de
Puppim Oliveira 2022). Be it a new mission, a new service to
new administrative procedures, public sector innovation is well
celebrated by practitioners and scholars alike. While there is no
doubt that public sector innovation is beneficial to all stakehold-
ers (e.g., government, citizens, civil society, businesses), the hard
question often rests on what (i.e., the features or characteristics)
and how (i.e., the linguistic articulation and expression) an in-
novation becomes successful. With limited public sector inno-
vation data available for analyses, and the majority of such data
are in “textual” format, scholars in this space are hard pressed to
come up with innovative ways to study public sector innovation.
Essentially, innovation in the public sector rests on our epis-
temic abilities to study “textual data” to tease out the great from
mediocre ideas and to discern the nature of the (time, space, cul-
ture, institution) context where these ideas compete to be among
the best. Like pharmaceutical research that aims to unravel the
few chemical compounds that offer the best cure out of millions
of compounds (Terwiesch and Ulrich 2009) or technical stan-
dards competing to be the dominant design (Suarez 2004), PA
scholars are not doing a dissimilar thing except that our level of
analysis lies in the “written” ideas and solutions (than chemical
properties) that create value for the public.
Innovation in textual format often contains hidden markers that
are not easily visible to human eyes, and we cannot yet know
its promise until some form of assessment takes place that pit
one innovation against others. We refer to these innovation as
a class of ideas or solutions or policies that contain “texts with
ex-­ante unknown (winner or loser) outcomes.” The passion in
working with textual data with ex-­ante unknown (winning
This is an open access article under the terms of the Creative Commons Attribution License, which permits use, distribution and reproduction in any medium,
provided the original work is properly cited.
© 2026 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.


## Page 2

2
Public Administration Review, 2026
or losing) outcomes in the field of PA has existed for many
years—from studies of policy speeches to infer election results
(Laver et al. 2006), citizens' complaints to predict government
responses (Wang et al. 2025), public procurement contracts to
detect the corruption risks (Fazekas et al. 2016), to policy de-
bate statements to predict advocacy outcomes (Struthers and
Ritzler 2024). Research using this type of data is exciting be-
cause it captures a natural experiment of some past behavior or
processes or mechanisms that offer a glimpse of what was pre-
ferred or chosen (or not) by their stakeholders based on certain
qualities at certain time and space.
What makes these “texts” special in the context of public sector
innovation is the competitive process that they must go through
in competing against other texts and the sheer number of actors
who are involved in the competition—from organizer, funder,
to evaluator—leading to a state of (win vs. lose or funded vs.
unfunded) outcomes. In other words, these public sector inno-
vation texts are not merely (or ordinary) data or “text as data”
(Grimmer and Stewart 2013; Isoaho et al. 2021) nor “open inno-
vation” data (Mergel and Desouza 2013) but essentially evidence
of tournaments (or contests or prizes)—labeled here as “text as
tournaments” or “competitive texts” where a myriad of ideas or
solutions in textual forms compete to be the best (Liotard and
Revest  2018; Terwiesch and Ulrich  2009; Williams  2012) to
achieve certain goals. Competitive texts offer rich, thick, and
large data points amenable to theory building and testing, as
well as descriptive analysis to make better policies and improve
governance.
The genesis of this article was the rise of generative pre-­trained
transformers (GPT) in late 2022, which triggered our experi-
mentation into its uses for advancing “how we can know” about
PA and policy research. GPT marked a new turning point for
PA scholarship as it offers unprecedented epistemic possibilities
to study public sector innovation from the lens of “competitive
texts” in tournaments. Our review of the literature suggests
a dearth of studies in this domain that use a competitive lens
and GPT.
Far beyond “statistical parrots” (Bender et al. 2021) or “syntactic
engine” (Floridi 2023b) that stitch together sequences of linguis-
tic forms without knowing their meaning, GPT offers new ways
of acquiring, creating, augmenting, using, and synthesizing
knowledge—the epistemic possibilities (Alvarado 2023). In fact,
GPT, and many types of artificial intelligence (AI) (Chandra
and Feng  2025), have opened a new scientific infrastruc-
ture (Bail  2024) and methodological possibilities (Grossmann
et al. 2023) to collect data, impersonate humans, automate data
analyses and—as we argue later—to predict and manipulate
competitive texts to simulate the past, present, and possibly the
future.
To-­date, GPT has been used for text annotation and showed gen-
erally satisfactory results (Anglin et al. 2025; Gilardi et al. 2023)
and offered cost and time saving, yet recent studies showed
mixed results, such as GPT's weaker ability to analyze high
context messages (Choi et  al.  2024) and lower recall on cod-
ing schemes (Gielens et al. 2025). GPT has also been fruitfully
used for generating “silicon samples” to impersonate human
respondents based on known political characteristics (Argyle
et  al.  2023) and predisposition toward social environmental
issues (Qu and Wang 2024). GPT has also been used recently
to simulate artificial society using multiple AI agents that can
automatically interact for policy decision support (Clemen
et al. 2025) and policy evaluation (Kang et al. 2025).
Although these pioneering studies using GPT have opened new
paths in PA scholarship, the focus on “competitive texts” for pub-
lic sector innovation in contexts where textual data have ex-­ante
known outcomes from tournaments in the real world remains at
the periphery of scholarly attention. Meanwhile, the epistemic
possibilities of GPT to design new ways of measurement to pre-
dict outcomes (or measurement for prediction) and using ex-­ante
known present outcomes to reconstruct the past using synthetic
data (Jenkins 2023) and explain how it leads to current states (in
good vs. high quality or winning vs. losing) (or manipulation
for retrodiction) like what scientists did by retracing fossils to
explain life in the past remains in infancy and still in the form
of conceptual debates (e.g., Davidson and Karell  2025; James
et al. 2021; Grossmann et al. 2023).
Our goal in this article was to explore and demonstrate new
epistemic possibilities to develop measurement scales using
GPT to measure texts (i.e., idea, solution, agenda) attributes
and features to see its ability to predict outcomes, with a spe-
cific focus on “competitive texts” in the domain of public sector
innovation—or what we labeled as GPT for scale development.
We were also exploring the new possibilities of generating
“synthetic data” (e.g., new data created out of its original data
that retain the patterns of the original data; Jenkins 2023) that
complement prior studies that simulate “synthetic respondents”
(Argyle et al. 2023; James et al. 2021; Qu and Wang 2024) and
to compare how synthetic data correspond with real world data
to explain a competitive process in public sector innovation. We
labeled this as GPT for synthetic data.
Accordingly, in this article, we asked two overarching ques-
tions: What epistemic capabilities can GPT offer to study compet-
itive phenomena that are captured in textual data using real and
synthetic data? Can we measure, predict, retrodict, and calibrate
them to see the correspondence between the real and synthetic
worlds? To demonstrate these new epistemic possibilities, we
conducted a study of competition in government proposals for
innovation in public services with contestants from around the
world using United Nations Public Service Awards (UNPSA)
textual data. Understanding government innovations that have
been implemented and competing to be among the best solu-
tions is valuable to PA and public policy scholarship because it
can make theoretical advances while also contributing to policy-­
making and better administrative strategies.
Evidence for Practice
•	 GPT is ripe for scale development and synthetic data
generation.
•	 GPT scale shows good predictive ability on real-­world
and synthetic text data.
•	 Larger amounts of training increased the predictive
accuracy of winners.


## Page 3

3
Public Administration Review, 2026
Overall, this study contributes to PA research in several ways.
First, it showcased a novel methodological framework—that
is, GPT as scale developer and synthetic data maker—that in-
tegrates real-­world data with synthetic data for retrodiction,
manipulation, and prediction analysis using public sector
innovation as a case. The framework offers a replicable and
extensible paradigm for future research on competitive admin-
istrative and policy phenomena, moving beyond mere descrip-
tion (studying “as is”) toward a design-­science approach in
PA (Meijer 2025; Romme and Meijer 2020) that studies “what
could be” (Simon 1969).
Second, it expanded the boundary of “synthetic data”—that
previously deployed GPT to generate “synthetic respondents”
(Argyle et al. 2023; Jenkins 2023)—and introduced a novel type
called “synthetic ideas” (i.e., synthetic data in the form of tex-
tual solutions, concepts, proposals, memos, pitches) for PA and
policy research. In doing so, it enables large-­scale, low-­cost coun-
terfactual thought experiments to explore alternative scenarios
or questions that are often difficult to study due to privacy and
security issues or simply because the real world data is lacking.
Finally, the study offers decision support tools for decision mak-
ers for a variety of purposes, from optimizing innovation ca-
pacity, enabling efficient idea evaluations, and inspiring better
solutions for the public.
In the next section, we first summarized the literature on GPT's
epistemic capabilities for PA research, its relevance and appli-
cation in the public sector innovation competition context, and
then proposed the research framework. Subsequently, we illus-
trated the research design, reported key findings, and concluded
with the study's contributions and future research directions.
2   |   Literature Review
2.1   |   GPT'S Epistemic Possibilities in Public
Administration Research
Among the hottest debates among philosophers is whether
GPTs have intelligence. One school of thought argues that GPT
is an “agency without intelligence” (Floridi 2023a; Bishop 2021).
This rests on the idea that GPTs are merely statistical parrots
that re-­arrange words in texts without actually understanding
anything (Bender et al. 2021). Yet, another school of thought,
such as the posthumanism philosophy (Nath and Manna 2023;
Brusseau 2023), argues that GPT can have intelligence, just like
bacteria and animals have some form of intelligence, challenging
the very notion of the “human exceptionalism” in intelligence.
As we have moved past the era of GPT as “botshit”
(Routledge 2025) and “bullshit” (Hicks et al. 2024), that was prev-
alent in the early years of “hallucination heavy” large language
models (e.g., ChatGPT 3 or 3.5), we have increasingly seen GPTs
that can produce novel ideas (Zhou and Lee 2024), enable sci-
entific discoveries (Bergamaschi Ganapini 2025), and facilitate
data science (e.g., generating Python codes, Nejjar et al. 2025),
to making decisions in a more neutral (just) way than humans
(Keppeler et al. 2025). Accordingly, there is very good reason to
believe that although GPTs may not work in the same way as
humans in reasoning, decision making, and intelligence, they
have “merits” that humans cannot do, of which such merits are
partly explainable and partly still unexplainable today.
What is exciting with GPT is that it enables scholars to tinker
with “what might be” or “what could be”—a question of design
(Simon  1969) and possibilities (Bail  2024)—in understanding,
explaining, shaping, and predicting phenomena in public ad-
ministration (PA) and policy. The rise of GPT is an opportune
time to rethink and re-­imagine how the epistemic possibili-
ties in PA studies will look like and take shape amid the ever-­
increasing computational prowess of GPT.
Without being utterly comprehensive, we summarize the known
epistemic possibilities of GPT (see Table 1) across the social sci-
ences, ranging from automating tasks such as data annotation
(Churchill et  al.  2025; Anglin et  al.  2025) and questionnaire
pre-­testing and translation (Olivos and Liu  2025; Kunst and
Bierwiaczonek  2023) to enabling novel research designs, in-
cluding artificial world simulation (Clemen et  al.  2025; Kang
et al. 2025; Ghaffarzadegan et al. 2024) and hypothesis genera-
tion (Tong et al. 2024; Banker et al. 2024).
These applications demonstrate that GPT's primary impact lies
not in redefining the PA field's core content or substantive knowl-
edge (e.g., concepts, constructs, theories), but in expanding its
procedural and epistemic capacities—the methods for studying
phenomena and “how we can know what we know” (Bail 2024;
Gilardi et al. 2023; Grossmann et al. 2023) and the standards
for legitimizing knowledge claims (Alvarado  2023; Ferrario
et al. 2024). As Table 1 illustrates, despite the expanding rep-
ertoire of GPT applications in the social sciences, its potential
remains critically under-­explored in PA for two key functions:
scale development and synthetic data generation. Bridging this
gap is methodologically significant, as it addresses the problem
of measuring latent constructs with validity and conducting pre-
dictive or retrospective analyses when real-­world data are limited
or imbalanced (e.g., limited textual data for public innovation
research, research that work with sensitive biological data, or
research that study ethical questions of public leaders and bu-
reaucrats). This also matters because the scale, size, and type
of textual, unstructured data have exploded worldwide since
the Internet was invented, where such data (non-­numerical in
nature) require a different approach to measure them—among
others by using dictionaries.
2.2   |   GPT for Innovation Contests: Manipulation,
Retrodiction, and Prediction
Innovation contests have emerged as a prominent mecha-
nism for public organizations to source and select promising
solutions amid constraints such as limited resources and risk
aversion (Adamczyk et al. 2012; Terwiesch and Ulrich 2009;
Cinar et  al.  2018). From national platforms like the USA's
Chall​enge.​gov, the UK's Big Green Challenge, and Singapore's
Public Sector Transformation Awards, to international in-
novation competitions such as the United Nations Public
Service Awards (UNPSA) and European Public Sector Awards
(EPSA), these contests use mechanisms of “survival of the fit-
test” selection for public sector innovation ideas (Terwiesch


## Page 4

4
Public Administration Review, 2026
and Ulrich  2009; Pihlajamaa and Merisalo  2021; Tan and
Chandra  2025). Like the brutal, competitive, and zero-­sum
contest in the “Hunger Games” televised show in the “phys-
ical” realm, public innovation contests rest on a “textual”
realm. Despite the importance of public innovation contests,
core epistemological challenges persist: how we can (i) predict
highly vs. lesser promising ideas or solutions or policies, (ii)
measure their features to know their promise, and (iii) repro-
duce such ideas or solutions or policies.
To address these challenges, we extended Meijer's (2025) design
science for PA and proposed a framework to evaluate GPT's
utility for conducting manipulation, retrodiction, and prediction
through two specific epistemic operations—scale development
and synthetic data generation—with several plausible pathways.
The first possibility is to see GPT as a means to vary innovations
(“manipulation”), while humans (judges or panels) select the
best innovations. That is, GPT is used for manipulating tools to
be used for measurement (e.g., creating new “dictionaries,” gen-
erating “synthetic data”) or intervention (e.g., creating “nudges”
in human language or “synthetic events”). The second possi-
bility is to see real, naturally occurring events (e.g., a real life
contest, along with its rules and judges or panels who discern
TABLE 1    |    Epistemic possibilities of GPT in social science research.
Use of GPT
Description of GPT use
Benefits
Citations
Data annotation
Code a section of a text to
give it a label or meaning
for interpretation (e.g.,
turning a paragraph or
phrase to a code label)
Time and cost saving for large scale
annotation, GPT can learn from human-­made
coding enhances the speed of annotation
Churchill et al. (2025),
Anglin et al. (2025),
Gilardi et al. (2023),
and Gielens
et al. (2025)
Sample generation
To impersonate human
respondents based on
known characteristics (e.g.,
political or environmental
orientation, gender, age,
social stereotypes)
A solution for limited or hard to access
population, dealing with sensitive data,
avoiding trolls in survey platforms,
for imputing missing data
Argyle et al. (2023), Qu
and Wang (2024), and
Kim and Lee (2023)
Questionnaire
pre-­testing and
translation
To develop and pre-­test
questionnaires for survey
research; translating survey
items across languages
Improving wording and comprehension of
survey items, lowering the cost of survey
Olivos and Liu (2025)
and Kunst and
Bierwiaczonek (2023)
Simulate artifical
world
To develop multiple AI
agents that can interact
and react to stimulus (e.g.,
policy, norm diffusion)
Asking ‘what if’ questions to simulate the
future, faster and scale-­up simulation,
validating simulation against real world data
Clemen et al. (2025),
Kang et al. (2025),
and Ghaffarzadegan
et al. (2024)
Experimental
intervention
To design the message
content of a behavioral
intervention (e.g.,
creating nudges for
persuasion messages)
Enhancing message intervention
transparency and variability, more
efficient message development
Hecht et al. (2025) and
Harrison et al. (2024)
Hypothesis
generation
To develop testable
hypotheses by extracting
the causal relationships of
variables in the literature
Allowing scientific discovery by
fusing new connections of ideas that
human readers may overlook
Tong et al. (2024) and
Banker et al. (2024)
Scale development
(e.g., dictionary-­
based measures)
To create ‘dictionaries’ that
measure a body of corpus
to predict some outcomes
(e.g., measuring ‘pronouns’
use in a speech to predict
election outcomes)
Measuring elements of texts are often invisible
to human eyes, avoiding cherry picking
of content via human coding, inclusive
wording allows more accurate prediction
No relevant
articles found
Synthetic data
maker
To generate new data
that preserves some
or all (qualitative or
quantitative) characteristics
of an original data
Useful when dealing with limited data,
hard to access population, sensitive data,
for retrodiction and prediction research
Jenkins (2023) and
Lee et al. (2025)
Note: None of the articles reviewed above has used GPT for public administration research, particularly for scale development and synthetic data generation.


## Page 5

5
Public Administration Review, 2026
winners from losers) and synthetic events (e.g., a synthetic con-
test) as an arena for retrodiction, that is to go back to the past
to explain and infer certain patterns based on current knowl-
edge on such past events. The third possibility is to see GPT as
a means to select the best innovations, that is, acting as a tool to
make prediction of real world and synthetic events.
This framework is operationalized through four testable path-
ways of public sector innovation contests (see Figure 1). That
is, creating GPT-­generated dictionaries and applying them to
(1) real world events (UNPSA texts data) to predict real world
outcomes (UNPSA winners) (Pathway 1). Second, using the
same GPT-­generated dictionaries and applying them to syn-
thetic events (synthetic public sector innovation texts data) to
predict synthetic winners (Pathway 2) as well as real world
outcomes (UNPSA winners) (Pathway 3). Lastly, using the
same GPT-­generated dictionaries and applying them to a com-
bination of synthetic and real world events (synthetic public
sector innovation and UNPSA texts data) to predict real world
winners (Pathway 4). To this end, this study empirically evalu-
ates the specific epistemic gains that GPT may enable for PA re-
search. This includes improved measurement validity through
scalable GPT-­generated dictionaries (pathways 1, 2, 3, and 4),
tractable retrodiction for counterfactual inquiry (pathway 2),
and improved prediction under data scarcity or imbalance
(pathways 3, 4).
3   |   Methodology
3.1   |   Real World Event as Data: The United
Nations Public Service Awards (UNPSA)
We selected the United Nations Public Service Awards
(UNPSA), a prestigious global contest that celebrates excel-
lence in public service, as the real world, naturally occurring
event that generated public sector innovation (PSI) data. This
contest honors the innovative achievements and contribu-
tions of public service institutions that enhance effective and
responsive governance across the world (Cinar et  al.  2024).
Public innovators from across the globe submit structured text
applications detailing their innovative initiatives, providing
rich textual data about each innovation. Since the first Awards
Ceremony in 2003, the United Nations has received an increas-
ing number of submissions from all around the world. Prior
research in PA did not make a sharp conceptual distinction
whether UNPSA belongs to “public sector innovation” or “pub-
lic service innovation,” although in the PA literature the for-
mer is a broader category where the latter is a subset of (c.f.
Borins 2012; Cinar et al. 2024; De Vries et al. 2016). Given the
large variety of innovations in UNPSA that include more than
just services, we follow the convention of treating UNPSA as
“public sector innovation.”
The textual data of this study came from two sources: one was
the UNPSA project texts, which were human generated PSI data
that were collected from 2018 to 2022 (n = 938; winners = 42,
non-­winners = 896). The data was collected from the UNPSA
website (https://​publi​cadmi​nistr​ation.​un.​org/​unpsa/​datab​ase/​).
The UNPSA project texts were submitted by public innovators
who offered answers to 12 questions (with strict word limits)
such as “the description of the initiative, the issue it aims to
address and its objectives,” “the categories of sustainable devel-
opment goals it contributes to,” “how it addressed significant
shortfall in PA”, “its target groups,” “its innovativeness,” “how
far it has been transferred to other contexts,” and “evaluation of
its impact.”
3.2   |   Synthetic Event as Data: GPT-­Generated
Synthetic Data on Public Sector Innovation
We also generated synthetic events as data using GPT. We call
these synthetic PSI data (or “synthetic data” for brevity) with
the size of n = 500 (synthetic winners = 250, synthetic non-­
winners = 250), where we used Azure AI (from Microsoft) to
generate synthetic texts with the same questions (12 questions
with word limits) as the real world UNPSA data (see Appendix
1). Synthetic winners refer to winners of public sector innova-
tion texts generated by GPT using prompts, whereas synthetic
non-­winners are also GPT-­generated but failed or lost in the pub-
lic sector innovation contest. To generate synthetic winners and
non-­winners, we followed the following procedures in synthetic
text generation.
FIGURE 1    |    Research framework.


## Page 6

6
Public Administration Review, 2026
We first provided Azure AI with instructions and context to
inform it of the task of generating PSI winners or non-­winners
initiatives. The prompts in Azure AI to generate the synthetic
winners and non-­winners was as follows (see more details in
Appendix 1):
I want you to write a description of a public sector
innovation initiative. This is the kind of initiative
that aims to improve public service delivery to
citizens. The initiative will have the features of a
winner in an international competition for public
service innovation. Please use this as the premise for
answering all subsequent questions.
I want you to write a description of the public sector
innovation initiative. This is the kind of initiative that
aims to improve public service delivery to citizens.
The initiative will have the features of a loser or
failed initiative in an international competition
for public service innovation. Please use this as the
premise for answering all subsequent questions.
Following this initial introduction, the Azure AI was then
tasked with answering the same 12 questions one by one from
the UNPSA application form to generate the content of each syn-
thetic text. To ensure the independence of each generated project
text and prevent sequential correlation in the output results, we
launched a new conversation session for each synthetic output
(and close a current conversation in Azure AI before proceeding
to the next synthetic text generation). All generated responses
were then compiled into the final synthetic dataset, mirroring
the format of the real UNPSA texts for subsequent analysis.
These texts became the synthetic texts. Finally, to simulate the
metadata attributes of real-­world data, we programmatically
assigned each synthetic text an application year and a country
code using R. The year was randomly drawn from a uniform
distribution spanning 2018–2022, and the country code was ran-
domly assigned from the pool of 74 country codes presented in
the original UNPSA corpus. This randomization simulated the
variability of real-­world metadata and prevents the model from
learning spurious associations between specific years/countries
and outcomes.
From these data collection and manipulation processes, we col-
lected and generated textual data that consisted of 1438 texts
(UNPSA texts = 938; synthetic texts = 500).
3.3   |   GPT for Scale Development
and Measurement
Innovation, impact, and replicability are the evaluation criteria
outlined in the official documentation of the UNPSA awards,
and thus these three elements were selected as independent vari-
ables for this study. This approach allows us to know if we could
retrospectively (and a la retrodiction) identify these variables as
the determinants of winning or losing the UNPSA contests, and
once this was established, whether it would allow us to make
predictions.
To measure these variables, we employed a dictionary-­based
scale development approach, a widely used method in text anal-
ysis for classifying and quantifying specific concepts, such as
sentiment (Herhausen et al. 2025; Hollibaugh 2019). In the past
(dating back to the 1990s to just before ChatGPT first appeared
in late 2022), the construction of a dictionary-­based approach
to measure a large corpus text data requires massive resources
and large teams working across multiple years (see Pennebaker
et al. 2003; Tausczik and Pennebaker 2010). Without discounting
the value of a traditional, manual approach to dictionary-­based
scale development (as it has value on its own), a GPT-­based ap-
proach has advantages due to its ease of implementation and
comprehension (Herhausen et  al.  2025), and opportunities to
generate multiple versions of dictionaries in a faster way for se-
lection and ease of scaling—while still incorporating “human
in the loop” as adjudicator in evaluating the accuracy, complete-
ness, and appropriateness of the dictionaries.
Through GPT-­generated dictionaries, we can measure the in-
dependent variables using the ratio (R) of words related to in-
novation, impact and replicability in each project text (Schäper
et  al.  2023). Specifically, for each PSI (UNSPA, synthetic, a
mixture of UNPSA and synthetic) project text, we used three
GPT-­generated dictionaries to calculate the frequency (F) of in-
novation, impact and replicability-­related words. Our analysis
of these dictionaries relied on the following formula where the
frequency of each category of words in the text was divided by
the length (L) of this project text, as follows:
To construct the three measurement dictionaries for Innovation,
Impact, and Replicability constructs (see details in Supporting
Information: Appendix 2), we deployed Azure AI to generate vo-
cabularies using targeted prompts, which were “Please provide
50 words to measure innovation in text analysis” (and the same
for Impact and Replicability). We repeated this step 200 times to
gather a comprehensive and inclusive list of vocabulary for each
construct. Next, we manually screened the results to remove du-
plicates and inappropriate terms (e.g., axiomatic, balanced, con-
cept). The remaining words were then converted to root words,
known as stemming (e.g., “connecting,” “connected,” “connec-
tion” into “connect”) to encompass all variations used in text
analysis. To ensure the quality and relevance of our vocabulary,
we consulted two experts in PA, who were blinded to the pur-
pose of the study, and received valuable inputs.
As a summary, the two experts noted that (1) all three scales
effectively captured the appropriate terms and corresponding
variables and there were no weird or noise terms. They also (2)
recommended multicollinearity checks, which we subsequently
addressed, and (3) suggested that we prompt the GPT to gener-
ate the vocabulary for each construct separately to avoid con-
tamination, a process that we had actually used. Based on their
feedback and going back and forth in refining our measures, we
developed the final dictionaries comprising 240 root words for
innovation, 319 for impact, and 183 for replicability.
The dependent variable was the outcome of the project texts, that
is, whether each project text was a winner or not (1 = Yes, 0 = No)
across two contest types (real world contest vs. synthetic contest).
R = F∕L


## Page 7

7
Public Administration Review, 2026
Accordingly, we did have ex-­ante known results of which projects
won or lost. But what we did not know was what factors predict
which PSI project texts would win or provide ex-­post insights.
We included several control variables in the analyses. These in-
cluded (1) numeric, which was measured by the number frequency
divided by the text length; (2) subjectivity, which was measured
using the Textblob package in Python (0 = very objective, 1 = very
subjective); (3) emotionality, which was measured by Lexicalsuite
(https://​lexic​alsui​te.​com/​) software (Rocklage et al. 2023), rang-
ing from 0 (very negative) to 9 (very positive); (4) certainty, which
was also measured by Lexicalsuite software (0 = very uncertain,
9 = very certain); (5) Year; (6) Country; (7) Word count.
4   |   Results
We used a logistic regression model in the R statistical program-
ming environment to test the predictive ability of the three key in-
dependent variables on the likelihood of winning or not in the data.
To test the validity of GPT-­generated dictionaries and texts, our
analyses consisted of four pathways (see Figure 1): using GPT dic-
tionary to (1) predict actual UNPSA winners using UNPSA texts
(Pathway 1); (2) predict synthetic winners using synthetic PSI texts
(Pathway 2); (3) predict actual UNPSA winners using synthetic
PSI texts (Pathway 3); and lastly (4) predict actual UNPSA winners
using a mix of UNPSA and synthetic PSI texts (Pathway 4).
4.1   |   Descriptive Analysis
Table 2 shows the results of descriptive statistics for all variables.
The mean value of the winner (Mean = 0.203) was relatively low,
and the high variability (SD = 0.402) suggested that only a few
of the applicants were winners (which matched the real data).
For impact-­related words, the mean proportion (Mean = 0.063)
was
higher
compared
to
innovation-­related
words
(Mean = 0.028) and replicability-­related words (Mean = 0.015),
with replicability showing the lowest mean value. Additionally,
there was considerable variability in word count (SD = 769.275)
and numeric values (SD = 28.487), suggesting a diverse range of
texts that include both detailed descriptions and those that may
lack depth. The texts exhibited a moderate level of subjectiv-
ity (Mean = 0.379, SD = 0.043) and emotionality (Mean = 3.041,
SD = 0.308) while demonstrating a high degree of certainty
(Mean = 6.456). This combination of metrics reflects the com-
plexity and variability within the analyzed texts.
4.2   |   Pathway 1: GPT Dictionaries Predicting
UNPSA Winners Using UNPSA Texts
We used data containing 1 year (2018, Model 1), 2 years (2018
to 2019, Model 2), 3 years (2018–2020, Model 3), and 4 years
(2018– 2021, Model 4) as training data sets to make predictions
for the remaining years and obtained the following regression
(see Supporting Information: Appendix 3.1) and prediction (see
Table 3) results.
As shown in Supporting Information: Appendix 3.1, Innovation,
Impact, and Replicability had significant positive effects on
TABLE 2    |    Descriptive analysis.
Variables
N
Mean
SD
Min
Max
Winner
1438
0.203
0.402
0
1
Innovation
1438
0.028
0.011
0.007
0.076
Impact
1438
0.063
0.022
0.013
0.125
Replicability
1438
0.015
0.007
0.003
0.056
Wordcount
1438
3197
769.275
810
5962
Numeric
1438
75.22
28.487
24
199
Subjectivity
1438
0.379
0.043
0.187
0.563
Emotionality
1438
3.041
0.308
2.277
4.688
Certainty
1438
6.456
0.153
5.751
6.874
Year
1438
2020
1.431
2018
2022
Country
1438
40.93
20.809
1
74
TABLE 3    |    Predictive accuracy results of UNPSA winners based on
UNPSA text training data (Pathway 1).
Predict UNPSA winner
Accuracy
UNPSA winner
Model 1 (predict years: 2019–2022)
No
Yes
No
609
25
96.06%
Yes
13
20
60.61%
Total
94.30%
Model 2 (predict years: 2020–2022)
No
Yes
No
437
7
98.42%
Yes
8
16
66.67%
Total
96.79%
Model 3 (predict years: 2021–2022)
No
Yes
No
274
2
99.28%
Yes
5
12
70.59%
Total
97.61%
Model 4 (predict year: 2022)
No
Yes
No
137
0
100%
Yes
2
7
77.78%
Total
98.63%
Note: The values in boxes mean the number of correctly predicted winners
(bottom right) and non-­winners (top left). Winners' predictive accuracy of Model
1 (60.61%) = Number of actual winners predicted (20) / Total number of actual
winners (13 + 20), the same for non-­winners and overall predictive accuracy.


## Page 8

8
Public Administration Review, 2026
predicting winners across the four models tested (except for
Innovation in Model 1). This suggested that Innovation, Impact,
and Replicability could be key factors in determining the likeli-
hood of success or being considered a “winner” in the context an-
alyzed. The negative effect of subjectivity suggested that a more
subjective description of the project texts would reduce its proba-
bility of winning. And the use of more numerical information in
the project texts would increase the probability of winning.
We present the predictive accuracy results of UNPSA winners
based on UNPSA text training datasets in Table 3. Overall, GPT-­
generated dictionaries' predictive accuracy for actual UNPSA
winners was 60.61% using 1 year of training data (2018), and this
predictive accuracy improved to 77.78% as the training data ex-
panded to 4 years (2018–2021). The accuracy of the GPT-­generated
dictionaries in predicting actual UNPSA non-­winners also
showed an upward trend, achieving an impressive increase from
96.06% to a perfect 100%. This suggests that it was much easier
to predict losers, and the rationale behind this was most probably
that there was a much larger dataset for losers than for winners.
To ensure the validity of the GPT-­generated dictionaries, we
conducted three sensitivity checks (see Supporting Information:
Appendix 4). First, we employed sub-­dictionary tests (see
Supporting Information: Figure  4.1) to isolate the impact of
informative terms from the dictionary size itself. For each
sub-­dictionary, we created random subsets at 20%, 40%, 60%,
and 80% of the complete (100%) size dictionary. For each sub-­
dictionary, we performed 100 random samples, recalculated the
features, and re-­evaluated the model using the same training/
test splits. The results are presented as performance-­versus-­size
curves, demonstrating stable prediction accuracy and F1 score
after substantial pruning. Second, we implemented placebo
swaps (see Supporting Information: Figure 4.2) to test the spec-
ificity of each dictionary. Swapping the Innovation dictionary
into the Impact or Replicability dictionaries slot led to a degra-
dation in winner prediction performance for Pathway 1. This
confirms that each dictionary captures a distinct and effective
construct. Finally, we compared the complete dictionaries (at
100%) against random sub-­dictionary sets (at 20%, 40%, 60%,
and 80%) (see Supporting Information: Figure 4.3), and as ex-
pected, these random lists exhibited performance degradation
compared to the complete dictionary.
4.3   |   Pathway 2: GPT Dictionaries Predicting
Synthetic Winners Based on Synthetic Texts
Building on the analytical approach in Pathway 1, we conducted
analyses for Pathway 2. We structured the analyses for the 500
GPT-­generated PSI texts by creating training datasets of differ-
ent time spans (1–4 years) to predict synthetic winners. A pre-
liminary analysis revealed that the model based on a single year
(2018) of synthetic text data suffered from limited statistical
power, resulting in statistically insignificant coefficients for all
independent variables. To ensure the robustness and reliability of
our findings, we therefore proceeded with the two-­, three-­, and
four-­year training datasets. The models tested (see Supporting
Information: Appendix 3.2) showed that Innovation, Impact,
and Replicability had significant positive effects on predicting
synthetic winners. This suggested that Innovation, Impact, and
Replicability were key factors in determining the likelihood of
success or being considered a synthetic winner.
Table  4 shows the predictive accuracy of synthetic winners
based on synthetic text training datasets in Pathway 2. The
results exhibited a pattern consistent with Pathway 1. With an
expansion of the training data, the model's accuracy in predict-
ing the synthetic winner increased from 83.33% to 94%, and the
overall accuracy also rose from 87.33% to 92%. This high accu-
racy indicates that the model has successfully learned the in-
herent patterns and rules of the synthetic data distribution upon
which its training relies.
4.4   |   Pathway 3: GPT Dictionaries Predicting
UNPSA Winners Based on Synthetic Texts
Next, to test Pathway 3, we utilized the 500 GPT-­generated
PSI texts as a training set to predict the real UNPSA winners.
Consistent with the methodology established in our earlier
Pathways 1 and 2 analyses and informed by the limited statis-
tical power of a one-­year (2018) training model, we constructed
two-­, three-­, four-­, and five-­year training datasets from the syn-
thetic data, omitting the one-­year set. The models tested (see
Supporting Information: Appendix 3.3) showed significant pos-
itive effects of Innovation, Impact, and Replicability in predict-
ing the likelihood of being synthetic winners.
TABLE 4    |    Predictive accuracy results of synthetic winners based on
synthetic text training data (Pathway 2).
Predict synthetic
winner
Accuracy
Synthetic winner
Model 5 (predict years: 2020–2022)
No
Yes
No
137
13
91.33%
Yes
25
125
83.33%
Total
87.33%
Model 6 (predict years: 2021–2022)
No
Yes
No
94
6
94.00%
Yes
12
88
88.00%
Total
91.00%
Model 7 (predict year: 2022)
No
Yes
No
45
5
90.00%
Yes
3
47
94.00%
Total
92.00%
Note: The values in boxes mean the number of correctly predicted winners
(bottom right) and non-­winners (top left). Non-­winner's predictive accuracy of
Model 5 (91.33%) = Number of synthetic non-­winners predicted (137) / Total
number of synthetic non-­winners (137 + 13), the same for winners and overall
predictive accuracy.


## Page 9

9
Public Administration Review, 2026
Table 5 reports the predictive accuracy results of UNPSA winners
based on synthetic text training datasets. When synthetic PSI
texts were used as training data, the predictive accuracy for actual
UNPSA winners improved from 40.48% to 50% as the training
data volume increased from two to 5 years, though it remained at
a relatively low level. However, the predictive accuracy for actual
UNPSA non-­winners was robust and consistently high, with all
values above 97%. This discrepancy suggests that our model may
have overfitted to the stylistic and thematic patterns inherent in
the synthetic data, which do not fully capture the nuanced and
diverse characteristics of real-­world winning projects.
4.5   |   Pathway 4: GPT Dictionaries Predicting
UNPSA Winners Using Hybrid UNPSA
and Synthetic Texts
Finally, to evaluate the predictive power of a combined data-
set, we integrated UNPSA and synthetic PSI texts to predict
the UNPSA winners. Specifically, we constructed two distinct
training datasets: One comprising mixed data of UNPSA and
synthetic PSI texts from the year 2018, and another encompass-
ing mixed data from the entire 2018–2021 period. These com-
bined training datasets were then used to predict the UNPSA
winners from the remaining years, testing the model's ability
to predict from a hybrid data source. The models tested (see
Supporting Information: Appendix 3.4) showed significant
positive effects of innovation and replicability in predicting the
likelihood of being winners, while the effect of impact was not
statistically significant.
Table 6 presents the predictive accuracy results of UNPSA win-
ners based on mixed text training datasets. Overall, both mod-
els demonstrated high overall accuracy (Model 12 at 97.45%
and Model 13 at 97.95%). However, further analysis of UNPSA
winner predictions revealed that, consistent with previous re-
search findings, prediction accuracy for UNPSA winners in-
creased with the expansion of training data, rising from 51.52%
for 1 year to 66.67% for 4 years. However, compared to Pathway
1 (GPT dictionaries predicting UNPSA winners using UNPSA
texts) in predicting UNPSA winners, the prediction accuracy of
models trained solely on UNPSA data outperforms mixed-­data
models over the same time span. Potential reasons include, first,
the winner features embedded in UNPSA texts are difficult for
GPT-­generated synthetic data to fully replicate. Although syn-
thetic data can expand the sample size, it suffers from degra-
dation when simulating real-­world characteristics. Secondly,
mixed data models must learn from a mixture of “real signals”
and “simulated signals,” which may introduce noise that dilutes
or obscures key discriminative features to some extent.
4.6   |   Model Evaluation
We first used the variance inflation factor (VIF) to conduct a
multicollinearity test to identify and assess the degree of cor-
relation between variables in the regression models. The results,
TABLE 5    |    Predictive accuracy results of UNPSA winners based on
synthetic text training data (Pathway 3).
Predict UNPSA winner
Accuracy
UNPSA winner
Model 8 (predict years: 2018–2022)
No
Yes
No
891
5
99.44%
Yes
25
17
40.48%
Total
96.80%
Model 9 (predict years: 2018–2022)
No
Yes
No
881
15
98.33%
Yes
23
19
45.24%
Total
95.95%
Model 10 (predict years: 2018–2022)
No
Yes
No
879
17
98.10%
Yes
22
20
47.62%
Total
95.84%
Model 11 (predict years: 2018–2022)
No
Yes
No
877
19
97.88%
Yes
21
21
50.00%
Total
95.73%
Note: The values in boxes mean the number of correctly predicted winners
(bottom right) and non-­winners (top left). The overall predictive accuracy
of Model 8 (96.80%) = Number of actual winners and non-­winners predicted
(891 + 17) / Total number of actual winners and non-­winners (891 + 5 + 25 + 17),
the same for winners and non-­winners' predictive accuracy.
TABLE 6    |    Predictive accuracy results of UNPSA winners based on
mixed text training data (Pathway 4).
Predict UNPSA winner
Accuracy
UNPSA
winner
Model 12 (predict years: 2019–2022)
No
Yes
No
633
1
99.84%
Yes
16
17
51.52%
Total
97.45%
Model 13 (predict year: 2022)
No
Yes
No
137
0
100.00%
Yes
3
6
66.67%
Total
97.95%
Note: The values in boxes mean the number of correctly predicted winners
(bottom right) and non-­winners (top left). The overall predictive accuracy of
Model 12 (97.45%) = Number of actual winners and non-­winners predicted
(633 + 17)/Total number of actual winners and non-­winners (633 + 1 + 16 + 17),
the same for winners and non-­winners' predictive accuracy.


## Page 10

10
Public Administration Review, 2026
as shown in Supporting Information: Appendix 5, indicated that
variables in these models have low multicollinearity (VIF < 10).
Accordingly we proceeded by reporting commonly used metrics
for evaluating the performance of these models in Supporting
Information: Appendix 6, including Precision (the proportion
of true positive predictions out of all positive predictions made
by the models), Recall (the proportion of true positive predic-
tions from all actual positive samples in the dataset), F1 Score (a
weighted harmonic mean of precision and recall, ranges from 0
to 1, with 1 being the best possible score), and PR-­AUC the area
under the precision-­recall curve and represents the model's over-
all performance, a perfect model would have a PR-­AUC of (1). In
summary, the models trained on UNPSA data (Pathway 1) and
mixed data (Pathway 4) performed well in predicting UNPSA
winners, whereas those based solely on synthetic data (Pathway
3) underperformed. Notably, the synthetic data demonstrated its
utility when used in a closed loop, with models performing well
in predicting their own synthetic winners (Pathway 2).
5   |   Conclusion
Public administration (PA) scholarship is undergoing a quiet rev-
olution with the increasing integration of AI, particularly GPT,
in its research repertoires (Anastasopoulos and Whitford 2018;
McDonald et al. 2022). Echoing the pioneering work of social
scientists that have used GPT as new epistemic possibilities
(Hecht et al. 2025; Abdurahman et al. 2025; Bail 2024), we par-
take in demonstrating a new epistemic possibility in using GPT
for scale development and synthetic data generation where we
measured, predicted, retrodicted, and calibrated the real and
synthetic texts data using public sector innovation as a case
using innovation contests as a lens. This study, while imperfect,
constitutes one of the earliest efforts in transforming PA schol-
arship in demonstrating empirically how GPT changes how we
can know about something to make claims—that is, epistemic
knowledge. And that this matters for PA.
Following design science's premise of not only observing and
studying the world “as is” but also partaking in intervening and
manipulating the world a la “how it might be” (Simon 1969), we
engaged in retrospective (scientific validation) and prospective
(manipulation oriented) research (Romme and Meijer 2020) to
explore GPT's epistemic capabilities (Alvarado  2023; Ferrario
et al. 2024) in understanding, explaining, and predicting com-
petitive texts that are embedded in the public service innovation
(PSI) phenomenon. Using GPT for purposes of scale develop-
ment and synthetic data generation for public sector innovation
and coupled with real-­world data on public sector innovation
from the United Nations Public Service Awards (UNPSA), we
examined the textual features of PSI texts that distinguished
promising from less promising PSI.
Specifically, this study first demonstrates the validity of GPT as a
tool for scalable measurement by developing and validating GPT-­
generated dictionaries to measure textual data. Scale development
is a resource and labor-­intensive process in the social sciences,
yet here we demonstrate the possibility of developing GPT-­
generated dictionaries faster, cheaper, and at scale. We applied
three GPT-­generated dictionaries—that measure for innova-
tion, replicability, and impact—to both real-­world UNPSA data
(n = 938, winners = 42, non-­winners = 896) and a comparative
corpus of synthetic PSI data (n = 500, synthetic winners = 250,
synthetic non-­winners = 250). The results showed that with suf-
ficient training data, GPT-­generated dictionaries had reasonably
good predictive ability on actual UNPSA results (Pathways 1, 3,
and 4) as well as synthetic PSI results (Pathway 2).
Secondly, we demonstrated the possibility of developing syn-
thetic data (i.e., synthetic PSI data generated using GPT and
certain prompts) for predictive modeling under limited data, al-
beit with some caveats. Specifically, we demonstrated that when
GPT-­generated dictionaries were applied to four-­year synthetic
PSI training data (Pathway 2), they achieved an overall accuracy
of 92%, with 94% accuracy for winners and 90% accuracy for
non-­winners. This indicates that synthetic data enables tracta-
ble retrodiction for counterfactual inquiry, confirming the dictio-
naries' internal validity and the synthetic data's self-­consistency
before they are applied to the complexities of the real world.
However, when synthetic PSI data were used as training data
alone to predict actual UNPSA outcomes (Pathway 3), the ac-
curacy in predicting winners went down (from 40.48% using
2018–2019 data to 50% using 2018–2021 data), but it was
much higher (all above 97%) in predicting non-­winners. On
the one hand, this reveals that synthetic PSI data may lack the
knowledge of “real-­world complexities” that can influence the
real-­world data. That is, synthetic data, whereas internally con-
sistent, may fail to capture the “publicness” of innovation, that
is, the political, bureaucratic, and contextual complexities that
transcend mere textual features and often determine success or
failure in the real world. Moreover, when we integrated UNPSA
and synthetic PSI texts to predict UNPSA winners (Pathway 4),
the prediction accuracy for UNPSA winners increased with the
expansion of training data, rising from 51.52% using 2018 data
to 66.67% using 2018–2021 data. This also suggests that a com-
bination of synthetic data and real-­world PSI data (i.e., having
a greater amount and diversity of training data) could increase
the predictive ability in using GPT-­generated dictionaries and
synthetic data to predict real world PSI data.
Although this study demonstrates the methodological potential
of GPT in predicting innovation in public sector competitions,
our findings must be interpreted with a grain of salt, alongside
critical ethical and normative considerations. Applying “black-­
box” algorithms to evaluate public innovation inherently raises
concerns about algorithmic transparency and alignment with
public values (Valle-­Cruz and García-­Contreras  2023; Mišić
et  al.  2025). This framework, which relies on GPT-­generated
dictionaries and synthetic data, underscores the necessity of
explicitly disclosing measurement constructs (dimensions and
their weights), prompts, model versions, and validation criteria
to ensure procedural fairness for all applicants. This calls for
greater research transparency when using GPT for social sci-
ences research to facilitate future replications. Accordingly, this
calls for gatekeepers of knowledge (such as journal editors and
reviewers) to not punish or penalize researchers for experiment-
ing with GPTs when the research results are not or less favorable
than ordinary approaches without GPT.
Furthermore, the predictive patterns identified by the models
may reflect and amplify biases inherent in the training data


## Page 11

11
Public Administration Review, 2026
(which could come from Wikipedia, YouTube, or even a large
database of past innovation contests), potentially disadvantag-
ing linguistically distinct innovations. Consequently, the de-
ployment of such systems needs to undergo rigorous bias audits
(Hilliard et al. 2024), where we as humans should explicitly po-
sition GPT as a decision-­support tool and render the final judg-
ment and accountability in the hands of human evaluators. Our
objective of using the GPT tool in this research is not to replace
human deliberation, but to enhance efficacy in ways that serve
the fundamental values of public administration, ensuring that
explorations of GPT's possibilities remain grounded in norma-
tive commitments to fairness, accountability, and public trust.
This study reveals a number of methodological limitations. Most
notably, the model exhibited signs of overfitting when trained
on synthetic data and applied to real-­world winner prediction.
This likely occurred because the GPT-­generated data reflects
an idealized or stereotypical notion of “innovation,” lacking the
nuanced diversity and authentic noise characteristic of genuine
UNPSA-­winning initiatives. To mitigate this issue in future re-
search, potential solutions include employing mixed training
datasets that combine fine-­tuned synthetic data and real data to
better simulate the complexity of actual scenarios. Second, when
constructing synthetic data, we deliberately balanced the num-
ber of texts from winners and non-­winners, which aims to force
the model to learn discriminative features that truly distinguish
“winners” from “non-­winners” rather than simply defaulting to
predicting the more common one. However, this artificial bal-
ance does not reflect the genuinely scarce distribution of award-­
winning projects in reality. Third, our expert validation process
employs a dichotomous (include/exclude) paradigm for term
screening, without calculating traditional inter-­rater reliability
TABLE 7    |    Future research agendas with GPT For public administration research.
Use of GPT
GPT for practitioners
GPT for researchers
Public sector
innovation
Quality public innovation: identifying
innovative ideas, enabling efficient idea
evaluations, and finding better “rules of the
game” that enhance solutions for the public
Data retrieval and management: easing the
retrieval and management of millions of PSI texts
Visualization: showing graphs of
relations among innovative ideas
Asking new research questions such as the role
of emotion or linguistics style in PSI success,
using retrodiction and prediction to predict PSI
success using real world and synthetic datasets,
doing experimental intervention to improve
quality of PSI project ideas, designing new words
that resonate with judges (what could be)
Public personnel
management
Fairness, justice, efficiency in decisioning:
avoid biases in human recruiter decision
making during employee selection, remove
human biases in staff performance evaluation,
efficient and faster matching between jobs
requirements with many job applicants,
new ideas in crafting job descriptions and
allocation, predicting staff turnover
Asking new research questions about factors to
predict stress, well-­being, emotions of staff using
email data; generating new hypothesis using
rarely used variables (e.g., DNA, body posture
when walking), sample generation for future jobs
applicants' analysis, designing new HR policies
that resonate with staff (what could be), pre-­testing
items to develop new public sector creativity scale
Public budgetting
and procurement
Better accountability: discovering potential
fraud or corruption, doing automated cross
checking of accounts and finances
Decision support tools: advice on how to
better spend public budgets efficiently using
multiple and complex criteria, designing
‘hard to crack’ public procurement clauses
Asking new research questions on factors
predicting fraud and accountability using
internal and external data, generating potential
fraudsters using silicon samples based on
past data, doing experimental intervention
on how to get local gov't be more efficient in
public spending, simulate cross departmental
coordination in budgeting and procurement
Digital governance
Better public services: providing ‘all
under one roof and 24/7’ service
Decision support tools: rapid analysis of
citizen complaints or feedback in chatbots,
capturing problems in the interaction
between AI agents and physical action
among robots as street level bureaucrats
Asking new research questions such factors
predicting trolls' comments in social media
and detecting dis/mis information, generating
silicon samples of potential criminal's action
based on past data, doing experimental
intervention to mobilize citizens for good cause
Strategic public
management
Better planning and strategizing: smarter
way to plan for short, medium, long
term strategic planning in government
(goals, resources, constraints)
Decision support tools: identifying idle resources
(staff, buildings, time) for optimization, doing
complex decision scenarios for planning
Asking ‘what if’ questions to simulate strategic
planning, generate synthetic data for testing new
‘vision and mission’ in government, developing
a new performance measurement scale in
government satisfaction research, simulate citizen-­
govt interactions to test new policy directions


## Page 12

12
Public Administration Review, 2026
metrics. Future research may adopt continuous rating scales
with statistical evaluation to enhance the methodological rigor
and transparency of scale development.
This study also opens several avenues for future research. As
shown in Table 7, we discussed the potential of GPT for prac-
titioners and researchers across several PA domains, includ-
ing public sector innovation, public personnel management,
public budgeting and procurement, digital governance, and
strategic public management. Future work could focus on eval-
uating and constructing human-­AI collaborative mechanisms,
which entails developing frameworks to assess whether GPT-­
enhanced decisions improve efficiency while upholding pub-
lic values. These insights could then be used to design hybrid
models that combine human expertise and GPT scalability for
sensitive tasks, such as fraud detection and strategic planning.
Additionally, a promising direction for qualitative research is to
conduct in-­depth case studies of predicted outliers. For instance,
analyzing why certain high-­scoring synthetic ideas or propos-
als failed in practice, or why some real-­world winning projects
received low GPT scores. Such investigations can transcend the
limitations of textual patterns, uncovering critical non-­textual
and contextual factors that current models fail to capture.
Methodologically, future research could explore integrating
multimodal data such as project budget information, agencies'
network structure data, image data of certain artifacts, and even
geospatial data to construct more comprehensive predictive
models. Moreover, more work is needed to test and evaluate the
effectiveness and limitations of synthetic data across different
policy simulation scenarios, and integrate GPT with cutting-­
edge methods such as computational experiments and causal
inference methods to provide more reliable evidence for complex
policy interventions.
Acknowledgments
We would like to express our sincere thanks to those who offered
valuable feedback on earlier versions of this work. We are particularly
indebted to Greta Nasi (Bocconi) and M. Jae Moon (Yonsei) and the au-
dience at the IRSPM 2025 conference. We also extend our thanks to the
organizers of the AI and Public Policy International Conference 2024,
hosted by the Nanyang Centre for Public Administration (NCPA) at
Nanyang Technological University (NTU), especially Jue Wang and
Jiwei Qian during the conference. Additionally, we sincerely thank
the three anonymous reviewers for their valuable comments and sug-
gestions, which have significantly improved this paper. Lastly, we are
grateful for colleagues and friends who share our passion for this re-
search including Alfred Ho, Richard Walker, Nick Petrovsky, Nicole Liu
Ning, as well as Eduardo Ongaro and Ignacio Criado.
Funding
The work described in this paper was fully supported by a grant from
the Research Grants Council of the Hong Kong Special Administrative
Region, China (Project No. CityU 15513723).
Disclosure
The authors have nothing to report.
Conflicts of Interest
The authors declare no conflicts of interest.
Data Availability Statement
The data that support the findings of this study are openly available in
Harvard Dataverse at https://​doi.​org/​10.​7910/​DVN/​WTMGTY.
References
Abdurahman, S., A. Salkhordeh Ziabari, A. K. Moore, D. M. Bartels,
and M. Dehghani. 2025. “A Primer for Evaluating Large Language
Models in Social-­Science Research.” Advances in Methods and Practices
in Psychological Science 8, no. 2: 1–25. https://​doi.​org/​10.​1177/​25152​
45925​1325174.
Adamczyk, S., A. C. Bullinger, and K. M. Möslein. 2012. “Innovation
Contests: A Review, Classification and Outlook.” Creativity and Innovation
Management 21, no. 4: 335–360. https://​doi.​org/​10.​1111/​caim.​12003​.
Alvarado, R. 2023. “AI as an Epistemic Technology.” Science and
Engineering Ethics 29, no. 5: 1–30. https://​doi.​org/​10.​1007/​s1194​8-­​023-­​
00451​-­​3.
Anastasopoulos, L. J., and A. B. Whitford. 2018. “Machine Learning for
Public Administration Research, With Application to Organizational
Reputation.” Journal of Public Administration Research and Theory 29,
no. 3: 491–510. https://​doi.​org/​10.​1093/​jopart/​muy060.
Andrews, R., B. Bellò, J. Downe, S. Martin, and R. M. Walker. 2021.
“The Motivations for the Adoption of Management Innovation
by Local Governments and Its Performance Effects.” Public
Administration Review 81, no. 4: 625–637. https://​doi.​org/​10.​1111/​
puar.​13375​.
Anglin, K. L., A. Bertrand, J. Gottlieb, and J. Elefante. 2025. “Scaling
up With Integrity: Valid and Efficient Narrative Policy Framework
Analyses Using Large Language Models.” Policy Studies Journal.
https://​doi.​org/​10.​1111/​psj.​70045​.
Argyle, L. P., E. C. Busby, N. Fulda, J. R. Gubler, C. Rytting, and D.
Wingate. 2023. “Out of One, Many: Using Language Models to Simulate
Human Samples.” Political Analysis 31, no. 3: 337–351. https://​doi.​org/​
10.​1017/​pan.​2023.​2.
Bail, C. A. 2024. “Can Generative AI Improve Social Science?”
Proceedings of the National Academy of Sciences 121, no. 21: e2314021121.
https://​doi.​org/​10.​1073/​pnas.​23140​21121​.
Banker, S., P. Chatterjee, H. Mishra, and A. Mishra. 2024. “Machine-­
Assisted Social Psychology Hypothesis Generation.” American
Psychologist 79, no. 6: 789–797.
Bender, E. M., T. Gebru, A. McMillan-­Major, and S. Shmitchell. 2021.
“On the Dangers of Stochastic Parrots: Can Language Models be
Too Big?” In In Proceedings of the 2021 ACM Conference on Fairness,
Accountability, and Transparency, 610–623. Association for Computing
Machinery. https://​doi.​org/​10.​1145/​34421​88.​3445922.
Bergamaschi Ganapini, M. 2025. “Can AI Make Scientific Discoveries?”
Philosophical
Studies:
1–19.
https://​doi.​org/​10.​1007/​s1109​8-­​025-­​
02299​-­​8.
Bishop, J. M. 2021. “Artificial Intelligence Is Stupid and Causal
Reasoning Will Not Fix It.” Frontiers in Psychology 11: 2603. https://​doi.​
org/​10.​3389/​fpsyg.​2020.​513474.
Borins, S. F. 2012. “Making Narrative Count: A Narratological Approach
to Public Management Innovation.” Journal of Public Administration
Research and Theory 22, no. 1: 165–189. https://​doi.​org/​10.​1093/​jopart/​
muq088.
Brusseau, J. 2023. “Mapping AI Avant-­Gardes in Time: Posthumanism,
Transhumanism, Genhumanism.” Discover Artificial Intelligence 3, no.
1: 32. https://​doi.​org/​10.​1007/​s4416​3-­​023-­​00080​-­​6.
Chandra, Y., and N. Feng. 2025. “Algorithms for a New Season?
Mapping a Decade of Research on the Artificial Intelligence-­Driven
Digital Transformation of Public Administration.” Public Management
Review: 1–35. https://​doi.​org/​10.​1080/​14719​037.​2025.​2450680.


## Page 13

13
Public Administration Review, 2026
Choi, J., W. Wehde, and R. Maulik. 2024. “Politics of Problem Definition:
Comparing Public Support of Climate Change Mitigation Policies Using
Machine Learning.” Review of Policy Research 41, no. 1: 104–134.
Churchill, A., S. Pichika, C. Xu, and Y. Liu. 2025. “GPT Models for
Text Annotation: An Empirical Exploration in Public Policy Research.”
Policy Studies Journal: 1–17. https://​doi.​org/​10.​1111/​psj.​70034​.
Cinar, E., C. Simms, P. Trott, and M. A. Demircioglu. 2024. “Public
Sector Innovation in Context: A Comparative Study of Innovation
Types.” Public Management Review 26, no. 1: 265–292. https://​doi.​org/​
10.​1080/​14719​037.​2022.​2080860.
Cinar, E., P. Trott, and C. Simms. 2018. “A Systematic Review of Barriers
to Public Sector Innovation Process.” Public Management Review 21, no.
2: 264–290. https://​doi.​org/​10.​1080/​14719​037.​2018.​1473477.
Clemen, T., A. Tolk, U. A. Clemen, D. Glake, and G. Günther. 2025.
“Creating Artificial Societies for Policy Decision Support: A Research
Agenda and Call to Action.” SIMULATION 101, no. 6: 645–660. https://​
doi.​org/​10.​1177/​00375​49724​1295765.
Criado, J. I., L. Alcaide-­Muñoz, and I. Liarte. 2025. “Two Decades of
Public Sector Innovation: Building an Analytical Framework From a
Systematic Literature Review of Types, Strategies, Conditions, and
Results.” Public Management Review 27, no. 3: 623–652. https://​doi.​org/​
10.​1080/​14719​037.​2023.​2254310.
Davidson, T., and D. Karell. 2025. “Integrating Generative Artificial
Intelligence Into Social Science Research: Measurement, Prompting,
and Simulation.” Sociological Methods & Research 54, no. 3: 775–793.
https://​doi.​org/​10.​1177/​00491​24125​1339184.
De Vries, H., V. Bekkers, and L. Tummers. 2016. “Innovation in the
Public Sector: A Systematic Review and Future Research Agenda.” Public
Administration 94, no. 1: 146–166. https://​doi.​org/​10.​1111/​padm.​12209​.
Demircioglu, M. A. 2024. “Public Sector Innovation: Sources, Benefits,
and Leadership.” International Public Management Journal 27, no. 2:
190–220. https://​doi.​org/​10.​1080/​10967​494.​2023.​2276481.
Fazekas, M., I. J. Tóth, and L. P. King. 2016. “An Objective Corruption
Risk Index Using Public Procurement Data.” European Journal on
Criminal Policy and Research 22: 369–397. https://​doi.​org/​10.​1007/​s1061​
0-­​016-­​9308-­​z.
Ferrario, A., A. Facchini, and A. Termine. 2024. “Experts or Authorities?
The Strange Case of the Presumed Epistemic Superiority of Artificial
Intelligence Systems.” Minds and Machines 34, no. 3: 30. https://​doi.​org/​
10.​1007/​s1102​3-­​024-­​09681​-­​1.
Floridi, L. 2023a. “AI as Agency Without Intelligence: On ChatGPT,
Large Language Models, and Other Generative Models.” Philosophy and
Technology 36, no. 1: 15. https://​doi.​org/​10.​1007/​s1334​7-­​023-­​00621​-­​y.
Floridi, L. 2023b. The Ethics of Artificial Intelligence: Principles,
Challenges, and Opportunities. OUP.
Ghaffarzadegan, N., A. Majumdar, R. Williams, and N. Hosseinichimeh.
2024. “Generative Agent-­Based Modeling: An Introduction and
Tutorial.” System Dynamics Review 40, no. 1: e1761. https://​doi.​org/​10.​
1002/​sdr.​1761.
Gielens, E., J. Sowula, and P. Leifeld. 2025. “Goodbye Human
Annotators? Content Analysis of Social Policy Debates Using ChatGPT.”
Journal of Social Policy 1-­20: 1–20. https://​doi.​org/​10.​1017/​S0047​27942​
4000382.
Gilardi, F., M. Alizadeh, and M. Kubli. 2023. “ChatGPT Outperforms
Crowd Workers for Text-­Annotation Tasks.” Proceedings of the National
Academy of Sciences 120, no. 30: e2305016120. https://​doi.​org/​10.​1073/​
pnas.​23050​16120​.
Grimmer, J., and B. M. Stewart. 2013. “Text as Data: The Promise and
Pitfalls of Automatic Content Analysis Methods for Political Texts.”
Political Analysis 21, no. 3: 267–297. https://​doi.​org/​10.​1093/​pan/​
mps028.
Grossmann, I., M. Feinberg, D. C. Parker, N. A. Christakis, P. E. Tetlock,
and W. A. Cunningham. 2023. “AI and the Transformation of Social
Science Research.” Science 380, no. 6650: 1108–1109. https://​doi.​org/​10.​
1126/​scien​ce.​adi1778.
Harrison, R. M., E. Lapteva, and A. Bibin. 2024. “Behavioral Nudging
With Generative AI for Content Development in SMS Health Care
Interventions: Case Study.” JMIR AIJMIR ai 3, no. 1: e52974.
Hecht, C. A., D. C. Ong, M. Clapper, et al. 2025. “Using Large Language
Models in Behavioral Science Interventions: Promise & Risk.”
Behavioral Science & Policy 11, no. 1: 98. https://​doi.​org/​10.​1177/​23794​
60725​1344698.
Herhausen, D., S. Ludwig, E. Abedin, N. Ul Haque, and D. de Jong.
2025. “From Words to Insights: Text Analysis in Business Research.”
Journal of Business Research 198: 115491. https://​doi.​org/​10.​1016/j.​jbusr​
es.​2025.​115491.
Hicks, M. T., J. Humphries, and J. Slater. 2024. “ChatGPT Is Bullshit.”
Ethics and Information Technology 26, no. 2: 1–10. https://​doi.​org/​10.​
1007/​s1067​6-­​024-­​09775​-­​5.
Hilliard, A., A. Gulley, A. Koshiyama, and E. Kazim. 2024. “Bias
Audit Laws: How Effective Are They at Preventing Bias in Automated
Employment Decision Tools?” International Review of Law, Computers
& Technology 39, no. 3: 327–343. https://​doi.​org/​10.​1080/​13600​869.​
2024.​2403053.
Hollibaugh, G. E. 2019. “The Use of Text as Data Methods in Public
Administration: A Review and an Application to Agency Priorities.”
Journal of Public Administration Research and Theory 29, no. 3: 474–
490. https://​doi.​org/​10.​1093/​jopart/​muy045.
Isoaho, K., D. Gritsenko, and E. Mäkelä. 2021. “Topic Modeling and
Text Analysis for Qualitative Policy Research.” Policy Studies Journal
49, no. 1: 300–324. https://​doi.​org/​10.​1111/​psj.​12343​.
James, S., C. Harbron, J. Branson, and M. Sundler. 2021. “Synthetic
Data Use: Exploring Use Cases to Optimise Data Utility.” Discover
Artificial Intelligence 1, no. 1: 15. https://​doi.​org/​10.​1007/​s4416​3-­​021-­​
00016​-­​y.
Jenkins, K. 2023. “Synthetic Data and Public Policy: Supporting Real-­
World Policymakers With Algorithmically Generated Data.” Policy
Quarterly 19, no. 2: 29–39. https://​doi.​org/​10.​26686/​pq.​v19i2.​8234.
Kang, J., P. Han, T. Zhang, and L. Gong. 2025. “PolicySimEval: A
Benchmark for Evaluating Policy Outcomes Through Agent-­Based
Simulation.” https://​doi.​org/​10.​48550/​arXiv.​2502.​07853​.
Keppeler, F., J. Borchert, M. J. Pedersen, and V. Lehmann Nielsen.
2025. “How Ensembling AI and Public Managers Improves Decision-­
Making.” Journal of Public Administration Research and Theory 35, no.
3: 261–276. https://​doi.​org/​10.​1093/​jopart/​muaf009.
Kim, J., and B. Lee. 2023. “Ai-­Augmented Surveys: Leveraging Large
Language Models for Opinion Prediction in Nationally Representative
Surveys.” https://​doi.​org/​10.​48550/​arXiv.​2305.​09620​.
Kunst, J. R., and K. Bierwiaczonek. 2023. “Utilizing AI Questionnaire
Translations in Cross-­Cultural and Intercultural Research: Insights
and Recommendations.” International Journal of Intercultural Relations
97: 101888. https://​doi.​org/​10.​1016/j.​ijint​rel.​2023.​101888.
Laver, M., K. Benoit, and N. Sauger. 2006. “Policy Competition in the
2002 French Legislative and Presidential Elections.” European Journal
of Political Research 45, no. 4: 667–697. https://​doi.​org/​10.​1111/j.​1475-­​
6765.​2006.​00313.​x.
Lee, K., J. Park, S. H. Choi, and C. Lee. 2025. “Ideology and Policy
Preferences in Synthetic Data: The Potential of LLMs for Public Opinion
Analysis.” Media and Communication 13: 77. https://​doi.​org/​10.​17645/​
mac.​9677.
Liotard, I., and V. Revest. 2018. “Contests as Innovation Policy
Instruments: Lessons From the US Federal Agencies' Experience.”


## Page 14

14
Public Administration Review, 2026
Technological Forecasting and Social Change 127: 57–69. https://​doi.​
org/​10.​1016/j.​techf​ore.​2017.​07.​008.
McDonald, B. D., J. L. Hall, J. O'Flynn, and S. van Thiel. 2022. “The
Future of Public Administration Research: An Editor's Perspective.”
Public Administration 100, no. 1: 59–71. https://​doi.​org/​10.​1111/​padm.​
12829​.
Meijer, A. 2025. “Design Science in Public Administration: Producing
Both Situational Interventions and Generic Knowledge.” Perspectives on
Public Management and Governance 8, no. 1: 1–11. https://​doi.​org/​10.​
1093/​ppmgov/​gvae012.
Mergel, I., and K. C. Desouza. 2013. “Implementing Open Innovation in
the Public Sector: The Case of Challenge.Gov.” Public Administration
Review 73, no. 6: 882–890. https://​doi.​org/​10.​1111/​puar.​12141​.
Mišić, J., R. van Est, and L. Kool. 2025. “Good Governance of Public
Sector AI: A Combined Value Framework for Good Order and a Good
Society.” AI and Ethics 5, no. 4: 4875–4889. https://​doi.​org/​10.​1007/​
s4368​1-­​025-­​00751​-­​3.
Nath, R., and R. Manna. 2023. “From Posthumanism to Ethics of
Artificial Intelligence.” AI & SOCIETYAi & Society 38, no. 1: 185–196.
https://​doi.​org/​10.​1007/​s0014​6-­​021-­​01274​-­​1.
Nejjar, M., L. Zacharias, F. Stiehle, and I. Weber. 2025. “LLMs for
Science: Usage for Code Generation and Data Analysis.” Journal of
Software: Evolution and Process 37, no. 1: e2723. https://​doi.​org/​10.​1002/​
smr.​2723.
Olivos, F., and M. Liu. 2025. “ChatGPTest: Opportunities and Cautionary
Tales of Utilizing AI for Questionnaire Pretesting.” Field Methods 37,
no. 4: 277–290. https://​doi.​org/​10.​1177/​15258​22X24​1280574.
Pennebaker, J. W., M. R. Mehl, and K. G. Niederhoffer. 2003.
“Psychological Aspects of Natural Language Use: Our Words, Our
Selves.” Annual Review of Psychology 54, no. 1: 547–577.
Pihlajamaa, M., and M. Merisalo. 2021. “Organizing Innovation
Contests for Public Procurement of Innovation: A Case Study of Smart
City Hackathons in Tampere, Finland.” European Planning Studies 29,
no. 10: 1906–1924. https://​doi.​org/​10.​1080/​09654​313.​2021.​1894097.
Qu, Y., and J. Wang. 2024. “Performance and Biases of Large Language
Models in Public Opinion Simulation.” Humanities and Social Sciences
Communications 11, no. 1: 1–13. https://​doi.​org/​10.​1057/​s4159​9-­​024-­​
03609​-­​x.
Rocklage, M. D., S. He, D. D. Rucker, and L. F. Nordgren. 2023. “Beyond
Sentiment: The Value and Measurement of Consumer Certainty in
Language.” Journal of Marketing Research 60, no. 5: 870–888. https://​
doi.​org/​10.​1177/​00222​43722​1134802.
Romme, A. G. L., and A. Meijer. 2020. “Applying Design Science in
Public Policy and Administration Research.” Policy & Politics 48, no. 1:
149–165. https://​doi.​org/​10.​1332/​03055​7319X​15613​69998​1234.
Routledge, A. J. 2025. “Has the World Gone Botshit Crazy? A Response
to the Frankfurtian Critique of ChatGPT in Higher Education.” Ethics
and Information Technology 27, no. 4: 1–14. https://​doi.​org/​10.​1007/​
s1067​6-­​025-­​09869​-­​8.
Schäper, T., C. Jung, J. N. Foege, M. L. Bogers, S. Fainshmidt, and S.
Nüesch. 2023. “The S-­Shaped Relationship Between Open Innovation
and Financial Performance: A Longitudinal Perspective Using a Novel
Text-­Based Measure.” Research Policy 52, no. 6: 104764. https://​doi.​org/​
10.​1016/j.​respol.​2023.​104764.
Simon, H. A. 1969. The Science of the Artificial. MIT Press.
Struthers, C. L., and C. Ritzler. 2024. “Advocacy Strategies in State
Preemption: The Case of Energy Fuel Bans.” Policy Studies Journal 52,
no. 2: 257–282. https://​doi.​org/​10.​1111/​psj.​12517​.
Suarez, F. F. 2004. “Battles for Technological Dominance: An Integrative
Framework.” Research Policy 33, no. 2: 271–286. https://​doi.​org/​10.​
1016/j.​respol.​2003.​07.​001.
Tan, J., and Y. Chandra. 2025. “Debate: AI as a Framework for Public
Service Innovation.” Public Money & Management 45: 1–3. https://​doi.​
org/​10.​1080/​09540​962.​2025.​2505206.
Tausczik, Y. R., and J. W. Pennebaker. 2010. “The Psychological
Meaning of Words: LIWC and Computerized Text Analysis Methods.”
Journal of Language and Social Psychology 29, no. 1: 24–54. https://​doi.​
org/​10.​1177/​02619​27X09​351676.
Terwiesch, C., and K. Ulrich. 2009. Innovation Tournaments: Creating
and Selecting Exceptional Opportunities. Harvard Business Press.
Tong, S., K. Mao, Z. Huang, Y. Zhao, and K. Peng. 2024. “Automating
Psychological Hypothesis Generation With AI: When Large Language
Models Meet Causal Graph.” Humanities and Social Sciences
Communications 11, no. 1: 1–14. https://​doi.​org/​10.​1057/​s4159​9-­​024-­​
03407​-­​5.
Valle-­Cruz, D., and R. García-­Contreras. 2023. “Towards AI-­Driven
Transformation and Smart Data Management: Emerging Technological
Change in the Public Sector Value Chain.” Public Policy and
Administration 40, no. 2: 254–275. https://​doi.​org/​10.​1177/​09520​76723​
1188401.
Wang, H. H., E. W. Cheng, X. Chen, and H. Liang. 2025. “How
Institutionalized Feedback Works: Online Citizen Complaints and
Local Government Responsiveness in China.” Governance 38: e12907.
https://​doi.​org/​10.​1111/​gove.​12907​.
Williams, H. 2012. “Innovation Inducement Prizes: Connecting
Research to Policy.” Journal of Policy Analysis and Management 31, no.
4: 752–776. https://​doi.​org/​10.​1002/​pam.​21638​.
Zambrano-­Gutiérrez, J. C., and J. A. de Puppim Oliveira. 2022. “The
Dynamics of Sources of Knowledge on the Nature of Innovation in
the Public Sector: Understanding Incremental and Transformative
Innovations in Local Governments.” Journal of Public Administration
Research and Theory 32, no. 4: 656–670. https://​doi.​org/​10.​1093/​jopart/​
muab053.
Zhou, E., and D. Lee. 2024. “Generative Artificial Intelligence, Human
Creativity, and Art.” PNAS Nexus 3, no. 3: 1–8. https://​doi.​org/​10.​1093/​
pnasn​exus/​pgae052.
Supporting Information
Additional supporting information can be found online in the
Supporting Information section. Data S1: Appendix.

