# Unpacking the Influence of Policy Advice Using Citation Network Analysis

## Page 1

Public Administration Review, 2026; 86:430–444
https://doi.org/10.1111/puar.70014
430
Public Administration Review
RESEARCH ARTICLE
OPEN ACCESS
Unpacking the Influence of Policy Advice Using Citation
Network Analysis
Johan Christensen  |  Petra van den Bekerom
Leiden University, Institute of Public Administration, Den Haag, the Netherlands
Correspondence: Johan Christensen (j.christensen@fgga.leidenuniv.nl)
Received: 28 June 2024  |  Revised: 3 July 2025  |  Accepted: 18 July 2025
Keywords: citation network analysis | influence | policy advice
ABSTRACT
Public policy often builds on a large body of policy advice—produced by bureaucrats, advisory bodies, scientists, and consult-
ants—that has accumulated over time about a specific policy problem and appropriate policy responses. Yet, how this body of
policy advice develops and which pieces of advice influence subsequent policy recommendations is poorly understood. We seek
to fill this gap by proposing a novel conceptualization and methodological approach for unpacking the influence of policy ad-
vice on other policy advice. First, we distinguish four conceptual dimensions along which the influence of policy advice varies:
lasting influence, broad influence, influential followers, and influence as broker. Second, we propose citation network analysis
as a methodological tool for measuring these multiple dimensions of influence. We present a set of citation network measures of
influence and illustrate their usefulness by analyzing influence patterns within a large network of Norwegian advisory reports.
1   |   Introduction
Public policy is seldom determined by one specific piece of ad-
vice; rather, it builds on a large body of policy advice—produced
by bureaucrats, advisory bodies, scientists, and consultants—
that has accumulated over time about a specific policy problem
and appropriate policy responses. For instance, political action
to combat climate change has been spurred by a long series of
advisory reports about the dangers of global warming and ef-
fective policy measures to reduce climate gas emissions. Within
this body of policy advice, new advisory reports engage with the
knowledge, arguments, and recommendations presented in pre-
vious advice. Yet, how this body of policy advice develops and
which pieces of advice have the most influence on subsequent
policy recommendations is poorly understood.
One reason for this is that the influence of policy advice varies
in multiple ways. Sometimes, the arguments and recommen-
dations in policy advisory reports leave a lasting mark on dis-
cussions about policy; other advice has short-­term impact but
then quickly fades from view. In some cases, the principles and
proposals advanced by an advisory report shape debates across
a wide range of policy areas, whereas in other cases, the impact
of advice is limited to a narrow policy field. And some advisory
reports have particular impact by shaping other advice that in
turn is influential or by connecting separate clusters of advice.
In this article, we seek to shed light on these patterns of in-
fluence within the body of policy advice, that is, on how pol-
icy advice influences other policy advice. Doing so is key for
understanding the knowledge and premises that underpin
public policies. It is of interest both to scholars seeking to un-
ravel the mechanisms through which evidence informs public
policy-­making (e.g., Head  2016; Jennings Jr. and Hall  2012;
Raymaekers et al. 2026; Cheng et al. 2025) and to those ex-
amining the power and influence of advisory actors (e.g.,
Campbell and Pedersen  2014; Hustedt and Veit  2017). It is
equally relevant for policy-­makers who commission and re-
ceive policy advice and for knowledge providers who seek to
maximize the impact of their analyses and recommendations.
Practitioners are often acutely aware that the influence of pol-
icy advice is multi-­faceted and can follow tortuous paths. Yet,
This is an open access article under the terms of the Creative Commons Attribution-NonCommercial-NoDerivs License, which permits use and distribution in any
medium, provided the original work is properly cited, the use is non-commercial and no modifications or adaptations are made.
© 2025 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.


## Page 2

431
Public Administration Review, 2026
so far, we lack the conceptual and methodological tools for
examining the multiple dimensions of the influence of policy
advice.
The article contributes conceptually and methodologically to
filling this gap. Conceptually, we propose a multidimensional
understanding of the influence of policy advice by unpacking
the temporal, spatial, and network dimensions of influence.
Challenging a one-­dimensional view of influence, our conceptual-
ization highlights that the answer to the question of how influen-
tial an advisory report is depends crucially on what dimension of
influence you look at: lasting influence, broad influence, influen-
tial followers, or influence as broker. Our conceptualization differs
from existing typologies of policy advice influence or knowledge
use, which distinguish the different purposes for which advice is
used (Weiss 1979; Hunter and Boswell 2015) or the different stages
of influence (Knott and Wildavsky 1980; Landry et al. 2003).
Methodologically, we make a novel contribution by applying ci-
tation network analysis as a tool for measuring these multiple
dimensions of the influence of policy advice. In recent years,
there has been growing interest in using data on the sources
cited in policy and advisory documents to map knowledge use in
policy-­making (Bornmann et  al.  2016; Vilkins and Grant  2017;
Christensen 2018; Pattyn et al. 2021; Smith et al. 2021; Karseth
et al. 2022; Christensen and Hesstvedt 2024; Ma and Cheng 2025).
The idea is that citations offer clues about the types of knowledge
and advice that are used in the policy-­making process. However,
existing work mostly relies on simple citation counts; that is, how
often specific (types of) advice documents are cited, which gives a
one-­dimensional view of the influence of a piece of advice. It disre-
gards other relevant information about the citation links between
documents, for instance about the characteristics or timing of the
citing and cited documents or their location within the broader
network of advisory documents.
We argue that citation network analysis can be a powerful
tool to exploit this information to shed light on multiple as-
pects of the influence of advice (see also Christensen  2023).
Citation network analysis—a form of network analysis—maps
and measures relationships between documents using data on
citations between documents. The main elements in citation
network analysis are the “nodes”—that is, the documents—and
the “edges”—that is, the citation links between documents.
Network analysis scholars use information about nodes and the
links between them to examine various features of networks,
including the centrality or importance of the nodes within a net-
work (Wasserman and Faust 1994). In our case, we use citation
network analysis to study variations in the influence of specific
advisory reports within a networked body of advisory reports.
We draw inspiration from work that has used citation network
analysis to study related phenomena, such as the importance of
legal cases within the body of law (Fowler et al. 2007; Lupu and
Voeten 2012) and the scientific impact of academic publications
(e.g., Georgiou 2014). Citation network analysis, we argue, can
enrich our methodological repertoire for examining influence
in policy processes, complementing existing approaches such as
qualitative process-­tracing and discourse analysis and quantita-
tive text analysis (e.g., Klüver 2015; Cross et al. 2021).
We present a set of citation network measures that can be used
to analyze the multiple dimensions of the influence of pol-
icy advice. We also illustrate the usefulness of these measures
for empirical research by applying them to analyze variations
in the influence of advisory reports within a network of 1545
Norwegian Advisory Commission reports spanning nearly a 50-­
year period. These commissions are appointed by government
to analyze policy problems and recommend appropriate policy
solutions, and usually consist of bureaucrats, academics, and in-
terest group representatives. We focus on Norwegian Advisory
Commission reports since they offer a rich empirical material
for analyzing influence patterns within a body of policy ad-
vice that has accumulated over time: Norwegian Commission
reports have since 1972 been published in an openly available
numbered report series, and reports frequently include citations
to previous commission reports (and other knowledge sources).
At the same time, the conceptual and methodological approach
that we propose can be applied broadly to analyze the impact of
advisory documents in different geographical settings, offering a
promising avenue for systematic empirical research in the field.
The rest of the article is structured as follows: In the first part,
we review existing literature of the influence of policy advice
and present a novel conceptualization of the multiple dimen-
sions of influence. In the second part, we introduce citation
network analysis as a method, discuss existing research that
employs citation (network) analysis and present our data. In the
third part, we present a set of citation network measures that tap
into the different conceptual dimensions of the influence of pol-
icy advice, and apply these measures to examine the influence
of Norwegian advisory reports. In the discussion and conclusion
sections, we reflect on the potential and limits of the conceptual
and methodological approach.
2   |   Unpacking the Influence of Policy Advice
2.1   |   Existing Research
Political leaders rely on informed advice to design policies to
address a wide range of societal challenges. Research on “pol-
icy advisory systems” (Halligan 1995; Craft and Halligan 2017)
Summary
•	 Public policy is rarely informed by a single piece of ad-
vice; rather, it builds on a large body of policy advice
that has accumulated over time.
•	 Understanding how this body of policy advice devel-
ops and which pieces of advice have the most influence
on subsequent policy recommendations is essential for
policy-­makers and knowledge providers who seek to
strengthen the evidence basis of public policy.
•	 The influence of policy advice varies along multi-
ple dimensions: It can be short-­lived or long-­lasting,
broad or narrow, amplified by influential followers or
muted, and connect distinct clusters of advice or not.
•	 Citation network analysis is a powerful tool to shed
light on the different dimensions of the influence of
policy advice.


