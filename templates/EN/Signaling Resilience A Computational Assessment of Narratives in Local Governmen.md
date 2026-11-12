# Signaling Resilience A Computational Assessment of Narratives in Local Governmen

## Page 1

Journal of Public Administration Research and Theory, 2023, 33, 688–700
https://doi.org/10.1093/jopart/muad001
Advance access publication 14 February 2023
Article
Signaling Resilience: A Computational Assessment of
Narratives in Local Government Budgets
Robert A. Greer
Bush School of Government & Public Service, Texas A&M University, USA
Tima T. Moldogaziev
Pennsylvania State University, USA
Ryan P. Scott
Political Science, Colorado State University, USA
Tyler A. Scott
Department of Environmental Science and Policy, University of California, USA
Address correspondence to the author at rgreer1@tamu.edu
Abstract
Local governments consider a wide range of policies to increase resilience in the face of myriad risks and employ a variety of tactics to communi-
cate about these policies to external actors. An important platform to signal resilience as a policy priority is through the budget process wherein
local communities decide “who gets what, when, and how.” Using computational text mining techniques, we assess how county governments
in California signal efforts toward resilience in their budgets during the 2012–2017 fiscal years, as well as whether and how those signals are
received by the capital market. Comparable budget documents are available for 38 counties across the state for a total of 161 county-year
observations. To test the relationship between local government resilience signals and capital market outcomes, we focus on county underlying
credit ratings issued by counties. Empirical results show that county underlying credit ratings are insensitive to resilience signals in local gov-
ernment budgets. By examining the efficacy of resilience signals and their effects on the capital market, we offer evidence on the link between
policy signaling and financial outcomes at the local government level.
Introduction
Local governments are expected to maintain efficient, con-
sistent public service delivery, while also mitigating external
risks. The United States’ exposure and vulnerability to a
range of factors such as severe heat, changes in precipitation
patterns, and rising sea levels, as well as non-climate-related
threats, are expected to increase. To deal with these risks,
there have been calls for local governments to become more
resilient so that they are able to withstand an extreme event
without suffering “devastating losses, damage, diminished
productivity, or quality of life…” (Mileti 1999, 32). Recent
research shows that local governments undertake a myriad
of policies to build up anticipatory and coping capacities
to prepare for external risks that they perceive are likely
(Barbera 2016, 2017; 2021; Hines et al. 2020; Saliterer et
al. 2021).
Seeking resilience is a complex task that has major prac-
tical components and implications. Local governments must
understand the relevant risks, develop strategies to address
and mitigate those risks, identify funding sources to imple-
ment those strategies, and then effectively communicate resil-
ience to external actors. Communication is important because
many resilience projects require significant capital investment
to build or maintain infrastructure. In the United States, and
several other countries, such as Canada or Mexico, local
governments finance that infrastructure by issuing debt di-
rectly or through conduits, which involves a number of fi-
nancial intermediaries. Traditionally, credit rating firms are
used to provide an independent evaluation of creditworthi-
ness along several core risk fundamentals. The ratings are an
important metric because they influence local governments’
access to external resources and the financing costs that
taxpayers incur. Therefore, the local government’s ability to
signal policies and plans that seek to minimize exposure or
mitigate shocks is likely critical for a more favorable credit
rating. Signaling refers to a variety of strategies that can be
used by borrowers to overcome information asymmetries and
communicate credit quality to lenders (Martell et al. 2021;
Milde and Riley 1988).
In this article, we explore how local governments’ stated
narratives with regard to their approaches to building re-
silience intersect with creditworthiness. While rating firms
openly communicate their increased attention to risk adap-
tation in credit quality, the extent to which this is actually
© The Author(s) 2023. Published by Oxford University Press on behalf of the Public Management Research Association. All rights reserved. For
permissions, please e-mail: journals.permissions@oup.com.


## Page 2

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
689
happening is unclear (Mathiesen 2018). Using the case of
counties in the state of California, we consider their attention
to resilience in the budget process and the language they use to
signal resilience to external actors. We use automated content
analysis tools to quantify and compare resilience priorities
discussed by county managers in proposed budget narratives.
Proposed budget narratives signal policy priorities to internal
and external parties, including financial intermediaries and
investors (Anastasopoulos et al. 2020; Ivonchyk 2020; Rich
et al. 2021). We then regress county credit ratings on these
stated approaches or themes to resilience, controlling for
socio-demographic characteristics, to explore the connection
between resilience signals and evaluations of local govern-
ment creditworthiness.
Background
Signaling Local Resilience
The concept of resilience has been the subject of increased
interest for both academics and policymakers, especially
in the context of climate change and risk management
(Meerow and Newell 2015). Local government resilience
has received particular attention given inconsistencies in
central government attention to climate change and the
increasing role of local governments in service delivery and
infrastructure provision (Godschalk 2003; Meerow et al.
2015). However, while the term resilience has become a
fundamental component for thinking about risk and safety
threats ranging from climate change and natural disasters
to economic crises (Doorn et al. 2019), it also exhibits a
“conceptual fuzziness” (Meerow and Newell 2015). In
other words, while the term resilience is widely invoked,
its meaning differs across disciplines and diverges even fur-
ther when moving from academic definitions to practitioner
language.
For example, in traditional engineering literature, resilience
is often a measure of the robustness and buffering capacity of
a system to changing conditions or to the recovery of infra-
structure to pre-disaster conditions (Agudelo-Vera et al. 2012;
Doorn et al. 2019; Liao 2012). Holling (1996) referred to this
use of the term as static resilience. This aligns with terms such
as coping capacity or bounce-back capacity in public manage-
ment research (e.g., Barbera et al. 2017). Conversely, the idea
of dynamic resilience focuses on maintaining key functions
when faced with a shock (Holling 1996). This perspective
aligns more closely with social-ecological dimensions of resil-
ience more focused on governance, politics, and social justice
(Adger et al. 2009). In recent public management scholarship,
terms such as anticipatory, adaptive, or bounce-forward ca-
pacity have been used to capture the dynamic features of re-
silience (e.g., Barbera et al. 2017; Meerow et al. 2016).
Pluralistic usage of the term resilience can be beneficial, as
it is applied to multiple problems across a variety of scientific
disciplines (Merrow and Newell 2015)—but also makes resil-
ience difficult to operationalize, or to develop generalizable
indicators or metrics across disciplines (Gunderson 2000;
Pizzo 2015; Vale 2014). Indeed, indicators that have been
used in previous studies typically focus on a particular aspect
of resilience such as natural resource spending to measure
flood mitigation efforts (Miao et al. 2021). Due to the wide
range of approaches to defining resilience across fields and
areas of practice, we acknowledge resilience as a pluralistic
concept that can be defined by different actors in different
ways.
Accordingly, for the purposes of our study, it is most
appropriate to assess how local governments express
resilience-oriented ideas and communicate those to external
stakeholders. We identify broad categories of resilience that
can be mapped onto the more “static resilience” strategies
and the more “dynamic resilience” strategies, respectively. For
example, themes relating to bouncing back from a disaster,
such as crisis management or security, would be consistent
with the former. Themes relating to maintaining systems
during a disaster, such as those around preparedness or risk
management, might be more closely aligned with the latter
view for resilience.
Despite the common usage of the term resilience among
state and local governments, there is not much known about
how local government officials communicate resilience to ex-
ternal actors. Building on work in political communication,
Boussalis et al. (2019) use computer-assisted content analysis
of city government press releases to describe the extent to
which climate policies appear in official communication and
examine the influence of key covariates on the likelihood of
discussing resilience in policy areas such as emissions, energy,
land use, and climate resiliency. Relatedly, using text anal-
ysis of the annual gubernatorial state of the state addresses,
Ivonchyk (2020) establishes a connection between key policies
discussed by governors and subsequent spending levels, such
as for transportation infrastructure. Most proximate to our
research, Rich et al. (2021) found evidence that management
discussion and analysis (M&A) section narratives of annual
financial reports are significant for alleviating credit risk
disagreements that may exist between competing credit rating
firms.1 Alternatively, there have been studies on how market
signals can encourage climate change adaptation through the
use of land and water markets (Anderson et al. 2019) that
shows the effects of various policies and market conditions on
distorting those signals. Risk communication is discussed in
a number of academic disciplines, however, there is relatively
little focus on resilience communication and even less on the
signaling of local resilience to external stakeholders, such as
credit rating agencies and capital market investors.
Local governments have a range of policies they can pursue
in an effort to become resilient (e.g., Barbera et al. 2017;
Hines et al. 2020; Meerow and Newell 2019; Saliterer et al.
2021). The effectiveness of such efforts matters both in prac-
tice and perception. Local governments that experience major
disasters exhibit diminished public works expenditure even
6–10 years after the event, owing in part to increased bor-
rowing costs attributable to downgraded credit ratings (Jerch
et al. 2020). This exemplifies how signaling resilience to cap-
ital market participants such as credit rating agencies, finan-
cial intermediaries, and investors could matter for government
financing outcomes. Existing capital market research shows
that signals or signaling by borrowers are critical for access to
external resources and the costs of financing (Krishnaswami
et al. 1999; Kwan and Carleton 2010; Leland and Pyle 1977;
Martell et al. 2021; Rich et al. 2021).
1At the same time, in the risk analysis literature, Peters et al. (2006) ex-
amine key components of environmental risk communication that lead to
perceptions of trust and credibility such as perceptions of knowledge and
expertise; perceptions of openness and honesty; and perceptions of concern
and care.


