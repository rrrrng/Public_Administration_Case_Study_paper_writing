# Distributive Justice in Collaborative Outputs Empowering Minority Viewpoints thr

## Page 1

Journal of Public Administration Research and Theory, 2024, 34, 1–15
https://doi.org/10.1093/jopart/muad012
Advance access publication 22 June 2023
Article
Distributive Justice in Collaborative Outputs: Empowering
Minority Viewpoints Through Deliberation
Jiho Kim
Syracuse University, USA
Address correspondence to the author at jkim36@syr.edu
ABSTRACT
This article explores how deliberation affects distributive justice for minority view participants in policy decisions made through collaborative gov-
ernance. It also examines whether the quality of deliberation (i.e., willingness to accept opposing viewpoints) and quantity of deliberation (i.e.,
length of discussion) can be an effective tool for minority view participants to overcome power imbalances in such collective decision-making
processes. I use agent-based modeling, a computer simulation experiment method, to examine interactions among participants in a collabora-
tive governance arrangement. I develop a series of theoretical propositions based on the simulation results, which are robust to various changes
in the parameters and assumptions of the model. First, both the quality and quantity of deliberation may enhance the decision acceptability
of participants with minority views. Second, the quality of deliberation may be more effective at empowering underrepresented minority view
participants than the quantity of deliberation. Third, the quantity of deliberation may better promote minority views than the quality of delib-
eration when minority view participants are overrepresented. These findings indicate that interpersonal justice in collaborative processes may
enhance distributive justice for minority viewpoints in collaborative outputs, even when procedural justice in the design of collaboration is
weakened by an underrepresentation of minority view participants. I conclude with suggestions for future research that can further improve the
external validity of the theoretical propositions.
INTRODUCTION
Justice is a core value that lays normative foundations and
guides scholarly endeavors in numerous disciplines, in-
cluding but not limited to philosophy (Rawls 1971), po-
litical science (Nozick 1974), psychology (Lind and Tyler
1988), and law (Hart 1961). Although myriad competing
perspectives exist on how justice should be realized in
societies, Aristotle’s Nicomachean Ethics offers a simple but
widely known definition of justice −giving people what they
deserve. In alignment with this definition, scholars have de-
veloped the theory of organizational justice, which studies
how individuals perceive and react to various aspects of
justice within and across organizations (see Adams 1965;
Greenberg 1987).
Although organizational justice encompasses both intra-
and inter-organizational contexts, little research in public ad-
ministration scholarship extends beyond the scale of public
employees in a single organization. In other words, few public
administration scholars have studied organizational justice
in multi-organizational arrangements, such as those found
in collaborative governance (for exceptions, see: Dobbin
and Lubell 2021; Kim and Siddiki 2018; Siddiki, Kim, and
Leach 2017). This raises the question: how might organiza-
tional justice be achieved in collaborative governance settings,
where representatives from multiple organizations across the
public, private, nonprofit, and civic sectors come to the table
to discuss a public policy issue at stake and engage in de-
signing and implementing policy decisions (Emerson and
Nabatchi 2015)? The need to investigate organizational jus-
tice in collaborative settings has grown since the New Public
Governance paradigm gained prominence in the twenty first
century (Bingham, Nabatchi, and O’Leary 2005; Osborne
2006; Torfing and Triantafilou 2013).
In this article, I apply the theoretical lens of organiza-
tional justice to interorganizational settings of collaborative
governance. Specifically, I investigate the potential impact
of deliberation on generating policy decisions that lead to
a fair allocation of resources (i.e., distributive justice) for
individuals with minority viewpoints. I also examine whether
and how deliberation can improve distributive justice in col-
laborative outputs (i.e., decisions), even when procedural jus-
tice is compromised by a low representation of minority view
participants. Thus, I address the following research questions:
how does deliberation affect distributive justice for minority
view participants in decisions made through collaborative
governance? If only few minority view participants are in-
cluded in collaborative governance, can the quality or quan-
tity of deliberation remedy power imbalance in the collective
decision-making processes?
To address these questions, I use agent-based modeling
(ABM), a computer simulation experiment method, and
develop theoretical propositions that can be tested with
empirical evidence in future studies. In the computational
model, members of the majority coalition (i.e., the coalition
that has the dominant viewpoint) argue in favor of a public
value or goal that is aligned with the status quo of public
policy (e.g., economic development) while the members with
the minority viewpoint advocate for a conflicting yet less
recognized public value or goal (e.g., environmental pro-
tection). In addition, I alter both the quality and quantity
© The Author(s) 2023. Published by Oxford University Press on behalf of the Public Management Research Association. All rights reserved. For
permissions, please e-mail: journals.permissions@oup.com.


## Page 2

2
Journal of Public Administration Research and Theory
of deliberation in the simulation and measure how these
variables affect distributive justice for minority interests in
the decisions made.
In the next section, I provide theoretical background re-
lated to organizational justice, collaborative governance,
and deliberation. I then describe the experimental design
of the simulation and its main treatment and outcome
variables. After summarizing the experiment results, I con-
duct a series of sensitivity analyses to check if the main
findings are robust to changes in the values of parameters
and assumptions of the model. Next, I suggest and discuss
theoretical propositions on distributive justice and deliber-
ation in collaborative governance. Finally, I conclude with
the theoretical and practical implications of this article and
offer possible ways to enhance the external validity of the
theoretical arguments.
THEORY
Three theoretical lenses—organizational justice, collaborative
governance, and deliberation—are fundamental to exploring
the research questions in this article. Each of these lenses is
discussed below.
Organizational Justice
Broadly defined, organizational justice refers to the fair
treatment of individuals within and across organizations.
While still the subject of some debate, most scholars agree
that organizational justice consists of three main factors:
procedural, interactional, and distributive (Colquitt 2001;
Colquitt and Greenberg 2003; Greenberg 1990; Le and
Pan 2021; Sweeney and McFarlin 1993). Procedural jus-
tice concerns the fairness of decision-making processes
and has six elements: consistency, unbiasedness, accuracy,
correctability, representativeness, and ethicality (Leventhal
1980). Interactional justice can be divided into two
subcomponents: (1) interpersonal justice, which pertains
to how well individuals are treated with respect and sen-
sitivity, and (2) informational justice, which refers to how
much explanation or rationale for decisions is provided
to individuals (Colquitt 2001). Distributive justice centers
on the fair allocation of resources—or benefits and costs—
among individuals and may be based on principles of equity,
equality, or need (Cook and Hegtvedt 1983). Figure 1
visualizes the different components of organizational justice.
Numerous scholars have analyzed the impact of organ-
izational justice on various outcomes at the individual and
organizational levels (Bell, Wiechmann, and Ryan 2006;
Cropanzano, Bowen, and Gilliland 2007; Moorman 1991;
Nowakowski and Conlon 2005). Much research on organ-
izational justice has been conducted in the private sector,
where among other topics, scholars have looked at how or-
ganizational justice explains the emotions, attitudes, and
behaviors of employees and affects organizational perfor-
mance (Ambrose and Schminke 2009; Greenberg 1990; Rupp
et al. 2006; Welbourne, Balkin, and Gomez-Mejia 1995).
In public administration, scholars link organizational jus-
tice with organizational commitment (Jang, Lee, and Kwon
2021), job satisfaction (Choi 2011), turnover (Al Afari and
Elanain 2014), conflicts (Alexander and Ruderman 1987),
trust in high-level managers (Rubin 2009), task performance
(Potipiroon and Rubin 2018), and organizational goal attain-
ment (Moon 2017). Other scholars have studied job com-
pensation (e.g., pay and promotions) in government agencies
(Cho and Sai 2013; Mani 1999; Mylona and Mihail 2019).
However, the development of organizational justice theory
remains an incomplete task in the public administration
scholarship, particularly in terms of its application to multi-
organizational, collaborative contexts. A growing number of
policy problems require collective action and dispute reso-
lution among actors from various organizations (Bingham,
Nabatchi, and O’Leary 2005; Head and Alford 2015).
Indeed, fewer government policies, programs, and services
are implemented within the context of a single, hierarchical
agency and more are delivered through cross-boundary col-
laboration (Sirianni 2010). In this sense, collaborative and
participatory governance have enriched and broadened the
practical (and thus theoretical) horizons of public administra-
tion. Scholars must attend to this new reality and examine or-
ganizational justice within collaborative governance systems,
where representatives of different beliefs and backgrounds
are encouraged to participate and voice their opinions.
Collaborative Governance
Two definitions of collaborative governance have be-
come prominent in the past literature. Ansell and Gash
(2008, 544) take a relatively narrower approach, defining
Figure 1. Types of Organizational Justice.


