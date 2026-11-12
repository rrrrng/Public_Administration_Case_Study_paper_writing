# Agency consultation networks in environmental impact assessment

## Page 1

Journal of Public Administration Research and Theory, 2024, 34, 448–464
https://doi.org/10.1093/jopart/muae008
Advance access publication 29 March 2024
Article
Agency consultation networks in environmental impact
assessment
Jie Wang1, Nicola Ulibarri1, Tyler A. Scott2,
1Department of Urban Planning and Public Policy, University of California Irvine, Irvine, CA, USA
2Department of Environmental Science and Policy, University of California Davis, Davis, CA, USA
*Corresponding author: jiew35@uci.edu
Abstract
Government agencies practice interagency consultation to ensure that broader governmental activities align with their missions and objectives.
Consultation allows agencies not only to express their preferences and interests, but also may create administrative burden and procedural
delay. To explore the conditions under which agencies choose to review activities proposed by fellow government actors, this research focuses
on the California Environmental Quality Act (CEQA), California’s environmental impact assessment law. We conceptualize the CEQA review net­
work as a two-mode network, in which each review agency is linked to particular projects, and use two-mode exponential random graph models
to test a series of hypotheses about agency, project, and agency–project dyadic characteristics that shape the choice to review. We find that
projects located in sites with socioeconomically vulnerable residents or higher levels of background pollution garner more consultation. Agencies
are more likely to provide consultation when their expertise aligns with the project’s impact, and are less likely to review a project with agencies
that possess the same expertise. This research highlights variations underlying interagency consultation and helps understand how agencies
try to influence other agencies’ decisions.
Key words: interagency consultation, environmental impact assessment, two-mode ERGM, California Environmental Quality Act.
Introduction
Many government decisions involve consultation or review
by other agencies. For example, in the US, federal agencies
are required to consult the Secretaries of the Interior and
Commerce to protect endangered and threatened wild­
life and plants if their activities might harm these species.
Likewise, the Department of the Interior regularly hosts
consultations with Tribal Nations to gather suggestions to
address tribal issues. These consultations may entail inter­
action between agencies at the same level of government, or
they may bring together different levels of government in
multilevel arrangements. Interagency consultation is intended
to mitigate against costly implementation failures: external
agencies provide feedback to ensure that their interests are
considered and to raise potential concerns about the legality
and viability of the proposed action. At the same time, con­
sultation can raise transaction costs as working with others
can introduce conflict, face greater difficulty in reaching an
agreement, require more time to build trust, and lengthen the
decision-making process (Li and Chan 2009; Sagar 2007),
raising questions about the appropriate balance between ef­
fectiveness and efficiency.
Interagency consultation is especially prominent in infra­
structure and development processes that require environ­
mental impact assessment (EIA) (Kørnøv et al. 2022; Scott,
Ulibarri, and Scott 2020; Ulibarri, Cain, and Ajami 2017). In
EIA, agencies consult on prospective actions to be implemented
directly by another agency, as well as those to be implemented
by local governments, businesses, and nonprofits that require
government permits or funding. Ideally, the number and types
of agencies involved in the review should reflect the types of
decisions being made and the extent of their potential impact,
with agencies only reviewing those projects intersecting with
their mission area or geographic scope. In practice, however,
EIA and associated regulatory approvals are often decried as a
locus of administrative bloat, anti-development lawsuits, and
delay (Carlin and Farabee 2011; DeWitt 2022; Russo 2020),
with frequent calls to streamline or reform these processes
(Trnka and Ellis 2014).
Even though interagency consultation is a ­well-established
bureaucratic
process,
this
phenomenon
is
relatively
understudied.
Studies
of
agency
notice-and-comment
procedures typically focus on consultation with nongov­
ernmental organizations or citizens (i.e., stakeholder par­
ticipation). Interagency consultation shares many features
with stakeholder consultation, including the opportunity
to gain feedback on overlooked components of the deci­
sion and avoid unintended side effects (Nabatchi and
Leighninger 2015; Reed 2008). However, an inherent chal­
lenge in stakeholder consultation is the power differential.
Public participants often have less information or limited
authority over the decision being made (Arnstein 1969;
Slotterback and Lauria 2019). In contrast, interagency con­
sultation involves government organizations with defined
areas of authority and expertise. Particularly for agencies
operating at the same level of government, or for those with
statutory roles, the power differential between consultee and
consultant may play less of a role in shaping engagement.
Nonetheless, there is substantial variation in how frequently
agencies engage in consultation; in the dataset presented
© The Author(s) 2024. Published by Oxford University Press on behalf of the Public Management Research Association. All rights reserved. For commercial
re-use, please contact reprints@oup.com for reprints and translation rights for reprints. All other permissions can be obtained through our RightsLink
service via the Permissions link on the article page on our site—for further information please contact journals.permissions@oup.com.


## Page 2

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
449
here, some state agencies review a handful of proposed
projects, while others review several thousand over the
same period. Evaluating the factors underlying this varia­
tion is an initial step toward clarifying when consultation is
advancing government objectives versus adding to adminis­
trative burden and delay.
To expand our understanding of how and when in­
teragency consultation occurs, this article examines the
conditions under which agencies provide consultation
during EIA processes. We draw on data from environmental
reviews conducted under the California Environmental
Quality Act (CEQA), commonly recognized as one of the
most rigorous EIA processes globally (Glasson and Therivel
2019). We represent patterns of consultation under CEQA
as a two-mode (a.k.a. bipartite) network of projects and
consulting agencies. Reviewing agencies (mode one) are
linked to projects (mode two) proposed under CEQA. Two-
mode exponential random graph models (ERGMs) are em­
ployed to test a series of hypotheses about the consistency
and complexity of CEQA administrative review processes as
a function of the agency, project, and agency–project dyadic
characteristics.
This research makes two primary contributions. First, we
analyze the role of interagency (as opposed to civil sector)
consultation in shaping government decisions. Second, we use
a two-mode network analysis to simultaneously assess char­
acteristics at the project, organizational, and dyadic levels
(Schaefer et al. 2022); this graph model also accounts for
structural autocorrelation between individual agency–project
dyads (Cranmer and Desmarais 2016), reflecting the reality
that consultation choices do not occur in isolation.
Understanding consultation with public
agencies
Consultation in public management
Consultation with external actors, including private sectors,
nonprofits, and citizens, is a central theme in much litera­
ture on public participation and engagement. Consultation
introduces distinct knowledge and provides scientific exper­
tise to help decision-makers fill their information gaps (Li
and Chan 2009; Sagar 2007; Scott and Carter 2019). In ad­
dition, the use of consultation reflects a transition to neolib­
eral and decentralized governance, in which nongovernment
organizations are empowered to influence policy-making and
shape policy outcomes (Jupe and Funnell 2015). Generally,
consultation is framed as a dyadic relationship where the
government agency seeks input from outside actors that is
distinct from a fully collaborative relationship where both
parties share decision-making power (Ames and Keck 1997;
Arnstein 1969; Leksmono et al. 2010). Public participants
often have limited information or authority over the decision
being made (Arnstein 1969; Slotterback and Lauria 2019).
As a result, input provided by external actors is frequently
ignored without the support of the government agency,
raising concerns about the fairness and efficiency of this ap­
proach (Ames and Keck 1997; Leksmono et al. 2010; Scott
and Carter 2019).
In contrast, interagency consultation involves govern­
ment organizations with defined areas of authority and ex­
pertise. Particularly for agencies operating at the same level
of government, or for those with statutory roles, the power
differential between consultee and consultant may play less
of a role in shaping engagement. As such, it is time to revisit
the interagency consultation network and investigate under
what conditions statutory actors are more likely to provide
consultations.
Agency discretion
The inner workings of interagency consultation—when
agencies choose to solicit input from others, when to pro­
vide input (i.e., consult) on another agency’s question, and
how the agencies incorporate any feedback they receive—are
examples of agency discretion. Agency discretion refers to
the flexibility agencies have to use their own judgment when
interpreting and implementing public policies. How much
discretion agencies use can be viewed as the result of their
assessment of benefits from acting in accordance with their
own preferences and interests and the costs generated from
greater administrative burdens (Grandy and Hiatt 2020;
Huber and Shipan 2002). That assessment can be influenced
by characteristics of agencies (Robbins 2005), and historical,
organizational, and situational contexts (Holzer and Yang
2005).
Agencies’ use of discretion or flexibility does not happen
in isolation. The Ecology of Games (EoG) perspective argues
that agencies participate in multiple, simultaneous, and inter­
dependent policy games and their decisions made in one policy
game may generate externalities by shaping costs and benefits
for other games (Lubell 2013; Scott and Thomas 2017).
While most EoG literature focuses on policy forums and col­
laborative governance platforms, infrastructure projects can
be viewed similarly as an ongoing set of interorganizational
policy games. Public agencies must weigh the time, effort,
and payoffs of consulting on projects given agency mission,
spillover effects to other projects of concern, and opportunity
cost. Consultation actions on specific projects are influenced
by interactions across multiple consultation activities—and
consultation opportunities not taken. How much flexibility
agencies use should thus not be viewed on a project-by-
project basis but rather as a collective outcome of an ecology
of infrastructure games.
CEQA environmental review process
CEQA requires that government-led or -approved activities
be reviewed by a relevant government agency to determine
whether they will “cause either a direct physical change in
the environment or a reasonably foreseeable indirect change
in the environment” (Pub. Resources Code §21065). CEQA
applies to activities undertaken directly by a California state
agency and to activities that require discretionary approval
from a California state agency; the latter may be proposed
by other levels of government, businesses, or nonprofit or­
ganizations. If a project falls within statutory or categorical
exemptions from CEQA, it will receive a Notice of Exemption
(NOE), which means that it is not required to prepare envi­
ronmental review documents.1 For each nonexempt project,
a public agency that has primary authority over undertaking
or approving a project will be selected as the lead agency for
the CEQA process (Pub. Resources Code §21067); the lead
175.5% of projects in our original dataset captured from the CEQAnet re­
ceived NOE review decisions.