## Page 3

690
Journal of Public Administration Research and Theory
A central premise of this article is thus capital investors
have a financial interest in a local government’s ability to
both “weather the storm” and bounce back from external
shocks. Investors have a good reason for concern: Boustan
et al. (2020) estimate that in the United States from 1920
to 2010, severe disasters experienced at the county level
increased out-migration by 1.5% and lowered housing
prices by 2.5%–5% (which helps to explain, given that
property taxes are the backbone of local revenues, why
rating agencies might downgrade local governments). Local
governments often need to access capital markets to borrow
funds to pursue projects to make their communities more
resilient. Examples include capital-intensive investments
such as retrofitting government-owned buildings or mass
transit (Boussalis et al. 2019; Johnson 1995; Mashayekh
et al. 2012). Historically, local governments in the United
States have relied on issuing tax-exempt bonds for these
types of costly infrastructure projects. The need to signal
credit quality to investors to access capital at desirable rates
suggests that local governments have a need to communi-
cate the approaches they take to be resilient to external
actors.
Infrastructure Financing
Infrastructure-related projects have emerged as a central piece
of adaptation and mitigation strategies, especially related to
climate-related risks (Zimmerman et al. 2019). While more
attention has been paid to infrastructure needs in resilience
planning, less has been spent on how resilience relates to
credit risk. Local governments generally finance infrastructure
through the issuance of a bond. In this process, the local gov-
ernment may issue a tax-exempt bond if the project qualifies
as a public-purpose investment and fails the private activity
bond test (IRS 2019). Tax-exempt bonds have an advantage
over a taxable bond because the interest paid to bondholders
is not included in their gross income for federal income tax
purposes, which means bondholders are willing to accept a
lower interest rate than they would accept if the interest was
taxable (IRS 2019; Johnson et al. 2014; Nanda and Singh
2004). Issuing tax-exempt bonds saves local governments
money and is a common method for financing public in-
frastructure in the United States (Hildreth and Zorn 2005;
Johnson et al. 2014).
Since investors are often unfamiliar with the financial
risk associated with these local governments, they value an
independent third-party assessment of creditworthiness or
default risk, also known as a credit rating. There are three
major credit rating agencies in the United States that provide
an opinion on credit quality for state and local governments:
Standard & Poor’s (S&P), Moody’s, and Fitch. These credit
ratings are paid for by the local government, and therefore
the local government has the option to purchase any number
of ratings from any of the agencies. Some choose to go un-
rated while others choose to purchase a rating from each
agency (Greer 2016; Johnson and Kriz 1999). Disclosure
of all credit ratings is typically required in the official bond
statement documents. The precise methodology for credit
ratings is proprietary and varies somewhat across the three
agencies, but general guidelines are provided by each firm.
For example, Moody’s published its rating methodology for
local governments bonds that are backed by the entity’s ad
valorem taxing power (these are called General Obligation
or GO bonds) and classified four broad rating factors: ec-
onomic strength, financial strength, management and gov-
ernance, and debt profile. Moody’s uses a weighted average
approach to analyzing these factors to determine a rating
range (Moody’s 2009).
All three agencies have specific written policies as to the
effect of management and governance on credit ratings. In
the Management and Governance category of Moody’s rating
methodology, they specifically point to financial planning,
capital planning, management of the tax base, and disclosure
as contributing factors. S&P is even more explicit in its evalu-
ation and dedicates 20% to management factors, 30% to eco-
nomic factors, and 10% to institutional factors (the remaining
40% is in liquidity, budgetary performance, budgetary flexi-
bility, debt, and liabilities). In the 20% for management, S&P
evaluates risk exposure and risk management as important
factors (S&P 2013). It is in these management and govern-
ance categories that rating agencies are most likely to con-
sider the specific effects of risk factors like climate change and
breaches in security.
In a 2017 report, S&P clarified that their U.S. public fi-
nance division “typically consider[s] ESG factors in the con-
text of management effectiveness and planning,” and they
further stated specifically for municipalities and states that
include a “focus on their management and the effectiveness
of their long-term planning” (Kernan et al. 2017). Finally, the
third-largest credit rating firm, Fitch, specifically said they
assess “the impact of physical climate risks when it assigns
credit ratings to issuers and transactions across all asset
classes” (McNeil and Tang 2020). More recently, the termi-
nology of environmental, social, and governance (ESG) risks
has gained popularity in both corporate and public finance
arenas (Brooks and Oikonomou 2018).
How Climate Change Relates to Credit Risk
Climate change threatens local government creditworthiness
on several fronts. For instance, population displacement and
property damage from disasters can result in further rev-
enue decline for local governments as in the case of the City
of New Orleans’ after Hurricane Katrina (Hildreth 2009).
Since Hurricane Harvey inundated the Houston, Texas
region in 2017, the potential for property devaluations and
foreclosures hindering the ability of special utility districts
to fulfill their bond obligations has caused concern (Assanie
and Weiss 2018). Furthermore, local utilities and other service
providers often rely on service fees and revenues to back
financed capital investments. In the case of the 2018 Camp
Fire in California that burned the town of Paradise, as many
residents were unable to return (NPR 2019), the drinking
water system remained unusable months later (“Water
Quality Advisory—After the Camp Fire—Paradise Irrigation
District” 2019), and, thus, questions were raised whether
much of the town would be rebuilt at all (Kasler and Lillis
2018). This jeopardized the ability of the local water utility
to fund debt payments, which had a direct implication for its
creditworthiness (Webster 2018).
While concerns about local government debt in reaction
to disasters are obvious, bond buyers and credit rating firms
are just as concerned about future risks that might result in
major losses for investors (Chen 2020; Fowles et al. 2009;
Hines et al. 2020). Moody’s (2017) announced that it would
factor climate risk and local government adaptation efforts