## Page 3

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
3
collaborative governance as “a governing arrangement
where one or more public agencies directly engage non-
state stakeholders in a collective decision-making process.”
In contrast, Emerson and Nabatchi (2015, 18) advance a
broader definition of collaborative governance that includes
intergovernmental and nongovernmental collaborations:
“the processes and structures of public policy decision
making and management that engage people constructively
across the boundaries of public agencies, levels of govern-
ment, and/or the public, private and civic spheres in order
to carry out a public purpose that could not otherwise be
accomplished.” Under both definitions, collaborative gov-
ernance brings together various stakeholders to collectively
address complex policy issues characterized by multiple
interrelated causes, overlapping jurisdictions, or conflicting
interests.
Given its multi-party, relationship-oriented nature, organi-
zational justice, and its associated concepts such as diversity,
equity, and inclusion, are undoubtedly critical in collaborative
governance (Ansell et al. 2020; Dobbin et al. 2023; Johnston
et al. 2011; Siddiki, Kim, and Leach 2017). Surprisingly, how-
ever, they have received little attention from scholars, with two
exceptions: one focused on procedural justice and represen-
tation, and another on interpersonal justice and deliberation.
First, some scholars emphasize representation as a key
element of procedural justice in collaborative governance
(Dobbin and Lubell 2021; Siddiki, Kim, and Leach 2017).
A key tenet of collaborative governance, backed by empir-
ical research, is that a broad and representative array of
stakeholders who share a diverse set of information, interests,
and beliefs can contribute to social learning (Schusler, Decker,
and Pfeffer 2003), civic capacity (Sirianni 2010), mutual trust
(Getha-Taylor et al. 2019), and conflict resolution (O’Leary
and Bingham 2003).
Implicit in the concept of representation is diversity. While
the physical aspects of diversity (i.e., gender, race, ethnicity)
are important in collaborative arrangements (Hoang, Suh,
and Sabharwal 2022; Kennedy 2014), so too is the issue of
viewpoint diversity. Indeed, from an organizational justice
perspective, the focal point of diversity in collaborative gov-
ernance often may lie in “context-specific stakeholder interests
and perspectives” that are not entirely in agreement with each
other (Douglas et al. 2020, 497). In other words, the pres-
ence and articulation of minority viewpoints on a policy issue
may be a more apropos criterion for assessing the level of
representation in collaborative governance. Specifically, since
participants in a collaborative governance come to the table
to achieve a shared goal, it may be less likely that they di-
vide along individual demographic characteristics because
such characteristics may not be related directly to the relevant
policy issue. Instead, conflicting views toward the policy goal
may be a more foundational driver of conflicts and power
imbalances in collaborative governance. Holding all other
conditions constant, the mere fact that a given person is a
woman and/or a person of color may be insufficient to fully
explain the battlelines among participants in collaborative
governance. Even if minority demographics become the focal
point of debates and power imbalances in collaborative gov-
ernance, the minority viewpoints would still reflect the un-
derlying motives and desires of the gender, racial, or ethnic
minorities. Therefore, the critical yardstick for discerning mi-
nority participants in collaborative governance could center
on their different perspectives on the policy issue, rather than
their demographic identifiers per se.
Second, interpersonal justice in collaborative governance
has been operationalized as the quality of deliberative process,
fair treatment of the participants, mutual respect, responsive-
ness to new information, and the existence of a mediator
(Kim and Siddiki 2018). While interpersonal justice is some-
times referred to as a part of procedural justice (Greenberg
1990; Sweeney and McFarlin 1993), it can play a distinctive
role in promoting cognitive and relational learning among
participants in collaborative governance (Siddiki, Kim, and
Leach 2017). Among others, deliberation is a crucial element
of interpersonal justice that distinguishes it both from rep-
resentation and from other elements of procedural justice in
collaborative governance.
Quality and Quantity of Deliberation
Beyond representation, or the mere presence of diverse actors,
deliberation may influence how policy decisions made through
collaborative governance promote the interests of participants
with minority views. Deliberation is an essential part of collab-
orative and polycentric decision making, in that it can promote
the transformation of varied perspectives of stakeholders into
a policy decision (Doberstein 2016). Deliberative processes
encourage participants to articulate their interests and en-
gage in negotiation and compromise (Bingham, Nabatchi,
and O’Leary 2005). Moreover, deliberation may mitigate the
problem of power asymmetry between stakeholders (Pirsoul
and Armoudian 2019). For example, results from large scale
field experiments indicate that deliberative forums can em-
power women’s voice and authority when women are de-
scriptively overrepresented or unanimous rule is adopted
(Karpowitz, Mendelberg, and Shaker 2012; Mendelberg,
Karpowitz, and Goedert 2014; Mendelberg, Karpowitz, and
Oliphant 2014). Without deliberation, other systems of collec-
tive decision-making (e.g., simple majority vote) are less likely
to facilitate minority perspectives and interests.
To maximize its potential gains, deliberation needs to be
designed and implemented in sufficient quality and quan-
tity. Participants of collaborative governance may enjoy
a higher level of satisfaction with decisions if they “are
willing to engage in considerable deliberation and open to
changing their perspectives and preferences” (Robertson
and Choi 2012, 98). At the same time, the quantity of de-
liberation itself can positively affect the consensus success
rate and acceptability of decisions in collaborative govern-
ance (Choi and Robertson 2014a). Nevertheless, if the level
of representation of minority view participants is low, an
increase in the quantity of deliberation alone might not
always have a powerful impact on distributive justice for
minority interests. This is because collaborative govern-
ance with weak countervailing power can degenerate into
“window dressing” governance where minority interests
are co-opted by the politically stronger majority (Fung
and Wright 2003, 265). Therefore, examining the effects of
both quality and quantity of deliberation could provide a
more nuanced understanding of deliberation as a tool for
strengthening minority interests when stakeholder repre-
sentation is imbalanced.
In sum, this article leverages the theory of organizational
justice to explain how deliberation may influence distributive


## Page 4

4
Journal of Public Administration Research and Theory
justice in collaborative governance. Using agent-based mod-
eling, a computer experiment method, it specifically explores
the causal effects of deliberation on distributive justice and
the moderating role of representation in the relationship be-
tween deliberation and distributive justice.
EXPERIMENT DESIGN
ABM is a computational simulation method of interactions
among autonomous agents and/or adaptations of their
behaviors to their external environments. Previous studies on
collaborative governance have used ABM to examine several
factors that can influence collaborative outputs and outcomes,
including: starting alternative, level of conflict, and flexibility
of participants to change their positions (Robertson and
Choi 2012); length of deliberation and decision rule (Choi
and Robertson 2014a); autonomy and balance of power in
caucuses (Choi and Robertson 2014b); prosocial motivations
of stakeholders (Choi and Robertson 2019); structural, pro-
cedural, and network conditions of collaboration (Scott,
Thomas, and Magallanes 2019); and existence and forma-
tive type of collaborative governance regimes (Bitterman and
Koliba 2020).
ABM has both methodological strengths and weaknesses
for collaborative governance research. First, the experi-
mental design of simulations enables researchers to estab-
lish causality between treatment and outcome variables by
controlling for all confounding variables in the model. By
mitigating methodological concerns stemming from potential
selection bias in case studies and observational studies, ABM
may allow researchers to produce valid and robust knowl-
edge on collaborative governance. Second, rigorous thought
experiments in ABM help build theoretical propositions that
can be tested in future empirical studies. While systematic em-
pirical evaluations of collaborative governance are often in-
feasible due to “the difficulty of obtaining longitudinal data
for a large sample of collaborative efforts” (Scott, Thomas,
and Magallanes 2019, 33), ABM can produce theories that
are applicable beyond the specific contexts of limited empir-
ical settings. Nevertheless, computational modeling of collab-
orative governance also has its weaknesses. While potential
threats to the internal validity of research using ABM are
much less of a concern, the external validity of their findings
can be relatively low. To address this shortcoming, scholars
recommend sensitivity analyses to check if the results remain
consistent with changes in the model or a mixed-methods ap-
proach which compares simulation experiment results to em-
pirical evidence from actual cases of collaborative governance
(Choi and Park 2021). To confirm the robustness of the sim-
ulation results, this article conducts a series of sensitivity
analyses in the later section.
Simulation Procedure
Figure 2 shows the agent interactions in the simulation ex-
periment during three stages of collective decision-making in
collaborative governance: (1) preference sharing and learning
(i.e., education phase), (2) policy proposal generation (i.e.,
negotiation phase), and (3) voting (i.e., decision phase). I
use MATLAB to program all stages of the simulations. The
experimental design of the study largely relies on Choi and
Robertson (2014a) but makes modifications to their model.
Informed by real-world cases of collaborative governance,
Choi and Robertson’s (2014a) model was intentionally
designed to reflect characteristics of the Sacramento Area
Water Forum. These characteristics include small group
size, education phases where preferences of participants are
discussed, and negotiation processes to reach a consensus on
a mutually acceptable decision. Even though a small group
size of eight in the computational model may not necessarily
be generalizable to the entire universe of collaborative govern-
ance cases, the three stages correspond to the core elements
of discovery, definition, deliberation, and determination for
principled engagement in the integrative framework of col-
laborative governance (Emerson and Nabatchi 2015). Also,
the three stages can be understood as being embedded in a
simplified “action arena” (Ostrom 2009) where actors be-
long to different advocacy coalitions (see Sabatier and Weible
2019), share their preferences about a policy issue, assign net
costs and benefits to potential collaborative outputs, and de-
cide on a policy proposal. Thus, the empirical and theoret-
ical grounds of the model provide supporting evidence for
the content validity of the stylized model of collaborative
governance.
Before discussing the simulation process in detail, I first
present a hypothetical example that is used to illustrate how
the computational model may reflect real-world collabora-
tive decision-making processes. Although the computational
model in this article is generic enough that it could represent
any situations where a set of two contrasting viewpoints col-
lide in collaborative processes, I describe the following sce-
nario to provide more intuitive explanations of the model.
I suppose that an imaginary city has development plans for
constructing a new shopping mall on the lake. The city gov-
ernment invites eight representatives from various sectors
and organizations to a collaborative forum. A majority of
the participants are “mall-lovers” who most value economic
Figure 2. Simulation Procedure.