## Page 3

432
Public Administration Review, 2026
and “knowledge regimes” (Campbell and Pedersen  2014) has
highlighted how different types of actors and bodies—including
bureaucrats, permanent advisory bodies, temporary advisory
commissions and task forces, universities and research insti-
tutes, think tanks and consultancy firms—provide decision-­
makers with policy-­relevant knowledge, that is, knowledge and
ideas about how policy problems can be understood and which
policy responses are appropriate. A key assumption in this lit-
erature is that policy advisory bodies may have influence (e.g.,
Craft and Howlett 2012). Their advice may shape the thinking
of policy-­making elites and serve as an important input when
governments formulate policies to address anything from pan-
demics and climate change to aging populations and economic
crisis.
Importantly, advice may shape public policy both in direct
and indirect ways (Campbell and Pedersen 2014; Christensen
and Hesstvedt  2024). Policy advice may have a direct influ-
ence on policy decisions, for instance, when a recommenda-
tion in an advisory report presented to government is picked
up by decision-­makers and adopted as policy. But—arguably
more often—the influence of policy advice is indirect: The
analyses, arguments, and recommendations presented in
advisory reports shape the discourse and debate about an
issue, which in turn may affect the problem understandings
and policy solutions embraced by decision-­makers. Indirect
influence can run through two different channels: either by
policy advice shaping public debates involving a broad range
of actors—what Vivien Schmidt  (2010) calls “communica-
tive discourse”—or by shaping debates among policy-­making
elites such as bureaucrats, scientific advisors, key stakehold-
ers, and so forth, about policy problems and solutions (i.e., “co-
ordinative discourse”). The latter includes how one piece of
policy advice shapes other pieces of policy advice, which is the
type of influence that we focus on in this article.
Existing typologies of policy advice influence or knowledge
use have furthermore distinguished the different purposes
for which advice is used, such as instrumental, symbolic,
political-­strategic, and enlightenment use (Weiss 1979; Hunter
and Boswell 2015), and the different stages in the knowledge
use of policy-­makers, that is, reception, cognition, discussion,
reference, effort, and influence (Knott and Wildavsky  1980;
Landry et al. 2003). Still, important conceptual blind spots re-
main. Existing work has not addressed the multiple dimensions
of the influence of policy advice, such as how the influence of
policy advice may be lasting or ephemeral, broad or narrow, and
so forth.
Empirically, there have only been scattered attempts to inves-
tigate the influence of policy advice, and scholars have often
highlighted the difficulties of measuring influence. For in-
stance, Campbell and Pedersen  (2014) stress the importance
of the influence question and offer some tentative empirical
observations about the influence of advisory bodies, but con-
clude that “determining which policy research organizations
are the most influential is difficult if not impossible” (p. 277)
and is “notoriously tricky business” (p. 278) (see also Hustedt
and Veit  2017, 46). Some recent empirical studies tackle the
influence question more directly, examining variation in in-
fluence between different advisory reports or types of advice
by analyzing citations to advisory reports or correspondence
between expert advice and policy decisions (Christensen and
Hesstvedt 2024; Jørgensen 2024). Beyond scholarship on policy
advice, there is also a well-­established literature on influence
in policy processes more generally, which has examined the
influence of policy actors—especially interest groups—using
both qualitative approaches such as process-­tracing and dis-
course analysis and different forms of quantitative text analysis
(Dür 2008; Klüver 2015; Wilkerson et al. 2015; Cross et al. 2021;
see Christensen 2023 for a discussion). However, although these
studies have made valuable empirical and methodological con-
tributions, they have not examined the different dimensions of
influence.
2.2   |   A Multidimensional Concept of the Influence
of Policy Advice
We develop a novel conceptualization that highlights the mul-
tidimensional character of the influence of policy advice. Our
theoretical starting point is that policy advice is a cumulative
process: The problem definitions and policy recommendations
presented in one advisory report may inspire and be developed
further in subsequent advice, which over time leads to the ac-
cumulation of a body of policy advice. Policy decisions usually
build on such a body of advice rather than on a single piece of
advice (see also Landry et al. 2003, 193).
The implication is that the influence of a piece of policy advice
should not be conceived of primarily as whether this piece of
advice shapes one specific policy decision. Rather, seeing policy
as a cumulative process directs our attention to how the influ-
ence of a piece of advice may extend both across time by shap-
ing subsequent pieces of advice and beyond the specific issue at
hand by inspiring advice in other policy areas, which in turn in-
forms public policies (see also Christensen and Hesstvedt 2024).
Furthermore, seeing policy advice as accumulating over time
and across policy areas invites us to think about this body of
policy advice as a constantly expanding network, where influ-
ence also depends on the extent to which insights presented in
policy advice spread throughout the network and on whether
advisory reports forge novel connections between distinct clus-
ters of advice.
This gives rise to a multidimensional concept of the influence
of policy advice, where the influence of a given piece of advice
varies along four axes:
1.	 Lasting influence: Does a piece of advice have a long-­
lasting impact on policy discussions or is its impact
ephemeral? Some advice has considerable impact at one
specific point in time, but is soon seen as outdated or
irrelevant. Other advice defines problems, introduces
ways of thinking, or establishes principles for policy that
continue to resonate in policy discussions for a long time
(e.g., gender equality or market principles for public pol-
icy). Beyond Weiss's (1979) broad argument that research
concepts and theories over time may “enlighten” policy
discussions, the temporal dimension of influence is not
well captured by existing concepts of the influence of
knowledge or advice.


## Page 4