## Page 4

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
691
into credit ratings. However, it remains somewhat unclear in
practice how and whether firms are incorporating such risks
in their credit ratings (Mathiesen 2018; “What you need to
know about what’s in—and absent from—Moody’s climate
risk report” 2019). The breadth of credit risks highlighted in
the Moody’s (2017) report—economic disruption, physical
damage, population shifts, and health/public safety—highlight
the comprehensiveness of the challenge local governments
face. Local adaptation needs vary by region, making it diffi-
cult to focus on specific policies or infrastructure investments
as a way to compare local governments.
While the Moody’s report highlights needed investments in
built infrastructure (e.g., for flood control), looking at capital
investment alone is not sufficient for understanding local gov-
ernment resilience. First, “green” infrastructure, regulatory
changes in zoning and building codes, and coordinated gov-
ernance have complementary and interactive effects on capital
infrastructure (Lubell 2019; Rosenzweig et al. 2011; Sutton-
Grier et al. 2015). Second, operators and regulators address
climate contingencies to varying degrees in siting, design, and
operations of infrastructure (Ulibarri and Scott 2019), so cap-
ital investment alone is not indicative of increased resilience.
To the extent that governments are investing in risky infra-
structure, these debt obligations carry the potential of being
underwater (pun intended) and increasing credit risk. In turn,
this risk affects the ability of local governments to finance
service provisions and improvements through access to tax-
exempt capital financing.
Rationale
Signaling and Credit ratings
With recent changes in credit rating firms’ attention to external
risks, we expect that local government resilience—and thus fi-
nancial risk—is likely to be associated with local government
creditworthiness. Local governments possess information
about their level of external risk exposures and internal risk
management strategies that credit rating agencies may not.
Signaling theory provides a lens for framing this information
asymmetry, whereby a given party must choose whether and
how to communicate information to the other, external party
(Connelly et al. 2011; Ederington et al. 1984; Martell et al.
2021; Peng and Brucato 2004; Rich et al. 2021). Signaling
theory is fundamentally concerned with reducing informa-
tion asymmetries (Connelly et al. 2011; Spence 2002). In a
classic labor market setting, Spence (1978) demonstrated how
a job applicant might engage in behaviors to reduce informa-
tion asymmetry that shapes the selection outcomes. However,
management scholars have also widely applied signaling
theory to explain the influence of information asymmetries in
a wide range of settings (Connelly et al. 2011).
For signaling to take place, the signaler should benefit by
some action from the receiver that the receiver would not
otherwise have done, and therefore, the signal has a stra-
tegic effect (Connelly et al. 2011). Previous studies in cor-
porate settings have tested signaling theory using corporate
shareholders (Certo et al. 2001) and debt holders (Elliott et al.
2009; Krishnaswami et al. 1999; Kwan and Carleton 2010)
as receivers. For example, in a study of young, publicly held
technology firms Janney and Folta (2003) find that issuing pri-
vate equity signals to the marketplace that managers believe
their growth opportunities are undervalued. Market signaling
and the advantages of reduced information asymmetries have
also been shown to be an impact factor in the municipal bond
market (Blackwell and Kidwell 1988; Moldogaziev et al.
2019). The key features are that these external actors stand
to gain from making decisions based on information from
signals. Credit rating agencies would benefit since their busi-
ness model depends on absorbing all material information,
especially with regard to relatively more fuzzy policies aimed
at fostering local resilience. As Rich et al. (2021) show such
signaling of local government financial health is already hap-
pening through M&A section narratives of audited financial
reports, whereby signals are used toward alleviating credit
quality disagreements.
Given the complex set of risk factors local governments
face—and ratings firms’ stated commitment to assessing
local resilience—it is prudent for local government managers
to communicate their commitment and plans for resilience.
Local governments are not subject to the same market com-
petition games that corporations are concerned with, how-
ever (Boyne 1996; Greer 2015; Greer and Denison 2014;
Greer et al. 2018b; Johnson and Kriz 2005). One means local
governments have to signal resilience to external actors is
through budget documents, in which public managers jus-
tify planned expenditures and outline spending (i.e., policy)
priorities. In the state of California, for instance, county
executives or administrative officers prepare a proposed
budget document that averages about 500 pages in length each
year. Credit rating agencies have stated in their methodologies
that they consider these documents as a way to measure
factors like management quality and political will. Therefore,
these documents represent an opportunity for local officials
to signal to credit rating agencies, and investors, that they rec-
ognize and are planning for external risks.
Budget justification documents contain two primary
forms of prose: (1) macro-narratives, which provide an over-
arching summary of the proposed county budget; and (2)
micro-narratives for individual government departments
(county administration office, environmental health depart-
ment, public works, etc.) or functional areas (public safety,
general government, etc.). We explore combined macro- and
micro-narratives in proposed budgets. These budget memo
narratives describe how the organization or department will
prioritize expenditures to deal with current issues in the up-
coming fiscal year. Budget narratives serve several general
functions for a local government: a financial plan, a policy
statement, a communication device, and an operations guide
(Anastasopoulos et al. 2020; Mikesell 2012; Schick 1966).
One advantage of relying on budget narratives, which ac-
company both proposed and adopted budgets, is they could
decrease the potential for cheap talk (Bingler et al. 2021).
Because narratives communicate the plan and policy designs
for the fiscal year, signals in a budget narrative have a corre-
sponding real cost (Farrell and Rabin 1996; Mikesell 2012).
In the case of county credit ratings, we are specifically fo-
cusing on whether budget narratives act as signals of local
government resilience to external actors.
Resilience in Public Management
Organizations require a modicum of predictability, stability,
and efficiency (March 1991; Selznick 2011), and efficiency
and procedural regularity are also important values in their
own right held for public organizations (Hood 1991; Rainey


## Page 5

692
Journal of Public Administration Research and Theory
2009). Thus, a core assumption of this analysis is that all
local governments want to be resilient—generally defined as
“the ability of a system to maintain its structure and patterns
of behavior in the face of disturbance” (Holling 1986, 203).
However, as described above, resilience is a pluralistic con-
cept that fits somewhat inconsistently with the operating
environments of public organizations (Duit 2016). Resilience,
in its pluralistic definition, is a public good that exists beyond
jurisdictions (Ostrom and Ostrom 2019). Local governments
can however package resilience efforts (Ostrom et al.
1961). Owing to local political and economic factors, local
governments are expected to differ in how they operation-
alize the concept of resilience in planning for the future and
pursuing certain priorities. This is corroborated by empirical
findings from research on local governments (e.g., Barbera et
al. 2017, 2021; Hines et al. 2020).
In what follows, we discuss several interrelated themes
that emerge in the organizational studies literature regarding
approaches to building resilience: crisis management, risk
management, security, and preparedness. Admittedly, these
themes can further be aggregated by their dynamic and
static features, as we discuss in the sections below. We use
these categories to classify local governments’ strategies to-
ward resilience—each strategy is a signal to outsiders about
commitments and priorities. The external signal recipient in
this context is the credit rating firm. If the signal is received
and interpreted by the credit rating agency as the local gov-
ernment intends, then the message will be absorbed into a
credit rating. The reflection of budgetary narratives in a credit
rating is a certification by rating firms to investors that the
approaches toward resilience are material to credit risk, and
therefore, a given local government is a creditworthy invest-
ment, all else equal.
First, organizational resilience has perhaps most commonly
been addressed within the context of crisis management. For
instance, there is a large swath of literature addressing how
governments can respond to disasters (e.g., Boin and van Eeten
2013; Comfort 2005, 2007). For example, Birkland (2006)
argues that the type of disaster affects the types of lessons
learned from it, and that certain conditions are necessary to
translate awareness into new policy which includes resilience
measures. These works focus on how organizations can de-
sign and implement response structures that can weather a
crisis and take immediate and effective steps toward recovery.
Crisis management focuses on how organizations can be resil-
ient by properly responding to a disruptive event.
Organizations have also been linked to resilience through
security. Security refers to efforts to buffer or buttress an or-
ganization against external threats by ensuring that such an
unwanted event does not happen—or is easily rectifiable if an
event occurs. For instance, flood-prone coastal cities seek se-
curity through physical and financial flood protection efforts
such as seawalls and flood insurance (Aerts et al. 2014).
These types of protective steps might contrast with a risk
management-oriented flood policy that tries to disincentivize
building in the floodplain zones. Key security questions relate
to how an organization should balance protective measures
without becoming overly rigid or incurring unwanted side
effects.
To make this point, Wildavsky (1988) uses the analogy
of the “jogger’s dilemma,” where a runner incurs some
increased health risk (e.g., a sprained ankle) in order to
decrease overall long-term health risk, to demonstrate the
basic paradox that organizations face in striving for se-
curity. This tension figures prominently in the discussion of
“high-reliability organizations” tasked with functions where
error is not tolerable (LaPorte and Consolini 1991), such as
homeland security or hazardous waste management. Such
organizations must possess strict, standardized procedures,
and yet, at the same time, have sufficient flexibility to ad-
dress unexpected contingencies (Frederickson and LaPorte
2002). It is worth noting that security considerations are
not limited just to classic security applications such as phys-
ical or information security. Security is also a focus of local
governments in the context of social needs such as food se-
curity (Barthel and Isendahl 2013) or public health (Chandra
et al. 2010).
In contrast to crisis management and security, risk man-
agement refers to an organizational focus on identifying po-
tential risks and taking steps to reduce the likelihood of or
impact of identified threats. Classically, organizational risk
management efforts focused primarily on threat identification
and vulnerability reduction (van der Vegt et al. 2015). Within
the context of organizational resilience, risk management
has come to focus less on predicting particular events and
reducing the probability of particular outcomes and more on
ensuring that an organization has sufficient capacity and flex-
ibility to deal with unexpected outcomes (Sutcliffe and Vogus
2003; van der Vegt et al. 2015). Either way, the idea remains
to manage an organization—and for a local government, by
extension, a local community—in such a way that unexpected
events are less disruptive and those particularly bad outcomes
are averted.
A final theme underlying how organizations pursue resil-
ience is through preparedness. Preparedness involves actions
such as the development of an emergency evacuation plan,
conducting emergency drills, and stockpiling or ensuring the
availability of post-event assets (Kapucu 2008). Comfort et
al. (2010) describe preparedness as taking steps to ensure that
emergency response assets are available when needed. As an
organization cannot possibly plan for everything, a key con-
sideration for organizational resilience involves figuring out
which types of events to prepare for (Pearson and Mitroff
1993). It is important to acknowledge that all of these four
resilience concepts are inextricably linked, such that this
is admittedly a forced series of distinctions or ideal forms.
The intent then is not to portray these components as being
standalone approaches but rather that these elements help to
frame the overall discussion of how organizations think about
and pursue resilience. For instance, preparedness efforts such
as developing a disaster response plan address crisis man-
agement actions that are spelled out in the plan. Thus, these
themes are not mutually exclusive.
Materials and Methods
Proposed Budget Narratives, 2012–2017
Counties in California produce a yearly proposed budget,
which may generally include a justification for expenditures
and outline policy priorities for the forthcoming fiscal year.
At the time of document collection, county budgets were
available for 5 fiscal years, from 2012–2013 to 2016–2017.
Each year, county executives or administrative officers pre-
pared a proposed budget document that averaged about 500
pages in length. As already discussed, we focus on proposed