## Page 5

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
5
development, while the remaining minority are “lake-lovers”
who most value the environment.1 As the majority view
participants and minority view participants come to the table,
they bring a set of preferences that reflect their contrasting
viewpoints toward the policy issue. The participants then en-
gage in preference sharing and learning processes where they
discover, define, and discuss the policy problem. Next, they
formulate a policy proposal and determine an action plan
based on consensus.
Basic Setup
The viewpoints of eight agents are represented mathemat-
ically in a preference matrix of m rows and n columns as
shown in equation (1). The m rows reflect the number of dif-
ferent sources of information that shape the preference of the
agents and the n columns indicate the number of different
dimensions of a policy on which agents decide. For example,
the information sources can include scientific data, expert
opinions, government reports, organizational assessments,
media information, personal experience, words of mouth, and
more, and influence how strongly each agent prefers the value
of economic development or environmental protection. The
columns can reflect diverse agendas of the mall construction
project (e.g., duration, location, size, budget, compensation,
environmental regulation) that require a collective decision
of the participants. The different agendas represent diverse
“decision points” that often are involved in complex deci-
sion-making processes in the policy implementation literature
(Pressman and Wildavsky 1984).

Preference matrixa =


wa
11 · · · wa
1n
...
... ...
wa
m1· · · wa
mn


(1)
where a denotes the agent a, m denotes the number of informa-
tion sources, n denotes the number of policy dimensions, and
wa
mn denotes the weight value of a preference point in row m
that reflects the agent a’s view toward a policy dimension in
column n.
The weight values wa
mn in the preference matrix show the
direction and strength of the agent a’s preference shaped by
the mth information source on the nth policy dimension. This
study assigns 12 rows and 12 columns for the preference ma-
trices of the eight agents. For all eight agents, one-eighth of
the elements (i.e., 18 elements) in the matrix are non-zero
numbers that are randomly drawn from a normal distribution
in its full range (i.e., about 99.7% of the values lying within
three standard deviations from the mean) while the rest are
zero.2 The farther away these weights are from zero, the more
extreme their viewpoints are toward the corresponding policy
dimension. Since the viewpoints of agents in the opposing
coalitions are in stark contrast with each other on a number
of policy dimensions, the simulation represents a highly sa-
lient and complex politics in collective decision-making
processes (Gormley 1986).
Power asymmetry among the agents in the simulation ex-
periment is created by two factors: (1) an imbalance in the
representation of participants of the majority and minority
coalitions and (2) the existing policy that supports the ma-
jority interests (e.g., economic development) over the mi-
nority interests (e.g., environmental protection). These two
factors indicate an underlying oppression and disenfran-
chisement that minority view participants might face in an
administrative system (Stivers et al. 2023). Thus, the agents
from the majority coalition, the “mall-lovers,” have positive
weights for every nonzero element in their preference ma-
trices, which are obtained from the absolute values of num-
bers randomly drawn from a normal distribution. In contrast,
agents from the minority coalition, the “lake-lovers,” have
negative values for all preference points, which are computed
from multiplying the absolute values by −1. If the sum of all
m weights in the nth column is positive for an agent i, then
the agent prefers the status quo for the corresponding policy
dimension. By the same logic, if the sum of all m weights in
the nth column is negative or zero, the agent does not support
the status quo.
Preference Sharing and Learning Stage
The simulation process of collaborative governance begins
with the preference sharing and learning stage among the eight
agents. At this stage, the agents engage in problem discovery
and definition by revealing a part of their own preference set
and calibrating the knowledge of others. Furthermore, they
modify the elements of their original preference matrix based
on new preference points shared by others. Equation (2)
illustrates how the shared preference point is learned by agents
in the model. First, a speaker s is randomly selected. Second, a
non-zero weight value wst
mn is randomly chosen from the pref-
erence matrix of the speaker s. Third, the speaker s shares the
non-zero preference point wst
mn and other agents learn and in-
corporate this new preference point into their own preference
matrices. More specifically, all agents except the speaker ac-
cept a part of the shared preference point into their matrices,
whose proportion is determined by the learning coefficient l
between 0 and 1. For the speaker s, the weight value of the
preference point remains the same.

wa(t+1)
mn
=
®
wat
mn + l × wst
mn,
a ̸= s
wat
mn,
a = s
(2)
where wa(t+1)
mn
denotes a weight value of a preference point at
(m,n) that an agent a updates in time (t + 1) after learning;
wat
mn denotes a weight value at (m,n) that an agent a possesses
in time t before learning; wst
mn denotes a weight at (m,n) that
the speaker s possesses in time t; and l denotes a learning coef-
ficient which represents the proportion of the new preference
point accepted.
Intuitively, if a lake-lover shares a preference point that
reflects a negative view toward the mall construction, it can
intensify the initial viewpoint of other lake-lovers or partially
abate the opposing viewpoint of the mall-lovers. However,
the agents are not modeled to learn more from the op-
posing coalition participants than from the same coalition
1Again, the values of majority view participants and minority view
participants can be anything, as long as they conflict with each other. For
example, the simulation results hold even if the majority view participants
prioritize the lake and the minority view participants support the mall con-
struction.
2The positions of non-zero elements are randomly chosen. Thus, two agents
can have a non-zero number in the same cell and all eight agents can have a
zero element for some parts of the preference matrix. This allows the model
to account for imperfect knowledge and uncertainty of the agents regarding
the policy issue at stake.


## Page 6

6
Journal of Public Administration Research and Theory
participants. How much the agents learn from the non-
coalition participants, or the quality of deliberation, is one
of the main independent variables of the simulation experi-
ment. As the quality of deliberation increases to a degree that
the agents learn from the opposing views as much as they do
from the similar views, the model is less likely to polarize the
views of the two coalitions and more likely to encourage the
agents to find the middle ground.
Policy Proposal Generation Stage
At the policy proposal generation stage, the agents engage
in negotiations where they collectively construct each part
of the policy package. First, the agents compute the sum of
weights of m preference points for each of the n columns of
the preference matrix.3 This sum indicates the overall level
of agreement of the agents toward a single decision point
of the construction project. Second, they reveal their post-
deliberation preference for each policy dimension based
on the sum of the weights in each column. If this sum is
greater than 0, the agent is in favor of economic develop-
ment for that specific policy dimension. Otherwise, the agent
is against the development plan. Third, a policy proposal
is generated and expressed as a 1 × n row vector in equa-
tion (3) whose elements take a value of either 1 or −1 (e.g.,
[11,1, −11,2, −11,3, . . . , 11,n−2, 11,n−1, −11,n]).
Equation
(4)
illustrates that if 75% or more out of eight agents (i.e., 6
or more agents) support the mall construction, a numerical
value of 1 is assigned to the corresponding policy dimension
in the policy proposal. However, if less than 75% of eight
agents (i.e., 5 or less agents) favor the mall construction, the
policy dimension takes a value of −1.4 In other words, if three
or more out of eight agents oppose the majority interests for
a given policy dimension, the policy proposal favors envi-
ronmental protection for the corresponding decision point.
If not, the policy proposal supports the construction of the
mall for the decision point. Unlike the voting stage where
the agents need to reach a consensus to decide on the policy
package as a whole, I apply a less strict decision rule (i.e.,
supermajority rule) at the policy proposal stage to allow for
more flexibility when deciding on each slice of the policy. A
full policy proposal is developed after repeating this proce-
dure for all n policy dimensions. Once the final policy pro-
posal is generated, the agents do not engage in additional
negotiation among themselves.

Policy proposal = [pd1, pd2, . . . , pdn−1, pdn]
(3)

pdn =







1,
if
m
�
i=1
wa
in > 0
for 75% or more of a number of agents
−1,
if
m
�
i=1
wa
in > 0
for less than 75% of a number of agents
(4)
where pdn denotes the nth dimension of the policy proposal
generated, and �m
i=1 wa
in > 0 denotes that an agent a in a col-
laborative governance arrangement possesses a positive sum
of the m preference weight values for the nth dimension at the
policy proposal generation stage.
Voting Stage
The last phase of the decision-making process is voting on
the whole  policy proposal generated in the previous stage.
Unlike the policy proposal generation stage that used the su-
permajority rule, the final voting stage requires consensus
(i.e., all individual agents need to find the policy proposal
acceptable). First, the level of acceptability of the policy pro-
posal is calculated for all agents as in equation (5). The agents
multiply the numerical value of each element in the policy
proposal by the sum of post-deliberation preference points in
the corresponding column of their own preference matrices,
after which they compute the average of these products.5
Second, individual agents cast a final vote on whether they
find the policy proposal acceptable. The agents vote in favor
of the policy proposal if the average of the products for the
twelve columns (i.e., decision acceptability) is greater than or
equal to zero and vote against it otherwise. A policy deci-
sion is successfully made on consensus if and only if all eight
participants find the proposal acceptable overall (i.e., the level
of acceptability for the policy proposal is not negative for all
agents). The participants fail to make a decision if one or
more participants do not accept the proposal (i.e., the level
of acceptability for the policy proposal is negative for at least
one agent).