433
Public Administration Review, 2026
2.	 Broad influence: Does the advice have an impact across
multiple policy areas or is its impact limited to a specific
field? Some advice has a great deal of influence within a
narrow policy field, for instance by introducing important
specific principles or design solutions for tax policy or fi-
nancial regulation, but has little broader relevance. Other
advice highlights cross-­cutting issues or establishes gen-
eral principles that resonate across a number of different
policy areas, such as the precautionary principle in risk
regulation. Although public policy scholars have been con-
cerned with the use of expert knowledge in policy subsys-
tems (Weible 2008), the extent to which the influence of
advice reaches across subsystem boundaries has received
little attention.
3.	 Influential followers: To what extent does the advice
gain traction by inspiring other advisory reports that
are themselves influential? Inspired by insights from
social network theory (Bonacich 1972), the influence of
an advisory report arguably depends on how important
its “followers” or “descendants” are: The impact of a re-
port is magnified if it lays the foundation for subsequent
reports that are highly influential—leading its insights
to be widely spread—whereas a report's influence peters
out if it is only picked up by reports that themselves have
little impact. This notion of influence through diffusion
has so far not been conceptualized in the policy advice
and knowledge use literature.
4.	 Influence as broker: To what extent does the advice have
influence by serving as a “broker” or “intermediary”
within the body of advice, connecting clusters of advice
that would otherwise not be connected? Network the-
ory teaches us that actors occupying a broker position in
a network—that is, who connect otherwise unconnected
actors—have power since they control information flows
within the network (Burt 2004). Applied to policy advice,
advisory reports that link different clusters of advice are
particularly influential since they define what ideas and
knowledge pass between different parts of the network.
For instance, an advisory report may combine insights
from reports on different issues to define a policy problem
in a way that sets the direction for future reports. Thinking
about influence as forging new and unique connections
adds a novel dimension to discussions about policy advice
influence.
Each of these dimensions thus captures substantively import-
ant variation in the influence of policy advice, offering a more
fine-­grained understanding of influence than existing concepts.
Importantly, the four dimensions are conceptually independent
from each other. That is, any combination of values on the dif-
ferent dimensions is possible. For instance, a piece of advice
that has lasting influence may have broad or narrow influence;
it may have influential followers or not; and it may serve as a
broker or not. Moreover, the four dimensions are not meant to
add up to an index of influence. Rather, they highlight that how
influential a piece of advice is depends on which dimension of
influence we consider.
In the following, we show how each of these conceptual dimen-
sions of influence can be measured empirically using citation
network analysis. Before we present our specific network mea-
sures, we introduce citation network analysis as a method and
our citation data.
3   |   Citation Network Analysis
3.1   |   Method
Citation network analysis is a subfield of bibliometrics and
network science that analyzes citation patterns between pub-
lications. Much of this work concerns scientific publications,
given the availability of data on millions of scientific articles
and the citation links between them. The earliest bibliometric
studies focused on simple statistics such as counting the number
of citations an article received. But over time, more advanced
techniques, such as social network analysis (Wasserman and
Faust 1994), have influenced the analysis of citation networks.
In a citation network, each publication is represented as a node,
and citations between publications are represented as edges
between nodes. This structure can be used to explore various
aspects of the scientific landscape, including the most influen-
tial articles, the most productive authors, the growth of research
fields over time, and the relationships between different subfields
(Leydesdorff  2007; see e.g., Batagelj et  al.  2017; Bandola-­Gill
et al. 2023). For example, centrality measures (Freeman 2002;
Hanneman and Riddle 2005) and network visualization tech-
niques (Borgatti et al. 2002; Bastian et al. 2009) developed in
social network analysis have been applied to citation networks
to analyze the influence of academic works.
Citation network analysis has also been applied to analyze the
impact, importance, or centrality of documents in other fields.
For instance, it has been used in political science studies of the
law to examine networks of legal rulings (Fowler et al. 2007;
Lupu and Voeten  2012). In one notable contribution, Fowler
et al. (2007) use citation network analysis to analyze the entire
network of US Supreme Court opinions, which are linked to-
gether through opinions citing precedent from previous cases.
They introduce several citation network measures for studying
the legal influence of specific opinions; that is, how important a
specific opinion is within the body of case law. Similarly, schol-
ars have examined which resolutions from the United Nations
General Assembly are most influential by analyzing the net-
work of citations between resolutions adopted by the General
Assembly (Mesquita and Pires 2024).
There is also a small but growing body of studies within the
fields of public policy and administration, bibliometrics/scien-
tometrics, public health, and education that employ data on ci-
tations in policy documents to examine the use and influence
of knowledge and advice in policy-­making. Scientometrics and
public administration scholars have analyzed how often ac-
ademic articles from different fields are cited or mentioned in
policy documents from international organizations and gov-
ernments, using large-­scale databases such as Altmetric and
Overton (Bornmann et al. 2016; Ma and Cheng 2025). Public
policy and administration researchers have also examined cita-
tions to a broader range of knowledge and advice in policy docu-
ments, such as the types of knowledge cited in EU and UK Brexit
ex ante impact appraisals (Pattyn et al. 2021) and citations to


## Page 5

434
Public Administration Review, 2026
advisory commission reports in Norwegian government white
papers and other advisory commission reports (Christensen and
Hesstvedt 2024). Similarly, scholars within public health and ed-
ucation have analyzed which evidence is cited most frequently
in public health recommendation documents from national and
international health authorities (Smith et  al.  2021) or in pol-
icy documents about education reform in the Nordic countries
(Karseth et al. 2022).
However, with a few exceptions, this existing work relies on sim-
ple counts of citations to determine how important or influential
a knowledge source is and does not analyze citation networks.1
It thereby discards relevant information about the citation links
between documents, for instance about whether citation links
stretch across time or policy areas or about the location of the
citing and cited documents within the larger network of docu-
ments. As explained above, citation network analysis can be a
powerful tool to exploit this information and tap into various
aspects of the influence of advisory documents.
Certainly, citation analysis and citation network analysis also
have important limits as a method for examining influence (see
e.g., Vilkins and Grant 2017; Christensen 2023). First, the basic
assumption that a citation indicates influence of one document
on another document can be challenged. Citations can be super-
ficial or symbolic, and they may even be used to reject or criti-
cize the arguments made in another document. This problem is
most effectively addressed through additional qualitative anal-
ysis of how citations are actually used in the citing documents.
For instance, Smith et al. (2021) conduct a further qualitative
analysis of citations in public health reports included in their
citation network analysis and find no evidence of citations being
used for rejection or critique. This is also the approach we adopt
in this article, by qualitatively analyzing a sample of citations for
validation (see Section 3.2).
Second, a document may of course influence another docu-
ment without being explicitly cited by it. One way to partially
address this problem is to look beyond academic-­style citations
in reference lists and footnotes and also consider mentions of
a document in the text. Mentions can be detected by searching
for report identifiers, numbers or titles in a text. For instance,
Mesquita and Pires (2024) construct a citation network of UN
General Assembly resolutions based on text searches for the
identifiers and titles of resolutions in the corpus of resolu-
tions. Similarly, Christensen and Hesstvedt (2024) include both
academic-­style citations and mentions of advisory reports in
white papers in their citation analysis. This makes the approach
applicable also to reports for instance from think tanks and con-
sultancies that do not necessarily use academic referencing—
provided, of course, that the sources these reports draw on are
somehow mentioned in the text and can reliably be detected.
Another way to address the problem of undetected influence is
to triangulate citation network analysis with other methods for
measuring influence, such as text reuse analysis, which detects
textual correspondence (i.e., copying) between two documents
(Wilkerson et al. 2015).
In the next part, we present a set of citation network measures
that can capture the different conceptual dimensions of the in-
fluence of policy advice (“Measures of the Influence of Policy
Advice”). However, we first briefly describe the data material
that we use in our citation network analysis.
3.2   |   Data
To illustrate the usefulness of citation network analysis for
studying patterns of influence within the body of policy advice,
we draw on data on citation patterns among 1545 Norwegian
Advisory Commission reports published between 1972 and
2017. These advisory reports are known as “Norwegian Official
Reports” (Norges offentlige utredninger—NOU) and are pro-
duced by temporary commissions appointed by government
to analyze a policy issue and recommend policy solutions.
Commission members are typically drawn from the civil service,
academia and research institutes, interest groups and political
parties. Commission reports are submitted to the government
and are made publicly available. The arguments and recommen-
dations presented in a commission report often form the basis
for government white papers and draft bills and resolutions, and
they also have an influence on subsequent commission reports
(Christensen and Hesstvedt 2024).
We are interested in analyzing the varying influence of these
advisory commission reports within the entire network of advi-
sory commission reports. That is, we seek to measure their in-
fluence on other advisory reports, not their influence on policy
output. We therefore collected data on citations in commission
reports to other commission reports. The data set was compiled
from pdf and html versions of commission reports that were
gathered from the websites of the Norwegian government (reg-
jeringen.no) and the Norwegian National Library (nb.no), where
all reports published since the report series started in 1972 are
publicly available. For each report, citations were manually col-
lected from the pdf or html documents by copying the content of
the report's reference list or footnotes into a spreadsheet. If the
report had a reference list/bibliography, all citations in the list
were collected. If not, all unique references in the footnotes of
the report were gathered. This resulted in a database contain-
ing all citations in all commission reports, with one entry per
citation and each entry linked to a citing report (a total of about
70,000 citations). The gathering of the reports and citations was
carried out by a team of research assistants and one of the au-
thors and coordinated by the author and a PhD researcher.
Identifying citations to official commission reports among cita-
tions to other sources in commission reports is in most cases
straightforward. Official commission reports are nearly always
referred to using the acronym “NOU” or the full series title
“Norges offentlige utredninger” as well as the report year and
number. A typical reference to an official commission report
would read “NOU 1976:23 Omlegging av sykepengeordningen”
[Reform of sickness benefits]. Citations were therefore first au-
tomatically coded in Stata by the PhD researcher to identify ci-
tations that contained the terms “NOU” and “Norges offentlige
utred” (with and without capitals) using the strpos command.
The automatic coding was then manually validated and cor-
rected by one of the authors. This involved both (a) checking
that all citations identified through the automatic coding were
indeed citations to official commission reports and (b) identify-
ing other citations to official commission reports that had not