## Page 3

450
Journal of Public Administration Research and Theory
agency may represent a special district, local, state, tribal, or
federal government.
The lead agency will first conduct an Initial Study to de­
termine whether to prepare a negative declaration (ND), a
mitigated negative declaration (MND), or an environmental
impact report (EIR), based on the project’s potential envi­
ronmental impact. Specifically, ND decisions are assigned
to projects that will not produce significant impacts on the
environment. MND decisions are made toward projects that
have potential environmental impacts but can be mitigated
by taking feasible measures. Projects that have significant en­
vironmental impacts are required to prepare an EIR, which
describes and analyzes the significant environmental effects
of the project and proposes mitigation measures or project
alternatives to reduce the negative impacts on the environ­
ment to an insignificant level.
After selecting the appropriate level of review, the lead
agency prepares a draft of the relevant document for the
project and submits it and other required materials to the
State Clearinghouse (SCH). SCH then distributes draft en­
vironmental documents to state agencies, who have the op­
tion to review and comment on the documents during the
public comment period. The duration of the comment period
varies depending on the level of review. Aside from some unu­
sual situations, the public comment period should not be less
than forty-five days for an EIR or thirty days for an ND or
MND (Cal. Code Regs. Tit. 14, § 15105). If agencies submit
comments, the SCH publishes them on CEQAnet (https://
ceqanet.opr.ca.gov/) and forwards them to the lead agency,
which can take comments into consideration while deter­
mining whether to approve the project. See figure 1 for an
overview of the CEQA process.
This article does not focus on lead agencies. Instead, we
consider how and when other agencies choose to consult on
projects. Under CEQA, there are two types of agencies that
can review and comment on projects: responsible agencies and
state review agencies. Responsible agencies have discretionary
authority over projects; they provide consultation and advice
to the lead agency before or after determining the environ­
mental impacts of projects and can also be involved directly
in the project review process. For example, a project located
in or near a river, stream, or lake may require a Streambed
Alteration Agreement (FGC §1602), triggering the involve­
ment of the California Department of Fish and Game as a
responsible agency. Likewise, the Department of Cannabis
Control is a responsible agency for all projects associated with
cannabis businesses. State review agencies, on the other hand,
self-select whether to provide input on a draft CEQA docu­
ment. The lead agency can recommend agencies they would
like to review the project, and SCH notifies potentially inter­
ested agencies when a draft is posted. SCH maintains a list
of criteria for “what state agencies want to review” (refer to
CEQA Appendix C: Notice of Completion & Environmental
Document Transmittal), which includes agencies who may
have jurisdiction over or interest in a project.2 However, these
agencies are not mandated by CEQA to provide input, and
other noninvited agencies can voluntarily review a project if
they are interested. We assume there is no hierarchical rela­
tionship between state review agencies as they operate at the
same administrative level.
Theoretical framework and hypotheses
Our analysis focuses on the second type of review agencies—
state review agencies—as they can decide whether and when
to engage in reviews on a more voluntary basis, unlike re­
sponsible agencies. There are a variety of reasons why an
agency might choose to consult or not. Consultation presents
an opportunity to exert influence, advance goals, and pro­
tect bureaucratic turf. Consultation also takes time and ef­
fort and can positively or negatively associate the agency with
the project. Therefore, the CEQA review process provides a
useful case to understand agencies’ choices about with whom
and when to consult. In this section, we draw on the collab­
orative governance and network governance literature to
develop a series of hypotheses about the contexts in which
agencies are more likely to review a project proposed under
CEQA. Describing factors associated with agency consulta­
tion decisions is also of practical importance to evaluate the
effectiveness of the consultation process.
Characteristics of projects
The first set of attributes that may impact agencies’ involve­
ment in a consultation network relates to the characteristics
of projects under review. Problem severity is widely acknowl­
edged to affect the likelihood of actors working together
(Lubell et al. 2002; McGuire and Silvia 2010; Nohrstedt
2016). Actors are more likely to work with others when a
public problem is more salient and difficult, and when any
one agency lacks sufficient authority or capacity to address
the problem (Lubell et al. 2002).
In the context of EIA, a project’s difficulty relates to (1)
the type and extent of its environmental impacts and (2) the
socioenvironmental characteristics of the proposed location
(Shepard 2006; Wang et al. 2023). Regarding the former,
projects affecting a more diverse set of environmental re­
source areas may require more diverse forms of expertise to
evaluate those impacts, especially given that environmental
problems often interact in complex and hard-to-predict ways.
For instance, more agencies are likely to comment on a project
affecting both air and water quality relative to a project that
just affects water. Likewise, projects with more substantial en­
vironmental impacts—those that will significantly change en­
vironmental quality—may also generate more attention from
agencies, relative to a project that will result in little variation
from the status quo.
Hypothesis 1a: Projects with more diverse environmental
impacts are more likely to be reviewed by consulting
agencies.
Hypothesis 1b: Projects with more significant environ­
mental impacts are more likely to be reviewed by con­
sulting agencies.
The social and environmental complexity of the proposed lo­
cation also shapes organizational incentives (Ostrom 2007;
Yandle, Noonan, and Gazley 2016). In locations with large
populations or high amounts of existing infrastructure and
existing pollution, there are likely already more agencies
working in the area. Likewise, areas with socioeconomically
vulnerable populations may also have increased agency ac­
tivity due to high amounts of program and grant support
(Ojerio Ryan et al. 2011; Yandle, Noonan, and Gazley 2016).
Adding a new project would affect (and could complicate)
2Personal correspondence with CEQA official, September 8, 2022.


## Page 4

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
451
their work, so they are more likely to consult to protect their
interests and minimize decision externalities. In contrast, in
less complicated institutional settings (e.g., rural open space)
there may be one or two land use or wildlife agencies with
existing interests, but not the panoply of agencies involved in
urbanization and development.
Socioeconomic context might also affect a project’s public
visibility, indirectly triggering agencies to engage in a re­
view. Projects in more densely populated areas trigger more
public engagement (Cohen, Reichl, and Schmidthaler 2014;
Wüstenhagen, Wolsink, and Bürer 2007). As agencies may
feel pressure to show that they are operating in the public
interest, projects with more public engagement may draw
agencies into the review network.
Hypothesis 2a: Projects located in densely populated areas
are more likely to be reviewed by consulting agencies.
Hypothesis 2b: Projects located in areas with more existing
pollution are more likely to be reviewed by consulting
agencies.
Figure 1. Generalized CEQA Process Flow Chart. Shaded boxes indicate the periods when agencies can be involved in the CEQA review process with
bold letters indicating the review periods studied in this article. The bold arrows indicate the pathways for proposed projects that are considered in our
analysis.


## Page 5

