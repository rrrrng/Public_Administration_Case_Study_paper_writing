# Ready, willing, and able Bureaucratic capacity, slack resources and political co

## Page 1

Journal of Public Administration Research and Theory, 2025, 35, 452–468
https://doi.org/10.1093/jopart/muaf021
Advance access publication 12 July 2025
Article
Ready, willing, and able? Bureaucratic capacity, slack
resources, and political control
Thomas Elston1,*,
, Yuxi Zhang2,
1Blavatnik School of Government, University of Oxford, Oxford, OX2 6GG, United Kingdom
2Global Business School for Health, University College London, London, E20 2AE, United Kingdom
*Corresponding author: Blavatnik School of Government, University of Oxford, Radcliffe Observatory Quarter, Oxford, OX2 6GG, United Kingdom. Email: thomas.
elston@bsg.ox.ac.uk
Abstract
Recent research suggests that bureaucratic responsiveness to political preferences may depend as much on organizational capacity as it does
on incentive alignment, information recovery, and the strategic interaction of principal and agent. Better-resourced bureaucracies should be
more able to comply with new political directions, irrespective of their willingness to do so. But because so much bureaucratic capacity is
sunk into implementing the prior policy commitments of current and former principals, responding to new political signals will depend—much
more specifically—on agents possessing adequate slack resources. This spare capacity should aid signal detection and program development;
decrease hesitance at over-committing to new assignments in volatile environments; and provide resources for implementing changes whilst
maintaining prior commitments. Using two-way fixed-effects regression and a novel dataset of 1,430 legislative requests of the UK executive,
we confirm that possession of slack resources specifically (rather than organizational capacity generally) significantly increases the likelihood of
bureaucracies consenting to make program changes requested by parliament. Agents with slack also commit to more precise timelines for im-
plementation. And survival analysis further reveals that, once committed, bureaucracies with more budgetary slack complete their assignments
more expeditiously.
Key words: bureaucratic capacity; slack resources; survival analysis; accountability; political control.
Introduction
Ensuring that civil service bureaucracies respond to changing
political preferences is a democratic imperative. Alongside
orthodox economic theories of principals, agents, incentives,
and information asymmetry, a small and innovative body of
research has begun to show that bureaucratic responsiveness
may also be explained by organizational capacity (Bolton
and Thrower 2022; Bolton, Potter, and Thrower 2016;
Dasgupta and Kapur 2020; Drolc and Keiser 2020; Huber
and McCarty 2004). In this account, political control depends
not only on “getting the contract right” in terms of incen-
tive alignment and information recovery, but also on ensuring
that bureaucracies are sufficiently resourced to detect, inter-
pret, and respond to new political signals. That is, rather than
posing a necessary risk to a less expert, less attentive, and
easily outmaneuvered principal, agent capacity may actually
assist in minimizing agency loss. In short, civil servants must
be ready, willing, and able.
Within empirical political science, bureaucratic capacity
tends to be a fairly simple construct, measured pragmatically
with little reference to management science. Notwithstanding
some recent objections and innovations (for instance, Bednar
2023; Bersch, Praça, and Taylor 2017; Dasgupta and Kapur
2020), capacity is typically estimated from basic workforce
metrics—often simply the bureaucracy’s headcount, de-
gree of professionalization, or ratio of merit-to-patronage
appointments. And although these measures have so far
proven fruitful in research and reflect how political scientists
conceive of the related concept of legislative capacity (see
Boushey and McGrath 2017; Huber, Shipan, and Pfahler
2001; Woods and Baranowski 2006), management science
would caution against relying exclusively on such simple met-
rics when trying to understand what an organization is “ca-
pable of.”
A further impediment to advancing a theory of respon-
siveness centered on ability is determining which aspects
of bureaucratic capacity are most relevant to detecting and
adapting to new instructions. To date, scholars contributing
to this emerging perspective have largely assumed that the
entirety of an agent’s capacity is freely available to respond
to politicians, leading to total headcount, professionalization,
or similar being adopted as the relevant explanatory vari-
able (Bolton and Thrower 2022; Bolton, Potter, and Thrower
2016; Drolc and Keiser 2020). But this misunderstands the
role of bureaucracies within political systems. In the main,
government ministries and agencies are created and funded in
order to implement the (incumbent or predecessor) principal’s
prior policy commitments—such as welfare entitlements for
the poor, work permits for migrants, regulation of industry, or
healthcare. Because so much capacity is sunk into implementing
this “accumulation” of enduring policy commitments (Adam
et al. 2020; Fernández-i-Marín et al. 2024; Knill, Steinbacher,
and Steinebach 2021), and because those resources cannot
be immediately redeployed without incurring significant legal,
political and organizational costs, the civil service is greatly
constrained in how it can respond to additional instructions.
© The Author(s) 2025. Published by Oxford University Press on behalf of the Public Management Research Association.
This is an Open Access article distributed under the terms of the Creative Commons Attribution License (https://creativecommons.org/licenses/by/4.0/),
which permits unrestricted reuse, distribution, and reproduction in any medium, provided the original work is properly cited.


## Page 2

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
453
As a result, political control should depend less on total bu-
reaucratic capacity than on what fraction of this is “left over”
once current unavoidable commitments are met.
Take, for example, the largest public service bureaucracy
in the UK: the English National Health Service (NHS). With
some 1,500,000 employees, 140,000 hospital beds, and 3,000
operating theatres, this gargantuan organization has remark-
able levels of capacity. But the continuing demand on that
capacity is also immense: in every 36-hour period, NHS organ-
izations interact with more than one million patients. When
politicians desire healthcare reform, therefore, the need to
maintain a ceaseless “business-as-usual” operation is a signif-
icant drag on resourcing any new policy ideas (Elston 2024).
And although it might be assumed that larger bureaucracies
are more prone to accumulating spare resources that can be
diverted to innovation purposes when the need arises (in which
case, total capacity would be a proxy for “slack” resources),
the correlation is unstable. Indeed, as figure 1 illustrates, for
the sample of UK government bureaucracies that we analyze
below, there is no discernible relationship between headcount
and three distinct measures of slack (explained later).
Our aim in this article is therefore to extend but reorient the
recent turn to capacity-based explanations of political con-
trol by developing a more precise and authentic account of
how bureaucratic capacity affects responsiveness. Firstly, we
posit that slack resources—those “in excess of current busi-
ness requirements” (Bentley and Kehoe 2020, p. 181)—will
help bureaucracies to detect signals from politicians, develop
change programs, and secure agreement among different in-
ternal constituencies. This is consistent with much manage-
ment research indicating that organizational slack facilitates
external attentiveness, innovation processes, and internal
deal-making (Carnes et al. 2019; Daniel et al. 2004; Mount
et al. 2024). Next, since slack also acts to “buffer” organiza-
tions from environmental perturbations (Leuridan and Demil
2022; Moulick and Taylor 2017; O’Toole and Meier 2010),
we further expect that possession of surplus resources will
decrease bureaucrats’ hesitance at over-committing to new
policy assignments in volatile environments. This should lead
to more precise commitments on timeframes for delivering
the requested changes. And finally, slack should also pro-
vide a more-or-less accessible stock of resources necessary
for completing these tasks, resulting in more expeditious im-
plementation. Overall, our claim is that politicians will ob-
tain greater responsiveness—on multiple dimensions—from
bureaucracies in possession of slack resources specifically,
rather than organizational capacity in general.
We test our theory on a novel dataset consisting of more
than 1,400 exchanges between the UK parliament and ex-
ecutive during 2010–2015, and a panel measuring slack re-
sources and assignment acceptance, anticipated timelines, and
completion for 49 government organizations during 2010–
2020 (to allow time for implementing each assignment). We
capture the legislature’s requests by focusing on the work
of the Public Accounts Committee. During 2010–2015, this
committee published 244 inquiry reports containing 1,674
separate asks of the bureaucracy, of which we analyze 1,430
relating to 49 ministries and agencies. For each request, we
record the organization’s response to the committee (i.e.,
whether it agrees to implement the change), the timeframe it
commits to, and each of its progress updates until completion.
As for the measurement of slack resources, we employ a com-
bination of financial, personnel, and workforce-survey data.
We measure the degree of underspend in each organization’s
Figure 1. Relationship between total headcount and three measures of slack resources. Slack variables are standardized within the range of −1 to 1,
with extreme outliers not shown. Bureaucracies are ranked by average staff size during 2010–2015, with smaller organizations at the bottom. Whisker
plots depict the range of within-organization variation in slack for each year 2010–2015. Organizational acronyms are defined in Appendix I.


## Page 3

454
Journal of Public Administration Research and Theory
administration budget, taking larger surpluses to indicate
greater capacity for extra work. We also calculate the man-
agement overhead of each organization, since, in the short
term, manager time is more fungible than that of frontline
staff (O’Toole and Meier 2010). And we use the annual civil
service staff surveys to measure perceived workload in each
organization over time.
Using two-way fixed-effects regression, we confirm that
both budgetary slack and worker-reported slack corre-
late with substantially higher predicted probabilities of
bureaucracies consenting to the Public Accounts Committee’s
requests. For each unit increase in budgetary slack, the av-
erage marginal effect on the probability of acceptance rises
by 26 percent; and for worker-reported slack, the figure is
31 percent per unit increase. Departments and agencies with
higher budgetary slack also propose more precise timelines
for completion, consistent with our view of slack as hedging
against over-commitment. And finally, survival analysis
reveals that organizations with more slack are significantly
more expeditious in delivery. At any given instant, the prob-
ability of an outstanding commitment being fulfilled (i.e., no
longer “surviving” in the dataset) is 54 percent higher when
there is one additional unit of budgetary slack. And where an
organization experiences a year-on-year increase in adminis-
trative budget, there is a 48 percent higher probability of it
fulfilling its assignment than otherwise. By contrast, a conven-
tional “headcount” measure of capacity is a poor predictor
of all three outcomes (acceptance, commitment, completion).
The remainder of the article proceeds as follows. The second
and third sections elaborate our core argument. The fourth
section describes our empirical case, the fifth introduces our
data and methods, and the sixth presents our results and ro-
bustness checks. Finally, we discuss implications, limitations,
and future research priorities.
Capacity and political control
Control of civil service bureaucracies has long been regarded
as a prototypical principal-agent problem, in which the in-
fluence of elected officeholders over policy implementation
hinges on the intensity of goal conflict and hidden informa-
tion, and the feasibility of curbing opportunism through ef-
fective contracting (see reviews in Brierley et al. 2023; Miller
2005; Moe 2012; Wood 2010). Questions of organizational
capacity are not entirely absent from this literature; but, in
the main, researchers have focused on the principal’s capacity
for writing detailed instructions, monitoring performance
directly or through third parties, and generally producing a
credible threat against bureaucratic rent-seeking (Aberbach
1990; Appeldorn and Fortunato 2022; Boushey and McGrath
2017; Huber, Shipan, and Pfahler 2001; Lillvis and McGrath
2017; Woods and Baranowski 2006). The agent’s capacity, by
contrast, whilst assumed to both motivate the decision to del-
egate in the first place and yet pose an inherent threat to the
principal’s interests (Bawn 1995; Ting 2011), has received far
less theoretical or empirical attention. Indeed, raising the ques-
tion of agent capacity only seems to have accelerated research
interest into whether politicians have sufficient resources to
deploy effective countermeasures against civil servants.
Huber and McCarty (2004, p. 481) were among the first
to turn attention to the potential enabling role of bureau-
cratic capacity in securing political control. As they argued,
“the information problem has dominated the existing delega-
tion literature, whereas the capacity issue has been essentially
ignored.” And although preferences remained firmly part
of Huber and McCarty’s formal theory of responsiveness,
which models bureaucrats as unmotivated to comply with
instructions in low-capacity contexts, their general critique
struck a chord more widely and provoked some scholars
to advocate distinguishing bureaucratic interests and ability
more clearly (e.g., Krause 2010; Krause and Woods 2014;
Moe 2012).
Although empirical projects taking this agenda forward
were slow to emerge, two studies in the US made notable
advances. Focusing on the quantity and quality of human re-
sources in social security agencies, Drolc and Keiser (2020, p.
774) show that increased oversight by national and state-level
politicians is effective only if bureaucratic capacity is also
high. “Agencies need internal capacity,” they conclude, “to re-
spond to the signals and pressure from elected officials….”
Similarly, Bolton, Potter, and Thrower (2016, p. 242) analyze
leader turnover, workforce size, and workload at the Office
of Information and Regulatory Affairs to suggest that: “the
political control apparatus of the administrative state is fun-
damentally constrained by organizational capacity. … [T]he
implementation of political goals is stymied in low-capacity
organizations.” Both studies add credence to Huber and
McCarty’s (2004, p. 484) earlier, unorthodox conjecture that:
“the politician can often induce a better action from a high-
capacity ‘enemy’ bureaucrat (with an ideal point far from the
politician’s) than from a low-capacity ‘friendly’ bureaucrat.”
But this type of work remains rare, and the potential for com-
bining the inchoate political science on capacity and control
with more established concepts from management science is
yet to be explored.
Organizational capacity is notoriously difficult to con-
ceptualize and measure. Unlike organizational performance,
which is a retrospective metric, capacity is future-oriented
and somewhat speculative—a “prospective ability” (Bednar
2023, p. 2) denoting “the range of possible implementa-
tion levels” that might be achieved by an organization
(Benn 2023). To date, the pragmatic response from polit-
ical scientists has been to measure the size, composition, or
perceived quality of the bureaucracy’s workforce as proxies
for its capacity. While this mirrors the approach taken in
studies of legislative capacity (e.g., Boushey and McGrath
2017; Huber, Shipan, and Pfahler 2001), it is not without
critics (Bednar 2023; Williams 2021). Moreover, it is not
clear that capacity in legislatures, which are largely con-
cerned with producing new policy (see Bucchianeri, Volden,
and Wiseman 2024), should determine how capacity in
bureaucracies is measured, these being mainly established
and funded to meet past policy commitments. Scholars have
long suspected that legislators tend to prioritize new policy
creation over the dismantling of old policies (Bardach 1976),
and recent empirical work has found the effect of this to be
the gradual “accumulation” of public policies and progres-
sive “overburdening” of the administrative state (Adam et al.
2020; Fernández-i-Marín et al. 2024; Knill, Steinbacher, and
Steinebach 2021; Mettler 2016). In consequence, as Krause
(2010, p. 539) observes, “many bureaucratic agencies are
sufficiently occupied with present policy and administrative
tasks such that they are not in a position to want or seek
additional responsibilities.”


## Page 4

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
455
To begin to accommodate these “business-as-usual”
constraints on bureaucratic responsiveness, several recent
quantitative studies of bureaucratic capacity have controlled
for “current workload” (Bednar 2023; Bolton, Potter, and
Thrower 2016; Dasgupta and Kapur 2020). And even in the
realm of legislative capacity for executive oversight, Aberbach
(1990, p. 69) has suggested that this might be most effective
among congressional committees with “excess” staff and
“slack resources.” It is this line of thinking that we now seek
to develop.
Slack resources and bureaucratic
responsiveness
All organizations must acquire and coordinate resources in
order to pursue their objectives (Barney and Clark 2007;
Lee and Whitford 2012). Organizational slack arises when
the stock of resources held (or potentially held) exceeds “the
minimum necessary to produce a given level of organiza-
tional output” (Nohria and Gulati 1997, p. 604). In other
words, slack is “the difference between total resources and
total necessary payments” (Cyert and March 1963, p. 36)—
although, in practice, measuring this surplus is complicated
by uncertainties over what activities are truly necessary
(rather than discretionary) for maintaining the organization’s
objectives, and what minimum level of inputs is required to
achieve those necessities.
It is usual in management science to distinguish between
“available,” “recoverable,” and “potential” slack, according
to how readily the surplus can be accessed and put to use
(Bourgeois and Singh 1983; Mount et al. 2024). As Cheng
and Kesner (1997, p. 2) explain, “Available slack consists of
resources that are not yet committed to organizational design
or a specific expenditure (e.g., excess liquidity).” Recoverable
slack, by contrast, involves “resources that have already been
absorbed into the system operation as excess costs (e.g., excess
overhead expenditures).” Only through reform can managers
extract and then redirect this kind of surplus. Finally, “poten-
tial slack consists of future resources that can be generated
from the environment by raising additional debt or equity
capital.” We exclude this subtype from discussions hereafter.
There are a number of routes by which available and re-
coverable slack accumulate in organizations (Sharfman et al.
1988). Slack may be deliberately sought by managers, either
as a “buffer” against unpredictable or adverse events (Bradley,
Shepherd, and Wiklund 2011; McCrea 2022; Yılmaz, Özer,
and Günlük 2014) or to provide a more benign environment
for task completion (Bradshaw et al. 2007; Busch 2002).
The organization’s internal and external control apparatus
should moderate this. In addition, since excess resources are
consumed by running operations at anything other than op-
timal efficiency, all organizations are prone to accumulating
some degree of recoverable slack, known by economists as
X-inefficiency. The complexity of the organization’s tech-
nology, dynamic variation in demand for its output, the com-
petitiveness of its operating environment, and, again, the
effectiveness of the control apparatus will all influence slack
accumulation (Jensen 1993; Ruggiero, Duncombe, and Miner
1995; Sharfman et al. 1988). And in public bureaucracies spe-
cifically, slack may also depend on general fiscal conditions,
past public management reforms that prioritize cost-cutting,
the attentiveness of oversight authorities to the matching of
supply and demand, or political attitudes toward contingency
staffing and “rainy day” funds (Leuridan and Demil 2022;
O’Toole and Meier 2010).
A vast literature in management science investigates the
impact of slack resources on the decision-making and per-
formance of (particularly business) organizations (for reviews
and/or meta-analyses, see Carnes et al. 2019; Daniel et
al. 2004; Mount et al. 2024). Many studies find that those
with more slack tend to respond more rapidly and substan-
tively to signals from their external environments, including
from shareholders and customers (Bowen 2002; Cheng and
Kesner 1997; Xiao et al. 2018). As Bourgeois (1981, p. 30)
explains, slack resources “allow an organization to adapt suc-
cessfully to internal pressures for adjustment or to external
pressures for change in policy.” In particular, slack releases
managers from being preoccupied with business-as-usual, ei-
ther because production of a surplus provides reassurance
that current organizational routines are effective, or because
slack hedges against any operational mistakes that may re-
sult from a period of management inattention.1 As a result,
slack increases opportunities for horizon scanning and inquis-
itive “slack search,” rather than conventional “problemistic”
search driven by specific errors in current operations.2
Moreover, slack may also increase the organization’s ability to
overcome “strategic discord” between internal constituencies
advocating different priorities (Bourgeois and Singh 1983, p.
43). With surplus resources in hand, investing in one proposal
is less contingent on disinvesting in others. And when slack
is available to absorb any mistakes resulting from innova-
tion, governance of resource allocation tends to be more re-
laxed and “the legitimacy of experimenting is less likely to be
questioned” (Singh 1986, p. 567).3
Interpreting this canon of knowledge in light of the
question of civil service responsiveness, we expect public
bureaucracies with more slack resources to be more attentive
to shifts in political preferences, better placed to interpret and
explore their implications for current and future operations,
and less constrained in what new projects they can “take on”
and agree internally whilst still meeting other obligations. We
thus hypothesize:
H1: Bureaucracies with greater organizational slack will
agree to implement more political requests than those with
less slack.
We also expect bureaucracies with slack resources to make
firmer commitments about when the agreed changes will be
implemented. One of the primary functions of slack is to
“buffer” organizations against environmental perturbations
by providing a stock of resources to deal with unexpected
1As Nohria and Gulati (1997, p. 605) explain, “In tight organizations with
little slack, managerial attention is likely to be consumed by short-term per-
formance issues,” since there is little margin for error. On the other hand,
“slack … buffers organizations from downside risk” (Singh 1986, p. 567)
2As Vanacker, Collewaert, and Zahra (2017, p. 1309) argue, slack “allows
managers to explore projects … that would not have been approved in the
face of resource scarcity.”
3Indeed, as Cheng and Kesner (1997, p. 3) argue, “When resources are tight,
organizational members spend a great deal of time forming coalitions and
bargaining for their fair share of resources.” But when slack abounds, “there
will be a solution for every problem” (Moch et al. 1977, p. 356) and a
commensurate reduction in infighting. Moreover, governance and decision-
processes differ in the two scenarios. Greater control and corporate disci-
pline is required in low slack environments, resulting in more formalized,
centralized, and robust processes of investment approval (Nohria and
Gulati 1997; Singh 1986).


## Page 5

456
Journal of Public Administration Research and Theory
problems as they arise (Bradley, Shepherd, and Wiklund 2011;
McCrea 2022; Yılmaz, Özer, and Günlük 2014). Indeed,
Bourgeois (1981, pp. 29, 30) refers to slack as an “absorp-
tion mechanism” that “prevents a tightly wound organization
from rupturing in the face of a surge of activity.” In the pres-
ence of slack, therefore, we expect more confident predictions
from bureaucrats about the time required for delivery, safe in
the knowledge that the agency is well placed to both deliver
the new assignment and meet any additional but as yet un-
known challenges as they arise. Conversely, where additional
commitments are taken on in the absence of slack but in full
knowledge of environmental volatility and the likelihood
of unplanned-for disruptions during the execution period,
bureaucrats will include a “safety valve” in their commitment
to politicians by specifying more vaguely the timeframe for
task completion. Then, should the need arise, progress on
the assignment can be paused when other priorities emerge,
without contract violation. Hence:
H2: Bureaucracies with greater organizational slack
will commit to a more explicit and precise timeline for
completing political requests.
Lastly, once committed, organizations in possession of slack
resources will complete their assignments more rapidly than
those lacking surplus capacity. In particular, if staff, materials,
or cash can be redeployed to non-routine purposes relatively
easily, task completion should be more straightforward and
less intermittent and interrupted than if managers must con-
tinually “beg and borrow” from other teams and budgets in
order to advance the new project. As Bourgeois (1981, p. 31)
argues, “slack is an agent of top management in … executing
strategic change.” Therefore:
H3: Bureaucracies with greater organizational slack will
more rapidly complete the political requests they have ac-
cepted for implementation.
Empirical context
To test this more constrained account of how organizational
capacity should affect bureaucratic responsiveness, we ana-
lyze how departments and agencies in the UK civil service
respond to requests for program changes made by the House
of Commons’ Public Accounts Committee. The PAC is the
oldest, most prolific, and, reputedly, most influential over-
sight committee in the UK parliament (Cooper, Elston, and
Bilous 2024; Dewar and Funnell 2016; Elston and Zhang
2023). The PAC consists of 14 backbench legislators, and
receives financial audits and value-for-money reports from
the 800 staff of the National Audit Office (the UK’s “supreme
audit institution”). The committee then interrogates the most
senior bureaucrats—particularly “accounting officers,” who
have personal responsibility for financial propriety in their
department/agency—and finally issues a further public re-
port requesting changes to the design and/or operation
of government programs. During the 2010–2015 parlia-
ment, the PAC published 244 reports, making on average 7
recommendations in each (max. 18, min. 1) and generating
in total 1,674 separate requests of the bureaucracy. After
excluding recommendations to wholly independent organi-
zations, like the BBC and Royal Household, 1,430 requests
remain, directed toward 49 departments and agencies (see
figure 2). (See Appendix III for illustrative examples of PAC
recommendations.)
Typically, this process commences with the NAO
investigating some aspect of government activity, selected
by the Comptroller and Auditor General—a technocrat with
a ten-year, non-renewable appointment, designed to ensure
the NAO’s independence from both parliament and execu-
tive. (Very occasionally, the PAC will issue a report without
prior NAO research.) After the NAO’s findings are published,
the PAC holds one or more public hearing(s) to receive oral
testimony from officials (almost never ministers) about
program implementation, before publishing a report with
recommendations. Government then responds to each PAC
report within 2–3 months of its publication, accepting or
rejecting each request on behalf of each named bureaucracy.
In cases of acceptance, a timeline for the work’s completion
may also be provided. Thereafter, the Treasury publishes pe-
riodic “progress reports” on outstanding commitments, so
that the implementation of each unfinished assignment can
be tracked until the bureaucracy itself (not the PAC, nor the
NAO) regards the action as completed (see Elston and Zhang
2023).
Based on these arrangements, we can measure three rel-
evant dimensions of bureaucratic responsiveness to a high-
profile legislative committee—agreement to implement a
program change, commitment to a timeframe, and the ac-
tual time until completion. This provides the opportunity
to study the impact of both inter-organizational and lon-
gitudinal variation in slack on political control for a wide
range of departments and agencies. It is also important to
note that, in the British system where a strong executive
dominates in both the proposing of legislation and the set-
ting of budgets, the PAC has no role in allocating resources to
the organizations that it makes requests of. Appropriations,
although ultimately authorized by parliament, are the result
of (typically) annual negotiations between budget holders
throughout government and HM Treasury as the finance
ministry.4
Data and empirical strategy
To test our hypotheses, we employ a combination of regres-
sion (at both the organizational and request level) and sur-
vival analysis. We use a purpose-built dataset describing: each
PAC request and government response during the 2010–2015
parliament; progress during implementation up to 2020; and
the attributes of each mentioned bureaucracy, including four
time-varying measures of slack.
Dataset
Dependent variables
Using the PAC’s 244 inquiry reports, we established a data
frame in which each row corresponds to an individual com-
mittee request (clustered by the report from which it came)
and each column records case attributes, beginning with the
4It is conceivable that budget holders might invoke challenging PAC
demands in their budget negotiations with the finance ministry, but this
seems unlikely given the differing timelines involved and the Treasury’s
long-standing position that extra in-year expenses—even very significant
changes, like higher pay settlements for public sector employees—should be
funded from within existing budgets.


## Page 6

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
457
identity of the responsible organization.5 Then, using the gov-
ernment reply to the committee, we record whether the de-
partment or agency fully agreed, partly agreed,6 or disagreed
with the request.7 For the organization-level analysis, these
responses were coded as 3, 2 and 1, respectively, and then
averaged within years to create acceptance scores, where
higher values indicate greater compliance with the com-
mittee. For the recommendation-level analysis, the response
categories were collapsed into an acceptance dummy, where
“1” indicates unqualified consent to the requested changes
and “0” indicates otherwise.
In addition, we recorded the bureaucracy’s “target imple-
mentation date” for completing the agreed actions, from which
we coded a timeline precision variable. Here, a higher score
indicates a more precise commitment (e.g., day-month-year,
month-year)8 while a lower score indicates a vague or highly
contingent timeline (e.g., season-year, year, or “when legisla-
tive time allows”). Finally, switching from the initial response
documents to the Treasury’s 14 “progress reports” up to
November 2020, we add to the dataset every update provided
by the bureaucracy for every outstanding action, up to and in-
cluding the date at which the assignment switches from being
reported as “in progress” to “completed.” This panel forms the
basis of our survival analysis, as explained below.
Independent variables
Various measures have been used to estimate slack in busi-
ness organizations, the most common being accounting ratios
measuring liquidity or administrative costs (see Mount et al.
2024).9 For the public sector, empirical studies of slack are
rare and lack consensus on measurement. We therefore adopt
a cautious approach by testing four different measures from
three separate data sources, informed by prior public and pri-
vate sector research.
Firstly, to capture the cash resources readily available
to bureaucrats when taking on extra workload, we calcu-
late the annual budget underspend in each organization.
(Overspending is unlawful and extremely rare in our context.)
This is known as “budgetary slack” (Davila and Wouters
2005).10 Where the underspend is low, the organization has
Figure 2. Distribution of 1,430 PAC requests by government organization, 2010–2015. Organizations are ranked by the mean number of requests
received per year.
5Where multiple organizations are named, we assigned a lead organization
based on where the predominant responsibility lay.
6Partly agreed also includes “welcomed” or “noted.”
7Among the 1,430 PAC requests, 74.7 percent are fully accepted, 10.6 per-
cent are fully rejected, and 14.7 percent are partially accepted. No organ-
ization that received more than six requests chose to accept all of them
during 2010–2015, and most in this category are small arm’s length bodies
excluded from the regressions due to missing slack data.
8Organizations that immediately complete their assignment before even
notifying the committee of their intention to do are also scored highly on
this commitment variable.
9Among the most common are the “current ratio” (current assets divided by
current liabilities) to measure available slack, and administrative expenses
divided by sales to measure recoverable slack.
10This measure is also closely related to the "surplus fund balance" measure
of slack in Moulick and Taylor (2017) and Fan, Meng, and Wei (2020), al-
though in those cases underspends are carried over from one financial year
to the next whereas those in our dataset are not.


## Page 7

458
Journal of Public Administration Research and Theory
little capacity for extra work; where it is high—and so man-
agement could have chosen to incur additional, already-
authorized expenditure—the organization is in possession
of “available” slack proportionate to the size of the budget
foregone. To compute this variable, we use budget documents
issued biannually by HM Treasury toward the start and end
of each April-March financial year, alongside outturn data
published the following July by individual departments and
agencies. To restrict our measure to the policymaking part
of each organization and exclude, for example, welfare
payments, grants to businesses or local government, and other
non-commutable “program” costs, we include only “adminis-
trative” expenditure, which relates to the cost of running the
department or agency (see HM Treasury 2011, p. 202). We
calculate a continuous budgetary slack variable as the final
administration budget minus the end-of-year expenditure
outturn for administration, scaled by that same year’s initial
budget. As is common in studies of slack (e.g., Marlin and
Geiger 2015; Wiersma 2017), we lag our dependent variables
against the numerical budgetary slack variable by one year
so that a response to the PAC in 2012 is matched with that
bureaucracy’s budgetary slack for 2011. This helps to exclude
the possibility of reverse causality by ensuring strict temporal
ordering of the decision-making process that we study.
Secondly, we also create a dummy variable, budgetary
increase, which measures growth (1) or not (0) in the admin-
istration budget during the financial year of the PAC’s request
compared with the previous year, after adjusting for infla-
tion using the Office for Budget Responsibility’s deflator. This
dummy echoes Bourgeois’s (1981, p. 37) distinction between
“slack gainers” and “slack losers,” and reflects the idea that
decision-makers will more likely know their organization’s
general slack trajectory than precise real-time position, and
so will use trajectory as a shortcut for decision purposes.
Stationary or shrinking budgets are taken as indicating a re-
duction in slack, assuming that organizational output of com-
parable scale must be achieved in the present period as in the
last, but with less input (after accounting for inflation). This is
consistent with the literature on policy accumulation (Adam
et al. 2020; Fernández-i-Marín et al. 2024; Knill, Steinbacher,
and Steinebach 2021), but ignores the potential for produc-
tivity gains to compensate for budgetary loss. Since the dummy
variable already reflects changes from the previous year to the
current year, it is not lagged against our dependent variables.
Thirdly, we obtained for each department and most agencies
the number of (full-time equivalent) staff employed each year,
and their seniority, using the annual Civil Service Statistics.
From this, we specify a continuous overhead slack variable
measuring the managerial cadre (in grades 6 and above) rel-
ative to total headcount. Many prior studies compare ad-
ministrative to total resourcing (variously defined) in order
to gauge how much “recoverable” slack is absorbed in the
organizational structure (Cheng and Kesner 1997; Wiersma
2017). By focusing on the managerial component of the ad-
ministrative workforce, we follow O’Toole and Meier (2010)
and Melton and Meier (2017) in regarding managers as pro-
viding organizations with partial slack capacity to the extent
that, in the short term, they can be diverted from their routine
tasks without significant detriment to current performance—
at least when compared with the immediate negative impact
of rationing frontline personnel. This notion of “storing slack
in administrative capacity” (O’Toole and Meier 2010, p. 345)
develops Henry Mintzberg’s (1983, p. 126) earlier observa-
tion that “there [is] a good deal of slack in … ‘hierarchical
expense.’” It is also consistent with Bourgeois’s (1981, p.
34) suggestion of using administrative intensity as a proxy
for organizational slack. Of course, some managerial tasks
(like coordination of frontline staff or the resolution of com-
plex cases) have more immediate performance consequences.
Moreover, in the long-term, postponing routine managerial
work (performance reviews, data analysis, planning, etc.) and
deferring what Etzioni (1960) calls “organizational mainte-
nance,” would be expected to damage performance. This is
perhaps why O’Toole and Meier (2010, p. 345) refer to man-
agerial capacity as only “partial slack.” Still, organizational
slack is typically conceived myopically in terms of excess re-
sources with respect to the “immediate production function”
(McHugh and Cross 2021, p. 1). Again, we lag the govern-
ment response to PAC requests against this numerical over-
head slack variable by one year.
Finally, we use the annual Civil Service People Survey,
which regularly achieves >350,000 responses from officials
employed in >100 government organizations, to measure
workforce perceptions of slack. In existing literature,
survey measures typically ask managers to estimate budget
achievability based on demands on the team and the resources
available (e.g., Nohria and Gulati 1997). Building on this, our
worker-reported slack variable measures the mean percentage
of employees (not just managers) agreeing or strongly agreeing
that they “have an acceptable workload” and “a good work–
life balance” during the survey window (September-October
each year). High workload and poor work–life balance imply
that task demands closely match or even exceed available re-
sources, indicating low slack in the employing organization,
and vice-versa. Data availability mirrors that for our over-
head slack variable, but we do not lag this variable on the
understanding that employee workload perceptions are more
subjective and possibly more transitory, and that managerial
responses to them are likely to be more immediate.
Figure 3 summarizes our principal slack measures for the
period 2010–2015. Here and in all model specifications the
three continuous variables are rescaled to the range [−1,1], to aid
comparability. The median and interquartile ranges are shown,
with dots indicating years with slack outside the interquartile
range. Organizations are ranked by the mean of each slack var-
iable. Overall, worker-reported slack tends to vary most across
organizations, with a span of 1.75-point on the standardized
scale. This is followed by budgetary slack (1.25-point span),
and then by overhead slack (0.75-point span). Both budgetary
and worker-reported slack also show considerable within-
organization variation over time, whereas managerial staff tend
to occupy a more consistent share of each organization’s work-
force. In line with much empirical research (Wiersma 2017), our
various measures of slack are uncorrelated.11
Control variables
During our main timeframe of 2010–2015, there was a single
chair of the PAC, a single head of the NAO, and only one prime
minister and deputy prime minister, chancellor (finance minister),
home secretary and foreign secretary, and a general slowing in
the rate of turnover in other ministerial positions. Because the
11For example, organizations might have low cash reserves but a good
work–life balance and/or high overheads.


## Page 8

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
459
challenge of planning and implementing the committee’s requests
may vary by the type of policy change involved (Benton and
Russell 2013), we include a manually-coded six-point categorical
variable capturing the type of action required, adapting Benton
and Russell’s general coding scheme for the PAC’s value-for-
money remit (see Elston and Zhang 2023). In addition, because
joint working between two or more organizations may increase
bargaining, compromise and even free-riding during the agree-
ment and execution processes, we include a dummy variable of
collaboration requirement. This takes a value of “1” if the PAC
instructed the organization to work with external partners, and
“0” if otherwise. Both variables were coded by the authors and
three research assistants following detailed protocols and using a
blind double-coding inter-coder reliability procedure (Elston and
Zhang 2023). Finally, organization and calendar year control
dummies are included in all regression models. And to allow us
to compare the explanatory power of our slack variables against
the more conventional measure of bureaucratic capacity, we also
include organization headcount (full-time equivalent).
A detailed description of all variables is provided in
Appendix II, along with descriptive statistics in Appendix IV.
Empirical strategy
To test whether slack resources increase the chance of
bureaucracies consenting to politically-requested changes
(H1), we employ two strategies. We start with the unit of
analysis as the organization-year, aggregating the base unit
of our main dataset (the PAC request) to produce an annually
pooled score of acceptance for each department and agency
during 2010–2015. This facilitates direct comparisons with
existing studies of capacity and responsiveness (e.g., Drolc
and Keiser 2020). We then disaggregate to the level of indi-
vidual recommendations, using logistic regression to estimate
the likelihood of an individual request being accepted (or
not) by the relevant bureaucracy, now controlling for the
properties of the individual requests (e.g., type of action) and
so better isolating the effect of slack on bureaucratic compli-
ance. We continue at this more granular level when testing the
effect of slack on commitment to implement (H2), replacing
the agree-disagree dummy with the timeline precision vari-
able and using both OLS and multinomial logit models. All
these models include fixed effects by organization and cal-
endar year. The two-way fixed effect guards against unknown
sources of heterogeneity; for example, staff morale in par-
ticular bureaucracies, political events in a particular year, or
the economic trend. Because the Breusch-Pagan test indicates
that heteroskedasticity is present, all models in Tables 1–3 are
presented with robust standard errors clustered by organiza-
tion in parentheses (see Abadie et al. 2022).
To explore the effect of slack resources on timeliness of as-
signment completion (H3), we perform survival analysis. This
technique has gained increasing attention in the social sciences
for its unique strengths in understanding the timing of an
event or the persistence of a status quo. As noted, our dataset
includes repeated observations on the progress of more than
1,000 accepted assignments until the point at which the bu-
reaucracy reports completion. Hence, the “event” we try to
predict is the conversion of a request from “still outstanding”
to “completed.”
One challenge in implementing the survival analysis is the
issue of censoring. This arises when the event of interest is
unobserved for some cases; for example, because it occurs
before the observation period commences, known as left
censoring, or after it ends, known as right censoring (Turkson,
Ayiah-Mensah, and Nimoh 2021). Left censoring in our data
involves immediate completion of the assignment before the
Figure 3. Organizations and slack, 2010–2015. Slack variables are standardized to the range of −1 to 1, with extreme outliers not shown.


## Page 9

460
Journal of Public Administration Research and Theory
government has even issued its initial response to the PAC;
and right censoring arises, more rarely, when completion
occurs after our dataset expires in November 2020. Both
types of case are dropped from the survival analysis. We also
have the problem of interval censoring, which occurs when
the event is known to have occurred within a specific time
interval (i.e., between publication of the current and previous
progress report), but the exact timepoint is unknown. To ac-
commodate interval censoring, we infer the completion date
as a random variable occurring within the certain time range,
following recent developments in biostatistics (Rodrigues et
al. 2018; Zhang and Sun 2010).
A second challenge is the inclusion of time-variant
covariates. As noted, organizational slack varies longitudi-
nally as well as inter-organizationally. One option is simply
to calculate a slope across multiple years and use this to pre-
dict the event of completion. However, following Therneau,
Crowson, and Atkinson (2024), a more robust solution is
to further disaggregate our original one-row-one-case data
frame so that every update for every accepted assignment
occupies its own row. We then populate each row with time-
varying organizational covariants corresponding to the spe-
cific financial year in which that update was published (or the
prior year, in the case of lagged variables). In this way, we re-
tain maximum granularity and the model estimation becomes
more reliable since covariates are only used to predict events
(or non-events) in consecutive periods, rather than assuming
longer-range associations.
Results
Slack and agreement to new assignments
Table 1 reports the results of OLS regressions in which the
dependent variable is the organization-level average accept-
ance score. Although this analysis does not utilize our more
granular, request-level dataset, it facilitates direct comparisons
with existing studies of capacity and responsiveness, and so
provides a useful starting point. Independent variables meas-
uring budgetary, overhead and worker-reported slack are
added separately in models (1) to (3), and then in combina-
tion in column (4) to compare effect sizes and significance.
Consistent with Hypothesis 1, worker-reported slack posi-
tively correlates with the acceptance score, and its statistical
significance holds across all models. The negative effect of
overhead slack was not hypothesized, although is not signif-
icant. The headcount measure of organizational capacity has
no effect on acceptance scores.
Next, Table 2 reports logistic regressions conducted at the
request level. We retain all covariates from Table 1, but add
collaboration requirement and type of action controls. Now,
budgetary slack and workforce-reported slack are signifi-
cantly and positively correlated with acceptance. Overhead
slack continues to have a consistent but unexpectedly nega-
tive impact on acceptance, although again is not statistically
significant. Unlike existing studies, organization headcount is
negatively related to responsiveness, although it is also not
significant.
To assess whether the robustness of our results depends on
the linearity assumption of the two-way fixed effects logistic
model (Imai and Kim 2021), we re-estimated our models using
the Poisson Pseudo Maximum Likelihood (PPML) approach
with high-dimensional fixed effects. The results, presented in
Appendix V Table A, confirm that our main conclusions remain
robust even when the functional form assumptions are relaxed.
To help interpret Table 2, figure 4 plots the marginal effect
at the mean (MEM) of each slack variable, noting the average
marginal effect (AME) at each x-axis label. Grey shadows de-
pict the 95 percent confidence intervals. Commencing with
AME, acceptance is shown to be 26 percent more likely for
each unit increase in the bureaucracy’s budgetary slack. This
is significant at the 99.9 percent level. Acceptance is also 10
Table 1. Slack and acceptance of PAC requests: organization-level OLS regression.
Dependent variable
Acceptance score
(1)
(2)
(3)
(4)
Budgetary slack
0.06 (0.23)
P = .78
0.18 (0.31)
P = .56
Budgetary increase
0.15 (0.15)
P = .34
0.21 (0.15)
P = .17
Overhead slack
−0.55 (1.25)
P = .66
−0.45 (1.27)
P = .72
Worker-reported slack
0.46 (0.22)
P = .04
0.48 (0.18)
P = .01
Organization headcount
−1.08 (0.84)
P = .20
−0.92 (0.78)
P = .24
−0.64 (0.78)
P = .41
−0.87 (0.96)
P = .37
Constant
1.76 (0.62)
P = .01
1.58 (1.06)
P = .14
2.16 (0.54)
P = .00
1.58 (0.97)
P = .11
Organization fixed-effect
Yes
Yes
Yes
Yes
Year fixed-effect
Yes
Yes
Yes
Yes
SE clustered by
Org.
Org.
Org.
Org.
Observations
113
107
110
100
Adjusted R2
0.07
−0.02
0.08
0.11
Note: P < .05 indicated in bold font.


## Page 10

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
461
percent more likely where the organization receives a year-on-
year increase in its administration budget, and 31 percent more
likely with each additional unit of workforce-reported slack.
All three results are highly significant. Overhead slack retains
its negative and non-significant influence on acceptance.
The magnitude of the effect of slack on responsiveness can
also be gleaned from the MEM plots. According to Panel I
of figure 4, when holding all other variables constant at their
mean values, increasing budgetary slack from 0 to 1 on the
standardized scale (corresponding to increasing underspends
from 0.6% to 71.1%) raises the likelihood of accepting the
PAC’s request from 70% (95% CI [0.67, 0.73]) to 96% (95%
CI [0.81, 1.11]). Similarly, for the dummy budget variable, or-
ganizations with constant or declining administrative budgets
have a 68% (95% CI [0.65, 0.72]) likelihood of acceptance,
but that rises to 80% (95% CI [0.76, 0.84]) where there is
year-on-year budgetary growth (see Panel II). And, most no-
tably, when the standardized scale for worker-reported slack
rises from −1 to 1 (corresponding to 45.5 percent and 75 per-
cent of employees reporting acceptable workloads and work–
life balance), likelihood of acceptance from 40% (95% CI
[0.24, 0.56]) to 94% (95% CI [0.84, 1.04]) (see Panel IV).
Conversely, when the standardized overhead slack variable
is −0.8 (meaning 21% of employees are managers), the
likelihood of acceptance is 81% (95% CI [0.72, 0.91]),
decreasing to 45% when the standardized variable is −0.4
(and 57% of employees are managerial) (Panel III).
Slack and timeline precision
Moving to Hypothesis 2 and the effect of slack resources
on bureaucratic commitment, we adopt the dependent var-
iable of timeline precision as a continuous scale for which
we fit OLS models.12 The results, shown in Table 3, reveal
that both budgetary measures positively and significantly
correlate with increased timeline precision. However, neither
overhead slack nor workforce-reported slack, nor indeed a
conventional headcount measure of organizational capacity,
predict timeline precision. As a robustness check, we reconsti-
tute the precision measure as a six-point categorical variable,
for which we fit multinomial logit models. These results, re-
ported in Table 4, confirm our main findings. An organiza-
tion with higher budgetary slack is significantly more likely
Table 2. Slack and acceptance of PAC requests: request-level logistic regression.
Dependent variable
Acceptance dummy
(5)
(6)
(7)
(8)
Budgetary slack
1.47 (0.50)
P = .00
1.55 (0.52)
P = .00
Budgetary increase
0.52 (0.36)
P = .14
0.64 (0.34)
P = .06
Overhead slack
−7.11 (5.46)
P = .19
−5.71 (4.18)
P = .17
Worker-reported slack
1.55 (0.41)
P = .00
1.87 (0.32)
P = .00
Organization headcount
−3.26 (2.07)
P = .12
−2.95 (1.90)
P = .12
−2.34 (2.31)
P = .31
−2.67 (2.18)
P = .22
Collaboration requirement
0.12 (0.23)
P = .62
0.17 (0.22)
P = .43
0.11 (0.20)
P = .58
0.09 (0.21)
P = .68
Analysis, research and data
0.52 (0.26)
P = .04
0.61 (0.25)
P = .01
0.70 (0.24)
P = .00
0.55 (0.23)
P = .02
Clarify and disclose
0.44 (0.29)
P = .13
0.59 (0.27)
P = .03
0.65 (0.28)
P = .02
0.52 (0.25)
P = .04
Guidance and control
0.58 (0.21)
P = .01
0.69 (0.18)
P = .00
0.74 (0.18)
P = .00
0.64 (0.18)
P = .00
Internal management
0.69 (0.37)
P = .06
0.81 (0.36)
P = .02
0.89 (0.33)
P = .01
0.79 (0.34)
P = .02
Not actionable
−0.52 (0.47)
P = .27
−0.37 (0.42)
P = .38
−0.39 (0.43)
P = .35
−0.57 (0.44)
P = .19
Constant
−2.68 (2.04)
P = .19
−6.36 (3.62)
P = .08
−1.41 (1.64)
P = .39
−5.93 (2.90)
P = .04
Organization fixed-effect
Yes
Yes
Yes
Yes
Year fixed-effect
Yes
Yes
Yes
Yes
SE clustered by
Org.
Org.
Org.
Org.
Observations
1,375
1,333
1,318
1,313
AIC
1,465.27
1,469.19
1,457.91
1,418.48
12Timeline precision is a categorical variable. Instead of using ordered logit
model, it is now conventional in econometric literature to fit OLS models
to ordered categorical dependent variables (Algan and Cahuc 2009; Nunn
and Wantchekon 2011).
Note: P < .05 indicated in bold font.


## Page 11

462
Journal of Public Administration Research and Theory
to commit to a precise timeline for completing its assignment
compared to the baseline category of making no timeline com-
mitment to the PAC. Moreover, an organization with higher
budgetary slack, or with a year-on-year increase in adminis-
tration budget, is also more likely to have taken prompt ac-
tion to complete the assignment by the time the government’s
initial response to the committee was published (which results
in “left-censored” data in our survival analysis, below).
Slack and assignment completion
Having explored the effect of slack resources on the bureaucracy’s
acceptance of, and commitment to, the PAC’s requests, we con-
clude by exploiting the longitudinal elements of our data to track
the implementation of these assignments over time.
Since most implementation processes in our dataset
span multiple years, during which time each organization’s
slack varies somewhat, we employ the time-variant Cox
Proportional Hazards model (Therneau, Crowson, and
Atkinson 2024).13 The dependent variable is formed from
three elements: start and stop are the two time points defining
a follow-up interval for each request; and status is a dummy
variable where “1” indicates that completion occurred at
some point during that interval, and “0” indicates that imple-
mentation remains in progress. As discussed, the exact timing
of completion is assumed to be randomly distributed within
the range to account for the imprecision of the timestamp
(Gómez et al. 2009 ; Rodrigues et al. 2018; Zhang and Sun
2010). Our independent variables are in the same form as
used in testing H1 and H2, above, although slack values are
truncated at the 5 percent and 95 percent levels to remove the
impact of outliers. We again used lagged measures of budg-
etary and overhead slack. We also include all control variables
from previous regressions, including organization fixed effects
and year fixed effects. Furthermore, since each implemen-
tation process has multiple observations that are correlated
with one another, a cluster variance recommendation ID is
added to the model. For the 1,430 PAC requests included in
our dataset, we have 2,897 unique follow-up intervals. After
removing left-censored cases and intervals with missing slack
data, we are left with 1,772 analyzable follow-up episodes.
Table 5 presents the exponential coefficients (or hazards
ratio) of covariates, in which values less than 1.0 indicate a
negative relationship. Robust standard errors are reported in
brackets next to the hazards ratios. In Model (13) to (15),
we add budgetary, overhead and worker-reported slack sep-
arately, and include all in Model (16). As Table 5 indicates,
these results show that both budgetary slack and budgetary
increase have a positive and significant effect on the hazards
ratio for the event of assignment completion. According to
Model (16), at a given instant in time, the probability of as-
signment completion by an organization with one more unit
of budgetary slack is 54 percent greater. Similarly, an organ-
ization experiencing year-on-year growth in administrative
resources is 48 percent more likely to fulfill its commitment
to the PAC than one experiencing budget stasis or decline.
Both results are significant at the 99 percent level. Moreover,
according to Model (15), an organization with one more unit
of employees reporting an acceptable workload and work–
life balance is 30 percent more likely to turn the status of
Figure 4. Marginal effect of slack variables in predicting PAC request acceptance. Plot based on marginal effect at the mean (MEM). AME: average
marginal effect.
13Cox Proportional Hazards models assume that the relative hazard remains
constant over time across different covariate levels, and that the relationship
between the log hazard and each continuous covariate is linear (Hashim
and Weiderpass 2019; Kuitunen et al. 2021). We test these assumptions in
Appendix VI figure A and find no violations.


## Page 12

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
463
implementation from “in progress” to “completed,” but this
loses statistical significance in the full model. Overhead slack
regains its previous negative impact on responsiveness (see
Table 2), but is only significant at the 90 percent level. Finally,
while organization headcount has a positive and significant
impact on implementation in Model (13), it loses significance
in all the other models.
One possible caveat to this analysis is that, due to occa-
sional reporting delays, a small proportion of intervals ex-
ceed 12 months. This creates difficulties in matching updates
with slack variables, particularly given our use of a one-year
lag. As a robustness check, Model (17) in Table 5 removes all
such instances where the gap between start and stop exceeds
one year, and then fits the complete survival model to the re-
maining 1,554 episodes.14 Both budgetary measures continue
to have positive effect on assignment completion, though
only the budget dummy remains highly significant across all
models. Overhead slack gains significance in the extended
Cox model used as a robustness check in Model (18), showing
a consistent negative effect on assignment completion.
Discussion
To summarize, using our dataset of 1,430 legislative requests
to UK government bureaucracies between 2010 and 2015, we
found: that both budgetary and worker-reported slack sig-
nificantly increase the likelihood of bureaucrats agreeing to
take on new assignments (Table 2; figure 4); that budgetary
slack and budgetary increase also correlate with more precise
timelines for delivering these commitments (Tables 3 and 4);
and that these are also associated with more rapid comple-
tion of assignments (Table 5). Budgetary and worker-reported
slack also greatly outperform the conventional headcount
measure of capacity, which proved unstable in direction and
typically fell short of statistical significance. Altogether, then,
while these findings attest to the importance of organizational
capacity in predicting the political control of bureaucracies,
in line with several recent empirical studies from the US, they
also indicate that it is slack resources specifically, rather than
organizational capacity in general, that makes civil servants
more responsive to democratic overseers. This is consistent
with expectations from management science, where slack has
Table 3. Slack and planned implementation timeframe: request-level OLS regression.
Dependent variable
Timeline precision
(9)
(10)
(11)
(12)
Budgetary slack
0.82 (0.39)
P = .04
0.92 (0.44)
P = .04
Budgetary increase
0.44 (0.14)
P = .00
0.48 (0.16)
P = .00
Overhead slack
−0.01 (0.75)
P = .99
0.48 (0.71)
P = .50
Worker-reported slack
−0.18 (0.45)
P = .69
0.03 (0.38)
P = .94
Organization headcount
−0.48 (0.90)
P = .60
−0.13 (0.91)
P = .89
−0.22 (1.03)
P = .83
−0.51 (1.01)
P = .62
Collaboration requirement
−0.09 (0.14)
P = .52
−0.06 (0.14)
P = .67
−0.07 (0.14)
P = .61
−0.09 (0.14)
P = .54
Analysis, research and data
0.05 (0.25)
P = .85
0.16 (0.29)
P = .58
0.15 (0.30)
P = .60
0.09 (0.25)
P = .73
Clarify and disclose
0.06 (0.23)
P = .81
0.17 (0.27)
P = .52
0.16 (0.27)
P = .55
0.08 (0.24)
P = .73
Guidance and control
0.06 (0.28)
P = .82
0.15 (0.32)
P = .64
0.15 (0.32)
P = .63
0.08 (0.29)
P = .77
Internal management
0.01 (0.23)
P = .96
0.12 (0.26)
P = .64
0.11 (0.25)
P = .65
0.04 (0.23)
P = .86
Not actionable
−0.13 (0.27)
P = .62
−0.05 (0.30)
P = .86
−0.04 (0.31)
P = .91
−0.11 (0.29)
P = .70
Constant
0.10 (0.77)
P = .89
0.74 (0.74)
P = .31
0.67 (0.90)
P = .46
−0.15 (0.82)
P = .85
Organization fixed-effect
Yes
Yes
Yes
Yes
Year fixed-effect
Yes
Yes
Yes
Yes
SE clustered by
Org.
Org.
Org.
Org.
Observations
1,306
1,263
1,270
1,245
Adjusted R2
0.42
0.40
0.40
0.41
Note: P < .05 indicated in bold font.
14Drawing on Schoenfeld tests for Model (17) (figure B, Appendix VI), we
addressed the violation of the proportional hazards assumption for Worker-
reported slack by transforming it into a categorical variable using quartile
cutpoints at the 25th, 50th, and 75th percentiles. This was included as a
strata term in Model (18), replacing the continuous version to correct for
non-proportionality and assess the robustness of estimates in an extended
Cox model, which remained valid. As is standard, the stratified variable is
not reported in the Model (18) output (Kuitunen et al. 2021; Licht 2011).


## Page 13

464
Journal of Public Administration Research and Theory
long been regarded as enabling greater external attentiveness,
willingness to experiment, and capacity for change.
According to theory, unspent budget should provide the
greatest responsiveness, this being the most ready-to-go and
fungible form of slack. As Wiersma (2017, p. 447) observes,
cash is “a sine qua non for strategic action.” And yet, while
our two budgetary variables are indeed the most consistent
predictors across the hypothesis tests, the perceptual measure
of worker-reported slack has greatest explanatory power at
the outset of the PAC accountability regime. This might in-
dicate that workforce-reported slack is not only measuring
the balance of workload-to-resources, but is also a proxy for
staff morale or even turnover intent, to which senior managers
pay close attention when determining their capacity for extra
assignments. Conversely, because overhead slack has already
been “absorbed” into operations, this form of surplus must first
be recovered before it can be redeployed, potentially weakening
the effect on responsiveness. Indeed, our unstable and non-
significant results for overhead slack may indicate reluctance
or inability to divert senior civil servants away from their
ordinary but urgent activities, such as briefing ministers and
meeting deadlines from the finance ministry. And where, in our
early analyses, overhead slack appears to decrease the chance
of accepting PAC requests (Tables 1 and 2, but rarely achieving
significance), this may indicate that more “top heavy” organi-
zations suffer from greater inertia, fragmented power, and stra-
tegic discord, making it harder to agree new initiatives.
Limitations
Our study has several limitations.
Firstly, although we assemble a ten-year panel using high-
quality financial, personnel and survey data, each of our
four measures of slack has strengths and weaknesses in the
extent to which it accurately compares workload pressures
against resources. Developing and validating improved
measures of available, recoverable and potential slack that
are tailored to the public sector context is clearly a priority
for research, potentially using production function analysis
to arrive at a better comparison of sufficient and available
resources.
Secondly, our survival analysis considers only the speed
of implementing the PAC’s request, not the quality or extent
of changes made. Also, whilst we classify key attributes of
each PAC-issued recommendation, we are unable to compute
the magnitude of the change requested of the bureaucracy
and, thus, what resourcing it requires. And the completion
of assignments is self-reported by individual bureaucracies,
and although risk of future investigation by either the PAC or
NAO should discourage egregious misrepresentation, some
manipulation is possible but presently untested.
Thirdly, several sources of endogeneity may affect our
results. The PAC may have approximate knowledge of the
level of slack available in each bureaucracy, and may adjust
its requests so as not to overload already-struggling ministries
and agencies. However, this seems unlikely given the vast,
Table 4. Slack and planned implementation timeframe: request-level multinomial logit regression.
Timeline precision
Subject to condition
Vague timeline
Standard timeline
Detailed timeline
Already implemented
Budgetary slack
−24.42 (42.57)
P = .57
−2.08 (1.08)
P = .05
−1.16 (0.91)
P = .21
27.29 (12.57)
P = .03
3.77 (1.14)
P = .00
Budgetary increase
1.91 (9.76)
P = .84
0.48 (0.39)
P = .22
0.10 (0.32)
P = .74
0.34 (0.85)
P = .68
1.27 (0.30)
P = .00
Overhead slack
−6.54 (45.01)
P = .88
−0.09 (1.75)
P = .96
−1.41 (1.58)
P = .37
7.28 (9.81)
P = .46
1.24 (1.54)
P = .42
Worker-reported slack
15.83 (30.58)
P = .60
0.39 (1.02)
P = .71
1.21 (0.77)
P = .12
−1.83 (2.51)
P = .47
0.36 (0.74)
P = .63
Organization headcount
−4.62 (144.02)
P = .97
−6.38 (2.99)
P = .03
−0.31 (2.50)
P = .90
23.43 (12.25)
P = .06
−1.40 (2.46)
P = .57
Collaboration requirement
−0.19 (1.17)
P = .87
0.32 (0.39)
P = .41
−0.08 (0.36)
P = .82
0.50 (0.72)
P = .49
−0.20 (0.35)
P = .57
Analysis, research and data
9.10 (81.33)
P = .91
0.39 (0.57)
P = .49
0.71 (0.57)
P = .21
0.44 (1.30)
P = .73
0.16 (0.54)
P = .76
Clarify and disclose
9.04 (81.33)
P = .91
−0.16 (0.56)
P = .78
0.57 (0.57)
P = .32
1.47 (1.23)
P = .23
0.08 (0.53)
P = .89
Guidance and control
7.87 (81.33)
P = .92
0.10 (0.57)
P = .86
0.31 (0.58)
P = .59
0.43 (1.32)
P = .75
0.10 (0.54)
P = .85
Internal management
4.45 (81.55)
P = .96
−0.21 (0.62)
P = .73
0.33 (0.62)
P = .59
0.90 (1.34)
P = .50
−0.06 (0.57)
P = .92
Not actionable
−0.15 (0.003)
P = .00
−2.55 (148.99)
P = .99
−3.34 (68.00)
P = .96
−3.97 (0.48)
P = .00
−4.82 (97.91)
P = .96
Constant
−22.68 (123.84)
P = .85
−14.74 (112.71)
P = .90
−11.46 (2.13)
P = .00
−16.79 (59.82)
P = .78
−18.57 (2.10)
P = .00
Organization Fixed-effect
Yes
Yes
Yes
Yes
Yes
Year Fixed-effect
Yes
Yes
Yes
Yes
Yes
Observations
1,245
1,245
1,245
1,245
1,245
Akaike Inf. Crit.
2,749.47
2,749.47
2,749.47
2,749.47
2,749.47
Note: P < .05 indicated in bold font.


## Page 14

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
465
cross-governmental remit of this committee and the enor-
mous information required to make such slack-contingent
recommendations. Indeed, when we tested for factors
predicting the number of requests issued by the PAC to each
organization, only one of our four slack measures—the budg-
etary increase dummy—proved a significant predictor of
committee attention (see Appendix VII). And this may simply
reflect the PAC’s particular interest in the government’s policy
priorities (which received additional budget during a period
of general retrenchment), rather than any extensive “in-
sider knowledge” on slack capacity in particular agencies.
Alternatively, completed assignments may generate in-year
productivity gains, adding to spare resources. Like other em-
pirical studies of slack, we rely on lagged variables to control
for this possibility, though this is more suited to H1 and H2
than to the multi-year survival analysis used for H3.
Finally, while our dataset is highly distinctive in current
empirical literature, its dependence on the value-for-money
regime of the NAO and PAC may limit generalizability. These
bodies perform both control and accountability functions,
and may elicit blame-avoidance and reputation manage-
ment responses from government. In addition, the legislative
requests that we monitor are fairly “technocratic” in nature,
and it remains unclear whether slack resourcing will be as
significant a predictor of bureaucratic responsiveness to more
ideologically-driven policy change.
Conclusion
The arrival of agency theory into the political bureaucracy
literature in the 1970s advanced scholarship into political-
administrative relations markedly (Brierley et al. 2023; Miller
2005; Moe 2012). Wood (2010, p. 201) even credits agency
theory with having “moved the field some distance toward
the type of science practiced in other disciplines.” Yet, even
among its staunch proponents, the need to look beyond
agency theory has latterly been conceded. Indeed, Moe (1984,
2012) has twice called upon political scientists to expand into
more theoretically “eclectic” territory, cautioning that “the
delegation literature has focused all its attention on the in-
formation problem and brushed capacity aside” (2012, p. 31).
Innovative research, beginning with Huber and McCarty
(2004), has begun to address this imbalance (Bednar 2023;
Bednar and Lewis 2024; Bolton and Thrower 2022; Bolton,
Potter, and Thrower 2016; Boushey and McGrath 2017;
Dasgupta and Kapur 2020; Drolc and Keiser 2020; Gailmard
and Patty 2013; Hausman et al. 2023; McGrath 2013). And it
is to this emerging literature that we have sought to contribute,
Table 5. Slack and implementation of PAC requests: time-variant survival analysis with Cox proportional hazards model.
Dependent variable
Hazards ratio of implementation completion—exp(coef)
(13)
(14)
(15)
(16)
(17) Robustness
check
(18) Robustness
check
Budgetary slack
1.58 (0.16)
P = .00
1.54 (0.16)
P = .00
1.20 (0.16)
P = .07
1.11 (0.18)
P = .39
Budgetary increase
1.50 (0.09)
P = .00
1.48 (0.09)
P = .00
1.28 (0.10)
P = .00
1.35 (0.11)
P = .00
Overhead slack
0.31 (0.63)
P = .07
0.34 (0.60)
P = .06
0.54 (0.55)
P = .13
0.19 (0.68)
P = .01
Worker-reported slack
1.30 (0.14)
P = .03
1.20 (0.15)
P = .14
0.89 (0.17)
P = .42
Organization
headcount
2.89 (0.72)
P = .05
2.57 (0.75)
P = .10
1.93 (0.76)
P = .23
1.37 (0.84)
P = .63
0.78 (0.91)
P = .72
0.46 (1.02)
P = .34
Collaboration
requirement
0.90 (0.14)
P = .38
0.90 (0.14)
P = .38
0.90 (0.14)
P = .36
0.92 (0.14)
P = .46
0.84 (0.16)
P = .24
0.89 (0.16)
P = .38
Analysis, research and
data
1.08 (0.20)
P = .68
1.08 (0.20)
P = .70
1.10 (0.20)
P = .61
1.03 (0.20)
P = .87
0.91 (0.22)
P = .61
0.86 (0.22)
P = .47
Clarify and disclose
1.24 (0.19)
P = .24
1.24 (0.19)
P = .25
1.25 (0.19)
P = .23
1.21 (0.19)
P = .30
1.03 (0.21)
P = .89
0.95 (0.22)
P = .80
Guidance and control
1.24 (0.20)
P = .26
1.23 (0.20)
P = .27
1.27 (0.20)
P = .21
1.20 (0.20)
P = .33
1.05 (0.22)
P = .78
1.06 (0.22)
P = .77
Internal management
1.37 (0.21)
P = .09
1.36 (0.21)
P = .11
1.40 (0.21)
P = .08
1.34 (0.21)
P = .12
1.11 (0.24)
P = .62
1.11 (0.24)
P = .63
Not actionable
1.12 (0.33)
P = .72
1.11 (0.32)
P = .75
1.12 (0.32)
P = .73
1.10 (0.33)
P = .77
1.02 (0.36)
P = .96
1.06 (0.37)
P = .87
Organization fixed-
effect
Yes
Yes
Yes
Yes
Yes
Yes
Year fixed-effect
Yes
Yes
Yes
Yes
Yes
Yes
SE clustered by
Rec.
Rec.
Rec.
Rec.
Rec.
Rec.
Observations
1,770
1,770
1,770
1,770
1,554
1,554
R2
0.09
0.08
0.08
0.10
0.09
0.09
Note: P < .05 indicated in bold font.


## Page 15

466
Journal of Public Administration Research and Theory
not only by providing a rare quantitative analysis of bureau-
cratic responsiveness in a non-US, non-presidential context,
but also by reconnecting political science with management
theory. Specifically, we have sought a more authentic account
of how bureaucracies with enduring policy commitments can
be rendered more or less responsive to democratic overseers
based not on organizational capacity in general, but the pres-
ence or absence of slack resources in particular.
We find strong empirical support for this argument.
Budgetary and worker-reported slack significantly aid
bureaucracies in consenting to political requests for change,
committing to those assignments, and/or implementing them
in a timely fashion. Future work should look to replicate
these findings in other contexts and with similar or improved
measures of slack, which remains an elusive concept to oper-
ationalize. More work is also needed on potential interactions
between different subtypes of slack (Marlin and Geiger 2015).
And qualitative research should elucidate the mechanisms by
which surplus resources enable bureaucratic responsiveness,
and the reasons for different effect sizes across slack subtypes.
Many theoretical opportunities are presented, too. As noted
at the outset, the aim is to enhance rather than replace agency
explanations. Boehmke and Shipan’s (2015, p. 371) argument
that, “to fully understand political influence over agencies, we
need to examine the interaction between preferences and ca-
pacity” (original emphasis), applies to bureaucracies as much
as to the time-poor legislatures about which they were writing.
One priority is to better understand the origins of organiza-
tional slack in government bureaucracies. For example, as
Moulick and Taylor (2017) argue, recoverable slack is more
easily “hidden” from overseers than available slack, meaning
that it is more easily protected from top-down budget cuts.
And beyond the appropriations process, slack also depends on
the fixity of the bureaucracy’s current programs. If both prin-
cipal and agent are willing to sacrifice performance on past
commitments, then a surplus can be created with which to fund
new objectives. Indeed, this is consistent with Suzanne Mettler’s
(2016, p. 371) argument that, so vast has the “policyscape”
of accumulated commitments become, “policymakers have
failed to maintain the majority of existing laws....” On the
other hand, if principal and agent disagree about the value or
necessity of maintaining prior commitments, then a second-
order agency problem arises. Now, control is hindered not by
disputes over the new policy direction, but rather by disagree-
ment over how to free-up the resources needed to proceed.
This seems especially likely at moments of political transition
from one governing party to another, and in highly institution-
alized bureaucracies with low staff turnover.
Most of all, prosecuting this research agenda relies on new
interdisciplinarity between political science and general man-
agement; for the ambition is, as Moe (2012, p. 34) argues,
to re-engage with “the organizational aspects of bureaucracy
[that] have gotten organized out of the formal theory.”
Supplementary Material
All appendixes are available at the Journal of Public
Administration Research and Theory online.
Acknowledgments
This research was funded by Research England (award
0010374) and the John Fell Fund (award 0008399). We are
grateful for advice from parliamentary officials, the National
Audit Office, and Audit Scotland; and for excellent research
assistance by Rachel Darby, Ben Hart, Edgar Gutiérrez Aiza,
and Anna Bilous. Working papers were presented at the
Oxford-LSE Workshop on Performance Auditing, and the
UK Political Studies Association Annual Conference. We are
grateful for comments received.
Data Availability
(DOI: 10.5255/UKDA-SN-857975).
References
Abadie, A., S. Athey, G. W. Imbens, and J. M Wooldridge. 2022. “When
Should You Adjust Standard Errors for Clustering?” The Quarterly
Journal of Economics 138: 1–35.
Aberbach, J. 1990. Keeping a Watchful Eye: The Politics of Congres-
sional Oversight. Washington, DC: Brookings Institution.
Adam, C., S. Hurka, C. Knill, and Y. Steinebach. 2020. Policy Accumu-
lation and the Democratic Responsiveness Trap. Cambridge: Cam-
bridge University Press.
Algan, Y., and P Cahuc. 2009. “Civic Virtue and Labor Market
Institutions.” American Economic Journal: Macroeconomics 1:
111–45.
Appeldorn, N. H., and D Fortunato. 2022. “Legislative Capacity in
Germany’s Parliaments.” Legislative Studies Quarterly 47: 309–28.
Bardach, E. 1976. “Policy Termination as a Political Process.” Policy
Sciences 7: 123–31.
Barney, J. B., and D. N. Clark. 2007. Resource-Based Theory: Creating
and Sustaining Competitive Advantage. Oxford: Oxford University
Press.
Bawn, K. 1995. “Political Control Versus Expertise: Congressional
Choices about Administrative Procedures.” American Political Sci-
ence Review 89: 62–73.
Bednar, N. R. 2023. “Bureaucratic Autonomy and the Policymaking
Capacity of United States Agencies, 1998–2021.” Political Science
Research and Methods 12: 652–65.
Bednar, N. R., and D. E Lewis. 2024. “Presidential Investment in the Ad-
ministrative State.” American Political Science Review 118: 442–57.
Benn, A. 2023. Constraining Governance: Strategic Incentives to Un-
dermine Bureaucratic Capacity. Berkley: University of California.
Bentley, F. S., and R. R Kehoe. 2020. “Give Them Some Slack—They’re
Trying to Change! The Benefits of Excess Cash, Excess Employees,
and Increased Human Capital in the Strategic Change Context.”
Academy of Management Journal 63: 181–204.
Benton, M., and M Russell. 2013. “Assessing the Impact of Parliamen-
tary Oversight Committees: The Select Committees in the British
House of Commons.” Parliamentary Affairs 66: 772–97.
Bersch, K., S. Praça, and M. M Taylor. 2017. “State Capacity, Bureau-
cratic Politicization, and Corruption in the Brazilian State.” Gov-
ernance 30: 105–24.
Boehmke, F. J., and C. R Shipan. 2015. “Oversight Capabilities in the
States: Are Professionalized Legislatures Better at Getting What
They Want?” State Politics & Policy Quarterly 15: 366–86.
Bolton, A., R. A. Potter, and S Thrower. 2016. “Organizational Ca-
pacity, Regulatory Review, and the Limits of Political Control.” The
Journal of Law, Economics, and Organization 32: 242–71.
Bolton, A., and S. Thrower. 2022. Checks in the Balance: Legisla-
tive Capacity and the Dynamics of Executive Power. Princeton:
Princeton University Press.
Bourgeois, L. J. 1981. “On the Measurement of Organizational Slack.”
The Academy of Management Review 6: 29–39.
Bourgeois, L. J., and J. V Singh. 1983. “Organizational Slack and Polit-
ical Behavior Among Top Management Teams.” Academy of Man-
agement Proceedings 1983: 43–7.


## Page 16

Journal of Public Administration Research and Theory, 2025, Vol. 35, No. 4
467
Boushey, G. T., and R. J McGrath. 2017. “Experts, Amateurs, and Bu-
reaucratic Influence in the American States.” Journal of Public Ad-
ministration Research and Theory 27: 85–103.
Bowen, F. E. 2002. “Does Size Matter?: Organizational Slack and Vis-
ibility as Alternative Explanations for Environmental Responsive-
ness.” Business & Society 41: 118–24.
Bradley, S. W., D. A. Shepherd, and J Wiklund. 2011. “The Importance
of Slack for New Organizations Facing ‘Tough’ Environments.”
Journal of Management Studies 48: 1071–97.
Bradshaw, J., J. Hills, C. Hunt, and B. Khanna. 2007. Can Budgetary
Slack Still Prevail within New Zealand’s New Public Management?
Working Paper no. 53, Centre for Accounting, Governance and
Taxation Research, Wellington, New Zealand.
Brierley, S., K. Lowande, R. A. Potter, and G Toral. 2023. “Bureaucratic
Politics: Blind Spots and Opportunities in Political Science.” An-
nual Review of Political Science 26: 271–90.
Bucchianeri, P., C. Volden, and A. E Wiseman. 2024. “Legislative Effec-
tiveness in the American States.” American Political Science Review
119: 21–39.
Busch, T. 2002. “Slack in Public Administration: Conceptual and Meth-
odological Issues.” Managerial Auditing Journal 17: 153–9.
Carnes, C. M., K. Xu, D. G. Sirmon, and R Karadag. 2019. “How
Competitive Action Mediates the Resource Slack–Performance Re-
lationship: A Meta-Analytic Approach.” Journal of Management
Studies 56: 57–90.
Cheng, J. L. C., and I. F Kesner. 1997. “Organizational Slack and Re-
sponse to Environmental Shifts: The Impact of Resource Allocation
Patterns.” Journal of Management 23: 1–18.
Cooper, C. A., T. Elston, and A. Bilous. 2024. “Shifting the Deckchairs:
How Blame Avoiders Cope with the Loss of a Scapegoat.” In
The Politics and Governance of Blame, edited by M. Flinders, G.
Dimova, M. Hinterleitner, R. A. W. Rhodes, and R. K. Weaver. Ox-
ford: Oxford University Press.
Cyert, R. M., and J. G. March. 1963. A Behavioral Theory of the Firm.
Englewood Cliffs: Prentice-Hall.
Daniel, F., F. T. Lohrke, C. J. Fornaciari, and R. A Turner. 2004. “Slack
Resources and Firm Performance: A Meta-Analysis.” Journal of
Business Research 57: 565–74.
Dasgupta, A., and D Kapur. 2020. “The Political Economy of Bureau-
cratic Overload: Evidence from Rural Development Officials in
India.” American Political Science Review 114: 1316–34.
Davila, T., and M Wouters. 2005. “Managing Budget Emphasis through
the Explicit Design of Conditional Budgetary Slack.” Accounting
Organizations and Society 30: 587–608.
Dewar, D., and W. Funnell. 2016. A History of British National Audit.
Oxford: Oxford University Press.
Drolc, C. A., and L. R Keiser. 2020. “The Importance of Oversight and
Agency Capacity in Enhancing Performance in Public Service De-
livery.” Journal of Public Administration Research and Theory 31:
773–89.
Elston, T. 2024. Understanding and Improving Public Management
Reforms. Bristol: Policy Press.
Elston, T., and Y Zhang. 2023. “Implementing Public Accounts Com-
mittee Recommendations: Evidence from the UK Government’s
‘Progress Reports’ since 2012.” Parliamentary Affairs 76: 662–93.
Etzioni, A. 1960. “Two Approaches to Organizational Analysis: A
Critique and a Suggestion.”. Administrative Science Quarterly 5:
257–78.
Fan, Z., Q. Meng, and N Wei. 2020. “Fiscal Slack or Environmental
Pressures: Which Matters More for Technological Innovation As-
similation?” International Public Management Journal 23: 380–404.
Fernández-i-Marín, X., M. Hinterleitner, C. Knill, and Y Steinebach.
2024. “Bureaucratic Overburdening in Advanced Democracies.”
Public Administration Review 84: 696–709.
Gailmard, S., and J. W. Patty. 2013. Learning while Governing: Exper-
tise and Accountability in the Executive Branch. Chicago: Univer-
sity of Chicago Press.
Gómez, G., M. L. Calle, R. Oller, and K. Langohr. 2009. “Tutorial on
methods for interval-censored data and their implementation in R.”
Statistical Modelling 9: 259–97.
Hashim, D., and E. Weiderpass. 2019. “Cancer Survival and Survivor-
ship.” In Encyclopedia of Cancer, 3rd ed., edited by P. Boffetta and
P. Hainaut, 250–9. Oxford: Academic Press.
Hausman, D. K., D. E. Ho, M. S. Krass, and A McDonough. 2023. “Ex-
ecutive Control of Agency Adjudication: Capacity, Selection, and
Precedential Rulemaking.” The Journal of Law, Economics, and
Organization 39: 682–721.
HM Treasury. 2011. Public Expenditure Statistical Analyses 2011. (Cm
8104). London: Stationery Office.
Huber, J. D., and N McCarty. 2004. “Bureaucratic Capacity, Delega-
tion, and Political Reform.” American Political Science Review 98:
481–94.
Huber, J. D., C. R. Shipan, and M Pfahler. 2001. “Legislatures and Stat-
utory Control of Bureaucracy.” American Journal of Political Sci-
ence 45: 330–45.
Imai, K., and I. S Kim. 2021. “On the Use of Two-Way Fixed Effects
Regression Models for Causal Inference with Panel Data.” Political
Analysis 29: 405–15.
Jensen, M. C. 1993. “The Modern Industrial Revolution, Exit, and the
Failure of Internal Control Systems.” Journal of Finance 48: 831–80.
Knill, C., C. Steinbacher, and Y Steinebach. 2021. “Balancing Trade-
Offs between Policy Responsiveness and Effectiveness: The Impact
of Vertical Policy-Process Integration on Policy Accumulation.”
Public Administration Review 81: 157–60.
Krause, G. A. 2010. “Legislative Delegation of Authority to Bureau-
cratic Agencies.” In Oxford Handbook of American Bureaucracy,
edited by R. F. Durant. Oxford: Oxford University Press.
Krause, G. A., and N. D. Woods. 2014. “State Bureaucracy: Policy Del-
egation, Comparative Institutional Capacity, and Administrative
Politics in the American States.” In Oxford Handbook of State and
Local Government, edited by D. P. Haider-Markel. Oxford: Oxford
University Press.
Kuitunen, I., V. T. Ponkilainen, M. M. Uimonen, A. Eskelinen, and A
Reito. 2021. “Testing the Proportional Hazards Assumption in Cox
Regression and Dealing with Possible Non-Proportionality in Total
Joint Arthroplasty Research: Methodological Perspectives and Re-
view.” BMC Musculoskeletal Disorders 22: 489.
Lee, S.-Y., and A. B Whitford. 2012. “Assessing the Effects of Organi-
zational Resources on Public Agency Performance: Evidence from
the US Federal Government.” Journal of Public Administration Re-
search & Theory 23: 687–712.
Leuridan, G., and B Demil. 2022. “Exploring the Dynamics of Slack in
Extreme Contexts: A Practice-Based View.” Human Relations 75:
1167–93.
Licht, A. A. 2011. “Change Comes with Time: Substantive Interpreta-
tion of Nonproportional Hazards in Event History Analysis.” Po-
litical Analysis 19: 227–43.
Lillvis, D. F., and R. J McGrath. 2017. “Directing Discipline: State Med-
ical Board Responsiveness to State Legislatures.” Journal of Health
Politics, Policy and Law 42: 123–65.
Marlin, D., and S. W Geiger. 2015. “A Reexamination of the Organi-
zational Slack and Innovation Relationship.” Journal of Business
Research 68: 2683–90.
McCrea, A. M. 2022. “The Role of Organizational Slack and Human
Capital in Managing Performance Shocks: How US Nursing Homes
Buffered Hurricane Katrina.” Journal of Policy Studies 37: 1–14.
McGrath, R. J. 2013. “Congressional Oversight Hearings and Policy
Control.” Legislative Studies Quarterly 38: 349–76.
McHugh, J. P., and D. A Cross. 2021. “The Application of Organizational
Slack to Hospital System Responsiveness During the COVID-19 Pan-
demic.” Journal of Hospital Management and Health Policy 5: 17–17.
Melton, E. K., and K. J Meier. 2017. “For the Want of a Nail: The Inter-
action of Managerial Capacity and Human Resource ­Management
on Organizational Performance.” Public Administration Review
77: 118–30.
Mettler, S. 2016. “The Policyscape and the Challenges of Contempo-
rary Politics to Policy Maintenance.” Perspectives on Politics 14:
369–90.
Miller, G. J. 2005. “The Political Evolution of Principal-Agent Models.”
Annual Review of Political Science 8: 203–25.


## Page 17

468
Journal of Public Administration Research and Theory
Mintzberg, H. 1983. Power In and Around Organizations. Englewood
Cliffs: Prentice-Hall.
Moch, M. K., L. R Pondy, James G. March, Johan P. Olsen, S.
Christensen, M. Cohen, and H. Enderud, et al. 1977. “The Struc-
ture of Chaos: Organized Anarchy as a Response to Ambiguity.”
Administrative Science Quarterly 22: 351–62.
Moe, T. M. 1984. “The New Economics of Organization.” American
Journal of Political Science 28: 739–77.
Moe, T. M. 2012. “Delegation, Control, and the Study of Public Bu-
reaucracy.” The Forum 10 : 1–45.
Moulick, A. G., and L. L Taylor. 2017. “Fiscal Slack, Budget Shocks,
and Performance in Public Organizations: Evidence from Public
Schools.” Public Management Review 19: 990–1005.
Mount, M. P., G. Ertug, K. Kavusan, G. George, and T Zou. 2024.
“Reeling in the Slack: An Integrative Review to Reinstate Slack
as a Central Theoretical Construct for Management Research.”
Academy of Management Annals 18: 473–505.
Nohria, N., and R Gulati. 1997. “What is the Optimum Amount of
Organizational Slack?: A Study of the Relationship Between Slack
and Innovation in Multinational Firms.” European Management
Journal 1995: 32–6.
Nunn, N., and L Wantchekon. 2011. “The Slave Trade and the Origins
of Mistrust in Africa.” American Economic Review 101: 3221–52.
O’Toole, L. J., and K. J Meier. 2010. “In Defense of Bureaucracy.”
Public Management Review 12: 341–61.
Rodrigues, A. S., V. F. Calsavara, F. I. B. Silva, F. A. Alves, and A. P.
M Vivas. 2018. “Use of Interval-Censored Survival Data as an Al-
ternative to Kaplan-Meier Survival Curves: Studies of Oral Lesion
Occurrence in Liver Transplants and Cancer Recurrence.” Applied
Cancer Research 38: 16.
Ruggiero, J., W. Duncombe, and J Miner. 1995. “On the Measurement
and Causes of Technical Inefficiency in Local Public Services.”
Journal of Public Administration Research and Theory 5: 403–28.
Sharfman, M. P., G. Wolf, R. B. Chase, and D. A Tansik. 1988.
“Antecedents of Organizational Slack.” Academy of Management
Review 13: 601–14.
Singh, J. V. 1986. “Performance, Slack, and Risk Taking in Organiza-
tional Decision Making.” Academy of Management Journal 29:
562–85.
Therneau, T., C. Crowson, and E Atkinson. 2024. “Using Time De-
pendent Covariates and Time Dependent Coefficients in the Cox
Model.” Survival Vignettes 2: 1–25.
Ting, M. M. 2011. “Organizational Capacity.” Journal of Law, Eco-
nomics, and Organization 27: 245–71.
Turkson, A. J., F. Ayiah-Mensah, and V Nimoh. 2021. “Handling
Censoring and Censored Data in Survival Analysis: A Standalone
Systematic Literature Review.” International Journal of Mathe-
matics and Mathematical Sciences 2021: 1–16.
Vanacker, T., V. Collewaert, and S. A Zahra. 2017. “Slack Resources, Firm
Performance, and the Institutional Context: Evidence from Privately
held European Firms.” Strategic Management Journal 38: 1305–26.
Wiersma, E. 2017. “How and When Do Firms Translate Slack into
Better Performance?” British Accounting Review 49: 445–59.
Williams, M. J. 2021. “Beyond State Capacity: Bureaucratic Perfor-
mance, Policy Implementation and Reform.” Journal of Institu-
tional Economics 17: 339–57.
Wood, B. D. 2010. “Agency Theory and the Bureaucracy.” In Oxford
Handbook of American Bureaucracy, edited by R. F. Durant, 181–
206. Oxford: Oxford University Press.
Woods, N. D., and M Baranowski. 2006. “Legislative Professionalism
and Influence on State Agencies: The Effects of Resources and Ca-
reerism.” Legislative Studies Quarterly 31: 585–609.
Xiao, C., Q. Wang, D. P. van Donk, and T van der Vaart. 2018. “When
are Stakeholder Pressures Effective? An Extension of Slack Re-
sources Theory.” International Journal of Production Economics
199: 138–49.
Yılmaz, E., G. Özer, and M Günlük. 2014. “Do Organizational Poli-
tics and Organizational Commitment Affect Budgetary Slack Cre-
ation in Public Organizations?” Procedia - Social and Behavioral
Sciences 150: 241–50.
Zhang, Z., and J Sun. 2010. “Interval Censoring.” Statistical Methods
in Medical Research 19: 53–70.

