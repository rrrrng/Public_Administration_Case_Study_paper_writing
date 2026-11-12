# Assessing drivers of sustained engagement in collaborative governance arrangemen(2)

## Page 1

Journal of Public Administration Research and Theory, 2024, 34, 498–514
https://doi.org/10.1093/jopart/muae005
Advance access publication 16 February 2024
Article
Assessing drivers of sustained engagement in
collaborative governance arrangements
Graham Ambrose1,*,
, Saba Siddiki2,
1School of Public and International Affairs, North Carolina State University, Raleigh, NC 27607, USA
2Maxwell School, Syracuse University, Syracuse, NY 13244, USA
*Corresponding author: gwambros@ncsu.edu
Abstract
The formal engagement of diverse stakeholder groups in policy design and implementation has become a mainstay governance strategy. While
much has been learned about collaborative governance arrangements in terms of their structure, processes, and participant dynamics, one
particularly salient dynamic has been relatively underexplored: the factors contributing to sustained participation in collaborative venues. Public
administration and policy have developed a variety of conceptual theories which draw attention to interpersonal interactions and the ability of
stakeholders to garner political wins as important contributing factors to sustained participation. In this article, we test four theoretically rooted
hypotheses to investigate stakeholder attendance in the collaborative governance case of an environmental justice council. We analyze council
meeting minute data using computational text analysis tools and a Stochastic Actor-Oriented Model to assess: (1) conflict and concord, meas­
ured in terms of repeated (dis)agreement with others and (2) interest advancement, or the extent to which a stakeholder makes positive, neutral,
and negative comments toward topics which become the council’s annual objectives in relation to an individual’s attendance. Our interpersonal
interaction results show that increased positive relationships are associated with increased attendance, and increased negative relationships
are associated with decreased attendance, but, for both cases, only when interactions are repeated and not one-off. Our interest advancement
results show: (1) an increase in supported annual objectives is associated with decreases in attendance for an individual stakeholder, but (2)
increased oppositional and neutral annual topics are associated with a greater likelihood of attendance. This article contributes to existing schol­
arship on collaborative governance by offering additional insights into individual factors associated with sustained engagement in the collabora­
tive venue. Furthermore, the article offers a generalizable methodological approach for analyzing these dynamics drawing on computational text
analysis of meeting minute data.
Key words: collaborative governance; stakeholder engagement; conflict; environmental justice council; computational text analysis.
Introduction
Collaborative governance, defined here as the engage­
ment of diverse arrays of policy stakeholders for the pur­
pose of advising or carrying out policy formulation and/or
policy implementation activities (Innes and Booher 2003),
is increasingly ubiquitous (Ansell and Torfing 2022; Innes
and Booher 2003). Extant scholarship points to the many
benefits that accrue to participants in collaborative gov­
ernance arrangements1; for example, exposure to diverse
viewpoints, resources, knowledge, and policy preferences
held by individuals and entities in and outside of govern­
ment who have vested interests or direct experiences with
policy issues being deliberated (Kim and Siddiki 2018), so­
cial learning (Ostrom 2009; Resh et al. 2014), and relation­
ship building (Bryson, Crosby, Stone 2006; Emerson and
Nabatchi 2015). The potential to fully realize such benefits
is heightened through sustained engagement in collaborative
venues, calling for descriptive assessments of whether and
to what extent participants engage in collaborative venues
over time as well as the factors that contribute to sustained
engagement (Siddiki and Ambrose 2023).
A variety of factors can aid or hinder sustained engagement
in collaborative arrangements. Collaborative governance
is often engaged to deal with complex public sector issues
associated with uncertainty and interdependent causes and
consequences. When dealing with such issues, stakeholders
may encounter difficulty in coming to agreement on the ac­
tual problems, and what actions should be taken to address
commonly recognized problems (Emerson and Nabatchi
2015; Sabatier and Weible 2019). Furthermore, because of
problem and action disagreement, there is increased poten­
tial for groups to become adversarial and unable to advance
individual interests, which may in turn influence whether and
how stakeholders participate in shared venues (Koski et al.
2018; Sabatier and Weible 2019). In some cases, disagree­
ment among participants in collaborative governance can be
polarizing and lead to intractable conflicts. Scholars of col­
laborative governance have specifically sought to assess the
conditions under which conflict arises and/or its impact on
the work of collaboratives (Weible and Heikkila 2017). The
presence of conflict and the ability of individuals to resolve
conflict is expected to influence an individual’s decision to
continue engaging in a collaborative process (Karjalainen and
Rapeli 2015; Pondy 1967).
Another factor influencing whether individuals sustain en­
gagement in collaborative venues is less relational, and more
© The Author(s) 2024. Published by Oxford University Press on behalf of the Public Management Research Association. All rights reserved. For commercial
re-use, please contact reprints@oup.com for reprints and translation rights for reprints. All other permissions can be obtained through our RightsLink
service via the Permissions link on the article page on our site—for further information please contact journals.permissions@oup.com.
1In this article, collaborative governance is identified as a form of gov­
ernance, whereas collaborative governance arrangements identify specific
instances where collaborative governance is instituted.


## Page 2

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
499
personally strategic. Policy stakeholders strategically choose
the venue in which they participate as a means to pursue their
own interests and goals (Berardo and Lubell 2019; Emerson
and Nabatchi 2015; Lubell 2013). Whether they continue to
participate in collaborations may reflect their (dis)satisfaction
with the policy and/or political gains they are able to achieve
therein.
Testing expectations about the association between inter­
personal conflict and interest advancement and sustained en­
gagement in collaborative venues, in this article we explore
how: (1) conflict and concord, measured in terms of repeated
(dis)agreement with others and (2) interest advancement, or
the extent to which a stakeholder makes positive, neutral, and
negative comments toward topics which become the council’s
annual objectives, influence the stakeholder’s sustained en­
gagement in a collaborative venue. We apply manual and com­
putational text analysis approaches to collect data from the
council’s meeting minutes and use Stochastic Actor-Oriented
Models (SAOM or colloquially called SIENA models) to spe­
cifically analyze these phenomena given this data.
We explore these dynamics in the context of a publicly
mandated environmental justice council, which we treat
as a case of collaborative governance. Environmental jus­
tice councils exemplify collaborative governance in that
they convene government, nongovernment, and community
stakeholders in ongoing processes aimed at designing and
implementing policies. Environmental justice councils are
specifically focused on advising the development and imple­
mentation of policies that prevent communities of color and
low-income communities from disproportionately bearing
environmental burdens.
Both the methodology and results reported in this article
are useful for public administration and scholars of collab­
orative governance. First, the methodology advanced offers
a robust means to describe conflict encountered within col­
laborative governance. Further, the analytical approach used
allows for an analysis of conflict among actors through in­
terpersonal communications across time. Second, the article
contributes to understanding of factors that lead to enduring
participation in collaboration, which has been understudied
in extant collaborative governance research, but which may
be considered a critical mechanism for attaining many other
collaboration benefits. Understanding this dynamic is also im­
portant to designers of collaborative venues.
This article proceeds as follows. In the second section, we
provide a brief overview of scholarship on collaborative gov­
ernance and the study of conflict therein. In the third section,
we provide an elaborate discussion of environmental justice
councils. In the fourth section, we describe the methods by
which we studied interpersonal conflict and interest achieve­
ment within a single environmental justice council case. In
the fifth section, we provide an overview of key findings. The
sixth section provides a discussion of key findings. Finally,
in the seventh section, we conclude with a discussion of
contributions to scholarship and practice, identify key limita­
tions, and present an agenda for future work.
Conceptual background
Collaborative governance
Over the last twenty years, public administration and policy
scholars have paid considerable attention to studying cases
of collaborative governance (Ansell and Gash 2008; Sabatier
et al. 2005). Enduring attention to the study of collaborative
governance reflects its continued prevalence in public sector
decision-making, as well as its promise for generating con­
textually appropriate and representative solutions to complex
public sector challenges. To develop the already sizable body
of scholarship on collaborative governance, scholars have re­
cently sought to extend or pursue new lines of inquiry into
understanding how collaborative processes evolve over time
(Imperial et al. 2016). Efforts to characterize such are part of
a wider effort to capture the life cycle stages of collaborative
governance arrangements (Imperial et al. 2016; Siddiki and
Ambrose 2023; Ulibarri et al. 2020). According to Imperial et
al. (2016), collaborative governance (or what they refer to as
networked governance) arrangements transition between dif­
ferent life cycle stages throughout the duration of their exist­
ence as indicated by their purpose, emphasis, membership and
social system, commitment among members, level of resist­
ance to change among members, and leadership characteris­
tics. This work examines how collaborations evolve over time
at the group-level (Imperial et al. 2016; Siddiki and Ambrose
2023; Ulibarri et al. 2020; Weible et al. 2011). Complementary
individual-level analyses that examine, for example, how
individuals’ participation in collaborative arrangements
fluctuates over time and factors contributing thereto have
been limited (Ansell et al. 2020). If one acknowledges that
a collaborative group’s actions are directly related to those
that are included/present for the ­decision-making (Cohen,
March, and Olsen 1972; Howlett 2018; Kingdon 1995), we
must also acknowledge a change in attendance in the actors
that comprise the group is expected to influence the evolution
of the collaboration at the group-level. Thus, understanding
the factors influencing sustained engagement at the actor-level
adds to the recent work exploring collaborative governance
evolution over time.
As identified earlier, collaborative governance venues can
be viewed as formalized venues in which individual actors ad­
vise or carry out policy formulation and/or policy implemen­
tation activities (Innes and Booher 2003). While these venues
may be seen as means to advance individual interests, they
often are not venues of common interests. This means, there
is no guarantee collaborative venues will lead to effective
­decision-making and individual interest advancement for all
members engaged (Emerson and Nabatchi 2015), thus beg­
ging the question of what motivates individuals to continue
participating in collaborative venues and expending resources
despite no guarantee of policy and/or political wins.
Building on the preceding discussion, in the following
two subsections, we offer further discussion of two factors
that may have bearing on whether and how individuals en­
gage in collaborative governance arrangements over time:
(1) individual interest advancement and (2) interpersonal
relationships and interactions over time.
Interest advancement
Extant research on collaborative governance explores the
role of interest advancement in shaping participation in col­
laborative settings. Scholars studying collaborative processes
through the lens of the Ecology of Games framework focus
on actors’ choices regarding which collaborative venues to
engage in, as well as how they engage within and across
venues (Berardo and Lubell 2019; Lubell 2013). Lubell


