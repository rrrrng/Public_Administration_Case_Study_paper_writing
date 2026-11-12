# Public Administration Review - 2025 - Potoski - Measuring Transaction Costs in P

## Page 1

Public Administration Review, 2026; 86:199–216
https://doi.org/10.1111/puar.13947
199
Public Administration Review
RESEARCH ARTICLE
OPEN ACCESS
Measuring Transaction Costs in Public Sector Contracting
Through Machine Learning and Contract Text
Matthew Potoski1  |  Bjarke Lund-Sørensen2  |  Ole Helby Petersen2
1Bren School of Environmental Science and Management, University of California, Santa Barbara, California, USA  |  2Department of Social Sciences and
Business, Roskilde University, Roskilde, Denmark
Correspondence: Ole Helby Petersen (olehp@ruc.dk)
Received: 11 April 2024  |  Revised: 12 February 2025  |  Accepted: 17 February 2025
Funding: This research was supported by the Independent Research Fund Denmark (Grant no. 9061-00020B).
Keywords: contract management | machine learning | transaction costs
ABSTRACT
Transaction cost (TC) theoretical constructs are central to research throughout the social sciences, yet key concepts, such as
measurability and asset specificity, often defy systematic empirical measurement. In government contracting research, empirical
measurements of key TC theoretical constructs are limited to the International City/County Management Association's surveys
of US municipal and county governments. We present a preregistered method using machine learning algorithms to generate
product-­level TC measures from contract text data and a government contract manager survey. We verify the algorithms' out-­of-­
sample performance and use them to generate TC measures for additional products from corresponding contract text data. The
result is a publicly available database of new TC measures for 176 diverse products and services covered in the European Union's
Common Procurement Directives. These new measures facilitate the application of the TC framework across public manage-
ment, including research on government contracting, collaboration, networks, and governance.
The transaction cost (TC) theoretical framework (Coase 1988;
Williamson  1979, 1985) identifies factors that influence the
costs, benefits, and risks inherent in social interactions.
Unsurprisingly, the framework has a robust presence through-
out the social sciences, with applications in areas such as organi-
zations (Scott 1987, 2004), financial markets (Hasbrouck 1993),
governments (North  1990, 1991), business management
(Geyskens et al. 2006), and self-­governance (Ostrom 1990).1 In
public administration research, the TC framework has guided
a generation of scholarship by identifying contracting chal-
lenges and potential management practices for any purchase
made by any government in any circumstance. Some of these
challenges arise because of the conditions of the exchange such
as the number of buyers and sellers in a market (Brunjes 2020;
Girth et al. 2012). Other challenges stem from the nature of the
product itself, particularly whether the product's features can be
easily specified in a contract and evaluated upon receipt (often
called “measurability”), and the degree to which a product loses
value if put to an alternative use (often called “asset specificity”)
(Brown and Potoski 2003b; Hefetz and Warner 2012; Levin and
Tadelis 2010; Madsen 2023; Malatesta and Smith 2011).
A challenge of the TC theoretical framework is that features that
make products difficult to purchase also make them difficult to
study in research. Products that are difficult to measure when
purchasing are also difficult to measure for research. For exam-
ple, it may be intuitively obvious that the outcomes of employ-
ment training services are more difficult to measure than those
of refuse collection services, but it is much less clear by how
much, or whether employment training services are more dif-
ficult to measure than childcare services. Asset specificity like-
wise defies measurement in research settings; a product's price
indicates its value to the buyer but not the value lost when the
buyer puts it to an alternative use. Using TC for its full potential,
This is an open access article under the terms of the Creative Commons Attribution-NonCommercial License, which permits use, distribution and reproduction in any medium, provided the
original work is properly cited and is not used for commercial purposes.
© 2025 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.


## Page 2

200
Public Administration Review, 2026
whether for theoretically informed contracting research or im-
proving public management practice, thus requires precise mea-
sures of abstract concepts across the broad range of goods and
services that governments purchase and with measures that can
be directly linked to large, robust datasets on government con-
tracting activities.
Over the past several decades, public management scholars have
responded to the challenge of measuring TC concepts, with each
effort deploying a similar analytic approach: Start with a stan-
dard source of contracting data and then survey government
managers about their perceptions of the TC features of the goods
and services in the data (Brown and Potoski 2003b; Hefetz and
Warner 2012; Levin and Tadelis 2010). The primary starting data
source has been the International City/County Management
Association's Alternative Service Delivery Survey (ICMA sur-
vey). The ICMA survey asks US municipal and county managers
about delivery practices for 67 common government services,
with managers indicating whether their government produces
the services or contracts for them with businesses, other govern-
ments, or nonprofits. Scholars then survey managers on their
perceptions of TC theoretical concepts in those services, such
as the difficulty of measuring quality or specificity of the assets.
Since introduced, these measures have been used in countless
studies of government contracting and contract management
(Ernita Joaquin and Greitens 2012; Fernandez 2007; Ferris and
Graddy 1986; Girth et al. 2012; Lamothe et al. 2018; Lamothe
and Lamothe  2016; Marvel and Marvel  2007; Stein  1993; Wei
et al. 2022).
Despite their widespread use in public management research,
the ICMA-­based TC measures have important limitations.
Governments buy many more products and services than the
67 items listed in the ICMA. Moreover, the ICMA items are
broad categories; specific purchases within those categories
can pose very different contract management challenges, and
the item labels may not correspond to the terms governments
use when making purchases. Finally, the ICMA is limited to
U.S. local governments, and the ICMA data may be subject
to the reliability limitations commonly found in survey data
(Lamothe et al. 2018). These limitations in how TC concepts
are measured have important consequences for contract man-
agement research and practice. For scholars, the ICMA TC
measures are difficult to apply outside of the ICMA surveys.
For practitioners, the ICMA TC measures may not apply to
the specific product or service they are considering purchas-
ing. Meanwhile, there are no product-­level TC measures for
the two largest publicly available data sources on government
contracting: The United States' Federal Procurement Data
System (FPDS) and the European Common Procurement
Directives (EU CPD).
In this article, we introduce a new series of TC measures for
176 commonly purchased products and services. We begin
with a comprehensive dataset of the complete contract text for
2774 government contracts (requests for proposals, products
specifications, delivery terms, contract clauses, and all other
documents) covering a broad range of products and services
that governments buy. We then replicate the procedures used
in the ICMA-­based TC measures: We survey public contract
managers to directly measure TC characteristics for 58 com-
monly purchased products. We use the survey TC measures
for 40 products to develop and train machine learning (ML)
natural language algorithms to produce measurement and
asset specificity measures from the corpus of contract text. All
steps in the training and application of the ML measures were
preregistered with the Open Science Framework (https://​doi.​
org/​10.​17605/​OSF.​IO/​6FE9Z​), and the computer code for the
analysis is provided on GitHub.2 We then use the algorithm
to produce out-­of-­sample TC measures for 18 additional prod-
ucts and validate their efficacy using the survey TC measures
for those products. We find that the ML algorithms produce
TC measures similar to the survey TC measures. Finally, we
apply the ML algorithms to contract text data to produce TC
measures for an additional 118 products, thereby generating
TC measures for a broad range of goods, services, and public
works purchased by governments.
The result is TC measures for 176 products with properties that
overcome the limitations of the ICMA TC measures, making
them more useful for public management scholars and practi-
tioners, as well as the broader scholarly communities using the
TC framework. This article thus offers several contributions to
government contracting research. First, the ML TC measures
are quite accurate in comparison to survey TC measures for
products that were not part of the sample used to develop the
ML algorithms. Second, the products are labeled using the
terminology of the European Union's Common Procurement
Vocabulary (CPV). The CPV is part of the EU CPD and thus
provides a standard labeling framework for commonly pur-
chased products and services across many governments and
countries in one of the world's largest economic zones, allow-
ing the TC measures to be used in many empirical settings.
Third, the CPV items apply at the contract level, thus provid-
ing a more precise correspondence between the TC framework
and the goods and services governments are actually buying.
Finally, to inform public management research, we make the
full dataset of measurement and asset specificity measures
easily accessible in Appendix S2. The metrics developed in this
study can thus be used in subsequent government contracting
research as well as other areas of social science inquiry where
the TC framework is relevant. TC factors are relevant not just
for government contracting but also for other areas where gov-
ernments interact with individuals and organizations, such as
Summary
•	 Identifying transaction cost risks stemming from
product characteristics is a persistent obstacle for gov-
ernment contracting research and practice.
•	 This article presents applied transaction cost meas-
ures for 176 commonly purchased products labeled
with the EU Common Procurement Vocabulary.
•	 These measures can guide research and practice by
precisely specifying the most theoretically and practi-
cally relevant product characteristics.
•	 This article shows how machine learning techniques
and contract text data can be leveraged to construct
theoretically and empirically relevant transaction
measures across a large range of products and services.


## Page 3