452
Journal of Public Administration Research and Theory
Hypothesis 2c: Projects located in areas with socioeco­
nomically vulnerable populations are more likely to be
reviewed by consulting agencies.
The lead agency associated with the project may also shape the
agencies’ likelihood of participating in the consultation net­
work. In collaborative partnerships, the characteristics of the
lead organization shape potential participants’ motivations to
engage (Bryson, Crosby, and Stone 2006; Emerson and Gerlak
2014; Isett and Provan 2005). For instance, lead organizations
that provide access to resources, expertise, or reputational
benefits attract partners (Ansell and Gash 2012; Isett and
Provan 2005; Maor, Sulitzeanu-Kenan, and Balmas 2023).
In the context of CEQA, however, the reviewing agency is
unlikely to receive instrumental gains from the lead agency.
Thus, they may instead consider whether they expect the lead
agency to take their comments into account when deciding
whether to review. After receiving comments from state review
agencies, the lead agency considers the comments and makes a
final decision about whether to carry out or approve a project.
Therefore, when deciding whether to review a project, we ex­
pect that agencies weigh the probability that their comments
will receive due consideration by the lead agency.
In coordination arrangements, actors who are politically
superior have more bargaining power to determine how costs
and benefits associated with the partnership are distributed
across actors (Gallemore et al. 2015; Hamilton, Lubell, and
Namaganda 2018). When the lead agency is at a local adminis­
trative level, state review agencies likely have more bargaining
power than when the lead agency is at an equal or higher
level. Voluntary consultation with a state agency carries the
shadow of coercion: a local government likely cannot simply
ignore the input of a more powerful state agency, but rather
faces the choice of dealing with this input now or later. Local
organizations also might need technical capabilities and issue
expertise offered by larger state agencies, and thus welcome
consultation. Taking these factors into consideration, we hy­
pothesize that agencies are more likely to review projects
whose lead agency is at a lower level.
Hypothesis 3: Projects whose lead agency is at a lower admin­
istrative level than the state are more likely to be reviewed.
Characteristics of review agencies
The second set of attributes potentially associated with the
choice to engage in an interagency consultation network are
the characteristics of the review agencies themselves. First, co­
ordination takes practice. Any past experience with collabo­
ration is a positive factor in fostering future collaborations
between agencies, even in instances when specific agencies
have not worked together (Monroe and Butler 2016); we ex­
pect these trends to impact coordination as well. Prior experi­
ence informs agencies of the resources and capabilities that are
needed to handle specific problems in the future (Nohrstedt
2016). On a granular level, past experience indicates that
an agency has employees experienced with reading and
commenting on technical environmental studies—and per­
haps even existing templates and boilerplate material that can
be redeployed (Scott, Marantz, and Ulibarri 2021).
Hypothesis 4: Agencies with a history of general consul­
tation experience are more likely to engage in future con­
sultation.
Processing information in a CEQA review and generating a
reply requires organizational learning to fulfill their adminis­
trative roles and expedite the review process. Organizations
learn when they incorporate direct experience, or the expe­
rience of others, into ongoing routines and practices (Levitt
and March 1988). Learning requires capacity—the organi­
zation must have the ability to process the experience and
enact change (Mahler 1997). In this case, that means devel­
oping routines for acting as a consulting agency, such as how
the organization should process externally prepared impact
assessments and provide feedback. Voluntary CEQA consul­
tation is also a proactive behavior—the agency is seeking to
shift or mitigate potential project impacts before they happen.
Public agencies with greater slack capacity—those having re­
sources in excess of demand (see Cohen, March, and Olsen
1972)—are better equipped to behave proactively and de­
vote specialized time and resources to learning (Moynihan
and Landuyt 2009). While organizational size is not a per­
fect proxy for organizational slack (e.g., Bowen 2002), gen­
erally speaking, we expect that larger agencies are better able
to have the necessary staff time, expertise, and supporting
resources to participate in a consultation network (Kosnik
2005; Ulibarri and Tao 2019).
Hypothesis 5: Larger agencies are more likely to engage in
consultation.
Dyadic characteristics
The final set of characteristics that may influence an agency’s
likelihood to engage in a consultation network is dyadic,
referring to relationships between a set of agencies or be­
tween an agency and a project. First, an agency is unlikely
to provide consultation if the project is not relevant to its
mission or area of expertise. The type of agencies that will
be involved in coordination networks also depends on how
project impacts intersect with review agencies’ interests. For
the consultation to be effective, there should be a match be­
tween the capability of a review agency and the project to be
reviewed. A good level of knowledge and experience should
be possessed by actors to play a significant role in the negoti­
ation and management of projects. For example, in the study
on the governance of urban water projects, Woldesenbet
(2020) finds that multistakeholder dialogue did not work well
when stakeholders involved did not have the experience or
expertise required to address water issues: actors without the
required expertise had less interest in being network members
as they had “no strong awareness of river concerns” (43). We
hypothesize that:
Hypothesis 6: Agencies are more likely to consult on
projects if their expertise aligns with the project’s impacts.
Second, many different areas of expertise can align with
project impacts. Due to the interdependencies among water,
land, energy, and other resources, it is nearly impossible to
see an environmental impact in isolation. Diverse knowledge
and skills from multiple agencies are necessary for estimating
the environmental impacts of projects and identifying
solutions to reduce or mitigate adverse impacts. An osten­
sible advantage of an agency consultation network is the
ability to synthesize actors’ different perspectives, expertise,
skills, and knowledge into unique resources (Vangen 2017;


## Page 6

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
453
Vangen and Huxham 2005). Different actors can provide
different perspectives and create opportunities for learning
(Baird et al. 2019; Osterblom and Bodin 2012). Therefore,
we expect that lead agencies are likely to encourage con­
sultation from review agencies with different purviews and
skill sets.
At the same time, for both lead and review agencies, consul­
tation with organizations with similar expertise is likely less
desirable. The potential value of information provided to the
lead agency by a like-minded commenter does less to offset
the transaction costs of review.3 This logic also extends to
reviewing agencies that fill similar roles. We expect that there
are diminishing marginal returns from additional reviews
provided by similar experts. Thus, lead agencies should be less
likely to solicit additional reviews when particular “slots” are
already filled, and reviewing agencies should be less willing to
provide reviews when another agency is already speaking to
the same issues.
Hypothesis 7: Agencies are less likely to review projects
with others who possess the same expertise.
Finally, we expect that review agencies experience a positive
economy of scale filling particular consultative roles on mul­
tiple projects. Specialization in tasks and services contributes
to the improvement of productivity and the facilitation of
learning (Narayanan, Balasubramanian, and Swaminathan
2009; Staats and Gino 2012). In the context of CEQA, the
review process can be seen as an efficient mass production
procedure if certain agencies are performing similar tasks
and reviewing similar projects. By reviewing similar projects,
agencies can adopt similar practices and even develop
standardized procedures to save time and effort. For example,
as agencies are likely to use shared texts between documents
(Scott, Marantz, and Ulibarri 2021), between-document boil­
erplate text can be more possible if they are reviewing similar
projects. In other words, the more agencies focus on homo­
geneous projects, the more efficient they become at fulfilling
the task of evaluating projects. Agencies’ preferences to re­
view similar projects also correspond to the theory of institu­
tional fit, which argues that governance arrangements should
align with the characteristics of environmental problems to
be addressed (Young 2002). By treating similar or intercon­
nected problems similarly, agencies can facilitate a feedback
loop between their reviewing activities and project outcomes
and achieve scale matching between social and ecological sys­
tems (Bodin 2017; Cumming, Cumming, and Redman 2006).
Therefore, we expect that:
Hypothesis 8: Agencies are more likely to review pairs of
projects that have the same impacts.
Figure 2 summarizes our main hypotheses with graph­
ical illustrations. In the figure, circles indicate state review
agencies and squares represent proposed projects.
Methodology
Data
Data on projects reviewed under CEQA were obtained from
the CEQAnet Web Portal. CEQAnet is the online public en­
vironmental database of the California State Clearinghouse
(SCH) and covers metadata on all CEQA documents
submitted to the SCH for CEQA review since 1990, including
project locations, date received, lead agencies, and state re­
view agencies. Our sample frame is projects submitted to the
SCH from 2011 to 2020. We focus on this time period as
socioeconomic and environmental data at the census tract
level are not systematically available prior to 2010. Our
observations are identified by a combination of SCH Number,
Received Time, and Review Level. SCH Number refers to the
unique identification number assigned by the SCH when a
lead agency submits draft CEQA documents; Received Time
is the date when environmental documents were received by
SCH; and Review Level indicates projects’ level of environ­
mental review. Duplicate observations were then removed.
We pair the CEQA metadata with socioeconomic and envi­
ronmental indicators at the census tract level to examine how
these indicators are associated with the formation of a review
network. These indicators include the American Community
Survey five-year estimates of tract population density and
(vulnerable) Population Characteristics and Pollution Burden
scores from the CalEnviroScreen tool.
After dropping projects whose attributes considered in our
network analysis are missing because of absent geolocation
data,4 we obtain a dataset that consists of seventy-two state
review agencies, 5,323 projects, and 64,123 agency–project
review dyads. This large-scale dataset helps overcome analyt­
ical challenges that often limit the study of interorganizational
collaboration and coordination (Ulibarri and Scott 2017).
See Table 1 for the basic properties of the CEQA review net­
work. On average, each state agency in our sample reviewed
891 projects between 2011 and 2020, and each project was
reviewed by twelve California state agencies.
Measurement
Project characteristics
We identify two sets of attributes at the project level that
are expected to determine the likelihood of state agencies
joining a consultation network: problem severity and the role
of the lead agency. We use two variables—the CEQA level
of review (Level of Review) and the number of project is­
sues associated with a project (Project Issues)—as proxies
for project severity. Projects with the most significant envi­
ronmental impacts are supposed to receive an EIR, whereas
projects whose impacts are not significant, or which can be
mitigated to nonsignificant, receive an ND or MND, respec­
tively. We expect that projects receiving an EIR should there­
fore attract the most attention from review agencies, followed
by MNDs (as the need for mitigation indicates some level of
complexity) and lastly NDs. We also expect that projects that
3One potential counterargument is that comments from agencies with sim­
ilar expertise might be seen as more valuable because of peer effects. For
instance, peer agencies might have a shared frame of reference and use sim­
ilar terminology. Agency employees might have shared membership in a
professional community. Bureaucratic officials care about their professional
standing and reputation and thus norms of professionalism have a great
deal of influence on agency behavior and decisions (Miller and Whitford
2016). In general, however, consultation processes are structured to high­
light points of divergence and not consensus—that is, the point is not for
the lead agency to be able to say “ten water agencies agree with our choice.”
Thus, we anticipate that while norms of professionalism certainly shape
how agencies analyze a project and the choices they make, these norms do
not strongly incentivize duplication in consultative roles.
4Project records with missing values were particularly concentrated in Los
Angeles County.


## Page 7