Acceptabilitya =
n
�
j=1
��m
�
i=1
wa
ij
�
× pdj
�
÷ n
(5)
where pdj denotes a numerical value of the policy proposal in
dimension j, and wa
ij denotes the weight value of a preference
point at (i,j) that an agent a possesses.
Table 1 shows the parameters and their values in the model.6
The number of non-zero preference points per agent (18) is
obtained from dividing the total number of preference points
in a preference matrix (144) by the total number of agents in
each collaborative governance arrangement (8). The learning
coefficient for preference points shared by agents on the same
coalition is set to 0.5 because it is unrealistic for a piece of in-
formation to be transmitted in its entirety. This is due to the
“bounded rationality” (Simon 1957) of participants who are
likely to have cognitive limitations on decision-making under
uncertainty (Lebiere and Anderson 2011). The value of 0.5
for the in-group learning coefficient reflects this natural loss
of information during its conveyance. However, the learning
coefficient for preference points shared by the members of
the out-group ranges from 0 to 0.5 and thus cannot exceed
the in-group learning coefficient. In contrast, the learning co-
efficient for preference points shared by agents on the oppo-
site coalition varies from 0 to 0.5, which will be discussed
more in the next section. The learning coefficients of this
study do not vary at an individual level but instead apply to
3For example, each agent adds up all 12 preference points in the first column
and repeats this calculation for the second through the twelfth columns. As
a result, the agent ends up with twelve different sums, one for each column.
4The proportion of 75% was chosen to reflect the supermajority rule for the
policy proposal generation stage. In the sensitivity analyses, the percentage
is changed to 62.5%, 87.5%, and 100%.
5For example, if an agent’s sum of all preference points in the first column
is −5.74 and the first element of the policy proposal is 1, the product of
−5.74 is assigned to the first dimension of the policy. The same calculation
is applied to the other eleven columns and the agent computes an average
of these 12 products.
6All values of the parameters in table 1 are the same as those in Choi and
Robertson (2014a)’s model except for the minimum number of agents re-
quired to oppose a policy dimension and the number of iterations. Choi and
Robertson (2014a) do not specify the decision-making rule for each policy
dimension but rather change the decision-making rule for the entire policy
decision to simple majority, supermajority, and unanimity and run the sim-
ulation for 2,500–25,000 times.


## Page 7

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
7
all members in a group equally. This is because this article
focuses on examining variations in group-level characteris-
tics of collaborative governance and comparing the relative
effects of the quality and quantity of deliberation of collab-
orative forums. The minimum number of agents required to
oppose a policy dimension is determined by a supermajority
rule that requires an agreement of at least 75% of 8 agents to
defend the status quo.
Outcome and Treatment Variables
I use three outcome variables – opposition rate of policy de-
cision, absolute decision acceptability, and relative decision
acceptability – to measure and capture two different aspects
of distributive justice for minority interests in the final policy
decision. The opposition rate measures how well the policy
decision itself is aligned with minority interests that are held
before having interactions with the agents. On the contrary,
the absolute and relative levels of decision acceptability
measure the perception of distributive justice based on the
minority interests after interactions.
The opposition rate of the policy decision is defined as the
percentage of the policy dimensions that have a numerical
value of −1 in the final decision. The policy outputs in the sim-
ulation are not a binary decision of whether the mall either
gets built or not. Rather, they represent a continuous spec-
trum of various possibilities of how the mall is constructed
(e.g., building the mall with environmental regulations to
minimize damage to the lake or allowing a small number
of eco-friendly local businesses near the lake, rather than a
comprehensive shopping mall). The absolute level of accept-
ability of minority view participants refers to the level of ac-
ceptability of the final decision among the minority viewpoint
agents. The relative level of acceptability for minority view
participants is the ratio of minority view agents’ acceptability
of the final policy proposal compared to that of majority
view agents and expressed in percentage terms.7 All outcome
metrics are averaged over 10,000 iterations and derived only
from the policy proposals where consensus is successfully
reached among all agents.
The treatment variables in this article are the quality and
quantity of deliberation and representation of minority
view participants. Quality of deliberation is defined as the
openness of participants to accept preference points from
members with contrasting views on a policy issue. It is
operationalized as the learning coefficient lo for preference
points shared by a member of the opposing party.8 In other
words, it is the proportion of a speaker’s preference point
in deliberative processes that is accepted and updated in
the preference matrix of members of the opposite coalition,
which varies from 0, 0.125, 0.25, 0.375, to 0.5.9 The quan-
tity of deliberation denotes the number of repetitions for
preference sharing and learning, which ranges from 1, 36,
72, 108, to 144.10 As the quantity of deliberation becomes
greater, the agents exchange more preference points with
each other before generating the policy proposal. In addi-
tion, I operationalize representation as the proportion of
minority view participants in collaborative governance. The
treatment status for representation varies from 12.5% (1
out 8), 25% (2 out of 8), 37.5% (3 out of 8) to 50% (4 out
of 8).
This article compares the values of the three outcome
variables for a total of 40 experimental groups.11 When the
quality of deliberation is changed, the quantity of delibera-
tion is fixed to a mid-point of 72. Similarly, when the quantity
of deliberation is the main treatment variable, the quality of
deliberation remains constant at 0.25.12 Additionally, I pro-
vide consensus success rates of each group, which are defined
as the percentage of policy proposals that achieved consensus
among all agents.
RESULTS
In this section, I summarize the main results of the simulation
experiment. First, I report how deliberation and representa-
tion affect the consensus success rate that serves as the basis
of the three outcome variables in the model.13 Although the
Table 1. Parameters of the Model
Parameter
Value
Number of agents in each collaborative governance arrange-
ment
8
Number of policy dimensions in a policy proposal
12
Number of preference points per policy dimension
12
Number of preference points in a preference matrix
144
Number of non-zero preference points per agent
18
Learning coefficient for preference points shared by agents on
the same coalition
0.5
Minimum number of agents required to oppose a policy
dimension
3
Number of iterations
10,000
7While the value of the absolute acceptability is simply greater than zero and
has no upper limit, the value of the relative level of acceptability is between
0% and 100%.
8The quality of deliberation is a multidimensional concept compared to the
quantity of deliberation which can be measured simply with the duration
or frequency of deliberative meetings. For example, the Discourse Quality
Index (DQI) developed by Steenbergen et al. (2003) has seven indicators
of the quality of deliberation: (1) free participation without interruption;
(2) level of justification for demands; (3) appeals made in terms of narrow
group interests or the common good; (4) negative or positive statements a-
bout the target groups of policy; (5) attitude toward demands of others; (6)
respect toward counter arguments; and (7) consensus building. To reflect its
multifaceted nature, I operationalize the quality of deliberation by centering
on the aspect of willingness of participants to accept preference points from
the opposing party.
9A learning coefficient of 0 indicates that the two coalitions never learn from
each other. Since the value of 0.5 for quality of deliberation would mean
that the agents accept half of the preference points shared by the opposite
party and be equally open to preference points from the two coalitions, this
variation between 0 and 0.5 is likely to represent a full spectrum of the val-
ues that quality of deliberation can take.
10The lowest value for the quantity of deliberation in the model is 1 because
the decision-making process without any deliberation cannot result in con-
sensus at the final voting stage. On the other hand, the highest value of 144
matches the number of elements in each agent’s preference matrix. Thus, the
range from 1 to 144 also covers a credibly comprehensive set of values for
quantity of deliberation.
1140 experimental groups = 4 values of representation × 5 values of quality
of deliberation + 4 values of representation × 5 values of quantity of delib-
eration.
12In the sensitivity analysis, I allow both quality and quantity of deliberation
to vary simultaneously to check the robustness of the results. In other words,
I include 100 experimental groups (= 4 values of representation × 5 values of
quality of deliberation × 5 values of quantity of deliberation).
13For 4 experimental groups with a zero consensus rate in table 2, I
conducted a total of 100,000 simulation iterations and checked that they
never reached a consensus.


## Page 8

