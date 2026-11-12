# The role of institutional factors in shaping university mission statements A top

## Page 1

R E S E A R C H A R T I C L E
The role of institutional factors in shaping university mission
statements: A topic-modeling approach
Nicole Philippczyck1
|
Harry Hoffmann1
|
Simon Oertel2
1Department of Economic Sciences and Media,
Management/Organization Group, Technische
Universität Ilmenau, Ilmenau, Germany
2Faculty of Law, Business and Economics,
Department of Business, Strategic Management
and Organization, Paris Lodron University of
Salzburg, Salzburg, Austria
Correspondence
Simon Oertel, Faculty of Law, Business and
Economics, Department of Business, Strategic
Management and Organization, Paris Lodron
University of Salzburg, Kapitelgasse 5–7, A-5020
Salzburg, Austria.
Email: simon.oertel@plus.ac.at
Abstract
Mission statements are common instruments for the strategic positioning of uni-
versities. However, there are few large-scale, cross-national studies examining the
factors that influence the content of universities’ mission statements. We address
this research gap, exploring the content of 413 mission statements from European
universities by applying correlated topic modeling (CTM). Moreover, relying on
institutional theories of organization, we study factors that explain differences in
the content of mission statements. Our findings reveal six distinct topics addressed
in mission statements. The prevalence of a specific topic is significantly shaped by
the cultural rationalization of the universities’ national context, the university’s
founding context, and institutional control. Our findings not only contribute to
research on universities’ strategic positioning but also shed light on the diffusion
of global trends across organizations and the determinants of their adaptation.
Moreover, our study offers an illustrative example of how big data analytics can
enhance public administration research.
Evidence for practice
• Institutional factors influence the crafting of mission statements.
• Mission statements are a tool for strategic positioning.
• CTM is an effective tool for analyzing large-scale textual data in public
administration.
INTRODUCTION
In the recent decades, universities worldwide have been
exposed to increasing rationalization pressures, trans-
forming them into modern organizations (Bozeman &
Youtie, 2020; Meyer & Schofer, 2007; Meyer & Bromley,
2013; Oliver-Lumerman & Drori, 2021; Ramirez, 2020;
Ramirez & Christensen, 2013). This “organizational turn”
implies that universities become organizational actors in
the sense of “an integrated, goal-oriented entity that
deliberately chooses its actions and can thus be held
responsible for what it does” (Krücken & Meier, 2006, p.
241). Based on this development, universities have also
become more central to public administration research
(Boer et al., 2007; Christensen et al., 2020; Crow et al.,
2020; Fowles et al., 2016; Oertel, 2018; Pearce et al., 2018;
Rabovsky & Rutherford, 2016). Examining universities as
public organizations, these studies focus on various
aspects of university structure, administration, and strate-
gic behavior. They highlight the complexity of universities
as organizational actors and the adaptation of strategies
that universities pursue regarding an increasingly global-
ized educational landscape. Empirically, these studies
show, for example, that national contexts and cultural dif-
ferences
have
a
significant
effect
on
universities
(Christensen et al., 2020; Fowles et al., 2016), that imprint-
ing has an influence on the structure of universities
(Oertel, 2018), and that strategic decisions in universities
and leadership issues have fundamentally gained in
importance (Crow et al., 2020; Pearce et al., 2018;
Rabovsky & Rutherford, 2016).
Universities becoming organizational actors has led
them to adopt rationalized business practices and struc-
tures (Townley, 1997), including for example, reputation
Received: 16 February 2023
Revised: 28 November 2024
Accepted: 10 December 2024
DOI: 10.1111/puar.13921
This is an open access article under the terms of the Creative Commons Attribution License, which permits use, distribution and reproduction in any medium, provided the
original work is properly cited.
© 2025 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.
Public Admin Rev. 2025;85:1187–1216.
wileyonlinelibrary.com/journal/puar
1187


## Page 2

management (Christensen et al., 2020; Christensen &
Gornitzka, 2017) and quality management (Csizmadia
et al., 2008), and let them become more internationally
oriented (Delgado-M�arquez et al., 2013; Zapp et al., 2021).
In line with this development, mission statements have
become increasingly popular in universities (Arias-Coello
et al., 2020; Davies & Glaister, 1996; Kosmützky, 2012;
Kosmützky & Krücken, 2015; Mizrahi-Shtelman & Drori,
2021; Morphew & Hartley, 2006; Oertel & Söll, 2017;
Seeber et al., 2019). According to Drucker (1974), mission
statements can be a valuable instrument for organiza-
tions, as they articulate business goals, values, and essen-
tial activities for stakeholders. They act as a public
declaration, mirroring organizational self-perceptions and
shaping external views of the organization (Collins &
Porras, 1996; Drucker, 1974; Mizrahi-Shtelman & Drori,
2021; Pearce, 1982; Seeber et al., 2019). Serving as a pro-
totypical identity narrative, they symbolize the organiza-
tion’s
essence
(Ran
&
Duimering,
2007)
and
are
considered important for organizations’ success (Alegre
et al., 2018). Mission statements are also highly relevant
for universities as well as other public organizations, as
they outline expectations from the institutional environ-
ment and allow them to position themselves strategically
in a market by communicating their institutions’ charac-
teristics, values, and history to their audiences (Morphew
& Hartley, 2006; Seeber et al., 2019). As a result, universi-
ties’ mission statements serve both as a guide to action
and as performative identity markers in this context
(Christensen et al., 2019; Frank & Meyer, 2020) and can be
used to gain legitimacy and avoid social sanctions by
aligning the organization with accepted norms and prac-
tices (Czarniawska & Wolff, 1998; Glynn, 2008). In addition
to affirming the organization’s normative identity profile,
they function as discursive enactments of its conceptual
meanings (Mizrahi-Shtelman & Drori, 2021). As such, they
communicate expectations to internal audiences as well
as a university’s institutional environment (Morphew &
Hartley, 2006). Moreover, mission statements also serve a
functional purpose: to align organizational objectives and
achieve internal cohesion (Davies & Glaister, 1996).
Despite extensive studies on mission statements in
public administration in general (Desmidt, 2016; Duncan
et al., 1994; Philipps, 2013) and in universities in particular
(Arias-Coello et al., 2020; Oertel & Söll, 2017; Seeber et al.,
2019), country-level and large-scale research on mission
statements has received scant attention. The few studies
following such an approach have been focused on spe-
cific groups of universities (Bayrak, 2020; S�anchez &
David, 2018), such as the world’s top-ranked universities.
Such “world-class” universities, however, are likely to be
rather homogeneous, limiting the depth of inquiry into
variations in mission statements (Bayrak, 2020). The
lack of large-scale and cross-national research designs
may be attributed to the high time and coding costs asso-
ciated with qualitative content analyses. However, such
approaches
are
highly
relevant,
as
they
provide
comprehensive insights into the factors underlying differ-
ences and similarities in universities’ mission statements
(Fumasoli et al., 2020). Furthermore, such an approach
increases our theoretical understanding of factors that
influence how organizations adapt to global trends and
institutionalized practices (Buckner, 2022; Goldenstein
et al., 2023; Mizrahi-Shtelman & Drori, 2023; Sarta et al.,
2021)—that is, why do some organizations adapt differ-
ently to global trends than others?
Guided by this research question, our study contrib-
utes to a more nuanced understanding of how public
organizations, particularly universities, adapt to or resist
global trends. Building on institutional theories of organi-
zation (Bromley & Meyer, 2015; Buckner & Zapp, 2021;
Marquis & Tilcsik, 2013; Meyer, 2010; Mizrahi-Shtelman &
Drori, 2022; Stinchcombe, 1965), we extend the discourse
on the global diffusion of practices and isomorphism in
public administration (Liu, 2024) by explaining factors
that make isomorphism more or less likely. This is highly
relevant to developing a more comprehensive under-
standing of how public organizations navigate the com-
plex interplay of cultural orientation of the country in
which they are located with institutional and global forces
concerning the adoption and implementation of prac-
tices. Moreover, our study bridges the fields of public
administration and higher education to offer a more
detailed insight into how public organizations strategi-
cally position themselves through mission statements.
This approach directly relates to earlier work in the field
focusing
on
reputation
management
in
universities
(Christensen et al., 2020; Christensen & Gornitzka, 2017)
and adds to discussions regarding how universities
become organizational actors (Krücken & Meier, 2006) as
well as the broader discourse on strategic management
in public organizations (Bryson & George, 2020; Bustos,
2021; Frumkin & Kim, 2001; Poister, 2010). Finally, from a
methodological perspective, we contribute to research in
public administration by applying correlated topic model-
ing (CTM) to bridge traditional qualitative analysis and big
data approaches. This methodological approach is partic-
ularly relevant to research in public administration, as it
has the potential to open up new avenues for under-
standing the strategic behavior of public organizations
(Blei & Lafferty, 2007; Blei et al., 2003; Roberts, Stewart, &
Airoldi, 2016).
Our study sample comprises 413 mission statements
of all 735 European universities located in the Czech
Republic, Denmark, Finland, France, Germany, Greece,
Hungary, Italy, the Netherlands, Norway, Poland, Portugal,
Slovakia, Spain, Sweden, and the United Kingdom.1 Fol-
lowing prior research on universities’ structure and
design, we focus on the cultural orientation of the coun-
try in which the university is located (Delmestri et al.,
2015; Reymert et al., 2021), founding context (Buckner &
Zapp, 2021; Oertel, 2018; Zapp et al., 2021), and institu-
tional control (Buckner, 2017; Oertel & Söll, 2017) of
European universities to better understand the similarities
1188
UNIVERSITY MISSION STATEMENTS


## Page 3

and differences in the content of their mission state-
ments. CTM results show that the content mentioned in
mission statements can be classified into six topics. More-
over, we observe that the cultural orientation of the coun-
try in which a university is located, its founding phase,
and institutional control affect the likelihood that topics
are mentioned in mission statements.
Because the design of our study deviates from the tra-
ditional structure of quantitative papers, we feel it is
important to briefly explain the outline of our study. In
the next section, we will discuss the global diffusion of
university mission statements, including the current state
of research. We then explain our dataset and emphasize
the role of CTM in public administration studies. Next, we
present the exploratory results of the CTM and highlight
the topics derived from the mission statements. Thereaf-
ter, we develop hypotheses about factors that affect
structures and procedures in organizations—that is, cul-
tural orientation, the institutional founding conditions,
and institutional control—proposing that these factors
also influence the content of mission statements. Follow-
ing the presentation of our hypothesis tests, we will dis-
cuss the findings in light of the current literature in the
field.
THE GLOBAL DIFFUSION OF UNIVERSITIES’
MISSION STATEMENTS
According to institutional theory, especially world society
theory (Bromley & Meyer, 2015; Meyer, 2010; Meyer &
Bromley, 2013), global institutionalization strongly influ-
ences universities because their central principles and
purposes are highly similarly constructed (Drori et al.,
2016; Meyer & Schofer, 2007; Ramirez, 2020; Ramirez &
Tiplic, 2014). As universities become increasingly embed-
ded in world society, they face growing pressure to
homogenize. The rising importance of excellence and
rankings also influences such a global orientation (Fowles
et al., 2016; Gerhardt et al., 2023). Research universities in
the United States, which dominate most rankings, are
therefore considered relevant benchmarks in global edu-
cation, and universities can achieve excellence by follow-
ing their best practices (Ramirez, 2020). Given that the
U.S. research university has become a global model for
universities and U.S. universities formulated and imple-
mented
mission
statements
early
in
their
history
(Morphew & Hartley, 2006; Ramirez, 2020; Taylor &
Morphew, 2010), it is not surprising that European univer-
sities are adopting mission statements as well (Arias-
Coello et al., 2020; Flavin et al., 2020; Seeber et al., 2019).
In terms of how global practices and trends are dissemi-
nated through organizations and adapted within them,
the European case is particularly interesting. First, there is
still a difference in the structure of higher education
among countries despite the Bologna reforms. Therefore,
studying the European higher-education sector gives an
insight into what influences the spread of globally institu-
tionalized practices, such as mission statements. Second,
mission statements are not as common in Europe as they
are in the United States (Arias-Coello et al., 2020). There-
fore, their content is less institutionalized.
Today’s best-practice understanding of universities
emphasizes
the
importance of
a
mission
statement
(Ramirez, 2020). An organization’s mission statement
reveals how it perceives itself and how it wants its institu-
tional environment to perceive it (Powell et al., 2016). As
universities strive for legitimacy and identity, they increas-
ingly rely on mission statements rather than governmental
or religious charters (Christensen et al., 2019). Accordingly,
mission statements serve as critical tools for communicat-
ing organizational identity, values, and strategic direction
(Seeber et al., 2019). Because of the diversity of institutions
and the interaction among multiple stakeholders, these
statements are particularly pertinent to higher education.
Table 1 provides an exhaustive list of studies on university
mission statements published since 1995.2
Regarding institutional types, research has focused on
higher-education institutions in general (Flavin et al.,
2020; James & Huisman, 2009; Mizrahi-Shtelman & Drori,
2021; Mizrahi-Shtelman & Drori, 2023), public universities
(Arias-Coello et al., 2020; Berghaeuser & Hoelscher, 2020;
Jungblut & Jungblut, 2017), business schools (Palmer &
Short, 2008), baccalaureate colleges (Taylor & Morphew,
2010), and top-ranked universities (Bayrak, 2020; Breznik
& Law, 2019; S�anchez & David, 2018).
Methodologically, the landscape is equally diverse.
Although quantitative approaches dominate, many stud-
ies use a hybrid methodology that combines qualitative
human coding with frequency analysis. Deductive coding
is the most prevalent (Newsom & Hayes, 1991; Taylor &
Morphew, 2010), followed by inductive (Morphew &
Hartley, 2006; Oertel & Söll, 2017; Seeber et al., 2019) and
combined approaches (Arias-Coello et al., 2020). Several
quantitative studies, however, also use automated con-
tent analysis methods—most commonly word frequency
analysis—which can be combined with clustering (Bayrak,
2020) and/or network analysis (Breznik & Law, 2019) or
collocation analysis (Sauntson & Morrish, 2010). Moreover,
studies combine human assessment and automated
approaches of text analysis, such as manually clustering
keywords and analysis of recurring themes in mission
statements (Mizrahi-Shtelman & Drori, 2021). These can
be used as input for hierarchical clustering and Fisher
tests (Jungblut & Jungblut, 2017).
Despite the plethora of studies, the findings are far
from consistent. Some research indicates a high level of
conformity in the content of mission statements (Davies
& Glaister, 1996; Kuenssberg, 2011; Sauntson & Morrish,
2010), whereas others report significant variance (James
& Huisman, 2009; Jungblut & Jungblut, 2017; Palmer &
Short, 2008). This inconsistency has spurred further
inquiry
into
the
factors
that
might
explain
these
differences.
PUBLIC ADMINISTRATION REVIEW
1189


## Page 4

T A B L E 1
Overview regarding studies on mission statements in higher education institutions.
General information
Analytical
procedure
Applied methods
Sample
Variables
Author(s)
Human
coding
Automated
approach
Inductive
coding
Deductive
coding
Inductive-
deductive
coding
Frequency
of codes
Word
frequencies Others
National
context
Sample
size
Type of institution
Inclusion of
explanatory
variables
National/
Regional
context
Reputation
Founding
context
Institutional
control
Methods
of
statistical
inference
Quantitative Aib and Shehzad (2023)
x
x
x
Not detailed
n = 100 Universities (top 100
listed in QS ranking)
Arias-Coello et al. (2020)
x
x
x
Spain
n = 45
Universities (public)
x
+
Bayrak (2020)
x
x
Clustering
Asia, Africa,
Europe, Latin
America,
North America
n = 227 Universities (top 50
listed in THE; top 27 for
Africa)
x
+
Berghaeuser and Hoelscher
(2020)
x
x
x
Germany
n = 73
Universities (public;
broad disciplinary
spectrum)
Breznik and Law (2019)
x
x
Clustering;
Network
Analysis
USA, UK,
Germany,
Netherlands,
Canada
n = 201 Higher education
institutions (top 250
listed in THE)
Cortés-S�anchez (2018)
x
x
Europe, North
America, Asia,
Oceania, Latin
America,
Africa
n = 248 Universities (top 400
listed in QS ranking)
x
+
+
+
Davies and Glaister (1996)
x
x
x
Chi-Square-
tests
UK
n = 66
Universities
x
(+)
x
Efe and Ozer (2015)
x
x
x
Turkey
n = 171 Universities
x
�
Flavin et al. (2020)
x
x
x
x
x
UK
n = 90
HEI
x
(+)
Giusepponi and Tavoletti
(2018)
x
x
x
Italy
n = 89
Universities
Gonzalez-Campo et al.
(2021)
x
x
x
Columbia
n = 84
Universities
x
+
Hladchenko (2016)
x
(x)
x
Ukraine
n = 46
Universities
x
+
James and Huisman (2009)
x
x
x
UK (Wales)
n = 14
HEI
x
+
+
Jungblut and Jungblut
(2017)
x
x
x
Hierarchical
clustering;
Fisher Tests
Germany
n = 74
Universities (public)
x
+
-
x
Kuenssberg (2011)
x
x
x
x
UK (Scotland)
n = 20
Universities
(x)
(+)
Mackay et al. (1995)
x
x
x
UK
n = 101 HEI
x
Manning (2021)
x
x
x
East Asia
n = 84
Universities (top listed
in QS, THE, US News,
Shanghai Jiaotong
University ranking)
x
+
Mizrahi-Shtelman and Drori
(2022)
x
x
x
Israel
n = 62
All accredited HEO
x
Mizrahi-Shtelman and Drori
(2021)
x
x
x
Israel
n = 65
All accredited HEO
x
Morphew and Hartley (2006) x
x
x
US
n = 299 4-year colleges and
universities
x
+
Newsom and Hayes (1991)
x
x
x
US
(southeastern
states)
n = 93
HEI (colleges)
x
+
Oertel and Söll (2017)
x
x
Logistic
regression
Germany
n = 75
Universities
x
(+)
+
+
x
Ozdem (2011)
x
x
x
Turkey
n = 72
Universities (public)
x
+
1190
UNIVERSITY MISSION STATEMENTS