## Page 3

500
Journal of Public Administration Research and Theory
(2013) argues that actors strategically choose to engage in
policy venues with the goal of advancing their own or their
group’s interest. Yet, given the diverse array of actors in the
venue and their diverse policy interests, all policy interests
cannot feasibly be addressed (Jones 2001; Simon 2013). Thus,
stakeholders must vie for policy interests they favor to be­
come the interest of the collaboration (Lubell 2013; Lubell
et al. 2010). Given this framing, one might expect actors to
continue to expend personal resources when the issues they
favor are advanced in a collaborative venue (Agranoff 2006;
Berardo and Lubell 2019). Furthermore, when actors per­
ceive that the process of decision-making does not adequately
incorporate their favored viewpoints, they are expected to
participate less frequently or move to another policy venue
entirely (Lubell 2013). Thus, we propose Hypothesis 1a and
Hypothesis 1b:
Hypothesis 1a: If a member expresses support toward
policy issue(s) included in the council’s annual objectives,
measured as the use of affirming statements regarding the
topic, in a given year, members will attend more meetings
in the following year.
Hypothesis 1b: If a member expresses support toward policy
issue(s) not included in the council’s annual objectives,
measured as the use of affirming statements regarding the
topic, in a given year, members will attend fewer meetings
in the following year.
Existing research on collaborative policymaking also points
to a relationship between the investment of personal resources
into a collaborative venue and the perceived probability of
policy losses (Sabatier et al. 1987; Sabatier and Weible 2019).
Referencing instances of adversarial, policy coalitions vying
to advance interdependent and conflicting policy interests,
sometimes within collaborative settings, scholars applying
the Advocacy Coalition Framework highlight ways in which
actors seek to translate their interest into policy before their
opponents can do the same, and/or invest resources where
political opponents have made policy gains (Sabatier and
Weible 2019). Grounding this research is the assumption that
stakeholders are motivated both by supporting their favored
policy interests, as well as by opposing the interests of their
opponents. (Sabatier et al. 1987; Weible, Siddiki and Pierce
2011). Thus, we propose Hypothesis 2a and Hypothesis 2b:
Hypothesis 2a: If a member expresses opposition toward
policy issue(s) included in the council’s annual objectives,
measured as the use of dissenting statements regarding the
topic, in a given year, members will attend more meetings
in the following year.
Hypothesis 2b: If a member expresses opposition to­
ward policy issue(s) not included in the council’s annual
objectives, measured as the use of dissenting statements
regarding the topic, in a given year, members will attend
fewer meetings in the following year.
Interpersonal relationships: conflict and concord
Collaborative governance arrangements are venues in which
diverse arrays of policy stakeholders engage, debate, and seek
to advance their policy goals (Weible and Heikkila 2017, 26).
They are, thus, analytical focal points in which to evaluate
conflict and concord among actors, as diverse arrays of actors
bring differing policy interests, knowledge, and beliefs to the
venue (Emerson and Nabatchi 2015; Innes and Gruber 2005;
Weible 2008). In recent years, scholars engaged in the study
of collaborative processes have called for further inquiry into
the phenomenon of policy conflict and policy concord (Weible
and Heikkila 2017; Yi et al. 2022). Policy conflict is defined as
disagreement among policy actors about the content and or
purpose of policy, whereas policy concord is defined as general
agreement among policy actors along the same elements (Yi
et al. 2022). Yi et al. (2022) argue the concepts of policy con­
flict and concord are theoretically identified (Schattschneider
1960) but are rarely engaged directly. Additionally, Weible
and Heikkila (2017) argue “theories and frameworks of
policy and politics typically treat conflict as a background
concept where it is . . . measured indirectly as political mobili­
zation, political activities, or competing values” (24).
While scholars acknowledge the importance of conflict in
collaborative groups, current scholarship (Ansell and Gash
2008; Emerson and Nabatchi 2015; Weible and Heikkila
2017; Yi et al. 2022) offers limited actor-level hypotheses that
address the influence of conflict and concord on future, indi­
vidual behavior. Insights on this can be drawn from Pondy
(1967) and Ostrom (2003).
Pondy’s (1967) seminal work theorized individual behavior
in response to interpersonal conflict within an organization,
recognizing that conflict should not be outright suppressed
and avoided, as it naturally emerges in all organizations. It is
the process in which conflict is engaged that ultimately leads to
functional or dysfunctional conflict. Conflict, thus, can be seen
as a shift from equilibrium within an organization to disequi­
librium. Conflict-causing disequilibrium is needed at times for
an organization to adapt and innovate, but it is suggested that
chronic and unresolved conflict leads to dysfunction. While a
level of conflict might be embraced if inducements (e.g., polit­
ical wins when favored individual interests are converted into
collaboration objectives) are great enough to bring conflict
into equilibrium, it is expected that actors will work to re­
solve conflict. When conflict remains chronic and there is little
perceived likelihood of reestablishing a lower level of conflict
in a relationship, actors will reduce their conflict by dissolving
the relationship. More recent work highlights this avoidance
behavior linking increased conflict to reduced engagement in
political settings (Karjalainen and Rapeli 2015; Neblo et al.
2010; Ulbig and Funk 1999).
While conflict can be measured in many ways, in this ar­
ticle we leverage a mix of sentiment analysis (i.e., level of (dis)
agreement) and manual coding of communication between
individual actors in a collaborative venue to evaluate con­
flict. In doing so, we work to measure the amount of conflict
individuals experience directly to examine its relation to sus­
tained engagement at the actor-level. Therefore, we propose
Hypothesis 3:
Hypothesis 3: Members experiencing repeated conflict
interactions, measured as instances of an actor’s repeated
dissenting statements toward another actor, across council
meetings in a given year will attend fewer meetings in the
following year.
While Hypothesis 3 aims to fill a clear gap in the litera­
ture regarding the effect of conflict generated in collabora­
tive venues, Hypothesis 4 is reflective of an often-studied


## Page 4

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
501
phenomenon in collaborative governance literature. Many
collaborative governance scholars have touted the impor­
tance of repeated, positive interactions through face-to-face
dialogue (Ansell and Gash 2007; Emerson and Nabatchi
2015; Ostrom 2009). Yet, little work has been done to ex­
plore the influence of repeated, positive interactions on
future behavior in collective action situations outside of
Ostrom’s lab experiments and associated work (Ostrom
2009). This work highlights the importance of both commu­
nication across actors as well as the influence of positive ac­
tion on future sustained engagement at the actor-level. Like
our measurement of policy conflict, we measure policy con­
cord directly by evaluating communication between indi­
vidual actors in the venue. Thus, we propose Hypothesis 4:
Hypothesis 4: Members experiencing repeated concord
interactions, measured as instances of an actor’s repeated
affirmative statements toward another actor, across council
meetings in a given year will attend more meetings in the
following year.
Figure 1 depicts the framework that informs the anal­
ysis in this article, including the four hypotheses tested.
The top half of the framework relates to “Policy Interest
Advancement” addressed by Hypotheses 1 and 2. The
bottom half of the framework relates to “Interpersonal
Interactions” addressed by Hypotheses 3 and 4. We theorize
that revealed preferences for policy issues as well as conflict
and concord through communication observed in one year
of venue meetings will result in various levels of meeting at­
tendance in the next year.
Study context: state-level environmental
justice councils
This article reports on an in-depth case study of a state-
mandated environmental justice council. Environmental jus­
tice (i.e., EJ) is defined by the US Environmental Protection
Agency as “the fair treatment and meaningful involvement of
all people regardless of race, color, faith, national origin, or in­
come, in the development, implementation, and enforcement of
environmental laws, regulations, and policies” (US EPA 2021).
Environmental justice first gained prominence in the US po­
litical system when Executive Order 12898, passed in 1994,
charged federal agencies with addressing the disproportionate
burden of pollution and other environmental externalities on
communities of color and low-income communities (Petersen
et al. 2006). Environmental justice has continued to gain atten­
tion across all levels of government in the US over the past three
decades (Grafton et al. 2015). Evidence of this is the growing
prevalence of publicly (e.g., policy) mandated environmental
justice councils at different levels of government.
Environmental justice councils (hereafter also called “EJ
councils” or “councils”) are venues in which citizens, govern­
ment actors, nongovernmental organizations, and other parties
are convened to collectively advise on the design and imple­
mentation of EJ policies. In contrast to other forms of EJ col­
laboration such as citizen climate juries (Ross et al. 2021) and
community-based collectives (Petersen et al. 2006), EJ councils
are unique as they are formally created through policies, such
as executive orders, legislation, or regulation, which specifi­
cally identify key aspects of their design, such as their stake­
holder composition, duties, expected activities and outputs,
and requirements for a minimum number of meetings in a year.
From diverse arrays of actors, EJ councils solicit advice
on social, scientific, policy, and other issues related to envi­
ronmental justice. More specifically, EJ councils are charged
with addressing topics related to climate change planning,
disaster management, reduction of pollution in overburdened
communities, equitable conservation and public lands use,
clean energy transitions, sustainable infrastructure, and
civil rights. Fundamentally, these councils are meant to in­
clude low-income and minority viewpoints in the discussion,
­decision-making, and implementation of policies that have
traditionally adversely and disproportionately affected them,
aligning with the fundamental foci outlined in the definition
of EJ. In doing so, EJ councils intend to support diverse rep­
resentation in information sharing in an attempt to facilitate
collective decision-making and joint problem solving.
Given these specific characteristics of EJ councils, they
prove to be an appropriate case in which to evaluate this
research for several reasons. First, because EJ councils are
mandated through a governing document, the permissions,
constraints, and required frequency of meetings are formally
identified. From a research design perspective, tracking both
participants and conflict over time is easier as the actors are
consistently and formally identified, given that the number
of council members and positions are established through
legislation. Second, they are ideal for studying the influence
of interest advancement and interpersonal conflict given EJ’s
orientation toward diverse inclusion in knowledge sharing,
discussion, and decision-making. While these concepts are
important to all collaborative governance arrangements, the
orientation of diverse representation is particularly prevalent
in EJ council policies, thus one might expect participants to
hold diverse perspectives rooted in different knowledge and
experiences. Better understanding the link between actor at­
tendance and their ability to advance their interest and their
level of relational conflict is fundamental to better under­
standing EJ councils and can lend insights about collaborative
governance more broadly. In the following section, we offer
additional information regarding the selection of the case as
well as the methods used to study conflict in EJ councils.
Methods
Sample selection
This study focuses on a single EJ council in the eastern US
mandated at the state-level by the state’s legislature. The
Figure 1 Theoretical framework.