Public Administration Review, 2026
201
policy networks (Lubell et  al.  2017), policy implementation
(Ramírez De La Cruz et al. 2020), comparative organizational
performance (Coupet and McWilliams 2017), and intergovern-
mental collaboration (Scott and Merton 2021; Ulibarri 2024).
The next section describes the TC theoretical framework and
the efforts and challenges toward its theoretical concepts in gov-
ernment contracting research settings. The following section
presents the methods and data for developing TC measures from
contract text. A fuller description is provided in Appendix S1.
The results section presents the TC measures and the analyses
verifying the algorithms' accuracy in generating out-­of-­sample
TC measures for all remaining products. The final section con-
cludes the article and suggests directions for applying the arti-
cle's insights and data in future research.
1   |   Theory and Background: The TC Framework
and the ICMA Service Delivery Surveys
When governments purchase products, a central manage-
ment challenge is to obtain the best value for the cost of the
purchase (Amirkhanyan and Lambright  2017; Andrews and
Entwistle 2010). The value includes the product's performance
and the broader social goals governments pursue, such as trans-
parency in purchasing or greenhouse gas reductions (Dimand
et al. 2023). The costs of a purchase include the product's price,
the money and effort expended to make exchanges happen, and
the risk of losses should the exchange fail (Petersen et al. 2019;
Van Slyke 2003). When contracting works well, the government
receives value greater than its costs, and when contracting fails,
the government can be left worse off than if it had not tried to
make any purchase at all. Improving contract management of-
fers important social value because of the financial stakes in
government purchasing, which range between 20% and 45% of
government budgets among the OECD countries (OECD 2021).
TC economics has become a theoretically informed and practi-
cally applicable framework for guiding research and practice re-
lated to contracting and contract management (Anguelov 2020;
Ferris and Graddy 1986). According to Williamson (1981), TCs
are the “comparative costs of planning, adapting, and monitor-
ing task completion under alternative governing structures” (pp.
552–553). A buyer facing prohibitive costs in finding desirable
products, negotiating with sellers, and enforcing the terms of the
agreement may find it better to produce the product on its own
than to buy it from the market. The TC framework helps guide
research and practice about when governments should purchase
products versus make them themselves and about what man-
agement practices should be implemented when purchasing
under different conditions (Dimand et al. 2023; Kang et al. 2022;
Lamothe et al. 2008; Piatak and Jensen 2024).
In the TC framework, the likelihood of contract failure depends
to a considerable degree on the product characteristics and
conditions of exchange. TCs arise when there is limited infor-
mation, uncertainty about the future, and when people or orga-
nizations may behave opportunistically to exploit the exchange
for their own gain (Coase 1988; Williamson 1979, 1981, 1985).
For example, contracts are more likely to fail when buyers have
incomplete information about product quality, perhaps because
the service is difficult to measure. Public management research
uses the term “difficult to measure” or “ease of measurement”
to refer to circumstances where the purchasing government is
uncertain about the quality of the product or is unable to pre-
cisely define what it wants to buy in the transaction (Brown
and Potoski 2003a, 2003b; Hefetz and Warner 2012; Levin and
Tadelis 2010; Schoute et al. 2018). Contracts are also more likely
to fail when the owner of a resource would lose value if the prod-
uct were put to an alternative use. Public management research
uses the term “asset specificity” to refer to conditions where
the owner of a resource experiences losses when deploying the
resources to an alternative use (Anguelov  2020; Brown and
Potoski 2003b; Esteve et al. 2024). The seller may look to exploit
difficult measurement and asset specificity by raising prices or
lowering quality, and the purchasing government may need to
spend more resources on contract management activities, such
as writing more detailed contracts (Brown et al. 2007) or mon-
itoring vendor performance (Ernita Joaquin and Greitens 2012;
Marvel and Marvel 2007).
Around the world, purchasing is one of the central tasks many
government managers perform. Nearly every academic study of
government contracting invokes concepts from the TC frame-
work, particularly the measurability and asset specificity of the
product being purchased, often called a product's “complexity”
(Malatesta and Smith 2014; Piatak and Jensen 2024). Taken as
a whole, government contracting research bears the hallmarks
of an unfortunate dilemma. On the one hand, the best empir-
ical measures of products' TC characteristics are attached to
ICMA surveys, which have questionable reliability (Lamothe
et al. 2018), cover only a small number of products, and cover
only municipal/county government purchasing in the United
States. On the other hand, the largest and most comprehensive
sources of data on government contracting lack empirical mea-
sures of products' TC characteristics. The constraints of these
two approaches are further discussed below.
Despite the importance of government purchasing, relatively
little research has used either of the two largest publicly avail-
able contracting systems in the world: FPDS and EU CPD,
which govern government purchasing throughout the European
Union's 27 member states. The EU CPD includes the EU CPV, a
classification system that categorizes all items governments pur-
chase. The EU CPV thus requires that the Barcelona city gov-
ernment and the national government of Germany use the same
purchasing code when buying printer articles. The EU CPD
also requires governments to disclose their purchasing notices
at Tenders Electronic Daily (TED) using a standard reporting
format, available to the public in a standardized online format at
no cost. In 2022, EU governments issued 676,000 procurement
notices worth approximately €670 billion (Tenders Electronic
Daily 2023).
A potential reason for the paucity of research using FPDS
and the EU CPD is the absence of TC measures for the vast
array of products covered in the data, leaving scholars to look
for patchwork solutions and workarounds (Anguelov  2020;
Brunjes 2020; Kim and Brown 2012; Piatak and Jensen 2024).
For example, Brunjes  (2020) analyzes FPDS data to investi-
gate the association between vendor competition and con-
tract closeout/termination. To identify product measurability,


## Page 4

202
Public Administration Review, 2026
Brunjes uses categorical variables for the broad product classi-
fication of what the government is purchasing, such as “infor-
mation technology,” “professional services,” “training,” and
“research” (Brunjes 2020), and Piatak and Jensen (2024) use
qualitative assessments to compare the complexity of human
services. Likewise, in the EU context, Petersen et al. (2015)
apply self-­assessed measures of low, medium, and high TCs
across a range of contracted services. Such simple proxy mea-
sures are quite likely to measure factors other than TCs and
TC characteristics for specific purchases.
In contrast to the FPDS and the EU CPD, there is relatively exten-
sive research using the ICMA surveys on municipal and county
government contracting in the United States. The ICMA is a U.S.-­
based professional association of local government managers
founded in 1914. The ICMA holds meetings, conducts research,
and advocates for its members. Every 4–5 years since 1982, the
ICMA has managed surveys of how municipal and county gov-
ernments throughout the U.S. deliver services. The data contain
information on 67 services, such as data processing, street re-
pairs, child welfare programs, and refuse collection, and report
on whether the service was delivered by the municipal govern-
ment, or through a contract with another government, a private
firm, or a nonprofit organization (Brown and Potoski  2003a,
2003b; Hefetz and Warner 2012). Since its launch, the ICMA data
have informed public management scholars, starting with Stein
(1990)'s classic study Urban Alternatives and continuing through
today (Lamothe and Lamothe 2024). Most of this research sup-
plements the ICMA surveys with additional data, such as U.S.
census data on population characteristics or municipal form of
government and finances.
An important reason for the broad application of the ICMA data
in public management research is the work by three separate
teams to produce TC measures for the products in the ICMA
data. The studies are Brown and Potoski  (2003a, 2003b) (BP),
Levin and Tadelis  (2010) (LT), and Hefetz and Warner  (2012)
(HW) with each effort deploying a similar analytic approach:
Starting with a standard source of contracting data and then sur-
veying government managers about their perceptions of the TC
features of the goods and services in the data. Table 1 reports the
TC constructs measured in each approach.3
As seen in Table 1, the BP, LT, and HW transaction-­cost measures
are quite similar. Each includes the degree to which a service is
difficult to measure, what BP and HW refer to as “difficult to
measure” and what LT refer to as “measurement.” Likewise, they
each assess the extent to which the seller's resources allocated
to the contract can be deployed to an alternative productive use,
what BP and HW refer to as “asset specificity” and what LT refer
to with two measures, “hold up” and “flexibility.” The approach
of measuring asset specificity and ease of measurement (as used
in both BP and HW) has been followed in other survey-­based TC
measurement research outside the ICMA. For example, Schoute
et al. (2018) present measurement difficult and asset specificity
measures for 12 goods and services in the Netherlands (Schoute
et al. 2018), and Petersen et al. (2019) present measurement dif-
ficulty measures for 22 goods and services in Denmark. Table 2
shows correlations among the BP, LT, and HW transaction-­cost
measures. The correlations show some clustering around theo-
retical concepts: The asset specificity measures correlate more
strongly with other asset specificity measures; the measurabil-
ity measures correlate more with other measurability measures;
and the measurability measures have lower correlations with the
asset specificity measures.
Taken together, Tables 1 and 2 suggest that ICMA-­based TC mea-
sures provide some guidance in measuring TC theoretical con-
cepts. There are theoretical and empirical reasons to distinguish
between asset specificity and measurability, and these concepts
have been most extensively applied in the scholarly literature.
We therefore focus on asset specificity and measurement as the
two TC categories for our TC measurement approach. We leave
the investigation into additional TC categories, such as those pro-
posed by Levin and Tadelis (2010), to future research.
Although some public management studies used the ICMA
surveys before the early 2000s (Ferris and Graddy  1986;
Stein 1993), the introduction of the TC measures facilitated the
increase in the number of public management studies using
the ICMA surveys and the breadth of topics covered in those
studies. The BP, LT, and HW measures have all proven use-
ful in applied contract management research and have been
used in scores of studies using the ICMA service delivery data.
Several studies focus on evaluating when governments choose
to purchase a product and whether they choose a business, gov-
ernment, or nonprofit as the seller (Brown and Potoski 2003b;
Levin and Tadelis 2010; Schoute et al. 2018). Others investi-
gate how TC characteristics influence contract management
practices (Anguelov  2020; Brown and Potoski  2003a, 2006;
Girth et al. 2012), the type of contract used for the exchange
(Lamothe and Lamothe 2012), and even the outcomes of the
contract (Fernandez 2007). These studies, and many others,
reveal how much the TC cost measures enhance the value of
the ICMA service delivery data.
At the same time, the ICMA surveys and TC measures have
important limitations. First, they cover a relatively small
range of items governments purchase, and these items are
largely government services and contain few physical prod-
ucts. Second, many of the ICMA items are broad categories
that can have several components with different theoretical
qualities. For example, the ICMA's “Child Welfare Programs”
can include both food provision, which can be relatively easy
to measure, and childcare, which can be significantly more
difficult to measure. Third, the ICMA items are not clearly
connected to the terms and concepts used in real public sector
contracts. In practice, a contract is more likely to use more
precise descriptions like the EU CPV's “personal care prod-
ucts—toiletries, toilet paper, and infant care” rather than
broad categories like the ICMA's “Child Welfare Programs.”
Perhaps most importantly, the ICMA data have questionable
reliability (Lamothe et al. 2018) and apply only to municipal
and county governments in the United States.
Contract management research has faced an unfortunate di-
lemma between using the ICMA data that has TC measures but
otherwise lacks breadth and reliability and using the U.S. FPDS
or EU CPD that have breadth and reliability but lack TC mea-
sures. This dilemma suggests an opportunity with vast potential
for advancing research and TC theory more generally: Adding
product-­level TC measures to large, publicly available government