## Page 5

Interestingly, cross-country studies are relatively rare
even though the institutional setting of a university is
likely a significant determinant of its mission. Instead,
much research has been conducted in the United States
(Morphew & Hartley, 2006; Newsom & Hayes, 1991; Taylor
& Morphew, 2010) and the U.K. (Connell & Galasi�nski,
1998; Davies & Glaister, 1996; Seeber et al., 2019) and
more specifically Scotland (Kuenssberg, 2011) and Wales
(James & Huisman, 2009). Research has also covered
Germany (Jungblut & Jungblut, 2017; Kosmützky, 2012;
Kosmützky & Krücken, 2015; Oertel & Söll, 2017), Spain
(Arias-Coello et al., 2020), Italy (Giusepponi & Tavoletti,
2018), Ukraine (Hladchenko, 2016), Turkey (Efe & Ozer,
2015; Ozdem, 2011), Israel (Mizrahi-Shtelman & Drori,
2021; Mizrahi-Shtelman & Drori, 2023), and Colombia
(Gonzalez-Campo et al., 2021). However, a few studies
also include multiple countries (Aib & Shehzad, 2023;
Bayrak, 2020; Breznik & Law, 2019; Manning, 2021; Cortés-
S�anchez, 2018), but comparative approaches are rare
(Bayrak, 2020; Cortés-S�anchez, 2018 Manning, 2021;).
These studies show differences in word usage (Bayrak,
2020; Manning, 2021) and mission statement length
(Cortés-S�anchez, 2018) across countries. However, these
studies do not compare all universities in a country but
instead select a few universities (such as top-ranked uni-
versities worldwide). Consequently, these studies provide
a limited perspective regarding mission statements—top
universities tend to be relatively homogeneous and face
similar environmental demands and are therefore likely
to have less diverse mission statements.
Besides the country of origin, the role of institutional
history and founding phases has been examined (Arias-
Coello et al., 2020; Hladchenko, 2016; James & Huisman,
2009; Kuenssberg, 2011; Oertel & Söll, 2017; Seeber et al.,
2019). For instance, Spanish universities founded during
different historical periods reflect the conditions and mis-
sions assigned at the time of their establishment (Arias-
Coello et al., 2020). Similarly, German universities founded
in earlier periods are less likely to include a service logic
in their mission statements than those founded more
recently (Oertel & Söll, 2017).
Furthermore, the distinction between the public and
private sectors is a frequent topic. Public universities
often emphasize regional commitments, whereas private
universities focus on their philosophical underpinnings
(Morphew & Hartley, 2006; Newsom & Hayes, 1991;
Palmer & Short, 2008). These mission statements are
shaped by the priorities of various stakeholders, which
differ in institutional type (Morphew & Hartley, 2006).
In summary, existing research on university mission
statements is extensive and varied, covering multiple
institutional
characteristics,
such
as
size,
reputation,
research output, internationalization, and disciplinary pro-
file (Cortés-S�anchez, 2018; Mizrahi-Shtelman & Drori,
2021, 2023; Oertel & Söll, 2017; Seeber et al., 2019; Taylor
& Morphew, 2010). However, the findings are often incon-
sistent and predominantly descriptive, particularly in
T A B L E 1
(Continued)
General information
Analytical
procedure
Applied methods
Sample
Variables
Author(s)
Human
coding
Automated
approach
Inductive
coding
Deductive
coding
Inductive-
deductive
coding
Frequency
of codes
Word
frequencies Others
National
context
Sample
size
Type of institution
Inclusion of
explanatory
variables
National/
Regional
context
Reputation
Founding
context
Institutional
control
Methods
of
statistical
inference
Palmer and Short (2008)
x
x
x
Clustering;
General
Linear
Models;
F-tests
US
n = 408 Business Schools
(AACSB-accredited)
x
+
x
Sauntson and Morrish
(2010)
x
x
Collocation
analysis
UK
n = 53
Universities
x
(+)
Seeber et al. (2019)
x
x
x
Co-
occurrences
of codes;
Poisson
regression
UK
n = 123 Universities
x
+
(+)
x
Taylor and Morphew (2010)
x
x
x
US
n = 100 Baccalaureate colleges
x
Qualitative
Kosmützky (2012)
x
x
Germany
n = 42
Universities
(x)
(+)
Kosmützky and Krücken
(2015)
x
x
Germany
n = 42
Universities; UAS
x
(+)
Mixed
methods
Connell and Galasi�nski
(1998)
x
x
x
(x)
UK
n = 146 Universities
Notes: + signifies that the included variable exerted an effect on the universities’ mission statement. (+) signifies that there was only a slight impact of the variable. �signifies that the included variable did not exert an effect.
PUBLIC ADMINISTRATION REVIEW
1191


## Page 6

comparative studies with larger sample sizes (Bayrak,
2020; Cortés-S�anchez, 2018). Moreover, most studies lack
robust statistical inference methods, which are generally
only applied in single-country studies with smaller sample
sizes (Davies & Glaister, 1996; Jungblut & Jungblut, 2017;
Seeber et al., 2019).
We aim to address these gaps by using a methodolog-
ically rigorous two-step approach. In the first phase, we
utilize CTM to conduct an exploratory analysis of the con-
tent of mission statements from European universities.
This is a critical step, as it allows us to identify the domi-
nant themes that are prevalent in these statements,
thereby laying the groundwork for our subsequent
research. In the second phase, we will develop and empir-
ically test hypotheses concerning the factors that influ-
ence the content of these mission statements, using
regression modeling techniques.
By integrating both exploratory and deductive statisti-
cal methods, we aspire to provide a more comprehensive
and nuanced understanding of the content and influenc-
ing factors of university mission statements. We take this
approach not only to reconcile the inconsistencies found
in previous research but also contribute substantively to
the academic discourse on institutional identity and stra-
tegic direction in higher education.
EMPIRICAL INVESTIGATION I: EXPLORING
THE CONTENT OF MISSION STATEMENTS OF
EUROPEAN UNIVERSITIES
This section focuses on capturing the core content of
European universities’ mission statements. Using CTM, we
identify the dominant topics in these statements. In this
section, we shed light on our data collection methodol-
ogy, CTM intricacies, and the thematic landscape of
European higher-education mission statements.
Data and data collection
The data for this study were obtained from the European
Tertiary Education Register (ETER) database (ETER project,
2021). ETER is a project funded by the EU and compiles
microdata on higher-education institutions in Europe. Our
data collection proceeded as follows. First, we retrieved
the full list of universities in the four largest countries in
Northern
Europe
(Denmark,
Finland,
Norway,
and
Sweden), Central and Eastern Europe (Czech Republic,
Hungary, Poland, and Slovakia), Southern Europe (Greece,
Italy, Portugal, and Spain), and Western Europe (France,
Germany, the Netherlands, and the United Kingdom)
based on their GDP from the ETER database (ETER project,
2021).3,4 We examined the listed institutions’ right to
award doctorates as a central indicator of universities.
Moreover, 11 French institutions had to be excluded
because they were listed separately in ETER but were not
independent universities. Therefore, our sample included
791 universities. We collected mission statements from
the universities’ websites based on this dataset. To ensure
comparability in our cross-national design, only English-
language mission statements were included. Two steps
were followed during data collection. Initially, five student
research assistants and the first and second authors
searched for mission statements on the assigned universi-
ties’ websites. We looked for university mission state-
ments explicitly labeled “mission (statement).” We then
consolidated and cross-validated 741 universities that
offered English websites. We also conducted a web
search to fill in missing values because the ETER data for
some
universities
is
incomplete.
The
final
analysis
included 735 universities with complete data. A mission
statement was found for 413 of the universities (351 pub-
lic universities and 62 private universities).
Correlated topic modeling
In the recent years, topic modeling has become increas-
ingly relevant for big data analysis in public administra-
tion research (Hollibaugh, 2019; Moschella & Pinto, 2019;
Walker et al., 2019). We applied CTM, a type of topic
modeling that incorporates a logistic normal topic distri-
bution to capture correlations between topics based on
latent dirichlet allocation (LDA). Assuming topics are
independent of each other in text mining document
classification can be quite restrictive in real-world appli-
cations, where topics frequently exhibit correlations. By
allowing topics to be correlated, CTM captures more
complex relationships between them (Blei & Lafferty,
2007). This is particularly important in public administra-
tion research, where complex interactions and correla-
tions
between
different
topics
are
common
(Hollibaugh, 2019).
In general, topic modeling is a text-mining method that
uncovers recurring themes in text data via unsupervised
learning (Bohn & Braun, 2021; Bohn & Rogge, 2022). The
resulting topics are distributions of words that frequently
occur together. Topic modeling enables the analysis of large
corpora that human readers cannot otherwise comprehend
(Bohn & Braun, 2021; Bohn & Rogge, 2022; Hannigan et al.,
2019; Kobayashi et al., 2018; Schmiedel et al., 2019).
When a topic model is fitted to a corpus, the underly-
ing document–topic and topic–word distributions are
estimated using an optimization algorithm. In the case of
CTM, the distribution parameters are estimated using vari-
ational expectation–maximization (Blei & Lafferty, 2007).
The main parameter is the number of topics, k. To find an
appropriate number of topics, various topic models can
be evaluated and compared using statistical metrics. In
this respect, topic modeling offers a relatively simple but
highly valuable methodological approach to analyzing
and structuring data (Bohn & Braun, 2021; Bohn & Rogge,
2022; Kobayashi et al., 2018).
1192
UNIVERSITY MISSION STATEMENTS


## Page 7

To apply CTM, we followed established preprocessing
steps (Banks et al., 2018; Hickman et al., 2022). First, we
transformed all words into lowercase and removed non-
alphanumeric characters. Then, numbers representing
years were replaced with a special token to preserve the
context of time, for instance when a university refers to
its future or history. The remaining numerical characters
were removed because they were often only part of list-
ings. Second, words were stemmed and converted into
tokens. To further reduce noise and improve topic quality,
we removed words that occurred too frequently or not
frequently enough to be meaningful. Specifically, we only
used words that occurred in a minimum of five docu-
ments and in less than fifty percent of the documents.
Third, the preprocessed data were analyzed using CTM,
where each mission statement represents a document.
The R package stm was used for the analysis.5
Method evaluation
Without proper evaluation and data processing, topic
modeling can lead to biased results. Therefore, we also
evaluated our method after processing the data. First,
because our study focuses on mission statements, we also
considered the literature on topic modeling, which raises
concerns about applying the method to comparatively
short texts (Albalawi et al., 2020; Phan et al., 2011; Yan et
al., 2013; Zuo et al., 2016). Short texts contain less infor-
mation about word co-occurrences, and sparsity might be
introduced in bag-of-words vectors, which makes calcu-
lating meaningful distance measures between vectors dif-
ficult (Phan et al., 2011). Therefore, as Albalawi et al.
(2020, p. 1), noted, it becomes “challenging to discover
useful information or more on the topic being discussed
from such content.” In our study, we analyzed mission
statements with an average length of 75 words and a
median length of 167 words. After preprocessing, which
included the removal of both rare and frequent words,
the mission statements had a mean length of 54 words
and a median length of 120 words. Given that these
lengths are close to the threshold for short texts of 50
words, as defined by Vayansky and Kumar (2020), we
carefully validated our resulting model to ensure topic-
modeling reliability. The previously mentioned removal of
rare words reduces sparsity in the bag-of-words vectors
while also reducing computational complexity. We vali-
dated the model by closely reviewing the resulting topic
and word distributions and through close reading of doc-
uments associated with the topics, assuring that the
topics are coherent and the distributions are not majorly
imbalanced. A possible method to improve the topic
model is the utilization of document metadata when esti-
mating topic prevalence, as proposed in the structural
topic model (STM; Grimmer et al., 2022; Roberts, Stewart,
& Tingley, 2016; Roberts et al., 2014). The results of the
CTM are robust compared to an STM fitted with the
covariates described later in this paper (Empirical Investi-
gation II). However, we refrained from using STM with
prevalence covariates for topic discovery because this
would introduce dependencies to topic prevalence on
the aforementioned covariates that are used to explain
topic prevalence in our regression analysis. After this
extensive validation, we conclude that CTM is appropriate
to use with our dataset.
Second, the question of the number of topics is often an
issue of concern in the context of topic modeling (Bohn &
Braun, 2021). At the same time, various methodological
options can eliminate such concerns or at least reduce them
to a minimum. Our decision regarding the number of topics
was based on multiple models that were trained and evalu-
ated with different topic numbers k = [2, …, 30] that were
appropriate for the corpus size of 413 documents of short
to medium length. Then, we selected models that per-
formed well based on log likelihood and semantic coher-
ence of the words occurring in a set of held-out test
documents given the previously fitted distributions of topics
and words per topic. A high likelihood indicates strong gen-
eralization capabilities (Blei et al., 2003). Semantic coherence
indicates topic quality and determines whether a topic’s top
words actually co-occur in documents (Mimno et al., 2011).
Figure 1 presents the log likelihood and semantic coherence
for models with different values for k in our search space.
From these model candidates, we chose a model with k = 6
topics because of the distinctiveness between its topics and
coherence within topics compared to other models. We
used spectral learning as an initialization method for all
fitted models. This way, not only the computing speed was
increased but most notably convergence at the optimal
parameters; also the results’ reproducibility was guaranteed,
circumventing multi-modality concerns usually associated
with traditional topic-modeling approaches (Roberts, Stew-
art, & Airoldi, 2016).
Findings regarding the content of mission
statements
Utilizing CTM, we identified six distinct topics in European
university mission statements. Given that labeling of topics
can often be a concern, we chose not to assign the labels
ourselves. Instead, we consulted six experts in the field: two
university vice presidents, a director of university communi-
cations, a dean and organizational researcher, and two
researchers specializing in higher-education research in
Europe. We contacted these experts independently via
email in August 2023 and presented them with the top
word lists for each topic. In the email, we asked them to
suggest possible labels. The experts’ responses were notably
consistent and clarified a cognitively well-perceived distinc-
tion between the topics. For example, experts labeled topic 1
“knowledge transfer,” “exploitation of research,” “research,”
or “transfer orientation.” Based on this expert feedback, we
defined the topics as follows (Table 2).
PUBLIC ADMINISTRATION REVIEW
1193


## Page 8

Upon examining the terms defining each topic, it
becomes apparent that their content is substantially dif-
ferent. For instance, mission statements related to topic
three are likely to contain terms such as “community,”
“values,” “respect,” “culture,” and “principles.” Conse-
quently, mission statements central to this topic under-
score the significance of university values, such as the
mission statement of the University of Girona.
The University of Girona is grounded on the
basic principles of freedom, justice, solidarity
and the culture of peace, and is committed
to promoting education in values and in
equal opportunities, and to fighting against
discrimination on the grounds of gender,
class, ethnicity, religion or any other distinc-
tive
feature
of
persons
and
collectives,
assuming
the
Universal
Declaration
of
Human Rights of the United Nations as its
own. In accordance with these principles and
the ideals of solidarity among peoples, the
University of Girona will cooperate in the
social and cultural progress of poor and
impoverished countries and countries in the
process of development.
The
terms
“science,”
“technology,”
“society,”
“public,” and “transfer” feature prominently in topic one,
indicating a discernible orientation toward the accessibil-
ity and application of research results by the public. As
illustrated below, the mission statement of the University
of M�alaga exemplifies this topic.
The aim of UMA’s Office for Transfer of
Research Results (OTRI) is to energise rela-
tions between the scientific community and
the
business
world.
Therefore,
OTRI
is
responsible for identifying the technological
needs in socio-economic sectors so as to fill
this technological gap between the public
and private sectors, thus contributing to the
implementation and commercialisation of
results
produced
by
the
University
of
M�alaga.
When interpreting the findings, certain terms can
appear simultaneously in different topics. The frequency
of occurrence of specific terms and their combinations
with others differ across topics. Topics that share some
terms may be dissimilar due to these differences. There-
fore, identifying which terms appear universally in all mis-
sion statements is essential for interpreting the findings
and compiling topics. For example, terms such as
“university,” “research,” “students,” and “education” can
be found in almost all mission statements. Table 3 lists
these terms, which tend to overlay differences between
mission statements rather than highlight them; therefore,
we excluded them.
Although the six topics we observed can be differenti-
ated based on their prevalence in the mission statements,
not all topics are equally distinct from one another.
Figure 2 illustrates these distances between topics. Based
on Jensen–Shannon divergence and estimated propor-
tions of topics in the CTM (Cox & Cox, 2008; Lin, 1991),
Figure 2 illustrates the two-dimensional representation of
relations between topics. Topic centers are spaced based
on how dissimilar the topics are, and bubble sizes reflect
the topic proportion across all analyzed mission state-
ments. Looking at Figure 2, it becomes obvious that, for
example, the topics “Profession and Performance” and
“Academic Excellence” differ regarding content, but the
degree of difference is smaller than between, for example,
F I G U R E 1
Metrics of model quality for correlated topic models with different k-values.
1194
UNIVERSITY MISSION STATEMENTS


## Page 9