## Page 6

435
Public Administration Review, 2026
been picked up by the automatic coding, which was done by
searching the full citation database in excel with terms such as
“utredning” (report), “utvalg” (commission), and “kommisjon”
(commission). This resulted in a data set containing all citations
between official commission reports. After removing duplicates,
this data set contained 2874 citations. For each of these citations,
the citing report and the cited report were coded using a 6-­digit
report ID code by one of the authors based on the report year
and number provided in the citation (In the few cases where this
information was missing or ambiguous, the report title was used
to find the right report number). These data were subsequently
transferred into a network matrix by the other author. We also
manually coded the appointing ministry of each commission
based on information from the title page or preface of the com-
mission report (Hesstvedt and Christensen 2023; see Supporting
Information: Table A1 for details).
To get a better sense of how these citations were actually used,
we also qualitatively analyzed a random sample of 50 citations
between advisory reports (see Christensen and Hesstvedt 2024).
We searched the citing report for every mention of the cited
report in the text, and for each mention we coded inductively
how the citation was used. The codes were then aggregated for
each of the 50 citations. In nearly half of the cases (21 out of
47 citations), citations were used to describe that the cited com-
mission's recommendations were adopted by the citing com-
mission and/or had been adopted in policy measures or laws.
Another 15 citations referred to arguments, factual information
or empirical findings from the cited report, whereas 9 citations
were casual references and 2 citations were used exclusively to
reject the cited commission's recommendations (see Supporting
Information: Table A2). The analysis suggests that while cita-
tions are used in different ways, they in many cases indicate
some form of adoption or endorsement of recommendations or
arguments from the cited report.
Based on the full citation data, we then constructed a cita-
tion network of commission reports where the reports are the
“nodes” and the citations are the “edges” (i.e., links) between
the nodes. The network encompasses 1545 reports (nodes) and
2874 citations (edges) between commission reports. The edges
are unidirectional since a report can only cite existing reports
and not future ones. The Gephi open source software for social
network analysis (version 0.10) was used for both the analysis
and the visualization of the commission reports citation net-
work (Bastian et al. 2009). In the network visualizations, the
reports are labeled with a 6-­digit identifying code made up of
the publication year and report number. For instance, the report
Power and democracy, report number 19 published in 2003, has
the code 200319. For reference, these codes are also provided
in parentheses when discussing reports in the text. The cita-
tion network data for NOU reports used in this study is publicly
available through Harvard Dataverse (Christensen and van den
Bekerom 2025).
4   |   Measures of the Influence of Policy Advice
In the following, we present a set of citation network measures
that can be used to capture the different conceptual dimensions
of the influence of policy advice and illustrate these measures
by applying them to analyze the citation network of Norwegian
advisory reports. As a baseline, we first present the conventional
citation measure of influence, namely a simple citation count
(i.e., in-­degree centrality). We then present alternative citation
network measures that tap into each of our four conceptual di-
mensions of influence: lasting influence, broad influence, influ-
ential followers and influence as broker. We draw on measures
of centrality within networks that are commonly used in cita-
tion network analysis and/or social network analysis. The mea-
sures that we outline are not intended to be exhaustive.
4.1   |   Conventional Citation Measures of Influence
The most widely used citation measure of influence is a simple
citation count, which in network analysis is called “in-­degree
centrality.” In-­degree centrality measures the number of edges
that point inward at a node (in our case, the number of other ad-
visory reports that cite a given advisory report). By contrast, out-­
degree centrality is the number of connections that originate at
a node and point outward (i.e., the number of other reports cited
by a given report) (Freeman 2002). A well-­known example of
an in-­degree centrality measure from the scientific world is the
Google Scholar citation count of an academic publication, which
is an indicator of a publication's scientific impact. The same logic
applies to the influence of advisory reports: A commission re-
port with a high in-­degree centrality score is cited by many other
commission reports, indicating that it is influential within the
body of policy advice.2
The 1545 Norwegian advisory commission reports that make
up our citation network vary greatly in in-­degree centrality, that
is, in the total number of inward citations from other reports.
Approximately 40% of all commission reports (n = 632) have an
in-­degree centrality score of 0, meaning that they are not cited by
any other report, whereas the most-­cited report has an in-­degree
centrality score of 25 (see Supporting Information: Figure A1).
Among the 913 reports that received at least one citation, the
vast majority are cited by only a few other reports. The average
commission report received 1.9 inward citations from other re-
ports (see Supporting Information: Table  A3). In-­degree cen-
trality scores generally show an increasing trend over time, but
reports published towards the very end of the study period have
lower scores since they have had little time to be cited yet (see
Supporting Information: Figure A2).
Table 1 shows the 15 most influential commission reports in the
citation network based on their in-­degree centrality. Yet, a sim-
ple in-­degree centrality measure is not well suited to compare
the influence of reports published in different years, given that
older commission reports have had more chances to be cited
than more recent reports. We therefore also calculate a stan-
dardized in-­degree centrality measure, defined as the in-­degree
divided by the total number of reports published after the focal
report, that is, those that could possibly have cited it, expressed
as a percentage (see the last column of Table 1).
The reports with the highest in-­degree centrality scores are
Internationalization of the economy (199617) with 25 citations
and Power and democracy (200319) and A better organized state
(198905) with 24 citations each. These reports are therefore the


## Page 7

436
Public Administration Review, 2026
most influential according to this measure. Yet, among the 15
reports with the most citations, the report Redistribution and so-
cial inequality (200910) is the most influential according to the
standardized in-­degree centrality measure: It is cited by 9.62%
of all reports that could possibly have cited it, slightly more than
Power and democracy, which is cited by 8.39% of possible reports.
However, conventional in-­degree centrality measures do not
allow us to examine to what extent the influence of an advisory
report is long-­lasting, broad, amplified by influential followers
or influential as broker between different clusters of advice.
To measure the four conceptual dimensions of influence out-
lined above, we therefore propose a set of alternative measures
that we present over the following pages (see Table 2 for an
overview).
4.2   |   Lasting Influence
To examine the first conceptual dimension, namely whether
the influence of policy advice is long-­lasting or short-­lived,
we first look at the number of citations a report has received
over time, that is, dynamic in-­degree centrality. Dynamic in-­
degree centrality takes into account the evolution of the cita-
tion network over time. It measures the importance of a node
not only based on the number of incoming edges it currently
has (i.e., regular in-­degree centrality), but also based on the
rate at which it acquires new incoming citations over time
(Bastian et al. 2009; Saqr and Peeters 2022). To measure the
dynamic in-­degree of a node, one calculates the in-­degree of
the node at each point in time (e.g., each year). This is a useful
measure for understanding how the importance of advisory
TABLE 1    |    The 15 most influential commission reports based on in-­degree centrality.
Report title
Report ID
In-­degree centrality
Standardized in-­
degree centrality
Internationalization of the economy
199617
25
5.18
Power and democracy
200319
24
8.39
A better organized state
198905
24
3.42
Criminal sanctions and care
200315
22
7.59
Dispute resolution
200132
19
5.76
Rights of persons with disabilities
200122
19
5.59
Freedom of speech
199927
18
4.48
Tax commission
200309
16
5.41
Green taxes
199609
16
3.26
Law on social services
198518
16
1.92
On the legal status of Sami people
198418
16
1.85
Redistribution and social inequality
200910
15
9.62
On the division of responsibilities between state, region and
municipality
200022
15
4.02
A strategy for employment and value creation
200021
15
4.01
A national strategy for employment growth in the 1990s
199226
15
2.50
TABLE 2    |    Conceptual dimensions of the influence of advice and corresponding citation network measures.
Dimension
Description
Measure
Influence (uni-­dimensional)
How influential is the advice?
In-­degree centrality
Standardized in-­degree centrality
1. Lasting influence
How long-­lasting is the influence of the advice?
Dynamic in-­degree centrality
Half-­life
2. Broad influence
To what extent does the advice have
influence across policy areas?
External–internal (E-­I) index
3. Influential followers
To what extent is the advice amplified
by influential followers?
Eigenvector centrality
4. Influence as broker
To what extent does the advice uniquely
connect different clusters of advice?
Betweenness centrality