## Page 5

502
Journal of Public Administration Research and Theory
council selected for this study bears features comparable to
those of other EJ councils publicly mandated at the state-level
with respect to purpose, structure, and duties. The rationale
for selecting the particular council case reported on in this ar­
ticle is based on data availability, as discussed in more detail
below.
The EJ council fits the definition of collaborative govern­
ance used in this article, as diverse actors are brought together
in a formalized setting to recommend policies and programs
as well as advise implementation. Encouraged by the diverse
memberships of the case council and its broad mandated
charge (both are discussed below), members bring a diversity
of interests and knowledge to the venue. With limited atten­
tion and resources, actors vie for their interests resulting in
interpersonal relationships of concord and conflict as well as
the advancement of individual interests to council objectives.
While this article examines one EJ council, the qualitative de­
scription is generalizable to many collaborative governance
venues mandated to engage complex policy issues. Given the
complexity of the issues, the diversity of the actors, and the
broadness of the mandate often observed in collaborative
governance venues, attention must be given to why diverse
actors continue to engage in complex topics in such venues.
Table 1 identifies key attributes of the EJ council case
evaluated for this article. The council is mandated by the
state legislature to provide advice to the state government
and its agencies regarding environmental justice and re­
lated community issues. The mandate requires at least six
meetings per year and identifies 20 positions on the council.
These positions are made up of two members representing
affected communities, 10 members representing various
public interests (e.g., nonprofits, business, local government,
etc.), as well as six agency heads or their delegates (i.e.,
Department of the Environment, Department of Health and
Mental Hygiene, Department of Housing and Community
Development, Department of Planning, Department of
Business and Economic Development, Department of
Transportation), a representative from the state senate, and
a representative from the state house. Thus, the council
represents a mix of an interpersonal (i.e., appointed citizens)
and an interorganizational (i.e., agency delegates) collabora­
tive governance venue. The affected community members as
well as the public interests are appointed by the Governor
and their office, but often recommended by the council itself.
For these members of the council, there is no stated per diem
or compensation. Additionally, while the mandate for the
council identifies six agency heads or their delegates, it is
often an agency delegate who attends consistently over mul­
tiple years. For all 20 members, there are no sanctions for
absences and there are no term limits to their membership.
In this case, there is variation in attendance across actors but
also across years. Furthermore, while turnover is observed,
it rarely occurs along the identified term lengths, again,
occurring variably across actors and positions. A twenty-first
actor, the staff liaison, is habitually present at the meeting,
and, thus, is also included in the analysis. While the indi­
vidual actors holding each of these positions might change
over the eight-year study period, the positions themselves
remain consistent. Finally, the mandate calls for the coor­
dination of all members to achieve the mandated goals of
the council. The information provided above aligns closely
with Emerson and Nabatchi’s (2015) definition of an ex­
ternally directed collaborative governance regime, as the
venue is appointed by legislation establishing the structure
and stakeholders to be included. Furthermore, while ambig­
uous, the mandate also defines the purpose of the council
(see mandated charge in Table 1) as well as its externally
identified strategy for changing—that is, advising state gov­
ernment and agencies.
At the end of each year, the council was mandated to
construct a report to the governor’s office. In this report,
the council outlined its activities over the prior year, as
well as identified three to six annual objectives for the up­
coming year. The annual objectives were established inter­
nally by the council itself and offered specific items within
the broad charge of the council. Furthermore, while some
of the objectives are observed multiple times, the objectives
broadly change from year to year, showing a variation in
policy interests being identified as council objectives (see
Supplementary Table A1).
Data collection
Three types of data were collected for the EJ council case.
First, the governing document mandating the creation of the
council, which identifies the number of council members and
identifies the required sectoral affiliation of each member
(e.g., community member, government representative), was
retrieved. Second, the annual reports for each year since the
council was established were collected from the council’s web­
site. These documents allowed for the connection of individual
names to each member position in each year. Furthermore,
the council’s “annual objectives” were coded in each of the
annual reports to identify the policy goals of the council in
each year. Finally, minutes for each council meeting since the
council was established were collected from the council web­
site. Each set of meeting minutes was coded to identify par­
ticipant attendance and the type of communication in which
participants are engaging, as well as the EJ topic, action, and
target associated with each statement (defined in more detail
in section ‘Data Processing and Coding’) being communicated.
The process for coding these documents is described system­
atically. Furthermore, the sample period was truncated to
2012 through 2019. While the council first started meeting
in 2011, the first meeting was in November, thus 2011 is not
represented by a full year of meetings. Similarly, given the
COVID-19 pandemic in 2020, the council did not meet on a
Table 1 Key attributes of the case.
Variables
Directives from the case’s mandate
Mandated charge
Mandated by State Legislature to advise State
government agencies on environmental jus­
tice and related community issues
Mandated structure
and process
Frequency of
meetings
At least six per year
Size of membership
20 members and 1 staff liaison
Guidance on co­
ordination among
council member
All members coordinate to achieve mandated
goals
Stakeholder
positions
12 appointed citizen members and 8 govern­
ment delegates


## Page 6

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
503
regular basis thereafter. The 2012 through 2019 period was
defined by regular meetings meaning changes in the number
of meetings a stakeholder attended from year to year are not
indicative of fewer meetings held by the council.
Meeting minute documents were originally collected in ei­
ther PDF or word processor format. The structure and prose
of the documents were consistent over time, which reduces
concerns that the results of this article are driven by changes
in reporting rather than changes in actions. Furthermore, the
documents reflected full sentences for each statement rather
than bulleted actions and or reports. The raw meeting minutes
were converted to a tabular format where each row represented
a single statement using R text mining and natural language
processing applications and through manual processing and
checking. A statement, in this study, is defined as an individual
sentence captured in the meeting minutes. Thus, larger sections
of the meeting minutes associated with a single individual were
subdivided into individual statements. This is done as an indi­
vidual might have differential sentiments based on the EJ topic,
action, and target associated with each statement. For example,
an individual might agree an EJ topic is important but disagree
with the policy instrument suggested to address it. These two
statements are stated by the same individual and linked to the
same statement recipient but are considered separately.
The following information was identified for each statement
extracted from the meeting minutes: (1) who made the state­
ment, (2) whether the statement conveyed a form of one-way
communication (i.e., announcement) or two-way communi­
cation (i.e., discussion with another person, asking of a ques­
tion, or answering of a question) (Nabatchi 2012), and (3)
who was the single recipient of the statement communicated
(if the statement was identified as reflecting two-way commu­
nication). When the speaker of the statement was not clear,
this assignment was left blank. 96.6% of statements coded for
the EJ council were coded to a participant. Table 2 exemplifies
how meeting minute data were arranged and coded to sup­
port downstream analysis thereof.
Data processing and coding
Once the meeting minutes were coded and manually checked, the
dataset was reentered into R to calculate the sentiment associ­
ated with each individual statement. Sentiment analysis broadly
captures qualities embedded in the language of statements. In
our study, we leverage sentiment analysis to examine the qual­
ities between (1) an actor’s affirmative or dissenting statements
toward a topic and (2) dyadic relationships that emerge as
an actor makes affirmative or dissenting statements toward
another actor. In this way, sentiment analysis is leveraged to
measure our operationalization of interest advancement and
interpersonal relationships. First, because this article is inter­
ested in conflict between council members and the network-
based methods, all announcements (i.e., instances of one-way
communication) are dropped from the dataset as they do not
represent a direct link between actors. Using the R package
sentimentr (Rinker 2017), the sentiment for each statement was
calculated. There are several advantages to using the sentimentr
package over other packages. Whereas other packages use a
basic dictionary lookup approach, counting the presence of
words in the observed sentence, sentimentr uses weighting
from valence shifters, which effectively reverse, increase, and
decrease the sentiment of the dictionary words (Naldi 2019;
Rinker 2017). Example sentences depicting and discussing the
effect of these valence shifters through the sentimentr package
are identified in Supplementary Appendix 1, along with the
scores of other prevailing sentiment dictionaries in R for com­
parison. The standard sentimentr dictionary was iteratively
refined to better fit the data sample—including the use of
acronyms and different names for the same entity (i.e., council
vs. EJ council). The scores calculated by the sentimentr package
are constrained between −1 and 1.
Finally, two-way communication statements identified
within the meeting minutes were further coded and/or analyzed
for type of conflict (conflict type), magnitude of conflict (con­
flict severity), and an integrated measure of conflict type and
conflict severity (conflict intensity) once sentiment scores were
calculated (Table 3). Conflict type is coded in trinary terms
(−1:0:1), denoting disagreement, neutrality, or agreement
with the referenced speaker in the meeting minutes. There is
a single referenced speaker, which is often the prior speaker.
However, at times, it is a different actor as statements can ref­
erence information and/or a statement that is noncontiguous
in the data table (i.e., actors returning to a point made earlier
in the conversation). Conflict severity is defined as the mag­
nitude of positive or negative sentiment as calculated using
sentimentr. The coding of conflict type directly interacts with
conflict severity resulting in the measure of conflict intensity.
Conflict intensity can be understood as the magnitude of sen­
timent calculated using sentimentr where the sign aligns with
the trinary coding of conflict, as it engages a single actor’s sen­
timent score for a single statement and their level of agreement
with the referenced speaker. Conflict severity is used for an­
nual objectives as it represents the positive, neutral, and neg­
ative sentiment value attached to the topic which the actor is
discussing. Returning to Table 2, one can see a practical ex­
ample of this coding where statements #3 and #5 are positive
in sentiment regarding the Act report and statements #4, #6,
and #7 are negative in sentiment toward the report. In contrast,
conflict intensity represents not the positive, neutral, and neg­
ative sentiment value attached to the topic but the relational
concord, neutrality, and conflict between actors. For example,
in statements #6 and #7, two linked actors make statements
negative in conflict severity (i.e., they have negative sentiment
toward the Act report), and thus statement #7 has a positive
conflict intensity (i.e., they concord in their negativity toward
the report) and a positive interpersonal relationship linkage.
Furthermore, the sign of conflict intensity is solely related to
conflict type. For example, in statement #6 conflict intensity
is negative as the speaker conflicts with the linked speaker;
whereas in statement #7 conflict intensity is positive as the
speaker is in concord with the linked speaker.
It is important to know that, given this operationalization,
conflict severity represents the measurement of affirmative
and dissenting statements made by an individual toward a
topic, whereas conflict intensity represents the measurement
of affirmation and dissent between two individuals. As a re­
sult, the dyadic nature of the conflict intensity is leveraged to
construct the networks discussed below. Because there is no
dyadic nature for conflict severity, it is evaluated in the study
as a count. Furthermore, in this article, positive conflict in­
tensity sentiment scores are indicative of interpersonal policy
concord between the statement speakers and referenced
speakers, whereas negative conflict intensity sentiment scores
are indicative of interpersonal policy conflict.
Each statement as well as the “council objectives” found in
the annual reports for each year were also coded to reflect the