T A B L E 2
Topic labels and most probable words of our final CTM.
Topic
Label
Description
Top words by probability
Top words by FREX
1
Research and
Knowledge
Transfer
This topic emphasizes the active role
of universities in promoting scientific,
technological, and creative
innovations. It underscores the
importance of research and its
application in various fields, both
regionally and internationally. The
label “Research and Knowledge
Transfer” captures the essence of this
topic. Words like “active”, “scienc”,
“technolog”, “innov”, and “transfer”
highlight the university’s commitment
to not only conducting research but
also transferring this knowledge to
benefit society.
Activ, scienc, cultur, scientif, econom,
technolog, social, promot, societi,
institut, field, intern, contribut, area,
innov, region, technic, public, creativ,
transfer
Technolog, econom, technic, dissemin,
scienc, activ, transfer, sport,
environment, artist, field, product,
cultur, promot, creation, creativ,
scientif, organ, depart, czech
2
Academic
Excellence
This topic revolves around the
university’s academic programs,
degrees, faculty, and goals. It also
touches upon the international
collaborations and the continuous
strive for higher standards in
academia. “Academic Excellence” is a
label that encapsulates the university’s
dedication to offering top-tier
academic programs and
collaborations. Terms like “program”,
“degree”, “academ”, and “high”
emphasize this commitment to quality
and excellence.
Programm, intern, studi, <YEAR>,
degre, goal, collabor, graduat, increas,
initi, academ, faculti, continu,
contribut, societi, strengthen, new,
defin, establish, high
Degre, programm, defin, initi, increas,
rank, strengthen, collabor, phd, year,
even, goal, number, compani, labour,
faculti, graduat, sector, offic, <YEAR>
3
Cultural and
Community
Values
This topic delves into the humanistic
and cultural aspects of the university,
emphasizing community, human
values, traditions, and academic
freedom. The label “Cultural and
Community Values” aligns well with
the topic’s focus on “community”,
“human”, “cultur”, “valu”, and
“freedom”, highlighting the
university’s commitment to fostering a
rich cultural environment and
upholding community values.
Communiti, human, cultur, academ,
valu, respect, <YEAR>, life, tradit,
freedom, institut, social, principl,
peopl, societi, good, teach, activ,
scientif, world
Link, christian, respect, truth, cathol,
scholar, church, freedom, faith, human,
everi, thought, tradit, express,
communiti, solidar, sens, religion,
realiti, good
4
Globalization
and World
Society
This topic suggests a forward-looking
vision with a global perspective,
emphasizing the university’s role in
addressing global challenges,
sustainability, and shaping the future.
“Globalization and World Society” is a
label that captures the essence of
terms like “world”, “society”, “global”,
and “intern”, which indicate the
university’s commitment to having a
global impact and preparing students
for a rapidly globalizing world.
World, societi, innov, communiti,
sustain, futur, excel, creat, global, valu,
challeng, peopl, new, intern, chang,
contribut, commit, social, make, shape
Global, sustain, leader, entrepreneuri,
impact, potenti, transform, inclus,
inspir, shape, across, challeng,
approach, world, deliv, chang, innov,
generat, excel, societ
5
Functional
Core
This topic emphasizes the act of
teaching, the responsibilities
associated with it, and the support
structures in place within the
university for both faculty and
students. The label “Functional Core”
suggests the foundational and
operational aspects of the university.
Words like “teach”, “respons”,
Teach, academ, respons, support,
member, commit, work, studi, intern,
orient, continu, promot, provid, scienc,
social, cooper, area, offer, universit,
administr
Universit, member, third, teach, orient,
administr, famili, equal, subject,
respons, commit, women, qualif, see,
transpar, self, scientist, support,
structur, academ
(Continues)
PUBLIC ADMINISTRATION REVIEW
1195


## Page 10

the topics “Research and Knowledge Transfer” and “Cultural
and Community Values.” Figure 2 also shows that the two
most prominent topics in the mission statements we ana-
lyzed are “Globalization and World Society” and “Research
and Knowledge Transfer.” These are followed by “Cultural
and Community Values” and “Profession and Performance”
and then by the topic “Functional Core.”
EMPIRICAL INVESTIGATION II: FACTORS
EXPLAINING THE CONTENT OF MISSION
STATEMENTS
Having clarified the “what” aspect by exploring the con-
tent of European universities’ mission statements using
CTM, we now focus on the “why”—the factors that influ-
ence this content. We propose that the narratives that
universities adopt in their mission statements are not ran-
dom but are shaped by external and internal factors. The
question of factors influencing structures and practices in
organizations is a central topic in organization and public
administration research (Christensen et al., 2020; Oertel,
2018), but comparatively few studies have been con-
ducted to examine the influence of such factors on the
content of mission statements (Seeber et al., 2019). How-
ever, this issue is of high relevance because mission
statements capture an organization’s identity, values, and
strategic direction (Alegre et al., 2018; Bart Baetz, 1998;
Mizrahi-Shtelman & Drori, 2021; Sasaki et al., 2020; Seeber
et al., 2019) and, consequently, can affect the success of
organizations (Alegre et al., 2018).
In the following section, we will develop and empiri-
cally test hypotheses that help explain the differences in
the content of European universities’ mission statements.
With respect to factors that influence mission statements’
contents, we focus on well-known factors that have
proven
to
influence
organizational
structures
and
procedures—that is, regional location (Delmestri et al.,
2015; Drori et al., 2013; Höllerer et al., 2017; Mizrahi-
Shtelman & Drori, 2022), institutional foundational condi-
tions (Marquis & Tilcsik, 2013; Stinchcombe, 1965), and
institutional control (Buckner, 2017; Ferreira & Hill, 2008;
Schulz et al., 2023).
Cultural rationalization and national context
World society theory focuses on institutional processes of
cultural rationalization and argues that organizational
models and practices spread globally not only for reasons
of efficiency but also because applying these models and
practices
promises
legitimacy
in
global
competition
T A B L E 2
(Continued)
Topic
Label
Description
Top words by probability
Top words by FREX
“support”, and “university” highlight
the essential functions that drive the
institution’s day-to-day operations.
6
Profession
and
Performance
This topic emphasizes the quality and
standards of education, as well as the
specialized training that prepares
students for professional roles.
“Profession and Performance” is a
label that underscores the university’s
commitment to delivering high-quality
education and training. Terms like
“quality”, “train”, “profession”, and
“performance” highlight the focus on
preparing students for professional
excellence.
Qualiti, train, provid, higher, high,
school, learn, profession, institut,
scientif, need, achiev, level, skill,
nation, cours, conduct, health, region,
aim
Train, school, agricultur, health,
hungarian, conduct, system, medicin,
hungari, power, qualiti, carri, oper,
medic, higher, food, care, need, wide,
veterinari
T A B L E 3
Excluded common words and their frequencies.
Words
Number of documents in which the word
appears
Share of documents in which the word
appears
Absolute number of
occurrences
<ORG>
321
78%
2590
research
305
74%
1219
educ
292
71%
759
univers
264
64%
1385
knowledg
228
55%
458
develop
225
54%
623
student
211
51%
574
1196
UNIVERSITY MISSION STATEMENTS


## Page 11

(Bromley & Meyer, 2015; Meyer, 2010; Meyer & Bromley,
2013). Cultural rationalization refers to the process by
which modern societies are influenced and evolve via the
interplay among global models of scientization, individual
rights, and education (Meyer, 2000, 2010; Meyer &
Bromley, 2013). In higher education, this process of cul-
tural rationalization has been particularly pertinent since
the 20th century, with universities experiencing exponen-
tial growth and rationalization (Drori et al., 2016; Krücken
& Meier, 2006; Meyer et al., 2007). In this respect, it is not
surprising that universities increasingly implement mis-
sion statements because they are widespread and legiti-
mate in top universities worldwide (Bayrak, 2020; S�anchez
& David, 2018).
Despite the emphasis on global isomorphism, world
society theory also acknowledges the role of national con-
texts and local translation processes that lead to differ-
ences
in
the
implementation
of
global
norms
(Boxenbaum, 2006; Drori et al., 2014a, 2014b; Goldenstein
et al., 2023). This argument refers to glocalization, a con-
cept that describes globalization processes as reshaped
by local conditions and in which local entities such as
organizations adopt and adapt global models to meet
specific local needs (Drori et al., 2013; Höllerer et al.,
2017). With respect to world society theory, glocalization
highlights the unequal patterns of diffusion and the vari-
ous costs of isomorphism that are explained by differ-
ences
in
local
institutions
and
structures
(Mizrahi-
Shtelman & Drori, 2022).
This local translation can also be observed with
respect
to
higher
education,
in
which
differences
between national systems persist (Christensen et al.,
2020; Delmestri et al., 2015; Drori et al., 2016), as local
institutions
vary
in
strength
and
national
higher-
education systems differ in historically grown traditions
(Dobbins et al., 2011; Neave, 2003; Ramirez, 2006). Conse-
quently, the diffusion of a globally spreading logic of
rational and professional organization varies in speed
across regions (Delmestri et al., 2015), which affects the
contents of university mission statements.
Focusing on research on mission statements, the small
body of existing research on regional differences in
content
shows
contradictory
findings.
For
example,
Cortés-S�anchez (2018) examines the length and word fre-
quencies of 248 university mission statements worldwide
based on top-ranked universities in the QS World Univer-
sity Ranking. The findings show that a university’s
regional location strongly influences certain content; for
example, universities in Latin American countries place
comparatively strong emphasis on the context of society
and knowledge creation. In European countries, the term
“research” appears to be dominant in mission statements.
“Students,” in contrast, appears most frequently as a
content-related term in the mission statements of univer-
sities from countries in the Oceania region. Taking a simi-
lar approach, Bayrak (2020) focuses on 227 mission
statements from top-ranked universities on each conti-
nent based on the Times Higher Education (THE) Ranking.
However, the findings differ somewhat, showing a high
homogeneity of the contents of mission statements
across regions. The terms “research,” “education,” and
“knowledge,” for example, are always central to university
mission statements in this sample.
Building on the argument of cultural rationalization in
world society theory and the role of local institutions in
the context of glocalization (Mizrahi-Shtelman & Drori,
2022; Drori et al., 2013; Höllerer et al., 2017), we seek to
reconcile the contradictions found in previous research
on
the
content
of
universities’
mission
statements
(Bayrak, 2020; Cortés-S�anchez, 2018). We propose that the
F I G U R E 2
Two-dimensional projections of topic distances and proportions of prevalence in our corpus.
PUBLIC ADMINISTRATION REVIEW
1197


## Page 12

interplay between global models and local specificities, as
characterized
by
glocalization,
can
provide
a
more
nuanced understanding of these dynamics. Therefore, our
approach aligns well with world society theory’s emphasis
on how global models are locally adapted and reinter-
preted (Meyer, 2010; Meyer & Bromley, 2013) and reflects
recent insights into the influence of glocalization on orga-
nizational identity (Mizrahi-Shtelman & Drori, 2021). Based
on this line of argument, we assume the following:
Hypothesis 1. The degree of cultural rationalization of
the country in which a university is located
affects the content of the university mission
statement.
Institutional founding conditions
In recent decades, imprinting theory has received signifi-
cant attention in organizational research (Marquis &
Tilcsik, 2013; Simsek et al., 2015) and has more recently
also found increasing recognition in public administration
studies (Oertel, 2018). Imprinting theory emphasizes the
lasting influence of an organization’s institutional found-
ing conditions on its structures and practices. This
imprinting persists over time through processes of institu-
tionalization and structural inertia that reinforce and sta-
bilize the initial conditions (Stinchcombe, 1965).
This theoretical framework complements the spatial
and cultural dimensions that can influence the global dif-
fusion
of
structures
and
practices
in
organizations
highlighted in world society theory (Boxenbaum, 2006;
Drori et al., 2014a, 2014b; Goldenstein et al., 2023).
Imprinting theory adds a temporal layer to these spatial
and cultural effects, arguing that the prevailing institu-
tional conditions at the time of an organization’s found-
ing have a long-lasting impact (Stinchcombe, 1965). This
argument is supported by a large number of empirical
studies in which researchers have explored various types
of influence of imprinting on organizations (for an over-
view, see Simsek et al., 2015). Moreover, imprinting theory
has recently been applied to the domain of higher educa-
tion (Geschwind & Broström, 2022; Oertel, 2018; Oertel &
Söll, 2017; Schulz et al., 2023; Zapp et al., 2021).
Oertel and Söll (2017), for example, found in their
study on mission statements in German universities that
imprinting influences the content of mission statements
regarding a service logic or a more traditional orientation.
More specifically, they show that universities from earlier
founding phases tend to use contents that correspond to
a Humboldtian idea of the university, whereas universities
from more recent founding phases are more likely to use
contents that reflect a more market-oriented logic. Buck-
ner and Zapp (2021), as another example, distinguish
between three founding periods (prior to the year 1945,
the time period 1946–1989, and after 1989) and show
that public universities founded in later periods are more
likely to offer business degree programs. They interpret
this finding as an imprinting effect; that is, universities
from later founding phases tend to be more compliant
with a market-oriented understanding of universities,
which makes them more likely to offer business degrees
compared to universities from earlier founding periods.
However, despite such studies on imprinting effects in
universities, in comparison to organization and manage-
ment research, imprinting theory has received less atten-
tion
in
research
on
universities.
This
is
surprising,
considering the high importance of history for universities
and their structure (Kosmützky & Krücken, 2015). More-
over, although the university as an institution has been
characterized by a high degree of persistence and conti-
nuity over the last thousand years (Drori et al., 2016), clear
founding phases can be identified. Medieval universities
and the predominant importance of religion strongly
influenced the initial university model. This university
model continued to evolve during the 19th century, with
an increasing focus on research activities in addition to
teaching. The combination of research and teaching in
the sense of a Humboldtian understanding of the univer-
sity (Nybom, 2003) became widespread worldwide—
including in the United States—at the beginning of the
20th century (Flexner 1930; Flexner & Kerr, 2021). After
the Second World War, and in view of the mass education
efforts in industrialized countries (Buckner & Zapp, 2021),
a new and more entrepreneurial understanding of univer-
sities increasingly developed globally. In this understand-
ing, universities are centrally responsible not only for
teaching and research but also innovation and engagement
in the context of theory, and practice transfer has become
increasingly important (Drori et al., 2016). Some researchers
consider the end of the Cold War in 1990 another relevant
founding phase in the context of university development
(Buckner & Zapp, 2021). In this regard, Buckner and Zapp
(2021) argue that after 1990, a new interest in expanding
access to higher education in relation to rapidly changing
labor markets emerged, which also changed the institution
of the university. Finally, the Bologna reforms greatly
affected European universities (Heinze & Knill, 2008) as they
represented an attempt to increase homogeneity and sub-
sequently forced universities to consider ways to distinguish
themselves from each other.
Imprinting theory adds a temporal layer to our under-
standing of the diversity in university mission statements.
While glocalization accounts for local cultural variations,
imprinting theory focuses on the long-lasting impact of
an institution’s founding conditions. This allows us to bet-
ter comprehend why mission statements, despite being
globally diffused practices, can differ significantly at the
organizational level. Following this line of argument, we
hypothesize the following:
Hypothesis 2. A university’s institutional founding condi-
tions
influence
the
content
of
its
mission
statement.
1198
UNIVERSITY MISSION STATEMENTS


## Page 13

Institutional control
In addition to the aforementioned factors, institutional con-
trol remains a pivotal determinant for the content of mission
statements. This is substantiated by a body of literature that
underscores the role of institutional control in shaping uni-
versity practices and structures, arguing that private higher-
education institutions overall reflect a stronger market orien-
tation compared to public institutions (Buckner, 2017;
Ferreira & Hill, 2008; Schulz et al., 2023), which also affects
mission statements (Oertel & Söll, 2017).
For instance, drawing on the insights of Buckner and
Zapp
(2021),
it
becomes
evident
that
institutional
logics—that is, the set of cultural norms, beliefs, and prac-
tices that guide how individuals and organizations inter-
act with and make sense of their environment—play a
pivotal role in shaping universities’ missions and societal
functions. They show that private universities are gener-
ally more aligned with a market-oriented institutional
logic, making them more likely to offer business-related
degrees. In contrast, public universities often operate
under different institutional logics, such as those that pri-
oritize state or national objectives, which may influence
their academic offerings differently. In line with institu-
tional theory, Schulz et al. (2023) provide empirical evi-
dence suggesting that private universities in Germany are
more predisposed to incorporate MBA programs into
their academic offerings. Similarly, Fay and Zavattaro
(2016) examine the phenomenon of branding in higher
education, focusing particularly on research-intensive
institutions in the United States. Their study shows that a
significant portion of these higher-education institutions
have implemented branding initiatives since 2006. These
branding strategies are heavily influenced by institutional
control. Public universities, which face a different set of
isomorphic pressures, are less likely to introduce branding
initiatives aimed at market differentiation than their pri-
vate counterparts. This trend underscores the nuanced
ways in which institutional control and logic manifest
themselves in various aspects of university management,
including mission statements. Finally, and with respect to
the content of mission statements, Morphew and Hartley
(2006) identify in their qualitative study discernible differ-
ences between private and public universities in the
United States, both in terms of content and linguistic
expression. Public universities predominantly emphasize
their commitment to public service, thereby reflecting the
concerns of policy makers and public funding agencies.
Conversely, private universities often portray themselves
as elite institutions focused on cultivating future leaders,
thereby aligning with a different set of stakeholder expec-
tations that include value proposition and performance.
While some research suggests that public and private
universities are similarly oriented toward a market logic
(Judson et al., 2006), it is important to consider the broader
context of institutional control within the rapidly evolving
higher education landscape (Fay & Zavattaro, 2016). In
Europe, a continent traditionally dominated by public higher
education, the private sector has been growing, particularly
in post-Communist countries that have experienced signifi-
cant privatization since the 1990s (Levy, 2012, 2018). Even in
Western European countries such as Austria, the number of
accredited private universities is approaching that of public
universities, with 22 public universities and 17 accredited
private universities in 2022 (BMBWF, 2022). This observation
is consistent with broader trends in higher education; pri-
vate institutions are not only increasing in number but also
in their share of student enrollment globally (Buckner, 2017;
Levy, 2018).
Given the global marketization of higher education,
enhanced by policy changes such as the Bologna
reforms in Europe, the role of institutional control in
shaping higher-education practices is likely to become
even more pronounced. This marketization exerts iso-
morphic pressures on both public and private institu-
tions.
However,
the
institutional
logic
underlying
decisions with respect to adoption of practices and
their content may differ because public and private uni-
versities fulfill different missions and societal roles (Fay
& Zavattaro, 2016).
Therefore, while acknowledging the potential for
convergence between the practices and structures of
private and public universities (Judson et al., 2006), our
study aligns with the strand of literature that argues
that broader, global trends in higher education and the
various institutional logics at play make institutional
control an increasingly relevant factor in understanding
the practices and orientations of public and private uni-
versities (Buckner & Zapp, 2021; Fay & Zavattaro, 2016).
Following
the
arguments
that
private
universities
become increasingly relevant in the higher-education
landscape, that institutional control is highly important
for the structure and implementation of practices in
universities, and that private universities follow more of
a market orientation, we assume that the contents of
mission statements in private universities differ from
the contents in public universities. Our hypothesis
reads as follows:
Hypothesis 3. Institutional control influences the content
of a university’s mission statement.
Variables and methods
Dependent variables: Our dependent variables were the
prevalence of each of the six topics, that is, the proportion
of a specific topic occurring in a mission statement.
Independent variables: In line with the theoretical
framework posited by Bromley and Meyer (2015) and
Meyer and Bromley (2013), we conceptualize cultural
rationalization as a construct influenced by three key
dimensions: scientization, individual rights and capacities,
and education. Our operationalization strategy draws
PUBLIC ADMINISTRATION REVIEW
1199