8
Journal of Public Administration Research and Theory
consensus success rate does not directly measure the distribu-
tive justice for minority interests, it shows how the values of
0, 0.125, 0.25, 0.375, and 0.5 for quality of deliberation are
roughly comparable to the values of 1, 36, 72, 108, and 144
for quantity of deliberation in terms of consensus making.
Figure 3 shows that the quality and quantity of deliberation
consistently increase the proportion of decisions that are ac-
ceptable to all eight agents, while the representation of mi-
nority view participants does not affect the consensus success
rates in a specific direction.
The main simulation results are summarized in Table 2 and
visually represented in figures 4, 5, and 6. Figure 4 indicates
that both the quality and quantity of deliberation do not con-
tinuously increase the opposition rates for all experimental
groups. If the observations are limited to underrepresented
minority viewpoints (i.e., 1 or 2 members in the minority
coalition), the opposition rate falls considerably less when
the quality of deliberation increases than when the quan-
tity of deliberation increases. When minority viewpoints
are overrepresented (i.e., 3 or 4 members in the minority
Figure 3. Consensus Success Rate.
Figure 4. Opposition Rate of Policy Decision.


## Page 9

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
9
Table 2. Summary of the Main Results
Representation
Quality of Deliberation
Quantity of Deliberation
0
0.125
0.25
0.375
0.5
1
36
72
108
144
Panel A. Consensus Success Rate (%)
1/8
0.03
7.61
53.83
93.22
99.44
7.60
20.48
55.36
92.27
99.58
2/8
0.03
6.35
45.36
87.04
98.15
0.37
25.62
44.67
74.80
93.17
3/8
0
24.85
67.68
90.39
97.80
0
27.43
68.25
88.09
96.41
4/8
0
2.81
26.57
65.63
93.07
0
4.29
25.55
54.14
75.43
Panel B. Opposition Rate of Policy Decision (%)
1/8
22.22
(4.81)
15.71
(6.81)
10.82
(7.75)
10.38
(8.26)
11.52
(8.83)
40.27
(6.74)
22.49
(8.10)
11.02
(7.74)
6.34
(6.65)
5.11
(6.20)
2/8
30.56
(4.81)
28.32
(8.40)
24.80
(9.60)
23.71
(11.19)
24.79
(12.00)
52.48
(5.51)
36.79
(9.35)
24.75
(9.83)
17.81
(9.77)
14.47
(9.60)
3/8
—
54.02
(10.57)
50.82
(8.69)
47.69
(12.19)
45.05
(13.08)
—
52.85
(8.67)
50.84
(10.63)
48.44
(11.95)
46.04
(12.69)
4/8
—
65.87
(7.62)
64.88
(10.89)
64.65
(9.02)
61.17
(12.37)
—
63.85
(7.85)
64.72
(9.08)
65.63
(10.23)
65.60
(11.00)
Panel C. Absolute Decision Acceptability of Minority View Participants
1/8
0.09
(0.02)
0.18
(0.16)
0.34
(0.27)
0.67
(0.39)
1.15
(0.50)
0.20
(0.17)
0.23
(0.19)
0.33
(0.27)
0.63
(0.39)
1.23
(0.57)
2/8
0.33
(0.21)
0.59
(0.38)
0.93
(0.55)
1.47
(0.75)
2.28
(0.95)
0.51
(0.28)
0.76
(0.44)
0.93
(0.54)
1.28
(0.71)
1.94
(0.98)
3/8
—
2.47
(0.67)
2.81
(0.98)
3.34
(1.13)
4.11
(1.36)
—
2.12
(0.79)
2.82
(0.97)
3.52
(1.18)
4.42
(1.41)
4/8
—
4.94
(1.22)
5.40
(1.42)
5.96
(1.54)
7.06
(1.90)
—
4.16
(1.06)
5.38
(1.41)
6.70
(1.74)
8.04
(2.11)
Panel D. Relative Decision Acceptability of Minority View Participants (%)
1/8
0.51
(0.08)
1.05
(1.00)
1.84
(1.51)
3.64
(2.05)
6.20
(2.40)
6.74
(7.07)
2.27
(2.08)
1.82
(1.48)
2.45
(1.34)
3.60
(1.23)
2/8
2.49
(1.46)
5.92
(5.03)
8.34
(5.84)
12.71
(7.42)
18.54
(7.78)
30.56
(24.09)
13.50
(11.63)
8.44
(6.04)
7.92
(4.59)
9.03
(4.15)
3/8
—
93.31
(71.67)
78.65
(60.82)
66.63
(43.30)
61.36
(31.66)
—
87.56
(63.76)
77.66
(57.28)
67.02
(50.21)
58.07
(41.75)
4/8
—
390.09
(213.74)
295.51
(290.95)
239.43
(165.81)
176.32
(101.85)
—
299.28
(218.00)
299.56
(224.37)
278.13
(224.46)
248.84
(195.69)
Note: Numbers are means. Numbers in parentheses are standard deviations.
Figure 5. Absolute Decision Acceptability of Minority View Participants.


## Page 10

10
Journal of Public Administration Research and Theory
coalition), the quantity of deliberation leads to a greater
increase or a smaller decrease in the opposition rate than the
quality of deliberation does.
In figure 5, the absolute acceptability increases monotonically
with better or more deliberation. For underrepresented minority
view participants, the numerical values of the slopes are higher
when the quality of deliberation, rather than the quantity of
deliberation, is enhanced. In contrast, the quantity of delibera-
tion performs slightly better at empowering the overrepresented
minority interests than the quality of deliberation.
Figure 6 shows similar patterns where relative decision ac-
ceptability of minority interests rises as more participants with
minority views are represented. Again, the quality of delibera-
tion is more effective at minority view empowerment when a
low number of the minority coalition members are included.
Note that in figure 6, when 1 or 2 minority view participants
are included, the relative decision acceptability rises with an
increase in the quality of deliberation. This provides par-
tial evidence that the interests of underrepresented minority
view participants might be promoted more than the majority
interests if the participants of collaborative governance are
more open to accepting counter arguments. In contrast, when
3 or 4 minority view participants are included, the relative
decision acceptability decreases with a higher quality of de-
liberation and falls less sharply with a greater quantity of
deliberation. This result indicates that, although the absolute
acceptability of minority view participants increases with
better or more deliberation, the absolute acceptability of ma-
jority view participants increases even more. Also, the relative
acceptability is very high for groups with four minority view
participants as indicated in Panel D of table 2 (i.e., ranges
between 390% and 176%), which may be because the sim-
ulation design allows three agents to oppose the status quo
policy dimension that serves the majority interests. In the
sensitivity analysis section, the high levels of relative accept-
ability become smaller after I require the minimum of four
agents to oppose a policy dimension (i.e., between 270% and
135%) or let the status quo of the policy vary randomly (i.e.,
between 137% and 114%).
To sum up using the mall example, three key findings emerge
from the experiment. First, with better or more deliberation,
participants in the anti-mall (minority view) coalition find the
policy decision more acceptable even when they “meet in the
middle” with the pro-mall (majority view) coalition (i.e., reduce
the revisions to the construction plan that improve its environ-
mental sustainability). Second, if the minority view lake-lovers
are underrepresented, distributive justice can be better achieved
when the participants are more willing to learn from the oppo-
site views (quality of deliberation) than when they just continue
talking (quantity of deliberation). Third, if the minority view
lake-lovers are overrepresented, “more” discussion leads to
greater distributive justice for their interests than “better” dis-
cussion. Intuitively speaking, the results indicate that if only one
or two lake-lovers were invited to the table, they would rather
talk for a short period of time (e.g., 30 min) with people who
are open to accepting different views than talk for a long time
(e.g., 3 h) with people who are obstinate about their own views.
Sensitivity Analysis
Next, I conduct a sensitivity analysis to rule out possible al-
ternative explanations that the results are driven by certain
parameters or assumptions in the model. To address potential
concerns related to the generalizability of the simulation de-
sign, I change the following properties and rerun the model
with 10,000 iterations: (1) interacting quality and quantity
of deliberation, rather than fixing the value of quality of de-
liberation at 0.25 when quantity of deliberation varies and
quantity of deliberation at 72 when quality of deliberation
changes; (2) setting the minimum number of agents required
to oppose a part of a policy proposal as one, two, and four,
instead of three; (3) letting all agents to randomly choose
their preference points from a fixed full preference matrix
Figure 6. Relative Decision Acceptability of Minority View Participants.