454
Journal of Public Administration Research and Theory
affect more social and environmental issues are more likely
to be reviewed by state agencies. In their CEQA application,
project proponents are required to indicate the types of po­
tential environmental and social impacts considered, termed
“project issues” on CEQAnet. Project issues captured from the
CEQAnet database follow multiple categorizations (CEQA
Appendix G: Environmental Checklist Form and Appendix
C: Notice of Completion & Environmental Document
Transmittal); these appendices changed multiple times during
the decade of observation. To ensure consistency across years
and reduce overlaps, we re-coded project issues in our sample
into twenty-four categories. On average, each CEQA project
is associated with 13.6 project issues.
Problem severity is also associated with project location. If
a project is located in a place already impacted by pollution
or other environmental harms, the new project’s cumulative
impact is greater. We use the Pollution Burden Score for the
census tracts where projects are located as the third indicator
of problem severity. CalEnviroScreen’s Pollution Burden
score aggregates a variety of environmental indicators, such
as air quality, hazardous materials, and groundwater contam­
ination (see Table 2 for the full list of pollution and contam­
inant sources). A tract with a higher Pollution Burden score
indicates more extant pollution; we expect that these tracts
are more likely to be impacted by proposed projects and
therefore reviewed by more state agencies.
We also include two socioeconomic indicators of location
complexity: the number of people per square mile by census
tract and the social vulnerability of a census tract. We used
the natural logarithm values of Population Density to make
it more normally distributed. The Population Vulnerability
refers to the Population Characteristics score captured from
CalEnviroScreen datasets, an index measure that combines
variables related to health status (e.g., asthma rates), educa­
tional attainment, housing burden, employment, and linguistic
isolation (OEHHA 2021). A high value of the Population
Vulnerability suggests that people living in this tract are more
vulnerable to environmental pollution.
To estimate the effects of projects’ leaders on the likeli­
hood of state agencies being involved in a certain project re­
view process, we include Lead Agency, a categorical variable
indicating the administrative level of the lead agency assigned
to each CEQA project. Importantly, the lead agencies are not
directly a part of the network; they exist only as a covariate
associated with the project. Different from the multiple state
review agencies for each project, only one lead agency is as­
sociated with a project and may represent governments at
any administrative level; in our dataset, the 5,323 projects
were proposed by 834 lead agencies. We categorized lead
agencies into eight types: tribal agencies, federal agencies,
Figure 2. Summary of attributes expected to influence reviewing activity. Circles represent agencies and squares represent projects. Black shading
indicates factor (node or edge) of interest.
Table 1. Basic properties of the two-mode review network.
Full
Number of the secondary node sets (projects)
5,323
Highest degree for the secondary node sets (projects)
27
Mean degree for the secondary node sets (projects)
12
Number of the primary node sets (agencies)
72
Highest degree for the primary node sets (agencies)
5,312
Mean degree for the primary node sets (agencies)
891
Number of Edges
64,123


## Page 8

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
455
state agencies, county agencies, city agencies, special districts,
nonprofit organizations, and joint power authorities. We then
coded lead agencies into two categories based on their admin­
istrative levels compared to state agencies: lead agencies at a
lower level than the state (counties, cities, special districts,
nonprofit organizations, and joint power authorities) and
those at the state or a higher level (state agencies, tribes,
and federal agencies). These two types of lead agencies ac­
count for 96.8% and 3.2% of those assigned to projects,
respectively.
Finally, the control variable Year is a factor variable to indi­
cate the year the project was submitted to CEQA for review.
Agency characteristics
We include two attributes at the agency level that can be as­
sociated with state agencies’ likelihood to be a member of a
review network. We indicate Past Experience by using the fre­
quency of state agencies consulting on projects in the decade
prior to our study (2001–2010). To proxy Agency Size, we
use the number of employees of state agencies in 2019, which
is a common indicator of organizational size (Kimberly
1976). Data on employee numbers were obtained from the
Government Compensation in California website (https://
publicpay.ca.gov/Reports/State/State.aspx). For the thirty-
four agencies (47%) whose employee data were not available
on this website, we found the best available estimate, either
directly from the agency website or from other agency reports,
for 2019 or as close as possible.
Dyadic characteristics
Along with the nodal agency and project attributes described
above, we also incorporate a set of dyadic characteristics. In a
network, a dyad is a pair of two nodes.
Issue Matching is a dyadic covariate to indicate whether en­
vironmental impacts associated with a project are within the
focus areas of the state review agency (Yes =1; No = 0). Our
dataset includes twenty-four types of environmental impacts
labeled for projects in CEQAnet (the Project Issues described
above) and thirteen types of agency focus areas (see Table A1
for the list of projects’ environmental impacts and agencies’
focus areas). The agency focus areas, based on CEQAnet im­
pact categories, were developed by reviewing each agency’s
website and mission. Two of the authors categorized the
agency focus areas separately, then discussed coding decisions
and revised to achieve consistency in our categorization.
For each agency–project relationship, we used grep() func­
tion in R to identify whether a vector of character strings
about environmental impacts contains characters of agency
focus. If the issue on which an agency focuses (partially or
exactly) matches with elements of the environmental impacts
Table 2. Variable definitions and data sources.
Variable names
Measurements
Data source
Project characteristics
Project issues
Number of project issues associated with one CEQA project
CEQAnet Database
Level of review
A categorical variable indicating whether a project received an ND, MND, or EIR
CEQAnet Database
Pollution burden
Index reflecting a census tract’s ozone and PM2.5 concentrations, diesel PM emissions, drinking
water contaminants, pesticide use, toxic releases from facilities, traffic density, cleanup sites,
impaired water bodies, groundwater threats, hazardous waste facilities and generators, solid
waste sites and facilities, and children’s lead risk from housing
CalEnviroScreen
2.0, 3.0, and 4.0
Population vulnera­
bility
Population characteristics score reflecting a census tract’s levels of asthma, cardiovascular disease,
low birth weight, educational attainment, housing-burdened low-income households, linguistic
isolation, poverty, and unemployment by census tract
CalEnviroScreen
2.0, 3.0, and 4.0
Population density
Residents per square mile by census tract
American Com­
munity Survey
5-year estimate
Lead agency
A binary variable indicating the administrative level of the lead agency: (1) local agencies (city,
county, special district, NGO, joint power authorities) or (2) state, tribal, or federal agencies
CEQAnet Database
Year
A factor variable to indicate the year when the project was proposed
CEQAnet Database
Agency characteristics
Past experience
An agency’s CEQA review count between 2001 and 2010
CEQAnet Database
Agency size
The number of employees
Government com­
pensation in
California
Dyadic characteristics
Issue matching
Whether environmental impacts associated with a project are within the focus areas of review
agencies
Compiled by the
authors
Knowledge similarity
The tendency for agencies with the same expertise to review the same project
Compiled by the
authors
Issue similarity
The tendency of projects with similar environmental impacts to be reviewed by the same agency
Compiled by the
authors
GW degree distri­
bution (centered on
projects)
Prevalence of agency consultations to cluster on certain projects
-
Network Density
Number of edges
-


## Page 9