## Page 14

inspiration from Bromley and Sharkey (2017) and Golden-
stein et al. (2023). For 2019, we quantify scientization
using data on the number of published scientific articles
from each country from the World Bank. Individual rights
and capacities are assessed via the Personal Freedom
Index from the Cato Institute, and the significance of edu-
cation is gauged through the United Nations Education
Index. Each of these indicators is based on the country
level of the university and standardized to a range from 0
to 1. We then aggregate these standardized values to
construct a composite index of cultural rationalization.
Specifically, the index is calculated as the mean of the
normalized values for the three dimensions. This compos-
ite measure enables us to capture the multidimensional
nature of cultural rationalization within our analytical
framework. The variable “imprinting” is delineated by the
university’s founding year and is segmented into four
founding phases, as informed by the temporal demarca-
tions used by Buckner and Zapp (2021). Universities are
categorized as founded prior to 1945, between 1945 and
1990, between 1991 and 1999, or post-1999. This classifi-
cation situates each university within a distinct historical
phase, such as the traditional era of European higher edu-
cation (pre-1945) or the period following the initiation of
the Bologna reforms (post-1999). Finally, institutional con-
trol indicates whether a university is private or public.
Control variables: We included multiple control vari-
ables. First, university reputation has proven to be highly
relevant in the context of university mission statements
(Oertel & Söll, 2017). We included the variable “ranking”
to represent a university’s rank in the THE ranking, which
is frequently applied in studies on university mission
statements (Bayrak, 2020). In our sample of 413 European
universities, 244 are listed. Under the assumption that
universities with good reputations and those aspiring to
higher ranks will report to the ranking, unranked universi-
ties are assigned the last position to make the variable
utilizable in regression. Second, founding institutional
conditions are distinct from the age of an organization;
unlike age, they do not rely on linear accounts. To
account for age effects, we included universities’ ages as
a continuous measure. Third, the size of a university
serves as a proxy for its resources and capabilities (Schulz
et al., 2023). We operationalized university size as the
number of enrolled students for programs with Interna-
tional Standard Classification of Education (ISCED) levels 5
to 7. Fourth, density has been shown to be highly rele-
vant for universities’ structures and practices (Schulz et
al., 2023). We measure density as the number of universi-
ties located within 50 kilometers of a focal university.
Fifth, a region’s wealth (average GDP) may also influence
a university’s mission, as universities often address the
social aspects of their environment. We determined the
average GDP at the smallest level of regional entities pub-
lished by the European Statistical Office.
To test our hypotheses, we used linear regression
models with composition to account for estimation
uncertainty in the dependent variables (topic prevalence).
This involves drawing a set of topic proportions from the
variational posterior, computing the regression coefficients,
and repeating the process. We then averaged all batches of
coefficients to get the aggregated model coefficients
(Roberts et al., 2019). Because we noticed heteroskedasticity
in the residuals of some models, we calculated HC3 robust
standard errors (Long & Ervin, 2000). Before fitting the
regression models, we reviewed possible issues of multicolli-
nearity using the variance inflation factor (VIF). Given that
the maximum VIF was 6.0, multicollinearity was not an issue
of concern (Greene, 2018).
In
addition,
recent
literature
also
recommends
regression models other than linear regression for
dependent variables of topic proportions—although
linear regression is often used in the context of regres-
sions based on topic modeling due to its high robust-
ness (Schulze et al., 2024). A central suggestion here is
beta regression, which can handle proportions better
than linear regression. Therefore, in addition to a linear
regression with composition, as recommended by Rob-
erts, Stewart, and Airoldi (2016), we also estimated a
beta regression (Schulze et al., 2024) to test the robust-
ness of our findings (see Appendix Table D1). To further
rule out problems with unobserved heterogeneity, we
included random effects in this beta regression. How-
ever, we only found minor differences in the results.
Given the similarity in results, and to reduce complexity
and increase the interpretability and comparability of
our findings, we decided to keep the linear regression
as an established method in the context of CTM
(Chandelier et al., 2018; Farrell, 2016; Kraus et al., 2023;
Moschella & Pinto, 2019; Schmiedel et al., 2019) but
offer the beta regression as a robustness check.
Results
Descriptive statistics and correlations for all variables are pro-
vided in Table 4. For each variable, the mean, median, stan-
dard deviation (SD), minimum value (Min), and maximum
value (Max) are given to provide a comprehensive overview
of its distribution. Looking at the findings in Table 4, some
interesting results emerge. The cultural rationalization index
has a mean of 0.57 and a standard deviation of 0.23, indicat-
ing the variability of cultural rationalization among universi-
ties in various countries in our sample. The institutional
control variables show that 85% of the universities are public,
while 15% are private. In addition, the foundation phase vari-
ables show that the majority of universities (43%) were
founded before 1945, 32% were founded between 1945 and
1990, 13% between 1990 and 1999, and 12% after 1999. The
average THE rank is 1246.31, although there are considerable
differences between the individual universities, as the high
standard deviation shows. The differences are also evident in
other variables, such as age and number of students, reflect-
ing the diversity of universities in our sample.
1200
UNIVERSITY MISSION STATEMENTS


## Page 15

Table 5 provides the results of the regression analysis,
illustrating the estimated effects of the covariates on the
prevalence of various topics in university mission state-
ments. The table includes the coefficients and robust stan-
dard errors for each covariate, indicating the direction and
strength of their impact on the identified topics. The covari-
ates considered in the analysis include the cultural rationali-
zation
index,
institutional
control
(public
vs.
private),
founding phases, ranking, log-transformed age, density, log-
transformed average GDP, and log-transformed number of
students. The reference categories for the analysis are uni-
versities founded before 1945 and public universities.
With respect to Hypothesis 1, our findings indicate
that elevated levels of cultural rationalization negatively
affect the inclusion of the topics “Research and Knowl-
edge Transfer,” “Academic Excellence,” “Cultural and
Community Values,” and “Profession and Performance”
in university mission statements. In contrast, our results
show a positive and significant effect of cultural rationali-
zation on the likelihood of including the topics “Globali-
zation and World Society” and “Functional Core.” These
results are in line with the general arguments of world
society theory. Universities in countries with higher levels
of cultural rationalization may align with global norms
and discourses to a greater degree, emphasizing topics
such as “Globalization and World Society” or “Functional
Core” that align with standardized, global educational
models. These global pressures for legitimacy in a com-
petitive academic landscape may outweigh the influence
of local traditions and values. This leads to a diminished
focus on topics such as “Research and Knowledge
Transfer,” “Academic Excellence,” “Cultural and Commu-
nity Values,” and “Profession and Performance.” In this
context, the negative effect of “Academic Excellence”
may initially appear counterintuitive but can be contextu-
alized in the global proliferation of educational models. In
highly rationalized societies, the topic of “Academic Excel-
lence” may be so deeply ingrained that it becomes an
implicit expectation rather than an explicitly stated mis-
sion
objective.
Regarding
“Cultural
and
Community
Values,” the focus in globally rationalized settings often
shifts toward universally accepted norms, such as scienti-
zation and individual rights, potentially marginalizing
local cultural and community values. This is consistent
with world society theory, which posits that global norms
can occasionally eclipse local traditions. In summary, our
findings support Hypothesis 1.
Hypothesis 2 is focused on the influence of organiza-
tional imprinting on the prevalence of specific topics in
university mission statements. While we also observe sup-
port for this hypothesis, the statistical significance is rela-
tively weak and does not encompass all topics under
consideration.
The
results
indicate
that
universities
founded after 1945 are significantly less likely to empha-
size the topic of “Globalization and World Society” in
their mission statements. Conversely, these universities
are more likely to highlight the “Functional Core” theme
T A B L E 4
Descriptive statistics of independent numeric variables.
Variables
Mean
Median
SD
Min
Max
(1)
(2)
(3)
(4)
(5)
(6)
(7)
(8)
(9)
(10)
(11)
(1)
Cultural Rationalization Index
0.57
0.51
0.23
0.08
0.88
1.00
(2)
Private
0.15
0.00
0.35
0.00
1.00
�0.05
1.00
(3)
Founding phase before 1945
0.43
0.00
0.50
0.00
1.00
0.24
�0.29
1.00
(4)
Founding phase 1945–1990
0.32
0.00
0.47
0.00
1.00
�0.11
�0.08
�0.60
1.00
(5)
Founding phase 1991–1999
0.13
0.00
0.33
0.00
1.00
�0.15
0.28
�0.33
�0.26
1.00
(6)
Founding phase after 1999
0.12
0.00
0.33
0.00
1.00
�0.05
0.26
�0.33
�0.26
�0.14
1.00
(7)
THE-Rank
1246.31
1201.00
795.25
1.00
2100.00
�0.30
0.35
�0.40
0.11
0.17
0.27
1.00
(8)
Age
128.00
70.00
163.70
8.00
934.00
0.14
�0.23
0.62
�0.31
�0.23
�0.25
�0.33
1.00
(9)
Density
4.36
2.00
5.54
0.00
23.00
0.05
0.05
0.21
�0.18
�0.04
�0.03
�0.05
0.09
1.00
(10)
AverageGDP
38124.80
17263.87
46551.05
1067.64
211672.67
�0.01
0.36
�0.04
�0.07
0.11
0.05
0.00
�0.06
0.31
1.00
(11)
Students
15954.23
12319.00
16194.78
108.00
145579.00
0.05
�0.26
0.28
�0.08
�0.12
�0.18
�0.42
0.34
�0.03
0.17
1.00
PUBLIC ADMINISTRATION REVIEW
1201


## Page 16

across all post-1945 founding cohorts. Reflecting these
results
based
on
imprinting
theory,
for
universities
founded after 1945, globalization may already be deeply
embedded in their organizational identity and opera-
tional frameworks. Consequently, they no longer see the
need to explicitly articulate this topic in their mission
statements. The concept of globalization might be an
implicit assumption or a foundational element for these
institutions, reflecting a post-war world where global
interconnectedness became a given rather than a goal to
be stated explicitly. This suggests that for universities
established after 1945, global orientation is rather intrinsic
to their existence and mission so that it becomes a back-
ground condition, allowing them to focus more on other
elements, such as the “Functional Core,” which aligns
with
their
strategic
and
operational
priorities.
The
increased focus on the “Functional Core” subsequently
can be explained by the rise of a more market-oriented
and entrepreneurial understanding of universities in the
post-war era, emphasizing efficiency, specialization, and
direct contributions to national economies.
Hypothesis 3 represents an investigation of the influence
of institutional control on the content of mission statements.
Our findings reveal nuanced effects that align with the
broader theoretical framework. The results indicate that pri-
vate universities are less likely to emphasize the “Research
and Knowledge Transfer” topic in their mission statements.
Conversely, private universities are more likely to focus on
“Cultural and Community Values.” These findings can be
understood in the context of institutional control and the
differing institutional logics that guide private versus public
universities. The negative association between private con-
trol and the emphasis on “Research and Knowledge Trans-
fer” may reflect the fact that many research-intensive,
technically oriented universities tend to be public and that
these universities show a particularly high focus of research
and knowledge transfer. In contrast, the positive effect of
private control on the inclusion of the topic “Cultural and
Community Values” in mission statements may occur
because private universities might emphasize their unique
identities and roles in society, possibly to differentiate them-
selves from public institutions and to appeal to a specific set
T A B L E 5
Estimated covariate effects on topic prevalence.
Variables
Model 1
Model 2
Model 3
Model 4
Model 5
Model 6
Research and
Knowledge Transfer
Academic
Excellence
Cultural and
Community Values
Globalization and
World Society
Functional
Core
Profession and
Performance
Intercept
0.2349 (0.1592)
0.0694
(0.0793)
0.1371 (0.1566)
0.8392 (0.2057)***
�0.4518
(0.1212)**
0.1698 (0.0905)
Cultural rationalization
Cultural
Rationalization
Index
�0.2358 (0.0343)***
�0.0629
(0.0214)†
�0.1971 (0.0375)***
0.4506 (0.0502)***
0.2351
(0.0326)***
�0.1894
(0.0265)***
Founding phase effect
Founding phase
1945–1990
0.0082 (0.0309)
�0.0042
(0.024)
�0.0089 (0.0327)
�0.0839 (0.0438)†
0.0703
(0.0229)*
0.0183 (0.0191)
Founding phase
1991–1999
0.02 (0.0441)
0.0145
(0.0355)
�0.0129 (0.0526)
�0.1453 (0.0639)*
0.0946
(0.0329)†
0.0287 (0.0272)
Founding phase
after 1999
�0.0204 (0.0506)
�0.0098
(0.0367)
0.0036 (0.0617)
�0.1758 (0.0702)*
0.1245
(0.0403)*
0.0768 (0.037)
Ownership
Private
�0.0981 (0.0235)**
�0.0227
(0.0193)
0.0891 (0.0433)*
0.0646 (0.0422)
0.0014
(0.0184)
�0.0333 (0.0196)
Control variables
THE-Rank
0 (0)
0 (0)
0 (0)
�0.0001 (0)**
0 (0)
0 (0)
log(Age)
�0.0029 (0.0189)
�0.0035
(0.0122)
0.0201 (0.018)
�0.085 (0.0253642)**
0.0558
(0.017)**
0.0102 (0.0104)
Density
�0.0037 (0.0011)*
�0.0009
(0.001)
0 (0.0013)
0.0068 (0.0023)*
�0.0036
(0.001)†
0.0014 (0.0011)
log(GDP
(NUTS3))
0.0155 (0.0084)
0.0067 (0.005)
�0.0034 (0.0098)
�0.0275 (0.0122)†
0.0077
(0.0067)
0.0011 (0.0058)
log(Students)
�0.0041 (0.0088)
�0.0002
(0.0052)
0.0061 (0.0101)
�0.007 (0.0111)
0.0083
(0.0061)
�0.003 (0.006)
Note: Robust standard errors in parentheses. Reference categories: Founding phase prior to 1945, Public Control.
†p < .10; *p < .05; **p < .01; ***p < .001.
1202
UNIVERSITY MISSION STATEMENTS


## Page 17

of stakeholders, including students and donors who value
community and cultural contributions.
Robustness checks
To assess the robustness of our findings, we conducted addi-
tional analyses. First, we considered the potential role of
accreditation in shaping the content of university mission
statements. It is plausible that accreditation status could exert
some influence on the themes emphasized in these state-
ments. Accredited universities are typically subject to guide-
lines and quality standards, which may encourage them to
highlight specific educational objectives, research commit-
ments, or community engagement activities. These guidelines
are often formulated by accrediting agencies operating
within broader institutional frameworks, which may be
aligned with market-oriented or state-serving logics. Conse-
quently, accreditation could inform what a university deems
significant enough to include in its mission statement.
Furthermore, the accreditation process usually entails a
degree of introspection and strategic planning, which could
potentially lead to a more nuanced and targeted mission
statement. In the context of the increasing marketization of
global higher education, accreditation might also function
as a competitive differentiator. Universities could opt to fea-
ture their accredited status in their mission statements as a
way to signal quality and credibility to various stakeholders,
including prospective students and faculty.
To investigate the potential role of accreditation on the
content of university mission statements, we utilized data
from the ETER database. This data included information on
whether universities are subject to external quality assur-
ance as per the European Quality Assurance Register for
Higher Education (EQAR). EQAR serves as a centralized
repository that lists quality assurance agencies responsible
for evaluating higher-education institutions in Europe in
accordance with the European Standards and Guidelines for
Quality Assurance. An evaluation by an EQAR-registered
agency serves as a robust proxy for a university’s accredita-
tion status, strongly suggesting that the institution meets
the high educational standards set forth by European edu-
cational authorities. We incorporated this variable into our
regression models to assess the robustness of our primary
findings. The inclusion of this variable resulted in marginal
changes in effect sizes but changed neither the direction
nor the significance levels of effects. However, it should be
noted that this variable was not available for all universities
in our sample and, despite extensive efforts, could not be
collected
subsequently.
Consequently,
we
decided
to
exclude this variable from the main regression models.6
Second, resource dependence theory posits that organi-
zations are contingent on their external environment for
critical resources (Pfeffer & Salancik, 2006). In the context of
universities, these resources can manifest as government
funding, third-party collaborations, or tuition fees. The allo-
cation and prioritization of these resources can influence
universities’ strategic orientation, which is often reflected in
the content of their mission statements. To further validate
the robustness of our findings, we conducted additional
analyses incorporating financial metrics of universities. Spe-
cifically, we included variables representing the total core
budget of the university, the total amount of third-party
funding, and potential revenues from student fees. These
variables were sourced from the ETER database and serve as
proxies for universities’ financial structure and resource
dependence. Upon inclusion of these financial variables, the
results remained robust, confirming the stability and validity
of our original findings. However, it is important to note that
the availability of these financial metrics was not universal
across all universities in our sample. The inclusion of these
additional variables led to a substantial reduction in sample
size. Given the risk of sample bias and the potential impact
on the generalizability of our findings, we decided to treat
these results as a robustness check rather than incorporat-
ing them into the main regression model.7
DISCUSSION
The long tradition of studying universities’ organization
(Cohen et al., 1972) has attracted increasing interest in public
administration research and organization studies in recent
decades (Bleiklie et al., 2015; Oertel, 2018; Paradeise &
Thoenig, 2013; Schulz et al., 2023). In line with this research,
the motivation for our study was twofold: First, the literature
lacks comprehensive conclusions about factors influencing
the content of university mission statements. Second,
although various methods have been applied in past research
on universities’ mission statements, topic-modeling algo-
rithms (particularly algorithms beyond LDA) have not gained
attention in this context, despite their ability to manage large
amounts of text. In our study, we use CTM to analyze 413
mission statements from all European universities located in
16 European countries. Our results show that cultural rational-
ization of the universities’ national context, founding context,
and institutional control influence the content of European
universities’ mission statements. These findings and the use
of CTM in this context have far-reaching contributions to fur-
ther research, which we will discuss below.
Contributions to research at the crossroads
of public administration research,
organization theory, and research on higher
education
As a result of decades of growing rationalization pressure,
universities have increasingly changed, and they are now
considered modern organizations (Meyer & Schofer, 2007;
Meyer & Bromley, 2013; Oliver-Lumerman & Drori, 2021;
Ramirez, 2020; Ramirez & Christensen, 2013). In this
respect, it is not surprising that the study of universities
has become a relevant topic in public administration
PUBLIC ADMINISTRATION REVIEW
1203