## Page 11

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
11
without any zero elements, instead of independently selecting
eighteen non-zero elements from a normal distribution; (4)
randomizing the status quo of a policy, rather than making
it to be in favor of the majority interests; and (5) randomly
choosing elements of preference matrices from a continuous
uniform distribution between −3 and 3, instead of a normal
distribution.
The sensitivity analysis results suggest that the overall
results are robust to a variety of changes made to the model
(see Supplementary figures A1, A2, A3, and A4 and tables A1,
A2, A3, A4, A5, and A6 ). However, a few exceptions to the
main results are identified in Supplementary figures A1–A4
where quality and quantity of deliberation interact with each
other in three-dimensional graphs. Consensus success rate
and absolute acceptability do not increase continuously with
greater quantity of deliberation when the quality of deliber-
ation is zero, and the same is observed with higher quality
of deliberation when the quantity of deliberation is one. In
other words, if the quality (or quantity) of deliberation is ex-
tremely low, an increase in the quantity (or quality) of de-
liberation may not translate into greater levels of consensus
success rate and absolute acceptability of the policy proposal.
Interestingly, both consensus success rate and absolute ac-
ceptability levels increase more strongly with a greater quality
(or quantity) of deliberation when quantity (or quality) of de-
liberation is higher. This indicates that the impact of quality
and quantity of deliberation can “stack up” that is, have posi-
tive interaction effects on consensus success rate and absolute
acceptability.
In addition, throughout the changes, the exact threshold
for distinguishing underrepresented and overrepresented
minorities (e.g., 1 or 2 members of the minority coalition
versus 3 or 4 members of the minority coalition) varies when
I compare the effects of the quality and quantity of delibera-
tion on distributive justice. In some cases, the quantity of de-
liberation begins to have a stronger positive influence on the
outcome variables than the quality of deliberation when 2 or
4 minority view participants are included. Notwithstanding,
the general tendency remains unchanged that the quantity
of deliberation becomes more effective than the quality of
deliberation as more participants with minority views are
included. The only exception to this pattern is observed in
Supplementary table A1 where one agent can oppose a policy
dimension. When only one member of the minority coalition
is included, the absolute decision acceptability of minority
view participants rises more sharply with an increase in the
quantity of deliberation than in the quality of deliberation.
One possible reason behind this deviation might be the new
decision rule adopted at the policy proposal generation stage.
Since the consensus rule may have already empowered the
single participant with the minority view, the quantity of
deliberation could enhance distributive justice for under-
represented views more than the quality of deliberation.
Nevertheless, the main findings remain largely consistent
under various changes in the simulation design.
DISCUSSION
In this section, I use the simulation results to offer four the-
oretical propositions on the role of deliberation in collabo-
rative governance and discuss the main implications of this
article to theory and practice. Three propositions center on
the potential contributions of deliberation to distributive jus-
tice in collaborative outputs, and one explores the possible
impact of deliberation on consensus building. Since the setup
of the simulation experiment in this study is agnostic to spe-
cific contexts of the collective decision-making processes, I
build propositions that may apply to a much wider array of
cases than the mall construction example. The broad appli-
cability of the propositions may contribute to scaling up the
knowledge on collaborative governance and moving beyond
small-n and medium-n case studies, or even beyond large-n
quantitative studies that are very specific to a particular loca-
tion or policy area.
First, the quality and quantity of deliberation can affect
the distributive justice for minority interests in collaborative
outputs. The simulation results show that with better or more
deliberation, the absolute decision acceptability level for mi-
nority view participants grows continuously but the opposi-
tion rate drops in most experimental groups. One possible
explanation for the adverse effect of deliberation on the op-
position rate may be that the variations in the quality and
quantity of deliberation do not only apply to the majority
view participants but also to minority view participants in
the model. As a result of more open and lengthier delibera-
tion, the minority view participants also receive and accept
more preference points from the majority view participants
and may make more compromises. This may be a reason why
minority view participants find the policy decision more ac-
ceptable after deliberation although the decision itself does
not serve their initial interests more strongly. Thus, both the
quality and quantity of deliberation have the potential to
ameliorate the subjective judgment of how well their interests
at the post-deliberation stage are reflected in collaborative
outputs. Moreover, the sensitivity analysis results indicate
that the quality and quantity of deliberation can have a syn-
ergistic relationship when both are relatively high and might
lose their effects when one of them is very low. Therefore, the
participants and facilitators of collaborative governance may
benefit from knowing that deliberation can be more effective
when its two dimensions—content (i.e., quality) and length
(i.e., quantity)—are at adequate levels than when either of
them is extremely low. This leads to the first proposition.
Proposition 1: With an increase in the quality or quantity
of deliberation, the minority view participants may find
more acceptable the decisions made in collaborative gov-
ernance, even when they make more compromises with the
viewpoints of majority participants.
Second, the quality and quantity of deliberation can have
different magnitudes of impact on distributive justice for mi-
nority interests in policy decisions, depending on how many
people with minority views are included. Even if a relatively
low number of people with minority views participate in a
collaborative governance process, their interests can still
have more influence over the collaborative outputs when
the participants are more receptive to the opposing opinions
(quality of deliberation). Longer discussions (quantity of de-
liberation) in a disrespectful environment toward different
viewpoints might not have such effects for underrepresented
minority view participants. Thus, different remedies are ad-
visable for different situations—for minority view empow-
erment, the external convener or the internal members of
collaborative governance may choose to increase the quality


## Page 12

12
Journal of Public Administration Research and Theory
or quantity of deliberation, contingent on the representation
of participants with minority perspectives. This leads to the
following propositions.
Proposition 2: If participants with minority views are
­underrepresented, an increase in the openness to accept
­opposing viewpoints is more effective at empowering mi-
nority interests in decisions made through collaborative
governance than the quantity of deliberation.
Proposition 3: If participants with minority views are
overrepresented, an increase in the quantity of deliberation
can better reinforce minority interests in decisions made
through collaborative governance than having greater o-
penness to learn from opposite viewpoints.
Finally, another proposition emerges from the result that both
the quality and quantity of deliberation can increase the prob-
ability of consensus making in collaborative governance, al-
though consensus success rate is not directly related to the
research questions of this article. As shown in figure 3, an
extremely low level of quality and quantity of deliberation
may create policy deadlocks. Interestingly, the inclusion of
more minority view participants does not effectively increase
consensus success rates in the results. This might be because a
more balanced representation of stakeholders reduces power
asymmetry between the majority and minority coalitions,
which makes it harder for the participants to reach a con-
sensus on the policy decision that serves the majority interests.
Overall, these results echo the argument of Robertson and
Choi (2012) that the willingness to adjust opinions can be
critical for conflict resolution in collaborative governance
and the proposition of Choi and Robertson (2014a) that the
quantity of deliberation positively influences the rate of deci-
sion success. More importantly, similar to absolute accepta-
bility, the sensitivity analysis reveals that the interaction effect
between quality and quantity of deliberation may exist for
consensus success rate, too. Again, this finding supports a bal-
anced approach toward improving the quality and quantity
of deliberation in collaborative governance. Therefore, I offer
the final proposition.
Proposition 4: As the participants learn more from oppo-
site viewpoints or engage in lengthier deliberations, they
are more likely to reach a consensus in collaborative gov-
ernance.
Beyond these propositions, this article also has multiple
implications for theory and practice. First, it contributes to
both the organizational justice and collaborative governance
literatures by exploring the relationship between procedural,
interpersonal, and distributive justice in interorganizational
contexts. While procedural justice, and particularly partici-
pant representation, is often highly associated with distribu-
tive justice (Hauenstein, McGonigle, and Flinder 2001), no
study has provided alternative solutions that can address the
effects of weak procedural justice on distributive justice in
collaborative governance. A key finding of this article is that
the quality of deliberation, an important contributing factor
to interpersonal justice in collaborative governance, can em-
power minority interests in collaborative outputs even when
the participants with opposing viewpoints are not represented
in a balanced manner. In other words, I argue that a greater
level of interpersonal justice in collaborative processes has the
potential to mitigate the negative effects of poor procedural
justice in the representation of participants in the design of
collaborative governance and thus reinforce distributive jus-
tice in collaborative outputs.
Second, this article calls for continued efforts of researchers
to provide a deeper understanding and a more nuanced the-
orization on the design (e.g., representation), process (e.g.,
quality and quantity of deliberation), and performance (e.g.,
facilitation of minority views) of collaborative and partici-
patory governance. For practitioners, it emphasizes the sig-
nificance of the design and implementation of deliberative
forums. The leaders and participants, as well as conveners and
facilitators, of collaborative governance should first identify
the main conflicting interests and observe which participants
hold which of these different viewpoints. They can then tell
how many minority view participants are represented and
whether increasing the quality or quantity of deliberation
would be more favorable for minority view empowerment.
Although minority view empowerment may not be the first
priority in all decision-making processes in the public sphere,
making informed decisions on managing the quality and
quantity of deliberation may at least ensure that public policy
making is not solely dominated by a single interest.
Third, this article underscores the role of deliberation in
improving the political and social equity of policy decisions.
This article offers theoretical insights into mechanisms through
which deliberation addresses “democratic deficits” in American
public administration where “democratic organizations,
institutions, and governments are seen as falling short of ful-
filling the principles of democracy in their practices or opera-
tion” (Nabatchi 2010, 378). Deliberation can attenuate these
democratic deficits in government agencies by encouraging
consensus building and producing equitable outputs of collab-
oration. More specifically, deliberation might have the potential
to correct for power inequalities that remain after an inclusion
of marginalized stakeholders is legally mandated in “exter-
nally directed” collaborative governance regimes (Emerson and
Nabatchi 2015). For instance, the inclusion of small and low-
income communities required by the state law of California led to
increased disparities in the representation of those communities
in the governing body of Groundwater Sustainability Agencies
(GSA) (Dobbin and Lubell 2021). This finding is worth atten-
tion from scholars and practitioners because inclusion in collab-
orative processes is often the result of a strategic choice made
by the active management of the administrative state (Ansell et
al. 2020). If the level of marginalized stakeholder representa-
tion stays low, setting a more open and respectful environment
for deliberation may empower their interests effectively during
the decision-making process. Otherwise, engaging in longer or
more frequent discussions may better enable the minorities to
have a say in the output of collaboration.
Fourth, this article contends that the theoretical horizons
of representation should be expanded beyond minority dem-
ographics in public administration research. Despite the
importance of values in shaping the power dynamics in col-
lective decision-making processes, scholars have paid more
attention to gender, race, and ethnicity than the contrasting
viewpoints of the participants. This is due, at least in part, to
methodological challenges associated with objectively meas-
uring and comparing individual values. However, simulation
experiments like ABM can enable researchers to overcome
the measurement issue and navigate crucial but understudied
areas of research on viewpoint representation. In practice, this