456
Journal of Public Administration Research and Theory
associated with a project, a consultant tie is expected to be
formed between them.
We further include a homophily effect based on agency
focus areas for agencies to capture the prevalence of agencies
with the same expertise to consulting on the same project
(Knowledge Similarity).5 We coded state agencies’ focus area
into one of thirteen types: agriculture and forestry, air quality,
biological resources, coastal zone, cultural resources, eco­
nomics/jobs/social, hazards/hazardous materials, hydrology,
land use/planning, public services, transportation, utilities/
service systems/infrastructure, and water quality.
Likewise, to estimate the role of project similarity on
network formation, we include a homophily term based
on project issues in the two-mode network analysis (Issue
Similarity). We count two projects as having shared issues
when they have the exact same combination of project issues.
In our dataset, out of 5,323 projects, 3,504 (~65.8%) have
peers with the same number of issues associated with them. It
is expected that projects with the same combination of envi­
ronmental impacts are more likely to be reviewed by the same
state review agency as the latter has experience and even spe­
cialized skills in reviewing similar types of projects.
Autoregressive structural controls
In brief, an ERGM works by setting the observed graph as
the dependent variable, representing this graph using a set of
count statistics (e.g., the total number of ties or the number of
ties between agencies and projects that share an issue focus),
and then estimating the model by comparing the observed
graph to a distribution of simulated graphs that share sim­
ilar count statistics. In any network, ties are not distributed
completely at random. Endogenous structural terms are in­
corporated into ERGM specifications so as to develop real­
istic simulated graphs that provide a valid basis for testing
specific variables of interest. Inclusion and parameterization
of structural terms is determined iteratively by fitting different
specifications and seeing if: (1) the MCMC process will con­
verge on stable estimates (which means the model will pro­
duce consistent results and generate a stable distribution of
sample graphs and (2) if the graphs simulated by the model
bear sufficient structural resemblance to the observed graph.
There is no definitive set of structural controls for an
ERGM, but in general, most well-fitting ERGMs account
for overall tie density, tie clustering or dispersion, and triadic
closure (Snijders et al. 2006). In our bipartite model, there
can be no triangles (since projects cannot be connected to
projects and consultants cannot be connected to consultants);
we were able to achieve strong goodness-of-fit (see Appendix)
using structural controls that account for the overall density
of ties and skewness of the distribution of ties on projects.
Density is represented using the edges term; this term can
be interpreted as reflecting the baseline probability of any
agency to review any project (Wang et al. 2009). In a large
network graph, the total number of possible ties (# projects
* # of agencies) is very large, and so density is very low (see
results below). Geometrically weighted degree distribution on
projects (gwb2degree) controls for the prevalence of agency
consultations to cluster on certain projects. A negative esti­
mate reflects a graph where edges are more centralized on se­
lect nodes (Levy et al. 2016; Lubell and Robbins 2022)—that
is, a skewed distribution of consultation on select, “popular”
projects. However, in the results shown below the estimated
geometrically weighted degree term is positive and large in
magnitude, meaning that consultation ties are relatively
equally distributed across projects. In practical terms, this
means we do not see many projects that are popular and at­
tract a lot of additional consultations, nor many projects that
are unpopular and attract no consultations.
See Table 2 for the definition and measurement of variables
and their data sources and Table 3 for summary statistics.
Analysis
The underlying mechanism of the CEQA interagency co­
ordination network is that agencies are linked not through
relationships with one another but by participating in the same
action, project, or institution. Therefore, we represent agency
consultation patterns as a two-mode network, with agencies
linked to projects and no direct agency or project links. Two-
mode networks are used to represent the association between
actors and activities, groups, or events with which the ac­
tors are affiliated (Jasny and Lubell 2015; Snijders, Lomi,
and Torló 2013). Network studies commonly convert two-
mode networks into one-mode networks by using the pro­
jection method, which has been questioned for overlooking
the effects of connecting entities (e.g., projects) on network
formation and leading to biased results (Borgatti and Everett
1997; Jasny and Lubell 2015; Opsahl 2013). Therefore, in this
article, we keep the original bipartite structure of interagency
consultation networks, with state review agencies acting as
the primary set of nodes and CEQA projects acting as a sec­
ondary set. Analyzing these data as a two-mode network
allows us to simultaneously incorporate project and organi­
zational attributes and focus on dyadic relationships between
agencies and individual projects. Analysis was conducted
using the statnet package in R (Handcock et al. 2008).
Results
In this section, we use a two-mode ERGM to test hypotheses
concerning how we expect different agencies to consult on
different projects. Coefficients in the model can be interpreted
as the change in the log-odds likelihood of a tie formation
between agencies and projects given a unit change in an at­
tribute, all else being equal (Goodreau et al. 2008). As shown
in Table 4, we include a set of variables at the project level to
indicate problem severity, agency size, and past experience at
the agency level, and three dyadic attributes expected to im­
pact agencies’ involvement in a consultation network.6 Two
endogenous parameters described above—the GW (project)
degree7 and network density—are also included to improve
model fit. Figure A1 in the Appendix shows the results of
goodness-of-fit and confirms the fit of our two-mode ERGM
5Note that while we discuss this feature as dyadic characteristic, because it
refers to an attribute of a pair of organizations, in a bipartite ERGM there
are no intramode (i.e., organization to organization) ties. Thus, as shown in
figure 2, the graph structure used to test Hypothesis 7 is actually a two-path
counting the number of cases where organizations with the same expertise
both consult on the same project. Likewise, the structure used to test for
issue matching (H6, figure 2), is also a two path where two projects are
connected to a given agency.
6Appendix Table A3 shows a restricted specification model without the
three dyadic characteristics; adding the dyadic attributes improves model fit
(lower AIC and BIC scores and higher log-likelihood value).
7We set the decay parameter for geometrically weighted project at 0.6 to
optimize model fit.


## Page 10

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
457
model. We did not find evidence of severe multicollinearity in
this ERGM model (see Duxbury 2018 and Table A2).
At the project level, the positive effect of social and envi­
ronmental complexity is partially supported. Agencies’ deci­
sion to consult is significantly associated with environmental
burdens facing projects’ locations: projects located in census
tracts facing greater environmental burdens are more likely
to be reviewed by state agencies (H2b). Being in a tract that
is more vulnerable to environmental pollution also increases
the probability of state agencies’ consultation (H2c). These
tracts are more likely to be impacted by proposed projects
and therefore reviewed by more state agencies. However, we
do not find a significant effect of census tracts’ population
density on driving agencies to consult on a project (H2a).
There are mixed results regarding the effects of project se­
verity. The project’s level of review shapes reviewing behavior,
in that projects receiving an EIR (which indicates more sig­
nificant environmental impacts) attract more attention from
review agencies compared to those receiving NDs (H1b). We
observed no difference in agencies’ tendency to consult on
projects receiving an MND versus an ND.
When a dyadic matching term for project issue and agency
expertise is included (model 1, Table 4), there is a statistically
significant, but small in substantive terms, negative relation­
ship between project issue count and the number of consulting
agencies (H1a). The odds of a state agency reviewing a CEQA
project decrease by 2% (exp(−0.024) = 0.98) if the project
is related to one additional environmental issue. When this
matching term is excluded, project issue count is positively as­
sociated with the number of consulting agencies (see Model
A1 in Table A3). We take this to indicate that complex projects
have more consultation simply because they create a greater
number of specific consulting roles that agencies can fill (e.g.,
a water agency, land use agency, air quality agency, etc.). But,
beyond this simple idea, there is no “popularity effect” of com­
plexity, where consultation begets more consultation or the
uncertainty of a complex project attracts more involvement.
Our expectation that state agencies would be more likely to
review projects proposed by governments at lower adminis­
trative levels (H3) was not supported.
Both agency level hypotheses are supported: agency size
and past experience are suggested to be significant and pos­
itive predictors for a state agency to be involved in review
networks, consistent with previous findings (Leach and
Sabatier 2005; Macgill 2011). If a state agency participated
in the CEQA review process more times between 2001 and
2010, it is more likely to review the environmental impacts of
projects in the following decade (H4). Likewise, state agencies
with more staff are more likely to consult, compared to those
with fewer employees (H5).
In terms of the effects of dyadic relationships on tie forma­
tion, our findings support the idea that knowledge salience
matters in the consultation network. The alignment between
project issues and agency expertise significantly predicts con­
sultation tie formation (H6). The odds of reviewing a project
are 2.1 (exp(0.736)=2.08) times greater if state agencies’
expertise aligns with the project’s impacts. Our hypothesis
about knowledge similarity is also supported, as projects are
less likely to be co-reviewed by state agencies with the same
expertise (H7). The odds of a state agency reviewing a CEQA
project decrease by 38.6% (exp(−0.494) = 0.61) if another
agency with similar expertise has participated in the review
network. In other words, two agencies with distinct knowl­
edge, expertise, and skills are more likely to review the same
project than those with overlapping knowledge. Finally, sim­
ilar projects tend to attract review by the same agency (H8).
Discussion
This analysis evaluated the contexts under which govern­
ment agencies consult on activities and programs proposed
by other government agencies. Taking the case of CEQA, we
reveal that agencies’ choice to provide consultation is deter­
mined by a combination of project (problem severity, envi­
ronmental pollution, and social vulnerability of the context),
agency (past experience, agency size), and agency–project
dyadic characteristics (expertise-based alignment, knowl­
edge similarity, and issue similarity). Overall, this research
enriches the understanding of consultation use in public man­
agement by focusing on agency behavior as consultants and
Table 3. Descriptive statistics of variables at the agency and project level.
Variables
Mean
S.D.
Min
Median
Max.
ln(Past experience)
7.3
2.4
0
8.1
10.6
ln(Agency size)
5.3
2.5
1.1
5.5
11.1
Project issues
13.6
7.1
1
16
24
Pollution burden score
5.0
1.6
0.7
4.9
10
Population vulnerability
4.6
1.9
0.4
4.5
10
ln(Population density)
6.2
2.5
−1.0
6.9
11.4
N (%)
Level of review
EIR
1,228 (23.1)
MND
3,648 (68.5)
ND
447 (8.4)
Lead agency
<State
5,151 (96.8)
≥State
172 (3.2)


## Page 11

458
Journal of Public Administration Research and Theory
contributes to the investigation of comprehensive and innova­
tive rationales for agencies’ decisions to participate in interde­
pendent networks as described in the EoG framework.
The political ecology of agency consultation
Interagency consultation often arises out of a desire to improve
the public good—to ensure that government-authorized activ­
ities align with the diverse missions of different agencies and
therefore meet a set of interests that provide public value. Yet
each additional consultation has the potential to add to the
time and cost it takes to develop and implement projects (Li
and Chan 2009; Sagar 2007; Ulibarri, Cain, and Ajami 2017)
and takes resources away from agencies to directly implement
their own programs. In our dataset, agencies commented on
an average of 891 projects during the ten-year period, which
is over seven reviews per month; some agencies commented on
over 5,000 projects, which is more than one review per day.
In the context of CEQA environmental reviews, while it is
within agencies’ discretion whether they provide consultation
or not, their choices appear to strike a balance between ef­
fectiveness and efficiency. While the EoG framework (Lubell
2013) has traditionally been applied to organizational choices
about which and how to engage in policy forums, infra­
structure projects pose similar strategic considerations. The
opportunities agencies have to consult on projects exceeds
available time and effort. We should expect agencies to con­
sult where the transaction costs of participation are lowest
and the potential payoffs are greatest. This is borne out in our
results: Agencies were more likely to comment on projects
that aligned with their expertise--cases where existing organ­
izational knowledge means lower learning costs and which
pose issues about which the agency can speak with most cred­
ibility (and thus presumably have more impact).
Further supporting an ecological perspective on interagency
consultation, two agencies with the same expertise were un­
likely to comment on the same project. In a few instances, this
is explained by state agencies that organize their activities into
regional offices—if the South Coast Air Quality Management
District (AQMD) comments on a project, there is little reason
for neighboring Mojave Desert AQMD to also review un­
less the project has a large spatial scope.8 However, most
agencies with shared expertise have the same statewide juris­
diction (e.g., Office of Toxic Substances Control and Office
of Pesticide Regulation), and they were equally unlikely to
both comment. These agencies fill a similar niche of exper­
tise in project assessment. If one office has already decided
to consult, the value of information provided by the second
office (how much the information improves the decision) is
likely to be lower, and thus there is less potential payoff to
consultation. Role- and problem-based consultation is effi­
cient from the perspective of a consulting agency weighing
time and effort against potential impact. Receiving a second
opinion about a key issue might not matter if the authoring
organization has similar expertise and thus in the first con­
sultant is providing a second opinion. However, in a rapidly
evolving area or where nuance matters, receiving only one
expert opinion potentially leads to blindspots. For instance,
we referenced the Office of Toxic Substances Control and
Office of Pesticide Regulation as potential substitutes earlier.
But these agencies have different expertise and foci that in
some cases might result in these agencies providing different
information to project decision-makers.
Public consultation versus agency consultation
Most research on participatory governance focuses on public
participation. In a general sense, the rationale for why agencies
and members of the public might choose to participate in re­
view and comment procedures is the same: commenting is
an opportunity to voice preferences and (perhaps) influence
decisions. However, agency commenting behavior and citizen
commenting behavior appear quite different. Citizens do not
fill specific technical roles as commenters, and redundancy
is often a core aim of advocacy campaigns (e.g., many form
letter comments are intended to signal that many people care
about the same issue). Thus, whereas the CEQA agency con­
sultation network was decentralized, with ties evenly distrib­
uted across projects, citizen participation networks are highly
centralized. A politically salient EIA process (e.g., the Pebble
Mine in Alaska or the Keystone XL gas pipeline) might garner
hundreds of thousands of citizen comments, whereas another
might garner a few dozen.
Relative to members of the public, agencies’ participation
choices likely involve a larger set of factors. First, in providing
a comment the agency is taking a position on the project.
Moreover, in choosing not to comment on a relevant project,
an agency is also taking a position of sorts. These choices
8To evaluate whether our inclusion of these regional offices was
overestimating the effect of knowledge similarity, we ran an additional anal­
ysis that collapses all the regional agencies into a single large agency (e.g.,
Caltrans becomes one agency rather than multiple regional districts). The
changed model does not change our story, as knowledge similarity remains
significantly negative (see model A2 in Appendix Table A4).
Table 4. Two-mode ERGM analysis of the CEQA review network.
Model 1
Hypothesis
Project characteristics
Project issues
−0.024 (0.000)
H1a(+)
ND (reference)
—
—
EIR
0.313 (0.000)
H1b(+)
MND
0.021 (0.456)
H1b(+)
Population density (logged)
−0.001 (0.864)
H2a(+)
Pollution burden score
0.026 (0.000)
H2b(+)
Vulnerable index
0.025 (0.000)
H2c(+)
Local lead (reference)
—
—
State, tribal, or federal lead
0.034 (0.402)
H3(-)
Agency characteristics
Past experience (logged)
1.299 (0.000)
H4(+)
Agency size (logged)
0.028 (0.000)
H5(+)
Dyadic characteristics
Issue matching
0.736 (0.000)
H6(+)
Knowledge similarity
−0.494 (0.000)
H7(-)
Issue similarity
0.002 (0.000)
H8(+)
GW (project) degree
442.191 (0.000)
Endogenous
Edges
−13.459 (0.000)
Endogenous
Year fixed effects
Yes
AIC
221,982.83
BIC
222,232.529
Log-likelihood
−110,968.415
Note: P-values are listed in parentheses. Local lead: Counties, cities, special
districts, nonprofit organizations, and joint power authorities.


## Page 12

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
459
might in turn affect how other agencies choose to comment
when roles are reversed—whereas public commenters are
presumably not worried about a back-and-forth relationship
with an agency. Similarly, in taking a position on the project
and critiquing (or supporting) the analysis, the consulting
agency is also potentially constraining itself; comments are
not legally binding, but it would look bad (and perhaps risk
litigation) for an agency to engage in behavior that it previ­
ously critiqued another agency for. Citizens commenting in a
private capacity never have to weigh project siting trade-offs
or make mitigation decisions, and so again the shadow of the
future is lessened.
Conclusion
Consultation is intended to introduce distinct knowledge
and provide scientific expertise to support decision-making
processes. In the case of CEQA, this goal is achieved as each
project was reviewed by an average of twelve state agencies.
The consultation activity provides input on many different
project impacts, from protecting air and water quality to
enhancing natural habitat to providing jobs. Likewise, we
found that agencies provide more consultation services when
warranted by site-specific considerations. Agencies were more
likely to comment on projects that could negatively affect
vulnerable populations and those located in places with high
levels of background pollution, which lends support to the
claim that EIA processes are an effective approach to identify
environmental risks and shape environmental justice. While
there are disputes regarding whether EIA can contribute to
distributional justice in the end (Wang et al. 2023), it does
promote environmental justice by involving agencies in the
consultation process and drawing their attention to disadvan­
taged communities in the decision-making process.
Collectively, these results suggest that agency consulta­
tion choices are largely role-driven and problem-focused.
Reviews provide public value by speaking to environmental
considerations and social and environmental justice that
might otherwise be overlooked in project decisions. However,
to the extent that this might be taken as evidence of CEQA
process effectiveness, there is an important caveat. EIA
arises relatively late in the development and implementation
of projects and programs. Most decisions regarding what
projects to implement, as well as where and how to imple­
ment them, may be made long before the formal EIA process
begins (Emerson et al. 2022; Scott, Ulibarri, and Scott 2022).
In other words, interagency consultation during the CEQA
process may have limited substantive impact on what is ulti­
mately built or implemented if most of the project design is
already completed.
Unfortunately, we have no data on whether, and how, the
lead agencies used the input they received from the CEQA
consultation network. Studies of other EIA jurisdictions find
relatively little change in how a project is conceptualized
during and after the environmental review (Ulibarri, Scott,
and Perez-Figueroa 2019). There is nothing in CEQA that
forces agencies to substantially change the project based
on consultants’ comments, and so it is unlikely that CEQA
projects change much during the review phase either. Again,
however, this likely has more to do with when consultations
are received—after major design about siting and design
have already happened—than lack of responsiveness. At
this stage of the process, consultants’ comments and lead
agency changes are in many respects path-dependent on
prior project choices. This article focused on agency behavior
as consultants. However, an important follow-up is under­
standing how the agency receiving the consultation chooses
to use the input. In the context of CEQA, this might entail
investigating the content of the reviews to assess whether they
shape the lead agency’s decision. Adding an interpretive lens
would also be beneficial, using interviews to understand why
agencies choose to provide or receive consultations from their
peer agencies.
Acknowledgments
The authors thank David R. Schaefer and Peng Huang for
feedback on an early draft of the manuscript, and California
Governor’s Office of Planning and Research (OPR) for
responding to our inquiries on the CEQA process.
Funding
This research was funded by the Solutions that Scale initia­
tive and the Interim COVID-19 Research Recovery Program
(ICCRP) at the University of California, Irvine and utilized the
Research Cyberinfrastructure Center (RCIC) at the University
of California, Irvine.
Data availability
The data and code necessary to replicate this article are avail­
able online at https://github.com/jiew3/CEQA_JPART2024.
git
References
Ames, Barry, and Margaret E. Keck. 1997. “The Politics of Sustain­
able Development Environmental Policy Making in Four Brazilian
States.” Journal of Interamerican Studies and World Affairs 39 (4):
1–40.
Ansell, Chris, and Alison Gash. 2012. “Stewards, Mediators, and
Catalysts: Toward a Model of Collaborative leadership1.” The In­
novation Journal: The Public Sector Innovation Journal 17 (1): 2.
Arnstein, Sherry R. 1969. “A Ladder Of Citizen Participation.” Journal
of the American Institute of Planners 35 (4): 216–24.
Baird, Julia, Ryan Plummer, Lisen Schultz, Derek Armitage, and Örjan
Bodin. 2019. “How Does Socio-Institutional Diversity Affect Col­
laborative Governance of Social-Ecological Systems in Practice?”
Environmental Management 63 (2): 200–14.
Bodin, Örjan. 2017. “Collaborative Environmental Governance:
Achieving Collective Action in Social-Ecological Systems.” Sci­
ence
357
(6352):
eaan1114.
https://www.ncbi.nlm.nih.gov/
pubmed/28818915
Borgatti, Stephen P, and Martin G. Everett. 1997. “Network Analysis of
2-Mode Data.” Social Networks 19 (3): 243–69.
Bowen, Frances E. 2002. “Does Size Matter?: Organizational Slack and
Visibility as Alternative Explanations for Environmental Respon­
siveness.” Business & Society 41 (1): 118–24.
Bryson, John M, and Barbara C. Crosby; Melissa Middleton
Stone. 2006. “The Design and Implementation of Cross-Sector
Collaborations: Propositions from the Literature.” Public Admin­
istration Review 66 ((s1): 44–55.
Carlin, Norman, and David Farabee. 2011. “CEQA Streamlining Leg­
islation: Some Small Steps Forward, but No Giant Leap.” 2011.
Cohen, Jed J, Johannes Reichl, and Michael Schmidthaler. 2014.
“Re-Focussing Research Efforts on the Public Acceptance of


## Page 13

460
Journal of Public Administration Research and Theory
­Energy Infrastructure: A Critical Review.” Energy 76 (November):
4–9.
Cohen, Michael D, James G. March, and Johan P. Olsen. 1972. “A Gar­
bage Can Model of Organizational Choice.” Administrative Science
Quarterly 17 (1): 1–25.
Cranmer, Skyler J, and Bruce A. Desmarais. 2016. “A Critique of Dy­
adic Design.” International Studies Quarterly: A Publication of the
International Studies Association 60 (2): 355–62.
Cumming, Graeme S, David H. M. Cumming, and Charles L. Redman.
2006. “Causes, Consequences, and Solutions.” Ecology and Society
11 (1): 14.
DeWitt, Noah. 2022. “A Twisted Fate: How California’s Premier Envi­
ronmental Law Has Worsened the State’s Housing Crisis, and How
To Fix It.” Pepperdine Law Review 49 (2): 413.
Duxbury, Scott W. 2018. “Diagnosing Multicollinearity in Exponential
Random Graph Models.” Sociological Methods & Research 50 (2):
491–530.
Emerson, Kirk, and Andrea K. Gerlak. 2014. “Adaptation in Collabo­
rative Governance Regimes.” Environmental Management 54 (4):
768–81.
Emerson, Kirk, Elizabeth Baldwin, Tyler A. Scott, Justin R. Pidot, Aaron
M. Lien, Faiz Currim, and Steven Bethard, et al. 2022. “Toward
NEPA Performance: A Framework for Assessing EIAs.” Environ­
mental Impact Assessment Review 97 (November): 106879.
Gallemore, Caleb, Monica Di Gregorio, Moira Moeliono, Maria
Brockhaus, and Rut Dini Prasti H. 2015. “Transaction Costs,
Power, and Multi-Level Forest Governance in Indonesia.” Ecolog­
ical Economics: The Journal of the International Society for Eco­
logical Economics 114 (June): 168–79.
Glasson, John, and Riki Therivel. 2019. Introduction to Environmental
Impact Assessment. London: Routledge.
Goodreau, Steven M, Mark S. Handcock, David R. Hunter, Carter T.
Butts, and Martina Morris. 2008. “A statnet Tutorial.” Journal of
Statistical Software 24 (9): 1–27.
Grandy, Jake B, and Shon R. Hiatt. 2020. “State Agency Discretion and
Entrepreneurship in Regulated Markets.” Administrative Science
Quarterly 65 (4): 1092–131.
Hamilton, Matthew, Mark Lubell, and Emilinah Namaganda. 2018.
“Cross-Level Linkages in an Ecology of Climate Change Adapta­
tion Policy Games.” Ecology and Society 23 (2): 36.
Handcock, Mark S, David R. Hunter, Carter T. Butts, Steven M.
Goodreau, and Martina Morris. 2008. “Statnet: Software Tools
for the Representation, Visualization, Analysis and Simulation of
Network Data.” Journal of Statistical Software 24 (1): 1548–7660.
Holzer, Marc, and Kaifeng Yang. 2005. “Administrative Discretion in
a Turbulent Time: An Introduction.” Public Administration Quar­
terly 29 (1/2): 128–39.
Huber, John D., and Charles R. Shipan. 2002. Deliberate Discretion?:
The Institutional Foundations of Bureaucratic Autonomy. New
York, NY: Cambridge University Press.
Isett, Kimberley Roussin, and Keith G. Provan. 2005. “The Evolution
of Dyadic Interorganizational Relationships in a Network of Pub­
licly Funded Nonprofit Agencies.” Journal of Public Administration
Research and Theory 15 (1): 149–65.
Jasny, Lorien, and Mark Lubell. 2015. “Two-Mode Brokerage in Policy
Networks.” Social Networks 41 (May): 36–47.
Jupe, Robert, and Warwick Funnell. 2015. “Neoliberalism, Consultants
and the Privatisation of Public Policy Formulation: The Case of
Britain’s Rail Industry.” Critical Perspectives on Accounting 29
(June): 65–85.
Kimberly, John R. 1976. “Organizational Size and the Structuralist Per­
spective: A Review, Critique, and Proposal.” Administrative Science
Quarterly 21 (4): 571–97.
Kørnøv, Lone, Sanne Vammen Larsen, Ivar Lyhne, Ida Engman
Puibaraud, Anne Merrild Hansen, Sara Bjørn Aaen, and Helle
Nedergaard Nielsen. 2022. “Collaboration through Environmental
Assessment Networks: Co-Creating Space and Cultivating a Joint
Learning Mindset.” Environmental Impact Assessment Review 97
(November): 106898.
Kosnik, Lea-Rachel D. 2005. “Sources of Bureaucratic Delay: A Case
Study of FERC Dam Relicensing.” The Journal of Law, Economics,
and Organization 22 (1): 258–88.
Leach, William D, and Paul A. Sabatier. 2005. “To Trust an Adversary:
Integrating Rational and Psychological Models of Collaborative
Policymaking.” The American Political Science Review 99 (4):
491–503.
Leksmono, Nurul, Paul Dorfman, Frank Burnet, David Gibbs, James
Longhurst, and Emma Weitkamp. 2010. “Enhancing Consultation
Practices on Air Quality Management in Local Authorities.” Journal
of Environmental Planning and Management 53 (5): 559–71.
Levitt, Barbara, and James G. March. 1988. “Organizational Learning.”
Annual Review of Sociology 14 (1): 319–38.
Levy, Michael A., Mark Lubell, Philip Leifeld, and Skyler Cranmer.
2016. “Estimating and Interpreting Geometrically Weighted Statis­
tics in Exponential Random Graph Models.” In Midwest Political
Science Association 2016 Research Conference. Chicago, IL, April.
Vol. 4.
Li, W., and Hon S. Chan. 2009. “Clean Air in Urban China: The Case
of Inter-Agency Coordination in Chongqing’s Blue Sky Program.”
Public Administration and Development: A Journal of the Royal
Institute of Public Administration 29 (1): 55–67.
Lubell, Mark. 2013. “Governing Institutional Complexity: The Ecology
of Games Framework.” Policy Studies Journal 41 (3): 537–59.
Lubell, Mark, Mark Schneider, John T. Scholz, and Mihriye Mete. 2002.
“Watershed Partnerships and the Emergence of Collective Action
Institutions.” American Journal of Political Science 46 (1): 148–63.
Lubell, Mark, and Matthew Robbins. 2022. “Adapting to Sea-level
Rise: Centralization or Decentralization in Polycentric Governance
Systems?” Policy Studies Journal: The Journal of the Policy Studies
Organization 50 (1): 143–75.
Macgill, Stephanie. 2011. “Does Mandated Collaboration Work? An
Analysis of Homelessness Planning Networks.” Western Political
Science Association 2011 Annual Meeting Paper.
Mahler, Julianne. 1997. “Influences of Organizational Culture on
Learning in Public Agencies.” Journal of Public Administration Re­
search and Theory 7 (4): 519–40.
Maor, Moshe, Raanan Sulitzeanu-Kenan, and Meital Balmas. 2023.
“The Reputational Dividends of Collaborating with a Highly Rep­
utable Agency: The Case of Interagency Collaboration between the
U.S. FDA and Its Domestic Partner Agencies.” Public Administra­
tion Review 83 (3): 639–53.
McGuire, Michael, and Chris Silvia. 2010. “The Effect of Problem Se­
verity, Managerial and Organizational Capacity, and Agency Struc­
ture on Intergovernmental Collaboration: Evidence from Local
Emergency Management.” Public Administration Review 70 (2):
279–88.
Miller, Gary J., and Andrew B. Whitford. 2016. Above Politics. Cam­
bridge, UK: Cambridge University Press.
Monroe, Ashley S, and William H. Butler. 2016. “Responding to a
Policy Mandate to Collaborate: Structuring Collaboration in the
Collaborative Forest Landscape Restoration Program.” Journal of
Environmental Planning and Management 59 (6): 1054–72.
Moynihan, Donald P, and Noel Landuyt. 2009. “How Do Public Or­
ganizations Learn? Bridging Cultural and Structural Perspectives.”
Public Administration Review 69 (6): 1097–105.
Nabatchi, Tina, and Matt Leighninger. 2015. Public Participation for
21st Century Democracy. Hoboken, NJ: John Wiley & Sons.
Narayanan, Sriram, Sridhar Balasubramanian, and Jayashankar M.
Swaminathan. 2009. “A Matter of Balance: Specialization, Task
Variety, and Individual Learning in a Software Maintenance Envi­
ronment.” Management Science 55 (11): 1861–76.
Nohrstedt, Daniel. 2016. “Explaining Mobilization and Performance
of Collaborations in Routine Emergency Management.” Adminis­
tration & Society 48 (2): 135–62.
OEHHA. 2021. “CalEnviroScreen 4.0.” September 20, 2021. https://
oehha.ca.gov/calenviroscreen/report/calenviroscreen-40.
Ojerio, Ryan, Moseley Cassandra, Lynn Kathy, and Bania Neil. 2011.
“Limited Involvement of Socially Vulnerable Populations in ­Federal


## Page 14

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
461
Programs to Mitigate Wildfire Risk in Arizona.” Natural Hazards
Review 12 (1): 28–36.
Opsahl, Tore. 2013. “Triadic Closure in Two-Mode Networks:
Redefining the Global and Local Clustering Coefficients.” Social
Networks 35 (2): 159–67.
Osterblom, Henrik, and Orjan Bodin. 2012. “Global Cooperation
among Diverse Organizations to Reduce Illegal Fishing in the
Southern Ocean.” Conservation Biology: The Journal of the Society
for Conservation Biology 26 (4): 638–48.
Ostrom, Elinor. 2007. “A Diagnostic Approach for Going beyond
Panaceas.” Proceedings of the National Academy of Sciences of the
United States of America 104 (39): 15181–7.
Reed, Mark S. 2008. “Stakeholder Participation for Environmental
Management: A Literature Review.” Biological Conservation 141
(10): 2417–31.
Robbins, Donijo. 2005. “Administrative Discretion: Its Use in Budg­
etary Analysis.” Public Administration Quarterly 29 (1/2): 186–
200.
Russo, Thomas N. 2020. “New NEPA Reforms and Duplicative State
Environmental Reviews Could Delay Renewables and Clean Elec­
tric Transmission.” Climate and Energy 37 (3): 24–32.
Sagar, Tracey. 2007. “Tackling on-Street Sex Work: Anti-Social
Behaviour Orders, Sex Workers and Inclusive Inter-Agency
Initiatives.” Criminology & Criminal Justice: The International
Journal of Policy and Practice 7 (2): 153–68.
Schaefer, D. R., T. V. Khuu, J. A. Rambaran, and D. Rivas-Drake.
2022. “How Do Youth Choose Activities? Assessing the Relative
Importance of the Micro-Selection Mechanisms behind Adoles­
cent Extracurricular Activity Participation.” Social Networks 77
(May): 139–50.
Scott, Ryan P, Nicola Ulibarri, and Tyler A. Scott. 2022. “Concise or
Comprehensive? Predictors of Impact Assessment Choices for Elec­
tric Transmission Line Projects.” Risk Analysis: An Official Publi­
cation of the Society for Risk Analysis 43 (5): 994–1010.
Scott, Tyler A, and Craig W. Thomas. 2017. “Winners and Losers
in the Ecology of Games: Network Position, Connectivity, and
the Benefits of Collaborative Governance Regimes.” Journal of
Public Administration Research and Theory: J-PART 27 (4):
647–60.
Scott, Tyler A, and David P. Carter. 2019. “Collaborative Governance
or Private Policy Making? When Consultants Matter More than
Participation in Collaborative Environmental Planning.” Journal of
Environmental Policy & Planning 21 (2): 153–73.
Scott, Tyler A, Nicholas Marantz, and Nicola Ulibarri. 2021. “Use of
Boilerplate Language in Regulatory Documents: Evidence from En­
vironmental Impact Statements.” Journal of Public Administration
Research and Theory 32 (3): 576–90.
Scott, Tyler A, Nicola Ulibarri, and Ryan P. Scott. 2020. “Stakeholder
Involvement in Collaborative Regulatory Processes: Using Auto­
mated Coding to Track Attendance and Actions.” Regulation &
Governance 14 (2): 219–37.
Shepard, Richard B. 2006. Quantifying Environmental Impact
Assessments Using Fuzzy Logic. New York, NY: Springer Science
& Business Media.
Slotterback, Carissa Schively, and Mickey Lauria. 2019. “Building a
Foundation for Public Engagement in Planning.” Journal of the
American Planning Association. American Planning Association
85 (3): 183–87.
Snijders, Tom A. B., Alessandro Lomi, and Vanina Jasmine Torló. 2013.
“A Model for the Multiplex Dynamics of Two-Mode and One-
Mode Networks, with an Application to Employment Preference,
Friendship, and Advice.” Social Networks 35 (2): 265–76.
Snijders, Tom A. B., Philippa E. Pattison, Garry L. Robins, and Mark
S. Handcock. 2006. “New Specifications for Exponential Random
Graph Models.” Sociological Methodology 36 (1): 99–153.
Staats, Bradley R, and Francesca Gino. 2012. “Specialization and Va­
riety in Repetitive Tasks: Evidence from a Japanese Bank.” Manage­
ment Science 58 (6): 1141–59.
Trnka, Joseph, and Elizabeth Ellis. 2014. “Environmental Reviews and
Case Studies: Streamlining the National Environmental Policy Act
Process.” Environmental Practice 16 (4): 302–8.
Ulibarri, Nicola, Bruce E. Cain, and Newsha K. Ajami. 2017. “A Frame­
work for Building Efficient Environmental Permitting Processes.”
Sustainability 9 (2): 180.
Ulibarri, Nicola, and Jiarui Tao. 2019. “Evaluating Environmental
Permitting Process Duration: The Case of Clean Water Act Section
404 Permits.” Journal of Environmental Planning and Management
62 (12): 2124–44.
Ulibarri, Nicola, and Tyler A. Scott. 2017. “Linking Network Structure
to Collaborative Governance.” Journal of Public Administration
Research 27 (1): 163–81.
Ulibarri, Nicola, Tyler A. Scott, and Omar Perez-Figueroa. 2019. “How
Does Stakeholder Involvement Affect Environmental Impact As­
sessment?.” Environmental Impact Assessment Review 79 (No­
vember): 106309.
Vangen, Siv. 2017. “Developing Practice-Oriented Theory on Collab­
oration: A Paradox Lens.” Public Administration Review 77 (2):
263–72.
Vangen, Siv, and Chris Huxham. 2005. “Aiming for Collaborative Ad­
vantage: Challenging the Concept of Shared Vision.” Advanced In­
stitute of Management Research Paper No. 015.
Wang, Jie, Nicola Ulibarri, Tyler A. Scott, and Steven J. Davis. 2023.
“Environmental Justice, Infrastructure Provisioning, and Envi­
ronmental Impact Assessment: Evidence from the California En­
vironmental Quality Act.” Environmental Science & Policy 146
(August): 66–75.
Wang, Peng, Ken Sharpe, Garry L. Robins, and Philippa E. Pattison.
2009. “Exponential Random Graph (p*) Models for Affiliation
Networks.” Social Networks 31 (1): 12–25.
Woldesenbet, Wassihun Gebreegiziaber. 2020. “Analyzing Multi-
Stakeholder Collaborative Governance Practices in Urban
Water Projects in Addis Ababa City: Procedures, Priorities, and
Structures.” Applied Water Science 10 (1): 44.
Wüstenhagen, Rolf, Maarten Wolsink, and Mary Jean Bürer. 2007. “So­
cial Acceptance of Renewable Energy Innovation: An Introduction
to the Concept.” Energy Policy 35 (5): 2683–91.
Yandle, Tracy, Douglas S. Noonan, and Beth Gazley. 2016. “Philan­
thropic Support of National Parks: Analysis Using the Social-
Ecological Systems Framework.” Nonprofit and Voluntary Sector
Quarterly 45 (4_suppl): 134S–55S.
Young, Oran R. 2002. The Institutional Dimensions of Environmental
Change: Fit, Interplay, and Scale. Cambridge, MA: MIT Press.


## Page 15

462
Journal of Public Administration Research and Theory
Appendix
Table A3. Analysis of the CEQA review network without dyadic covariates.
Model A1
Project characteristics
Project issues
0.009 (0.000)
ND (reference)
—
EIR
0.263 (0.000)
MND
0.042 (0.267)
Population density (logged)
−0.001 (0.663)
Pollution burden score
0.021 (0.000)
Vulnerable index
0.021 (0.000)
Local lead (reference)
—
State, tribal, or federal lead
0.042 (0.267)
Agency characteristics
Past experience (logged)
1.394 (0.000)
Agency size (logged)
0.035 (0.000)
Dyadic characteristics
Issue matching
—
Knowledge similarity
—
Issue similarity
—
GW (project) degree
550.985 (0.000)
Edges
−14.691 (0.000)
Year fixed effects
Yes
AIC
227,942.799
BIC
228,159.929
Log-likelihood
−113,951.400
Note: P-values are listed in parentheses. Local lead: Counties, cities, special
districts, nonprofit organizations, and joint power authorities.
Table A1. Agencies’ focus areas and projects’ environmental impacts.
Focus areas (agency)
N
%
Environmental impacts (project)
N
%
Agriculture and forestry
2
2.8
Aesthetic/visual
3,876
72.8
Air quality
1
1.4
Agriculture and forestry resources
2,834
53.2
Biological resources
20
27.8
Air quality
4,401
82.7
Coastal zone
2
2.8
Biological resources
4,636
87.1
Cultural resources
2
2.8
Coastal zone
568
10.7
Economics/jobs/social
1
1.4
Cultural resources
4,327
81.3
Hazards and hazardous materials
2
2.8
Cumulative effects
2,941
55.3
Hydrology
6
8.3
Drainage/absorption
3,156
59.3
Land use/planning
2
2.8
Economics/jobs/social
607
11.4
Public services
8
11.1
Flood plain/flooding
2,969
55.8
Transportation
15
20.8
Geology/soils
4,092
76.9
Utilities/service systems/infrastructure
2
2.8
Greenhouse gas emissions
260
4.9
Water quality
9
12.5
Growth inducement
1,957
36.8
Hydrology/water quality/supply
4,070
76.5
Land use/planning
3,655
68.7
Mineral resources
2,453
46.1
Noise
4,268
80.2
Population/housing
2,844
53.4
Public services
3,531
66.3
Recreation
3,071
57.7
Schools/universities
2,315
43.5
Transportation
4,119
77.4
Utilities/service systems/infrastructure
3,306
62.1
Wildfire
2,376
44.6
Table A2. Detecting multicollinearity: the variance inflation factor (VIF)
from ERGM parameters.
VIF
Project issues
3.31
ND (reference)
—
EIR
4.48
MND
1.02
Pollution burden score
3.64
Vulnerable index
2.28
Population density (logged)
2.11
Local lead (reference)
—
State, tribal, or federal lead
2.34
Past experience (logged)
2.71
Agency size (logged)
11.57
Issue matching
1.62
Knowledge similarity
1.31
Issue similarity
1.53
GW (project) degree
21.32
Note: VIF > 20 indicates a potential risk of multicollinearity and VIF > 100
indicates severe collinearity (Duxbury 2018).


## Page 16

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 3
463
Figure A1. Two-model ERGM goodness-of-fit.


## Page 17

464
Journal of Public Administration Research and Theory
Table A4. Analysis of the CEQA review network with regional agencies
collapsed into a single large agency.
Model A2
Project characteristics
Project issues
−0.025 (0.000)
ND (reference)
—
EIR
0.382 (0.000)
MND
0.023 (0.460)
Population density (logged)
−0.005 (0.130)
Pollution burden score
0.024 (0.000)
Vulnerable index
0.026 (0.000)
Local lead (reference)
—
State, tribal, or federal lead
0.037 (0.423)
Agency characteristics
Past experience (logged)
1.458 (0.000)
Agency size (logged)
0.007 (0.075)
Dyadic characteristics
Issue matching
0.776 (0.000)
Knowledge similarity
−0.158 (0.000)
Issue similarity
0.002 (0.000)
GW (project) degree
311.047 (0.000)
Edges
−14.855 (0.000)
Year fixed effects
Yes
AIC
128,463.614
BIC
128,702.503
Log-likelihood
−64,208.807
Note: P-values are listed in parentheses. Local lead: Counties, cities, special
districts, nonprofit organizations, and joint power authorities.


## Page 18

© 2024 Public Management Research Association. Copyright of Journal of Public
Administration Research & Theory is the property of Oxford University Press / USA and its
content may not be copied or emailed to multiple sites or posted to a listserv without the
copyright holder's express written permission. However, users may print, download, or email
articles for individual use.