## Page 18

research (Crow et al., 2020; Oertel, 2018; Pearce et al.,
2018; Rabovsky, 2014) and that studies on universities fre-
quently refer to organizational theories to explain how
certain structures and practices diffuse across universities
(Buckner & Zapp, 2021; Philippczyck et al., 2024; Seeber et
al., 2019; Zapp et al., 2021).
At these crossroads of research, studies show that uni-
versities worldwide are increasingly adopting mission
statements (Bayrak, 2020; Cortés-S�anchez, 2018). How-
ever, although a growing homogenization trend in the
higher-education sector can be observed worldwide, with
the American research university serving, in some ways,
as a kind of best practice (Ramirez, 2020; Ramirez & Tiplic,
2014), universities around the world still differ in many
respects in their structures and practices. These differ-
ences are particularly visible regarding how universities
present themselves to their environment (Delmestri et al.,
2015; Drori et al., 2016). We contribute to this research
and
argue
that
idiosyncrasies
relate
to
university
characteristics—that is, contextual and organizational dif-
ferences among universities cause differences in their
mission statements. The functions of university mission
statements, such as signaling organizational identity,
establishing strategic priorities, and enhancing legitimacy,
align closely with those of value and mission statements
in other public organizations (Desmidt, 2016; Duncan et
al., 1994; Hyndman & Eden, 2001; Ossewaarde et al., 2008;
Weiherl & Masal, 2016). Therefore, the insights from our
study can be applied to public administration research
and managers by providing a framework for understand-
ing
factors
that
influence
the
content
of
mission
statements.
The central focus of our study was to offer a compre-
hensive overview of the contents of mission statements
and to better understand factors that explain differences
in content. Such a comprehensive overview is highly
important because it allows a better understanding of
certain interrelationships, as illustrated by the example
of our findings on institutional control. Looking at our
findings in relation to private universities, the results
may at first seem counterintuitive. One might wonder
why private universities are less likely to emphasize
knowledge transfer and research in their mission state-
ments, given that they typically have strong ties to
industry. Why, in contrast, do they emphasize cultural
and community values more than public universities do?
These counterintuitive findings may be related to the
fact that the underlying intuition is biased. Concerning
the influence of institutional control, a few very success-
ful private universities come to mind, but these by no
means represent all the private universities in Europe.
While it may be tempting to generalize based on a few
high-profile
private
universities,
our
comprehensive
analysis of 413 universities in 16 European countries
offers an in-depth understanding.
Our data show that previous findings and assump-
tions shift when considering a broad range of private
universities, including smaller and less prestigious institu-
tions. Social responsibility and community values are
becoming a central theme in their mission statements,
and the articulation of social values is gaining importance.
Issues such as knowledge transfer and research, on the
other hand, seem to be less emphasized. These findings
support arguments against the previous image of private
universities, which prioritize income-generating activities
and global competitiveness over local cultural and social
engagement due to a stronger market orientation com-
pared to public universities. At the same time, cultural
and community contributions might be particularly rele-
vant for smaller private universities, as they often rely
heavily on donors who highly value such engagements—
or the signaling of such engagements through the
emphasis of these topics in a mission statement. Conse-
quently, with our findings showing how a university’s cul-
tural rationalization, founding phase, and institutional
control influence the content of mission statements, we
contribute to a better understanding of what constitutes
the content of universities’ mission statements (Bayrak,
2020; Cortés-S�anchez, 2018; Seeber et al., 2019).
Considering the overlap in their most frequent words
in the observed mission statements, our study also con-
tributes to the arguments of world society theory more
generally (Meyer et al., 1997) by confirming an increasing
homogenization of higher-education institutions world-
wide (Ramirez, 2020; Ramirez & Tiplic, 2014). Furthermore,
the global sphere and an international outlook seem to
be an important part of European universities’ mission
statements because these issues constitute one of our
revealed themes (Mizrahi-Shtelman & Drori, 2021). These
findings indicate the continuous internationalization of
higher education (Zapp & Ramirez, 2019). At the same
time, our study shows that European universities’ mission
statements, beyond this layer of commonalities, differ in
how they represent themselves to their audiences. Specif-
ically, universities with similar features show considerable
commonalities in their mission statements while differing
from others. By observing the interplay between the
international homogenization process in academia and
contingent factors, we provide insight into determinants
that explain how universities respond to global homoge-
nizing pressures in terms of convergence versus diver-
gence (Ramirez, 2020; Ramirez & Tiplic, 2014). With regard
to theory development, we contribute to the research on
world society theory and the debate in the context of glo-
calization by considering horizontal, vertical, and tempo-
rary forces that influence the adaptation of practices in
organizations (Drori et al., 2014a,b). We model the hori-
zontal level of glocalization through the influence of cul-
tural rationalization of the university’s national context.
We account for institutional control in the vertical dimen-
sion, to some extent, as we can thereby capture differ-
ences in orientation with respect to institutional logics
and governance, though certainly very coarsely grained
and as a proxy. Additionally, we capture the temporal
1204
UNIVERSITY MISSION STATEMENTS


## Page 19

dimension of glocalization by including imprinting theory,
showing that a university’s institutional founding context
has
a
lasting
impact
on
the
content
of
mission
statements—that is, mission statements today differ in
content across founding phases. In doing so, we provide
an initial strategy for integrating these three dimensions
of glocalization in an empirical approach, which contrib-
utes to a better, more complete understanding of the
causal relationships among these dimensions as well as
how these dimensions influence the adaptation of prac-
tices in organizations (Boxenbaum, 2006; Drori et al.,
2014a,b; Goldenstein et al., 2023; Höllerer et al., 2017).
Consistent with this contribution, our study also
relates to research on diffusion theory in public adminis-
tration (Berry & Berry, 1990; Fay et al., 2022). Although our
primary theoretical approach is not diffusion theory, our
findings are related to the broader literature on policy dif-
fusion in public administration. Similarly to how policies
and innovations diffuse through various mechanisms in
government administrations (Berry & Berry, 1990), our
study suggests that university mission statements are
influenced by both internal factors and external pressures.
This is consistent with the notion that organizations,
including universities, do not operate in isolation but are
influenced by a complex interplay of internal characteris-
tics and external institutional environments. Furthermore,
Fay et al. (2022) emphasize the concept of vertical–
diagonal diffusion, in which policies affect lower-level
governance systems beyond direct hierarchical lines.
Applying this perspective, our findings suggest that uni-
versities’ mission statements may reflect a broader policy
environment and organizational domains that are influ-
enced by both higher-level educational policies and peer
institutions. Linking our findings to this theoretical per-
spective provides an additional factor explaining how uni-
versities, like other public organizations, navigate and
adapt in the face of a complex array of influences.
Finally, our study’s findings have significant implica-
tions for framing theory (Goffman, 1974), particularly
within the domains of organization studies and public
administration research. Framing theory, which posits
that the presentation of issues can influence perceptions
and actions (Benford & Snow, 2000; Entman, 1993), reso-
nates in our analysis of university mission statements. We
observe that university mission statements are affected
by the cultural rationalization of the country where they
are located, founding context, and institutional control.
We propose that these effects are due to institutional set-
tings, but universities may also frame their mission state-
ments strategically, tailoring their mission statements
based on institutional settings (Mizrahi-Shtelman & Drori,
2021). This aligns with the theoretical underpinnings of
framing theory, which emphasizes the strategic use of
language to construct reality and influence stakeholder
perceptions (Goffman, 1974). For instance, our findings
on the emphasis of public universities regarding the topic
“Cultural and Community Values” can be interpreted as a
framing
strategy
aimed at
organizational legitimacy
(Suchman, 1995). Moreover, the use of CTM in our study
adds a methodological nuance to framing analysis, which
could be particularly beneficial for public administration
research focusing on, for example, discourse analysis
(Vogel, 2012).
Methodological contributions
In addition to our theoretical contributions, our study also
has clear methodological contributions. Our literature
review of empirical studies on universities’ mission state-
ments shows 30 studies published since 1995. These stud-
ies reveal a high degree of methodological pluralism with
a surprisingly high proportion of quantitative empirical
approaches. At the same time, existing methodological
procedures for quantitative text analysis remain largely
unaddressed (Bayrak, 2020; Cortés-S�anchez, 2018), and
researchers have yet to apply CTM. However, CTM allows
new methods of investigation regarding content analysis
of universities’ mission statements. First, topic modeling
“enables the identification of important themes that
human readers are unable to discern” (Hannigan et al.,
2019, p. 590). This makes topic modeling especially useful
for larger amounts of text (Bohn & Rogge, 2022) in which
correlations and possible qualitative codes are not always
easy to recognize. Because language is central to docu-
ments’ cognitive content (Whorf, 2012), and actors (such
as universities) use certain vocabulary to represent similar
and the same content (Loewenstein et al., 2012), CTM can
represent new developments in the context of universi-
ties’ strategic positioning through the content of mission
statements. Second, CTM is particularly useful when find-
ings are to be used for further quantitative analyses—that
is, when topics discovered should be linked to document
metadata. In our study, it was possible to show not only
specific topics of mission statements but also to point out
which variables influence the likelihood of a particular
topic’s occurrence. In addition, although interpretation of
topics and findings might be as prone to subjectivity as
every manual coding approach, and although data collec-
tion and preprocessing are subject to individual decisions,
topic estimation and the subsequent analysis follow strict
algorithmic rules and are, therefore, accountable and eas-
ily reproducible (Roberts, Stewart, & Tingley, 2016).
Limitations and future research
Similar to most empirical research, the present study has
several limitations that we would like to highlight. First, to
ensure comparability in a cross-national setting, we
focused exclusively on mission statements that were
explicitly labeled as such and were available on English-
language university websites. This methodological choice
adheres to a narrow definition of what constitutes a
PUBLIC ADMINISTRATION REVIEW
1205


## Page 20

mission statement. However, it is worth noting that uni-
versities may opt to publish their mission statements in
local languages (Mizrahi-Shtelman & Drori, 2021, 2022) or
articulate their long-term goals and values in alternative
documents that are not formally labeled as mission state-
ments. However, this limitation also unveils several
intriguing avenues for future research. For instance,
researchers could explore how the content of mission
statements varies based on the language in which they
are published. Language, as a cultural artifact, may influ-
ence the framing and emphasis of various topics, thereby
offering a nuanced understanding of organizational iden-
tity and strategy. Additionally, researchers could consider
regional variations within countries to examine how local-
ized cultural, economic, or educational factors shape mis-
sion statements’ contents. Such an approach would
contribute to a more comprehensive and contextually
rich understanding of how universities articulate their
missions, thereby extending the theoretical and empirical
horizons of our initial study.
Second, while the cross-sectional design of our study
presents a limitation in capturing the temporal dynamics
of mission statements and the enduring influence of
organizational imprints, it simultaneously opens a promis-
ing avenue for future research. Specifically, the question
of how and to what extent organizational imprints erode
or evolve over time offers a valuable basis for longitudinal
studies. Marquis and Tilcsik (2013) further elaborate on
the complexities of imprinting, suggesting that imprints
are not merely static but can be subject to various contex-
tual influences over time. Therefore, future research could
benefit from using a longitudinal design to explore these
temporal
aspects,
thereby
contributing
to
a
more
nuanced understanding of isomorphic forces and the
durability or malleability of organizational imprints. This
approach would not only extend the discourse on
imprinting but also provide empirical insights into the
evolving nature of mission statements in higher educa-
tion institutions. With such a longitudinal setting, it would
be possible—for example—to better understand how
mission statements evolve and what factors influence this
evolution.
Third, a potential limitation of our study is the undi-
rected nature of our hypotheses, which are focused on
the influence of cultural orientation, imprinting, and insti-
tutional control on the content of university mission
statements. While this approach allows for a comprehen-
sive exploration of these key factors, it may not provide
the granularity needed to understand their directional
impact on particular topics of mission statements. How-
ever, we view this as a strategic choice in an emerging
area of research, laying the groundwork for a founda-
tional understanding of the complex interplay between
these factors. We intend for this study to serve as an ini-
tial step toward a more nuanced understanding of how
cultural orientation, imprinting, and institutional control
shape mission statements. This undirected approach
opens the door for future research to formulate more
directed hypotheses, thereby contributing to a more
detailed understanding of these factors and how they
shape the content of mission statements. Subsequent
studies could leverage our foundational work to explore
each factor’s specific directional influences on particular
topics included in mission statements.
The final limitation of our study is that it does not
directly address questions about the purpose and impact
of mission statements. For example, our data do not allow
us to draw conclusions about whether university mem-
bers are aware of their respective mission statements, the
degree to which these mission statements form the basis
of universities’ organizational identities, and whether uni-
versities follow their mission statements or whether these
mission statements are, to some extent, decoupled arti-
facts. These would all be interesting and relevant ques-
tions, but they are beyond the scope of our current study
and the possibilities that our data allow. Therefore, future
studies should include such questions, perhaps using
methods like that of Davies and Glaister (1996), which
involves interviewing decision-makers about the adoption
and intended goals of the mission statements. In this
way, future research could provide a better understand-
ing of the impact of mission statements on academic
institutions as well as their internal relevance.
CONCLUSION
We focused on the complex interplay of factors that influ-
ence the content of university mission statements, partic-
ularly in the European context. By using CTM, we have
identified six distinct topics that are prevalent in these
statements. Furthermore, our findings indicate that the
prominence of these topics is significantly shaped by vari-
ables such as the cultural rationalization of universities’
national context, the universities’ institutional founding
context, and institutional control. These results contribute
to the theoretical understanding of how public organiza-
tions adapt to or resist global trends, and our methodo-
logical approach offers a tool for large-scale textual
analysis in public administration, which can be particu-
larly useful for analyzing policy documents or organiza-
tional statements at scale. However, we view our study as
a first step in this direction, as mission statements from
public organizations are likely to differ depending on the
field of activity. Therefore, a larger sample of public orga-
nizations outside the higher-education field could be
examined in future research to further validate our meth-
odological approach and theoretical arguments. More-
over, the application of CTM can extend beyond mission
statements to other forms of organizational text, offering
a robust method for understanding the strategic behavior
of public organizations.
From a practical standpoint, our study provides a
framework
for
understanding
universities’
strategic
1206
UNIVERSITY MISSION STATEMENTS


## Page 21