## Page 13

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
13
article suggests that public managers with the authority to in-
itiate and sustain collaborative governance should include a
sufficient number of minority view participants. A balanced
composition of participants can translate into distributive jus-
tice for minority interests in collaborative outputs, which may
then improve the political efficacy of the minority members
(Atkeson and Carrillo 2007).
CONCLUSION
Deliberation is a crucial component of collaborative gov-
ernance because it can play a critical role in empowering
minority views in the decisions made. The simulation experi-
ment results corroborate that the quality and quantity of de-
liberation can be an effective means of increasing the level
of decision acceptability for participants with minority views
and the probability of consensus making. Even when mi-
nority view participants are underrepresented, they may exert
greater influence over and feel more satisfied with the deci-
sion if the participants are more willing to accept information
from the opposing party.
Future studies can further adjust and develop the “toy
model” of complex decision-making in this article to pro-
vide additional insights into deliberation and representation
in collaborative governance. First, more complex policy is-
sues can entail various sets of conflicting viewpoints among
the participants, and the distinction between majority and
minority interests may not always be dichotomous. For ex-
ample, if more than two groups vie for power over collec-
tive decision-making processes, some participants may prefer
the interests of multiple groups, which might make it hard
to clearly  distinguish between   the majority and minority
interests. Thus, the multidimensional and cross-cutting na-
ture of viewpoints can be a potential extension of the compu-
tational model. Although this article simplifies such possible
complexities, it can still have implications for instances where
a number of different perspectives converge to two main
groups and form a bipolar political structure.
Second, multiple discussions with the same participants can
add more dynamic components to the experimental design.
This article only accounts for one-shot meetings, but some
parameters of the model can be updated based on the results
of previous decision-making processes. For instance, learning
capacity, whether for participants with similar or different
viewpoints, may depend on how well the participants accept
the decisions made in earlier meetings with each other.
Third, future scholars can consider individual variations
in the degree to which each of the participants accepts new
information from others. Since the majority and minority
view coalitions in collaborative governance are the main unit
of analysis in this article, the learning coefficients are held
constant for participants in the same coalition. However,
different participants might still have different levels of
bounded rationality even if they belong to the same coali-
tion, possibly due to various demographic characteristics.
These potential variations can be incorporated into micro-
level studies in the future that focus on assessing the impact
of individual-level factors on information decay in collab-
orative governance. Therefore, future research can extend
the scope of this article by addressing the possible existence
of several viewpoints, repeated discussions, and individual
differences in learning.
One challenge of this article would be to check and further
improve the external validity of the simulation findings. Even
though the sensitivity analysis yields robust results, one should
be cautious about expecting the theoretical propositions to
hold true in the real-world cases of collaborative governance.
Future studies can explore the roles of deliberation in collabo-
rative governance to test if any discrepancy exists between the
simulation results and empirical data. For example, an in-depth
case study on the dynamics of decision-making in collabora-
tive governance might reveal any unrealistic or invalid features
of the computational model. A quantitative empirical analysis
using a large-n dataset of collaborative governance can produce
an estimate of the average treatment effect (ATE) of the quality
and quantity of deliberation on distributive justice observed in
the actual voting records, which might conflict with the theory.
If so, scholars may identify which aspects of the simulation de-
sign and variables can be modified to better reflect the reality
of collaborative governance. Therefore, theory building articles
and theory testing research can strengthen each other. This ar-
ticle serves as a useful starting point for researchers who wish
to validate the ABM-generated theory with empirical evidence.
Empirical findings in turn will allow for potential adjustments
of the simulation design to increase the explanatory and pre-
dictive power of theoretical propositions.
Acknowledgements
The author would like to thank Tina Nabatchi, Taehyon Choi,
Craig Thomas, and Sarah Hamersma for providing insightful
and constructive feedback on earlier drafts of this article.
Data Availability
The code for replicating computational simulations in this
article are available in the Harvard Dataverse at https://doi.
org/10.7910/DVN/65BFOG. No empirical data were used.
References
Adams, J. Stacy. 1965. Inequity in social exchange. Advances in Exper-
imental Social Psychology 2: 267–99.
Al Afari, Thamna S., and Elanain, Hossam M. Abu. 2014. Procedural
and distributive justice as mediators of the relationship between
interactional justice and work outcomes: An empirical study of
the UAE public health care sector. Journal of Applied Business Re-
search 30 (4): 1091–108.
Alexander, Sheldon, and Marian Ruderman. 1987. The role of proce-
dural and distributive justice in organizational behavior. Social Jus-
tice Research 1 (2): 177–98.
Ambrose, Maureen L., and Marshall Schminke. 2009. The role of o-
verall justice judgments in organizational justice research: A test of
mediation. Journal of Applied Psychology 94 (2): 491–500.
Ansell, Christopher, Carey Doberstein, Hayley Henderson, Saba Siddiki,
and Paul ‘t. 2020. Understanding inclusion in collaborative govern-
ance: A mixed methods approach. Policy and Society 39 (4): 570–91.
Ansell, Christopher, and Alison Gash. 2008. Collaborative govern-
ance in theory and practice. Journal of Public Administration Re-
search and Theory 18 (4): 543–71. https://doi.org/10.1093/jopart/
mum032.
Atkeson, Lonna Rae, and Nancy Carrillo. 2007. More is better: The
influence of collective female descriptive representation on external
efficacy. Politics & Gender 3 (1): 79–101.
Bell, Bradford S., Darin Wiechmann, and Ann Marie Ryan. 2006.
Consequences of organizational justice expectations in a selection
system. Journal of Applied Psychology 91 (2): 455–66.


## Page 14