## Page 6

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
693
budget documents because budget narratives signal policy
priorities to internal and external parties, including financial
intermediaries and investors (Anastasopoulos et al. 2020;
Ivonchyk 2020; Rich et al. 2021).2
Narratives, sometimes both macro- and micro-narratives,
are not available for all counties, however. Partially, this is
because several largest counties have a separate strategic
performance budget, where separate narratives may be
contained. Several of the smallest counties, on the other ex-
treme, have simple documents with barely any text in them.
Finally, several counties moved from having a single budget
document to separate operating budget vs. capital improve-
ment budget documents, or from having no narratives in
the earlier periods to adding annotated discussions in the
latter periods. After preparing California county budget
documents for text analysis, we retain and can use an un-
balanced panel of 39 counties.3 The recommended budget
narratives data are then coupled with political, economic,
and fiscal variables over 2012–2017 in order to assess
whether or how resilience signals relate to credit ratings for
California counties.
Reading Resilience Signals from Local Government
Budgets
To model each government’s expressed orientation to-
ward resilience, we use a pre-trained vector space model for
words. Also known as a word embedding model, this method
represents individual words in a multidimensional concept
space based on observed proximity and co-occurrence in the
text corpus on which the model is trained. The basic intuition
is that words that co-occur more frequently, or occur in sim-
ilar contexts, are assumed to have more shared meaning or
relate to more similar concepts, and vice versa. Every word is
assigned a location value on each dimension, and the vector
of dimension values for each word represents its location rel-
ative to other words.
We used the pre-trained ConceptNet 5.5 vector space
model (Speer et al. 2017), which represents 417,194 words
along 300 dimensions. Multiple words can be added or
subtracted to produce an aggregate location of the words
in question. Subtracting one word or phrase vector from
another vector produces the difference between the two
vectors, and adding two words or phrases combines
the two vectors (e.g., a classic example is that in a well-
fit word embeddings model, “king” – “man” + “woman”
should identify the word “queen” as the nearest word). We
used this approach in two stages to develop a vector space
representation of each of the four resilience orientations
described previously.
For the first stage, shown in table 1, we created a word
equation meant to represent and distinguish each resilience
orientation. For each equation, we started with the root words
or phrases (crisis management, security, preparedness, and
risk management), and then added several words assumed to
reflect each concept (see the discussion in §3.2). We then add
the words “resilient” (to reflect the desired overall context)
and “budget” (since the documents we analyzed are proposed
county budgets). When using the same vector space model,
these equations produce the same vectors each time, so each
equation is directly reproducible.
In the second stage, we applied each vector shown in table
1 to the broader word vector model to identify the rele-
vant words and phrases in the model that are most closely
related to each initial vector. Specifically, we identified the
25-word embeddings most closely located to each concept,
as measured by cosine similarity (essentially, a multidimen-
sional measure of distance). For each resilience orientation,
we then computed the combined vector of these 25 words,
and then subtracted the combined vector for each of the other
three resilience orientations to differentiate each vector from
the others. The resulting measures are presented in figure 1,
where words are grouped by theme and plotted by cosine
similarity to the equations in table 1.4 Each set of words in
figure 1 demonstrates a relatively high level of cosine simi-
larity, around 0.75, to the associated initial concept vector
(table 1), and likewise low similarity, around 0, to the other
initial concept vectors.
Finally, to code documents based on resilience emphases,
we measure the cosine similarity of each resilience emphasis
vector with respect to a vectorized representation of each
document. In other words, for each budget narrative, we de-
velop an additive vector of its constituent words (similar to
the process shown in table 1) and then measure the distance
between this vector and each of the concept vectors. Words
that do not convey meaning, such as “the,” “and,” or “but,”
are removed before vectorization. Words that occur multiple
times are included each time, and thus weighted more heavily.5
3The omitted counties are smaller jurisdictions with no textual narratives
in the proposed budgets. This, however, should not influence the findings
in the study as these smaller counties also do not have underlying credit
ratings and no rated bonds were issued by them during the period under
review. Should they want to gain access to the capital market, the need
to communicate material financial information to the capital market still
­remains. Thus, in the sample we evaluate, the signal that is being sent to
external actors is only by the counties that seek to maintain access to exter-
nal, capital market financial resources. Budget narratives data are adopted
from: Anastasopoulos, Lefteris; Moldogaziev, Tima T.; Scott, Tyler, 2019,
“Replication Data for: “Organizational Context and Budget Orientations:
A Computational Text Analysis”, https://doi.org/10.7910/DVN/JWTBUG,
Harvard Dataverse, V2.
Table 1 Initial Word Vector Models Used to Develop a Concept Vector for
Each Resilience Orientation
Security
~“security” + “harden” + “prevent” + [“resilient”
+ “budget”]
Crisis manage-
ment
~“crisis” + “management” + “respond” + “con-
tain” + “recover” + [“resilient” + “budget”]
Preparedness
~“prepare” + “plan” + “forethought” + [“resilient”
+ “budget”]
Risk management ~“risk_management” + “identification” + “assess”
+ “approaches” + “plan” + [“resilient” + “budget”]
4For a robustness check on the Cosine similarity between organizational
resilience concept vectors and Wikipedia page for each concept see figure
A1 in the appendix.
2Note, however, that unlike the federal, state, and sometimes large city
budget processes, there is not much of a checks-and-balances system in place
at the county level. Rather there is a certain level of fusion of responsibilities,
where the proposed budgets from the Chief Executive Officer or the
Chief Administrative Officer in the county are already inclusive of policy
preferences of county commissioners. For instance, we find that it is not un-
usual to see that the text in macro-and micro-narratives in proposed county
budgets is identical to text in adopted county budgets.
5As a bag-of-words approach, it is important to note that this method does
not maintain semantic meaning so much as it reassigns meanings to indi-
vidual words based on the ConceptNet database, averaging across words
in a document to produce a paragraph-to-concept similarity (Hopkins and
King 2010).


## Page 7

694
Journal of Public Administration Research and Theory
Underlying County Credit Ratings
To evaluate the impact that these modeled resilience emphases
have on credit ratings, we use a general model of credit ratings
based on the methodologies of local government credit quality
published by the credit rating agencies and the extant aca-
demic literature on the determinants of credit ratings. There
is a robust literature on state and local credit ratings, which
are typically studied through the lens of financial intermedi-
ation, in which the principal role of credit rating agencies is
the reduction of uncertainty or informational asymmetry re-
garding default probability (Millon and Thakor 1985; Pottier
and Sommer 1999; Ramakrishnan and Thakor 1984). By
resolving information problems, borrowers are able to gain
access to capital markets and enjoy lower financing costs
(Ederington et al. 1984; Greer et al. 2018a; Johnson and Kriz
2005; Martell et al. 2021; Peng and Brucato 2004; Rich et al.
2021). A variety of management factors as well as fiscal insti-
tutional factors have been shown to affect local government
creditworthiness and borrowing costs (Denison et al. 2007;
Grizzle 2010; Greer 2016; Greer and Denison 2016; Guzman
and Moldogaziev 2012; Johnson et al. 2012; Johnson and
Kriz 1999; Maher et al. 2016; Simonsen and Robbins 1996).
Credit ratings can be assigned to the issuing local gov-
ernment by one or more of the major public finance rating
agencies and serve as a forward-looking opinion about
long-term creditworthiness and financial strength through
multiple business cycles (Greer 2016; Moldogaziev and
Guzman 2015). These ratings represent a source of informa-
tion about the financial, economic, and administrative envi-
ronment of the entity being rated, which is important in the
municipal bond market where investors have not always
had access to relevant data and there has historically been
Figure 1 Each Panel Presents 25 Words that are Closest to Each Theme in Cosine Similarity. Each Point Represents the Cosine Similarity between a
Word and the Theme Corresponding to the Color.


## Page 8

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
695
a lack of transparency (Copeland and Ingram 1982; Reck
and Wilson 2006). The distribution of underlying county
credit ratings in the sample for this study is fairly similar to
those found in previous studies and are clustered at the AA
and AA+ credit rating notches. There are very few ratings
below “A.”6
Results
In this subsection, we present several general models of local
government credit quality, with the four measures extracted
from budget documents as key concepts of interest. In ad-
dition to these measures of local government resilience sig-
nals, the general models also include institutional factors
and market factors such as median home values7, unemploy-
ment, population, and long-term general liabilities. These
are fairly standard covariates in state and local government
credit rating models and have been discussed elsewhere (e.g.,
Johnson et al. 2021; Johnson and Kriz 2005; Marlowe 2011;
Maher et al. 2016; Moldogaziev and Guzman 2015; Palumbo
and Zaporowski 2012). Descriptive statistics for all variables
are presented in table 2.
The dependent variable is the underlying county credit
rating. Following what is now a conventional approach (e.g.,
Johnson and Kriz 2005; Maher et al. 2016; Marlowe 2011;
Moldogaziev and Guzman 2015; Palumbo and Zaporowski
2012), we treat ratings as ordinal data. Due to the spar-
sity of many specific rating values, we group ratings into
six categories. All ratings at or below A/A2 are coded as
the lowest value (1), and AAA/Aaa ratings are coded as the
highest value (6). The analysis was conducted on all California
counties that had a credit rating from the major credit rating
agencies, S&P, Moody’s Investor Services (Moody’s), and
Fitch. Ordered logit credit rating models are estimated sep-
arately, to mitigate the potential impact of multicollinearity
between them, for the four measures of signals of resilience
and presented in table 3. Following the convention for hierar-
chical regression models (Gelman and Hill 2006), continuous
variables are standardized (mean-centered and divided by the
standard deviation).
The regression results in table 3 show that none of the sig-
nals of local government resilience have a statistically signif-
icant association with underlying county credit ratings. In
other words, we fail to observe a relationship between re-
silience language and credit ratings for local government. In
contrast, the results for control variables are large as expected
(e.g., a higher median home value is associated with having
a better credit rating). There may be several explanations for
this null result. One possibility is that despite recent rhetoric,
rating agencies do not place significant weight on resilience
when determining creditworthiness. This explanation could
be because they do not view it as a significant risk factor or
because that is not what investors are demanding. An alterna-
tive explanation is that due to the well-documented confusion
on what resilience means, the signals that local governments
send to credit rating agencies are just too noisy to be useful.
One might then expect noisy signals to have less of an im-
pact when rating agencies are evaluating local government
creditworthiness. To assess these alternative implications it is
worth testing a different conceptualization of resilience lan-
guage. We address this, and other practical implications, in
the next section.
Discussion and Alternatives
The goal of this study was to explore whether and how local
governments’ stated narratives with regard to their approaches
to resilience relate to credit risk. To do this we considered
resilience communication in the context of signal theory.
One of the general challenges when studying local resilience
is that the term “resilience” does not have a single agreed-
upon definition (Meerow et al. 2016), and policymakers do
not always utilize the same approaches to resilience (Barbera
et al. 2017, 2021). Due in part to the variety of disciplines
that have contributed to the resilience literature, there are a
variety of concepts from psychology, engineering, and envi-
ronmental science that have been wrapped into the term resil-
ience (Meerow et al. 2016; Meerow and Newell 2019).
However, one useful and common approach to
characterizing resilience is to adopt a distinction between
static resilience, referring to a system’s ability to bounce
back after a system shock, and dynamic resilience, which
6County credit ratings from Fitch, Moody’s, and Standard & Poor’s are
coded from lowest to highest, where A and below = 1 and AAA/Aaa =
6. When there is a disagreement in credit ratings between the firms (split
ratings), the highest rating is selected for coding—very few counties have
ratings from all three firms or even two firms, however, and split ratings
are observed in only a small proportion of observations in the sample. An
inclusion of a split rating dummy measure in the regressions does not alter
key conclusions.
7Other institutional control variables including political ideology, median
income, and other measures of county fiscal condition were also considered,
but are highly correlated with the controls that are used below. Robustness
checks with these alternative controls were estimated, but have no signifi-
cant differences.
Table 2 Descriptive Statistics
n
Min
Median
Mean
Max
County rating
161
Baa1|BBB+
Aa2|AA
Aaa|AAA
Crisis management
161
0.13
0.25
0.25
0.32
Security
161
0.01
0.09
0.09
0.16
preparedness
161
0.13
0.21
0.21
0.3
Risk management
161
0.24
0.33
0.32
0.37
Ln(Population)
161
9.56
12.98
13.05
16.13
Unemployment rate
161
3.1
7.8
8.66
27.7
Ln(Median home value)
161
11.89
12.69
12.68
13.66
Ln(Long-term general liabilities)
161
4.34
5.93
5.92
7.58