positioning through their mission statements. Decision-
makers in higher education can utilize this framework for
benchmarking and strategic planning. Moreover, our
study can guide universities in their adaptation to or resis-
tance against global trends. Understanding the factors
that influence mission statement content can help univer-
sities make informed decisions about how to position
themselves in a global educational landscape.
In summary, our study serves as a theoretical and
practical resource for understanding the factors that
influence the content of university mission statements. It
provides a nuanced view of how universities can strate-
gically position themselves in response to various insti-
tutional and contextual pressures. While our study offers
a comprehensive analysis of the current landscape, it
also opens avenues for future research, particularly in
exploring how these mission statements evolve over
time and how they impact various stakeholder percep-
tions and behaviors. Moreover, to discover potential var-
iations in the driving forces behind university mission
statements,
researchers
should
conduct
detailed
country-specific analyses to better understand between-
and within-country differences. Such analyses could
reveal how governance structures, cultural contexts, and
educational policies influence the formulation and con-
tent of mission statements. By examining these aspects,
future studies can provide a more nuanced understand-
ing of the role and impact of mission statements in
higher-education institutions worldwide.
ENDNOTES
1 Note that while our initial study encompassed all 735 European univer-
sities from the listed countries, not every university had an available
mission statement in English. As language plays a significant role in
content articulation (Mizrahi-Shtelman & Drori, 2021), our analysis was
specifically centered on the English versions of mission statements.
This approach ensures a more consistent and comparable dataset,
allowing for a nuanced understanding of how European universities
present themselves to a global audience. However, since not all univer-
sities have mission statements, it seems reasonable to also analyze fac-
tors influencing the likelihood of a university adopting a mission
statement (for such an analysis, which is not the central focus of our
study, see Appendix Table A1.)
2 We focused primarily on studies in journals listed on the Web of
Science.
3 We selected countries from different geographic regions to ensure
diversity in our sample, as regional differences can influence institu-
tional characteristics. We then focused on the four largest economies
in each region to balance comprehensiveness with the practical limita-
tions of data availability.
4 We considered this a very important requirement for data collection.
Universities publish extensive documents on strategies like strategic
plans and development reports that could somehow be included in
our analysis. A narrow definition was important for us to ensure a high
degree of comparability with previous studies as well as an adequate
basis for future research. Strategic plans and documents are also com-
paratively short-term in nature and very focused on cyclical political
requirements, whereas mission statements are generally of a more
long-term and strategic nature. Additionally, we focused on English-
language mission statements to avoid discrepancies that might arise
from translation and to maintain consistency across the dataset
(Mizrahi-Shtelman & Drori, 2023). Moreover, while strategic plans vary
widely in format and scope, mission statements provide a more stan-
dardized and enduring reflection of institutional identity and strategic
intent.
5 To enable the application of our methodological procedure to similar
research questions in the context of public administration, our code,
along with descriptions of the central steps of the procedure, and the
data used in our study are available upon request.
6 See Appendix Table B1.
7 See Appendix Table C1.
REFERENCES
Aib, Iman, and Wasima Shehzad. 2023. “Defining Mission Statements in
Higher Education: Towards a Genre Perspective.” Higher Education
Quarterly 77(1): 138–157. https://doi.org/10.1111/hequ.12378.
Albalawi, Rania, Tet Hin Yeap, and Morad Benyoucef. 2020. “Using Topic
Modeling Methods for Short-Text Data: A Comparative Analysis.”
Frontiers in Artificial Intelligence 3: 42. Frontiers. https://doi.org/10.
3389/frai.2020.00042.
Alegre, Inés, Jasmina Berbegal-Mirabent, Adri�an Guerrero, and Marta
Mas-Machuca. 2018. “The Real Mission of the Mission Statement: A
Systematic Review of the Literature.” Journal of Management and
Organization 24(4): 456–473. https://doi.org/10.1017/jmo.2017.82.
Arias-Coello, Alicia, Jose Simon-Martin, and Jose Luis Gonzalo Sanchez-
Molero. 2020. “Mission Statements in Spanish Universities.” Studies
in
Higher
Education
45(2):
299–311.
https://doi.org/10.1080/
03075079.2018.1512569.
Bart Baetz, Christopher K. M. C. 1998. “The Relationship between Mission
Statements and Firm Performance: An Exploratory Study.” Journal
of Management Studies 35(6): 823–853. https://doi.org/10.1111/
1467-6486.00121.
Banks, George C., Haley M. Woznyj, Ryan S. Wesslen, and Roxanne L. Ross.
2018. “A Review of Best Practice Recommendations for Text Analysis
in R (and a User-Friendly App).” Journal of Business and Psychology 33:
445–459. https://doi.org/10.1007/s10869-017-9528-3.
Bayrak, Tuncay. 2020. “A Content Analysis of Top-Ranked Universities’
Mission Statements from Five Global Regions.” International Journal
of Educational Development 72: 102130. https://doi.org/10.1016/j.
ijedudev.2019.102130.
Benford, Robert D., and David A. Snow. 2000. “Framing Processes and
Social Movements: An Overview and Assessment.” Annual Review
of Sociology 26(1): 611–639. https://doi.org/10.1146/annurev.soc.26.
1.611.
Berghaeuser, Hendrik, and Michael Hoelscher. 2020. “Reinventing the
Third Mission of Higher Education in Germany: Political Frame-
works and Universities’ Reactions.” Tertiary Education and Manage-
ment 26(1): 57–76. https://doi.org/10.1007/s11233-019-09030-3.
Berry, Frances Stokes, and William D. Berry. 1990. “State Lottery Adop-
tions as Policy Innovations: An Event History Analysis.” American
Political Science Review 84(2): 395–415. https://doi.org/10.2307/
1963526.
Blei, David M., and John D. Lafferty. 2007. “A Correlated Topic Model of
Science.” The Annals of Applied Statistics 1(1): 17–35. https://doi.
org/10.1214/07-AOAS114.
Blei, David M., Andrew Y. Ng, and Michael I. Jordan. 2003. “Latent Dirich-
let Allocation.” Journal of Machine Learning Research 3(Jan): 993–
1022.
Bleiklie, Ivar, Jürgen Enders, and Benedetto Lepori. 2015. “Organizations
as Penetrated Hierarchies: Environmental Pressures and Control in
Professional Organizations.” Organization Studies 36(7): 873–896.
https://doi.org/10.1177/0170840615571960.
BMWBF.
2022.
Austrian
Federal
Ministry
of
Education,
Science
and Research https://www.bmbwf.gv.at/Themen/HS-Uni/Hochschul
system.html
Bohn, Stephan, and Timo Braun. 2021. “Field-Configuring Projects: How
Projects Shape the Public Reflection of Electric Mobility in
PUBLIC ADMINISTRATION REVIEW
1207


## Page 22

Germany.” International Journal of Project Management 39(6): 605–
619. https://doi.org/10.1016/j.ijproman.2021.04.006.
Bohn, Stephan, and Jan-Christoph Rogge. 2022. “The Framing of Green
Innovations—a Comparative Topic Modeling Study on the Public
Frames of the Electric Vehicle in Germany and UK.” Journal of
Cleaner Production 364: 132499. https://doi.org/10.1016/j.jclepro.
2022.132499.
Boxenbaum, Eva. 2006. “Lost in Translation: The Making of Danish Diver-
sity Management.” American Behavioral Scientist 49(7): 939–948.
https://doi.org/10.1177/0002764205285173.
Bozeman, Barry, and Jan Youtie. 2020. “Robotic Bureaucracy: Adminis-
trative Burden and Red Tape in University Research.” Public
Administration Review 80(1): 157–162. https://doi.org/10.1111/
puar.13105.
Breznik, Kristijan, and Kris M. Y. Law. 2019. “What Do Mission Statements
Reveal about the Values of Top Universities in the World?” Interna-
tional Journal of Organizational Analysis 27(5): 1362–75. https://doi.
org/10.1108/IJOA-08-2018-1522.
Bromley, Patricia, and John W. Meyer. 2015. Hyper-Organization: Global
Organizational Expansion. Oxford, UK: Oxford University Press.
https://doi.org/10.1093/acprof:oso/9780199689859.001.0001.
Bromley, Patricia, and Amanda Sharkey. 2017. “Casting Call: The Expand-
ing Nature of Actorhood in US Firms, 1960–2010.” Accounting,
Organizations and Society 59: 3–20. https://doi.org/10.1016/j.aos.
2017.06.001.
Bryson, John, and Bert George. 2020. “Strategic Management in Public
Administration.” In Oxford Research Encyclopedia: Politics 1–26.
Oxford,
UK:
Oxford
University
Press.
https://doi.org/10.1093/
acrefore/9780190228637.013.1396.
Buckner, Elizabeth. 2017. “The Worldwide Growth of Private Higher Edu-
cation: Cross-National Patterns of Higher Education Institution
Foundings by Sector.” Sociology of Education 90(4): 296–314.
https://doi.org/10.1177/0038040717739613.
Buckner, Elizabeth. 2022. “Embracing the Global: The Role of Ranking,
Research Mandate, and Sector in the Internationalisation of Higher
Education.” Compare: A Journal of Comparative and International
Education 52(2): 232–249. https://doi.org/10.1080/03057925.2020.
1753499.
Buckner, Elizabeth, and Mike Zapp. 2021. “Institutional Logics in the
Global Higher Education Landscape: Differences in Organizational
Characteristics by Sector and Founding Era.” Minerva 59: 27–51.
https://doi.org/10.1007/s11024-020-09416-3.
Bustos, Edgar O. 2021. “Organizational Reputation in the Public Adminis-
tration: A Systematic Literature Review.” Public Administration
Review 81(4): 731–751. https://doi.org/10.1111/puar.13363.
Chandelier, Marie, Agnès Steuckardt, Raphael Mathevet, Sascha Diwersy,
and Olivier Gimenez. 2018. “Content Analysis of Newspaper Cover-
age of Wolf Recolonization in France Using Structural Topic Model-
ing.” Biological Conservation 220: 254–261. https://doi.org/10.1016/
j.biocon.2018.01.029.
Christensen, Tom, S. Gabriela Gavrila, Liang Ma, and Francisco O.
Ramirez. 2020. “Reputation Management by Chinese Universities:
Primary Profile and Comparative Features.” Public Administration
98(4): 1027–43. https://doi.org/10.1111/padm.12679.
Christensen, Tom, and Åse Gornitzka. 2017. “Reputation Management in
Complex Environments—a Comparative Study of University Orga-
nizations.” Higher Education Policy 30: 123–140. https://doi.org/10.
1057/s41307-016-0010-z.
Christensen, Tom, Åse Gornitzka, and Francisco O. Ramirez. 2019. “Repu-
tation Management, Social Embeddedness, and Rationalization of
Universities.” In Universities as Agencies: Reputation and Professional-
ization, edited by Tom Christensen, Åse Gornitzka and Francisco O.
Ramirez, 3–39. Cham, Switzerland: Palgrave Macmillan.
Cohen, Michael D., James G. March, and Johan P. Olsen. 1972. “A Gar-
bage Can Model of Organizational Choice.” Administrative Science
Quarterly 17(1): 1–25. https://doi.org/10.2307/2392088.
Collins, James C., and Jerry I. Porras. 1996. “Building Your Company’s
Vision.” Harvard Business Review 74: 65–78.
Cortés-S�anchez, Juli�an D. 2018. “Mission statements of universities
worldwide: Text mining and visualization.” Intangible Capital 14(4):
584–603. https://doi.org/10.3926/ic.1258.
Connell, Ian, and Dariusz Galasi�nski. 1998. “Academic Mission State-
ments: An Exercise in Negotiation.” Discourse and Society 9(4): 457–
479. https://doi.org/10.1177/0957926598009004003.
Cox, Michael A. A., and Trevor F. Cox. 2008. “Multidimensional Scaling.” In
Handbook of Data Visualization, edited by C. Chen-houh, W. Härdle,
and A. Unwin, 315–347. Berlin/Heidelberg, Germany: Springer.
Crow, Michael M., Kyle Whitman, and Derrick M. Anderson. 2020.
“Rethinking Academic Entrepreneurship: University Governance
and the Emergence of the Academic Enterprise.” Public Administra-
tion Review 80(3): 511–15. https://doi.org/10.1111/puar.13069.
Csizmadia, Tibor, Jürgen Enders, and Don F. Westerheijden. 2008. “Qual-
ity Management in Hungarian Higher Education: Organisational
Responses to Governmental Policy.” Higher Education 56: 439–455.
https://doi.org/10.1007/s10734-007-9103-3.
Czarniawska, Barbara, and Rolf Wolff. 1998. “Constructing New Identities
in Established Organization Fields: Young Universities in Old
Europe.” International Studies of Management and Organization
28(3): 32–56. https://doi.org/10.1080/00208825.1998.11656739.
Davies, Stuart W., and Keith W. Glaister. 1996. “Spurs to Higher Things?
Mission Statements of UK Universities.” Higher Education Quarterly
50(4): 261–294. https://doi.org/10.1111/j.1468-2273.1996.tb01706.x.
De Boer, Harry F., Jürgen Enders, and Liudvika Leisyte. 2007. “Public Sec-
tor Reform in Dutch Higher Education: The Organizational Transfor-
mation of the University.” Public Administration 85(1): 27–46.
https://doi.org/10.1111/j.1467-9299.2007.00632.x.
Delgado-M�arquez, Blanca L., M. ´Angeles Escudero-Torres, and Nuria E.
Hurtado-Torres. 2013. “Being Highly Internationalised Strengthens
Your Reputation: An Empirical Investigation of Top Higher Educa-
tion Institutions.” Higher Education 66(5): 619–633. https://doi.org/
10.1007/s10734-013-9626-8.
Delmestri, Giuseppe, Achim Oberg, and Gili S. Drori. 2015. “The Unbear-
able Lightness of University Branding: Cross-National Patterns.”
International Studies of Management and Organization 45(2): 121–
136. https://doi.org/10.1080/00208825.2015.1006012.
Desmidt, Sebastian. 2016. “The Relevance of Mission Statements: Analysing
the Antecedents of Perceived Message Quality and Its Relationship to
Employee Mission Engagement.” Public Management Review 18(6):
894–917. https://doi.org/10.1080/14719037.2015.1051573.
Dobbins, Michael, Christoph Knill, and Eva Maria Vögtle. 2011. “An Ana-
lytical Framework for the Cross-Country Comparison of Higher Edu-
cation Governance.” Higher Education 62: 665–683. https://doi.org/
10.1007/s10734-011-9412-4.
Drori, Gili S., Giuseppe Delmestri, and Achim Oberg. 2013. “Branding the
University: Relational Strategy of Identity Construction in a Compet-
itive Field.” Trust in higher education institutions 86: 134–147.
Drori, Gili S., Giuseppe Delmestri, and Achim Oberg. 2016. “The Iconogra-
phy of Universities as Institutional Narratives.” Higher Education 71:
163–180. https://doi.org/10.1007/s10734-015-9894-6.
Drori, Gili S., Markus A. Höllerer, and Peter Walgenbach, eds. 2014a.
Global Themes and Local Variations in Organization and Manage-
ment: Perspectives on Glocalization. New York, NY: Routledge.
Drori, Gili S., Markus A. Höllerer, and Peter Walgenbach. 2014b. “Unpack-
ing the Glocalization of Organization: From Term, to Theory, to
Analysis.” European Journal of Cultural and Political Sociology 1(1):
85–99. https://doi.org/10.1080/23254823.2014.904205.
Drucker, Peter F. 1974. Management: Tasks, Responsibilities, Practices.
New York, NY: Harper and Row.
Duncan, W. Jack, Peter M. Ginter, and W. Keith Kreidel. 1994. “A Sense of
Direction in Public Organizations: An Analysis of Mission State-
ments in State Health Departments.” Administration & Society 26(1):
11–27. https://doi.org/10.1177/009539979402600102.
Efe, Ibrahim, and Omer Ozer. 2015. “A Corpus-Based Discourse Analysis
of the Vision and Mission Statements of Universities in Turkey.”
Higher Education Research & Development 34(6): 1110–22. https://
doi.org/10.1080/07294360.2015.1070127.
1208
UNIVERSITY MISSION STATEMENTS


## Page 23

Entman, Robert M. 1993. “Framing: Toward Clarification of a Fractured
Paradigm.” Journal of Communication 43(4): 51–58. https://doi.org/
10.1111/j.1460-2466.1993.tb01304.x.
ETER Project. 2021. European Tertiary Education Register https://eter-
project.com/.
Farrell, Justin. 2016. “Corporate Funding and Ideological Polarization
About Climate Change.” Proceedings of the National Academy of Sci-
ences 113(1): 92–97. https://doi.org/10.1073/pnas.1509433112.
Fay, Daniel L., Abby Kinch, and Frances S. Berry. 2022. “Explaining Inter-
state Military Friendly Policy Diffusion across US Universities: Unco-
vering Vertical-Diagonal Diffusion.” Public Management Review
24(12): 2053–78. https://doi.org/10.1080/14719037.2021.1960735.
Fay, Daniel L., and Staci M. Zavattaro. 2016. “Branding and Isomorphism:
The Case of Higher Education.” Public Administration Review 76(5):
805–815. https://doi.org/10.1111/puar.12626.
Ferreira, Aristides I., and Manuela M. Hill. 2008. “Organisational Cultures
in Public and Private Portuguese Universities: A Case Study.” Higher
Education 55: 637–650. https://doi.org/10.1007/s10734-007-9080-6.
Flavin, Michael, Ting Zhou Chen, and Valentina Quintero. 2020. “Size
Matters: An Analysis of UK Higher Education Institution Mission
Statements.” Journal of Higher Education Policy and Management
42(3): 285–299. https://doi.org/10.1080/1360080X.2019.1658839.
Flexner, Abraham. 1930. Universities: American, English, German. Oxford,
UK: Oxford University Press.
Flexner, Abraham, and Clark Kerr. 2021. Universities: American, English,
German.
New
York,
NY:
Routledge.
https://doi.org/10.4324/
9780429339608.
Fowles, Jacob, H. George Frederickson, and Jonathan G. S. Koppell. 2016.
“University Rankings: Evidence and a Conceptual Framework.” Pub-
lic Administration Review 76(5): 790–803. https://doi.org/10.1111/
puar.12610.
Frank, David John, and John W. Meyer. 2020. “The University and the
Global Knowledge Society.” Princeton, NJ: Princeton University Press
http://digital.casalini.it/9780691202075.
Frumkin, Peter, and Mark T. Kim. 2001. “Strategic Positioning and the
Financing of Nonprofit Organizations: Is Efficiency Rewarded in the
Contributions Marketplace?” Public Administration Review 61(3), Ltd:
266–275. https://doi.org/10.1111/0033-3352.00029.
Fumasoli, Tatiana, Giovanni Barbato, and Matteo Turri. 2020. “The Deter-
minants of University Strategic Positioning: A Reappraisal of the
Organisation.” Higher Education 80(2): 305–334. https://doi.org/10.
1007/s10734-019-00481-6.
Gerhardt, Lisa-Maria, Jan Goldenstein, Simon Oertel, Philipp Poschmann,
and Peter Walgenbach. 2023. “The Managerialization of Higher
Education in Germany and Its Consequences: Changes in Job
Advertisements for Professorships in German Universities, 1990 to
2010.” In University Collegiality and the Erosion of Faculty Authority,
Vol 86, edited by Kerstin Sahlin and Ulla Eriksson-Zetterquist, 59–
85. Leeds, UK: Research in the Sociology of Organizations. Emerald
Publishing. https://doi.org/10.1108/S0733-558X20230000086003.
Geschwind, Lars, and Anders Broström. 2022. “To Be or Not to Be a Tech-
nical University: Organisational Categories as Reference Points in
Higher Education.” Higher Education 84(1): 121–139. https://doi.
org/10.1007/s10734-021-00757-w.
Giusepponi, Katia, and Ernesto Tavoletti. 2018. “Vision and Mission State-
ments in Italian Universities: Results of an Empirical Investigation
on Strategic Orientation.” Journal of the Knowledge Economy 9(1):
301–328. https://doi.org/10.1007/s13132-015-0343-7.
Glynn, Mary A. 2008. “Beyond Constraint: How Institutions Enable Identi-
ties.” In The SAGE handbook of organizational institutionalism, edi-
ted by Royston Greenwood, C. Oliver, K. Sahlin and R. Suddaby,
413–430. Los Angeles; London: SAGE.
Goffman, Erving. 1974. Frame Analysis: An Essay on the Organization of
Experience. Cambridge, MA: Harvard University Press.
Goldenstein, Jan, Philipp Poschmann, and Michael Hunoldt. 2023. “The
Global Orientation of Organizations: An Analysis of the Effects of
Global
Cultural
Rationalization
and
National
Institutional
Traditions.” Journal of Management Studies 60(6): 1584–1623.
https://doi.org/10.1111/joms.12858.
Gonzalez-Campo, Carlos Hernan, Guillermo Murillo-Vargas, and Monica
Garcia Solarte. 2021. “Differentiation of Colombian University Mis-
sion Statements.” International Journal of Educational Management
35(7): 1421–30. https://doi.org/10.1108/IJEM-12-2020-0579.
Greene, William H. 2018. Econometric Analysis (eigth ed.), New York, NY:
Pearson.
Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. 2022. Text
as Data: A New Framework for Machine Learning and the Social Sci-
ences. Princeton, NJ: Princeton University Press.
Hannigan, Timothy R., Richard F. J. Haans, Keyvan Vakili, Hovig Tchalian,
Vern L. Glaser, Milo Shaoqing Wang, Sarah Kaplan, and P. Devereaux
Jennings. 2019. “Topic Modeling in Management Research: Rendering
New Theory from Textual Data.” Academy of Management Annals
13(2): 586–632. https://doi.org/10.5465/annals.2017.0099.
Heinze, Torben, and Christoph Knill. 2008. “Analysing the Differential
Impact of the Bologna Process: Theoretical Considerations on
National Conditions for International Policy Convergence.” Higher
Education 56: 493–510. https://doi.org/10.1007/s10734-007-9107-z.
Hickman, Louis, Stuti Thapa, Louis Tay, Mengyang Cao, and Padmini
Srinivasan. 2022. “Text Preprocessing for Text Mining in Organizational
Research: Review and Recommendations.” Organizational Research
Methods 25(1): 114–146. https://doi.org/10.1177/1094428120971683.
Hladchenko, Myroslava. 2016. “The Organizational Identity of Ukrainian
Universities as Claimed through Their Mission Statements.” Tertiary
Education and Management 22(4): 376–389. https://doi.org/10.
1080/13583883.2016.1236144.
Höllerer, Markus A., Peter Walgenbach, and Gili S. Drori. 2017. “The Con-
sequences of Globalization for Institutions and Organizations.” In
The SAGE Handbook of Organizational Institutionalism, edited by
Royston Greenwood, Christine Oliver, Thomas B. Lawrence, and
Renate E. Meyer, 214–242. London, UK: SAGE.
Hollibaugh, Gary E. 2019. “The Use of Text as Data Methods in Public
Administration: A Review and an Application to Agency Priorities.”
Journal of Public Administration Research and Theory 29(3): 474–490.
https://doi.org/10.1093/jopart/muy045.
Hyndman, Noel, and Ron Eden. 2001. “Rational Management, Perfor-
mance Targets and Executive Agencies: Views from Agency Chief
Executives in Northern Ireland.” Public Administration 79(3): 579–
598. https://doi.org/10.1111/1467-9299.00270.
James, Helen, and Jeroen Huisman. 2009. “Missions Statements in Wales:
The Impact of Markets and Policy on Congruence between Institu-
tions.” Journal of Higher Education Policy and Management 31(1):
23–35. https://doi.org/10.1080/13600800802559229.
Judson, Kimberly M., Linda Gorchels, and Timothy W. Aurand. 2006. “Build-
ing a University Brand from Within: A Comparison of Coaches’ Per-
spectives of Internal Branding.” Journal of Marketing for Higher
Education 16(1): 97–114. https://doi.org/10.1300/J050v16n01_05.
Jungblut, Jens, and Marc Jungblut. 2017. “All Different? All Equal? Differ-
entiation of Universities’ Mission Statements and Excellence Initia-
tives in Germany.” Science and Public Policy 44(4): 535–545. https://
doi.org/10.1093/scipol/scw082.
Kosmützky, Anna. 2012. “Between Mission and Market Position: Empiri-
cal Findings on Mission Statements of German Higher Education
Institutions.” Tertiary Education and Management 18(1): 57–77.
https://doi.org/10.1080/13583883.2011.617466.
Kosmützky, Anna, and Georg Krücken. 2015. “Sameness and Difference.”
International Studies of Management and Organization 45(2): 137–
149. https://doi.org/10.1080/00208825.2015.1006013.
Kraus, Sascha, Satish Kumar, Weng Marc Lim, Jaspreet Kaur, Anuj
Sharma, and Francesco Schiavone. 2023. “From Moon Landing to
Metaverse: Tracing the Evolution of Technological Forecasting and
Social Change.” Technological Forecasting and Social Change 189:
122381. https://doi.org/10.1016/j.techfore.2023.122381.
Krücken, G., and F. Meier. 2006. “Turning the University into an Organiza-
tional Actor.” In Globalization and Organization: World Society and
PUBLIC ADMINISTRATION REVIEW
1209