## Page 8

437
Public Administration Review, 2026
reports changes over time, and can help identify reports that
have experienced short bursts of influence or that have more
sustained impact.
As an illustration of different over-­time patterns of influence,
Figure 1 displays the cumulative frequency distribution of the
in-­degree for two reports, namely Living standards study: final
report (197628) and A better organized state (198905), plotted
over time. The former report was published in 1976 and gath-
ered 11 citations between 1976 and 1982, after which it was
never cited again. In contrast, the latter report was published
in 1989 and gradually accrued 24 citations between 1989 and
2017, spanning nearly three decades. In other words, the in-
fluence of the Living standards study was significant but
short-­lived, whereas the report on A better organized state had
long-­lasting influence.
Another way of examining whether the influence of advisory
reports is brief or lasting is by looking at their half-­life. In med-
icine, this term refers to the time it takes for the concentra-
tion of a substance (such as a drug or a radioactive element)
in the body to decrease by half. In citation network analysis,
the half-­life measure refers to the time it takes for half of the
total citations received by a publication to occur (Burton and
Kebler 1960). Applied to advisory reports, this measure pro-
vides insight into the temporal decay of a report's influence
on other reports. For instance, as shown in Table 3 below, the
half-­life of the Living standards study (197628) is 3 years—that
is, it received half of its citations within the initial 3 years
after publication—which suggests that its influence decayed
rapidly. By contrast, the half-­life of the report on A better or-
ganized state (198905) is 11 years, suggesting more enduring
influence.
A limitation of the half-­life measure is its time-­sensitiveness.
Reports published more recently may appear to have shorter
half-­lives simply because they have had less time to accumulate
citations, whereas older reports have had the opportunity to re-
ceive citations over a more extended period.
4.3   |   Broad Influence
To measure the second conceptual dimension, namely whether
the influence of a commission report extends across different
policy areas or is limited to a specific policy field, we propose
using the “external–internal (E-­I) index.” The E-­I index is a so-
cial network measure to assess the degree of group integration
(Krackhardt and Stern 1988). It is based on comparing the num-
ber of connections that exist within a group to those that exist
outside of the group. To calculate the E-­I index, the number of
edges that a node has with nodes inside the group is subtracted
from the number of edges that it has with nodes outside of the
group (Hanneman and Riddle 2005). This result is then divided
by the total number of edges. The resulting index ranges from −1
to +1, where a score of −1 indicates that all edges are within the
group, and a score of +1 indicates that all edges are outside of the
group. A score of 0 indicates that the node is equally integrated
within and outside of the group.
In citation network analysis, the E-­I index is used to quantify the
extent to which an article is cited by (or cites) sources within the
same field (internal citations) versus outside of the field (exter-
nal citations) (see Hur 2017). In our case, a high E-­I index value
indicates that a report is predominantly cited by reports from
commissions with a different appointing ministry, indicating
broad impact, while a low E-­I index value indicates that a report
is cited mostly by commission reports with the same appointing
ministry, indicating narrow impact.
Table 3 shows the values on the E-­I index for a selection of com-
mission reports, as well as how these reports score on other mea-
sures of influence. For instance, we see that the report Corporate
and capital taxation: a blueprint for reform (198914) has an E-­I
index score of −1, which means that it is exclusively cited by other
reports appointed by the same ministry, in this case the Ministry
of Finance. By contrast, the report Redistribution and social in-
equality (200910)—which was also commissioned by the Ministry
of Finance—has an E-­I index score of 0.7, indicating that the ma-
jority of its inward citations are from commission reports with
FIGURE 1    |    Cumulative frequency distribution of in-­degree for the reports Living standards study: final report (197628) and A better organized
state (198905).


## Page 9

438
Public Administration Review, 2026
TABLE 3    |    Selection of commission reports and their scores on the different measures of influence.
Report title
Report ID
In-­
degree
Out-­
degree
Standardized
in-­degree
Half-­
life
Internal
in-­degree
External
in-­degree
E-­I
index
Eigenvector
Betweenness
The living standards study:
final report
197628
11
0
0.9
3
5
6
0.1
0.233
0.0
Personal taxation
198422
8
4
0.9
4
5
3
−0.3
0.269
804.8
A better organized state
198905
24
0
3.4
11
0
24
1.0
0.945
0.0
Corporate and capital
taxation: a blueprint for
reform
198914
9
4
1.3
11
9
0
−1.0
0.299
1052.7
Internationalization of the
economy
199617
25
1
5.2
5
8
17
0.4
1.000
235.6
Flatter taxes
199907
3
11
0.7
2
2
1
−0.3
0.161
1433.3
Rights of persons with
disabilities
200122
19
26
5.6
9
2
17
0.8
0.416
10,635.8
Tax commission
200309
16
4
5.4
5
9
7
−0.1
0.327
2853.2
Power and democracy
200319
24
0
8.4
6
1
23
0.9
0.423
0.0
Redistribution and social
inequality
200910
15
7
9.6
2
2
13
0.7
0.314
2466.7
Welfare and migration
201107
11
7
8.9
3
4
7
0.3
0.145
2848.7


## Page 10

439
Public Administration Review, 2026
a different appointing ministry. This difference is visualized in
Figures 2 and 3, which show the citation ego-­networks of the two
reports, with the different colors represent different appointing
ministries. Although the impact of the tax report was limited to
the field of economic and financial policy, the report on redistribu-
tion and inequality had broad impact across various policy areas,
including labor market, education and gender equality policy.
4.4   |   Influential Followers
To measure the third conceptual dimension of influence, the ex-
tent to which advice gains traction by inspiring other advice that
is itself influential, we use eigenvector centrality (Bonacich 1972).
Eigenvector centrality is based on the notion that the importance
of a node depends not only on how many connections it has di-
rectly, but also on the importance of the nodes it is connected to.
The score is determined iteratively based on the principle that
the centrality score of a node is proportional to the sum of the
centrality scores of the nodes it is connected to (Wasserman and
Faust 1994). Applied to commission reports, reports with high
eigenvector centrality scores are those that are cited by other in-
fluential reports. A high eigenvector centrality score indicates
that a report is credible and influential because many other well-­
respected reports cite it.
However, like in-­degree centrality scores, eigenvector centrality
scores are likely to be higher in policy areas with extensive advi-
sory activity, where there is a greater chance that advice is am-
plified by other reports (this if confirmed by our empirical data,
see Supporting Information: Figure A7). Eigenvector centrality
scores are therefore most valuable for comparing the influence
of reports produced within the same policy area.
For this reason, and to ease visual interpretation of the results, we
illustrate the eigenvector centrality measure by examining a sub-
network rather than the full network of advisory reports. The sub-
network includes all commission reports in the field of tax policy
with at least one inward or outward citation (30 reports). Figure 4
depicts eigenvector centrality in the citing patterns within this sub-
network of reports. In addition, Table 4 presents—among other
things—the eigenvector centrality scores for the commission re-
ports in this subnetwork. The values in Table 4 assume that these
30 reports are the only ones in the network, unlike the results in
Table 3 that take the whole network into account.
Figure 4 and Table 4 show that Personal taxation (198422) and
Corporate and capital taxation: a blueprint for reform (198914)
have the highest eigenvector centrality scores (1.000 and 0.802,
respectively). This suggests that these reports had considerable
impact by laying the foundation for a series of other advisory
reports that were themselves influential. This fits with what we
know from qualitative research: The 1984 report on personal
taxation first diagnosed the efficiency and equity problems of
the existing tax system, whereas the 1989 report on corporate
and capital taxation established the basic principles for tax pol-
icy design that guided policy advice and reform of the tax system
in the following decades (Christensen 2017, 118–131).
4.5   |   Influence as Broker
To assess the fourth conceptual dimension, namely which ad-
vice has influence by serving as a broker between different clus-
ters of advice, we look at betweenness centrality. Betweenness
centrality is a measure of the importance of a node in a network
based on how frequently it appears on the shortest path (geode-
sic) between pairs of other nodes in the network (Freeman 1977,
2002; Wasserman and Faust 1994), that is, how much a node
is connected to other nodes that do not have a direct connec-
tion between them. In scientometrics, betweenness centrality
can be used to identify which articles or authors act as “bro-
kers” or “intermediaries” between different research disciplines
(Leydesdorff 2007). Applied to our commission reports network,
reports with a relatively high betweenness score act as interme-
diaries, connecting commission reports in different parts of the
network that would otherwise not be connected and thereby de-
fining what ideas and knowledge pass between different areas
of the network.
FIGURE 2    |    Citation ego-­network of the report Redistribution and
social inequality (200910). The network is ordered by publication year of
the reports. The color of the nodes represents the appointing ministry
(see Supporting Information: Table A1 for color codes). The size of the
nodes reflects their score on in-­degree centrality.
FIGURE 3    |    Citation ego-­network of the report Corporate and capi-
tal taxation: a blueprint for reform (198914). The network is ordered by
publication year of the reports. The color of the nodes represents the
appointing ministry (light blue = Ministry of Finance). The size of the
nodes reflects their score on in-­degree centrality.
FIGURE 4    |    Citation network of taxation commissions. The network
is ordered by publication year of the reports. The size of the nodes re-
flects their score on eigenvector centrality.