## Page 9

696
Journal of Public Administration Research and Theory
focuses on maintaining key functions when faced with the
shock (Meerow et al. 2016; Meerow and Newell 2019). In
public management literature, this is akin to the concepts
of coping and anticipatory capacities of local governments
(e.g., Barbera et al. 2017, 2021; Saliterer et al. 2021). The
latter is discussed here as the “focus on anticipation and
awareness of risks, […] that is, the extent to which an or-
ganization has a clear understanding of the environment
and is able to manage key vulnerabilities,” while the former
concept relates to the “capacity to cope with unanticipated
shocks once they manifest themselves” (Barbera et al. 2017,
672).
To draw from this conceptualization of static and dynamic
resilience, we reconstruct the approaches or themes of re-
silience in county budget narratives along these two facets.
Here, the language used in the Crisis Management construct
is primarily concerned with recovering or “bouncing back”
from a shock and the language used in the Security is prima-
rily concerned with engineering terms that rely on preventing
a disturbance but not necessarily maintaining functionality.
Therefore, it is reasonable to reclassify these signals as “static
facets of resilience.” Conversely, the risk management con-
struct is focused on assessment and evaluation language,
while the preparedness construct includes planning and fore-
sight language. These ideas fit within the “dynamic facets
of resilience” classification. One possibility is that while
investors will value bouncing back from a disaster, they are
primarily concerned with issues of repayment and default.
This suggests that, a priori, they would value dynamic resil-
ience capacity that would result in fewer disruptions to bond
repayments.
Reconfiguring the models presented in table 4 to a static
versus dynamic facet of resilience, we still find no statistically
significant results that would suggest that rating agencies
Table 3 Ordered Logistic Models for the Covariates of Underlying County Credit Ratings
M1: Crisis Management
M2: Security
M3: Preparedness
M4: Risk Management
Linear Predictors (estimate + p-value)
Scale(resilience signal)
-0.635 (0.263)
-0.103 (0.857)
-0.071 (0.885)
0.179 (0.753)
Scale(ln(median home value))
10.618 (0.000)
10.359 (0.000)
10.288 (0.000)
10.322 (0.000)
Scale(ln(population))
5.124 (0.006)
4.858 (0.015)
4.691 (0.014)
4.796 (0.014)
Scale(ln(total liabilities per-capita))
-0.089 (0.876)
-0.138 (0.806)
-0.137 (0.808)
-0.121 (0.830)
Scale(Unemp. rate)
0.609 (0.780)
0.608 (0.777)
0.672 (0.754)
0.642 (0.765)
Additional Model Terms
Cut points
yes
yes
yes
yes
Year fixed effect
yes
yes
yes
yes
County random effect
yes
yes
yes
yes
Goodness-of-fit
AIC
241.415
242.676
242.598
242.665
BIC
287.637
288.897
288.819
288.886
Log-likelihood
-105.708
-106.338
-106.299
-106.333
Observations
N (county-year)
161
161
161
161
# groups (counties)
38
38
38
38
Note: p-values in parentheses, * p < 0.05, ** p < 0.01, *** p < 0.001. Due to high collinearity between the measures of signals of resilience, models
including each measure are estimated separately. List-wise regressions using alternative fiscal measures (output omitted for brevity) do not change
conclusions for the signals of resilience. Additionally, list-wise regressions using alternative debt burden measures (output omitted for brevity) do not change
conclusions for the signals of resilience. Cut points and other fit statistics for panel ordered logistic models were omitted for brevity.
Table 4 Ordered Logistic Models for the Covariates of County Credit
Ratings, Collapsed Resilience Signal Measures
Static
Dynamic
Linear Predictors (estimate + p-value)
Scale(resilience
signal)
-0.563 (0.000)
0.051 (0.926)
Scale(ln(median
home value))
10.609 (0.000)
10.323 (0.000)
Scale(ln(population))
5.259 (0.000)
4.775 (0.013)
Scale(ln(total liabili-
ties per-capita))
-0.106 (0.000)
-0.138 (0.806)
Scale(Unemp. rate)
0.538 (0.000)
0.626 (0.771)
Additional Model Terms
Cut points
yes
yes
Year fixed effect
yes
yes
County random
effect
yes
yes
Goodness-of-fit
AIC
241.948
242.688
BIC
288.169
288.909
Log-likelihood
-105.974
-106.344
Observations
N (county-year)
161
161
# groups (counties)
38
38
Note: p-values in parentheses, * p < 0.05, ** p < 0.01, *** p < 0.001. Due
to high collinearity between the measures of signals of resilience, models
including each measure are estimated separately. List-wise regressions
using alternative fiscal measures (output omitted for brevity) do not change
conclusions for the signals of resilience. Additionally, list-wise regressions
using alternative debt burden measures (output omitted for brevity) do not
change conclusions for the signals of resilience. Cut points and other fit
statistics for panel-ordered logistic models were omitted for brevity.