## Page 7

504
Journal of Public Administration Research and Theory
Table 2 Example of the tabular formatting from the EJ council.
Type of statement
Statement coding
Participant
name
Other
participant
referenced
Statements
Announcements Discuss Ask Answer Environmental
justice topic
Action
Target
Conflict
type
Conflict
severity
Conflict
intensity
1
Part. #1
The Vice Chair of the commission gave an
overview of the Executive Summary of the
report introducing all of the stakeholders
involved in the report.
1
0
0
0
Regulation
Value Alignment
Council
0
0.000
0.000
2
Part. #2
Part. #1
asked why is this report coming to the com­
mission?
0
0
1
0
Regulation
Value Alignment
Council
0
0.000
0.000
3
Part. #1
Part. #2
said because stakeholders have ask the
council for advise and recommendations
on how to integrate environmental justice
and equity into their consideration for the
Act, and the report helps do that.
0
0
0
1
Regulation
Value Alignment
Council
0
0.200
0.000
4
Part. #2
Part. #1
said the report was way too long and lengthy
0
1
0
0
Regulation
Value Alignment
Council
−1
−0.472
−0.472
5
Part. #1
Part. #2
The strategies in the Act are good for the
community and could create about 37,000
jobs by 2020
0
1
0
0
Regulation
Value Alignment
Council
0
0.390
0.000
6
Part. #2
Part. #1
I disagree. The fact of the matter is jobs will
be created but how do we get them to the
folks that are systemically are under unem­
ployed and the people who transitioning
from extracted industries get other jobs.
0
1
0
0
Regulation
Value Alignment
Council
−1
−0.739
−0.739
7
Part. #3
Part. #2
These recommendations do not make sure
that we are not displacing people to really
creating opportunities in this new green
economy and it is only going to happen if
we are thoughtful and sit down with our
stakeholders and think about how that
could happen
0
1
0
0
Regulation
Value Alignment
Council
1
−0.377
0.377


## Page 8

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
505
main EJ topic addressed therein. The EJ topics coded for are
identified below. These topics were identified both deductively
through literature (Grafton et al. 2015; Ross et al. 2021) as
well as inductively through the coding process. The topics are:
Regulation: Statements reflecting discussion of policy and/
or programs being considered by the council or the state
or local governments.
Land use and planning: Statements reflecting discussion of
land use and development.
Justice: Statements reflecting discussion of issues such as
justice, inclusion, diversity, and/or Title VI of the Civil
Rights Act.2
Internal process: Statements reflecting discussion of council
aims, orientation, and process.
Health: Statements reflecting discussion of health and/or
health impacts related to environmental justice topics.
Environment: Statements reflecting the discussion of natural
resources or related conditions (e.g., water, waste, pollu­
tion, and climate change).
Engagement: Statements reflecting discussion of engaging
various stakeholders.
Statements were coded by two different coders and
differences in coding were reconciled. Where statements
appeared to address multiple EJ topics, a main topic was
selected for each statement based on the specific wording and
interpretation of the statement, as well as statement context.
Each statement and annual objective were also coded for
its action. Actions reflect specific activities of the council. Like
topics, actions were identified both deductively through lit­
erature (Ambrose et al. 2022; Siddiki et al. 2015) as well as
inductively through the coding process. The actions are:
Value alignment: Statements/objectives discussing the
members’ or councils’ orientation toward problem def­
inition and available actions.
Policy design: Statements/objectives discussing policy design.
Plan development: Statements/objectives discussing what
actions the council should take and how to take those
actions.
Membership: Statements/objectives discussing handling of
membership, member vacancies, and appointments.
Council logistics: Statements/objectives discussing the spe­
cific process of the council (e.g., date and time of next
meeting)
Information gathering: Statements/objectives referencing in­
formation gathering.
Information dissemination: Statements/objectives discussing
the dissemination of specific information (e.g., producing
an EJ 101 brief for legislators).
Engagement: Statements/objectives discussing outreach and
engagement activities to broad or specific stakeholder
groups.
Compliance:
Statements/objectives
discussing
compli­
ance and permitting of actions across both government
agencies as well as stakeholders (e.g., businesses and
local government).
Ally identification: Statements/objectives discussing allies
and advocates in the council’s mission and aims.
Advise: Statements/objectives discussing recommendations
but not advancing specific policy language.
Finally, each statement and annual objective was coded
based on the target of the policy. Those targets include the
state government (i.e., the governor and the governor’s
office), local government (city- or county-level), state
legislators, state agencies, businesses, academia, specific
communities or locales (i.e., communities and/or regions of
citizens), stakeholder groups (e.g., nonprofits and other or­
ganized groups), specific EJ advocates, and the council itself.
Variable construction and model specification
The processing and coding of the data resulted in the dif­
ferent types of data used in our co-evolution SAOM. Given
the many recent advancements in network modeling, there
are many advanced models to engage network data. SAOM
can evaluate the likely count of the outcome rather than the
structure of the network. We model the co-evolution of the
network and attendance, but we focus narrowly on the model
predicting the ordinal, behavioral outcome of attendance. The
output of the SAOM is reported in log-odds, identifying the
different odds of attendance between actors who are the same
except across the parameter of interest. Each variable of in­
terest is identified in Supplementary Table A2.
There are four independent variables of interest used to
model the factors identified in our theoretical framework. First
is the number of annual objective topics an individual discusses
in a year, as a means to evaluate their interest advancement
in the council. This variable captures positive conflict se­
verity (i.e., stated support, measured as the use of affirming
statements regarding the topic, for an annual objective), neu­
tral conflict severity (i.e., neutral information exchange re­
garding an annual objective), and negative conflict severity (i.e.,
stated opposition, measured as the use of dissenting statements
regarding the topic, for an annual objective). In practice, if the
annual report in a year presents five annual objectives with dis­
tinctive topics, actor i, in the same year, could have supported
two topics, opposed one, and did not discuss the other two;
Table 3 Key definitions and operationalizations.
Term
Definition
Operationalization
Conflict
type
The assessment of agreement,
neutrality, and disagreement
as coded in a two-way com­
munication statement linking
the speaker and a referenced
stakeholder
Trinary code denoting
disagreement (−1),
neutrality (0), or
agreement (1)
Conflict
severity
The magnitude of positive or
negative sentiment within
a two-way communication
statement
Assessed through a
refined sentimentr
model (continuous
from −1 to 1)
Conflict
intensity
The integration of both the con­
flict type and conflict severity
resulting in both the direction
of conflict (i.e., agreement,
neutrality, and disagreement)
and the magnitude of senti­
ment
Magnitude: Conflict
Severity (continuous
from −1 to 1)
Polarity: Conflict Type
(denoting disagree­
ment {−1}, neutrality
{0}, or agreement {1})
2Title VI of the Civil Rights Act of 1964, prohibits, for any program or
activity that receives Federal funds or other Federal financial assistance, dis­
crimination on the basis of race, color, or national origin (Civil Rights Act,
1964).


## Page 9