## Page 24

Organizational Change, edited by Gili S. Drori, John W. Meyer, and
Hokyu Hwang, 241–257. Oxford, UK: Oxford University Press.
Kuenssberg, Sally. 2011. “The Discourse of Self-Presentation in Scottish
University Mission Statements.” Quality in Higher Education 17(3):
279–298. https://doi.org/10.1080/13538322.2011.625205.
Levy, Daniel C. 2012. “How Important Is Private Higher Education in
Europe? A Regional Analysis in Global Context.” European Journal
of Education 47(2): 178–197. https://doi.org/10.1111/j.1465-3435.
2012.01517.x.
Levy, Daniel C. 2018. “Global Private Higher Education: An Empirical Pro-
file of Its Size and Geographical Shape.” Higher Education 76(4):
701–715. https://doi.org/10.1007/s10734-018-0233-6.
Lin, Jianhua. 1991. “Divergence Measures Based on the Shannon
Entropy.” IEEE Transactions on Information Theory 37(1): 145–151.
https://doi.org/10.1109/18.61115.
Liu, Zejin. 2024. “Institutional Pressures and the Prevalence of Nonprofit
Sector Support Organizations.” Public Administration Review 1-13.
https://doi.org/10.1111/puar.13866.
Loewenstein, Jeffrey, William Ocasio, and Candace Jones. 2012. “Vocabu-
laries and Vocabulary Structure: A New Approach Linking Catego-
ries, Practices, and Institutions.” Academy of Management Annals
6(1): 41–86. https://doi.org/10.5465/19416520.2012.660763.
Long, J. Scott, and Laurie H. Ervin. 2000. “Using Heteroscedasticity Con-
sistent Standard Errors in the Linear Regression Model.” The Ameri-
can Statistician 54(3): 217–224. https://doi.org/10.1080/00031305.
2000.10474549.
Mackay, Lesley, Peter Scott, and David Smith. 1995. “Restructured and
Differentiated? Institutional Responses to the Changing Environ-
ment of UK Higher Education.” Higher Education Management 7(2):
193–205.
Manning, Keenan Daniel. 2021. “Textual Analysis of University Mission
Statements in East Asian World-Class Universities.” Higher Educa-
tion Evaluation and Development 15(1): 19–34. https://doi.org/10.
1108/HEED-09-2020-0033.
Marquis, Christopher, and Andr�as Tilcsik. 2013. “Imprinting: Toward a
Multilevel Theory.” The Academy of Management Annals 7(1): 195–
245. https://doi.org/10.1080/19416520.2013.766076.
Meyer, John W. 2000. “Globalization: Sources and Effects on National
States and Societies.” International Sociology 15(2): 233–248.
https://doi.org/10.1177/0268580900015002006.
Meyer, John W., and Evan Schofer. 2007. “The University in Europe and
the World: Twentieth Century Expansion.” In Towards a Multiversity?
Universities between global trends and national traditions, edited by
G. Krücken, A. Kosmützky, and M. Torka, 45–62. Bielefeld, Germany:
transcript.
Meyer, John W., Francisco O. Ramirez, David J. Frank, and Evan Schofer.
2007. “Higher Education as an Institution.” In The Sociology of Higher
Education, edited by Patricia J. Gumport, 187–221. Baltimore, MD:
Johns Hopkins University Press.
Meyer, John W. 2010. “World Society, Institutional Theories, and the
Actor.” Annual Review of Sociology 36: 1–20. https://doi.org/10.
1146/annurev.soc.012809.102506.
Meyer, John W., John Boli, George M. Thomas, and Francisco O. Ramirez.
1997. “World Society and the Nation-State.” American Journal of
Sociology 103(1): 144–181. https://doi.org/10.1086/231174.
Meyer, John W., and Patricia Bromley. 2013. “The Worldwide Expansion
of ‘Organization.” Sociological Theory 31(4): 366–389. https://doi.
org/10.1177/0735275113513264.
Mimno, David, Hanna M. Wallach, Edmund Talley, Miriam Leenders, and
Andrew McCallum. 2011. “Optimizing Semantic Coherence in Topic
Models.” In Proceedings of the Conference on Empirical Methods in Nat-
ural Language Processing, 262–272. EMNLP ‘11. Association for Com-
putational Linguistics https://doi.org/10.5555/2145432.2145462.
Mizrahi-Shtelman, Ravit, and Gili S. Drori. 2021. “World-Rank and/or
Locally Relevant? Organizational Identity in the Mission Statements
of Higher Education Organizations in Israel, 2008–2018.” Minerva
59(1): 1–25. https://doi.org/10.1007/s11024-020-09414-5.
Mizrahi-Shtelman, Ravit, and Gili S. Drori. 2022. “World Society Theory
and Glocalization: Culture between Transnationality, Structuration,
Rationalization and Actorhood.” In Handbook of Culture and Glocali-
zation, edited by Victor N. Roudometof and Ugo Dessì, 337–353.
Cheltenham, UK: Edward Elgar.
Mizrahi-Shtelman, Ravit, and Gili S. Drori. 2023. “Ivory Tower or Tower of
Babel? The Challenge of Multilingualism for the Globally Embedded
University.” Higher Education 85(6): 1357–79. https://doi.org/10.
1007/s10734-022-00894-w.
Morphew, Christopher C., and Matthew Hartley. 2006. “Mission State-
ments: A Thematic Analysis of Rhetoric across Institutional Type.”
The Journal of Higher Education 77(3): 456–471. https://doi.org/10.
1080/00221546.2006.11778934.
Moschella, Manuela, and Luca Pinto. 2019. “Central Banks’ Communica-
tion as Reputation Management: How the Fed Talks under Uncer-
tainty.” Public Administration 97(3): 513–529. https://doi.org/10.
1111/padm.12543.
Neave, Guy. 2003. “The Bologna Declaration: Some of the Historic
Dilemmas Posed by the Reconstruction of the Community in Eur-
ope’s Systems of Higher Education.” Educational Policy 17(1): 141–
164. https://doi.org/10.1177/0895904802239290.
Newsom, Walter, and C. Ray Hayes. 1991. “Are Mission Statements
Worthwhile?” Planning for Higher Education 19(2): 28–30.
Nybom, Thorsten. 2003. “The Humboldt Legacy: Reflections on the Past,
Present, and Future of the European University.” Higher Education
Policy
16(2):
141–159.
https://doi.org/10.1057/palgrave.hep.
8300013.
Oertel, Simon. 2018. “The Role of Imprinting on the Adoption of Diversity
Management in German Universities.” Public Administration 96(1):
104–118. https://doi.org/10.1111/padm.12384.
Oertel, Simon, and Matthias Söll. 2017. “Universities between Traditional
Forces and Modern Demands: The Role of Imprinting on the Mis-
sions of German Universities.” Higher Education 73: 1–18. https://
doi.org/10.1007/s10734-016-0013-0.
Oliver-Lumerman, Amalya, and Gili S. Drori. 2021. From Ivory Tower to
Academic Commitment and Leadership: The Changing Public Mission
of Universities. Cheltenham, UK: Edward Elgar Publishing. https://
doi.org/10.4337/9781781000342.
Ossewaarde, Ringo, André Nijhof, and Liesbet Heyse. 2008. “Dynamics of
NGO Legitimacy: How Organising Betrays Core Missions of INGOs.”
Public Administration and Development 28(1): 42–53. https://doi.org/
10.1002/pad.472.
Ozdem, Guven. 2011. “An Analysis of the Mission and Vision Statements
on the Strategic Plans of Higher Education Institutions.” Educational
Sciences: Theory and Practice 11(4): 1887–94.
Palmer, Timothy B., and Jeremy C. Short. 2008. “Mission Statements in U.
S. Colleges of Business: An Empirical Examination of Their Content
With Linkages to Configurations and Performance.” Academy of
Management Learning & Education 7(4): 454–470. https://doi.org/10.
5465/amle.2008.35882187.
Paradeise, Catherine, and Jean-Claude Thoenig. 2013. “Academic Institu-
tions in Search of Quality: Local Orders and Global Standards.”
Organization
Studies
34(2):
189–218.
https://doi.org/10.1177/
0170840612473550.
Pearce, Craig L., Bob G. Wood, and Christina L. Wassenaar. 2018. “The
Future of Leadership in Public Universities: Is Shared Leadership
the Answer?” Public Administration Review 78(4): 640–44. https://
doi.org/10.1111/puar.12938.
Pearce, John A. 1982. “The Company Mission as a Strategic Tool.” Sloan
Management Review 23(3): 15–24.
Pfeffer, Jeffrey, and Gerald Salancik. 2006. “External Control of Organiza-
tions—Resource
Dependence
Perspective.”
In
Organizational
Behavior 2, edited by John B. Miner, 355–370. London, UK:
Routledge.
Phan, Xuan-Hieu, Cam-Tu Nguyen, Dieu-Thu Le, Le-Minh Nguyen,
Susumu Horiguchi, and Quang-Thuy Ha. 2011. “A Hidden Topic-
Based Framework toward Building Applications with Short Web
1210
UNIVERSITY MISSION STATEMENTS


## Page 25

Documents.” IEEE Transactions on Knowledge and Data Engineering
23(7): 961–976. https://doi.org/10.1109/TKDE.2010.27.
Philippczyck, Nicole, Jan Grundmann, and Simon Oertel. 2024. “The
Framing of Diversity Statements in European Universities: The Role
of Imprinting and Institutional Legacy.” Minerva 62(1): 69–92.
https://doi.org/10.1007/s11024-023-09507-x
Philipps, Axel. 2013. “Mission Statements and Self-Descriptions of Ger-
man Extra-University Research Institutes: A Qualitative Content
Analysis.” Science and Public Policy 40(5): 686–697. https://doi.org/
10.1093/scipol/sct024.
Poister, Theodore H. 2010. “The Future of Strategic Planning in the Pub-
lic Sector: Linking Strategic Management and Performance.” Public
Administration Review 70(s1): s246–s254. https://doi.org/10.1111/j.
1540-6210.2010.02284.x.
Powell, Walter W., Aaron Horvath, and Christof Brandtner. 2016. “Click
and Mortar: Organizations on the Web.” Research in Organiza-
tional Behavior 36: 101–120. https://doi.org/10.1016/j.riob.2016.
07.001.
Rabovsky, Thomas M. 2014. “Using Data to Manage for Performance at
Public Universities.” Public Administration Review 74(2): 260–272.
https://doi.org/10.1111/puar.12185.
Rabovsky, Thomas, and Amanda Rutherford. 2016. “The Politics of
Higher Education: University President Ideology and External Net-
working.” Public Administration Review 76(5): 764–777. https://doi.
org/10.1111/puar.12529.
Ramirez, F. O. 2006. “Growing Commonalities and Persistent Differences
in Higher Education: Universities between Global Models and
National Legacies.” In The New Institutionalism in Education, edited
by Heinz-Dieter Meyer and Brian Rowan, 123–141. Albany, NY: State
University of New York Press.
Ramirez, Francisco O. 2020. “The Socially Embedded American Univer-
sity: Intensification and Globalization.” In Missions of Universities:
Past, Present, Future, edited by Lars Engwall, 131–161. Cham,
Switzerland:
Springer.
https://doi.org/10.1007/978-3-030-41834-
2_9.
Ramirez, Francisco O., and Tom Christensen. 2013. “The Formalization of
the University: Rules, Roots, and Routes.” Higher Education 65: 695–
708. https://doi.org/10.1007/s10734-012-9571-y.
Ramirez, Francisco O., and Dijana Tiplic. 2014. “In Pursuit of Excellence?
Discursive Patterns in European Higher Education Research.” Higher
Education
67(4):
439–455.
https://doi.org/10.1007/s10734-013-
9681-1.
Ran, Bing, and P. Robert Duimering. 2007. “Imaging the Organization:
Language Use in Organizational Identity Claims.” Journal of Busi-
ness and Technical Communication 21(2): 155–187. https://doi.org/
10.1177/1050651906297167.
Reymert, Ingvild, Jens Jungblut, and Siri B. Borlaug. 2021. “Are Evaluative
Cultures National or Global? A Cross-National Study on Evaluative
Cultures in Academic Recruitment Processes in Europe.” Higher
Education
82:
823–843.
https://doi.org/10.1007/s10734-020-
00659-3.
Roberts, Margaret E., Brandon M. Stewart, and Edoardo M. Airoldi. 2016.
“A Model of Text for Experimentation in the Social Sciences.” Jour-
nal of the American Statistical Association 111(515): 988–1003.
https://doi.org/10.1080/01621459.2016.1141684.
Roberts, Margaret E., Brandon M. Stewart, and Dustin Tingley. 2016.
“Navigating the Local Modes of Big Data: The Case of Topic
Models.” In Computational Social Science Tools, edited by R. Michael
Alvarez, 51–97. Cambridge, UK: Cambridge University Press.
Roberts, Margaret E., Brandon M. Stewart, and Dustin Tingley. 2019.
“Stm: An R Package for Structural Topic Models.” Journal of Statisti-
cal Software 91(2): 1–40. https://doi.org/10.18637/jss.v091.i02.
Roberts, Margaret E., Brandon M. Stewart, Dustin Tingley, Christopher
Lucas,
Jetson
Leder-Luis,
Shana
Kushner
Gadarian,
Bethany
Albertson, and David G. Rand. 2014. “Structural Topic Models for
Open-Ended Survey Responses.” American Journal of Political Sci-
ence 58(4): 1064–82. https://doi.org/10.1111/ajps.12103.
Kobayashi, Vladimer B., Stefan T. Mol, Hannah A. Berkers, G�abor
Kismih�ok, and Deanne N. Den Hartog. 2018. “Text Mining in Orga-
nizational Research.” Organizational Research Methods 21(3): 733–
765. https://doi.org/10.1177/1094428117722619.
Sarta, Andrew, Rodolphe Durand, and Jean-Philippe Vergne. 2021.
“Organizational Adaptation.” Journal of Management 47(1): 43–75.
https://doi.org/10.1177/0149206320929088.
Sasaki, Innan, Josip Kotlar, Davide Ravasi, and Eero Vaara. 2020. “Dealing
with Revered Past: Historical Identity Statements and Strategic
Change in Japanese Family Firms.” Strategic Management Journal
41(3): 590–623. https://doi.org/10.1002/smj.3065.
Sauntson, Helen, and Liz Morrish. 2010. “Vision, Values and International
Excellence: The ‘Products’ that University Mission Statements Sell
to Students.” In The Marketisation of Higher Education and the Stu-
dent as Consumer. edited by Elizabeth Nixon, Mike Molesworth and
Richard Scullion, 87–99. Abingdon, UK: Routledge.
Schmiedel, Theresa, Oliver Müller, and Jan vom Brocke. 2019. “Topic
Modeling as a Strategy of Inquiry in Organizational Research: A
Tutorial With an Application Example on Organizational Culture.”
Organizational Research Methods 22(4): 941–968. https://doi.org/10.
1177/1094428118773858.
Schulz, Ann-Christine, Kerstin Fehre, and Simon Oertel. 2023. “The Adop-
tion of MBA Programs in Germany: An Institutional Perspective.”
Academy of Management Learning and Education 22(2): 216–238.
https://doi.org/10.5465/amle.2020.0289.
Schulze,
Patrick,
Simon
Wiegrebe,
Paul
W.
Thurner,
Christian
Heumann,
and
Matthias
Aßenmacher.
2024.
“A
Bayesian
Approach to Modeling Topic-Metadata Relationships.” AStA
Advances in Statistical Analysis 108: 333–349. https://doi.org/10.
1007/s10182-023-00485-9.
Seeber, Marco, Vitaliano Barberio, Jeroen Huisman, and Jelle Mampaey.
2019. “Factors Affecting the Content of Universities’ Mission State-
ments: An Analysis of the United Kingdom Higher Education Sys-
tem.” Studies in Higher Education 44(2): 230–244. https://doi.org/10.
1080/03075079.2017.1349743.
Simsek, Zeki, Brian Curtis Fox, and Ciaran Heavey. 2015. “What’s Past Is
Prologue’: A Framework, Review, and Future Directions for Organi-
zational Research on Imprinting.” Journal of Management 41(1):
288–317. https://doi.org/10.1177/0149206314553276.
Stinchcombe, Arthur L. 1965. “Social Structure and Organizations.” In
Handbook of Organizations, edited by James G. March, 142–193.
Chicago, IL: Rand McNally & Co.
Suchman, Mark C. 1995. “Managing Legitimacy: Strategic and Institu-
tional Approaches.” Academy of Management Review 20(3): 571–
610. https://doi.org/10.5465/amr.1995.9508080331.
Taylor, Barrett J., and Christopher C. Morphew. 2010. “An Analysis of Bac-
calaureate College Mission Statements.” Research in Higher Educa-
tion 51(5): 483–503. https://doi.org/10.1007/s11162-010-9162-7.
Townley,
Barbara.
1997.
“The
Institutional
Logic
of
Performance
Appraisal.” Organization Studies 18(2): 261–285. https://doi.org/10.
1177/017084069701800204.
Vayansky, Ike, and Sathish A. P. Kumar. 2020. “A Review of Topic Model-
ing Methods.” Information Systems 94: 101582. https://doi.org/10.
1016/j.is.2020.101582.
Vogel, Rick. 2012. “Framing and ccounter-framing new public manage-
ment: The case of Germany.” Public Administration 90(2): 370–392.
https://doi.org/10.1111/j.1467-9299.2011.01981.x.
Walker, Richard M., Yanto Chandra, Jiasheng Zhang, and Arjen van
Witteloostuijn. 2019. “Topic Modeling the Research-Practice Gap in
Public Administration.” Public Administration Review 79(6): 931–37.
https://doi.org/10.1111/puar.13095.
Weiherl, Julia, and Doris Masal. 2016. “Transformational Leadership and
Followers’ Commitment to Mission Changes.” International Journal
of
Public
Administration
39:
861–871.
https://doi.org/10.1080/
01900692.2015.1053611.
Whorf, Benjamin Lee. 2012. Language, Thought, and Reality: Selected Writ-
ings of Benjamin Lee Whorf. Cambridge, MA: edited by James G.
PUBLIC ADMINISTRATION REVIEW
1211