## Page 11

440
Public Administration Review, 2026
To illustrate the betweenness centrality measure, we again
examine the subnetwork of commission reports on taxation.
In Figure 5, we present the citation network for these reports,
where this time the node size corresponds to the betweenness
centrality score. Table 4 also shows the betweenness centrality
score for the 30 commission reports in this sub-­network.3 We
see that the report from the Tax commission (200309) from 2003
has the highest score on betweenness centrality, with a value of
27. This indicates that the report was influential as a “broker”
in the network, serving as the bridge between older and newer
advisory reports on taxation. This rhymes well with what we
know from qualitative research: This report played an import-
ant role in the development of Norwegian tax policy, entrench-
ing the tax reform principles established by earlier commission
reports and setting the direction for tax reforms and commission
reports on tax policy in the 2000s and 2010s (Christensen 2017,
129–131). Other reports that score high on this measure are the
1989 report on corporate and capital taxation (198914) and the
1999 report Flatter taxes (199907), with betweenness central-
ity scores of 19.5 and 13.5, respectively. The latter is somewhat
TABLE 4    |    Subnetwork of all taxation commission reports and their scores on the different measures of influence.
Report title
Report ID
In-­degree
Out-­degree
Eigenvector
Betweenness
Taxation of housing
197303
1
0
0.008
0.0
The value-­added tax system
197567
1
0
0.044
0.0
Valuation of residential and recreational
properties
197836
1
0
0.008
0.0
Taxation of benefits in kind
198148
1
0
0.717
0.0
Personal taxation
198422
3
0
1.000
0.0
Corporate and capital taxation: a blueprint for
reform
198914
7
2
0.802
19.5
A general value-­added tax on services
199011
2
0
0.033
0.0
Corporate and capital taxation: taxation of wealth
199117
1
0
0.025
0.0
An improved value-­added tax law
199130
1
1
0.025
2.0
Taxation of power companies
199234
2
1
0.105
1.3
Reorganization of the tax administration
199301
3
0
0.023
0.0
Should the value-­added tax be differentiated?
199308
1
0
0.008
0.0
New tax accounting
199328
0
1
0.000
0.0
Green taxes
199609
7
0
0.464
0.0
New law on property tax
199620
2
0
0.283
0.0
Flatter taxes
199907
2
4
0.289
13.5
Inheritance tax
200008
0
8
0.000
0.0
Taxation of petroleum activities
200018
1
3
0.025
2.0
Value-­added tax and the municipalities
200303
1
2
0.008
2.0
Tax commission
200309
7
2
0.214
27.0
Excise duties and frontier trade
200317
1
1
0.025
0.0
Differentiated electricity tax for households
200408
2
3
0.033
2.0
Better tax collection
200412
0
1
0.000
0.0
Shipping tax
200604
1
3
0.025
1.3
An assessment of the excise duties
200708
1
5
0.008
2.0
Value-­added tax on culture
200807
0
4
0.000
0.0
Measures against tax evasion
200904
1
0
0.008
0.0
Fiscal paradises and development
200919
0
1
0.000
0.0
Capital taxation in an international economy
201413
1
4
0.008
3.3
Put a price on the environment
201515
0
5
0.000
0.0


## Page 12

441
Public Administration Review, 2026
puzzling, given that this report—which explored the possibility
of a flatter tax rate structure—had limited impact on Norwegian
tax reform discussions (ibid.).
Finally, we assess empirically whether the four dimensions of
influence are independent from each other by examining the
correlation between the different measures within our report
dataset (see Supporting Information: Table A3). We find only
weak or negligible correlations between the measures half-­life,
E-­I index, betweenness centrality, and eigenvector centrality.
This supports our argument that the four dimensions pick up
distinct aspects of influence.
5   |   Discussion
If public policies are informed by a cumulative body of advice
about policy problems and appropriate solutions, how can we
understand the patterns of influence within this body of policy
advice? Which pieces of advice set the direction for subsequent
policy advice?
Conceptually, our article makes a novel contribution by un-
packing the notion of “influence” of policy advice. Taking issue
with the conventional one-­dimensional view of influence, we
propose a multidimensional concept of the influence of policy
advice that considers the temporal, spatial, and network dimen-
sions of influence. The answer to the question of how influential
an advisory report is depends crucially on which dimension of
influence you are interested in: lasting influence, broad influ-
ence, influential followers, or influence as broker. These dimen-
sions capture important differences in how policy advice shapes
other policy advice across policy areas and over time, which so
far have not been explored in the literature. While we place our
contribution within the literature on policy advice, our multidi-
mensional concept of influence is also relevant for related dis-
cussions, for instance, about how to understand the influence of
policy ideas (e.g., Campbell and Pedersen 2014).
Our conceptualization is broadly applicable to policy advisory
processes across a range of geographical settings. Even when pol-
icy advisory systems are less structured than in the Norwegian
case, we would expect policy advice to be cumulative to a con-
siderable degree—with new pieces of advice building further on
previously presented problem definitions and ideas about policy
solutions—and we would expect the influence of advice to vary
in its temporal and spatial reach, amplification, and brokering
character. Of course, the extent to which policy advice has last-
ing or broad influence may depend on distinctive features of the
national political-­administrative context and advisory system.
For instance, advice may be less likely to have influence across
policy areas in systems with a strongly compartmentalized bu-
reaucracy and advisory system.
Methodologically, we have proposed citation network analysis
as a novel approach for measuring the different dimensions of
the influence of policy advice. Network analysis offers various
measures of the centrality or importance of a node within a
network and has been employed with great effect to measure
influence within networks of scientific publications or legal rul-
ings. We have argued that such measures are highly relevant for
examining influence within networks of policy advisory docu-
ments, too. Going beyond simple citation counts as measures of
influence, citation network analysis allows us to tap into how
the influence of a piece of advice develops over time, how it is
distributed across policy areas, and how it spreads throughout
the constantly expanding body of policy advice.
We have already discussed some important limitations of ci-
tation (network) analysis and strategies to address these lim-
itations (see Section 3.1). Here, we return to one key question,
namely under which conditions citation network analysis is a
viable method for studying patterns of policy advice influence.
First, like all methods that rely on documents/text, a necessary
precondition for conducting citation network analysis is that
policy advice is presented in written form and that advisory doc-
uments are possible to identify and access for researchers. This
makes the method more challenging to apply in systems where
policy advice is highly informal or opaque. It also means that the
method is easier to apply when there are openly available gov-
ernment repositories of advisory reports of different kinds than
when advisory documents need to be gathered one by one from
different government webpages. Increasingly, governments and
international organizations make advisory documents like ex-
pert group reports or evaluation reports available in online re-
positories, but there is still large variation across countries and
organizations.
A second prerequisite for citation network analysis is that the
documents analyzed allow us to identify links to other docu-
ments. This is easiest when advisory reports use academic-­style
referencing to cite their sources (i.e., in-­text citations and ref-
erence lists or footnotes), such as the commission reports we
analyze. Academic citation practices are increasingly common
in advisory documents: For instance, the recently established
Overton database contains citations from 18 million policy-­
relevant documents worldwide, many of which are advisory
documents from government research bodies, think tanks, and
international expert institutions (see Szomszor and Adie 2022;
Ma and Cheng  2025). Citation analysis is more challenging
when advisory reports do not cite their sources in a systematic
way. Still, we have argued that in these cases an alternative way
to establish links between documents is to identify mentions of a
document in a text, for instance by searching for report identifi-
ers, numbers, or titles (see Mesquita and Pires 2024). This makes
citation network analysis a flexible approach that can usefully
be applied to study influence within networks of advisory and
policy documents across a range of different countries and or-
ganizations. Finally, we would like to stress the importance of
methodological triangulation: Citation network analysis is most
powerful as a method for studying influence patterns when
FIGURE 5    |    Citation network of taxation commissions. The network
is ordered by publication year of the reports. The size of the nodes re-
flects their score on betweenness centrality.