506
Journal of Public Administration Research and Theory
thus, their number of annual objectives topics discussed would
be equal to two for Positive Objectives, equal to zero for
Neutral Objectives, and equal to one for Negative Objectives.
Furthermore, we acknowledge that policy topics are often
made up of complex components, thus, an actor’s support and
opposition for the same topic can be observed. The measure of
interest advancement is oriented to the number of topics rather
than the number of comments to avoid potential endogeneity
given a positive correlation between increased attendance and
an increased number of comments.
Second, we include three network measures to represent
relationship effects in the collaboration in association with
Hypotheses 3 and 4: out-degree ties, in-degree ties, and an
Alter’s average of dyadic covariate weighted. First, actors can
experience communication relationships as either speakers
(out-degree ties) or receivers (in-degree ties). Furthermore, the
hypotheses also highlight the repeated-interaction dynamics
within a relationship. As such, we also examine the weighted
value of a communication relationship to explore the dif­
ferential dynamics of one-off interactions against repeated
interactions within a relationship.
The first network measure is the number of out-degree ties
of actor i calculated as,
snet
i1 (x, z) = zixi+ = zi
�
j
xi→j
where snet
i1 (x, z) is the relationship between behavior z, that
is, attendance, in the network of interest, zi is the ordinal at­
tendance of actor i, xi+ is a means-centered calculation of
out-degree ties for actor i, and xi→j represents all commu­
nication relationships from actor i to all other connected
actors j (Ripley et al. 2022). This represents all communica­
tion relationships where actor i is talking to another actor.
Relationships, in this article, are defined as connections or
ties between individuals. Thus, if any number of statements
are made from actor i to actors j, actor i has an out-degree
relationship with actor j. The second network measure is the
number of in-degree ties of actor i calculated as,
snet
i1 (x, z) = zixi+ = zi
�
j
xj→i
where all variables are the same as the out-degree calcula­
tion but xj→i represent all communication relationships con­
necting actors j to actor i (Ripley et al. 2022). This represents
all communication relationships where actor i is receiving
communication from other actors.
Because out-degree and in-degree measures calculate the
number of relationships, but not the number of interactions
within a relationship, we also calculate an Alter’s average of
dyadic covariate weighted by the number of interactions, cal­
culated by:
snet
i1 (x, z) = ziw i
where w i =
��
h xihwih
xi+
if xi+ > 0
0
if xi+ = 0
where all variables are the same as out-degree and
in-degree calculations and w i represents all communi­
cation relationships weighted by the average number of
interactions between actor i and all other actors h (Ripley
et al. 2022). In this article, interactions are defined as the
individual statements between actors within relationship.
Furthermore, Alter’s average of dyadic covariate measure
does not consider out-degree (i.e., xi→h) and in-degree (i.e.,
xh→i) separately; rather, it considers the covariate weight
(i.e., wih) associated with all communication relationship
ties (i.e., xih).
Across out-degree, in-degree, and Alter’s average of dy­
adic covariate calculations, conflict intensity is used as a
measure for interpersonal conflict, as it links the sentiment
of statements to the concord, neutrality, and conflict coded
in a two-way communication statement linking the speaker
and a referenced stakeholder. A positive, neutral, and nega­
tive conflict intensity networks were constructed for each of
the years included in this study. Practically, a directional tie in
the network represents a directional relationship between two
actors in the network, and the weight associated with that tie
represents the count of interactions observed in that relation­
ship over the given year. The number of statements within
each network across each year can be found in Supplementary
Table A3.
Finally, we include six control variables in the modeling
exercise. The first, average in-degree Alter’s attendance,
considers the likelihood of attendance given the rate of at­
tendance by those communicating with actor i (i.e., is an
actor more likely to attend given those talking to them at­
tend more frequently?). The second considers the behav­
ioral influence of the number of one-way communication
statements or Announcements actor i gives in a year. The
third considers differential attendance outcomes given the
sectors of the actors. The fourth and fifth variables iden­
tify the shape of the behavior function in SAOM models,
where a linear shape is the value of the attendance of actor
i and a quadratic shape is the effect of the attendance upon
itself such that the change in actor i’s attendance behavior
depends on actor i’s current attendance behavior (Ripley et
al. 2022).
The variables identified accord with the conceptual
framework of figure 2. In the top box, the number of pos­
itive objectives operationalizes Hypothesis 1, whereas
the negative objectives operationalizes Hypothesis 2. The
measured network dynamics across each of the positive com­
munication, neutral communication, and negative communi­
cation networks operationalizes the conflict hypotheses (e.g.,
Hypotheses 3 and 4). Finally, the number of announcements
and other actor attributes are added as controls. We use the
RSiena package in R (Ripley et al. 2022) to model the concep­
tual framework of figure 2.
Results
Model results and fit
First, Table 4 outlines the descriptive statistics for each of
the variables of interest. All variables are right-skewed, as
the mean is closer to zero, but larger value outliers exist. The
means and standard deviations are used later in this section
to depict realistic differences in annual objectives, communi­
cation relationships (i.e., degrees), and average interactions
across communication relationships (i.e., covariate weighted
ties). Finally, in-degree and out-degree are not reported in
Table 4, as they are equal in count and reported simply as the
number of degrees.


## Page 10

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
507
Table 5 depicts the result of the SAOM. All t-ratio values
across the model are, in absolute terms, less than 0.1, which is
considered an acceptable level of model convergence (Ripley
et al. 2022). As a stricter indicator of convergence (Ripley et
al. 2022), our SAOM results have an overall maximum con­
vergence ratio of 0.2465, where 0.25 is a threshold for ade­
quate convergence across the full model.
We present a representation of goodness of fit for the out­
come behavior, attendance, in figure 3 using the sienaGOF
function in RSiena (Ripley et al. 2022). The function
calculates goodness of fit statistic based on the actual at­
tendance values identified at the end of each time period
and simulated values given the results of the SAOM model
(Lospinoso and Snijders 2019; Ripley et al. 2022). The gray
solid lines denote the actual number of participants falling
into each of the attendance bins across the x-axis. The vi­
olin plots represent the results of the simulated attendance
given our calculated SAOM. Lastly, the function calculated
a P-value of .4481 suggesting an acceptable goodness of fit
across the SAOM model.
Announcements and peer effects
Before discussing our four hypotheses, results will be
presented for the number of announcements made as well as
the average in-degree alter. First, the estimate for the number
of announcements made by an individual in a given year is
statistically insignificant in its association with the number of
meetings attended. This suggests that the model is not driven
purely by more communication activity; thus, the type of com­
munication seems to be important for sustained attendance.
Unlike the number of announcements made by an in­
dividual, the average in-degree alter for both neutral and
negative communication networks proves to be statistically
significant. More specifically, neutral average in-degree alter
has a positive magnitude (i.e., β = .090, SE = 0.043) suggesting
that if the actors who share information with a stakeholder at­
tend more, the stakeholder is likely to attend council meetings
more. In contrast, negative average in-degree alter has a neg­
ative magnitude (i.e., β = −.093, SE = 0.049) suggesting that
if the actors who make negative conflict statements toward
a stakeholder attend more, the stakeholder is likely to attend
Figure 2 Conceptual framework.
Table 4 Descriptive statistics.
Variables
Mean
SD
Min.
Max.
Attendance
3
2.717
0
10
Number of annual objectives supported (positive)
1.302
0.971
0
4
Number of annual objectives offering information (neutral)
1.186
0.998
0
4
Number of annual objectives opposed (negative)
0.593
0.726
0
2
Positive degrees
1.338
2.043
0
12
Positive weighted ties
1.641
1.224
1
9
Neutral degrees
1.346
2.079
0
11
Neutral weighted ties
2.405
2.578
1
20
Negative degrees
0.823
1.364
0
7
Negative weighted ties
1.589
1.380
1
10
Number of announcements
3.246
7.377
0
73
Note: Because there is a single in-degree recipient and out-degree sender for each tie, they are equal in count, thus simply the number of degrees is reported.


## Page 11

508
Journal of Public Administration Research and Theory
council meetings less. Finally, the positive average in-degree
alter’s estimate is not statistically significant.
Annual objectives
Figure 4 depicts the influence of the number of annual
objectives for which the participant engaged and the number
of meetings attended. Given the descriptive statistics, the
log-odds are calculated across one, three, and five objectives
to offer a realistic depiction of attendance outcomes. The
number of annual objectives supported (i.e., topics in which
they communicated positive conflict severity; top panel),
the number of annual objectives offered information (i.e.,
neutral conflict severity; middle panel), and the number of
annual objectives opposed (i.e., negative conflict severity;
bottom panel) are all statistically significant (see Table 5).
For stated support, one sees a decrease in attendance as
an actor supports more annual objectives (i.e., β = −.132,
SE = 0.059). In contrast, one sees an increase in attendance
given an increase in neutral information offered regarding an
annual objective (i.e., β = .204, SE = 0.071) and an increase
in stated opposition to an annual objective (i.e., β = .205,
SE = 0.087).
Relationships and interactions
There are mixed results across the significance of the
out-degree relationships (i.e., where the actor is making
statements), in-degree relationships (i.e., where the actor
is receiving statements), and Alter’s average of the dyadic
covariate (i.e., average number of interactions per relation­
ship) estimates across the positive, neutral, and negative
communication networks. For the neutral communication
network, none of the estimates prove to be statistically sig­
nificant, and, thus, are not further discussed below. For the
positive communication network, one can see the in-degree
relationship estimate is statistically significant and negative
in magnitude (i.e., β = −.026, SE = 0.014); whereas the esti­
mate for the average number of interactions per positive rela­
tionship is statistically significant but positive (i.e., β = .196,
SE = 0.042). Furthermore, the estimate for out-degree rela­
tionship is not statistically significant in the positive commu­
nication network (i.e., β = .004, SE = 0.054). This suggests,
for the positive communication network, relationships where
actors receive statements are influential but relationships
where they make statements are not. While the esti­
mate for the average number of interactions per negative
Table 5 Stochastic actor-oriented model results.
Variables
Estimate
P-value
t-ratio
Rate (period 1)
17.149*
.018
−0.007
Rate (period 2)
10.687***
~.000
0.065
Rate (period 3)
23.003*
.022
0.019
Rate (period 4)
60.697**
.008
−0.010
Rate (period 5)
21.464***
~.000
0.026
Rate (period 6)
8.238***
~.000
−0.029
Linear shape
−0.119*
.018
0.004
Quadratic shape
−0.177*
.035
−0.016
Number of annual objectives supported (positive)
−0.132*
.012
0.032
Number of annual objectives offering information (neutral)
0.204***
.002
0.043
Number of annual objectives opposed (negative)
0.205**
.009
−0.006
Positive in-degree (spoken communication relationships)
−0.026*
.029
−0.011
Positive out-degree (received communication relationships)
0.004
.468
0.001
Positive weighted ties (count of statements)
0.194***
~.000
−0.026
Neutral in-degree (spoken communication relationships)
−0.001
.481
−0.005
Neutral out-degree (received communication relationships)
−0.044
.082
0.003
Neutral weighted ties (count of statements)
−0.028
.234
−0.016
Negative in-degree (spoken communication relationships)
0.001
.493
0.007
Negative out-degree (received communication relationships)
0.134**
.008
−0.014
Negative weighted ties (count of statements)
−0.227***
~.000
−0.033
Positive average in-degree Alter
0.056
~.000
0.015
Neutral average in-degree Alter
0.090*
.234
−0.056
Negative average in-degree Alter
−0.093*
~.000
−0.046
Number of announcements
−0.002
.378
−0.006
Agency delegates (DEL)
0.229***
.003
−0.021
Turn over
−0.026
.423
−0.010
Overall maximum convergence ratio
0.2465
Note: Total of 5,383 iteration steps.
*P-values < .05,
**P-values < .01,
***P-values < .001.


