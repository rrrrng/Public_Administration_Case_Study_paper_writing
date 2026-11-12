# Public Administration Review - 2025 - Whetsell - Applied Causal Inference in Pub

## Page 1

Public Administration Review, 2025; 85:1771–1787
https://doi.org/10.1111/puar.70009
1771
Public Administration Review
RESEARCH ARTICLE
OPEN ACCESS
Applied Causal Inference in Public Sector Networks
Travis A. Whetsell1  |  Michael D. Siciliano2
1Jimmy and Rosalynn Carter School of Public Policy, Georgia Institute of Technology, Atlanta, Georgia, USA  |  2Department of Public Policy, Management,
and Analytics, University of Illinois Chicago, Chicago, Illinois, USA
Correspondence: Travis A. Whetsell (travis.whetsell@gatech.edu)
Received: 1 May 2024  |  Revised: 15 March 2025  |  Accepted: 1 July 2025
Keywords: causal inference | network governance | social network analysis
ABSTRACT
Public administration research has increasingly turned to network analysis to understand complex inter-­organizational and
interpersonal dynamics. While the discipline has made significant progress in analyzing networks, it has yet to adequately
address causality. This gap limits our ability to provide evidence-­based insights to practitioners who must make strategic
decisions within networks. This article calls for the systematic integration of causal design into network research. We iden-
tify challenges that complicate causal analysis and discuss a set of practical research designs to address threats to validity.
Borrowing insights from adjacent disciplines, we demonstrate how the logic of causal inference can be applied to public sector
networks. We aim to equip scholars and practitioners with the tools to evaluate causal relationships in networks.
1   |   Introduction
Network scholars in public administration have produced
a variety of insights on a range of topics related to inter-­
organizational networks in the public sector. As Siciliano and
Whetsell (2023) recently argued, these insights have not yet
led to a systematic understanding of causality in the formation
and performance of public sector networks. Practitioners and
scholars alike continue to wonder, now that we understand
the contours of a network, what can we do to improve its func-
tioning. How do we know that these actions produced our in-
tended effects? These questions demand causal designs which
have yet to be explored in our discipline. In contrast, schol-
ars in adjacent disciplines have been calling for more inquiry
into causal inference in social networks (Fowler et al. 2011;
Aral 2016; Rogowski and Sinclair 2017; An et al. 2022). We
extend and develop these insights and provide a non-­technical
overview for public administration. Thus, our intention is not
to develop new designs or strategies for causal inference, but
rather to highlight the opportunities for conducting causal
research on public sector networks by applying the logic and
methods of modern research design (Cunningham  2021;
Morgan and Winship 2014; Angrist and Pischke 2009).
The approach to social networks in this article draws on com-
plexity theory and network science (Simon  2019; Miller and
Page 2009; Morçöl 2013; Barabási 2016). We define social net-
works as the complex structures that emerge from interactions
between actors. Social networks are thus comprised of dyadic
and actor-­level information. While the existing network inter-
vention literature calls attention to the active manipulation of
networks, and thus is closely associated with causal designs,
it has generally focused on personal networks in public health
contexts (Valente  2012). Public administration offers a more
diverse setting for the analysis of networks at the institutional
(Siciliano and Whetsell  2023), interorganizational (Kapucu
and Hu 2020), and interpersonal levels (Whetsell et al. 2021).
By inference, we generally mean a systematic process by which
conclusions are generated from data, evidence, or facts.1
However, this broad definition leaves out a critical element of
causal inference. In the words of Imbens and Rubin  (2015),
This is an open access article under the terms of the Creative Commons Attribution-NonCommercial-NoDerivs License, which permits use and distribution in any
medium, provided the original work is properly cited, the use is non-commercial and no modifications or adaptations are made.
© 2025 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.


## Page 2

1772
Public Administration Review, 2025
“causality is tied to an action (or manipulation, treatment, or
intervention)” (p. 4). For this reason, causality cannot be fully
identified through probabilistic analysis of variables alone.
Rather, as Pearl (2009) argues, “causal relationships are onto-
logical, describing objective physical constraints in our world”
(p. 25). Public sector networks offer a unique setting for study-
ing various policy changes, treatments, and administrative in-
terventions. However, very little attention has been paid to the
topic so far.
This article suggests attention to five basic research designs for
understanding causal inference in public sector networks: (1)
observational studies of networks using descriptive and stochas-
tic methods that lack active interventions or control networks;
(2) simulation studies that leverage computational resources to
generate test environments for network interventions; (3) natu-
ral experiments, where intervention occurs organically in one or
more network(s) accompanied by an analysis of a conceptually
adjacent comparison network(s); (4) network field experiments,
where researchers actively intervene in real-­world networks and
compare effects to control or comparison networks; and lastly, (5)
laboratory network experiments that design interventions and
implement randomization to treatment and control networks.
The more general purpose of this article is to draw attention
to research designs for causal inference in network settings.
Networks pose challenges to the traditional methods of impact
evaluation. This article addresses these challenges by applying
modern causal inference methods to public sector networks.
This is important to the development of network studies in
public administration for both researchers seeking to develop
network-­based research designs and public managers seeking
to understand how their actions within networks might help or
hinder the achievement of public policy or administrative aims.
Without a sense of causality in networks, our advice to man-
agers will remain limited to case studies of network formation
and effects, and public administration will continue to lack an
understanding of “what works” to improve a network's capacity
and performance (Provan and Milward 2001).
2   |   Development of Causal Inference in Social
Networks
As noted above, causal inference requires manipulation (Imbens
and Rubin 2015). Social network researchers have focused on in-
tervention as the term of art for inferential designs in social net-
work settings. Valente (2012) defines network interventions as
“purposeful efforts to use social networks or social network data
to generate social influence, accelerate behavior change, im-
prove performance, and/or achieve desirable outcomes among
individuals, communities, organizations, or populations” (p.
49). The subject of network interventions as a topic in public ad-
ministration is very new. Few articles have explicitly sought to
analyze the topic.2
The network interventions literature has origins in clinical psy-
chology and social work research emphasizing the relevance of
social networks in mental health treatment and outcomes, often
referred to as “network therapy” (Speck and Rueveni  1969).
This literature begins in the late 1960s and analyzes therapeu-
tic interventions for individuals that leverage family, friend,
and broader social ties as a component of treatment. For exam-
ple, Attneave  (1969) examines therapeutic network interven-
tions in the social context of Native American tribes. Similarly,
Rueveni (1975) describes a therapeutic process involving a series
of network-­based counseling sessions, which included extended
family, friends, and neighbors. This literature largely utilizes
ego-­centered networks that are mapped outward from the pa-
tient. Such networks take on various types of ties, including
material resources and emotional exchanges, as well as broader
“norming” processes and structural conditions that affect pa-
tient outcomes. Scholars here suggest network interventions
fall under three model types: helping patients integrate better
into existing networks, helping patients generate more robust
connections, and helping patients understand their positioning
within a social network (Hurd et al. 1981).
Later, Cohen and Adler  (1984) assessed the effectiveness of
network interventions in gerontology, noting the development
of a standard protocol for data collection, referred to as the
“Network Analysis Profile”. They designed an evaluation of its
use in an observational study of a senior living facility. However,
as Auslander and Litwin (1987) noted, very few attempts had
been made to measure the effects of network interventions on
social support for patients. Subsequent research began to em-
ploy techniques designed to elicit causal inference. For example,
Calsyn et al. (1998) used a randomized control trial (RCT) to
assess the effectiveness of network interventions for clients in
the mental health and homelessness context. Clinical research
showed notable improvement in the application of social net-
work concepts, protocols for network intervention by social
workers (Pinto 2006), and the application of the tools of causal
inference to establish impact (Soyez et al. 2006). However, many
studies still did not explicitly utilize formal network analysis in
terms that many contemporary network scientists would expect.
Rather, these studies focused on patients and clients in clinical
settings, where networks are understood in a metaphorical,
qualitative, or ego-­centric manner.
At the same time, the network intervention approach began
to gain momentum in the public health literature. As a result,
Summary
•	 Public managers frequently grapple with tough ques-
tions about the efficiency and effectiveness of pro-
grams and policies implemented in network-­based
settings.
•	 Network analysis in public administration continues
to largely focus on the exploration and description of
network structures and processes but lacks attention
to causal inference.
•	 To address the question of “what works” in public sec-
tor networks, more resources and research should be
committed to large-­scale data collection and carefully
crafted interventions.
•	 This article identifies opportunities and challenges of
leveraging causal research design in the network set-
ting and proposes a basic set of strategies for generat-
ing causal insights.


## Page 3