## Page 5

Public Administration Review, 2026
203
TABLE 1    |    Manager survey transaction cost measures for ICMA products.
Product
BPAS
BPME
HWAS
HWME
LTCD
LTM
LTF
LTH
Airport operation
4.19
2.96
3.99
3.47
All other vehicles maintenance
3.39
2.61
Ambulance service
3.61
2.43
4.11
3.17
Animal control
2.68
2.81
2.98
2.83
0.64
0.20
0.37
0.39
Animal shelter operation
2.80
2.87
3.10
2.69
Building security
2.24
2.17
2.78
2.37
−0.98
−0.45
−0.36
−0.76
Buildings/grounds maintenance
2.00
2.20
2.94
2.45
−1.08
−0.69
−0.27
−0.79
Bus system maintenance
3.18
2.91
Cemeteries maintenance
2.37
2.41
2.26
2.07
Child welfare programs
3.52
4.08
3.29
3.47
Commercial waste collection
3.06
1.97
2.83
2.15
Convention centers/auditoriums operation
3.58
2.77
3.27
3.02
−1.21
−0.96
−0.61
−0.28
Crime prevention/patrol
3.37
3.60
4.07
3.89
Cultural/arts programs operation
3.00
3.26
2.79
2.87
2.08
1.11
0.99
1.10
Data processing
3.14
2.61
3.75
2.91
Daycare facilities operation
3.36
3.44
2.99
2.74
0.78
0.53
0.52
0.09
Delinquent tax collection
2.51
2.08
3.00
2.53
−0.72
−0.45
−0.41
−0.26
Drug/alcohol treatment programs
3.63
4.12
3.32
3.38
1.64
0.83
1.12
0.51
Elderly programs
3.14
3.48
3.00
2.99
1.16
0.76
0.61
0.36
Electric utility management
4.08
2.96
4.20
3.59
Emergency medical service
3.91
2.76
4.40
3.42
0.72
0.32
0.12
0.73
Emergency vehicles maintenance
3.28
2.11
3.74
2.70
Fire prevention/suppression
3.80
3.24
4.35
3.64
1.41
0.89
0.28
1.08
Gas utility management
4.08
3.00
4.11
3.55
Hazardous materials disposal
4.22
2.88
4.14
3.56
Heavy equipment maintenance
3.06
2.22
3.66
2.71
Homeless shelters operation
3.12
3.42
2.65
2.92
Hospital operation/management
4.17
3.40
4.14
3.92
Insect/rodent control
2.53
2.63
2.74
2.44
0.32
0.47
0.11
−0.14
Inspection/code enforcement
2.97
2.72
3.94
3.43
1.47
0.84
0.82
0.56
Job training programs
3.09
3.05
Legal services
3.39
3.46
4.20
2.90
0.54
0.13
0.55
0.09
Libraries operation
3.50
2.61
3.53
3.07
0.34
0.28
−0.07
0.34
Lots/garages operation
2.36
2.03
2.18
2.04
−1.29
−0.55
−0.60
−0.91
Mental health programs operation
3.96
4.29
3.63
3.53
Museums operation
3.59
2.85
3.39
2.94
0.46
0.38
−0.03
0.38
Operation of bus transit systems
3.35
2.48
Paratransit system maintenance
3.50
2.69
3.1
2.92
Parking meter maintenance
2.39
2.24
1.87
2.07
Parks landscaping/maintenance
2.33
2.11
2.9
2.47
−0.91
−0.31
−0.62
−0.49
(Continues)


## Page 6