## Page 12

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
509
relationship is also statistically significant (i.e., β = −.227,
SE = 0.059), in the negative communication network out-
degree relationships are statistically significant (i.e., β = .134,
SE = 0.056) and in-degree relationships are statistically in­
significant (i.e., β = .001, SE = 0.042). Thus, for the negative
communication network, relationships where actors receive
statements are not influential but relationships where they
make statements are.
Because the number of individuals an actor talks to (i.e.,
out-degree), the number of individuals that talk to the actor
(i.e., in-degree), and the average number of statements across
those relationships (i.e., Alter’s average of dyadic covariates)
are interrelated estimates, each line in figure 5 represents
three individual variables. First, OD# identifies the number of
out-degree relationships (i.e., relationships where the actor is
speaking); ID# identifies the number of in-degree relationships
(i.e., relationships where the actor is receiving); and W#
identifies the weighted covariate for average interactions
(i.e., the average number of repeated interactions across the
identified relationships). Thus, the solid black line in the posi­
tive communication network figure can be interpreted as such:
an actor who has one relationship where they are stating posi­
tive communication, one relationship where they are receiving
positive communication, and, across these relationships, they
average three interactions per relationship.
To emphasize the estimated differences in single-interaction
relationships (i.e., W = 1) and repeated-interaction relationships
(i.e., W = 3) in figure 5, single-interaction relationships are gray
lines, whereas repeated-interaction relationships are black
lines. The variation across these variables was selected to offer
realistic variation as identified in Table 4. Furthermore, since
the estimate for in-degree relationships is statistically signifi­
cant and the estimate for out-degree relationships is statisti­
cally insignificant in the positive communication network, only
in-degree relationship values (i.e., ID#) vary. Similarly, only
out-degree relationship values (i.e., OD#) vary for the negative
communication network.
In the top panel of figure 5, one sees a smaller variation in
the difference across single-interaction relationship estimates
for the positive communication network. While small in mag­
nitude, the attendance decreases as the actor increases in
single-interaction-in-degree relationships. In contrast, as re­
peated interactions in the positive communication network
increases, attendance increases.
Depicted in the bottom panel of figure 5, variation is
estimated in the negative communication model across both
the single-interaction relationship and repeated-interaction
relationship estimates. First, there is little difference between
few single-interaction relationships (i.e., OD1_ID1_W1) and
few repeated-interaction relationships (i.e., OD1_ID1_W3).
This suggests actors engaging in few negative relationships—
single-interaction or repeated—are expected to attend a
similar number of meetings in the following year. Single-
interaction relationships move right as they increase, whereas
repeated-interaction relationships move to the left. Stated
differently, as actors have many relationships with one neg­
ative statement, they are more likely to attend more meetings
the following year; whereas actors within many relationships
with many negative statements are more likely to attend fewer
meetings in the following year.
Discussion
How do positive statements toward annual
objectives influence attendance?
Interest advancement is assumed to be a salient factor within
collective action settings, such as collaborative governance
Figure 3 Goodness of fit for attendance. Note: Gray solid lines denote the actual number of participants and violin plots display the results of the
simulated attendance from the calculated SAOM.


## Page 13

510
Journal of Public Administration Research and Theory
arrangements (Emerson and Nabatchi 2015; Lubell 2013).
Whether the decision is deemed rational or boundedly ra­
tional, actors have limited tangible resources (e.g., money
and staff) and intangible resources (e.g., time and effort) and
must decide how to allocate those resources. Hypothesis 1a
suggests that actors will remain in a collaborative govern­
ance arrangement if they see initiatives they support being
advanced therein. In the case of Hypothesis 1b, when actors
see initiatives they support not being advanced by the council,
they will attend less frequently.
The top panel of figure 4 is a representation of the log-odds
results which estimate the association between the number of
annual objective topics for which an actor made statements of
support in a year and the number of meetings they attended
(Table 5). One sees a decrease in meetings attended given an
increase in supported topics making it into the annual objec­
tive (i.e., β = −.132, SE = 0.059). In practical terms, this means
that as an actor moves from supporting one annual objective
to three annual objectives, they are expected to attend 23.2%
fewer meetings (i.e., roughly 2 less meetings per year), holding
all other factors constant. As such, the result suggests an op­
posite influence on attendance compared to that expected in
Hypotheses 1a and 1b.
Furthermore, the results suggest actors come less frequently
when their topics are represented in the annual objectives of the
council. While this result might be counter-intuitive to the in­
terest achievement hypothesis as originally presented, the out­
come may still be reflective of an individual actor’s cost–benefit
estimate via a free-rider problem. As Olsen (1965) identifies,
and Ostrom (2009) elaborates, actors are motivated to re­
ceive goods without expending resources. Thus, if the good
(i.e., supported interests) will be provided without expending
resources (i.e., attending), it is in the actor’s best interest to at­
tend less frequently. This idea is seen elsewhere in collaborative
governance literature; namely through the notion of core and
peripheral members (Carboni et al. 2017; Koski et al. 2018;
Weible 2008). While core members, who have a dedicated
understanding of the council’s purpose, possess political and
relational skills, and engage consistently (Crosby and Bryson
2005; Koski et al. 2018; Weible 2008), the literature suggests
peripheral members selectively choose to engage (Weible 2008;
Zafonte and Sabatier 2004). In this way, if the interests of pe­
ripheral members overlap with those of core members who are
Figure 4 Influence of the number of annual objectives in which the
participant engaged on attendance.
Figure 5 Positive and negative influence of relationships and interactions
on attendance. Note: OD# identifies the number of out-degree
relationships; ID# identifies the number of in-degree relationships; and
W# identifies the weigh covariate for average interactions across the
identified tie relationships. Lines: Single-interaction relationships are gray
lines and repeated-interaction relationships are black lines.


## Page 14

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
511
already translating their interests into annual objectives, the
cost–benefit decision is for the peripheral member to become a
free-rider and not attend future meetings.
How do negative statements toward annual
objectives influence attendance?
Hypothesis 2 hinges on the notion that an actor will be spurred
to attend more meetings in the following year if they oppose
a topic which makes it into the annual objectives (Sabatier et
al. 1987; Weible 2008; Weible, Siddiki and Pierce 2011). In
the bottom panel of figure 4, we see support for this hypoth­
esis. As the representation of the estimated log-odds shows,
one sees the number of meetings attended in the following
year increase given the increase in opposing topics making
it into the annual objective (i.e., β = .205, SE = 0.087). This
represents a 50.7% increase in meetings attended in the fol­
lowing year (i.e., roughly 4 meetings per year) when an actor
offers stated opposition to three annual objectives compared
to an actor who offers opposition to one annual objective,
all else held equal. As such, this result offers support for
Hypothesis 2.
How does interpersonal conflict influence
attendance?
While policy process scholars have called for better
representations of the mechanism for and outcomes of con­
flict in the policymaking process (Weible and Heikkila 2017),
there currently is a theoretical vacuum specifically regarding
conflict as current policy process theories and frameworks
treat conflict as a background concept, detached from its
sources, and measured indirectly as political mobilization,
political activities, or competing values (Weible and Heikkila
2017). Leveraging Pondy’s (1967) notions of actor conflict
within an organization and through Hypothesis 3, we bring
conflict amongst collaborative actors to the fore, attaching
conflict directly to the sender and receiver of communication,
and directly measuring how conflict associates with attend­
ance in the venue.
For the negative communication network, the estimates
in Table 5 suggest that only out-degree relationships (i.e.,
β = .134, SE = 0.056) and not in-degree relationships (i.e.,
β = .001, SE = 0.042) are associated with changes in attend­
ance, as the estimate for in-degree relationships effectively
suggests a null relationship to attendance in the following
year. This suggests that conflictual statements made by actors
are more salient toward future attendance than statements
received. The associated log-odds representation for the neg­
ative communication network results in the bottom panel of
figure 5 suggest interesting trends for both single-interaction
relationships and repeated-interaction relationships (nega­
tive weighted ties = −0.227, SE = 0.059). More specifically,
as negative single-interaction relationships increase, attend­
ance is estimated to increase, while attendance is expected
to decrease when negative repeated-interaction relationships
increase. As an illustrative example, given two actors who
have five negative out-degree relationships, the actor en­
gaging in single-interaction relationships is expected to at­
tend just under seven meetings, whereas an actor engaging
in repeated-interaction relationships is expected to attend
just over one meeting, ceteris paribus.
These results broadly support Hypothesis 3 since the results
identify the association between different types of conflict
and attendance. The single-interaction case might be seen as
movements from conflict equilibrium to disequilibrium, and
back to equilibrium. In contrast, the repeated-interaction
cases might be seen as chronic conflict cases. Our results sug­
gest short spells of conflict are associated with increased at­
tendance, whereas chronic conflict is associated with large
decreases in the number of council meetings a stakeholder
attends.
How does interpersonal concord influence
attendance?
Repeated interactions are a hallmark of Ostrom’s (2009)
model of individuals overcoming collective action issues, and
are the theoretical root for Hypothesis 4. In contrast to the
negative communication network, the positive communica­
tion network estimates suggest in-degree relationships (i.e.,
β= −.026, SE = 0.014) and not out-degree relationships (i.e.,
β = .004, SE = 0.054) are associated with changes in attend­
ance. Furthermore, the associated log-odds representations in
the top panel of figure 5 suggest different association trends
for single-interaction relationships and repeated-interaction
relationships. While there is a smaller variation in attendance
for single-interaction relationships, the results depict decreases
in meetings attended as the number of single-interaction-in-
degree relationships increases. In contrast, as actors engage in
more repeated-interaction relationships the results show the
likelihood of meetings attended increases (positive weighted
ties = 0.196, SE = 0.042). Thus, given two actors who have
five positive in-degree relationships, the actor engaging in
single-interaction relationships is expected to attend just
under two meetings, whereas an actor engaging in repeated-
interaction relationships is expected to attend just under six
meetings, ceteris paribus.
This suggests there is value in not only the number of pos­
itive relationships but in the repetitiveness of interactions
within relationships, as repeated-positive-interactions prove
to be salient for increased attendance. While case studies often
identify face-to-face dialogue as an important mechanism
for successful collaboration (Ansell and Gash 2008; Ostrom
2009), our results suggest repeated, positive interactions
through face-to-face dialogue are associated with more com­
mitted attendance when analyzing the actor-level.
How do neutral associations and the attendance of
peers influence attendance?
In this article, we set out clear hypotheses for both positive
and negative statements but make no assertions regarding the
influence of neutral statements and the attendance of peers
on a stakeholder’s attendance. Yet, the results for neutral
statements linked to annual objectives as well as the estimates
regarding peer attendance in the neutral and negative com­
munication networks prove to be interesting, and, thus, they
are discussed below.
While not explicitly stated in the hypotheses, it is of note
that an increase in the number of annual objectives for which
an individual offered neutral information is estimated to
increase the number of meetings an actor attends (i.e., middle
panel figure 4). Lubell (2013) suggests actors participate in
policymaking venues and form networks to gain key polit­
ical resources such as political advancements as well as in­
formation (Berardo and Scholz 2010). In subsequent work,
he and colleagues argue learning takes place when actors


## Page 15

512
Journal of Public Administration Research and Theory
can effectively communicate a range of new information
(Berardo and Lubell 2019; Bodin 2017) leading to a better
understanding of the problem as well as how other actors
are thinking about the problem (Berardo and Lubell 2019).
While we do not measure the level of learning in this study,
our results suggest sharing information regarding a topic that
makes it into the annual objectives is more salient to attend­
ance than supporting the topic. Free-riders may be able to
achieve similar political advances without frequent attend­
ance, but it is less likely they can achieve similar levels of in­
formation exchange without frequent attendance.
Furthermore, the attendance of peers who speak to a stake­
holder is statistically significant in the neutral communication
network (i.e., β = .090, SE = 0.043) and the negative com­
munication network (i.e., β= −.093, SE = 0.049). One might
expect the logic for the neutral communication network to
supplement the argument made in the last paragraph—there
must be other stakeholders from whom to receive information.
Thus, the results from our model suggest if actors from whom
a stakeholder receives information attend more meetings, the
stakeholder is more likely to attend more meetings as well.
Finally, while the estimate for in-degree relationships did not
prove to be statistically significant in the negative communi­
cation network, if the actor who makes a negative statement
toward a stakeholder attends a greater number of meetings,
the stakeholder is expected to attend fewer meetings. While
more research is needed, this statistically significant estimate
suggests a very specific dynamic in the venue. Particularly,
there is a quality to who is making negative statements. If core
members who are attending many meetings in a year make
a negative comment to a stakeholder, this is more impactful
to a stakeholder’s attendance than a negative statement from
a peripheral member attending less often. This suggests not
only how many negative interactions but from whom the
interactions are coming is important to future attendance.
Conclusion
This article contributes to research on collaborative govern­
ance through an examination of individual dynamics associ­
ated with sustained engagement in collaborative venues. While
other past work has examined the evolution of collaborations
(Imperial et al. 2016; Siddiki and Ambrose 2022; Ulibarri et
al. 2020; Weible et al. 2011), it has done so at the group-level.
Thus, this research contributes insights regarding the relation­
ship between individual experiences and sustained engage­
ment, with the understanding that a collaborative group’s
actions are directly related to those that are included/present
in the process (Cohen, March, and Olsen 1972; Howlett
2018; Kingdon 1995). Further, by drawing on computational
text analysis of meeting minute data, this article offers a gen­
eralizable methodological approach for assessing these dy­
namics and phenomena in collaborative governance but also
in collaborative policy making more broadly. The method­
ology used supports recent interest in developing a clearer
understanding and measurement of conflict in collaborative
arrangements engaged in policy formulation and implemen­
tation (Weible and Heikkila 2017; Yi et al. 2022).
While this article contributes to research and practice, the
authors acknowledge limitations to the study. First, the article
presents analysis from a single collaborative venue case. For
this reason, the generalizability of these results, while broadly
supporting the hypothesis posited from literature, needs to
be further tested. Furthermore, the relationships and interests
leveraged in this work only reflect the communication
captured in the meeting minutes of the collaboration. While
we acknowledge the likelihood of conversations and relation­
ship building outside of the meeting, the methods presented
here are seen as a robust representation given the available
data. Additionally, the authors acknowledge meeting minute
data is limited by its interpretation. Nuance associated with
sarcasm, perception, and the salience of specific topics for in­
dividual actors can be minimized in such methods. As such,
more work, including qualitative work, is needed to under­
stand the perceptions of actions and how different topics are
more or less salient to individual actors. Yet, substantial and
significant findings are observed.
When exploring interest advancement’s influence on con­
tinued attendance in collaborative venues, the results show
the advancement of one’s own interests is inversely associated
with attendance by actors compared to expectations. In other
words, in our study, as an actor moves from supporting one
topic to five topics reflected in collaborative annual objectives,
there is an expected decrease in that stakeholder’s likelihood
of attendance. In contrast, the results show the inclusion
of topics in the collaboration’s annual objective for which
the individual stated opposition is salient to attendance, as
increased oppositional annual topics is associated with a
greater likelihood of attendance. A similar trend is observed
for neutral statements. As actors have more annual objectives
for which they make neutral, informing statements, there is
a greater likelihood of attendance. While collaborative gov­
ernance literature often highlights the importance of interest
advancement in collaborative governance venues (Berardo
and Lubell 2019; Emerson and Nabatchi 2015; Lubell
2013), less work evaluates these links. Our results highlight
the importance of interest advancement but show that it is a
nuanced dynamic. More work is needed to evaluate if similar
associations across topic support and opposition are observed
in other venues as well as other domains implementing col­
laborative governance.
The second group of factors explored in this article
corresponds to interpersonal relationships observed in the
collaborative venue. Here, the results suggest the importance
of repeated-positive-interaction relationships in increasing the
likelihood of attendance, whereas single-positive-interaction
relationships were associated with decreases in attendance
likelihood. While the results show single-negative-interaction
relationships were associated with increases in attendance
likelihood, repeated-negative-interaction relationships were
associated with decreases in attendance likelihood, suggesting
the important difference between minimal and chronic con­
flict in collaborative venues. While there is a growing amount
of literature focusing on conflict in collaborative governance
(Karjalainen and Rapeli 2015; Koebele and Crow 2023;
Ulibarri 2023; Weible and Heikkila 2017), this study focuses
on the interpersonal relationships that emerge between ac­
tors, thus focusing on conflict and concord as it emerges at the
actor-level rather than measuring conflict at the group-level
of the council. Thus, we argue, understanding the behavior
of actors within the collaboration governance arrangement is
needed to better understand collaborative governance itself.
These results can help inform practitioners in two ways.
First, when interest advancement is seen as strategic decisions


## Page 16

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 4
513
associated with future attendance, it can be used by collabo­
rative governance conveners to think critically about the iden­
tification of annual objectives. More specifically, not only is
a broad representation of topics important, but also a broad
representation of the interests across actors. When a broad
set of actors support and oppose multiple annual objectives,
greater stability in the group might be expected; whereas, if
the annual objectives reflect the support of a narrow group
of actors, attendance might be more volatile in the following
year. Second, not all conflict is bad, but chronic conflict is. This
supports literature that suggests conflict and disagreement in
collaborative governance may be constructive (Emerson and
Nabatchi 2015; Heikkila and Gerlak 2013). Yet, our study
shows that chronic conflict is associated with the greatest de­
cline in attendance. These results, in conjunction with the dy­
adic measurement of interpersonal relationships in this study,
offer an important highlight for practitioners—the emer­
gence of chronic conflict specifically between two individuals
can be detrimental. While conflict is often measured at the
group-level in studies, we show that the relationships between
individuals matter. Thus, practitioners should give particular
interest to specific chronic relationships of conflict.
Supplementary material
Supplementary material is available at Journal of Public
Administration Research and Theory online.
Data Availability
The datasets were derived from sources in the public do­
main:
https://mde.maryland.gov/programs/crossmedia/
environmentaljustice/pages/cejsc.aspx
Funding
This research is supported by NSF-USDA Innovations at the
Nexus of Food, Energy, and Water Systems (INFEWS) [grant
# 2019-67019-30463].
References
Agranoff, R. 2006. “Inside Collaborative Networks: Ten lessons for
Public Managers.” Public Administration Review 66: 56–65.
Ambrose, G., S. Siddiki, and U Brady. 2022. “Collaborative Govern­
ance Design in Local Food Systems in the United States.” Policy
Design and Practice 5 (3): 362–83.
Ansell, C., and A Gash. 2008. “Collaborative Governance in Theory
and Practice.” Journal of Public Administration Research and
Theory 18 (4): 543–71.
Ansell, C., and J. Torfing, eds. 2022. Handbook on Theories of Govern­
ance. United Kingdom: Edward Elgar Publishing.
Berardo, R., and M Lubell. 2019. “The Ecology of Games as a Theory
of Polycentricity: Recent Advances and Future Challenges.” Policy
Studies Journal 47 (1): 6–26.
Berardo, R., and J. T. Scholz. 2010. Self‐organizing policy networks:
Risk, partner selection, and cooperation in estuaries. American
Journal of Political Science 54 (3): 632–49.
Bodin, Ö. 2017. “Collaborative Environmental Governance: Achieving
Collective Action In Social-Ecological Systems.” Science 357
(6352): eaan1114.
Bryson, J. M., B. C. Crosby, and M. M Stone. 2006. “The Design and
Implementation of Cross‐Sector Collaborations: Propositions from
the Literature.” Public Administration Review 66: 44–55.
Carboni, J. L., Siddiki, S., Koski, C., and Sadiq, A. A. 2017. “Using
Network Analysis to Identify Key Actors in Collaborative Gov­
ernance Processes.” Nonprofit Policy Forum 8 (2): 133–45. De
Gruyter.
Civil Rights Act, Title VI, 42 U.S.C. § 2000d et seq. 1964. https://www.
govinfo.gov/app/details/COMPS-342
Cohen, M. D., J. G. March, and J. P Olsen. 1972. “A Garbage can
Model of Organizational Choice.” Administrative Science Quar­
terly 17: 1–25.
Crosby, B. C, and J. M Bryson. 2005. “A Leadership Framework for
Cross-Sector Collaboration.” Public Management Review 7 (2):
177–201.
Emerson, K., and T. Nabatchi. 2015. Collaborative Governance
Regimes. Washington D.C., USA: Georgetown University Press.
Grafton, B., A. C. Perez, K. Hintzen, P. Mohai, S. Orvis, and R Hardin.
2015. “From the Michigan Coalition to Transnational Collabora­
tion: Interactive Research Methods for the Future of Environmental
Justice Research.” Politics, Groups, and Identities 3 (4): 684–91.
Heikkila, T., and A. K Gerlak. 2013. “Building a conceptual approach
to collective learning: Lessons for public policy scholars.” Policy
Studies Journal 41 (3): 484–512.
Howlett, M. 2018. “Matching Policy Tools and Their Targets: Beyond
Nudges and Utility Maximisation in Policy Design.” Policy & Pol­
itics 46 (1): 101–24.
Imperial, M. T., E. Johnston, M. Pruett‐Jones, K. Leong, and J Thomsen.
2016. “Sustaining the Useful Life of Network Governance: Life
Cycles and Developmental Challenges.” Frontiers in Ecology and
the Environment 14 (3): 135–44.
Innes, J. E., and D. E Booher. 2003. “Collaborative Policymaking: Gov­
ernance Through Dialogue.” In Deliberative Policy Analysis: Un­
derstanding Governance in the Network Society, edited by Hajer,
M. A., and H. Wagenaar 33–59. Cambridge, England: Cambridge
University Press.
Innes, J. E., and J. Gruber. 2005. “Planning styles in conflict: the metro­
politan transportation commission.” Journal of the American Plan­
ning Association 71 (2): 177–88.
Jones. 2001. Politics and the Architecture of Choice: Bounded Ration­
ality and Governance. University of Chicago Press.
Karjalainen, M., and L Rapeli. 2015. “Who will not deliberate? Attri­
tion in a multi-stage citizen deliberation experiment.” Quality &
Quantity 49: 407–22.
Kim, J., and S Siddiki. 2018. “Linking diversity of collaborative
policymaking venues with procedural justice perceptions: A study
of US marine aquaculture partnerships.” The American Review of
Public Administration 48 (2): 159–74.
Kingdon, J. W. 1995. Agendas, Alternatives, and Public Policies. 2nd.
NY: Haper Collins College Publisher.
Koebele, E. A., and D. A Crow. 2023. “Mitigating Conflict with Col­
laboration: Reaching Negotiated Agreement Amidst Belief Diver­
gence in Environmental Governance.” Policy Studies Journal 51 (2):
439–58.
Koski, C., S. Siddiki, A. A. Sadiq, and J Carboni. 2018. “Representa­
tion in Collaborative Governance: A Case Study of a Food Policy
Council.” The American Review of Public Administration 48 (4):
359–73.
Lospinoso, J., and T. A Snijders. 2019. “Goodness of Fit for Stochastic
actor-oriented models.” Methodological Innovations 12 (3):
2059799119884282.
Lubell, M. 2013. “Governing Institutional Complexity: The ecology of
games framework.” Policy studies journal 41 (3): 537–59.
Lubell, Henry, and McCoy. 2010. “Collaborative institutions in an
ecology of games.” American Journal of Political Science 54 (2):
287–300.
Nabatchi, T. 2012. “Putting the ‘public’ back in public values research:
Designing Participation to Identify and Respond to Values.” Public
Administration Review 72 (5): 699–708.
Naldi, M. 2019. “A Review of Sentiment Computation Methods with
R packages.” arXiv preprint arXiv 1901.08319.


## Page 17

514
Journal of Public Administration Research and Theory
Neblo, M. A., K. M. Esterling, R. P. Kennedy, D. M. Lazer, and A. E.
Sokhey. 2010. “Who wants to deliberate—and why?”. American
Political Science Review 104 (3): 566–83.
Ostrom, E. 2009. Understanding Institutional Diversity. Princeton,
USA: Princeton University Press.
Petersen, D., M. Minkler, V. B. Vasquez, and A. C Baden. 2006. “Com­
munity‐Based Participatory Research as a Tool for Policy Change:
A Case Study of the Southern California Environmental Justice
Collaborative.” Review of Policy Research 23 (2): 339–54.
Pondy, L. R. 1967. “Organizational Conflict: Concepts and Models.”
Administrative Science Quarterly 12: 296–320.
Resh, W., S. Siddiki, and W. R McConnell. 2014. “Does the network
centrality of government actors matter? Examining the Role of
Government Organizations in Aquaculture Partnerships.” Review
of Policy Research 31 (6): 584–609.
Rinker, T. 2017. “Package ‘Sentimentr.’” Retrieved 8: 31.
Ripley, R. M., Snijders, T. A., Boda, Z., Vörös, A., and Preciado, P.
(2022). Manual for RSiena. University of Oxford, Department of
Statistics, Nuffield College.
Ross, A., J. Van Alstine, M. Cotton, and L Middlemiss. 2021. “Delibera­
tive Democracy And Environmental Justice: Evaluating the Role of
Citizens’ Juries in Urban Climate Governance.” Local Environment
26 (12): 1512–31.
Sabatier, Focht, Lubell, Trachtenberg, and Vedlitz. eds. 2005. Swim­
ming Upstream: Collaborative Approaches to Watershed Manage­
ment. Cambridge, USA: MIT Press.
Sabatier, P., S. Hunter, and S McLaughlin. 1987. “The devil shift:
Perceptions and misperceptions of opponents.” Western Political
Quarterly 40 (3): 449–76.
Sabatier, P. A., and Weible, C. M. 2019. “The Advocacy Coali­
tion Framework: Innovations and Clarifications.” In Theories
of the Policy Process (2nd edition), 189–220. United Kingdom:
Routledge.
Schattschneider, E. E. 1960. The Semi-Sovereign People. New York,
USA: Rinehart and Holt.
Siddiki, S., and G Ambrose. 2023. “Evaluating Change in Representa­
tion and Coordination in Collaborative Governance Over Time: A
Study of Environmental Justice Councils.” Environmental Manage­
ment 71 (3): 620–40.
Siddiki, S. N., J. L. Carboni, C. Koski, and A. A Sadiq. 2015. “How Policy
Rules Shape the Structure and Performance of Collaborative Govern­
ance Arrangements.” Public Administration Review 75 (4): 536–47.
Simon, H. A. 2013. Administrative Behavior. New York, USA: Simon
and Schuster.
Ulbig, S. G., and C. L Funk. 1999. “Conflict Avoidance and Political
Participation.” Political Behavior 21: 265–82.
Ulibarri, N. 2023. “An Analysis of Micro-Scale Conflict in Collabora­
tive Governance.” Journal of Public Administration Research and
Theory 34 (2): 316–30.
Ulibarri, N., K. Emerson, M. T. Imperial, N. W. Jager, J. Newig, and E.
Weber. 2020. “How does collaborative governance evolve? Insights
from a medium-n case comparison.” Policy and Society 39 (4):
617–37.
United States Environmental Protection Agency. 2021. “Environmental
Justice.” https://www.epa.gov/environmentaljustice. Accessed Oc­
tober 27, 2021.
Weible, C. M. 2008. “Expert‐Based Information and Policy Subsystems:
A Review and Synthesis.” Policy Studies Journal 36 (4): 615–35.
Weible, C. M., and T Heikkila. 2017. “Policy Conflict Framework.”
Policy Sciences 50: 23–40.
Weible, C. M., P. A. Sabatier, H. C. Jenkins‐Smith, D. Nohrstedt, A. D.
Henry, and P DeLeon. 2011. “A Quarter Century of the Advocacy
Coalition Framework: An Introduction to the Special Issue.” Policy
Studies Journal 39 (3): 349–60.
Weible, C. M., S. N. Siddiki, and J. J Pierce. 2011. “Foes to Friends:
Changing Contexts and Changing Intergroup Perceptions.” Journal
of Comparative Policy Analysis: Research and Practice 13 (5):
499–525.
Yi, H., C. M. Weible, C. Chen, J. Kagan, J. Yordy, R. Berardo, and F.
Holm, 2022. “Measuring Policy Conflict and Concord.” Society &
Natural Resources 35 (6): 684–91.
Zafonte, M., and P. Sabatier. 2004. “Short‐Term Versus Long‐Term
Coalitions in the Policy Process: Automotive Pollution Control,
1963–1989.” Policy Studies Journal 32 (1): 75–107.


## Page 18

© 2024 Public Management Research Association. Copyright of Journal of Public
Administration Research & Theory is the property of Oxford University Press / USA and its
content may not be copied or emailed to multiple sites or posted to a listserv without the
copyright holder's express written permission. However, users may print, download, or email
articles for individual use.