## Page 10

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
697
are picking up on resilience language in county budget
documents. One expectation was that dynamic resilience
should have a positive and significant impact on credit ratings
because as such capacity would minimize disruptions to bond
repayments, but this analysis suggests that neither concept is
valued in the credit rating process. We leave the possibility
open that investor demands may be shifting and that these
measures will become more important as severe whether
events result in higher risk profiles for local governments,
but additional studies are needed to identify this complex
relationship.
To explore the context of these findings we turn to the re-
cent literature on environmental finance and specifically the
sustainable investment movement and interest in ESG-labeled
assets. Investor demand for sustainable investing options has
grown quickly and ESG ratings have become more popular
in recent years (Hartzmark and Sussman 2019). In corporate
finance, these trends have driven more investors to rely on
third-party assessments of corporate ESG performance (Berg
et al. 2019). To capture any market premiums that exist for
sustainable investments, some issuers (both corporate and
municipal) have issued a variety of “green” or “sustainable”
labeled bonds. However, the price advantage of these labeled
bonds has been mixed at best. While there are some premiums
found for corporate issuers in the secondary municipal bond
market, there are no conclusive results that this premium
is present and consistently found in the primary municipal
bond market (Partridge and Medda 2020; Larcker and Watts
2020). Our findings, which suggest that resilience is not being
captured in credit ratings, would be consistent with these
findings that issuers are not seeing strong investor interest in
ESG bonds although the link between these streams of litera-
ture warrants further attention.
Recent public management studies that relied on docu-
ment text analysis and their relationship with important
organizational outcomes confirm that narratives and sig-
nals have a meaningful role to play (Anastasopoulos and
Whitford 2018; Hollibaugh 2018; Ivonchyk 2020; Rich et
al. 2021). However, because we rely on concept similarity
for signals of resilience, it is important here to recognize
that language can serve as both an intentional and uninten-
tional signal. Given the lack of agreement on a consistent
definition of resilience, the expectation that local govern-
ment managers who are tasked with multiple priorities are
using the proper language to signal their resilience might be
cause for concern, especially given the patterns we find in
the results. Conversely, it is also possible that a signal is not
received the same way by different internal and external or-
ganizational stakeholders.
Conclusion
Local governments are often at the forefront of the impacts
of, as well as managing exposures to, external risks. With lim-
ited resources, they must develop strategies to mitigate these
risks and recent attention has been paid to local governments
becoming more resilient, despite often conflicting ideas about
what that might mean in practical terms. Capital market ac-
tors represent one stakeholder group that has a vested interest
in local government resilience. This study contributes to the
literature on local government resilience and financial man-
agement by focusing on the types of resilience signals they
may communicate to external actors through the budget
process and whether those signals are then absorbed in credit
ratings. Findings indicate that narratives in county budget
documents of local approaches to become resilient do not
have an impact on county credit ratings.
The concept of resilience is complex because it encompasses
a variety of strategies and priorities that are potentially at
odds with one another. When examining policy priorities
for any organization, but specifically local governments, one
key source of information are the documents produced in
the budget process. The budgets are a policy document that
signals to external stakeholders what the priorities are for
the next year, what challenges the leadership foresees, and
their strategies for dealing with those issues (Anastasopoulos
et al. 2020; Ivonchyk 2020; Schick 1966). We use budget
documents as the basis of our text analysis to determine what
language local governments are using to communicate resil-
ience across four approaches: crisis management, security,
risk management, and preparedness. While there is overlap
across these themes, they represent the different ways local
governments may approach resilience signaling.
The findings presented here offer several avenues for fur-
ther research. First, the Wordvector text analysis approach to
classify language used in communicating resilience in budget
documents is a unique approach that can be applied in other
settings. We believe that budget documents are a useful text
corpus that can be explored further, but this approach can
also be used on other public texts such as strategic planning
documents, capital improvement plans, records of hearings,
and others. Specifically, we expect that text in capital im-
provement plans would be an interesting extension of our re-
search to get directly at infrastructure resilience. Second, there
is a great deal of variation in the sizes and responsibilities that
counties have across the United States. Research on signaling
behaviors across multiple states in light of these different
responsibilities is an important extension of current work. At
the same time, the level of transparency is likely to vary with
regard to the production and availability of budget documents
from one state to another. We do believe, however, that our
approach and findings are generalizable to other states and
their counties, as well as larger metropolitan cities.
Third, more consideration of how local governments send
signals of resilience, or any other policy signals, to external
actors is needed. Thus, as Boussalis et al. (2019) discuss, there
may be political advantages to signaling resilience, but as we
demonstrate here, there may be both financial advantages and
disadvantages to doing so as well. More research is needed,
however, to fully understand the relationship between ac-
tual local government resilience levels and policies and credit
ratings. Though a deeper understanding of how markets re-
ceive and process signals of resilience is important, we do
not know in any comprehensive way how actual, objective
resilience levels interact with the local government capital
financing and management function. Given the increased
policy salience and investor interest in sustainable investing
and ESG risks, the task of signaling resilience to the market
will be an important one going forward.
Data Availability
All data and code necessary to replicate this article are availa-
ble at https://github.com/tylerandrewscott/hiwassee


## Page 11

698
Journal of Public Administration Research and Theory
Appendix
Figure A1. Cosine similarity between signals of resilience con-
cept vectors and Wikipedia page for each concept.
To assess the extent to which each modeled concept captures
a unique facet of a signal of resilience we want to measure,
we can apply the model to texts for which the topic is known
a priori and see whether these known topical emphases are
picked up by the model. For our purposes, the Wikipedia
subpages for each of the four signals of resilience provide a
useful foil. In figure A1, we present the results of fitting each
of these concept models to the Wikipedia pages for each of
the original four measures for resilience signals. Importantly,
each measure is most similar to its respective Wikipedia page.
In other words, when we measure the cosine similarity be-
tween the concept vector and the text of the Wikipedia pages
for each of the four signals of resilience, in all four cases the
page with the highest cosine similarity to each concept vector
is the page pertaining to that same concept. This demonstrates
the construct validity of resilience measures.
References
Adger, W. N., S. Dessai, M. Goulden, M. Hulme, I. Lorenzoni, D. R.
Nelson, L. Otto Naess, J. Wolf, and A. Wreford. 2009. “Are there
social limits to adaptation to climate change?”. Climatic Change
93 (3–4): 335–54.
Aerts, J. C., W. J. Wouter Botzen, K. Emanuel, N. Lin, H. de Moel, and
E. O. Michel-Kerjan. 2014. “Evaluating flood resilience strategies
for coastal megacities.” Science 344 (6183): 473–75.
Agudelo-Vera, C. M., W. R. Leduc, A. R. Mels, and H. H. Rijnaarts.
2012. Harvesting urban resources towards more resilient cities. Re-
sources, Conservation and Recycling, 64: 3–12.
Anastasopoulos, L. J., T. T. Moldogaziev, and T. A. Scott. 2020. “Or-
ganizational context and budget orientations: A computational
text analysis.” International Public Management Journal 23 (2):
292–313.
Anastasopoulos, L. J., and A. B. Whitford. 2018. “Machine learning for
public administration research, with application to organizational
reputation.” Journal of Public Administration Research and Theory
29 (3): 491–510. https://doi.org/10.1093/jopart/muy060.
Anderson, S., T. Anderson, A. Hill, M. Kahn, H. Kunreuther, G. Libecap,
H. Mantripragada, P. Mérel, A. Plantinga, and V. Kerry Smith.
2019. “The critical role of markets in climate change adaptation”.
Climate Change Economics 10 (1): 1950003.
Assanie, L., and M. Weiss. 2018. “Harvey Highlights Houston MUD
Bond Development Funding—Southwest Economy, Second Quar-
ter 2018—Dallas Fed.” Federal Reserve Bank of Dallas. https://
www.dallasfed.org/~/media/documents/research/swe/2018/
swe1802b.pdf.
Barbera, C., E. Guarini, and I. Steccolini. 2016. “Italian municipalities
and the fiscal crisis: Four strategies for muddling through.” Finan-
cial Accountability & Management 32 (3): 335–61.
Barbera, C., M. Jones, S. Korac, I. Saliterer, and I. Steccolini. 2017.
“Governmental financial resilience under Austerity in Austria,
England and Italy: How do local governments cope with financial
shocks?” Public Administration 95 (3): 670–97.
———. 2021. “Local government strategies in the face of shocks and
crises: The role of anticipatory capacities and financial vulnerabil-
ity.” International Review of Administrative Sciences 87 (1): 154–70.
Barthel, S., and C. Isendahl. 2013. “Urban gardens, agriculture, and
water management: Sources of resilience for long-term food secur-
ity in cities.” Ecological Economics 86 (Supplement C): 224–34.
Bingler, J. A., M. Kraus, and M. Leippold. 2021. “Cheap talk and cher-
ry-picking: What ClimateBert has to say on corporate climate risk
disclosures.” Finance Research Letters 47: 102776.
Birkland, T. A. 2006. “Lessons of Disaster: Policy Change After Cata-
strophic Events.” Washington, DC: Georgetown University Press.
Blackwell, D. W., and D. S. Kidwell. 1988. “An investigation of cost
differences between public sales and private placements of debt.”
Journal of Financial Economics 22 (2): 253–78.
Boin, A., and M. J. G. van Eeten. 2013. “The resilient organization.”
Public Management Review 15 (3): 429–45.
Boussalis, C., T. Coan, and M. Holman. 2019. “Communicating cli-
mate mitigation and adaptation efforts in American cities.” Climate
7 (3): 45.
Boustan, L. P., M. E. Kahn, and P. W. Rhode. 2020. “The effect of nat-
ural disasters on economic activity in US counties: A century of
data.” Journal of Urban Economics 118: 103257.
Boyne, G. A. 1996. “Competition and local government: A public
choice perspective.” Urban Studies 33 (4–5): 703–21.
Brooks, C., and I. Oikonomou. 2018. “The effects of environmental,
social and governance disclosures and performance on firm value:
A review of the literature in accounting and finance.” The British
Accounting Review 50 (1): 1–15.
Certo, S. T., C. M. Daily, and D. R. Dalton. 2001. “Signaling firm
value through board structure: An investigation of initial public
offerings.” Entrepreneurship Theory and Practice 26 (2): 33–50.
Chandra, A., J. Acosta, L. S. Meredith, K. Sanches, S. Stern, L. Uscher-
Pines, M. Williams, and D. Yeung. 2010. “Understanding commun-
ity resilience in the context of National Health Security.” Arlington,
VA: RAND. https://www.rand.org/content/dam/rand/pubs/work-
ing_papers/2010/RAND_WR737.pdf.
Chen, G. 2020. “Assessing the financial impact of natural disasters on
local governments.” Public Budgeting and Finance 40 (1): 22–44.
Comfort, L. K. 2005. “Risk, security, and disaster management.” An-
nual Review of Political Science 8: 335–56.
———. 2007. “Crisis management in hindsight: Cognition, communi-
cation, coordination, and control.” Public Administration Review
67 (December): 189–97.
Comfort, L. K., A. Boin, and C. C. Demchak. 2010. “Designing resil-
ience: Preparing for extreme events.” Pittsburgh, PA: University of
Pittsburgh Press.
Connelly, B. L., S. Trevis Certo, R. Duane Ireland, and C. R. Reutzel.
2011. “Signaling theory: A review and assessment.” Journal of
Management 37 (1): 39–67.
Copeland, R. M., and R. W. Ingram. 1982. “The association between
municipal accounting information and bond rating changes.” Jour-
nal of Accounting Research 275–289.
Denison, D. V., W. Yan, and Z. (jerry) Zhao. 2007. “Is management
performance a factor in municipal bond credit ratings? The case
of Texas school districts.” Public Budgeting and Finance 27 (4):
86–98.
Doorn, N., P. Gardoni, and C. Murphy. 2019. A multidisciplinary def-
inition and evaluation of resilience: The role of social justice in
defining resilience. Sustainable and Resilient Infrastructure 4(3):
112–123.
Duit, A. 2016. “Resilience thinking: Lessons for public administration.”
Public Administration 94 (2): 364–80.
Ederington, L., J. Yawitz, and B. Roberts. 1984. “The informational
content of bond ratings.” https://doi.org/10.3386/w1323.
Elliott, W. B., A. K. Prevost, and R. P. Rao. 2009. “The announcement
impact of seasoned equity offerings on bondholder wealth.” Jour-
nal of Banking & Finance 33 (8): 1472–80.
Environmental Defense Fund. 2019. “What you need to know about
what’s in—and absent from—Moody’s climate risk report.” https://
www.edf.org/blog/2018/01/03/what-you-need-know-about-whats-
and-absent-moodys-climate-risk-report.
Farrell, J., and M. Rabin. 1996. “Cheap talk.” The Journal of Economic
Perspectives: A Journal of the American Economic Association 10
(3): 103–18.
Fowles, J., G. Liu, and C. Brian Mamaril. 2009. “Accounting for natu-
ral disasters: The impact of earthquake risk on California munic-
ipal bond pricing.” Public Budgeting and Finance 29 (1): 68–83.