204
Public Administration Review, 2026
contracting data sources can pave the road for contract manage-
ment research studying a fuller range of products and services
purchased by many different governments in different social and
economic circumstances. The next section describes our proce-
dures for producing these measures using contract manager sur-
veys, large databases of contract text, and ML algorithms.
2   |   Methods and Data for Generating TC Measures
From Contract Text Using Manager Survey and ML
Algorithms
We use contract text, a survey of government managers, and
ML algorithms to generate TC measures for 176 goods, services,
and public works contracts listed in the EU CPV, the largest
publicly available data on government contracting worldwide.
The analysis plan was preregistered with the Open Science
Framework (https://​doi.​org/​10.​17605/​OSF.​IO/​6FE9Z​). Because
these procedures are particularly complex and ML techniques
are relatively new in public administration (Anastasopoulos and
Whitford  2019), we briefly summarize the procedures below
while providing a more complete description in Appendix S1.
Figure 1 depicts the sequence of steps in the analytic procedures.
We first downloaded complete contract text (requests for pro-
posals, product specifications, delivery terms, contracts, and all
other documents) for 2774 Danish municipal and county govern-
ment contracts and assigned 1740 contracts (representing 60 CPV
codes) into a dataset for creating the ML algorithms to generate TC
measures. We surveyed 1061 government contract managers (549
Product
BPAS
BPME
HWAS
HWME
LTCD
LTM
LTF
LTH
Payroll
2.36
1.53
3.33
2.37
Personnel services
2.58
3.31
3.4
2.78
Police/fire communications
3.80
2.59
4.28
3.64
0.6
0.40
0.26
0.25
Prisons/jails
4.04
3.21
4.09
3.73
Public health programs
3.46
3.74
3.66
3.6
Public relations/public information
2.65
3.31
3.1
2.77
Recreation facilities maintenance
2.94
2.61
3.3
2.83
0.22
0.20
0.04
0.07
Residential waste collection
3.00
2.06
2.91
2.17
−1.25
−1.09
−0.75
−0.03
Sanitary inspection
3.06
2.57
3.24
2.93
Secretarial services
1.75
2.92
2.61
2.14
Sewage collection/treatment
4.09
2.36
4.49
3.59
0.35
0.00
0.03
0.55
Sludge disposal
3.52
2.36
3.7
2.93
Snow plowing/sanding
2.50
2.21
2.7
2.37
Street repair
2.64
2.4
3.32
2.56
−0.31
−0.17
0.11
−0.51
Street/lot cleaning
2.26
2
2.4
1.94
−1.19
−0.35
−0.54
−1.03
Tax assessing
2.93
2.87
3.72
3.02
Tax bill processing
2.31
1.91
3.23
2.56
Title records/plat map maintenance
3.21
2.58
3.45
2.8
Traffic control/parking enforcement
2.59
2.53
2.91
2.77
Traffic sign maintenance
2.91
2.24
3.6
2.61
Tree trimming/planting
2.14
2.36
2.61
2.34
−0.85
−0.30
−0.20
−0.92
Utility billing
3.11
2.5
3.03
2.45
Utility meter reading
2.32
2.03
2.88
2.37
−1.27
−0.56
−0.92
−0.46
Vehicle towing and storage
2.07
1.97
2.23
2.14
−1.16
−0.65
−0.37
−0.84
Waste disposal
3.33
2.12
3.81
2.82
−0.40
−0.44
−0.50
0.40
Water distribution
3.94
2.44
4.45
3.5
Water treatment
4.12
2.36
4.45
3.54
0.29
−0.13
0.09
0.53
Welfare eligibility determination
3.35
2.48
2.94
3.11
Abbreviations: BPAS, Brown and Potoski (2003a, 2003b) asset specificity; BPME, Brown and Potoski (2003a, 2003b) measurement; HWAS, Hefetz and Warner (2012)
asset specificity; HWME, Hefetz and Warner (2012) measurement; LTCD, Levin and Tadelis (2010) contract difficulty; LTF, Levin and Tadelis (2010) flexibility; LTH,
Levin and Tadelis (2010) holdup; LTM, Levin and Tadelis (2010) measurability.
TABLE 1    |    (Continued)


## Page 7

Public Administration Review, 2026
205
responses, response rate = 51.7%) to create TC measures for these
60 CPV codes. We then divided the 60 products into a training and
testing set, with 42 products in the training set and 18 products
in the testing set. Two of the 42 products in the training set had
no corresponding contracts in the contract dataset. We therefore
ended up with 58 products: 40 products in the training set and 18
in the testing set.4 We used all contracts for the 40 CPV codes to
train ML algorithms to identify product description language in
the contract text. We then trained the ML algorithms to generate
TC measures from the product description text and the contract
manager TC measures at the contract level. We aggregated these
contract-­level scores for the products and services corresponding
to the corresponding CPV codes. We then conducted an out-­of-­
sample assessment by applying the algorithms to generate new
TC measures for the 18 products in the test dataset and compared
these measures to our contract manager survey TC measures.
Finally, we applied the best-­performing algorithms to the contract
text for the remaining 118 products in the contract dataset, thereby
generating ML algorithm TC measures for all types of goods, ser-
vices, and public works contracts purchased by municipal and
county governments. Scholars can use these TC measures to study
a comprehensive range of procurement and contract management
topics across the diverse contexts of the EU member countries.
Moreover, scholars can use these ML procedures (described more
fully in Appendix S1) to create TC measures for other products and
in other settings, thereby facilitating the advancement of public
management research using the TC framework.
2.1   |   Step 1: Contract Text Database
We created a contract text dataset by downloading all procure-
ment announcement documents and contract text from online
databases (Mercell, EU-­Supply, Ethics, Comdia, iBinder, and
others) for all purchases made by Danish municipal and county
governments (including municipal utility companies) over
2 years in 2021 and 2022. We conducted the downloads weekly,
with each being subjected to manual inspection and quality as-
surance by the research team. We used a computer program to
divide the documents into text sections based on headings and
subheadings and create a database of documents for 2774 pur-
chases (contracts) covering the full population of Danish munic-
ipal and county government contracts.
2.2   |   Step 2: Create Dataset for Training,
Assessment, and Application of the ML Algorithms
We assigned 1740 contracts for 58 CPV codes to a dataset that
we used to train and assess the ML algorithms. We further di-
vided the 58 CPV codes by randomly assigning 40 CPV codes
(approximately 70%) to a training dataset for developing the
ML algorithms to generate TC measures, and 18 CPV codes
(approximately 30%) to a testing dataset for assessing the ML
algorithms. In ML research, assigning 70% of the data to a
training dataset and 30% to a testing dataset is standard prac-
tice (Anastasopoulos and Whitford 2019). We assigned the 1034
contracts for the remaining 118 CPV codes to another dataset for
applying the ML algorithms to create new TC measures.
2.3   |   Step: 3 Extract Product Description
Language From Contract Text
We trained four ML algorithms to identify product descrip-
tion language using manually coded product description text
in a sample of contracts from the training dataset. We manu-
ally coded contract text by developing a coding procedure for
identifying product description language in the contract text
dataset. To develop the procedures, all three authors manually
coded the same documents and cross-­checked their results
(see Appendix S1 for the description of the specific coding pro-
cedure). We then applied the four ML algorithms to the con-
tract text data to identify product description language using
the manually coded contract text: Linear regression, random
forest, support vector machine, and neural network machine
learning.
We conducted six rounds of algorithm training to extract prod-
uct description language. After each round, we added addi-
tional manually coded contracts and assessed the algorithms'
TABLE 2    |    Correlations among manager survey transaction cost measures.
Transaction cost measures
BPAS
BPME
HWAS
HWME
LTCD
LTM
LTF
LTH
BPAS
1
BPME
0.46
1
HWAS
0.80
0.27
1
HWME
0.86
0.62
0.83
1
LTCD
0.60
0.81
0.51
0.73
1
LTM
0.44
0.77
0.36
0.61
0.95
1
LTF
0.43
0.85
0.36
0.60
0.93
0.88
1
LTH
0.79
0.62
0.70
0.82
0.86
0.72
0.66
1
Abbreviations: BPAS, Brown and Potoski (2003a, 2003b) asset specificity; BPME, Brown and Potoski (2003a, 2003b) measurement; HWAS, Hefetz and Warner (2012)
asset specificity; HWME, Hefetz and Warner (2012) measurement; LTCD, Levin and Tadelis (2010) contract difficulty; LTF, Levin and Tadelis (2010) flexibility; LTH,
Levin and Tadelis (2010) holdup; LTM, Levin and Tadelis (2010) measurability.


## Page 8

206
Public Administration Review, 2026
performance via measures of accuracy and recall, following stan-
dard practice in ML approaches (James et al. 2013). Accuracy
measures the proportion of correct predictions from an algorithm
(both true positives and true negatives) over all cases. Although
accuracy provides a general performance indicator, recall focuses
on how well the model captures positive cases, which is partic-
ularly relevant because most of the contract text does not con-
tain product description language. We adjusted the algorithms'
hyperparameters to improve performance (Arnold et al. 2024)
and report the specific adjustment on GitHub.2 After the sixth
round, we selected the best-­performing algorithm and applied it
to generate product description language from the contract text
for all 2774 contracts.
2.4   |   Step 4: Contract Manager TC Survey
We surveyed 1061 government contract managers (549 re-
sponses, response rate = 51.7%) for their estimates of two TC
characteristics—asset specificity and measurability—for the 60
FIGURE 1    |    Research procedures and methods.


## Page 9

Public Administration Review, 2026
207
(58) CPV codes. The contract manager survey used a scale of 1–5
for both TC measures, and for the 58 products, the mean score
and standard deviation were 2.64 and 0.45 for measurability and
2.41 and 0.49 for asset specificity. The survey procedures are de-
scribed in full detail in (Casady et al. 2023).
2.5   |   Step 5: Training and Assessing TC Measure
Algorithm
We trained four ML algorithms to generate TC measures using
the survey TC measures for the 40 CPV code training dataset,
with product description contract text identified by the ML al-
gorithm from Step 3. The algorithms used the training dataset to
“learn” how to “predict” the TC measures. To assess model per-
formance, we used standard evaluation metrics, including mean
squared error (MSE), mean absolute error (MAE), and R-­squared
(James et al. 2023). To find the best version of each algorithm, we
adjusted the hyperparameters of each kernel, such as the kernel
type for the support vector machine and the learning rate and
batch size for the neural network. Specific experiments with the
hyperparameter adjustments can be found on GitHub2. We se-
lected the best-­performing versions of these four algorithms and
applied them to generate out-­of-­sample TC measures in the 18
CPV code test dataset using contract description text from 389
contracts. We identified the best-­performing algorithm by com-
paring the difference between the ML TC measurements and
survey TC measurements in the training dataset against the dif-
ference between the ML TC measurements and the survey TC
measurements in the test dataset.
2.6   |   Step 6: Using ML Algorithm to Create New
TC Measures
Finally, we used the best-­performing algorithm for identifying
product description language and the best-­performing algo-
rithm for generating TC measures to produce TC measures from
contract text for the remaining 118 CPV codes (1034 contracts)
in our dataset.
3   |   Results
We first report the two TC measures (asset specificity and measur-
ability) for the 58 CPV codes used to develop and assess the ML
algorithms. We then present results assessing the ML algorithms
by comparing their TC measures against the TC measures from
the manager survey. We find that the ML algorithms produced TC
measures that are very similar to the TC measures from the con-
tract manager survey. Finally, we present the TC measures gen-
erated by the ML algorithms for the remaining 118 CPV codes.
3.1   |   Assessing ML Algorithm Generated TC
Measures Against Contract Manager Survey TC
Measures
Table  3 reports measurability and asset specificity TC mea-
sures generated by the ML algorithms and the contract man-
agers for the 40 CPV codes. The TC measurements produced
by the ML algorithms are very similar to the contract manager
survey TC measures. For these 40 products, the average differ-
ence between the contract manager survey and ML-­generated
measures for measurability and asset specificity is −0.02 and
0.03, respectively. A two one-­sided test (TOST) for equivalence
suggests that the manager survey and ML measures are sta-
tistically equivalent at a 95% confidence level within an inter-
val of ±0.05 for measurability and ±0.12 for asset specificity.
For a sense of scale, recall that the contract manager survey
used a scale of 1–5 for both TC measures and had a respective
mean scores and standard deviations of 2.64 and 0.45 for mea-
surability and 2.41 and 0.49 for asset specificity. These small
differences suggest that the ML algorithm performed well
in producing TC measures that mimic the contract manager
survey TC measures. Nonetheless, these small differences are
not sufficient evidence for the validity of our measurement ap-
proach given that this is a within-­sample prediction: The con-
tract manager TC measures were part of the data used to train
the ML algorithms.
Table 4 reports measurability and asset specificity measures from
the manager survey and ML-­generated measures, thus summa-
rizing the out-­of-­sample test for the 18 CPV codes that were not
part of the data used to train the ML algorithms. The average
differences between the manager survey and ML-­generated
measures are slightly larger for the 18 out-­of-­sample CPV codes
than for the 40 within-­sample CPV codes: 0.09 for measurabil-
ity and −0.07 for asset specificity. Unsurprisingly, the test for
equivalence suggests that the ML algorithm performed better in
predicting the manager survey measures in the within-­sample
prediction for the 40 products than in the out-­of-­sample predic-
tion for the 18 products. For these 18 products, the manager sur-
vey and ML measures are equivalent at a 95% confidence level
within an interval of ±0.25 for measurability (around half a stan-
dard deviation) and ±0.33 for asset specificity (around two-­thirds
of a standard deviation). These results suggest the ML algorithm
performed satisfactorily in producing TC measures that mimic
the contract manager survey, even for CPV codes that were not
part of the data used to train the ML algorithms, indicating the
algorithms' efficacy in making out-­of-­sample TC estimates when
using only contract text data.
Beyond the statistical tests, the data reported in Table 4 sug-
gest that the ML algorithm produced substantively mean-
ingful TC measures. The ML algorithms indicate that
information technology products and social services such as
job training, mentoring, and home services for the elderly are
the most difficult to measure CPV codes. The ML algorithms
also indicate that the most asset-­specific CPV codes tend to be
in areas where only the government makes purchases, such as
fire prevention and emergency services and public transport.
Meanwhile, the ML algorithm identified easy-­to-­measure
and nonasset-­specific CPV codes in areas that tend to have
commodities that are widely sold, such as office and clean-
ing supplies. This pattern is similar to the TC measures for
products listed in scholarly studies drawing on the ICMA data
(Brown and Potoski  2003b; Hefetz and Warner  2012; Levin
and Tadelis 2010). Taken together, these results suggest that
the ML algorithms produced TC measures that approximate
the manager survey measures both in the in-­sample and out-­
of-­sample predictions.


## Page 10

208
Public Administration Review, 2026
TABLE 3    |    Manager survey and ML generated transaction cost measures: 40 CPV codes in training data.
Product name
Measurability
Asset specificity
Manager
survey
ML
generated
Difference
Manager
survey
ML
generated
Difference
Job training programs
3.41
3.40
0.01
2.81
2.80
0.01
Maintenance of green areas, sports
facilities, and so forth
2.35
2.42
−0.07
2.21
2.25
−0.03
Office and school supplies
1.92
2.17
−0.26
1.71
2.27
−0.56
Special driving and referred driving
2.76
2.77
−0.01
2.86
2.84
0.02
Apparel, uniforms, and so forth
2.21
2.25
−0.04
2.40
2.39
0.01
Rodent control
2.54
2.54
0.00
1.97
1.97
0.00
Toys, sporting equipment, and
musical instruments
2.13
2.12
0.01
1.79
1.81
−0.02
Legal and accounting services
3.16
3.14
0.02
2.13
2.25
−0.12
Repair and maintenance of vehicles
2.81
2.87
−0.06
1.98
2.08
−0.10
Installation of sewerage, district
heating, and so forth
2.79
2.87
−0.08
2.67
2.43
0.24
Insurance services
2.86
2.83
0.03
2.41
2.40
0.01
Cleaning of work apparel
2.26
2.27
−0.01
2.35
2.34
0.01
Maintenance of streams
2.87
2.89
−0.02
2.59
2.46
0.13
Building and window cleaning
2.25
2.29
−0.03
1.82
1.88
−0.06
Banking and asset management
3.04
3.03
0.01
2.55
2.56
−0.01
Installation of internet and network
connections
2.30
2.30
0.01
2.40
2.59
−0.19
Fire prevention and emergency
services
2.81
2.90
−0.09
4.00
2.52
1.48
Waste containers
1.95
1.99
−0.04
2.33
2.35
−0.02
Solid waste disposal
2.81
2.81
0.00
2.70
2.60
0.10
Computers and tablets
2.07
2.08
−0.01
1.94
1.99
−0.05
Street cleaning and draining of
rainwater gullies
2.37
2.48
−0.11
2.24
2.36
−0.12
Coaching and mentoring programs,
including the employment area
3.72
3.48
0.25
2.60
2.51
0.09
Danish lessons for foreigners
3.41
3.43
−0.02
2.81
2.75
0.05
Signs, traffic control, and street
lighting
2.20
2.16
0.04
2.43
2.39
0.05
Tradesman services
3.05
3.01
0.05
1.90
2.13
−0.23
Maintenance of elevators and
ventilation systems
2.53
2.54
−0.01
2.49
2.45
0.04
Temporary staffing services
3.08
3.10
−0.02
2.67
2.61
0.06
Electronic systems for fire and
burglary prevention
2.72
2.74
−0.03
2.84
2.76
0.07
Heavy vehicles—busses, trucks,
vans
2.28
2.28
0.00
2.57
2.39
0.18
Fuel—gas, oil, wood pellets
2.32
2.34
−0.02
2.18
2.20
−0.02
(Continues)


## Page 11

Public Administration Review, 2026
209
3.2   |   TC Measures Generated From ML Algorithm
Having evaluated the ML algorithm for generating out-­of-­sample
TC measures using the products with survey TC measures, we
applied the trained ML algorithms to generate TC measures for
all the remaining 118 CPV codes purchased by Danish municipal
and county governments. Table 5 below presents TC measures
for the 118 remaining CPV codes. The full dataset for all products
will be made publicly available in an online data archive to fa-
cilitate further research in government contracting and contract
management using the TC theoretical constructs in applied set-
tings. The open data includes both the CPV codes and product
names, making it usable for research in the EU, where the CPV
codes can be directly linked to national contract datasets, and
in other countries where public authorities purchase the same
products and services.
4   |   Conclusion
The theory of TCs provides a framework for analyzing risk and ob-
stacles across a wide range of social interactions and contexts, and
nearly every social science field uses the framework as part of its
theoretical toolkit. In public management, the TC framework has
guided generations of research on topics such as inter-­organizational
relations (Bel and Mur 2009; Lubell et al. 2017), municipal gov-
ernance (Feiock 2009; Feiock et al. 2003; Zeemering 2008), and,
of course, government contract management (Bel et  al.  2010;
Malatesta and Smith 2011; Piatak and Jensen 2024). Within public
management and beyond, a persistent research challenge with the
TC framework has been deploying effective measurement strate-
gies in large sample settings. The limitations of the ICMA surveys
have been highlighted in the contracting literature (e.g., Lamothe
et al. 2018; Lamothe and Lamothe 2024), and researchers have not
yet developed TC measures for the larger, more reliable, and more
geographically comprehensive contracting datasets.
This article paves the way for advancing public sector contract-
ing research using TC theory by harnessing synergies between
advanced ML analytic methods and large contract text datasets
to develop new measures of core TC concepts. Drawing on the
TC framework (Coase 1988; Williamson 1979, 1985) and sub-
sequent applications in public management research (Brown
and Potoski 2003a, 2003b; Levin and Tadelis 2010; Hefetz and
Warner 2012), this article develops a new approach to produce
methodologically validated measures for measurability and
asset specificity. We present this method and show its effective-
ness in generating out-­of-­sample TC measures for goods and ser-
vices purchased by governments. The ML algorithm performed
well in producing TC measures that approximate the contract
manager survey TC measures, long considered the state-­of-­
the-­art measurement approach for TC concepts. We deploy the
method to contract text for 2774 purchases to produce measur-
ability and asset specificity measures for 176 products, all linked
via CPV code to the largest database on government purchasing
in the world.
The research presented here has some limitations that suggest
directions for future research. One limitation is that the survey
and contract text data come from a single EU country; even
Product name
Measurability
Asset specificity
Manager
survey
ML
generated
Difference
Manager
survey
ML
generated
Difference
Dental products—dentures and
other equipment
2.62
2.65
−0.03
2.74
2.69
0.06
Cafeteria and catering
2.67
2.69
−0.02
2.52
2.51
0.01
IT consultancy and program
development
3.41
3.43
−0.02
3.04
2.98
0.06
Furniture and fixtures—office and
school furniture
2.12
2.13
−0.01
1.83
1.86
−0.03
Winter services—snow plowing/
sanding
2.57
2.57
0.00
2.48
2.45
0.02
Light vehicles—cars, mini busses,
and so forth
2.25
2.44
−0.19
2.05
2.32
−0.27
Maintenance of streetlights, signs,
and lane markings
2.52
2.52
0.00
2.65
2.56
0.09
Turnkey and individual trade
contracts in construction
3.29
3.13
0.16
2.53
2.42
0.11
Cleaning supplies, garbage bags,
and so forth
2.02
2.05
−0.03
1.65
1.67
−0.02
Engineering and architect
consultancy
3.32
3.34
−0.02
2.45
2.46
−0.01
Average
2.64
2.66
−0.02
2.41
2.38
0.03
TABLE 3    |    (Continued)


## Page 12

210
Public Administration Review, 2026
product-­level TC characteristics may differ across countries. A
product's asset specificity may be different in one country than
another because of the nature of economic circumstances. To
facilitate future research, we make publicly available all meth-
ods and codebooks to facilitate replication in other countries,
potentially leading to a series of public datasets that can facil-
itate comparative contracting research across diverse settings.
Another potential limitation is that the contract text may not
provide full information on products' TC characteristics because
contracts are incomplete (Frydlinger and Hart 2023; Hart and
Moore 1999), and what is missing from the contract text may be
correlated with TC factors. Future research may build on our
approach to investigate these potential limitations.
Future public management and contracting research can build
on this article along several dimensions. The new TC measures
enable researchers to evaluate core theoretical concepts for a
broad range of products, across national, regional, and local lev-
els, and in different economic, regulatory, and political contexts.
The CPV codes integrate our TC measures with the EU's cen-
tral contract database, covering government purchasing among
all 27 member countries. For applications beyond the EU, our
results provide product names for a broad range of products, ser-
vices, and public works commonly purchased by governments,
such as office supplies, cleaning services, street lighting, school
bus transportation, building renovation, and information tech-
nology systems. Scholars studying government contracting in
TABLE 4    |    Manager survey and ML generated transaction cost measures: 18 CPV codes in testing data.
Product name
Measurability
Asset specificity
Manager
survey
ML
generated
Difference
Manager
survey
ML
generated
Difference
Interpreting services
3.29
2.73
0.56
2.83
2.45
0.38
Coffee and tea
2.12
2.01
0.11
1.70
2.15
−0.45
Home services for the elderly
3.45
3.10
0.35
2.96
2.63
0.33
Medical products and materials
2.49
2.54
−0.05
2.72
2.63
0.09
Payroll systems
3.02
2.46
0.56
3.77
2.76
1.01
Residential solid waste
collection
2.29
2.67
−0.38
2.74
2.61
0.14
Undertaker and funeral
services
2.66
2.33
0.33
1.97
2.37
−0.40
Building and construction
material
2.62
2.70
−0.08
2.27
2.38
−0.11
Operation of public busses—
public transit
2.56
3.01
−0.45
2.99
2.80
0.19
Gifts and rewards
2.73
2.17
0.56
1.31
2.30
−0.99
Operation and maintenance of
fire engineering facilities
2.74
2.81
−0.06
2.72
2.29
0.43
Catering center equipment and
domestic appliances
2.03
1.98
0.05
1.98
2.13
−0.15
Indoor lighting—lamps and
light bulbs
1.98
2.03
−0.04
1.74
2.54
−0.80
Emergency call devices,
burglary protection, and fire
extinguishing materials
2.57
2.30
0.27
2.72
2.33
0.38
Miscellaneous food items
2.54
2.41
0.12
2.20
2.28
−0.08
Personal care products and
infant care
2.25
2.37
−0.13
1.74
2.51
−0.77
Management training and
professional development
3.39
3.58
−0.19
2.30
2.84
−0.54
Medical equipment and
products
2.68
2.48
0.20
2.71
2.58
0.13
Average
2.63
2.54
0.09
2.41
2.48
−0.07


## Page 13

Public Administration Review, 2026
211
TABLE 5    |    TC measures for 118 CPV codes generated by ML algorithms from contract text.
CPV code
Product name
Measurability
Asset specificity
090
Other petroleum products, fuel, electricity, and other sources of energy
2.85
2.28
093
District heating
2.74
2.3
140
Chemical and fertilizer minerals
2.28
2.28
142
Gravel, sand, crushed stone, and aggregates
2.01
2.25
146
Slag, dross, ferrous waste, and scrap
2.31
2.26
158
Dietetic products
2.32
2.29
159
Beverages, tobacco, and related products
2.44
2.28
160
Wheeled loaders
2.94
2.32
189
Goods-­packing sacks
2.05
2.33
190
Leather and textile fabrics, plastic, and rubber materials
2.38
1.95
192
Linen
2.82
1.96
220
Printed matter and related products
2.6
2.31
224
Trade-­advertising material, commercial catalogues, and manuals
2.38
2.31
229
Miscellaneous printed matter
2.57
2.28
240
Other chemical products
2.29
2.3
241
Gases
2.23
2.34
243
Basic inorganic and organic chemicals
2.02
2.34
245
Primary form of vinyl polymers
2.28
2.29
249
Fine and various chemical products
2.13
2.33
300
Office and computing machinery, equipment and
supplies except furniture and software packages
2.24
2.17
311
Chargers
3.19
2.58
312
Electricity distribution and control apparatus
2.39
2.54
313
Insulated wire and cable
2.55
2.54
317
Electronic, electromechanical, and electrotechnical supplies
3.12
2.55
320
Telecommunication and networks
2.63
2.49
322
Telecommunications equipment and supplies
2.33
2.45
323
Microphones and loudspeakers
2.12
2.48
324
Networks
2.94
2.43
325
Telecommunications system
2.67
2.39
331
Medical equipment
3.06
2.69
336
Pharmaceutical products
2.77
2.5
340
Other transport equipment and auxiliary products for transportation
2.91
2.3
341
Motor vehicles
2.84
2.35
342
Vehicle bodies, trailers, or semi-­trailers
1.69
1.84
344
Motorcycles, bicycles, and sidecars
2.13
2.04
346
Railway and tramway locomotives, and rolling stock and associated parts
2.29
2.3
349
Miscellaneous transport equipment, and spare parts
2.57
2.43
(Continues)


## Page 14

212
Public Administration Review, 2026
CPV code
Product name
Measurability
Asset specificity
350
Emergency and security equipment
2.58
2.35
378
Handicraft and art supplies
2.84
1.93
380
Other laboratory, optical, and precision equipment (excl. glasses)
2.74
2.18
382
Geological and geophysical instruments
2.62
2.15
384
Instruments for checking physical characteristics
2.84
2.05
385
Checking and testing apparatus
2.94
2.19
389
Polymerase chain reaction (PCR) equipment
2.83
2.08
390
Furniture (incl. office furniture), furnishings, domestic
appliances (excl. lighting), and cleaning products
2.84
2.16
393
Catering equipment
2.87
2.24
398
Cleaning and polishing products
2.79
2.08
420
Other industrial machinery
2.79
2.46
421
Machinery for the production and use of mechanical
power, including pumps and compressors
2.85
2.43
423
Waste incinerators
2.71
2.43
424
Lifting and handling equipment and parts
3.21
2.47
425
Cooling and ventilation equipment
2.85
2.5
429
Miscellaneous general and special-­purpose machinery
2.42
2.6
430
Machinery for mining, quarrying, construction equipment
1.97
2.43
432
Earthmoving and excavating machinery, and associated parts
2.62
2.43
434
Mineral-­processing machinery
2.57
2.42
440
Other construction structures and materials; auxiliary
products for construction (excepts electric apparatus)
3.16
2.44
443
Cable, wire, and related products
2.49
2.3
444
Goods used in construction
2.54
2.38
445
Tools, locks, keys, hinges, fasteners, chain, and springs
2.88
2.37
446
Tanks, reservoirs, containers, and pressure vessels
3.06
2.4
450
Other construction work
2.80
2.31
451
Site preparation work
3.16
2.37
452
Works for complete or part construction and civil engineering work
2.75
2.42
480
Other software package and information systems
3.17
2.63
481
Medical software package
3.34
2.49
482
Internet and intranet software package
1.66
2.06
489
Miscellaneous software package and computer systems
3.22
2.5
503
Repair, maintenance and associated services
related to personal computers, office equipment,
telecommunications, and audio–visual equipment
3.06
2.36
505
Repair and maintenance services for pumps, valves,
taps and metal containers, and machinery
3.10
2.25
510
Other installation services (except software)
2.76
2.41
(Continues)
TABLE 5    |    (Continued)


## Page 15

Public Administration Review, 2026
213
CPV code
Product name
Measurability
Asset specificity
511
Installation services of electrical and mechanical equipment
2.38
2.34
550
Other canteen and catering services
2.97
2.4
553
Cafeteria services
2.53
2.43
601
Taxi services
2.96
2.88
602
Railway transport services
2.57
2.47
604
Air transport services
2.33
2.27
631
Cargo handling and storage services
2.84
2.37
637
Support services for land transport
2.85
2.49
640
Other telecommunications services
2.62
2.69
641
Post and courier services
2.67
2.44
642
Telecommunications services
2.59
2.5
650
Other electricity distribution
2.38
2.48
653
Electricity distribution
2.40
2.47
654
Other sources of energy supplies and distribution
2.50
2.46
700
Real estate services
2.52
2.43
718
Consulting services for water supply and waste consultancy
2.49
2.69
719
Laboratory services
2.41
2.44
723
Data services
2.29
2.74
726
Computer support and consultancy services
2.48
2.79
750
Other administration, defense and social security services
2.52
2.45
751
Administration services
2.59
2.12
752
Provision of services to the community
2.67
2.65
771
Composting services
2.40
2.36
772
Forestry services
2.44
2.34
790
Other business services: Law, marketing, consulting,
recruitment, printing, and security
2.56
2.24
793
Market and economic research; polling and statistics
2.33
2.43
794
Business and management consultancy and related services
2.37
2.28
797
Investigation and security services
2.46
2.44
798
Printing and related services
2.59
2.42
799
Miscellaneous business and business-­related services
2.54
2.37
800
Other education and training services
2.39
2.74
801
Primary education services
2.41
2.63
805
Training services
2.47
2.78
850
Other health and social work services
2.29
2.69
851
Health services
2.40
2.78
900
Other sewage, refuse, cleaning, and environmental services
2.28
2.45
904
Sewage services
2.31
2.24
(Continues)
TABLE 5    |    (Continued)


## Page 16

214
Public Administration Review, 2026
the US, Brazil, China, or elsewhere may find value in the data
and measurement approaches presented here. For scholars, our
contribution can aid research in the many literatures that apply
TC concepts to social interaction, particularly public manage-
ment topics such as inter-­organizational collaboration (Elston
et  al.  2023; Wiechman et  al.  2024), policy networks (Lubell
et  al.  2017), local governance (Agranoff  2014; Feiock  2009),
and public sector performance (Walker and Andrews  2015).
Moreover, our analytic approach may be useful for studying addi-
tional types of TCs, such as market competitiveness and property
rights delineation.
Our article also offers guidance for contract management prac-
tice. Government contract managers can use our TC measures
to categorize purchases and identify the nature and source of
contract risks. For relatively simple products—products with
low asset specificity and measurement difficulty—contract
managers can devote relatively few contract management re-
sources, knowing that quality deficiencies will be relatively easy
to detect, and a poorly performing supplier can be relatively eas-
ily replaced. For more complex products, those with high asset
specificity and measurement difficulty, contract managers may
refrain from contracting (i.e., by choosing in-­house production),
or if purchasing is necessary, they may deploy contract manage-
ment activities such as monitoring procedures (Anguelov 2020)
or market-­building activities (Girth et al. 2012) to reduce the risk
of quality shading and vendor lock-­in (Hart et al. 1997).
Conflicts of Interest
The authors declare no conflicts of interest.
Endnotes
1	Searching Google Scholar for “transaction costs” turns up 2,150,000
citations as of February 11, 2025.
2	GitHub-­link:
https://​github.​com/​Bjark​eLS/​Measu​ring-­​Trans​actio​n-­​
Costs​-­​in-­​Publi​c-­​Secto​r-­​Contr​actin​g-­​throu​gh-­​Machi​ne-­​Learn​ing-­​and-­​
Contr​act-­​Text/​blob/​main/​Measu​ring%​20Tra​nsact​ion%​20Cos​ts%​20in%​
20Pub​lic%​20Sec​tor%​20Con​tract​ing%​20thr​ough%​20Mac​hine%​20Lea​
rning%​20and%​20Con​tract%​20Text%​20%​20-­%​20Cod​ebook%​20.​ipynb​.
3	Hefetz and Warner (2012) and Levin and Tadelis (2010) also include
nontransaction cost variables such as citizen interest in the service
and competition in the marketplace. Although such factors are likely
to be quite relevant for contracting research and practice, they are
concepts that apply to the jurisdiction doing the purchasing rather
than the product or service being purchased, suggesting other mea-
surement approaches are better suited to capturing variability in these
factors.
4	Our preregistration with the Open Science Framework (https://​doi.​org/​
10.​17605/​OSF.​IO/​6FE9Z​) mentions 60 products divided into a training
set of 42 products and a testing set of 18 products. We followed the pre-
registered procedure, but two of the 42 products in the training set had
no corresponding contracts in the contract dataset. As a result, the pre-
registered procedure resulted in 40 products in the training set for our
analysis.
References
Agranoff, R. 2014. “Local Governments in Multilevel Systems:
Emergent Public Administration Challenges.” American Review of
Public Administration 44, no. 4_suppl: 47S–62S.
Amirkhanyan, A. A., and K. T. Lambright. 2017. Citizen Participation
in the Age of Contracting: When Service Delivery Trumps Democracy.
Routledge.
https://​doi.​org/​10.​4324/​97813​15146​577/​citiz​en-­​parti​cipat​
ion-­​age-­​contr​actin​g-­​anna-­​amirk​hanya​n-­​krist​ina-­​lambr​ight.
Anastasopoulos, L. J., and A. B. Whitford. 2019. “Machine Learning for
Public Administration Research, With Application to Organizational
Reputation.” Journal of Public Administration Research and Theory 29,
no. 3: 491–510.
Andrews, R., and T. Entwistle. 2010. “Does Cross-­Sectoral Partnership
Deliver? An Empirical Exploration of Public Service Effectiveness,
Efficiency, and Equity.” Journal of Public Administration Research and
Theory 20, no. 3: 679–701.
Anguelov, L. G. 2020. “Monitoring Arrangements for Outsourced Public
Services: The Importance of Service Characteristics for the Distribution
of Oversight Responsibilities.” International Public Management
Journal 23, no. 2: 252–275.
Arnold, C., L. Biedebach, A. Küpfer, and M. Neunhoeffer. 2024. “The
Role of Hyperparameters in Machine Learning Models and How to
Tune Them.” Political Science Research and Methods 12, no. 4: 841–848.
Bel, G., and M. Mur. 2009. “Intermunicipal Cooperation, Privatization
and Waste Management Costs: Evidence From Rural Municipalities.”
Waste Management 29, no. 10: 2772–2778.
CPV code
Product name
Measurability
Asset specificity
905
Refuse and waste-­related services
2.25
2.55
906
Cleaning and sanitation services in urban or
rural areas and related services
2.45
2.44
907
Environmental services
2.30
2.44
909
Cleaning and sanitation services
2.30
1.92
920
Recreational, cultural and sporting services
2.35
2.3
922
Television services
2.44
2.42
923
Entertainment services
2.32
2.28
925
Archive services
2.15
2.31
980
Other community, social, and personal services
2.24
2.28
983
Miscellaneous services
2.27
2.37
TABLE 5    |    (Continued)


## Page 17

Public Administration Review, 2026
215
Bel, G., X. Fageda, and M. E. Warner. 2010. “Is Private Production of
Public Services Cheaper Than Public Production? A Meta-­Regression
Analysis of Solid Waste and Water Services.” Journal of Policy Analysis
and Management 29, no. 3: 553–577.
Brown, T. L., and M. Potoski. 2003a. “Managing Contract Performance:
A Transaction Costs Approach.” Journal of Policy Analysis and
Management 22, no. 2: 275–297.
Brown, T. L., and M. Potoski. 2003b. “The Influence of Transactions
Costs on Municipal and County Government Choices of Alternative
Modes of Service Provision.” Journal of Public Administration Research
and Theory 13, no. 4: 441–468.
Brown, T. L., and M. Potoski. 2006. “Contracting for Management:
Assessing Management Capacity Under Alternative Service Delivery
Arrangements.” Journal of Policy Analysis and Management: The
Journal of the Association for Public Policy Analysis and Management
25, no. 2: 323–346.
Brown, T. L., M. Potoski, and D. M. Van Slyke. 2007. “Trust and Contract
Completeness in the Public Sector.” Local Government Studies 33, no. 4:
607–623.
Brunjes, B. M. 2020. “Competition and Federal Contractor
Performance.” Journal of Public Administration Research and Theory
30, no. 2: 202–219.
Casady, C. B., O. H. Petersen, and L. Brogaard. 2023. “Public Procurement
Failure: The Role of Transaction Costs and Government Capacity in
Procurement Cancellations.” Public Management Review: 1–28.
Coase, R. H. 1988. “The Nature of the Firm: Origin.” Journal of Law,
Economics, and Organization 4, no. 1: 3–17.
Coupet, J., and A. McWilliams. 2017. “Integrating Organizational
Economics and Resource Dependence Theory to Explain the Persistence
of Quasi Markets.” Administrative Sciences 7, no. 3: 29.
Dimand, A.-­M., A. S. Patrucco, E. Rodriguez-­Plesa, and A. M. Hiriscau.
2023. “Social Equity in Federal Contracting During Emergencies: A
Portfolio Management Perspective.” Public Administration Review 83,
no. 5: 1319–1338.
Elston, T., G. Bel, and H. Wang. 2023. “If It Ain't Broke, Don't Fix It:
When Collaborative Public Management Becomes Collaborative
Excess.” Public Administration Review 83, no. 6: 1737–1760.
Ernita Joaquin, M., and T. J. Greitens. 2012. “Contract Management
Capacity Breakdown? An Analysis of U.S. Local Governments.” Public
Administration Review 72, no. 6: 807–816.
Esteve, M., J. C. Garrido-­Rodríguez, A. Moore, C. Schuster, and J. L.
Zafra Gómez. 2024. “Assessing the Effects of User Accountability
in Contracting Out.” Journal of Public Administration Research and
Theory 34, no. 2: 211–223.
Feiock, R. C. 2009. “Metropolitan Governance and Institutional
Collective Action.” Urban Affairs Review 44, no. 3: 356–377.
Feiock, R. C., M. Jeong, and J. Kim. 2003. “Credible Commitment and
Council-­Manager Government: Implications for Policy Instrument
Choices.” Public Administration Review 63, no. 5: 616–625.
Fernandez, S. 2007. “What Works Best When Contracting for Services?
An Analysis of Contracting Performance at the Local Level in the US.”
Public Administration 85, no. 4: 1119–1141.
Ferris, J., and E. Graddy. 1986. “Contracting Out: For What? With
Whom?” Public Administration Review 46, no. 4: 332–344. https://​doi.​
org/​10.​2307/​976307.
Frydlinger, D., and O. Hart. 2023. “Overcoming Contractual
Incompleteness: The Role of Guiding Principles.” Journal of Law,
Economics, and Organization 40: ewac027.
Geyskens, I., J.-­B. E. M. Steenkamp, and N. Kumar. 2006. “Make,
Buy, or Ally: A Transaction Cost Theory Meta-­Analysis.” Academy of
Management Journal 49, no. 3: 519–543.
Girth, A. M., A. Hefetz, J. M. Johnston, and M. E. Warner. 2012.
“Outsourcing Public Service Delivery: Management Responses in
Noncompetitive Markets.” Public Administration Review 72, no. 6:
887–900.
Hart, O., A. Shleifer, and R. W. Vishny. 1997. “The Proper Scope of
Government: Theory and an Application to Prisons.” Quarterly Journal
of Economics 112, no. 4: 1127–1161.
Hart, O., and J. Moore. 1999. “Foundations of Incomplete Contracts.”
Review of Economic Studies 66, no. 1: 115–138.
Hasbrouck, J. 1993. “Assessing the Quality of a Security Market: A
New Approach to Transaction-­Cost Measurement.” Review of Financial
Studies 6, no. 1: 191–212.
Hefetz, A., and M. E. Warner. 2012. “Contracting or Public Delivery?
The Importance of Service, Market, and Management Characteristics.”
Journal of Public Administration Research and Theory 22, no. 2: 289–317.
James, G., D. Witten, T. Hastie, and R. Tibshirani. 2013. An Introduction
to Statistical Learning. Springer.
James, G., D. Witten, T. Hastie, R. Tibshirani, and J. Taylor. 2023.
An Introduction to Statistical Learning: With Applications in Python.
Springer.
Kang, S. C., R. Nesbit, and J. L. Brudney. 2022. “Local Government
Volunteer Use: A Resource Dependence and Transaction Costs
Explanation.” Public Administration Review 82, no. 5: 806–817.
Kim, Y. W., and T. L. Brown. 2012. “The Importance of Contract
Design.” Public Administration Review 72, no. 5: 687–696.
Lamothe, M., and S. Lamothe. 2012. “What Determines the Formal
Versus Relational Nature of Local Government Contracting?” Urban
Affairs Review 48, no. 3: 322–353.
Lamothe, M., S. Lamothe, and E. Bell. 2018. “Understanding Local
Service Delivery Arrangements: Are the ICMA ASD Data Reliable?”
Public Administration Review 78, no. 4: 613–625.
Lamothe, S., and M. Lamothe. 2016. “Service Shedding in Local
Governments: Why Do They Do It?” Journal of Public Administration
Research and Theory 26, no. 2: 359–374.
Lamothe, S., and M. Lamothe. 2024. “Toward a Better Understanding
of Local Service Provision: Implications for Studying the Determinants
of Production Choice.” Public Administration Review 84, no. 5: 904–917.
Lamothe, S., M. Lamothe, and R. C. Feiock. 2008. “Examining Local
Government Service Delivery Arrangements Over Time.” Urban Affairs
Review 44, no. 1: 27–56.
Levin, J., and S. Tadelis. 2010. “Contracting for Government Services:
Theory and Evidence From U.S. Cities.” Journal of Industrial Economics
58, no. 3: 507–541.
Lubell, M., J. M. Mewhirter, R. Berardo, and J. T. Scholz. 2017.
“Transaction Costs and the Perceived Effectiveness of Complex
Institutional Systems.” Public Administration Review 77, no. 5: 668–680.
Madsen, M. S. 2023. “Intergovernmental Cooperation and Joint Purchasing
Agreements: Do Governments Free-­Ride?” Public Administration Review
84, no. 4: 604–622. https://​doi.​org/​10.​1111/​puar.​13727​.
Malatesta, D., and C. R. Smith. 2011. “Resource Dependence,
Alternative Supply Sources, and the Design of Formal Contracts.”
Public Administration Review 71, no. 4: 608–617.
Malatesta, D., and C. Smith. 2014. “Designing Contracts for Complex
Services.” Public Administration 92, no. 3: 531–548.
Marvel, M. K., and H. P. Marvel. 2007. “Outsourcing Oversight: A
Comparison of Monitoring for In-­House and Contracted Services.”
Public Administration Review 67, no. 3: 521–530.
North, D. C. 1990. Institutions, Institutional Change and Economic
Performance. Cambridge University Press. https://​books.​google.​com/​
books?​hl=​en&​lr=​&​id=​oFnWb​TqgNP​YC&​oi=​fnd&​pg=​PA10&​dq=​


## Page 18

216
Public Administration Review, 2026
dougl​as+​north​+​1990+​insti​tutio​ns+​insti​tutio​nal+​chang​e&​ots=​s-­​
iqSaK​hQ9&​sig=​3zwxY​CzDMB​xqnv5​3gkev​trcw-­​eM.
North, D. C. 1991. “Institutions.” Journal of Economic Perspectives 5, no.
1: 97–112.
OECD. 2021. “Government at a Glance 2021, Paris: Organisation for
Economic Co-­Operation and Development.” https://​www.​oecd-­​ilibr​ary.​
org/​gover​nance/​gover​nment​-­​at-­​a-­​glanc​e-­​2021_​1c258​f55-­​en.
Ostrom, E. 1990. Governing the Commons: The Evolution of Institutions
for Collective Action. Cambridge university press.
Petersen, O. H., E. Baekkeskov, M. Potoski, and T. L. Brown. 2019.
“Measuring and Managing Ex Ante Transaction Costs in Public Sector
Contracting.” Public Administration Review 79, no. 5: 641–650.
Petersen, O. H., K. Houlberg, and L. R. Christensen. 2015. “Contracting
Out Local Services: A Tale of Technical and Social Services.” Public
Administration Review 75, no. 4: 560–570.
Piatak, J., and C. Jensen. 2024. “Public Values and Sector Service
Delivery Preferences: Public Preferences on Contracting From Simple
to Complex Human Services.” Public Administration Review 84, no. 5:
948–965. https://​doi.​org/​10.​1111/​puar.​13794​.
Ramírez De La Cruz, E. E., E. J. Grin, P. Sanabria-­Pulido, D. Cravacuore,
and A. Orellana. 2020. “The Transaction Costs of Government
Responses to the COVID -­19 Emergency in Latin America.” Public
Administration Review 80, no. 4: 683–695.
Schoute, M., T. Budding, and R. Gradus. 2018. “Municipalities'
Choices of Service Delivery Modes: The Influence of Service, Political,
Governance, and Financial Characteristics.” International Public
Management Journal 21, no. 4: 502–532.
Scott, R. J., and E. R. K. Merton. 2021. “When the Going Gets Tough,
the Goal-­Committed Get Going: Overcoming the Transaction Costs of
Inter-­Agency Collaborative Governance.” Public Management Review
23, no. 11: 1640–1663.
Scott, W. R. 1987. “The Adolescence of Institutional Theory.”
Administrative Science Quarterly 32, no. 4: 493–511. https://​doi.​org/​10.​
2307/​2392880.
Scott, W. R. 2004. “Reflections on a Half-­Century of Organizational
Sociology.” Annual Review of Sociology 30, no. 1: 1–21.
Stein, R. M. 1990. Urban Alternatives: Public and Private Markets in the
Provision of Local Services. University of Pittsburgh Press.
Stein, R. M. 1993. “Arranging City Services.” Journal of Public
Administration Research and Theory 3, no. 1: 66–92.
Tenders Electronic Daily. 2023. “What is TED?” https://​ted.​europa.​eu/​
TED/​main/​HomeP​age.​do.
Ulibarri, N. 2024. “An Analysis of Micro-­Scale Conflict in Collaborative
Governance.” Journal of Public Administration Research and Theory 34,
no. 2: 316–330.
Van Slyke, D. M. 2003. “The Mythology of Privatization in Contracting
for Social Services.” Public Administration Review 63, no. 3: 296–315.
Walker, R. M., and R. Andrews. 2015. “Local Government Management
and Performance: A Review of Evidence.” Journal of Public
Administration Research and Theory 25, no. 1: 101–133.
Wei, W., Z. Zhang, and K. Yang. 2022. “Local Institutions and Public
Service Outsourcing: Managerial Professionalism, Mayoral Strength,
and Electoral Rules.” Public Administration Review 82, no. 6: 1095–1123.
Wiechman, A., S. Alonso Vicario, and E. A. Koebele. 2024. “The Role
of Intermediate Collaborative Forums in Polycentric Environmental
Governance.” Journal of Public Administration Research and Theory 34,
no. 2: 196–210.
Williamson, O. E. 1979. “Transaction-­Cost Economics: The Governance
of Contractual Relations.” Journal of Law and Economics 22, no. 2:
233–261.
Williamson, O. E. 1981. “The Economics of Organization: The
Transaction Cost Approach.” American Journal of Sociology 87, no. 3:
548–577.
Williamson, O. E. 1985. The Economic Institutions of Capitalism. Free
Press.
Zeemering, E. S. 2008. “Governing Interlocal Cooperation: City
Council Interests and the Implications for Public Management.” Public
Administration Review 68, no. 4: 731–741.
Supporting Information
Additional supporting information can be found online in the
Supporting Information section.