## Page 26

March MIT Press. https://hdl.handle.net/11858/00-001M-0000-000F-
9F34-C.
Yan, Xiaohui, Jiafeng Guo, Yanyan Lan, and Xueqi Cheng. 2013. “A
Biterm Topic Model for Short Texts.” In Proceedings of the 22nd
International Conference on World Wide Web, 1445–56. WWW ‘13.
New York, NY, USA: Association for Computing Machinery. https://
doi.org/10.1145/2488388.2488514.
Zapp, Mike, Jens Jungblut, and Francisco O. Ramirez. 2021. “Legitimacy,
Stratification, and Internationalization in Global Higher Education:
The Case of the International Association of Universities.” Tertiary
Education and Management 27(1): 1–15. https://doi.org/10.1007/
s11233-020-09062-0.
Zapp, Mike, and Francisco O. Ramirez. 2019. “Beyond Internationalisation
and Isomorphism – the Construction of a Global Higher Education
Regime.” Comparative Education 55(4): 473–493. https://doi.org/10.
1080/03050068.2019.1638103.
Zuo, Yuan, Jichang Zhao, and Ke Xu. 2016. “Word Network Topic Model:
A Simple but General Solution for Short and Imbalanced Texts.”
Knowledge and Information Systems 48: 379–398. https://doi.org/10.
1007/s10115-015-0882-z.
AUTHOR BIOGRAPHIES
Nicole Philippczyck is a doctoral student of Manage-
ment and Organization at TU Ilmenau. Her research
focuses on institutional theories of organization and
the diffusion of practices among organizations. Email:
nicole.philippczyck@tu-ilmenau.de
Harry Hoffmann is a doctoral student of Management
and Organization at TU Ilmenau. His research focuses
on the application of computational methods and
natural language processing in fields like institutional-
ism
and
management.
Email:
harry.hoffmann@tu-
ilmenau.de
Simon Oertel is a professor of strategic management
and organization at Paris Lodron University of Salz-
burg, Austria. His research focuses on organization
theories (in particular institutional theories of organi-
zation), their empirical testing and further develop-
ment. His research has been published in journals
such as Business & Society, Entrepreneurship Theory
and Practice, Journal of Business Venturing, Organiza-
tion Studies, Public Administration or Strategic Organi-
zation. Email: simon.oertel@plus.ac.at
How to cite this article: Philippczyck, Nicole,
Harry Hoffmann, and Simon Oertel. 2025. “The Role
of Institutional Factors in Shaping University
Mission Statements: A Topic-Modeling Approach.”
Public Administration Review 85(4): 1187–1216.
https://doi.org/10.1111/puar.13921
1212
UNIVERSITY MISSION STATEMENTS


## Page 27

APPENDIX 1
T A B L E A 1
Logistic regression analysis on mission statement adoption.
Variable
Model 1
Model 2
Model 3
Model 4
Intercept
1.2718***
1.1794***
1.1787***
0.9193***
Cultural rationalization
Cultural Rationalization Index
0.1008†
0.1013
0.1199†
Founding phase
Founding phase 1945–1990
0.1211*
Founding phase 1991–1999
0.1226†
Founding phase after 1999
0.1099
Ownership
Private
�0.0053
�0.0050
Control variables
THE-Rank
0.0000
0.0000
0.0000
0.0000
log(Age)
�0.0272†
�0.0296†
�0.0300†
0.0144
log(GDP)
0.0008
0.0013
0.0019
0.0033
Density
0.0013
0.0012
0.0011
0.0024
log(Students)
�0.0232†
�0.0202
�0.0205
�0.0231†
Note: Reference categories: Founding phase prior to 1945, Public Control.
†p < 0.10; *p < 0.05; **p < .01; ***p < .001.
PUBLIC ADMINISTRATION REVIEW
1213


## Page 28

T A B L E B 1
Robustness check for university accreditation.
Variable
Topic 1
Topic 2
Topic 3
Topic 4
Topic 5
Topic 6
Intercept
0.1593 (0.2195)
0.2108 (0.1678)
0.098 (0.2228)
0.5833 (0.3439)†
�0.3645 (0.2295)
0.2663 (0.1555)†
Cultural rationalization
Cultural Rationalization Index
�0.2788 (0.0562)***
�0.0457 (0.0364)
�0.1412 (0.0554)*
0.3241 (0.084)***
0.3353 (0.0556)***
�0.1903 (0.0352)***
Founding phase effect
Founding phase 1945–1990
0.0396 (0.0487)
�0.1008 (0.036)**
0.0116 (0.0499)
0.0218 (0.0807)
0.0551 (0.0523)
�0.0257 (0.0337)
Founding phase 1991–1999
�0.0327 (0.0647)
�0.0744 (0.0501)
0.0487 (0.0705)
0.0123 (0.108)
0.0461 (0.0706)
0.007 (0.0435)
Founding phase after 1999
0.0058 (0.0816)
�0.1329 (0.0617)*
0.0327 (0.0801)
�0.06 (0.1324)
0.1252 (0.0838)
0.0311 (0.0543)
Ownership
Private
�0.0669 (0.0414)
�0.0265 (0.0289)
0.1147 (0.0405)**
0.0423 (0.0595)
�0.0192 (0.0372)
�0.0444 (0.0256)†
Accreditation
Number of programme accreditations
0 (0)
0 (0)
0 (0)
�0.0001 (0)**
0 (0)
0 (0)†
Number of institutional accreditations
�0.0149 (0.0256)
�0.036 (0.0194)†
0.0243 (0.026)
�0.0368 (0.0409)
0.0569 (0.0265)*
0.0068 (0.0176)
Control variables
THE-Rank
�0.0054 (0.004)
�0.0027 (0.003)
0.0043 (0.004)
0.0013 (0.0065)
0.0025 (0.0037)
�0.0002 (0.0026)
log(Age)
0.0114 (0.0117)
0.011 (0.0098)
�0.017 (0.0123)
0.0002 (0.0188)
�0.0096 (0.0124)
0.0056 (0.0085)
Density
0.0162 (0.0132)
0 (0.0095)
0.0144 (0.0134)
�0.0236 (0.0202)
0.0099 (0.0131)
�0.0145 (0.0086)†
log(GDP (NUTS3))
0.0001 (0.0001)
0.0001 (0.0001)
0.0002 (0.0001)
�0.0006 (0.0002)**
0.0002 (0.0001)†
0 (0.0001)
log(Students)
�0.001 (0.0049)
�0.0017 (0.0037)
0.0002 (0.0052)
�0.0065 (0.0075)
0.0107 (0.0052)*
�0.0012 (0.0032)
Note: Reference categories: Founding phase prior to 1945, Public Control.
†p < .10.
*p < .05.
**p < .01.
***p < .001.
APPENDIX 2
1214
UNIVERSITY MISSION STATEMENTS


## Page 29

T A B L E C 1
Robustness check for university funding.
Variable
Topic 1
Topic 2
Topic 3
Topic 4
Topic 5
Topic 6
Intercept
0.4646 (0.2535)†
0.0814 (0.1976)
0.1922 (0.2903)
0.6562 (0.346)†
�0.527 (0.2358)*
0.1256 (0.2269)
Global orientation
Globalization Index
�0.2779 (0.0771)***
�0.0455 (0.0537)
�0.2428 (0.0799)**
0.4192 (0.0925)***
0.3758 (0.0686)***
�0.228 (0.0566)***
Founding phase effect
Founding phase 1945–1990
�0.0117 (0.0412)
�0.0099 (0.0325)
�0.0241 (0.0522)
�0.0701 (0.0607)
0.072 (0.0392)†
0.0442 (0.0374)
Founding phase 1991–1999
�0.0041 (0.0766)
0.009 (0.0584)
�0.0575 (0.0866)
�0.0594 (0.1072)
0.0603 (0.0669)
0.0531 (0.0671)
Founding phase after 1999
�0.0452 (0.0691)
�0.0409 (0.0587)
0.0327 (0.0907)
�0.1987 (0.1102)†
0.1333 (0.0681)†
0.1203 (0.0646)†
Ownership
Private
�0.0461 (0.0622)
�0.014 (0.0515)
0.1051 (0.0823)
�0.0526 (0.0952)
0.0856 (0.0636)
�0.079 (0.0543)
Funding
Core Budget
�0.0002 (0.0002)
0 (0.0001)
0.0001 (0.0002)
0.0001 (0.0003)
0.0003 (0.0002)
�0.0002 (0.0002)
Third Party Funding
0.0056 (0.0048)
�0.0014 (0.0039)
�0.0042 (0.0058)
�0.0001 (0.0072)
�0.0063 (0.0047)
0.0064 (0.0043)
Student Fees
�0.0037 (0.0023)
�0.0018 (0.002)
�0.0017 (0.0029)
0.0192 (0.0037)***
�0.0106 (0.0024)***
�0.0013 (0.0022)
Control variables
THE-Rank
0 (0)
0 (0)
0 (0)
0 (0)
0 (0)
0 (0)
log(Age)
�0.0139 (0.0258)
�0.0073 (0.0216)
0.0284 (0.0312)
�0.1005 (0.038)**
0.0656 (0.0265)*
0.0281 (0.0227)
GDP (NUTS3)
�0.0009 (0.0022)
�0.0004 (0.0018)
0.0016 (0.0025)
�0.0021 (0.0034)
�0.0003 (0.002)
0.0021 (0.0019)
log(Density)
�0.0017 (0.0142)
0.0043 (0.0117)
�0.002 (0.0165)
�0.0051 (0.0197)
0.0052 (0.0147)
�0.0003 (0.0128)
log(Students)
0.002 (0.0156)
0.0087 (0.0124)
0.004 (0.0188)
�0.0299 (0.0231)
0.0182 (0.0149)
�0.0031 (0.0148)
Note: Reference categories: Founding phase prior to 1945, Public Control.
†p < .10; *p < .05; **p < .01; ***p < .001.
APPENDIX 3
PUBLIC ADMINISTRATION REVIEW
1215


## Page 30

APPENDIX 4
T A B L E D 1
Beta regression with random effects and robust standard errors.
Variables
Research and
Knowledge Transfer
Academic
excellence
Cultural and
community values
Globalization and
world society
Functional
core
Profession and
performance
Random effect variance
Country-level
Intercept
0.0806
0.0016
0.0396
0.119
0.2026
0.0004
Cultural rationalization
Cultural
Rationalization
Index
0.0672
0.0000
0.0248
0.1959
0.0386
0.0009
Founding phase effect
Founding phase
1945–1990
0.1115
0.0000
0.0454
0.0107
0.0066
0.0069
Founding phase
1991–1999
0.1866
0.1362
0.4882
0.1425
0.0336
0.0019
Founding phase
after 1999
0.0032
0.0000
0.4908
0.0522
0.0085
0.2078
Ownership
Private
0.0146
0.1591
0.1536
0.1326
0.1237
0.098
Fixed effects
Intercept
�1.3181 (0.1348)***
�2.2394
(0.1136)***
�1.8265 (0.1399)***
�0.7601 (0.1703)***
�2.4589
(0.1649)***
�2.0077 (0.104)***
Cultural rationalization
Cultural
Rationalization
Index
�0.4678 (0.1112)***
�0.153
(0.0477)**
�0.2886 (0.0789)***
0.7906 (0.1601)***
0.131
(0.0929)
�0.3455
(0.0446)***
Founding phase effect
Founding phase
1945–1990
�0.1201 (0.1742)
0.0255
(0.1529)
0.0011 (0.1824)
�0.0316 (0.1765)
0.2817
(0.136)*
0.0434 (0.1482)
Founding phase
1991–1999
�0.2565 (0.2543)
0.1289
(0.2715)
0.0547 (0.3156)
�0.1029 (0.2789)
0.3005
(0.2046)
0.1104 (0.2071)
Founding phase
after 1999
�0.3447 (0.2511)
�0.1296
(0.2649)
0.2431 (0.3518)
�0.3131 (0.3041)
0.3986
(0.2281)†
0.2266 (0.2735)
Ownership
Private
�0.7071 (0.1624)***
�0.2646
(0.2099)
0.5134 (0.1987)**
0.4092 (0.2113)†
0.019
(0.1663)
�0.2137 (0.1747)
Control variables
THE-Rank
0.0373 (0.0536)
0.103
(0.0525)*
0.0064 (0.0647)
�0.1086 (0.0638)†
0.0195
(0.046)
0.0939 (0.0513)†
log(Age)
�0.1031 (0.0876)
�0.021
(0.0917)
0.1886 (0.1025)†
�0.1974 (0.1051)†
0.1918
(0.0763)*
0.0197 (0.0855)
Density
�0.04 (0.0547)
�0.0372
(0.05)
0.0043 (0.0529)
0.0045 (0.0583)
0.0383
(0.0499)
0.0065 (0.0488)
log(GDP
(NUTS3))
0.0189 (0.0513)
0.0609
(0.0486)
�0.0272 (0.0563)
�0.0675 (0.0578)
�0.0119
(0.0439)
0.0037 (0.0461)
log(Students)
�0.031 (0.0503)
�0.0268
(0.0506)
0.0291 (0.0633)
0.0626 (0.0612)
0.072
(0.0471)
�0.046 (0.0478)
Note: Reference categories: Founding phase prior to 1945, Public Control.
†p < .10; *p < .05; **p < .01; ***p < .001.
1216
UNIVERSITY MISSION STATEMENTS


## Page 31

Copyright of Public Administration Review is the property of Wiley-Blackwell and its
content may not be copied or emailed to multiple sites or posted to a listserv without the
copyright holder's express written permission. However, users may print, download, or email
articles for individual use.