## Page 12

Journal of Public Administration Research and Theory, 2023, Vol. 33, No. 4
699
Frederickson, H. G., and T. R. LaPorte. 2002. “Airport security, high
reliability, and the problem of rationality.” Public Administration
Review 62 (September): 33–43.
Gelman, A., and J. Hill. 2006. Data analysis using regression and multi-
level/hierarchical models. Cambridge University Press.
Godschalk, D. R. 2003. Urban hazard mitigation: Creating resilient
cities. Natural Hazards Review 4 (3): 136–143.
Greer, R. A. 2015. “Overlapping local government debt and the fiscal
common.” Public Finance Review 43 (6): 762–85.
———. 2016. “Local government risk assessment: The effect of gov-
ernment type on credit rating decisions in Texas.” Public Budgeting
and Finance 36 (2): 70–90.
Greer, R. A., and D. V. Denison. 2014. “Does intrastate competition in
segmented municipal bond markets affect interest costs? An em-
pirical test of the preferred habitat hypothesis.” Municipal Finance
Journal 35 (2): 1–15.
———. 2016. Determinants of debt concentration at the state level.
Public Budgeting and Finance 36 (4): 111–30.
Greer, R. A., T. T. Moldogaziev, and A. J. Grandage. 2018a. “A mu-
nicipal debt market governance framework: A balancing act with
competing objectives.” Municipal Finance Journal 39 (3): 1–31.
Greer, R. A., T. T. Moldogaziev, and T. A. Scott. 2018b. “Polycentric
governance and the impact of special districts on fiscal common
pools.” International Journal of the Commons 12 (2): 108.
Grizzle, C. 2010. “The impact of budget stabilization funds on state
general obligation bond ratings.” Public Budgeting & Finance 30
(2): 95–111.
Gunderson, L. H. 2000. “Ecological resilience—in theory and ap-
plication.” Annual Review of Ecology and Systematics 31 (1):
425–39.
Guzman, T., and T. Moldogaziev. 2012. “Which bonds are more expen-
sive? The cost differentials by debt issue purpose and the method
of sale: An empirical analysis.” Public Budgeting and Finance 32
(3): 79–101.
Hildreth, W. B. A. 2009. “The financial logistics of disaster: The case
of hurricane Katrina.” Public Performance & Management Review
32 (3): 400–36.
Hildreth, W. B., and C. Kurt Zorn. 2005. “The evolution of the state
and local government municipal debt market over the past quarter
century.” Public Budgeting Finance 25 (4s): 127–53.
Hines, R. E., A. J. Grandage, and K. G. Willoughby. 2020. “Staying
afloat: Planning and managing climate change and sea level rise
risk in Florida’s coastal counties.” Urban Affairs Review, 58 (2):
1078087420980526.
Hollibaugh, G. E. 2018. “The use of text as data methods in public
administration: A review and an application to agency priorities.”
Journal of Public Administration Research and Theory 29 (3): 474–
90. https://doi.org/10.1093/jopart/muy045.
Holling, C. S. 1986. “The resilience of terrestrial ecosystems; local sur-
prise and global change.” In Sustainable Development of the Bio-
sphere, ed. W. C. Clark and R. E. Munn, 292–317. Cambridge, UK:
Cambridge University Press.
———. 1996. “Engineering resilience versus ecological resilience.” En-
gineering within Ecological Constraints 31 (1996): 32.
Hood, C. 1991. “A public management for all seasons?” Public Admin-
istration 69 (1): 3–19.
Hopkins, D. J., and G. King. 2010. “A method of automated nonpa-
rametric content analysis for social science.” American Journal of
Political Science 54 (1): 229–47.
IRS. 2019. “Tax-exempt governmental bonds.” Publication 4079 (Rev.
9-2019) Catalog number 34663R. https://www.irs.gov/pub/irs-pdf/
p4079.pdf.
Ivonchyk, M. 2020. “Gubernatorial policy priorities and state fiscal
outcomes.” Politics & Policy 48 (3): 490–524.
Janney, J. J., and T. B. Folta. 2003. “Signaling through private equity
placements and its impact on the valuation of biotechnology firms.”
Journal of Business Venturing 18 (3): 361–80.
Jerch, R., M. E. Kahn, and G. C. Lin. 2020. “Local public finance
dynamics and hurricane shocks.” https://www.nber.org/papers/
w28050.
Johnson, C. L. 1995. “Managing financial resources to meet environ-
mental infrastructure needs: The case of state revolving funds.”
Public Productivity & Management Review 18 (3): 263.
Johnson, C. L., S. N. Kioko, and W. Bartley Hildreth. 2012.
“Government-wide financial statements and credit risk.” Public
Budgeting & Finance 32 (1): 80–104.
Johnson, C. L., and K. A. Kriz. 2005. “Fiscal institutions, credit ratings,
and borrowing costs.” Public Budgeting Finance 25 (1): 84–103.
Johnson, C. L., M. J. Luby, and T. T. Moldogaziev. 2014. “State and
local financial instruments: Policy changes and management.”
Cheltenham, UK: Edward Elgar Publishing Ltd.
———. 2021. “State and local financial instruments: Policy changes
and management,” 2nd ed. Cheltenham, UK: Edward Elgar Pub-
lishing Ltd.
Kapucu, N. 2008. “Collaborative emergency management: Better
community organising, better public preparedness and response.”
Disasters 32 (2): 239–62.
Kasler, D., and R. Lillis. 2018. “Camp fire: Paradise faces long recov-
ery and ongoing risks.” Sacbee. The Sacramento Bee. December
16, 2018. https://www.sacbee.com/news/state/california/fires/arti-
cle222900130.html.
Kernan, P., M. Button, A. Birry, K. E. Forsgren, M. Kraemer, and A.
D. Palmer. 2017. “How does S&P global ratings incorporate
environmental, social, and governance risks into its ratings a-
nalysis.”
S&P
Global
Ratings.
https://www.spratings.com/
documents/20184/1634005/How+does+sandp+incorporate+ESG+
Risks+into+its+ratings/6a0a08e2-d0b2-443b-bb1a-e54b354ac6a5.
Krishnaswami, S., P. A. Spindt, and V. R. Subramaniam. 1999. “In-
formation asymmetry, monitoring, and the placement structure of
corporate debt.” Journal of Financial Economics 51 (3): 407–34.
Kwan, S. H., and W. T. Carleton. 2010. “Financial contracting and the
choice between private placement and publicly offered bonds.”
Journal of Money, Credit, and Banking 42 (5): 907–29.
LaPorte, T. R., and P. M. Consolini. 1991. “Working in practice but
not in theory: Theoretical challenges of ‘high-reliability organiza-
tions’.” Journal of Public Administration Research and Theory 1
(1): 19–48. https://doi.org/10.1093/oxfordjournals.jpart.a037070.
Leland, H. E., and D. H. Pyle. 1977. “Informational asymmetries, fi-
nancial structure, and financial intermediation.” Journal of Finance
32 (2): 371–87.
Liao, K. H. 2012. A theory on urban resilience to floods—a basis for
alternative planning practices. Ecology and Society 17(4).
Lubell, M. 2019. “The governance gap: Climate adaptation and sea-level
rise in the San Francisco bay area.” University of California, Davis.
http://climatereadinessinstitute.org/wp-content/uploads/2014/03/
UC-Davis-Governance-Gap-Sea-Level-Rise-Final-Report.pdf.
Maher, C. S., S. C. Deller, J. I. Stallmann, and S. Park. 2016. “The im-
pact of tax and expenditure limits on municipal credit ratings.” The
American Review of Public Administration 46 (5): 592–613.
March, J. G.1991. “Exploration and exploitation in organizational
learning.” Organization Science 2 (1): 71–87.
Marlowe, J. 2011. “Beyond 5 percent: Optimal municipal slack re-
sources and credit ratings.” Public Budgeting and Finance 31 (4):
93–108.
Martell, C. R., T. T. Moldogaziev, and S. Espinosa. 2021. “Information
resolution and subnational capital finance.” Oxford, UK: Oxford
University Press.
Mashayekh, Y., J. Paulina, S. Constantine, T. H. Chris, B. Michael, L. M.
Heather, and H. Scott Matthews. 2012. “Potentials for sustainable
transportation in cities to alleviate climate change impacts.” Envi-
ronmental Science & Technology 46 (5): 2529–37.
Mathiesen, K. 2018. “Rating climate risks to credit worthiness.” Nature
Climate Change 8 (6): 454–6.
McNeil, D., and M. Tang. 2020. “Growing protection gap for physi-
cal climate risks.” FitchRatings. November 3, 2020. https://www.
fitchratings.com/research/corporate-finance/growing-protection-
gap-for-physical-climate-risks-03-11-2020-1.
Meerow, S., and J. P. Newell. 2015. “Resilience and complexity: A
bibliometric review and prospects for industrial ecology.” Journal
of Industrial Ecology 19 (2): 236–51.