## Page 13

442
Public Administration Review, 2026
combined with other forms of qualitative and quantitative anal-
ysis (Christensen 2023).
Empirically, the citation network analysis of influence patterns
within a large network of Norwegian Advisory Commission
reports supports the notion that the influence of policy advice
is multidimensional. The measures of the different conceptual
dimensions of influence are weakly or not at all correlated with
each other, with different reports scoring highest on different in-
fluence measures. These results highlight that advisory reports
can be influential in multiple distinct ways: They can define
enduring principles for thinking about problems and solutions
within a specific policy area, like taxation or school policy;
they can establish principles that resonate across many areas
of government activity, such as gender equality or cost–bene-
fit analysis; they can lay the analytical foundations for future
generations of influential reports; or they can couple previously
separate policy discourses, for instance about immigration and
the welfare state.
Instead of trying to collapse these multiple facets of influence
into one single influence measure, scholars ought to embrace
the multiplex character of the influence of policy advice in their
theories, methods, and empirical research. First, our multi-
dimensional concept encourages scholars to formulate with
greater precision what kind of influence they aim to study.
Second, it suggests that different types of influence are likely
to be explained by different drivers and mechanisms, which
invites more fine-­grained theorization of what makes advisory
bodies influential. Third, the validity of quantitative influence
measures is often questioned due to the large gap between the
abstract concept of influence and the specific indicators used to
measure it. Our multidimensional influence concept and associ-
ated measures can help scholars narrow this gap by establishing
a direct link between conceptual dimensions and operational
measures.
This points to several promising avenues for further research.
First, we invite future studies to investigate the multiple dimen-
sions of the influence of policy advice in other empirical con-
texts, to test the general applicability of the concept and method.
Second, while explaining variation in influence on different
dimensions is beyond the scope of this article, we encourage
future research to examine theoretically and empirically the
drivers and mechanisms behind different types of influence.
For instance, scholars could examine whether different forms of
influence are connected to features of the design and composi-
tion of advisory bodies, to features of the policy issue (e.g., issue
complexity or political salience) or to the specific organization of
national or sectoral policy advisory systems.
Third, whereas this article has examined the influence of advice
on other policy advice, future research can extend citation net-
work analysis to investigate the influence of advice on the policy
agenda and on policy output. Policy advice may not only shape
subsequent advice on how to understand and respond to a prob-
lem, it may also influence which issues make it onto the political
agenda. This can be studied by looking for citations or mentions
of advisory documents, for instance, in party manifestos or gov-
ernment coalition agreements. The citation network measures
that we propose can readily be used to study the influence of
policy advice on final policy decisions, too. A logical next step
is therefore to analyze the influence of policy advice within a
two-­mode network made up of advisory documents and policy
decision documents. More broadly, we hope that this article can
inspire scholars of public policy and administration to make
more active and creative use of the wealth of available public
documents and citation network analysis tools to study public
policy-­making processes.
Finally, our conceptual and methodological agenda has impli-
cations for practice. Policy-­makers and knowledge providers
seeking to foster more evidence-­informed policy-­making can
draw on a multidimensional understanding of influence to
develop more targeted strategies for how advice can achieve
impact, for instance focusing on policy area-­specific or
government-­wide impact. They can also make use of citation
network analysis to measure and monitor different forms of
advisory impact.
6   |   Conclusion
Understanding the influence of policy advice is essential for
policy-­makers and knowledge providers who seek to strengthen
the evidence basis of public policy. Yet, existing scholarship in
public policy and administration has struggled to come to grips
with the influence of policy advice, both conceptually and meth-
odologically. Our article has made novel contributions to this de-
bate. As policy decisions rarely reflect a single piece of advice but
rather draw on an accumulated body of policy advice, it is crucial
to understand how this body of policy advice develops and which
pieces of advice set the direction for subsequent advice—that is,
to examine the influence of policy advice on other policy advice.
We have highlighted that the influence of policy advice is not one-­
dimensional but rather varies along multiple dimensions: lasting
influence, broad influence, influential followers, and influence as
broker. We have also shown how citation network analysis can be
a powerful tool for investigating the multiple dimensions of the
influence of policy advice, adding to existing methodological ap-
proaches for studying influence in policy-­making, such as qualita-
tive approaches and quantitative text analysis.
Conflicts of Interest
The authors declare no conflicts of interest.
Endnotes
1	A few studies use citation network measures to identify clusters of doc-
uments that cite or are cited by the same documents or articles that
bridge different topics (Smith et al. 2021; Karseth et al. 2022; Ma and
Cheng 2025).
2	However, note that just like the citation counts of academic publica-
tions vary across disciplines since some disciplines publish and cite
more, the in-­degree centrality score of advisory reports may vary
across policy areas depending on the degree of advisory activity: In
policy fields where many advisory reports are produced, there is a
greater chance of being cited. The same applies to the eigenvector cen-
trality and external-­internal index measures. This insight is confirmed
by our empirical data (see Supporting Information: Figures A3–A8).
3	Note that only reports with at least one outward citation have a be-
tweenness centrality score greater than zero.


## Page 14