1773
Public Administration Review, 2025
a stronger methodological shift occurred from clinical to in-
ferential frameworks. For example, El-­Bassel et  al.  (2006)
conducted a study utilizing random selection to explain the
effects of network intervention on risk behaviors in the con-
text of HIV/AIDS. Similarly, Sherman et al. (2009) and Latkin
et  al.  (2009) analyzed the effects of peer network interven-
tions versus life skill interventions on methamphetamine and
HIV/AIDS risk behaviors using a randomization and repeated
measurements approach. Yet, as Latkin and Knowlton (2015)
suggested, the literature focused primarily on ego-­centric per-
sonal networks, with fewer articles branching into sociomet-
ric networks.
In 2012, Thomas Valente published “Network Interventions” in
Science, which provided a descriptive typology of network inter-
vention methods directly leveraging tools from network science.
As he suggested, network interventions tended to fall into four
categories: individual, segmentation, induction, and alteration.
The clinical approach exemplifies the individual strategy, while
the public health approach to targeting segmented vulnerable
groups and inducing network processes tends to exemplify both
the segmentation and the induction approaches. Less research
has been conducted using the alteration approach, which re-
quires explicit information about network structure in order to
make informed choices about which nodes or ties to target for
alteration, that is, addition or deletion. Further, Valente's (2012)
conceptualization reflected the increasing necessity to go be-
yond metaphors and engage in the collection and formal analy-
sis of social network data.
The approach suggested by Valente (2012) further coincided
with newer developments in inferential social network anal-
ysis, which included the development of exponential random
graph models (ERGMs) and stochastic actor-­oriented models
(SAOMs) (Lusher et al. 2013; Snijders et al. 2010). For exam-
ple, Steglich et al. (2012) used SAOMs to estimate the social
network determinants of smoking in school children, with
implications for smoking cessation interventions. Similarly,
Haas and Schaefer (2014) conducted a study on the asymmet-
ric effects of peer influence on starting and quitting smoking
in adolescents, using the SAOM approach. Henry et al. (2016)
used ERGMs to estimate the effects of physical activity on
friendship formation among school children, suggesting im-
portant context factors for interventions targeting exercise.
El-­Sayed et  al.  (2013) employed a simulation approach to
study network interventions among well-­connected nodes
in the context of obesity. These inferential network analysis
approaches combine observational data with computational
elements of simulation to generate inferences about interven-
tions (Cranmer et al. 2020); though these inferences are not
necessarily causal.
Building on the causal evaluation of network interventions in
the public health setting, Hunter et al. (2019) conducted a ret-
rospective meta-­analysis of 37 studies. They found 27 RCTs and
several other studies with varying designs, including partial
RCTs, cluster RCTs, randomized placebo-­controlled designs,
randomized crossovers, controlled before and after designs,
and quasi-­experimental designs. They categorize every study by
Valente's (2012) taxonomy, finding that the majority use individ-
ual and induction strategies. While the outcomes of these studies
are not of interest here, Hunter et al. (2019) note that treatment
contamination across groups was a biasing factor. They raise
an important point with respect to inference in network stud-
ies: “the correct way to obtain unbiased effect estimates is not
obvious and certainly nontrivial when individual observations
fail the independence assumptions that are required for conven-
tional analysis” (p. 16), a point which will be discussed at length
in a later section.
As Siciliano and Whetsell  (2023) observed, the vast majority
of network intervention research focuses on interpersonal net-
works and has ignored institutional determinants of network
structure and outcomes. The intervention literature also has
little to say about the world of inter-­organizational networks.
Thus, there was no development in research questions such as:
how do policies and programs affect the formation or dissolu-
tion of ties in governance networks; what are the consequences
for outcomes of interest in governance networks when collab-
oration structures are altered; and how do we assess impact
with respect to policies and programs implemented in an inter-­
organizational network context?3
Research in public administration under the banner of net-
work governance has uncovered a variety of network ele-
ments, leveraging myriad concepts and methods (Siciliano
et al. 2021; Medina et al. 2022). However, much, if not all, of
this work remains fundamentally descriptive, lacking the ele-
ment of intervention. Thus, public administration has avoided
questions of causal inference regarding the impacts of poli-
cies and programs on governance and intra-­organizational
networks. Network studies in public administration have
made incremental movement toward causal inference in the
past decades, but the costs of data collection and intervention
across a large number of networks place considerable con-
straints upon future progress. As Yi and Scholz (2016) state,
“the costs and difficulty in gathering survey data even for a
single network imposes a substantial obstacle for comparing
network performance over a set of independent networks” (p.
249). Given these constraints, the discipline remains under-­
prepared to fully address the practical question of “what
works” in networks.
Early work in public administration lamented the lack of a the-
ory of network formation (Hay and Richards 2000) and aimed
to establish a theory of social exchange, emphasizing shared
agendas and pooled resources. Toke (2000) sought to build up a
formation theory on individual cognitive factors through qual-
itative analysis of discourse. Graddy and Chen (2006) added to
the literature by identifying inputs to network size and scope,
such as resource dependence, using traditional statistical meth-
ods. Much of the early literature treated the network either in a
metaphorical way, that is, “networking” or in an ego-­centric ap-
proach counting the number of partners in a focal organization's
portfolio (Meier and O'Toole 2003). Such studies did not employ
formal social network analysis. At this point, as a discipline,
we were roughly two decades behind developments in parallel
disciplines. For example, Krackhardt  (1988) and Krackhardt
and Stern (1988) had been conducting formal network studies
within organizations since the 1980s. As shown earlier, clinical
psychology and social work have been implementing network
interventions since the 1970s.


## Page 4

1774
Public Administration Review, 2025
Provan and Milward  (1995) and Milward and Provan (1998)
suggested attention to formal network structure. Much of this
work provided a good foundation for the development of net-
work governance. Yet arguably, it was overshadowed by the met-
aphors of network management until an attempt was made to
advance a theory of network effectiveness vis-­à-­vis Provan and
Kenis (2008). This landmark work connected policy domains to
distinct “modes” of network governance, representing a contin-
gency theory of network effectiveness.
Around the same time, more rigorous applications of network
analysis began to be published in public administration and
policy journals. Henry (2011) conducted an analysis of the de-
terminants of network structure, gathering social network data
and leveraging a network correlation method similar to the qua-
dratic assignment procedure (QAP). Berardo and Scholz (2010)
applied ERGMs to estimate the probability of ties forming in
water management networks. Lee et al. (2012) used ERGMs to
analyze formation in regional economic development networks.
Scott and Thomas (2015) used ERGMs for environmental resto-
ration networks. Siciliano (2015) applied ERGMs to the intra-­
organizational context to analyze determinants of network
formation among schoolteachers.
As these studies noted, using the traditional statistical meth-
ods on network data risked biasing estimates due to complex
dependencies in relational data (Robins et al. 2012). What they
further revealed was the effect of a complex set of endogenous
drivers of network formation that had not been fully addressed
in public administration, such as homophily (actors who share
similar traits are more likely to form relationships), transitiv-
ity (the tendency for actors who share a common third party
to also form a relationship), and preferential attachment (the
tendency to form ties with actors who are popular) (Siciliano
et al. 2021).
Nevertheless, there remains limited work that seeks to estab-
lish causal inferences about public action upon networks. As of
this writing, no published studies exist in public administration
that have collected network data and explicitly designed and
implemented a public policy or program to change the shape or
structure of an inter-­organizational network. In public health,
RCTs of network interventions are now so numerous that meta-­
analyses may be conducted on them as a group. There are good
reasons for these disciplinary differences such as cost and au-
thority. But it is time for network scholars in public administra-
tion to address causality and answer the “what-­works” question.
3   |   Causal Questions for Networks in Public
Administration
In the social sciences, the most common framework for thinking
about causal inference has been the potential outcomes frame-
work (Imbens and Rubin 2015). This framework systematizes
the attempt to incorporate counterfactual intuition into state-
ments about causal effects. In other words, what would have
happened in the absence of the intervention?
Equation (1) shows the basic potential outcomes model, where
the treatment effect on individual i is simply the difference in
potential outcomes that would be observed for that individual
in a treated (noted, with a 1 in parentheses) vs. untreated (noted
with a 0) state. The issue is that we can never observe an indi-
vidual in both a treated and untreated state. Our inability to see
the counterfactual for a given individual is known as the funda-
mental problem of causal inference. Consequently, our interest
often moves from individual treatment effects to average treat-
ment effects. Equation (2) shows the average treatment effect,
defined as the difference in expected outcomes when a popu-
lation is treated and untreated. This average treatment effect,
while also unobservable, can be estimated, if we can establish
treatment and control groups that represent a random sample
from the population of interest. If we randomize a population
of individuals into treated and untreated groups, we can rely on
statistical properties to ensure that the groups are equivalent
on all possible confounders. This leaves treatment status as the
only difference between the groups and thus allows for estima-
tion of the average treatment effect. However, randomization
is not often feasible or ethical. Thus, drawing valid inferences
in  situations where actors can select into treatment requires
the elimination of threats to validity through careful research
design.
Before exploring in more detail the tools and approaches one
may use to estimate causal effects with network data, let's first
clarify the types of causal questions public administration and
policy scholars may study. To begin, it is helpful to note that
network-­based questions are defined by the level of analysis
(Siciliano et  al.  2022; Borgatti et  al.  2022; Krackhardt  2010).
Most network questions reside at one of three levels: the network
level, the node level, and the dyad level. These levels are relevant
to any network, regardless of the actor type (people, organiza-
tions, countries) or relationship type (friendship, advice, formal
contracts). Therefore, it is important to distinguish the unit of
analysis from the level of analysis.
The units of analysis are the types of nodes that comprise the
members of the network. So if our nodes are school teachers,
then school teachers are the unit of analysis. If our nodes are
local governments, then local governments are the unit of anal-
ysis. The level of analysis, on the other hand, concerns the struc-
tural features of the network that one is interested in modeling
or explaining. To make this discussion more concrete, let us as-
sume we have a network of 10 cities in a region, and the ties
among them are shared service agreements related to sustain-
ability. At the network level of analysis, we are interested in the
composition and structure of the network as a whole. Perhaps,
one wants to explore the centralization or density of the net-
work. For these measures, we have only a single observation, as
network-­level measures describe the entire network.
At the node level of analysis, we are interested in the structural
positions and performance of the nodes. For example, we may
want to examine how a city's fiscal stress influences its position
in the network, perhaps as measured by betweenness centrality.
In this instance, we would have 10 observations, one for each of
the cities in the network.
(1)
Treatment Effecti = Yi(1) −Yi(0)
(2)
Average Treatment Effect = E[Y(1)] −E[Y(0)]


## Page 5

1775
Public Administration Review, 2025
At the dyadic level of analysis, our interest lies in the presence
and absence of the ties among the nodes. One may be interested
in explaining why service contracts are formed between certain
cities but not others. Because each of the ten cities could possi-
bly have a service contract with nine other cities, the number
of observations at the dyadic level is 90. As evident in this brief
discussion, the level of analysis for a given research question dic-
tates the number of observations one has available to answer that
question. For our example network with 10 cities, we had one
observation at the network level, 10 at the nodal level, and 90 at
the dyadic level (if we assume the relations are symmetric, then
we would have 45 observations at the dyadic level). The level
also determines the amount of dependency and autocorrelation
in the data—an issue we will discuss in more detail later.
In addition to the level of analysis, network research is often
divided into two major branches: antecedents of networks and
consequences of networks (Borgatti and Foster 2003; Siciliano
et al. 2022). The antecedents of networks focus on the various
factors and mechanisms that facilitate or constrain the forma-
tion of ties among the actors. Common theories and mechanisms
of tie formation include homophily, transitivity, and preferential
attachment (Siciliano et al. 2021).
Research focused on the consequences of networks treats the
network and its composition and structural features as the in-
dependent variable. Thus, the emphasis is on understanding the
implications of certain network configurations for the actors and
the system as a whole. Common mechanisms and theories used
to explain the outcomes associated with networks include social
capital (the benefits to actors based on bridging and bonding), cen-
trality (how the structural position of an actor affects its success),
and density (how the overall connectivity of the network affects
its performance) (Medina et al. 2022). Thus, network research is
interested in causation from two directions (VanderWeele and
An 2013). The first direction links various factors, contexts, and
actor attributes and behaviors to the formation of ties. The second
direction is focused on the consequences of network structure and
how actor positions and relationships influence the attributes and
behaviors of those in the network. Overall, researchers in pub-
lic administration are interested in explaining both the anteced-
ents and consequences of networks at different levels of analysis.
Network scholars are also particularly interested in cross-­level
interactions, especially macro–micro and micro–macro linkages.
For more discussion on cross-­level interactions, (see Siciliano
et al. 2022; Snijders and Steglich 2015).
Table 1 summarizes these distinctions and provides represen-
tative causal questions. For this table, we will stick with the ex-
ample above of a regional network comprised of cities working
together on sustainability issues. One could imagine gathering
data on multiple regions as needed by the research question to
gain variation on network-­level variables.
Each of the questions in Table 1 deals with important inquiries
about how government institutions should be designed and in-
centivized to create strong collaborative networks and to under-
stand the implications of those networks on outcomes of interest.
While this example centered on local governments engaged in
sustainability activities, these questions could easily be framed
to consider other relationship types and policy domains as well
as intra-­organizational networks, for example, police officers in
a police department or teachers within a school.
As may be evident to readers familiar with social networks, some
of the proposed treatments are difficult to apply in a random or
exogenous manner. This is a key reason why much of the research
addressing questions similar to the ones posed above has been
based primarily on descriptive and associational analyses. Take
the example of network-­level consequences concerning how
TABLE 1    |    Causal questions for network levels.
Level of analysis
Network antecedents
Network consequences
Network level
Question: Does the creation of regional
institutions dedicated to sustainability increase
collaboration among local governments?
Treatment: Presence or absence
of a regional institution.
Outcome: Level of regional collaboration,
measured by network density.
Question: Does increased regional collaboration
produce better sustainability outcomes?
Treatment: Increase in regional collaboration.
Outcome: Improved sustainability
outcomes for the region.
Node level
Question: Do dedicated sustainability
officers increase the centrality of local
governments in collaboration networks?
Treatment: Presence or absence
of a sustainability officer.
Outcome: Centrality in the collaboration network.
Question: Does movement of local governments
into network bridging positions increase
their ability to meet sustainability goals?
Treatment: Increase in bridging relations.
Outcome: Improved sustainability
outcomes for the local government.
Dyadic level
Question: Does participation in regional forums
increase collaboration between local governments?
Treatment: Mutual participation
in a regional forum.
Outcome: Formation of a collaborative tie.
Question: Does collaboration on
sustainability issues increase goal
alignment between local governments?
Treatment: Presence or absence
of a collaborative tie.
Outcome: Similarity in sustainability goals.


## Page 6

1776
Public Administration Review, 2025
network density may improve sustainability outcomes. A criti-
cal challenge is determining how to increase density in an exog-
enous fashion. What policy levers or changes in rules or norms
might influence tie-­formation decisions to increase connectiv-
ity? Such manipulation of network structures might be difficult
to create outside of the laboratory (Bavelas 1950; Leavitt 1951;
Centola 2010). Or consider the question relating the bridging ties
of a local government to its performance. Exogenously increas-
ing bridging ties for some actors, but not others, may be difficult,
though possible (Carnabuci and Quintane 2023).
A major goal of this article is to encourage scholars in public
administration and policy to pursue and adopt stronger research
designs. Such designs and strategies provide stronger causal
claims and evidence that address the “what-­works” question.
Before considering different methods and strategies for network
inference, we first need to consider the major challenges to mak-
ing causal claims with network data.
4   |   Challenges for Causal Inference
Answering causal questions about networks presents a number
of methodological issues. In this section, we will highlight some
of these challenges. While these challenges are present in most
empirical work, they are often more acute in network studies.
4.1   |   Selection Bias
One of the key challenges, especially in public administration,
arises from the fact that the majority of network-­based studies
rely on observational data (Siciliano et al. 2022). Consequently,
researchers lack experimental control and exogenous variation
on the variable of interest. This leads to concerns about selection
bias. In the potential outcomes framework, considering a binary
treatment, selection bias is defined as:
Selection bias is the difference in expected outcomes between
the treated, T = 1, and the untreated, T = 0, groups, if no treat-
ment was given to either, Y(0) (Cunningham  2021). In other
words, selection bias is the difference in the outcomes we would
expect between the two groups in the absence of treatment. A
classic example is the question of the difference in standardized
test scores between children who attend private school and those
who attend public school (Angrist and Pischke 2009). Because
families with certain characteristics self-­select into having their
children attend private school, we can't simply compare the out-
comes between public and private school children. Those chil-
dren are different in observable and unobservable ways. The
amount of selection bias present would be the difference in stan-
dardized test scores between private and public school children
had both groups of children attended public school.
We typically think of selection concerns with regard to treat-
ment status, such as attending a private school or participating
in a job training program. These same concerns hold in network
settings. For example, if one was interested in exploring varia-
tion in network size and structure between private school and
public school students, we can't consider school status as exog-
enous. In addition, with network data, we are also concerned
with selection into specific ties and network positions. For ex-
ample, a large body of research has found that individuals who
play bridging roles in networks tend to have higher levels of per-
formance, innovation adoption, and pay (Burt 2000, 2009). But
because individuals with certain attributes and personalities
may be inclined toward bridging positions, concerns of selection
bias are warranted. Thus, with regard to networks, network ef-
fect models may be biased to the extent that individuals select
into their network positions. Li (2013) cites a revealing comment
by Fleming and Waguespack (2007). They state: “network anal-
ysis has mainly ignored the problem of separating the causal ef-
fects of position from the intentions of the individual who may
have consciously and strategically created the position” (p. 177).
4.2   |   Omitted Variable Bias
Omitted variable bias (OVB) is a common concern for most em-
pirical analyses. As widely discussed in econometrics textbooks
(Wooldridge 2008), the coefficient on the variable of interest in
a regression model will suffer OVB if two conditions are met.
First, the variable of interest has to be correlated with the ex-
cluded variable, that is, the one omitted from the model. Second,
the variable that was excluded must be correlated with the out-
come of interest.
Though less often discussed, network-­based methods of infer-
ence, such as ERGMs and SAOMs, can also suffer from OVB.
Therefore, researchers need to carefully consider the data-­
generating process and include all relevant variables. For exam-
ple, suppose one is interested in the effect of transitivity on tie
formation in a network but leaves out an important homophily
term. In that case, the coefficient on transitivity will be biased,
as clustering in networks is also driven by homophily.
More generally, in network models, there are two common vari-
able types that raise concerns with OVB: shared contexts and
shared relations. Shared contexts are the common environments
and settings in which people interact. Shared contexts include
work and school environments, social institutions (churches,
soccer leagues, etc.), and geography. These shared contexts can
influence both the likelihood of two actors forming a relation-
ship as well as their attitudes and behaviors. If relevant shared
contexts are not accounted for, the coefficients of interest may
be biased.
Omitting shared relations is the second variable of concern.
All network studies need to bound the network in some fash-
ion. The bounding process can omit key actors from consider-
ation. For example, a study of teachers may bound the network
based on the school in which one works. But if teachers form
meaningful ties with peers in other schools, then it is likely that
these ties shape not only their behavior in the school but also
the ties they form. Regarding the latter, models of network for-
mation based on a bounded network will be misleading if there
are prominent omitted actors who have ties with members of
the bounded network. For a simple example, consider Figure 1.
The large circle bounds the network, and a single node, actor E,
has been left out. E has ties with the actors in the network, but
Selection Bias = E[Y(0) ∣T = 1] −E[Y(0) ∣T = 0]


## Page 7

1777
Public Administration Review, 2025
those ties are not witnessed as E was excluded from the study.
Based on the bounded network, one might conclude that there is
no clustering. But that conclusion would change if actor E were
considered.
4.3   |   Network Dependence
One of the major underlying assumptions of standard sta-
tistical analysis is that observations are independent and
identically distributed (IID). The IID assumption states that
(i) the outcome or behavior of one observation does not in-
fluence the outcomes or behavior of another and that (ii) the
observations come from the same probability distribution
(Wooldridge 2010). Random sampling is a key method for ob-
taining data that is IID. However, for most network studies,
random sampling is not possible or desirable since researchers
are specifically interested in collecting data on actors who are
thought to be connected to one another. Further, the failure to
properly account for network dependence can result in biased
parameter estimates. As noted by Cranmer et al. (2020), mod-
els designed for different types of dependent data, for example,
hierarchical modeling, spatial modeling, gravity models, and
so forth, are often not adequate to account for complex net-
work dependencies.
Concerns about non-­independence primarily affect nodal and
dyadic level analyses. At the nodal level, the primary concern is
network autocorrelation. Network autocorrelation arises when
attribute or outcome values for nodes are similar to those of their
alters. This similarity can occur through a variety of forces, and
(especially with cross-­sectional data), it can be very difficult
to determine which is driving the autocorrelation (Shalizi and
Thomas 2011). Three forces acting on node level outcomes to
consider are contagion, homophily, and shared contexts/en-
vironments. Contagion, or social influence, is the process by
which ideas, attitudes, and behaviors spread through social
interaction (Friedkin and Johnsen 2011). Actors who are con-
nected to one another may begin to think and act in a similar
manner due to their interactions. The issue of contagion will
also be discussed below in the section on network interference
and spillovers. Tendencies toward homophily have been well
documented in a variety of settings, from youth friendships
(Goodreau et  al.  2009) to organizational networks where ties
are driven by similar missions and funding sources (Atouba and
Shumate 2015).
Similarly, at the dyadic level, non-­independence and auto-
correlation is a very significant concern. Autocorrelation at
the dyadic level arises through several processes. Consider a
directed network represented as an adjacency matrix, where
the i, j cell indicates the presence or absence of a relationship
between actor i and actor j. In the matrix, all of the cells in
row i have actor i as the sender. And all of the cells in col-
umn j have j as the receiver. So any attribute about i or j that
makes them more outgoing or attractive leads to correlation
among the dyads containing that actor. More problematic,
however, are higher-­order structural dependencies. The dyads
in the network are not only dependent upon the actors who
comprise each dyad (e.g., actors i and j) but potentially all
other dyads in the network, which is a primary reason that
standard statistical models are inappropriate in the network
context. The old adage “a friend of a friend is a friend” is a
common example. Two actors in a network are much more
likely to become friends if they have a friend in common, often
referred to as transitivity. Thus, we can't simply look at actors
i and j to assess the likelihood that they are connected, we
need to know the status of their relationship with all other
actors in the network. A number of network models have
emerged that attempt to account for or directly model these
higher-­order dependencies. These network models include the
QAP (Krackhardt 1988), ERGMs (Lusher et al. 2013; Robins
et al. 2007), and SAOMs (Snijders 2017; Snijders et al. 2010).
At the network level, the assumption of independence becomes
much more tenable. For example, if we gather network data on
local government collaborations for sustainability in different
metropolitan regions around the country, we could argue that
each regional network operates in relative independence from
one another. While independence can be gained, the data col-
lection demands for statistical analysis when the network is the
level of analysis are much higher (Yi and Scholz 2016; Siciliano
et  al.  2022). Despite these challenges, public administration
scholars have continued to increase the sample size of their
network-­level studies. Research now includes analyses on doz-
ens or more networks (Wang 2016; Yi 2018; Raab et al. 2015).
While these studies have a larger N, they do not apply a causal
identification strategy or rely on exogenous variation to obtain
causal estimands.
4.4   |   Network Interference and Spillovers
Since social networks are objects explicitly defined by inter-
dependence between actors, interventions or treatments on
individuals or groups within networks often violate a key
assumption in causal inference: no interference between
treated and untreated units (Sobel  2006). This assumption
is a central component of the stable unit treatment value as-
sumption (SUTVA), which requires that the outcome observed
for one actor does not depend on the treatment assigned to
FIGURE 1    |    Omission by network boundary.


## Page 8

1778
Public Administration Review, 2025
other actors (Rubin 1980). In other words, the assumption is
that there are no spillover effects (Leung 2020; Bhattacharya
et al. 2020). A related concept is individual treatment response
(Manski 2013) which also assumes independence of treatment
effects.
A classic example of non-­interference is a medical trial where pa-
tients are randomly assigned to take an experimental drug or a
placebo. Because those who participate in the trial are assumed
to be independent of one another and because the treatment as-
signment of one participant has little influence on the potential
health outcome of others, non-­interference is usually thought to
hold in these settings (Hong and Raudenbush 2013). In contrast,
consider a public administration example, where several local
governments out of dozens in a region hired a sustainability
director. Assume a study was interested in testing whether the
presence of a sustainability director improves the sustainabil-
ity initiatives of the “treated” local governments. Because the
local governments are all part of the same region and interact
to coordinate and address regional challenges and sustainability
issues, non-­interference is violated. Indeed, if we consider net-
work formation and network effects, both types of studies will
be affected. On the network formation side, the treatment status
of actors in the network may influence the presence and absence
of the social ties of others. For example, if those cities with a
sustainability director become more active in the network, it is
not only their ties and position that are changing, but that of the
other governments in the region as well. On the network effects
side, social influence may operate whereby the behaviors of one
actor may influence those adopted by others. Perhaps those who
hired a sustainability director tended to set more ambitious sus-
tainability goals and such decisions may influence the goals set
by other cities in the region.
To overcome these issues, cluster-­randomized trials have been
proposed and used in many settings where participants inter-
act. In cluster-­randomized trials, every member of the cluster
is assigned to the same treatment. These techniques have been
widely deployed in educational settings, where entire schools
are randomly treated (Hong and Raudenbush  2013), and de-
velopment economics, where entire communities are randomly
treated (Banerjee et  al.  2010; Crépon et  al.  2013). Such ap-
proaches translate nicely to network settings, where rather than
randomizing treatment at the node level, treatment is assigned
at the network level.
Research on peer effects, which have been one of the most stud-
ied dynamics associated with networks (Bramoullé et al. 2020),
is in fact a study of interference and SUTVA violation. A mo-
tivating question in the network literature has been to develop
an understanding of how the treatment given to actor i has a
causal effect on the outcomes for actor j. Thus, whereas causal
inference in other fields requires non-­interference to hold, net-
work processes and dynamics are of interest because of these
violations.
4.5   |   Other Considerations
There are several other challenges to causal inference in net-
work settings, including simultaneity, measurement error, and
mechanism identification. Simultaneity presents a challenge
for most empirical research. In a typical regression model, con-
cerns with simultaneity arise when the predictor variables and
the outcome variable mutually influence one another. A classic
example from economics is supply and demand. In network set-
tings, concerns with simultaneity arise in at least two scenarios.
First, and as noted earlier, studies that seek to associate an ac-
tor's position with outcomes need to clarify that it is indeed the
structural position that leads to a given outcome, rather than the
presence of the outcome leading to a particular position (Li 2013;
An et al. 2022). Second, in models exploring social influence, in-
dividuals in the network are mutually influencing one another,
making it difficult to discern the direction.
The role of measurement error in biasing parameter esti-
mates is well established in econometrics (Wooldridge  2008).
Measurement error in the explanatory variables causes atten-
uation bias and can lead to incorrect inferences. In relation to
network data, measurement error is a primary concern with
regard to how accurately one is able to capture the social struc-
ture of interest. Studies over several decades have shown that
people often have poor memories of their social interactions
and vary in their ability to accurately recollect them (Bernard
et  al.  1982; Killworth and Bernard  1976; Ertan et  al.  2019;
Casciaro et al. 1999). Unfortunately, there are no easy solutions
here. The researcher must attempt to gather more data, for ex-
ample, through multiple methods, including improved recall
techniques for self-­report data, leveraging complementary data
sources, and in some cases using network data imputation tech-
niques designed to handle missing data (Krause et al. 2018).
Finally, there is the challenge of identifying the specific mecha-
nism that may be at work. Even in the area of peer effects, which
have been the most widely researched network dynamic from
a causal inference perspective, the particular mechanisms that
drive the observed peer effects remain uncertain. As Bramoullé
et al. (2020) note: “A well identified estimation of peer effects
only constitutes a first step in the analysis of social interactions.
Peer effects can have different causes, including complementar-
ities, conformism, social status, social learning, and informal
risk sharing.” (p. 611).
5   |   Research Designs for Network Inference
Literature on causal inference tends to distinguish between
observational studies and experimental studies, where obser-
vational studies lack (i) randomization of subjects to control
and treatment groups and (ii) an intervention designed to elicit
some outcome that has effects in one group but not the other.
The purpose of such control is to establish inferences about
the intervention relative to a counterfactual reality where the
intervention did not take place (Pearl 2009). However, there is
variety within the observational to experimental continuum,
often termed “quasi-­experimental” (Cook et  al.  2002). The
relevant categories presented here include (1) observational
network studies, (2) network simulation studies, (3) natural
network experiments, (4) network field experiments, and (5)
laboratory network experiments. These categories are marked
by variation on (a) the type of network intervention, where
some studies explicitly design network-­based interventions,


## Page 9

1779
Public Administration Review, 2025
and (b) the type of experimental control, where studies imple-
ment randomization or attempt to establish valid comparison
networks.
Regarding the level of experimental control, both observational
studies and natural experiments lack researcher control over
assignment to treatment and control groups. These instances
then require other strategies to identify the missing potential
outcomes needed to identify the treatment effect. It is in such
scenarios where the modern causal inference toolkit is most
applicable, such as difference-­in-­differences, regression dis-
continuity, synthetic control, matching methods, and so forth,
(Cunningham  2021; Imbens and Rubin  2015; Angrist and
Pischke 2009; Morgan and Winship 2014). We will showcase the
use of some of these methods in our examples below.
5.1   |   Observational Network Studies
The first and most common type of network study design in
public administration is the observational study. These tend to
be single network cross-­sections without network interventions
and without control or comparison networks. Thus, these types
of studies lack the essential research design elements necessary
for generating causal inference, that is, intervention and con-
trol. Consequently, such studies tend to focus on correlations
between variables (Siciliano et al. 2022). However, insights from
the causal revolution suggest a number of design strategies that
may enhance inference in the observational setting (Imbens and
Rubin 2015; Cunningham 2021). Despite the limitations of ob-
servational network studies, they continue to be of great impor-
tance to the development of network theory in the discipline.
Many network researchers in public administration are inter-
ested in describing landscapes of interaction between diverse
actors across various policy domains (Nowell et al. 2019; Nowell
and Albrecht 2023). Such studies often identify whole network
statistics, such as centralization, while also generating node po-
sition statistics such as node centrality. Many such studies focus
on estimating the effects of network statistics like node cen-
trality on outcomes like performance (Siciliano 2015; Whetsell
et  al.  2020). These studies often use network metrics within
the context of the standard linear model to determine net-
work effects on other outcomes of interest (Medina et al. 2022).
Generally, network effects studies tend to establish correlations
rather than estimating the effects of network interventions in an
experimental manner.
In network formation studies, it has become standard to em-
ploy inferential models, like ERGMs, to estimate effects on tie
formation. Such models allow researchers to identify endoge-
nous processes that operate in a wide array of social, biological,
and physical networks. These include, for example, reciprocity
(Gouldner 1960), transitivity (Girvan and Newman 2002), and
preferential attachment (Barabási and Albert  1999), which
serve as general tie generation mechanisms across the network.
Extensions of these models exist for temporal network data.
For example, Ingold and Leifeld (2016) compare cross-­sectional
ERGMs to (T)emporal ERGMs and (S)eperable TERGMs to an-
alyze perceived influence in policy networks; Yoon (2023) uses
TERGMs to analyze board inter-­locks in the non-­profit sector;
and Liu and Yi (2024) use TERGMs to analyze the influence of
managers in interlocal agreements.
There are also dyadic processes such as assortative mixing, that
is, homophily and heterophily, which facilitate ties between
nodes based on shared (homophily) or different (heterophily)
attributes (McPherson et  al.  2001). Here researchers collect a
range of attribute data on the nodes of interest, such as age, size,
motivation, sector, and so forth. In addition to considering as-
sortative mixing, these attribute variables can also be utilized as
exogenous predictors of tie formation. For example, in an ERGM
setting, one could look at sender and receiver effects to address
questions of whether public, private, or non-­profit sector organi-
zations are more likely to form ties in a given network (Lusher
et al. 2013). While ERGMs are considered a class of inferential
network models, the research design used to generate the data
determines whether or not causal statements are warranted
not—the method of analysis.
Many observational network studies employ ego-­network ap-
proaches that do not collect sociocentric, or whole network
data, but focus on an ego and its reported ties. Such studies are
more common in the managerial networking literature and are
often considered a type of “implicit network analysis” (Scott and
Ulibarri 2019). These studies cannot account for complex whole-­
network or dyadic processes but can nevertheless address ques-
tions related to the collaborative activities of the actor of interest.
Table 2 describes an approach to research design for a hypothet-
ical observational study that addresses the question of whether
sustainability officers increase inter-­local collaboration of gov-
ernments in regional sustainability networks. The question
connects specific micro-­level mechanisms associated with tie
formation to the overall patterns of behavior in the network. A
sample design is suggested to account for unobserved confound-
ing and spillover effects using techniques related to selection on
observables.4 While this design lacks experimental intervention
or control, we can nevertheless establish relative comparisons
using, for example, matching techniques. While threats to inter-
nal validity are still present, with a careful design, fewer threats
may remain than in descriptive case studies.
5.2   |   Network Simulation Studies
Network simulation studies often specify the rules or processes
of interaction between nodes and permit their manipulation in
order to observe differences in network outcomes. These studies
often dictate that certain node types are more likely to form ties
while others are less likely. Following the framework proposed
by Valente (2012), they may alter networks, adding and remov-
ing nodes, or adding and removing ties, in order to observe
changes in network processes and structures. They may incor-
porate shocks dynamically into a system, for example, modeling
a disaster response by a group of cross-­sector network actors (Li
et al. 2019). Such studies may also simulate a program or policy
intervention designed to stimulate or suppress network activity.
Simulation studies may have a few advantages over observa-
tional studies. For example, such studies can simulate interven-
tions, control/comparison networks, and their dynamics over


## Page 10

1780
Public Administration Review, 2025
time. However, simulation studies are only as good as the as-
sumptions and rules that structure them (Desai 2012). An ad-
vantage is that network simulation may start with assumptions
derived from observed network data (cross-­sectional or panel)
but then incorporate such assumptions into the design rules of
the simulation.
Methodological developments in inferential network analysis,
for example, SAOM, in addition to providing options for longi-
tudinal network models and co-­evolution models, also permit
robust simulation capabilities and may be empirically calibrated
with reference to existing data sets (Steglich and Snijders 2022).
The ERGM framework also provides simulation capabilities in
the network setting. For example, networks can be generated
based on observed network data, and initial parameters on
processes such as reciprocity or transitivity may be adjusted to
simulate potential impacts. Similarly, nodes may be added or
removed to simulate effects on network processes and struc-
ture. More generally, simulation studies are often very useful for
decision-­making, but are also useful in generating inferences in
the face of complexity.
There currently exist only a handful of simulation-­based stud-
ies in public administration. One example is Scott et al. (2019),
who combine network analysis with agent-­based models to sim-
ulate differential effects on collaborative processes. Similarly,
Bitterman and Koliba (2020) employ simulation techniques to
test the effects of collaborative governance design on perfor-
mance outcomes. Lazer and Friedman (2007) conduct a simu-
lation combining agent-­based models and network analysis to
generate theoretical propositions about the effects of communi-
cation patterns in problem-­solving networks on organizational
performance. Koliba, Zia, and Merrill (2019) directly discuss the
use of agent-­based models and simulation techniques in public
administration.
Table 3 describes a hypothetical approach to a research design
for a network simulation study which addresses the following
question: Do principled engagement techniques, targeting pol-
icy belief change, increase cross-­sector collaboration? The de-
sign starts with real world network data to identify the sign
and significance of coefficients on relevant variables, for exam-
ple, homophily, preferential attachment, and so forth. The re-
searcher systematically changes the actors' perceptions of the
theory of change (actor attribute), comparing the results of the
simulation runs with varying levels of researcher intervention.
The verisimilitude of the simulation depends upon empirical
calibration from high quality real world networks.
5.3   |   Natural Network Experiments
In the causal inference literature, a natural experiment is
one where a naturally occurring event is used as a proxy for a
researcher-­designed intervention (Dunning 2012). In the pres-
ent context, the natural experiment represents an event that has
implications for the functioning, structure, and performance of
a network. In the natural experiment, the treatment and control
cannot be randomized, and so the traditional threats to validity
apply, with increased concerns for spillovers and SUTVA viola-
tions mentioned above.
Conditions frequently arise in public administration where
one set of actors experiences the benefits of a particular policy
or program while another does not. Often, policy interventions
are crafted without a conscious understanding of networks, but
such interventions nevertheless have network-­based effects.
For example, industrial policy targeting a particular sector may
seek to enhance or inhibit the development of cooperative rela-
tionships between public, private, and non-­profit organizations
(Mowery 1998) without reference to broader network processes
or structures.
Government intervention in the technology sector is particu-
larly relevant (Bozeman 1994, 2000; Salter and Martin 2001).
Nations compete globally to develop and maintain strategic do-
mestic markets that do not rely too heavily on foreign partners or
investment. These often take an economics approach, but pub-
lic administration is implicated when an inter-­organizational
approach is taken. For example, in the former approach, poli-
cymakers may seek direct subsidies or sanctions that target in-
dividual firms, but in the latter, a network approach may target
TABLE 2    |    Observational network study.
Design elements
Description
Causal question
Do sustainability officers increase their local government's levels of
collaboration (degree centrality) in regional sustainability networks?
Form of intervention
No direct intervention by the researcher, as local governments
self-­select for the presence of the officer.
Level and unit of analysis
Level: Node. Unit: Local governments.
Primary threats to validity
Spillovers: actors in the same regional network influence one another's behavior. Selection bias
and omitted Variable Bias: sustainability officer are not randomly assigned to governments.
Data and analysis strategy
Using an ego-­network survey design asking the city manager about formal collaborative
relationships, sample cities from different regional networks to limit spillover effects.
Identify cities with and without sustainability officers, and use matching methods
on a set of known confounders to identify similar treatment and control cities.
Other analytical techniques to deal with confounding could include, regression
on observables, inverse probability weighting, doubly robust estimation.


## Page 11

1781
Public Administration Review, 2025
cooperation between domestic organizations as a source of na-
tional competitive advantage (Browning et  al.  1995; Whetsell
et al. 2020). Here, key concepts from network governance, such
as the “network administrative organization” are recast as a po-
tential type of intervention mechanism (Provan and Kenis 2008).
Such situations may be reconceptualized for inference in terms
of natural network experiments. In these cases, it is important
for the researcher to gather relational network data across not
only the entire target network but also conceptually adjacent
networks. This has been achieved in the economics and busi-
ness management literature. For example, the literature on
strategic alliances has long recognized the importance of net-
works, and numerous articles compare networks across markets
(Rosenkopf and Schilling 2007; Schilling 2009). However, rarely
do such studies implement network interventions, and random-
ization remains difficult outside of simulation or laboratory
settings.
To build off one example in public policy, Scott (2015) applies
matching to establish comparisons between treated and un-
treated areas, where the intervention is the presence of a collab-
orative forum and the outcome is environmental quality. While
Scott (2015) does not collect network data, such a design could
be applied with the added context of network data to create a
natural network quasi-­experiment design. A hypothetical ex-
ample might be to compare the effects of programs that support
local resilience planning networks in one geographic location
versus another location that receives no such support. Another
example might be to compare the effects of legislation that man-
dates participation of public organizations in collaborative fo-
rums in one jurisdiction versus another with no such mandate.
Table  4 describes an approach to a research design that ad-
dresses how exogenous shocks to interorganizational networks
influence tie formation. The hypothetical natural network ex-
periment asks: Do disaster declarations increase the formation
of disaster preparedness ties between local governments?5 In
this setting, OVB and selection bias are reduced but could still
be present. However, spillover effects remain a pertinent threat
to internal validity.
5.4   |   Network Field Experiments
The key distinction between natural and field experiments is
that the researcher actively intervenes in the treatment net-
work, whereas in the natural experiment, the treatment is im-
plemented by the policymaker without considering network
effects, or the treatment occurs as a natural event. Additionally,
in the field experiment context, researchers must craft control
networks that are not affected by treatment network spillovers.
Network field experiments have been conducted more widely
outside of public administration, having rarely been conducted
on public-­oriented networks with an eye toward public prob-
lem resolution. For example, Hasan and Bagde (2015) estimate
the effects of a college program randomizing peer interaction
on social network growth and measure the effects by conduct-
ing successive waves of network surveys before and after the
peer intervention. Similarly, Carrell et al. (2013) evaluate the
effect of randomizing network composition on academic per-
formance through assignment to control and treatment net-
works. Another interesting example is Lungeanu et al. (2023)
who conducted a field experiment on astronauts training for
deep space travel to determine the effects of isolation on team
structure. While the isolated crew executed its mission in a con-
trolled setting, the researchers constructed comparison teams
of university students to perform similar tasks in a non-­isolated
setting and took repeated measurements of network structure
for both over time.
Table 5 presents a hypothetical approach to a network field ex-
periment that addresses the following question: Do collective
versus individual performance evaluations increase informa-
tion sharing (tie formation) in public schools? In this design, the
researcher working collaboratively with school principals de-
signs an intervention to implement collective performance eval-
uations in schools currently using individualized evaluations.
Since schools could be randomly selected, the typical threats to
internal validity are largely addressed. As with any experiment
that faces non-­compliance, assignment to treatment can be used
as an instrument to capture the average treatment effect for the
compliers (Angrist and Pischke 2009).
TABLE 3    |    Network simulation study.
Design elements
Description
Causal question
Does increasing the degree to which actors share beliefs around a theory of change
lead to increased levels of cross-­sector collaboration in a governance network?
Form of intervention
Researcher manipulates actor-­attributes (beliefs) in an
empirically calibrated agent-­based simulation.
Level and unit of analysis
Level: Network. Unit: Organizations.
Primary threats to validity
Omitted Variable Bias: Empirically calibrated model parameters may be biased due to model
mis-­specification or measurement error in the initial study on which the simulation is calibrated.
Data and analysis strategy
Obtain high quality empirical panel data on one or more networks in the policy area
and geographic area of interest. This data is often a convenience sample based on
already collected data. Analyze data using a stochastic actor-­oriented model, where
actors' perceptions of the theory of change are systematically altered in the population to
observe how increasing alignment (homophily) increases cross-­sector tie formation.


## Page 12

1782
Public Administration Review, 2025
5.5   |   Network Laboratory Experiments
Network-­based laboratory experiments implement experimen-
tal network interventions in controlled environments. Such
experiments have the greatest internal validity and control for
threats common in network settings more effectively. However,
concerns with external validity are often more pronounced.
While network-­based experiments are quite rare, they are
becoming more common. For example, Shore et  al.  (2015)
conducted a laboratory experiment where participants were
assigned to networks of varying structure and played a “who-
dunit” type game. The experiment was designed to test the
effects of network structure on exploration behavior. Another
example is McBride and Hewitt  (2013) who conducted a
laboratory experiment where subjects were shown partial net-
work diagrams of fictional dark networks of illegal activity
and then made to choose which nodes to arrest in order to
determine optimal network disruption decisions. Similarly,
McBride and Caldara  (2013) conducted a laboratory experi-
ment where subjects were shown network diagrams or table
format data in order to make network disruption decisions.
Shifting topics, Takács et  al.  (2018) conducted a laboratory
experiment to test whether referrals and information flows
increase discrimination in the hiring process. Similarly, re-
searchers have conducted network experiments where par-
ticipants are assigned to positions within predetermined
network structures under the assumption that information
and behaviors spread differently given different topologies
(Bavelas 1950; Centola 2010; Shore et al. 2015).
TABLE 4    |    Natural network experiment.
Design elements
Description
Causal question
Do gubernatorial disaster declarations increase the formation
of disaster preparedness ties of cities/counties?
Form of intervention
No direct intervention by the researcher, as gubernatorial disaster
declarations are driven by naturally occurring events.
Level and unit of analysis
Level: Dyadic. Unit: Local governments (cities and counties).
Primary threats to validity
Selection bias and omitted variable bias: assignment to treated/control units
are not random. Spillover effects: Units not affected but aware of disasters may
alter their behavior; actions taken by affected cities influence others.
Data and analysis strategy
Combine longitudinal data on all interlocal agreements formed for a given state around
disaster preparedness with administrative records on disaster declarations affecting specific
cities/counties. Selection bias and omitted variable bias can be reduced with panel data on
prior disaster declarations along with the inclusion of factors influencing likelihood of a
disaster and response. Identifying the proper control variables requires strong theory of the
data generating process, e.g., city fiscal stress may influence disaster prevention and external
collaboration. Use a stochastic actor-­oriented model (SAOM) where the nodes are cities/
counties and the ties are a formal collaborative arrangement for disaster preparedness. The
disaster declaration at t −1 is used as a nodal attribute to predict the formation of disaster
preparedness ties at time t. Include geographic distance as an edge covariate between cities and
an interaction term between distance and alter disaster declaration to help address spillovers.
TABLE 5    |    Network field experiment.
Design elements
Description
Causal question
Do collective versus individual performance evaluations increase
information sharing (tie formation) in public schools?
Form of intervention
Researcher & practitioner design and implement collective
performance program in randomly selected schools.
Level and unit of analysis
Level: Network. Unit: Teachers.
Primary threats to validity
Spillovers: Teachers and schools in same district or region may be aware
of and respond to each other's programmatic changes.
Data and analysis strategy
Randomly select schools for intervention that have existing individual performance
evaluation programs. To avoid spillovers, schools in different districts should be selected.
Gather dyadic social network data on teachers information seeking ties in schools
before and after the intervention. Analyze the networks for changes in structural
cohesion (e.g., average degree, density) using a difference-­in-­differences approach.


## Page 13

1783
Public Administration Review, 2025
To our knowledge there have been no published studies of
laboratory-­based network experiments in public administra-
tion journals. Such studies would bring participants into the
laboratory and randomly assign individuals to a treatment ver-
sus control network to assess the effect of some intervention
strategy and isolate any spillover effects between the networks.
A hypothetical example is described in Table 6. Individuals are
recruited under appropriate ethical guidelines, assigned an
organizational identity (farmers, environmental non-­profits,
and public sector organizations), and then assigned to one of
three experimental conditions representing either centralized,
modular, or decentralized communication network structures.
Participants are then asked to solve a collective action dilemma
and produce a consensus-­based decision. Their time to arrive
at the decision is the outcome. The laboratory setting can be
controlled to eliminate internal threats to validity, but the ex-
ternal threat of generalizability remains.
6   |   Conclusion
While network research in public administration has grown tre-
mendously in the past three decades, the vast majority of this
research continues to be descriptive and observational, lack-
ing the experimental elements of intervention and control. We
need to continue to build on descriptive work but move toward
causal inference in order to address the “what-­works” question.
Siciliano and Whetsell (2023) suggested network interventions
as a framework for thinking about these issues (Valente 2012).
Take the classic example of Provan and Milward (1995), who
found that centralized networks tend to be higher performing.
If public managers seriously consider this insight, what actions
could they take to make their networks more or less centralized,
and how would they demonstrate that their actions produced the
expected outcomes? We have yet to fully address such questions.
Network analysts have made significant progress by generating
studies with larger sample sizes, across diverse contexts, and le-
veraging greater methodological sophistication (Yi et al. 2018;
Wang  2016; Raab et  al.  2015). Despite this progress, identifi-
cation of causality in networks remains elusive. Network ana-
lysts could advance the discipline by shifting toward research
designs that more carefully consider threats to validity, iden-
tify comparison and control networks, and implement network
interventions.
In the previous sections, we have presented questions, chal-
lenges, and research designs for network inference in relatively
distinct containers. Yet these elements often overlap in complex
ways. Network dependency presents challenges and opportuni-
ties to rethink dominant approaches to research design in pol-
icy and program evaluation. While the implementation may be
more or less difficult than our hypothetical examples suggest,
the point is that the use of inferential network methods on data
collected with attention to research design could mark a signifi-
cant step forward in combining insights from network method-
ologists and scholars of causal inference.
In conclusion, we have sought to address fundamental questions
of causal inference in the context of public sector networks.
While network analysis has flourished dramatically in public
administration in recent decades, the vast majority of studies re-
main descriptive, lacking the experimental elements of network
intervention and control. Given this lacuna in public adminis-
tration, we believe it prudent to leverage scholarship from a vari-
ety of disciplines that have made significant advances. With this
additional context in mind, we articulate a core set of questions,
challenges, and research designs relevant to network-­based
causal inference. Hopefully, this article may serve as a point of
departure for researchers seeking to establish causal inferences
in public sector networks.
Conflicts of Interest
The authors declare no conflicts of interest.
Endnotes
1	The Oxford English Dictionary defines inference as “by inductive or
deductive methods; reasoning from something known or assumed to
something else which follows from it.”
2	A Web of Science search conducted in Fall of 2023 (“network interven-
tion*” OR “network-­based intervention*”) under the category of public
TABLE 6    |    Network laboratory experiment.
Design elements
Description
Causal question
Does network structure (centralized, modular, decentralized) affect time to
consensus based decision making when facing collective action dilemmas?
Form of intervention
Researchers randomly assign participants to one of three network structures in the laboratory.
Level and unit of analysis
Level: Network. Unit: Individual participant.
Primary threats to validity
External validity: Behavior in the laboratory may not correspond
to organization level behavior in the real world.
Data and analysis strategy
Recruit individuals to participate in the lab experiment. Randomly assign individuals to
different experimental conditions (network structures). Assign organization specific goals to
individuals, e.g., a collective action problem that concerns a watershed would assign individuals
to represent farms, environmental non-­profits, and governments. Individuals communicate
only through their assigned network structures and attempt to reach consensus on the collective
action problem. Time to reach consensus is compared across experimental conditions.


## Page 14

1784
Public Administration Review, 2025
administration returns three results: (Siciliano and Whetsell 2023; Frank
et al. 2018; Scott and Thomas 2015). The following are the exact search
terms entered into WoS. Please note the web of science category “pub-
lic administration” also includes major policy journals, excluding public
health: WC = “public administration” AND (TS = “network interven-
tion*” OR TS = “network-­based intervention*”). Without category restric-
tions, the result is 534 articles and reviews. For this reason, it is necessary
to review the extant literature outside of public administration.
3	We use the term governance networks, as Koliba, Meek, et al. (2019)
define it: “interorganizational networks comprised of multiple actors,
often spanning sectors and scale, working together to influence the
creation, implementation, and monitoring of public policies” (p. 3).
4	Defined as the practice of drawing inferences from data using compar-
isons that are established from observable characteristics rather than
experimentally (Cunningham 2021).
5	This research design example is based off of the dissertation work of
Medina (2023).
References
An, W., R. Beauvile, and B. Rosche. 2022. “Causal Network Analysis.”
Annual Review of Sociology 48: 23–41.
Angrist, J. D., and J.-­S. Pischke. 2009. Mostly Harmless Econometrics:
An Empiricist's Companion. Princeton University Press.
Aral, S. 2016. “Networked Experiments.” In The Oxford Handbook of the
Economics of Networks, 376–411. Oxford University Press.
Atouba, Y. C., and M. Shumate. 2015. “International Nonprofit
Collaboration: Examining the Role of Homophily.” Nonprofit and
Voluntary Sector Quarterly 44, no. 3: 587–608.
Attneave, C. L. 1969. “Therapy in Tribal Settings and Urban Network
Intervention.” Family Process 8: 192–210.
Auslander, G. K., and H. Litwin. 1987. “The Parameters of Network
Intervention: A Social Work Application.” Social Service Review 61, no.
2: 305–318.
Banerjee, A. V., E. Duflo, R. Glennerster, and D. Kothari. 2010.
“Improving Immunisation Coverage in Rural India: Clustered
Randomised Controlled Evaluation of Immunisation Campaigns With
and Without Incentives.” BMJ 340: c2220.
Barabási, A. L. 2016. Network Science. Cambridge University Press.
Barabási, A.-­L., and R. Albert. 1999. “Emergence of Scaling in Random
Networks.” Science 286, no. 5439: 509–512.
Bavelas, A. 1950. “Communication Patterns in Task-­Oriented Groups.”
Journal of the Acoustical Society of America 22, no. 6: 725–730. https://​
doi.​org/​10.​1121/1.​1906679.
Berardo, R., and J. T. Scholz. 2010. “Self-­Organizing Policy Networks:
Risk, Partner Selection, and Cooperation in Estuaries.” American
Journal of Political Science 54, no. 3: 632–649.
Bernard, H. R., P. D. Killworth, and L. Sailer. 1982. “Informant Accuracy
in Social-­Network Data v. An Experimental Attempt to Predict Actual
Communication From Recall Data.” Social Science Research 11, no. 1:
30–66.
Bhattacharya, R., D. Malinsky, and I. Shpitser. 2020. “Causal Inference
Under Interference and Network Uncertainty.” In Uncertainty in
Artificial Intelligence, 1028–1038. PMLR.
Bitterman, P., and C. J. Koliba. 2020. “Modeling Alternative
Collaborative Governance Network Designs: An Agent-­Based Model of
Water Governance in the Lake Champlain Basin, Vermont.” Journal of
Public Administration Research and Theory 30, no. 4: 636–655.
Borgatti, S. P., and P. C. Foster. 2003. “The Network Paradigm
in Organizational Research: A Review and Typology.” Journal of
Management 29, no. 6: 991–1013.
Borgatti, S. P., M. G. Everett, J. C. Johnson, and F. Agneessens. 2022.
Analyzing Social Networks Using r. Sage.
Bozeman, B. 1994. “Evaluating Government Technology Transfer:
Early Impacts of the ‘Cooperative Technology Paradigm’.” Policy Studies
Journal 22, no. 2: 322–337.
Bozeman, B. 2000. “Technology Transfer and Public Policy: A Review
of Research and Theory.” Research Policy 29, no. 4–5: 627–655.
Bramoullé, Y., H. Djebbari, and B. Fortin. 2020. “Peer Effects in
Networks: A Survey.” Annual Review of Economics 12: 603–629.
Browning, L. D., J. M. Beyer, and J. C. Shetler. 1995. “Building Cooperation
in a Competitive Industry: SEMATECH and the Semiconductor
Industry.” Academy of Management Journal 38, no. 1: 113–151.
Burt, R. S. 2000. “The Network Structure of Social Capital.” Research in
Organizational Behavior 22: 345–423.
Burt, R. S. 2009. Structural Holes: The Social Structure of Competition.
Harvard University Press.
Calsyn, R. J., G. A. Morse, W. D. Klinkenberg, M. L. Trusty, and G.
Allen. 1998. “The Impact of Assertive Community Treatment on the
Social Relationships of People Who Are Homeless and Mentally Ill.”
Community Mental Health Journal 34: 579–593.
Carnabuci, G., and E. Quintane. 2023. “When People Build Networks
That Hurt Their Performance: Structural Holes, Cognitive Style, and
the Unintended Consequences of Person–Network Fit.” Academy of
Management Journal 66, no. 5: 1360–1383.
Carrell, S. E., B. I. Sacerdote, and J. E. West. 2013. “From Natural
Variation to Optimal Policy? The Importance of Endogenous Peer
Group Formation.” Econometrica 81, no. 3: 855–882.
Casciaro, T., K. M. Carley, and D. Krackhardt. 1999. “Positive Affectivity
and Accuracy in Social Network Perception.” Motivation and Emotion
23: 285–306.
Centola, D. 2010. “The Spread of Behavior in an Online Social Network
Experiment.” Science 329, no. 5996: 1194–1197.
Cohen, C. I., and A. Adler. 1984. “Network Interventions: Do They
Work?” Gerontologist 24, no. 1: 16–22.
Cook, T. D., D. T. Campbell, and W. Shadish. 2002. Experimental and
Quasi-­Experimental Designs for Generalized Causal Inference. Vol. 1195.
Houghton Mifflin.
Cranmer, S. J., B. A. Desmarais, and J. W. Morgan. 2020. Inferential
Network Analysis. Cambridge University Press.
Crépon, B., E. Duflo, M. Gurgand, R. Rathelot, and P. Zamora. 2013.
“Do Labor Market Policies Have Displacement Effects? Evidence From
a Clustered Randomized Experiment.” Quarterly Journal of Economics
128, no. 2: 531–580.
Cunningham, S. 2021. Causal Inference: The Mixtape. Yale University
Press.
Desai, A. 2012. Simulation for Policy Inquiry. Springer Science &
Business Media.
Dunning, T. 2012. Natural Experiments in the Social Sciences: A Design-­
Based Approach. Cambridge University Press.
El-­Bassel, N., L. Gilbert, E. Wu, and M. Chang. 2006. “A Social Network
Profile and HIV Risk Among Men on Methadone: Do Social Networks
Matter?” Journal of Urban Health 83: 602–613.
El-­Sayed, A. M., L. Seemann, P. Scarborough, and S. Galea. 2013.
“Are Network-­Based Interventions a Useful Antiobesity Strategy? An
Application of Simulation Models for Causal Inference in Epidemiology.”
American Journal of Epidemiology 178, no. 2: 287–295.
Ertan, G., M. D. Siciliano, and D. Yenigün. 2019. “Perception Accuracy,
Biases and Path Dependency in Longitudinal Social Networks.” PLoS
One 14, no. 6: e0218607.


## Page 15

1785
Public Administration Review, 2025
Fleming, L., and D. M. Waguespack. 2007. “Brokerage, Boundary
Spanning, and Leadership in Open Innovation Communities.”
Organization Science 18, no. 2: 165–180.
Fowler, J. H., M. T. Heaney, D. W. Nickerson, J. F. Padgett, and B.
Sinclair. 2011. “Causality in Political Networks.” American Politics
Research 39, no. 2: 437–480.
Frank, K. A., X. Ran, and W. R. Penuel. 2018. “Implementation of
Evidence-­Based Practice in Human Service Organizations: Implications
From Agent-­Based Models.” Journal of Policy Analysis and Management
37, no. 4: 867–895.
Friedkin, N. E., and E. C. Johnsen. 2011. Social Influence Network
Theory: A Sociological Examination of Small Group Dynamics. Vol. 33.
Cambridge University Press.
Girvan, M., and M. E. J. Newman. 2002. “Community Structure in
Social and Biological Networks.” Proceedings of the National Academy
of Sciences 99, no. 12: 7821–7826.
Goodreau, S. M., J. A. Kitts, and M. Morris. 2009. “Birds of a Feather,
or Friend of a Friend? Using Exponential Random Graph Models
to Investigate Adolescent Social Networks.” Demography 46, no. 1:
103–125.
Gouldner, A. W. 1960. “The Norm of Reciprocity: A Preliminary
Statement.” American Sociological Review 25: 161–178.
Graddy, E. A., and B. Chen. 2006. “Influences on the Size and Scope of
Networks for Social Service Delivery.” Journal of Public Administration
Research and Theory 16, no. 4: 533–552.
Haas, S. A., and D. R. Schaefer. 2014. “With a Little Help From My
Friends? Asymmetrical Social Influence on Adolescent Smoking
Initiation and Cessation.” Journal of Health and Social Behavior 55, no.
2: 126–143.
Hasan, S., and S. Bagde. 2015. “Peers and Network Growth: Evidence
From a Natural Experiment.” Management Science 61, no. 10: 2536–2547.
Hay, C., and D. Richards. 2000. “The Tangled Webs of Westminster and
Whitehall: The Discourse, Strategy and Practice of Networking Within
the British Core Executive.” Public Administration 78, no. 1: 1–28.
Henry, A. D. 2011. “Ideology, Power, and the Structure of Policy
Networks.” Policy Studies Journal 39, no. 3: 361–383.
Henry, T., S. B. Gesell, and E. H. Ip. 2016. “Analyzing Heterogeneity in
the Effects of Physical Activity in Children on Social Network Structure
and Peer Selection Dynamics.” Network Science 4, no. 3: 336–363.
Hong, G., and S. W. Raudenbush. 2013. “Heterogeneous Agents, Social
Interactions, and Causal Inference.” In Handbook of Causal Analysis for
Social Research, 331–352. Springer.
Hunter, R. F., K. de la Haye, J. M. Murray, et al. 2019. “Social Network
Interventions for Health Behaviours and Outcomes: A Systematic
Review and Meta-­Analysis.” PLoS Medicine 16, no. 9: e1002890.
Hurd, G. S., E. Mansell Pattison, and R. Llamas. 1981. “Models of Social
Network Intervention.” International Journal of Family Therapy 3, no.
4: 246–257.
Imbens, G. W., and D. B. Rubin. 2015. Causal Inference in Statistics,
Social, and Biomedical Sciences. Cambridge University Press.
Ingold, K., and P. Leifeld. 2016. “Structural and Institutional
Determinants of Influence Reputation: A Comparison of Collaborative
and
Adversarial
Policy
Networks
in
Decision
Making
and
Implementation.” Journal of Public Administration Research and Theory
26, no. 1: 1–18.
Kapucu, N., and Q. Hu. 2020. Network Governance: Concepts, Theories,
and Applications. Routledge.
Killworth, P., and H. Bernard. 1976. “Informant Accuracy in Social
Network Data.” Human Organization 35, no. 3: 269–286.
Koliba, C. J., J. W. Meek, A. Zia, and R. W. Mills. 2019. Governance
Networks in Public Administration and Public Policy. Routledge.
Koliba, C., A. Zia, and S. Merrill. 2019. “Using Agent-­Based Models
to Study Network and Collaborative Governance.” In Networks and
Collaboration in the Public Sector, 210–231. Routledge.
Krackhardt, D. 1988. “Predicting With Networks: Nonparametric
Multiple Regression Analysis of Dyadic Data.” Social Networks 10, no.
4: 359–381.
Krackhardt, D. 2010. Encyclopedia of Group Processes and Intergroup
Relations, edited by J. M. Levine and M. A. Hogg, vol. 1. Sage.
Krackhardt, D., and R. N. Stern. 1988. “Informal Networks and
Organizational Crises: An Experimental Simulation.” Social Psychology
Quarterly 51: 123–140.
Krause, R. W., M. Huisman, C. Steglich, and T. A. B. Snijders. 2018.
“Missing Network Data a Comparison of Different Imputation
Methods.” In 2018 IEEE/ACM International Conference on Advances in
Social Networks Analysis and Mining (ASONAM), 159–163. IEEE.
Latkin, C. A., and A. R. Knowlton. 2015. “Social Network Assessments
and Interventions for Health Behavior Change: A Critical Review.”
Behavioral Medicine 41, no. 3: 90–97.
Latkin, C. A., D. Donnell, D. Metzger, et al. 2009. “The Efficacy of a
Network Intervention to Reduce HIV Risk Behaviors Among Drug
Users and Risk Partners in Chiang Mai, Thailand and Philadelphia,
USA.” Social Science & Medicine 68, no. 4: 740–748.
Lazer, D., and A. Friedman. 2007. “The Network Structure of
Exploration and Exploitation.” Administrative Science Quarterly 52, no.
4: 667–694.
Leavitt, H. J. 1951. “Some Effects of Certain Communication Patterns
on Group Performance.” Journal of Abnormal and Social Psychology 46,
no. 1: 38–50.
Lee, Y., I. W. Lee, and R. C. Feiock. 2012. “Interorganizational
Collaboration Networks in Economic Development Policy: An
Exponential Random Graph Model Analysis.” Policy Studies Journal 40,
no. 3: 547–573.
Leung, M. P. 2020. “Treatment and Spillover Effects Under Network
Interference.” Review of Economics and Statistics 102, no. 2: 368–380.
Li, M. 2013. “Social Network and Social Capital in Leadership and
Management Research: A Review of Causal Methods.” Leadership
Quarterly 24, no. 5: 638–665.
Li, Q., S. Dong, and A. Mostafavi. 2019. “Modeling of Inter-­
Organizational Coordination Dynamics in Resilience Planning of
Infrastructure Systems: A Multilayer Network Simulation Framework.”
PLoS One 14, no. 11: e0224522.
Liu, I. S., and H. Yi. 2024. “Member Duality and Policy Tourism:
Learning in Interlocal Policy Networks.” Public Administration 102:
1532–1557.
Lungeanu, A., L. A. DeChurch, and N. S. Contractor. 2023. “A Tale
of Three Teams: Effect of Long-­Term Isolation in SIRIUS-­21 on Crew
Interpersonal Networks.” Acta Astronautica 212: 617–623.
Lusher, D., J. Koskinen, and G. Robins. 2013. Exponential Random
Graph Models for Social Networks: Theory, Methods, and Applications.
Cambridge University Press.
Manski, C. F. 2013. “Identification of Treatment Response With Social
Interactions.” Econometrics Journal 16, no. 1: S1–S23.
McBride, M., and D. Hewitt. 2013. “The Enemy You Can't See: An
Investigation of the Disruption of Dark Networks.” Journal of Economic
Behavior & Organization 93: 32–50.
McBride, M., and M. Caldara. 2013. “The Efficacy of Tables Versus
Graphs in Disrupting Dark Networks: An Experimental Study.” Social
Networks 35, no. 3: 406–422.


## Page 16

1786
Public Administration Review, 2025
McPherson, M., L. Smith-­Lovin, and J. M. Cook. 2001. “Birds of a
Feather: Homophily in Social Networks.” Annual Review of Sociology
27, no. 1: 415–444.
Medina, A. 2023. Ebb and Flow in Collaborative Networks: A Longitudinal
Analysis of Network Formation and Evolution. University of Chicago.
Medina, A., M. D. Siciliano, W. Wang, and H. Qian. 2022. “Network
Effects Research: A Systematic Review of Theoretical Mechanisms
and Measures.” American Review of Public Administration 52, no. 7:
513–528.
Meier, K. J., and L. J. O'Toole. 2003. “Public Management and
Educational Performance: The Impact of Managerial Networking.”
Public Administration Review 63, no. 6: 689–699.
Miller, J. H., and S. E. Page. 2009. Complex Adaptive Systems: An
Introduction to Computational Models of Social Life: An Introduction to
Computational Models of Social Life. Princeton University Press.
Milward, H. B., and K. G. Provan. 1998. “Measuring Network Structure.”
Public Administration 76, no. 2: 387–407.
Morçöl, G. 2013. A Complexity Theory for Public Policy. Routledge.
Morgan, S. L., and C. Winship. 2014. “Counterfactuals and Causal
Inference: Methods and Principles for Social Research.” In Analytical
Methods for Social Research, 2nd ed. Cambridge University Press.
Mowery, D. C. 1998. “The Changing Structure of the US National
Innovation System: Implications for International Conflict and
Cooperation in r&d Policy.” Research Policy 27, no. 6: 639–654.
Nowell, B., and K. Albrecht. 2023. “A Population Ecology of Network
Domains.” Public Management Review 26: 1–24.
Nowell, B., M. C. Hano, and Z. Yang. 2019. “Networks of Networks?
Toward an External Perspective on Whole Networks.” Perspectives on
Public Management and Governance 2, no. 3: 213–233.
Pearl, J. 2009. Causality. Cambridge University Press.
Pinto, R. M. 2006. “Using Social Network Interventions to Improve
Mentally Ill Clients' Well-­Being.” Clinical Social Work Journal 34, no.
1: 83–100.
Provan, K. G., and H. B. Milward. 1995. “A Preliminary Theory of
Interorganizational Network Effectiveness: A Comparative Study of
Four Community Mental Health Systems.” Administrative Science
Quarterly 40: 1–33.
Provan, K. G., and H. B. Milward. 2001. “Do Networks Really Work?
A Framework for Evaluating Public-­Sector Organizational Networks.”
Public Administration Review 61, no. 4: 414–423.
Provan, K. G., and P. Kenis. 2008. “Modes of Network Governance:
Structure, Management, and Effectiveness.” Journal of Public
Administration Research and Theory 18, no. 2: 229–252.
Raab, J., R. S. Mannak, and B. Cambré. 2015. “Combining Structure,
Governance, and Context: A Configurational Approach to Network
Effectiveness.” Journal of Public Administration Research and Theory
25, no. 2: 479–511.
Robins, G., J. M. Lewis, and P. Wang. 2012. “Statistical Network
Analysis for Analyzing Policy Networks.” Policy Studies Journal 40, no.
3: 375–401.
Robins, G., T. Snijders, P. Wang, M. Handcock, and P. Pattison. 2007.
“Recent Developments in Exponential Random Graph (p*) Models for
Social Networks.” Social Networks 29, no. 2: 192–215.
Rogowski, J. C., and B. Sinclair. 2017. “Causal Inference in Political
Networks.” In The Oxford Handbook of Political Networks, 131–146.
Oxford University Press.
Rosenkopf, L., and M. A. Schilling. 2007. “Comparing Alliance Network
Structure Across Industries: Observations and Explanations.” Strategic
Entrepreneurship Journal 1, no. 3–4: 191–209.
Rubin, D. B. 1980. “Randomization Analysis of Experimental Data:
The Fisher Randomization Test Comment.” Journal of the American
Statistical Association 75, no. 371: 591–593.
Rueveni, U. 1975. “Network Intervention With a Family in Crisis.”
Family Process 14, no. 2: 193–203.
Salter, A. J., and B. R. Martin. 2001. “The Economic Benefits of Publicly
Funded Basic Research: A Critical Review.” Research Policy 30, no. 3:
509–532.
Schilling, M. A. 2009. “Understanding the Alliance Data.” Strategic
Management Journal 30, no. 3: 233–260.
Scott, T. 2015. “Does Collaboration Make any Difference? Linking
Collaborative Governance to Environmental Outcomes.” Journal of
Policy Analysis and Management 34, no. 3: 537–566.
Scott, T. A., and N. Ulibarri. 2019. “Taking Network Analysis Seriously:
Methodological Improvements for Governance Network Scholarship.”
Perspectives on Public Management and Governance 2, no. 2: 89–101.
Scott, T. A., C. W. Thomas, and J. M. Magallanes. 2019. “Convening
for Consensus: Simulating Stakeholder Agreement in Collaborative
Governance Processes Under Different Network Conditions.” Journal
of Public Administration Research and Theory 29, no. 1: 32–49.
Scott, T., and C. Thomas. 2015. “Do Collaborative Groups Enhance
Interorganizational Networks?” Public Performance & Management
Review 38, no. 4: 654–683.
Shalizi, C. R., and A. C. Thomas. 2011. “Homophily and Contagion Are
Generically Confounded in Observational Social Network Studies.”
Sociological Methods & Research 40, no. 2: 211–239.
Sherman, S. G., C. Sutcliffe, B. Srirojn, C. A. Latkin, A. Aramratanna,
and D. D. Celentano. 2009. “Evaluation of a Peer Network Intervention
Trial Among Young Methamphetamine Users in Chiang Mai, Thailand.”
Social Science & Medicine 68, no. 1: 69–79.
Shore, J., E. Bernstein, and D. Lazer. 2015. “Facts and Figuring: An
Experimental Investigation of Network Structure and Performance
in Information and Solution Spaces.” Organization Science 26, no. 5:
1432–1446.
Siciliano, M. D. 2015. “Advice Networks in Public Organizations: The
Role of Structure, Internal Competition, and Individual Attributes.”
Public Administration Review 75, no. 4: 548–559.
Siciliano, M. D., and T. Whetsell. 2023. “Network Interventions: Applying
Network Science for Pragmatic Action in Public Administration and Policy.”
Perspectives on Public Management and Governance 6, no. 2–3: 67–79.
Siciliano, M. D., W. Wang, and A. Medina. 2021. “Mechanisms of Network
Formation in the Public Sector: A Systematic Review of the Literature.”
Perspectives on Public Management and Governance 4, no. 1: 63–81.
Siciliano, M. D., W. Wang, Q. Hu, A. Medina, and D. Krackhardt. 2022.
Networks in the Public Sector: A Multilevel Framework and Systematic
Review. Cambridge University Press.
Simon, H. A. 2019. The Sciences of the Artificial, Reissue of the Third
Edition With a New Introduction by John Laird. MIT Press.
Snijders, T. A. B. 2017. “Stochastic Actor-­Oriented Models for Network
Dynamics.” Annual Review of Statistics and Its Application 4: 343–363.
Snijders, T. A. B., and C. E. G. Steglich. 2015. “Representing Micro–
Macro Linkages by Actor-­Based Dynamic Network Models.”
Sociological Methods & Research 44, no. 2: 222–271.
Snijders, T. A. B., G. G. Van de Bunt, and C. E. G. Steglich. 2010.
“Introduction to Stochastic Actor-­Based Models for Network Dynamics.”
Social Networks 32, no. 1: 44–60.
Sobel, M. E. 2006. “What Do Randomized Studies of Housing Mobility
Demonstrate? Causal Inference in the Face of Interference.” Journal of
the American Statistical Association 101, no. 476: 1398–1407.


## Page 17

1787
Public Administration Review, 2025
Soyez, V., G. De Leon, E. Broekaert, and Y. Rosseel. 2006. “The Impact
of a Social Network Intervention on Retention in Belgian Therapeutic
Communities: A Quasi-­Experimental Study.” Addiction 101, no. 7:
1027–1034.
Speck, R. V., and U. Rueveni. 1969. “Network Therapy: A Developing
Concept.” Family Process 8: 182–191.
Steglich, C. E. G., and T. A. B. Snijders. 2022. “Stochastic Network
Modeling as Generative Social Science.” In Handbook of Sociological
Science, 73–99. Edward Elgar Publishing.
Steglich, C., P. Sinclair, J. Holliday, and L. Moore. 2012. “Actor-­Based
Analysis of Peer Influence in a Stop Smoking in Schools Trial (ASSIST).”
Social Networks 34, no. 3: 359–369.
Takács, K., G. Bravo, and F. Squazzoni. 2018. “Referrals and Information
Flow in Networks Increase Discrimination: A Laboratory Experiment.”
Social Networks 54: 254–265.
Toke, D. 2000. “Policy Network Creation: The Case of Energy
Efficiency.” Public Administration 78, no. 4: 835–854.
Valente, T. W. 2012. “Network Interventions.” Science 337, no. 6090:
49–53.
VanderWeele, T. J., and W. An. 2013. “Social Networks and Causal
Inference.” In Handbook of Causal Analysis for Social Research, 353–
374. Springer Netherlands.
Wang, W. 2016. “Exploring the Determinants of Network Effectiveness:
The Case of Neighborhood Governance Networks in Beijing.” Journal of
Public Administration Research and Theory 26, no. 2: 375–388.
Whetsell, T. A., A. Kroll, and L. DeHart-­Davis. 2021. “Formal
Hierarchies and Informal Networks: How Organizational Structure
Shapes Information Search in Local Government.” Journal of Public
Administration Research and Theory 31, no. 4: 653–669.
Whetsell, T. A., M. J. Leiblein, and C. S. Wagner. 2020. “Between Promise
and Performance: Science and Technology Policy Implementation
Through Network Governance.” Science and Public Policy 47, no. 1:
78–91.
Wooldridge, J. M. 2008. Introductory Econometrics: A Modern Approach.
ISE-­International Student Edition. Cengage Learning.
Wooldridge, J. M. 2010. Econometric Analysis of Cross Section and Panel
Data. MIT Press.
Yi, H. 2018. “Network Structure and Governance Performance: What
Makes a Difference?” Public Administration Review 78, no. 2: 195–205.
Yi, H., and J. T. Scholz. 2016. “Policy Networks in Complex Governance
Subsystems: Observing and Comparing Hyperlink, Media, and
Partnership Networks.” Policy Studies Journal 44, no. 3: 248–279.
Yi, H., F. S. Berry, and W. Chen. 2018. “Management Innovation and
Policy Diffusion Through Leadership Transfer Networks: An Agent
Network Diffusion Model.” Journal of Public Administration Research
and Theory 28, no. 4: 457–474.
Yoon, N. 2023. “The Antecedents of Nonprofit Board Interlock: A
Longitudinal Examination on Network Structure, Homophily, and
Organizational Attributes.” Nonprofit and Voluntary Sector Quarterly
52, no. 1: 196–221.