## Page 13

700
Journal of Public Administration Research and Theory
———. 2019. “Urban resilience for whom, what, when, where, and
why?” Urban Geography 40 (3): 309–29.
Meerow, S., J. P. Newell, and M. Stults. 2016. “Defining urban resil-
ience: A review.” Landscape and Urban Planning 147: 38–49.
Miao, Q., Y. Shi, and D. Meri. 2021. “Fiscal decentralization and nat-
ural disaster mitigation: Evidence from the United States.” Public
Budgeting & Finance 41 (1): 26–50.
Mikesell, J. L. 2012. Financial Administration. Wiley.
Milde, H., and G. R. John. 1988. “Signaling in credit markets.” The
Quarterly Journal of Economics 103 (1): 101–29.
Mileti, D. 1999. “Disasters by design: A reassessment of natural hazards
in the United States.” Joseph Henry Press.
Millon, M. H., and A. V. Thakor. 1985. “Moral hazard and information
sharing: A model of financial information gathering agencies.” The
Journal of Finance 40 (5): 1403–22.
Moldogaziev, T. T., R. A. Greer, and J. Lee. 2019. “Private placements
and the cost of borrowing in the municipal debt market.” Public
Budgeting & Finance 39 (3): 44–74.
Moldogaziev, T. T., and T. Guzman. 2015. “Economic crises, eco-
nomic structure, and state credit quality through-the-cycle.” Public
Budgeting and Finance 35 (4): 42–67.
Moody’s. 2009. “General Obligation Bonds Issued by U.S. Local
Governments Rating Methodology.” Moody’s U.S. Public Finance.
———. 2017. “Climate change is forecast to heighten US exposure to
economic loss placing short- and long-term credit pressure on US
states and local governments.” https://www.moodys.com/research/
Moodys-Climate-change-is-forecast-to-heighten-US-exposure-to--
PR_376056.
Nanda, V., and R. Singh. 2004. “Bond insurance: What is special about
munis?” Journal of Finance 59 (5): 2253–80.
NPR. 2019. “Their home survived the camp fire—But their in-
surance
did
not,”
February
17,
2019.
https://www.npr.
org/2019/02/17/695205917/their-home-survived-the-camp-fire-
but-their-insurance-did-not.
Ostrom, V., M. T. Charles, and W. Robert. 1961. “The organization
of government in metropolitan areas: A theoretical inquiry.” The
American Political Science Review 55 (4): 831–42.
Ostrom, V., and E. Ostrom. 2019. “Public goods and public choices.”
In Alternatives for delivering public services, 7–49. New York, NY:
Routledge.
Palumbo, G., and M. P. Zaporowski. 2012. “Determinants of municipal
bond ratings for general-purpose governments: An empirical analy-
sis.” Public Budgeting and Finance 32 (2): 86–102.
Paradise Irrigation District. 2019. “Water Quality Advisory—After the
Camp Fire—Paradise Irrigation District.” https://pidwater.com/
wqadvisory.
Pearson, C. M., and I. I. Mitroff. 1993. “From crisis prone to crisis
prepared: A framework for crisis management.” The Academy of
Management Executive 7 (1): 48–59.
Peng, J., and P. F. Brucato. 2004. “An empirical analysis of market and in-
stitutional mechanisms for alleviating information asymmetry in the
municipal bond market.” Journal of Economics and Finance 28 (2):
226–238.
Pizzo, B. 2015. “Problematizing resilience: Implications for planning
theory and practice.” Cities 43: 133–140.
Pottier, S. W., and D. W. Sommer. 1999. “Property-liability insurer fi-
nancial strength ratings: Differences across rating agencies.” The
Journal of Risk and Insurance 66 (4): 621–42.
Reck, J. L., and E. R. Wilson. 2006. “Information transparency and
pricing in the municipal bond secondary market.” Journal of Ac-
counting and Public Policy 25 (1): 1–31.
Rainey, H. G. 2009. “Understanding and managing public organiza-
tions.” Hoboken, NJ: John Wiley & Sons.
Ramakrishnan, R. T. S., and A. V. Thakor. 1984. “Information reliabil-
ity and a theory of financial intermediation.” The Review of Eco-
nomic Studies 51 (3): 415–32.
Rich, K. T., B. L. Roberts, and J. X. Zhang. 2021. “Linguistic tone of
management discussion and analysis disclosures and the municipal
debt market.” Journal of Public Budgeting, Accounting & Financial
Management 39 (February): 88.
Rosenzweig, C., D. S. William, B. Reginald, B. Malcolm, F. Craig, G.
Vivien, H. Radley, et al. 2011. “Developing coastal adaptation to
climate change in the New York City infrastructure-shed: Process,
approach, tools, and strategies.” Climatic Change 106 (1): 93–127.
Saliterer, I., S. Korac, C. Barbera, and I. Steccolini. 2021. “Taking stock:
The role of the institutional context for local government financial
resilience.” In Local public finance: An international comparative
regulatory perspective, ed. René Geissler, Gerhard Hammerschmid,
and Christian Raffer, 319–32. Cham: Springer International Pub-
lishing.
Schick, A. 1966. “The road to PPB: The stages of budget reform.” Pub-
lic Administration Review 26 (4): 243.
Selznick, P. 2011. “Leadership in administration: A sociological inter-
pretation.” New Orleans, LA: Quid Pro Books.
Simonsen, W., and M. D. Robbins. 1996. “Does it make any differ-
ence anymore? Competitive versus negotiated municipal bond issu-
ance.” Public Administration Review 56 (1): 57.
Speer, R., J. Chin, and C. Havasi. 2017. “ConceptNet 5.5: An Open
Multilingual Graph of General Knowledge,” 44–51. AAAI.
Spence, M. 1978. Job market signaling. In Uncertainty in economics,
281–306. Cambridge, MA: Academic Press.
———. 2002. “Signaling in retrospect and the informational struc-
ture of markets.” American Economic Review. https://doi.
org/10.1257/00028280260136200.
S&P. 2013. “U.S. Local Governments General Obligation Ratings:
Methodology and Assumptions.” S&P Global Ratings.
Sutcliffe, K. M., and T. J. Vogus. 2003. Organizing for resilience. In:
Cameron, K.S., Dutton, J.E. and Quinn, R.E., eds. Positive Organ-
izational Scholarship: Foundations of a New Discipline, 94–110.
San Francisco: Berrett-Koehler.
Sutton-Grier, A. E., K. Wowk, and H. Bamford. 2015. “Future of
our coasts: The potential for natural and hybrid infrastructure
to enhance the resilience of our coastal communities, economies
and ecosystems.” Environmental Science & Policy 51 (August):
137–48.
Ulibarri, N., and T. A. Scott. 2019. “Environmental hazards, rigid
institutions, and transformative change: How drought affects the
consideration of water and climate impacts in infrastructure man-
agement.” Global Environmental Change 59: 102005.
Vale, L. J. 2014. “The politics of resilient cities: Whose resilience
and whose city?” Building Research and Information 42 (2):
191–201.
Vegt, G. S. van der, P. Essens, M. Wahlström, and G. George. 2015.
“Managing risk and resilience.” Academy of Management Journal
58 (4): 971–80.
Webster, K. 2018. “Wildfire’s destruction of California town creates un-
charted credit territory.” Bond Buyer. November 13, 2018. https://
www.bondbuyer.com/news/california-wildfire-destruction-may-
devastate-credits.
Wildavsky, A. B. 1988. “Searching for safety.” Piscataway, NJ: Trans-
action Publishers.
Zimmerman, R., S. Foster, J. E. González, K. Jacob, H. Kunreuther, E.
P. Petkova, and E. Tollerson. 2019. “New York City panel on cli-
mate change 2019 report chapter 7: Resilience strategies for criti-
cal infrastructures and their interdependencies.” Annals of the New
York Academy of Sciences 1439 (1): 174–229.


## Page 14

© 2023 Public Management Research Association. Copyright of Journal of Public
Administration Research & Theory is the property of Oxford University Press / USA and its
content may not be copied or emailed to multiple sites or posted to a listserv without the
copyright holder's express written permission. However, users may print, download, or email
articles for individual use.