443
Public Administration Review, 2026
References
Bandola-­Gill, J., M. Arthur, and R. I. Leng. 2023. “What Is Co-­
Production? Conceptualising and Understanding Co-­Production of
Knowledge and Policy Across Different Theoretical Perspectives.”
Evidence & Policy 19, no. 2: 275–298.
Bastian, M., S. Heymann, and M. Jacomy. 2009. “Gephi: An Open Source
Software for Exploring and Manipulating Networks.” Proceedings of
the International AAAI Conference on Web and Social Media 3, no. 1:
361–362.
Batagelj, V., A. Ferligoj, and F. Squazzoni. 2017. “The Emergence of a
Field: A Network Analysis of Research on Peer Review.” Scientometrics
113: 503–532.
Bonacich, P. 1972. “Factoring and Weighting Approaches to Status
Scores and Clique Identification.” Journal of Mathematical Sociology 2,
no. 1: 113–120.
Borgatti, S. P., M. G. Everett, and L. C. Freeman. 2002. Ucinet 6 for
Windows: Software for Social Network Analysis. Analytic Technologies.
Bornmann, L., R. Haunschild, and W. Marx. 2016. “Policy Documents as
Sources for Measuring Societal Impact: How Often Is Climate Change
Research Mentioned in Policy-­Related Documents?” Scientometrics
109, no. 3: 1477–1495.
Burt, R. S. 2004. “Structural Holes and Good Ideas.” American Journal
of Sociology 110, no. 2: 349–399.
Burton, R. E., and R. W. Kebler. 1960. “The ‘Half-­Life’ of Some Scientific
and Technical Literatures.” American Documentation 11, no. 1: 18–22.
Campbell, J. L., and O. K. Pedersen. 2014. The National Origins of Policy
Ideas. Princeton University Press.
Cheng, Y., L. Thompson, S. Wang, et al. 2025. “Evidence-­Based Practices
and US State Government Civil Servants: Current Use, Challenges, and
Pathways Forward.” Public Administration Review 85, no. 1: 9–20.
Christensen, J. 2017. The Power of Economists Within the State. Stanford
University Press.
Christensen, J. 2018. “Economic Knowledge and the Scientization of
Policy Advice.” Policy Sciences 51, no. 3: 291–311.
Christensen, J. 2023. “Studying Expert Influence: A Methodological
Agenda.” West European Politics 46, no. 3: 600–613.
Christensen, J., and S. Hesstvedt. 2024. “The Influence of Expert
Groups: A Citation Analysis.” Journal of European Public Policy 31, no.
5: 1259–1294.
Christensen, J., and P. van den Bekerom. 2025. Unpacking the Influence
of Policy Advice Using Citation Network Analysis. Harvard Dataverse.
https://​doi.​org/​10.​7910/​DVN/​06OWUI.
Craft, J., and J. Halligan. 2017. “Assessing 30 Years of Westminster
Policy Advisory System Experience.” Policy Sciences 50, no. 1: 47–62.
Craft, J., and M. Howlett. 2012. “Policy Formulation, Governance
Shifts and Policy Influence: Location and Content in Policy Advisory
Systems.” Journal of Public Policy 32, no. 2: 79–98.
Cross, J. P., R. Eising, H. Hermansson, and F. Spohr. 2021. “Business
Interests, Public Interests, and Experts in Parliamentary Committees:
Their Impact on Legislative Amendments in the German Bundestag.”
West European Politics 44, no. 2: 354–377.
Dür, A. 2008. “Measuring Interest Group Influence in the EU: A Note
on Methodology.” European Union Politics 9, no. 4: 559–576.
Fowler, J. H., T. R. Johnson, J. F. Spriggs, S. Jeon, and P. J. Wahlbeck.
2007. “Network Analysis and the Law: Measuring the Legal Importance
of Precedents at the US Supreme Court.” Political Analysis 15, no. 3:
324–346.
Freeman, L. C. 1977. “A Set of Measures of Centrality Based on
Betweenness.” Sociometry 40: 35–41.
Freeman, L. C. 2002. “Centrality in Social Networks: Conceptual
Clarification.” In Social Network: Critical Concepts in Sociology, 238–
263. Routledge.
Georgiou, I. 2014. “Seeing the Forest for the Trees: An Atlas of the
Politics–Administration Dichotomy.” Public Administration Review 74,
no. 2: 156–175.
Halligan, J. 1995. “Policy Advice and the Public Service.” In Governance
in a Changing Environment, edited by G. B. Peters and D. J. Savoie, 138–
172. McGill–Queen's University Press.
Hanneman, R. A., and M. Riddle. 2005. Introduction to Social Network
Methods. University of California.
Head, B. W. 2016. “Toward More ‘Evidence-­Informed’ Policy Making?”
Public Administration Review 76, no. 3: 472–484.
Hesstvedt, S., and J. Christensen. 2023. “Norwegian Public Inquiry
Commissions Dataset.” Sikt. https://​doi.​org/​10.​18712/​NSD-­​NSD29​
71-­​V2.
Hunter, A., and C. Boswell. 2015. “Comparing the Political Functions
of Independent Commissions: The Case of UK Migrant Integration
Policy.” Journal of Comparative Policy Analysis 17, no. 1: 10–25.
Hur, W. 2017. “The Patterns of Knowledge Spillovers Across Technology
Sectors Evidenced in Patent Citation Networks.” Scientometrics 111:
595–619.
Hustedt, T., and S. Veit. 2017. “Policy Advisory Systems: Change
Dynamics and Sources of Variation.” Policy Sciences 50: 41–46.
Jennings, E. T., Jr., and J. L. Hall. 2012. “Evidence-­Based Practice and
the Use of Information in State Agency Decision Making.” Journal of
Public Administration Research and Theory 22, no. 2: 245–266.
Jørgensen, J. V. 2024. “Knowledge Utilisation Analysis: Measuring
the Utilisation of Knowledge Sources in Policy Decisions.” Evidence &
Policy 20, no. 2: 205–225.
Karseth, B., K. Sivesind, and G. Steiner-­Khamsi. 2022. Evidence and
Expertise in Nordic Education Policy: A Comparative Network Analysis.
Palgrave Macmillan.
Klüver, H. 2015. “The Promises of Quantitative Text Analysis in Interest
Group Research: A Reply to Bunea and Ibenskas.” European Union
Politics 16, no. 3: 456–466.
Knott, J., and A. Wildavsky. 1980. “If Dissemination Is the Solution,
What Is the Problem?” Knowledge 1, no. 4: 537–578.
Krackhardt, D., and R. N. Stern. 1988. “Informal Networks and
Organizational Crises: An Experimental Simulation.” Social Psychology
Quarterly 51: 123–140.
Landry, R., M. Lamari, and N. Amara. 2003. “The Extent and
Determinants of the Utilization of University Research in Government
Agencies.” Public Administration Review 63, no. 2: 192–205.
Leydesdorff, L. 2007. “Betweenness Centrality as an Indicator of the
Interdisciplinarity of Scientific Journals.” Journal of the American
Society for Information Science and Technology 58, no. 9: 1303–1319.
Lupu, Y., and E. Voeten. 2012. “Precedent in International Courts: A
Network Analysis of Case Citations by the European Court of Human
Rights.” British Journal of Political Science 42, no. 2: 413–439.
Ma, J., and Y. Cheng. 2025. “Why Do Some Academic Articles Receive
More Citations From Policy Communities?” Public Administration
Review 85, no. 3: 907–929.
Mesquita, R., and A. Pires. 2024. “The References of the Nations:
Introducing a Corpus of United Nations General Assembly Resolutions
Since 1946 and Their Citation Network.” Journal of Peace Research 62:
00223433241254997.
Pattyn, V., A. Gouglas, and J. De Leeuwe. 2021. “The Knowledge Behind
Brexit. A Bibliographic Analysis of Ex-­Ante Policy Appraisals on Brexit


## Page 15

444
Public Administration Review, 2026
in the United Kingdom and the European Union.” Journal of European
Public Policy 28, no. 6: 821–839.
Raymaekers, P., K. Migchelbrink, V. Pattyn, and P. De Smedt. 2026.
“Organizational and Individual Factors of Evidence Informed Policy
Making in Public Organizations.” Public Administration Review 86,
no. 1: 58–73.
Saqr, M., and W. Peeters. 2022. “Temporal Networks in Collaborative
Learning: A Case Study.” British Journal of Educational Technology 53,
no. 5: 1283–1303.
Schmidt, V. A. 2010. “Taking Ideas and Discourse Seriously: Explaining
Change Through Discursive Institutionalism as the Fourth ‘New
Institutionalism’.” European Political Science Review 2, no. 1: 1–25.
Smith, M. J., A. J. Baxter, K. Skivington, M. McCann, S. Hilton, and S. V.
Katikireddi. 2021. “Examining the Sources of Evidence in E-­Cigarette
Policy Recommendations: A Citation Network Analysis of International
Public Health Recommendations.” PLoS One 16, no. 8: e0255604.
Szomszor, M., and E. Adie. 2022. “Overton: A Bibliometric Database
of Policy Document Citations.” Quantitative Science Studies 3, no. 3:
624–650.
Vilkins, S., and W. J. Grant. 2017. “Types of Evidence Cited in Australian
Government Publications.” Scientometrics 113, no. 3: 1681–1695.
Wasserman, S., and K. Faust. 1994. Social Network Analysis: Methods
and Applications. Cambridge University Press.
Weible, C. M. 2008. “Expert-­Based Information and Policy Subsystems:
A Review and Synthesis.” Policy Studies Journal 36, no. 4: 615–635.
Weiss, C. H. 1979. “The Many Meanings of Research Utilization.” Public
Administration Review 39, no. 5: 426–431.
Wilkerson, J., D. Smith, and N. Stramp. 2015. “Tracing the Flow of
Policy Ideas in Legislatures: A Text Reuse Approach.” American Journal
of Political Science 59, no. 4: 943–956.
Supporting Information
Additional supporting information can be found online in the
Supporting Information section. Data S1: puar70014-­sup-­0001-­supinfo.