14
Journal of Public Administration Research and Theory
Bingham, Lisa Blomgren, Tina Nabatchi, and Rosemary O’Leary. 2005.
The new governance: Practices and processes for stakeholder and
citizen participation in the work of government. Public Administra-
tion Review 65 (5): 547–58.
Bitterman, Patrick, and Christopher J. Koliba. 2020. Modeling alter-
native collaborative governance network designs: An agent-based
model of water governance in the Lake Champlain Basin, Vermont.
Journal of Public Administration Research and Theory 30 (4): 636–
55. https://doi.org/10.1093/jopart/muaa013.
Cho, Yoon Jik, and Na Sai. 2013. Does organizational justice matter in
the federal workplace? Review of Public Personnel Administration
33 (3): 227–51.
Choi, Sungjoo. 2011. Organizational justice and employee work
attitudes: The federal case. The American Review of Public Admin-
istration 41 (2): 185–204.
Choi, Taehyon, and Peter J. Robertson. 2014a. Deliberation and deci-
sion in collaborative governance: A simulation of approaches to
mitigate power imbalance. Journal of Public Administration Re-
search and Theory 24 (2): 495–518. https://doi.org/10.1093/jopart/
mut003.
Choi, Taehyon, and Peter J. Robertson. 2014b. Caucuses in collabo-
rative governance: Modeling the effects of structure, power, and
problem complexity. International Public Management Journal 17
(2): 224–54.
Choi, Taehyon, and Peter J. Robertson. 2019. Contributors and free-
riders in collaborative governance: A computational exploration of
social motivation and its effects. Journal of Public Administration
Research and Theory 29 (3): 394–413. https://doi.org/10.1093/
jopart/muy068.
Choi, Taehyon, and Shinae Park. 2021. Theory building via agent-based
modeling in public administration research: Vindications and limi-
tations. International Journal of Public Sector Management 34 (6):
614–29.
Colquitt, Jason A. 2001. On the dimensionality of organizational jus-
tice: A construct validation of a measure. Journal of Applied Psy-
chology 86 (3): 386–400.
Colquitt, Jason A., and Jerald Greenberg. 2003. Organizational jus-
tice: A fair assessment of the state of the literature. In Organiza-
tional behavior: The state of the science, ed. J. Greenberg, 165–210.
Mahwah, NJ: Lawrence Erlbaum Associates Publishers.
Cook, Karen S, and Karen A. Hegtvedt. 1983. Distributive justice, eq-
uity, and equality. Annual Review of Sociology 9: 217–41.
Cropanzano, Russell, David E. Bowen, and Stephen W. Gilliland. 2007.
The management of organizational justice. Academy of Manage-
ment Perspectives 21 (4): 34–48.
Dobbin, Kristin B., and Mark Lubell. 2021. Collaborative governance
and environmental justice: Disadvantaged community represen-
tation in California sustainable groundwater management. Policy
Studies Journal 49 (2): 562–90.
Dobbin, Kristin B., Michael Kuo, Mark Lubell, Darcy Bostic, Jessica Men-
doza, and Ernest Echeveste. 2023. Drivers of (in) equity in collabo-
rative environmental governance. Policy Studies Journal 51: 375–95.
Doberstein, Carey. 2016. Designing collaborative governance deci-
sion-making in search of a ‘collaborative advantage’. Public Man-
agement Review 18 (6): 819–41.
Douglas, Scott, Christopher Ansell, Charles F. Parker, Eva Sørensen,
Paul ‘T Hart, and Jacob Torfing. 2020. Understanding collabora-
tion: Introducing the Collaborative Governance Case Databank.
Policy and Society 39 (4): 495–509.
Emerson, Kirk, and Tina Nabatchi. 2015. Collaborative governance
regimes. Washington, DC: Georgetown University Press.
Fung, Archon, and Erik Olin Wright. 2003. Deepening democracy: In-
stitutional innovations in empowered participatory governance,
vol. 4. New York, NY: Verso.
Getha-Taylor, Heather, Misty J. Grayer, Robin J. Kempf, and Rose-
mary O’Leary. 2019. Collaborating in the absence of trust? What
collaborative governance theory and practice can learn from the
literatures of conflict resolution, psychology, and law. The Ameri-
can Review of Public Administration 49 (1): 51–64.
Gormley, William T., Jr. 1986. Regulatory issue networks in a federal
system. Polity 18 (4): 595–620.
Greenberg, Jerald. 1987. A taxonomy of organizational justice theories.
Academy of Management Review 12 (1): 9–22.
Greenberg, Jerald. 1990. Organizational justice: Yesterday, today, and
tomorrow. Journal of Management 16 (2): 399–432.
Hart, Herbert Lionel Adolphus. 1961. The concept of law. Oxford,
UK: Oxford University Press.
Hauenstein, Neil M. A., Tim McGonigle, and Sharon W. Flinder. 2001.
A meta-analysis of the relationship between procedural justice and
distributive justice: Implications for justice research. Employee
Responsibilities and Rights Journal 13: 39–56.
Head, Brian W., and John Alford. 2015. Wicked problems: Implications
for public policy and management. Administration & Society 47
(6): 711–39.
Hoang, Trang, Jiwon Suh, and Meghna Sabharwal. 2022. Beyond a
numbers game? Impact of diversity and inclusion on the percep-
tion of organizational justice. Public Administration Review 82 (3):
537–55.
Jang, Jeongyeon, Dae Woong Lee, and Giheon Kwon. 2021. An analysis
of the influence of organizational justice on organizational com-
mitment. International Journal of Public Administration 44 (2):
146–54.
Johnston, Erik W., Darrin Hicks, Ning Nan, and Jennifer C. Auer. 2011.
Managing the inclusion process in collaborative governance. Jour-
nal of Public Administration Research and Theory 21 (4): 699–
721. https://doi.org/10.1093/jopart/muq045.
Karpowitz, Christopher F., Tali Mendelberg, and Lee Shaker. 2012.
Gender inequality in deliberative participation. American Political
Science Review 106 (3): 533–47.
Kennedy, Brandy. 2014. Unraveling representative bureaucracy: A sys-
tematic analysis of the literature. Administration & Society 46 (4):
395–421.
Kim, Jangmin, and Saba Siddiki. 2018. Linking diversity of collabo-
rative policymaking venues with procedural justice perceptions: A
study of US marine aquaculture partnerships. The American Re-
view of Public Administration 48 (2): 159–74.
Le, Huy, and Liyao Pan. 2021. Examining the empirical redundancy
of organizational justice constructs. Organizational Behavior and
Human Decision Processes 165: 21–44.
Lebiere, Christian, and John R. Anderson. 2011. Cognitive constraints
on decision making under uncertainty. Frontiers in Psychology 2:
305–7.
Leventhal, Gerald. S. 1980. What should be done with equity theory?
In Social exchange, eds. J. G. Kenneth, M. S. Greenberg and R. H.
Willis, 27–55. Boston, MA: Springer.
Lind, E. Allan, and Tom R. Tyler. 1988. The social psychology of proce-
dural justice. Berlin, Germany: Springer Science & Business Media.
Mani, Bonnie G. 1999. Challenges and opportunities for women to
advance in the federal civil service: Veterans’ preference and
promotions. Public Administration Review 59 (6): 523–34.
Mendelberg, Tali, Christopher F. Karpowitz, and Nicholas Goedert.
2014. Does descriptive representation facilitate women’s distinc-
tive voice? How gender composition and decision rules affect de-
liberation. American Journal of Political Science 58 (2): 291–306.
Moon, Kuk-Kyoung. 2017. Fairness at the organizational level:
Examining the effect of organizational justice climate on collective
turnover rates and organizational performance. Public Personnel
Management 46 (2): 118–43.
Moorman, Robert H. 1991. Relationship between organizational
justice and organizational citizenship behaviors: Do fairness
perceptions influence employee citizenship? Journal of Applied Psy-
chology 76 (6): 845–55.
Mylona, Evangelia, and Dimitrios Mihail. 2019. Enhancing employees’
work performance through organizational justice in the context of
financial crisis. A study of the Greek public sector. International
Journal of Public Administration 42 (6): 509–19.
Nabatchi, Tina. 2010. Addressing the citizenship and democratic
deficits: The potential of deliberative democracy for public


## Page 15

Journal of Public Administration Research and Theory, 2024, Vol. 34, No. 1
15
­administration. The American Review of Public Administration 40
(4): 376–99.
Nowakowski, Jaclyn M., and Donald E. Conlon. 2005. Organizational
justice: Looking back, looking forward. International Journal of
Conflict Management 16 (1): 4–29.
Nozick, Robert. 1974. Anarchy, state, and utopia, vol. 5038. New York,
NY: Basic Books.
O’leary, Rosemary, and Lisa B. Bingham. 2003. Promise and perfor-
mance of environmental conflict resolution. Washington, DC: Re-
sources For the Future.
Osborne, Stephen P. 2006. The new public governance? Public Manage-
ment Review 8 (3): 377–87.
Ostrom, Elinor. 2009. Understanding institutional diversity. Princeton,
NJ: Princeton University Press.
Pirsoul, Nicolas, and Maria Armoudian. 2019. Deliberative democracy
and water management in New Zealand: A critical approach to
collaborative governance and co-management initiatives. Water
Resources Management 33 (14): 4821–34.
Potipiroon, Wisanupong, and Ellen V. Rubin. 2018. Who is most
influenced by justice perceptions? Assessing the role of occupational
status. Review of Public Personnel Administration 38 (3): 271–302.
Pressman, Jeffrey L., and Aaron Wildavsky. 1984. Implementation:
How great expectations in Washington are dashed in Oakland; Or,
why it’s amazing that federal programs work at all, this being a saga
of the Economic Development Administration as told by two sym-
pathetic observers who seek to build morals on a foundation, vol.
708. Oakland, CA: University of California Press.
Rawls, John. 1971. A theory of justice. Boston, MA: Harvard Univer-
sity Press.
Robertson, Peter J., and Taehyon Choi. 2012. Deliberation, consensus,
and stakeholder satisfaction: A simulation of collaborative govern-
ance. Public Management Review 14 (1): 83–103.
Rubin, Ellen. V. 2009. The role of procedural justice in public personnel
management: Empirical results from the Department of Defense.
Journal of Public Administration Research and Theory 19 (1): 125–
43. https://doi.org/10.1093/jopart/mum035.
Rupp, Deborah E., Jyoti Ganapathi, Ruth V. Aguilera, and Cynthia A.
Williams. 2006. Employee reactions to corporate social responsi-
bility: An organizational justice framework. Journal of Organiza-
tional Behavior 27 (4): 537–43.
Sabatier, Paul A., and Christopher M. Weible. 2019. The advocacy
coalition framework: Innovations and clarifications. In Theories
of the policy process, 2nd Ed., ed. P. Sabatier, 189–220. London,
UK: Routledge.
Schusler, Tania M, Daniel J. Decker, and Max J. Pfeffer. 2003. Social
learning for collaborative natural resource management. Society &
Natural Resources 16 (4): 309–26.
Scott, Tyler A., Craig W. Thomas, and José Manuel Magallanes. 2019.
Convening for consensus: Simulating stakeholder agreement
in collaborative governance processes under different network
conditions. Journal of Public Administration Research and Theory
29 (1): 32–49. https://doi.org/10.1093/jopart/muy053.
Siddiki, Saba, Jangmin Kim, and William D. Leach. 2017. Diversity,
trust, and social learning in collaborative governance. Public Ad-
ministration Review 77 (6): 863–74.
Simon, Herbert. 1957. Models of man, social and rational: Mathemat-
ical essays on rational human behavior in a social setting. New
York, NY: Wiley.
Sirianni, Carmen. 2010. Investing in democracy: Engaging citizens in
collaborative governance. Washington, DC:  Brookings Institution
Press.
Steenbergen, Marco R., André Bächtiger, Markus Spörndli, and Jürg
Steiner. 2003. Measuring political deliberation: A discourse quality
index. Comparative European Politics 1 (1): 21–48.
Stivers, Camilla, Sanjay K. Pandey, Leisha DeHart-Davis, Jeremy L.
Hall, Kathryn Newcomer, Shannon Portillo, Meghna Sabharwal,
Eiko Strader, and James Wright, II. 2023. Beyond social equity:
Talking social justice in public administration. Public Administra-
tion Review 83 (2): 229–40.
Sweeney, Paul D., and Dean B. McFarlin. 1993. Workersʹ evaluations
of the “ends” and the “means”: An examination of four models of
distributive and procedural justice. Organizational Behavior and
Human Decision Processes 55 (1): 23–40.
Torfing, Jacob, and Peter Triantafillou. 2013. What’s in a name? Grasp-
ing new public governance as a political-administrative system. In-
ternational Review of Public Administration 18 (2): 9–25.
Welbourne, Theresa M, David B. Balkin, and Luis R. Gomez-Mejia.
1995. Gainsharing and mutual monitoring: A combined agency-
organizational justice interpretation. Academy of Management
Journal 38 (3): 881–99.


## Page 16

© 2024 Public Management Research Association. Copyright of Journal of Public
Administration Research & Theory is the property of Oxford University Press / USA and its
content may not be copied or emailed to multiple sites or posted to a listserv without the
copyright holder's express written permission. However, users may print, download, or email
articles for individual use.

