# Public Administration Review - 2025 - Gules‐Guctas - How Do Algorithmic Decision

## Page 1

Public Administration Review, 2026; 86:371–382
https://doi.org/10.1111/puar.70043
371
Public Administration Review
RESEARCH ARTICLE
OPEN ACCESS
How Do Algorithmic Decision-­Making Systems Used
in Public Benefits Determinations Fail? Insights From
Legal Challenges
Esra Gules-Guctas
John Glenn College of Public Affairs, The Ohio State University, Columbus, Ohio, USA
Correspondence: Esra Gules-­Guctas (gules-guctas.1@osu.edu)
Received: 15 July 2024  |  Revised: 11 September 2025  |  Accepted: 16 September 2025
Funding: This article is part of a project supported in part by grants from the American Political Science Association; the Russell Sage Foundation (Grant
#2202-­3710); and the Law and Science Dissertation Grant program funded by National Science Foundation Law and Science Program (SBE #2016661).
Keywords: administrative error | algorithmic decision-­making systems | algorithms
ABSTRACT
When algorithmic decision-­making systems fail to function as intended, they become conduits for administrative error and risk
producing arbitrary determinations through the very technologies meant to prevent them. Analysis of 71 federal and state court
dockets contesting algorithm-­based determinations in disability, unemployment, and nutrition assistance programs shows how
this risk manifests in practice. Findings show that deviations from legally prescribed outcomes occur when the translation of
statutory requirements into computational logic is compromised by flawed data, problematic design choices, or inherent system
limitations. These algorithmic administrative errors are neither isolated glitches nor purely technical problems; they constitute
a systemic governance problem that cuts across legal, organizational, and technical domains. Addressing them requires coordi-
nated oversight across all three areas, rather than reliance on post hoc troubleshooting.
Algorithmic decision-­making systems (ADS) now screen ap-
plicants, calculate benefits, and flag suspected fraud across a
growing range of public programs. The proliferation of ADS
in public-­sector decision-­making is accelerating the shift from
street and screen-­level to system-­level bureaucracy. Most ad-
ministrative tasks are now handled by algorithmic “decision
factories” running quietly on networks of servers, monitored by
system managers at their (Bovens and Zouridis 2002; Zouridis
et al. 2020). Even in hybrid decision-­making contexts, ADS de-
termine which cases are processed automatically and which are
flagged for further review (Larsson 2021).
Agencies embrace ADS to address enduring challenges in ad-
ministrative decision-­making. Public servants operate under
bounded rationality: limited information, time, and cognitive
capacity lead them to satisfice rather than optimize (Simon 1967).
In addition, street-­level discretion risks arbitrariness and incon-
sistency, and therefore requires managerial control (Jorna and
Wagenaar 2007). ADS are expected to mitigate both: by handling
far larger volumes of data than human capacity allows, and by
hard-­coding rules, they can reduce inconsistency and constrain
frontline (Kleinberg et al. 2018; Sunstein 2021; Coglianese and
Lai 2021).
The appeal of ADS thus rests on the promise of greater efficiency
and consistency, but this promise must be weighed against pub-
lic law mandates such as due process and accountability. Public
law scholars have long cautioned that when efficiency becomes
the dominant objective, it risks sidelining these obligations (Moe
and Gilmour 1995; Lynn and Laurence 2009). Today, these risks
This is an open access article under the terms of the Creative Commons Attribution-NonCommercial-NoDerivs License, which permits use and distribution in any
medium, provided the original work is properly cited, the use is non-commercial and no modifications or adaptations are made.
© 2025 The Author(s). Public Administration Review published by Wiley Periodicals LLC on behalf of American Society for Public Administration.


## Page 2

372
Public Administration Review, 2026
are heightened: the proliferation of ADS is resulting in decision-­
making processes that often defy scrutiny and accountability
(Busuioc 2021; Calo and Citron 2020).
Yet debates around ADS in government remain polarized be-
tween overly optimistic claims about transformative improve-
ments in public service delivery and dystopian warnings about
opaque, unaccountable algorithmic bureaucracy. Moving be-
yond these extremes requires understanding how decisions
made or assisted by ADS can go awry in real-­world implementa-
tion. The challenge is not only to ensure ex post accountability
after errors and problematic outcomes surface but also to pre-
vent them from arising in the first place. Because ADS do not
simply mechanize existing processes but also encode legal and
policy choices, maintaining fidelity to law requires more than ex
post review of questionable outputs.
Public administration scholars have highlighted the account-
ability concerns and the transformation of bureaucratic dis-
cretion associated with system-­level bureaucracy (Zouridis
et  al.  2020; Busuioc  2021). However, what remains underex-
plored is another by-­product of this transformation: a highly
scalable, difficult-­to-­detect form of administrative error that
this article terms algorithmic administrative errors. These errors
are systemic, unintended deviations from legally prescribed out-
comes that originate in data, design choices, or inherent system
limitations.
Understanding how such errors arise is crucial for ensuring
legal compliance. As Valle-­Cruz et  al.  (2024) emphasize, the
“dark side” of government algorithms often stems from “the lack
of understanding of how [an ADS] generates certain results,
bias, or errors” (Valle-­Cruz et al. 2024, 364). Although computer
science literature demonstrates that ADS are prone to errors and
do not always function as advertised (Deborah Raji et al. 2022),
public administration research has yet to fully grapple with how
these issues translate into administrative errors in practice.
To address this need, this article examines how ADS used in
public benefits determinations can fail. Central to this inquiry
are the following questions: How do algorithmic errors manifest
in public benefits determinations? What are the sources of errors
that lead to erroneous determinations? And what implications
might these errors have for the implementation of advanced AI
systems in public administration?
To answer these questions, this study employed a qualitative
multiple-­case design grounded in litigation records from 71
federal and state dockets that challenged algorithm-­based de-
terminations in disability benefits, unemployment insurance,
and nutrition assistance programs. Because litigation obliges
agencies to explain and defend their decision logic, court re-
cords document real-­world instances where algorithmic outputs
are credibly alleged to diverge from statutory criteria. Treating
each docket as a bounded case, the analysis traced how system
outputs contributed to contested decisions. This process yielded
a three-­part typology of error sources—data, design, and sys-
tem limitations—that structures the findings and underpins
the concept of algorithmic administrative error. The results
demonstrate that ADS designed to optimize decision-­making
can instead become conduits for administrative error, breaching
statutory mandates in ways that disparate-­impact analysis alone
cannot reveal.
1   |   Administrative Errors: From Street Level to
System Level
Administrative errors are defined as any deviation from an in-
tended action or outcome mandated by laws, rules, or proce-
dures (Bullock  2014). These errors burden both agencies and
the citizens they serve: agencies must devote scarce resources
to managing errors, while citizens may experience delayed or
denied access to legally entitled benefits (Eubanks 2018; Peeters
and Widlak  2023). Although automation is often expected to
reduce administrative errors, the empirical evidence is mixed.
Studies have found that automation can reduce certain types of
errors (Greer and Bullock 2018), but it has not eliminated dis-
parities in error rates across racial and ethnic groups (Compton
et al. 2023) and has even increased errors in programs with more
complex eligibility rules (Young et al. 2023).
These findings indicate that not all errors can be avoided
through automation. Recent studies illustrate the consequences
when systems err: citizens have been wrongly labeled as high-­
risk offenders (Angwin et al. 2016), falsely flagged for child ne-
glect (Eubanks 2018), and accused of welfare fraud (Peeters and
Widlak 2023). In each instance, the underlying issue was not the
carelessness or malfeasance of frontline caseworkers, but rather
errors stemming from how algorithms were designed, trained,
or implemented.
Taken together, this evidence underscores the need to under-
stand how system-­level errors arise. Yet that question remains
underexplored. Existing research often focuses on aggregate
error rates (Greer and Bullock 2018; Compton et al. 2023) or
on downstream harms to citizens (Eubanks 2018; Peeters and
Widlak 2023). Although aggregate rates are valuable indica-
tors of organizational performance, they reveal little about
the mechanisms that generate errors. Consequence-­oriented
studies are crucial for showing how system failures translate
into real-­world harms, and they do uncover particular failure
Summary
•	 Public administrators must look beyond technical per-
formance alone to ensure statutory compliance before
deployment.
•	 Encoding eligibility criteria or program requirements
is as much a matter of statutory interpretation as it is
of systems engineering.
•	 Data-­science metrics may label a model's output “ac-
curate,” yet if that output contravenes statutory crite-
ria, agencies still bear legal liability.
•	 The very features that make advanced AI systems at-
tractive—the capacity to process large, noisy datasets
and to self-­learn—also heighten their susceptibility to
data-­quality problems and design flaws.
•	 A single system-­level error can replicate instantly
across thousands of benefit determinations.


## Page 3

373
Public Administration Review, 2026
modes, such as algorithmic bias (Eubanks  2018). However,
they treat those errors mainly as explanatory variables and
therefore reveal only part of the pathways through which
system-­level errors may emerge. Consequently, our under-
standing of the spectrum of potential errors remains limited.
Without such understanding, administrators cannot reliably
assess whether system outputs comply with statutory require-
ments or policy goals.
As ADS proliferate, administrative errors now include system-­
level failures. When public benefit determinations were made
entirely by street-­level bureaucrats, most errors could be traced
to a caseworker who misread an earnings statement, applied the
wrong rule, or overlooked missing paperwork. Although public
administrators have long dealt with such errors, system errors
are categorically different: they occur differently, less predict-
ably, and are more difficult to audit and detect. Meaningful
oversight now requires that administrators understand how
ADS operate and produce their results (Green  2022). Public
administrators, tasked with overseeing ADS, stand at the fore-
front of this challenge. They must supervise black-­box systems
they did not design and contend with errors that are systemic,
opaque, and embedded within complex layers of code. Yet, re-
search shows that agencies often have little to no input into the
design of these systems, or even knowledge about how well sys-
tem design aligns with agency goals or the metrics by which suc-
cess should be judged (Brauneis and Goodman 2018).
Scholars have urged greater attention to the systems shaping
public decision-­making, rather than focusing on a steadily de-
clining cadre of street-­level officials with discretion (Zouridis
et al. 2020). Yet, despite the proliferation of ADS, systematic ev-
idence on how these systems behave in practice is remarkably
thin (Eubanks 2018; Compton et al. 2023; Young et al. 2023).
Multiple literature reviews conclude that the field needs more
research grounded in real-­world implementation (Mergel
et al. 2023; Roehl and Hansen 2024; Madan and Ashok 2023;
Wirtz et al. 2021). The scarcity of such evidence has led much
of the inquiry to remain at a high level of abstraction, result-
ing in broad mappings of normative concerns. Consequently, a
persistent knowledge gap exists between the current state of im-
plementation and the skills and competencies public managers
need to leverage these technologies (Mergel et al. 2023).
Although scholars continue to call for practitioner-­oriented
research (Pencheva et al. 2020), the majority of existing work
centers on the government's role as a regulator rather than a
user of algorithms (Madan and Ashok 2023). The literature is
dominated by forward-­looking work that maps future risks or
devises ex-­ante classifications of high-­risk systems. Such frame-
works are invaluable for agenda-­setting, yet they reveal little
about how risks unfold in day-­to-­day operations. At the same
time, attempts to translate broad responsible AI principles into
concrete guidance remain stalled by conceptual ambiguity and
cross-­disciplinary silos (Morley et al. 2020).
2   |   Algorithmic Administrative Errors
Existing research tends to approach system failures in isola-
tion, documenting aggregate error rates and disparate outcomes
through single-­system case studies. This piecemeal view limits
the field's ability to capture the full spectrum of errors that can
affect administrative decisions. It also leaves administrators
without the guidance they need to monitor and prevent those
errors.
Although concepts derived from computer science such as “AI
fairness,” “trustworthiness,” or “responsible AI” have influ-
enced regulatory approaches (Raso  2021), these terms often
conflate public and private-­sector AI, despite their very differ-
ent characteristics, mandates, and constraints. They are also too
indeterminate for day-­to-­day practice and are interpreted incon-
sistently across domains. Even the words ‘artificial’ and ‘intelli-
gence’ are contested for their rigidity and usefulness (Dwivedi
et al. 2021). As Dwivedi et al. (2021) suggest, an “institutional
hybrid” vocabulary that is sensitive to both context and disci-
pline remains necessary.
To answer this need, this article introduces the concept of al-
gorithmic administrative error (AAE) to denote systemic, unin-
tended deviations from legally mandated outcomes that originate
in an algorithmic decision-­making system's data, design choices,
or system limitations. This concept builds on Bullock's (2014)
outcome-­based definition of administrative error but extends it
to the system level. Not every technical malfunction qualifies
as an AAE. What distinguishes an AAE from a transient glitch
is that the system continues to function and produce outputs
that appear plausible, allowing errors to propagate undetected
until an external audit finally brings them to light. Data-­science
metrics may label a model output “accurate” or “fair,” yet if that
output contravenes statutory criteria, agencies still bear legal li-
ability. Framing such failures as AAEs foregrounds their public-­
law stakes and clarifies why administrators must look beyond
technical performance.
Although AI applications in government now range from
rule-­based to advanced language models, all share one salient
property: they execute a finite sequence of machine-­readable
instructions, that is, an algorithm (Russell and Norvig  2021).
As such, the concept of algorithmic administrative error is suf-
ficiently broad to encompass both rule-­based systems and ad-
vanced AI models. Algorithmic decision-­making is the product
not only of code but of choices about data inputs, feature selec-
tion, and operational logic. Consequently, AAE can originate
in any of those layers. In sum, the concept of AAE provides a
systems-­level lens for studying how legally mandated outcomes
can be derailed by data flaws, design choices, or inherent system
limits. The next section explains the study's research design and
methods, detailing how AAEs were traced empirically through
analysis of litigation records.
3   |   Research Design
This study adopted a qualitative multiple case study design in
which each litigated docket served as an analytic case. This ap-
proach is well-­suited to explaining complex processes while re-
taining contextual detail (Yin 2018; Stake 2013; Stewart 2012).
A central challenge in studying ADS in public administration
is access to data. The data on internal operations of public agen-
cies are typically not available (Compton et al. 2023), and the


## Page 4

374
Public Administration Review, 2026
underlying data and design choices are generally not open to in-
spection (Busuioc 2021). Litigation, however, obliges agencies to
disclose detailed records and justifications, giving researchers a
rare window into how errors emerge in practice.
3.1   |   Data
The dataset comprises several hundred court documents drawn
from 71 docket entries in U.S. federal and state courts that con-
test determinations in disability benefits, unemployment in-
surance (UI), and Supplemental Nutrition Assistance Program
(SNAP) determinations (see Appendix S1 for the full list of court
cases analyzed). These programs were selected because they ex-
emplify ‘large decision factories’ that handle thousands of in-
dividual cases on the basis of a legal framework (Bovens and
Zouridis 2002). In disability benefits, algorithmic systems such
as RUGs and interRAI have been widely adopted to structure
needs assessments and allocate care resources. In UI and SNAP,
many states have recently implemented algorithmic fraud-­
detection and eligibility screening systems to identify over-
payments, potential fraud, or ineligibility (Brown et al. 2020).
Including all three programs enabled examination of error types
across distinct algorithmic functions.
A purposive, information-­rich sampling strategy was employed
(Patton 2014), systematically targeting legal challenges in which
an ADS played a material role in the contested benefit deter-
mination and where the available court record was sufficiently
detailed to enable in-­depth analysis of error mechanisms. This
approach prioritizes information-­rich cases over statistical rep-
resentativeness (Yin  2018; Stewart  2012) and aligns with the
study's goal of developing a grounded understanding of the
types and sources of error rather than quantifying or comparing
error rates across programs.
Case identification, document retrieval, and coding were car-
ried out over a two-­year period (2021–2023). Case identification
followed a triangulated search protocol, combining Boolean
queries in LexisNexis and Westlaw databases, docket-­alert mon-
itoring, and citation tracing. Program-­specific terms (“disability
benefits,” “unemployment insurance,” “SNAP”) were paired
with ADS-­related keywords (‘algorithm,’ “model,” “scoring sys-
tem,” “automated tool”) and terms indicative of administrative
error (‘erroneous,’ “arbitrary,” “inaccurate”). Known system
names (e.g., InterRAI, CBMS, CalSAWS, RUG-­IV) were also in-
cluded to ensure comprehensive coverage. This process yielded
1284 docket entries, which were systematically screened for el-
igibility. Because Lexis and Westlaw search results begin with
a summary or opinion, agency reliance on algorithmic output
was not always explicit and required close examination of com-
plaints, exhibits, or references to system names in the pleadings.
A docket was retained only when the record showed that a sys-
tem had materially influenced the disputed eligibility or benefit
amount. Dockets satisfying this screen were then assessed for
completeness. Cases were retained only when the file contained
sufficient accessible documents including complaints, motions,
opinions, and, where available, deposition transcripts or expert
reports. Lawsuits were excluded when ADS involvement could
not be confirmed, dockets were sealed or incomplete, or key doc-
uments were unavailable.
Seventy-­one dockets filed between 2005 and 2022 satisfied these
criteria. Of these, 47 challenge disability-­benefit determinations,
five contest unemployment benefit determinations, and eight in-
volve SNAP decisions. Eleven of the dockets are appeals arising
from nine trial-­level suits; all were retained because appellate
dockets contribute additional documentation and context. The
predominance of disability benefits cases in the dataset likely re-
flects this program's earlier and broader adoption of automated
assessment tools (Glaze et al. 2021), as well as SSDI's complex,
appeal-­intensive adjudication process and strong financial in-
centives for legal representation—contrasting with near-­zero
incentives and typically only legal aid involvement in other pro-
grams (Hoynes et al. 2022). Because the study seeks explanatory
depth rather than prevalence estimates, statistical representa-
tiveness was not a design objective.
For each lawsuit, all retrieved court documents were down-
loaded and organized in NVivo, including complaints, answers,
motions, judicial opinions, interlocutory and final appeals, and,
where available, materials produced during discovery such as
deposition transcripts, expert reports, or internal agency records
filed as exhibits. Because discovery materials are not always
public unless filed in support of motions or introduced at trial,
only those discovery documents that entered the public court
record were included.
3.2   |   Methods
Consistent with the exploratory aims of the study, coding was
conducted inductively, allowing new forms of error to emerge
as analysis progressed. Documents within each docket were
coded for any passage describing how an algorithmic system
contributed to a contested determination. Initial open coding
yielded descriptive labels (e.g., “outdated data,” “irrebuttable
presumption,” “missing variable”), which were iteratively re-
fined through constant comparison both within and across
cases: incident-­to-­incident within a docket, incident-­to-­category
as new data accumulated, and category-­to-­category to delineate
analytic boundaries. Some error mechanisms appeared in mul-
tiple cases, while others were unique but remained analytically
important for illustrating types of failure modes. The priority
throughout was to provide detailed, grounded accounts of how
ADS used in public-­benefit determinations fail.
As coding progressed, a typology was developed to classify the
mechanisms of algorithmic error into three primary categories:
data quality, design flaws, and system limitations. Data quality
refers to flaws arising from the integrity of input data, such as
outdated or unrepresentative data, or failures in data integration
between systems. Design flaws encompass errors in algorithmic
design or coding, such as the omission of essential variables,
exclusion of legally relevant factors, and irrebuttable presump-
tions. System limitations capture errors stemming from inher-
ent computational constraints, such as the inability to discern
context or conflation of correlation and causation. This typology
provided the conceptual scaffolding for both cross-­case analysis
and the thematic organization of findings.
To minimize subjectivity, detailed analytic memos were main-
tained throughout to document coding decisions, track the


## Page 5

375
Public Administration Review, 2026
evolution of the coding scheme, and record the rationale for code
assignment. The researcher is a former practicing attorney with
litigation experience, which informed the reading and interpre-
tation of court documents. To minimize the risk of bias influenc-
ing analytic decisions, reflexive memos were also maintained
throughout the research process to bracket prior assumptions
and document the rationale for including or excluding cases.
Given space constraints, a subset of exemplar cases was selected
for thick description after coding was complete. Consistent
with the study's purposive, information-­rich sampling strat-
egy (Patton 2014, 264) and Stake's guidance to focus on cases
offering the greatest opportunity to learn (Stake 2013), case se-
lection followed a two-­stage procedure: First, within-­case rich-
ness was assessed by documentary detail, such as the presence
of discovery-­based exhibits; second, among cases illustrating
the same mechanism, those offering the clearest documentary
trace of how the error arose were prioritized. This approach was
used to illustrate both common and analytically distinctive error
mechanisms.
3.3   |   Limitations and Transferability
This study is bounded by litigated cases with accessible records;
matters resolved administratively and dockets in which ADS in-
volvement could not be verified were excluded. The sample is
therefore purposive and information-­rich, not statistically repre-
sentative, and findings illuminate how algorithmic errors arise
rather than how often they occur. Confirming ADS use often
required close examination of supporting documents, a step that
may have inadvertently excluded sparsely documented dockets
despite efforts to ensure breadth.
As noted above, conclusions about disability-­benefit errors rest
on a larger set of dockets, whereas observations for unemploy-
ment insurance and SNAP derive from fewer dockets and should
be interpreted cautiously with respect to program-­specific nu-
ances. Coding and selection of exemplar cases were guided by
conceptual relevance, clarity, and richness, which, while ap-
propriate for qualitative inquiry, inevitably reflect researcher
judgment. Reflexive and analytic memos were maintained
throughout to mitigate bias and provide a transparent audit
trail. Although statistical generalizability is not claimed, the
error mechanisms identified are likely relevant to other contexts
where ADS are used for public benefits adjudication. Thick de-
scriptions of context are provided to allow readers to assess the
transferability of findings to other public sector settings where
ADS are used.
4   |   Results
The analysis identified three primary sources of algorithmic
administrative error: data quality, design flaws, and limitations
intrinsic to the nature of algorithmic systems themselves. As
Table 1 shows, each source encompasses several subtypes, each
leading to specific forms of error that can cause system outputs
to diverge from statutory criteria. By tracing errors to their or-
igins, this typology illustrates the distinct pathways through
which algorithmic administrative errors arise in practice. The
following sections explain each source in detail, drawing on
exemplar cases to demonstrate how these errors materialize in
real-­world benefit determinations.
4.1   |   Data Quality
ADS can process large datasets and detect patterns, but their
outputs are constrained by the quality, relevance, and complete-
ness of the underlying data. Data must not only be sufficient in
quantity and accuracy; it must also reflect the factors decision-­
makers are legally required to consider. When those conditions
are not met, errors follow. In real-­world deployments, conditions
change over time. When models trained on historical data are
not updated, “data drift” can render once-­accurate predictions
unreliable or even erroneous because the data no longer reflects
the current reality. In disability benefits determination, if the
algorithmic model is based on past medical conditions or care
needs, it may lead to inaccurate assessments that may not align
with beneficiaries' current circumstances.
The case of Brandy C. v. Palmer is an example of a real-­world in-
stance where data drift influenced outcomes for disability ben-
efits determinations. This case involves a class action lawsuit
against the Florida Agency for Persons with Disabilities chal-
lenging the use of an ADS called iBudget for determining dis-
ability benefits. The system is used to determine an amount that
sets a floor on the level of assistance a beneficiary may receive.
The testimony of an expert witness in this case exemplifies how
reliance on outdated data can lead to decisions that are not in
sync with the actual, current needs of the beneficiaries. The
expert witness explained that the “goal was to develop a model
that would accurately reflect future clients' needs, but the model
itself was based on the actual 2013–2014 needs.”1
Because the algorithmic model was based on past data, sys-
tem output was limited to the needs determined in the past.
However, the needs of beneficiaries are likely to have changed
since 2013–2014 due to changing and likely worsening health
conditions or economic situations. Data drift occurs when the
statistical properties of the target variable, which the model pre-
dictions are based on, change over time. As pointed out in the
expert testimony, the ADS could not account for changes in ac-
tual need that have occurred since the data was collected and
the model was built.
In addition to data drift, erroneous decisions in algorithmic
decision-­making can originate from the use of unrepresentative
or incomplete training data, or the reliance on flawed informa-
tion. This issue is starkly illustrated in several legal cases, high-
lighting the severe consequences of data inaccuracies in such
systems. For instance, in the case of K.W. v. Armstrong, chal-
lenging the Idaho Department of Health and Welfare's use of an
ADS for disability benefits, deposition transcripts from expert
witnesses revealed significant data flaws. The system's initial
data set comprised records from 3512 participants, but over 37%
had to be discarded due to clear errors. Further data issues in-
cluded mismatched Medicaid IDs and incomplete or unreliable
information, leading to a drastic reduction in the usable dataset.
From the 2180 participant records, only 998 (less than half) even
appeared to be valid. Yet, when IDHW's analyst loaded those


## Page 6

376
Public Administration Review, 2026
998 records into the algorithmic system, the system could only
use 733 of those records. In other words, 66% of the original sam-
ple size was not used to build the tool because of unmatched
Medicaid IDs, missing IIN assessment data, and missing paid
claims data.2
Despite the drastic reduction in the usable dataset, the depart-
ment argued that the remaining sample size was statistically
significant. However, further analysis revealed substantial un-
derrepresentation and inaccuracies, with one region being sig-
nificantly underrepresented due to a database transition. As
a result, the algorithmic tool failed to produce adequate bud-
gets for up to 15% of participants, meaning hundreds received
insufficient funds for their needs. The unreliability of the data
was compounded by the fact that the department did not verify
whether the data used were from participants who received all
necessary services or institutionalization in 2009/2010.
Errors can also arise when integrating data across different
systems. Even if data is processed correctly within one system,
mismatches in data formats, scale, or interpretations when
transferred between systems can lead to erroneous determi-
nations. The class action lawsuits challenging the Michigan
Unemployment Insurance Agency's use of the Michigan
Integrated Data Automated System (MiDAS) reveal the severe
consequences that can arise from data quality issues.3 This
TABLE 1    |    Typology of algorithmic administrative error sources.
Error source
Subtype
Definition
Exemplar cases (jurisdiction/year)
Data quality
Data drift
Outdated training
data misrepresents
current conditions.
Brandy C. v. Palmer (N.D. Fla. 2018).
Unrepresentative data
Gaps/exclusions in
training data that
bias outputs.
K.W. v. Armstrong (D. Idaho 2016).
Data Integration failures
Errors when migrating,
merging, or matching
data across systems
(IDs, formats, records).
Cahoo v. SAS Analytics (6th Cir. 2019,
2023); Bauserman v. UIA (Mich. 2022).
Design flaws
Omitted variables
Legally relevant factors
are not encoded.
Arkansas DHS v. Ledgerwood (Ark. 2017;
2019). Jacobs v. Gillespie (Ark. 2016)
Failure to capture all
eligibility categories
System rules or
workflows omit required
eligibility bases.
A.M.C. v. Smith (M.D. Tenn. 2022).
Unauthorized eligibility
requirements
Extra-­legal criteria
imposed via system logic.
Darjee v. Betlach (D. Ariz. 2018).
Statutory criteria narrowed
Implemented instructions
remove legally required
factors or create
new, unpromulgated
standards; categorical
presumptions
displace need-­based
determinations.
Cholvin v. Wis. DHFS (Wis. Ct. App.
2008); Samantha A. v. DSHS (Wash.
2011); D.B. v. Dreyfus (W.D. Wash.
2012); Rekhter v. DSHS (Wash. 2014).
Inappropriate proxies
Computationally
convenient metrics
mismeasure the legally
relevant construct
Cahoo v. SAS Analytics (6th Cir. 2019),
2023; Bauserman v. UIA, (Mich. 2022).
Construct-­validity/reliability defects
Instrument/subscale does
not fully capture legally
relevant constructs.
Brandy C. v. Palmer (N.D. Fla. 2018)
System
limitations
Correlation substitutes for causation
Statistical association is
used as legal attribution.
Correlation ≠ causation
Barry v. Lyon (6th Cir. 2016);
Bauserman v. UIA (Mich. 2022).
Contextual blindness
Systems cannot weigh
intent, mitigation, or
ambiguity in records.
Bauserman v. UIA (Mich. 2022).


## Page 7

377
Public Administration Review, 2026
system, despite being a $47 million initiative designed to lever-
age vast internal databases for detecting unemployment benefit
fraud, severely faltered due to poor data quality and system con-
figuration errors. MiDAS was supposed to enhance efficiency by
cross-­referencing data from various sources, including employ-
ers, state agencies, and the federal government. In 2013 alone,
MiDAS inaccurately accused ~48,000 individuals of fraud—a
significant increase compared to the system it replaced. A sub-
sequent state review found that 93% of these determinations
were incorrect. A critical contributor to the high error rate was
that the transition from the agency's legacy system to MiDAS
involved inaccurate data entry and poor data conversion prac-
tices. As explained below, that rate was further amplified by
reliance on an inappropriate proxy to operationalize legal cri-
teria. Overall, these cases illustrate how data-­quality defects—
whether due to data drift or unrepresentative sampling can yield
wrongful determinations.
4.2   |   Design Flaws
Even if the underlying data are accurate, errors can occur due to
flawed design choices in system logic or coding. These include
mistaken assumptions about variable relationships, faulty im-
plementation of legal criteria, and programming errors in pre-­
populated fields or flags. Such flaws may result from oversight
during system design, efforts to oversimplify models, insuffi-
cient knowledge of the aims of public benefits programs, or mis-
understanding which factors are essential to measure.
The case of Cholvin v. Wisconsin Department of Health and
Family Services illustrates how design choices can result in the
misapplication of statutory criteria. Here, the plaintiff chal-
lenged the determination because the algorithmic assessment
yielded “wildly different” functionality evaluations compared to
prior evaluations. The court found that the instruction given to
the system to determine the level of care “[mis]interprets law be-
cause it removes from consideration a number of possible func-
tional limitations,” and that the model imposed a new eligibility
standard not validly promulgated as a rule.4
Similar design-­driven distortions emerged in Darjee v. Betlach.
In this case, the state's HEAPlus system (Health-­e Arizona Plus)
incorrectly imposed a five-­year residency requirement on ref-
ugees transitioning to permanent residency. As a result, indi-
viduals entitled to full coverage were mistakenly restricted to
emergency-­only health services, demonstrating how flawed op-
erationalization of legal criteria can result in wrongful determi-
nations.5 Parallel issues were revealed in A.M.C. v. Smith. Here,
Tennessee's TennCare eligibility determination system failed to
evaluate all disability-­related eligibility categories and required
beneficiaries to submit irrelevant documentation for redeter-
mination.6 This practice not only burdened beneficiaries with
unnecessary paperwork but also led to wrongful terminations
for failing to provide information that the state had no legal
grounds to demand.
Flawed operationalization of legal criteria can also occur
due to the omission of key variables in the coding process. In
Ledgerwood v. Arkansas Department of Human Services, exam-
ination of the Resource Utilization Groups (RUGs) algorithm
revealed that the system failed to account for several factors
essential to accurately assessing beneficiary needs. The system
failed to flag double below-­knee amputations as “foot problems”
and diabetes, cerebral palsy, and septicemia were entirely omit-
ted due to missing codes for these conditions. Internal data
revealed the direct consequences: 75% of those affected by the
diabetes coding error lost authorized care hours, and at least 152
people lost an average of 25 h per month due to the cerebral palsy
error.7
Beyond omitted variables, flawed categorizations that oversim-
plify individual circumstances can also undermine statutory
compliance. In Samantha A. v. Washington Department of Social
& Health Services, it was revealed that the state's Comprehensive
Assessment and Reporting Evaluation (CARE) system automat-
ically reduced care hours based on irrebuttable age and housing
presumptions, treating certain needs as “met” regardless of ben-
eficiaries' actual situations. The court found that this mechan-
ical categorization violated statutory requirements by reducing
benefits for reasons other than actual need and invalidated the
relevant code.8 Similar CARE-­based rules were challenged in
D.B. v. Dreyfus, M.T.E. v. Wash. State Department of Social &
Health Services, and Rekhter v. Department of Social & Health
Services.9 These cases show how seemingly technical design
choices (what to include, exclude, or assume) can render certain
needs or conditions invisible to the algorithm and circumvent
the statutory requirement of individualized assessment.
The litigation record also reveals another type of design flaw: re-
liance on inappropriate proxies that mismeasure the legally rel-
evant construct. Beyond the data quality flaws discussed above,
the MiDAS system operationalized fraud detection using an
“income spreading” method.10 This approach averaged a claim-
ant's total quarterly earnings over 13 weeks and assigned that
average to each week in the quarter, regardless of whether the
claimant actually earned zero income in some weeks. By sub-
stituting this computationally convenient proxy for the legally
required measure of actual weekly income, the system produced
widespread false fraud accusations. As a result, MiDAS auto-
matically deemed claimants to have committed fraud whenever
it detected a week with reported zero income within a quarter
that included any earnings, regardless of whether the claimants
were, in fact, entitled to benefits for weeks they did not work.
A related but distinct measurement flaw was documented in
Brandy C. v. Palmer, where the system failed to capture the le-
gally relevant constructs it was designed to assess. Specifically,
the Questionnaire for Situational Information (QSI) used by
the iBudget system exhibited construct validity issues: one of
its three subscales showed only a weak correlation with its in-
tended measures, and the QSI proved more reliable in assess-
ing functional and physical limitations than behavioral ones.
These measurement flaws were not merely technical issues;
they produced determinations so arbitrary that the plaintiff's
expert characterized them as “the equivalent of funding service
needs by putting individual funding amounts on a dart board
and throwing darts at it.”11 For example, one plaintiff's approved
cost plan for FY 2016–2017 was $138,491.88; after iBudget was
applied, the allocation dropped to $27,934.27—an almost 80%
reduction—despite no material change in medically necessary
services.


## Page 8

378
Public Administration Review, 2026
Although distinct in their technical mechanisms, both forms
of design flaw are rooted in oversimplification. In MiDAS, this
manifests as algorithmic reductionism, reducing legal complex-
ity to a computationally convenient but substantively inaccurate
proxy. In iBudget, the flaw lies in privileging easily quantifiable
physical functions over harder-­to-­observe, complex behavioral
needs. In both cases, the systems were optimized for quantifi-
able simplicity at the expense of statutory complexity.
4.3   |   System Limitations
Improving data quality and design addresses many sources of
administrative error. However, some limits are intrinsic to the
nature of these systems. Unlike errors arising from flawed data
or design, these limitations reflect the epistemological boundar-
ies of systems: ADS process patterns, not meaning; correlations,
not causation; data, not context. While correlational analyses
can identify statistical relationships between variables, many
systems apply these associations to causal decision-­making
procedures, despite limited scientific evidence supporting such
an approach (Wang et al. 2024). Ultimately, ADS optimize pat-
tern recognition, not legal reasoning. They cannot interrogate
whether inputs are complete or appropriate, nor can they inde-
pendently distinguish an honest mistake from intentional fraud.
These limits surface clearly in Barry v. Lyon, where SNAP re-
cipients were automatically disqualified based solely on a data
match to outstanding felony warrants even when law enforce-
ment later confirmed that the disqualified person was not the
individual sought in the warrant. The Sixth Circuit affirmed
classwide relief, holding that automatic disqualification on the
basis of a warrant hit without verifying identity or warrant va-
lidity violated statutory requirements. The case highlights the
risks of treating data-­match correlation as legal attribution.12
MiDAS, discussed above, likewise illustrates how pattern rec-
ognition can supplant legal judgment. The system automati-
cally inferred fraud when it detected inconsistencies such as a
week of reported zero income within a quarter that contained
any earnings. It also generated fraud flags whenever there was a
discrepancy between the reason for employment termination as
reported by the claimant and the employer, because the system
could not account for the possibility of honest factual disputes,
indiscriminately treating any discrepancy as evidence of fraud.13
In these instances, correlation was treated as causation, and pat-
tern recognition became a substitute for probative legal evidence
even though a statistical discrepancy does not, in itself, establish
legal culpability. Recognizing these inherent limits matters for
governance: even with perfect data pipelines and carefully spec-
ified code, ADS lack the capacity to discern context. Agencies
therefore need procedures that pair ADS outputs with verifica-
tion, rebuttal opportunities, and individualized assessment.
5   |   Discussion
The lessons from legal challenges are clear: when systems fail to
function as intended, ADS designed to optimize administrative
decision-­making instead become conduits for administrative
error. As evidenced across the litigation record, whether an error
arises from a clerk's misreading of a file or a line of mis-­coded
logic, the outcome is the same: deviation from legally prescribed
outcomes. The difference lies in modality and scale. Algorithmic
administrative errors (AAEs) are not isolated incidents but sys-
temic, embedded failures. They arise when the translation of
statutory requirements into computational logic is compromised
by flawed data, problematic design choices, or inherent system
limitations. Unlike street-­level administrative errors, which typ-
ically affect isolated cases, a mis-­specified proxy can undermine
thousands of determinations, as exemplified by the 48,000 false
fraud flags produced by Michigan's MiDAS system. A single
error by a frontline worker could not, except in highly unusual
circumstances, propagate across tens of thousands of cases in
the way a system-­level flaw can.
These findings speak directly to persistent challenges in public
administration. Agencies adopt ADS to transcend the cognitive
limitations of human decision-­makers (Simon 1967) and curb
the arbitrary use of discretion (Jorna and Wagenaar 2007) with
expectations that algorithms will outperform street-­level bu-
reaucrats (Sunstein 2021). Yet, these benefits are only realized
if systems function as intended. The evidence presented here
shows what happens when they do not. ADS themselves are
bounded by data quality, model design, and system capabilities.
Furthermore, ADS shift rather than resolve the control problem.
These systems increase processing speed, but they do not elim-
inate human fallibility. The risk is simply relocated from the
caseworker's desk to the developer's keyboard.
Despite the continued dominance of system designers in di-
agnosing and “speaking for” error in algorithms (Lin and
Jackson 2023), the evidence presented here demonstrates that
AAEs transcend purely technical problems. Data science met-
rics measure how well a system predicts outcomes using avail-
able data and predefined labels, but they capture only what is
measurable within the dataset. Consequently, AAEs can per-
sist undetected precisely because systems function as designed,
leaving agencies to manage the consequences only after the fact.
Identifying AAEs requires more than simply auditing code; it
depends on designers understanding the policy and operational
context of public assistance programs as thoroughly as public
administrators do. Encoding eligibility criteria or program re-
quirements is as much a matter of statutory interpretation as of
system engineering. As demonstrated here, an output may be
statistically accurate by data science standards, yet remain le-
gally noncompliant when data schemas do not fully conform
to statutory criteria (K.W. v. Armstrong), when legally relevant
factors are not encoded (Ledgerwood v. Arkansas Department of
Human Services), or when the code distorts legally significant
constructs (Brandy C. v. Palmer). As Young et al. (2023) show,
automated claims systems record higher error rates precisely
where program rules are most complex (Young et al. 2023).
Although the litigation record analyzed here concerns rule-­
based systems, its lessons extend to the next wave of public-­sector
AI. Advanced AI systems operate on larger, noisier datasets and
continually adjust their decision parameters. Indeed, the very
features that make them appealing—scalability, capacity to pro-
cess noisy datasets, and continual self-­updating—intensify the
conditions in which errors may arise. A mis-­labeled training


## Page 9

379
Public Administration Review, 2026
record or a mis-­specified feature can cascade through millions
of inferences. In deep learning systems, parameter weights may
bear no semantic relation to categories such as “household” or
“ability to work.” Moreover, systems that learn and adjust to new
data increase the risk that originally sound models become mis-
aligned with legal standards over time. Improving data quality
and design addresses many failures, but some limits are intrin-
sic to ADS. Prediction systems optimize pattern recognition,
not legal reasoning: they cannot interrogate whether inputs are
complete or appropriate, nor can they independently distinguish
an honest mistake from intentional fraud. Hence, systems de-
signed for pattern recognition cannot fulfill public law's demand
for reasoned interpretation.
For public managers, the challenge is no longer limited to con-
trolling errors at the street level; it now extends to controlling
the systems themselves. The surfacing of AAEs only after
litigation indicates that current oversight mechanisms are
inadequate. Agencies must build organizational capacity to in-
tercept AAEs at their source. Although classification and over-
sight of high-­risk AI systems remain essential (Bannister and
Connolly 2020), the evidence presented here underscores that
macro-­level risk classifications must be paired with micro-­level
interventions. Meeting this challenge requires a multilayered,
life-­cycle approach to oversight that pairs error sources (Table 1)
with targeted controls (Table 2).
As Table 2 illustrates, each error source requires distinct pre-­
and post-­deployment controls. The table also highlights the
need for both legal and program expertise not only at the design
stage but throughout the system's operational life cycle so that
agencies can ensure statutory compliance ex ante rather than
reacting to harms ex post.
6   |   Conclusion
ADS promise unprecedented gains in efficiency, yet the evi-
dence presented here demonstrates that efficiency gains come
bundled with algorithmic administrative errors (AAEs) that are
systemic, scalable, and difficult to detect. Treating such errors
merely as technical problems obscures how ADS can breach stat-
utory mandates by omitting legally relevant variables, relying on
proxies that mismeasure statutory constructs, or optimizing for
quantifiable simplicity at the expense of statutory complexity.
Because such error pathways extend beyond the equity concerns
that disparate impact analysis can surface, these findings un-
derscore that algorithmic administrative errors must be under-
stood and addressed as a systemic governance problem, rather
than as isolated malfunctions examined in disciplinary silos.
The concept of AAE provides a systems-­level diagnostic lens for
examining how statutory mandates are undermined by deficien-
cies in data quality, design logic, or inherent system limitations.
By doing so, this article makes two conceptual advancements:
first, it moves beyond narrow technical metrics to place public-­
law compliance at the center of validity—reminding us that an
output may be statistically accurate yet still legally noncompli-
ant; second, it offers a layered typology for diagnosing failures
across both rule-­based and machine-­learning systems.
TABLE 2    |    Oversight of algorithmic administrative errors.
Error source
Subtype
Pre-­deployment
Post-­deployment
Data quality
Data drift
Drift risk assessment and
monitoring protocols; document
expected drift channels
Quarterly audits, establish
retraining triggers
Unrepresentative data
Data provenance register; independent
review of inclusion/exclusion decisions
Periodic completeness/
validity audits
Data integration failures
Data migration validation
(reconciliation w/legacy system data)
Match-­rate monitoring
(ID/record thresholds)
Design flaws
Omitted variables
Rule-­translation audit: lawyers and
program lead review to confirm
inclusion of every statutory
factor and eligibility pathway
Targeted audits of
denials/benefit cuts
Unauthorized requirements
Rule-­translation audits (statutory
requirements ↔ code alignment)
Change-­management
logs with legal sign-­off.
Inappropriate proxies/
Construct validity defects
Demonstrate construct
alignment between metric and
legally required construct; bar
deployment absent validation
Periodic revalidation
System limitations
Correlation as causation
Models may flag but not conclusively
adjudicate fraud/eligibility
Identity/validity verification,
rebuttal opportunities,
Adjudicator override
Contextual blindness
Human-­in-­the-­loop review
Rebuttal opportunities,
Adjudicator override


## Page 10

380
Public Administration Review, 2026
This article broadens our understanding of the limitations of
ADS by showing how flaws in data quality, design, and system
constraints can result in determinations that contravene the
laws governing public benefits adjudication. In doing so, it re-
sponds to calls for greater attention to the systems that shape
public decision-­making (Zouridis et al. 2020), and expands our
understanding of the consequences of transitioning from street-­
level to system-­level bureaucracy (Bovens and Zouridis 2002).
As ADS displace frontline discretion, AAEs supplant street-­level
administrative errors. If left unchecked, AAEs risk producing
arbitrary determinations through the very technologies in-
tended to prevent them.
AI governance scholars devote considerable attention to antici-
pating potential future harms, but developing effective oversight
begins with understanding the problems that are occurring now.
The problem of AAE is already with us; it is not a hypothetical
risk confined to a distant, “more-­AI” future. Advanced AI mod-
els are just as, if not more, vulnerable to issues of data quality
and design flaws as demonstrated here. Moreover, machines are
incapable of doubting the correctness of their outputs or ques-
tioning whether the data they process is flawed. Accordingly,
the evidence presented underscores that macro-­level risk clas-
sifications must be paired with micro-­level interventions. This
study translates lessons from legal challenges into actionable
guidance for oversight by developing a typology that traces
failures to their proximate sources and links each source to a
specific locus of institutional control. In doing so, it responds
to calls for practitioner-­oriented research on mitigating the dark
sides of AI in public decision-­making (Gomes and Domingos
2025; Schwarz et al. 2022).
Preventing repeated errors requires that lessons from past fail-
ures are made visible to practitioners. However, the identifica-
tion of AAEs is necessarily contingent on available evidence.
This study draws on litigated cases with publicly available re-
cords, meaning that both the visibility and the interpretation
of error are shaped by what surfaces through legal challenges.
Whether AAE manifests similarly across a broader spectrum
of public benefits determinations remains an open question for
future research.
Ultimately, the tension between opportunity and risk is a per-
sistent theme in government use of ADS. Efficiency, although
quantifiable in computational speed and reduced labor, may
come at the cost of undermining legal compliance. Thus, the
question for the future of public administration is not whether
ADS can outperform street-­level bureaucrats, but how to gov-
ern AAEs so that efficiency gains do not come at the expense
of statutory compliance. For policymakers, the risk lies in pre-
scribing outdated remedies for novel problems; for researchers,
the challenge lies in keeping pace with the rapid diffusion of
ADS in the public sector, lest the field risk fighting yesterday's
battles.
Acknowledgments
I am sincerely grateful for valuable feedback on earlier versions of this
manuscript from Julie Novkov, Virginia Eubanks, Patricia Strach,
Stephan Stohler, and Jill Clark. I also thank the editors and anonymous
reviewers for their guidance and constructive feedback.
Conflicts of Interest
The author declares no conflicts of interest.
Endnotes
1	Brandy C. v. Palmer, 2018 WL 4689464 (N.D. Fla. 2018); Deposition of
James T. McClave, Ph.D., 17:22–25 (on file with author).
2	K.W. ex rel. D.W. v. Armstrong, 789 F.3d 962, 970–74 (9th Cir. 2015);
Brief in Support of Plaintiffs' Motion for Summary Judgment on Class
Claims, at 7, K.W. ex rel. D.W. v. Armstrong, No. 1:12-­cv-­00022-­BLW
(D. Idaho July 27 2015), ECF No. 189–1; Ex. 8, ECF No. 189–44.
3	Bauserman v. Unemployment Ins. Agency, No. 333181, 2019 WL
6622945 (Mich. Ct. App. 2019); Cahoo v. SAS Inst. Inc., 377 F. Supp.
3d 769, 771–72 (E.D. Mich. 2019).
4	Cholvin v. Wisconsin Department of Health & Family Services, 2008
WI App 127, ¶ 12 (Wis. Ct. App. 2008).
5	Darjee v. Betlach, No. CV-­16-­00489-­TUC-­RM (DTF) (D. Ariz. Sept 4
2018); for another example, see M.K.B. v. Eggleston, 445 F. Supp. 2d
400, 412 (S.D.N.Y. 2006).
6	Amended Complaint, A.M.C. v. Smith, No. 3:20-­cv-­00240, 2023 WL
6881785 (M.D. Tenn. May 5, 2022).
7	Ledgerwood v. Arkansas Department of Human Services, 60 CV-­
17-­442 (Ark. Cir. Ct. May 14 2018); Jacobs v. Gillespie, No. 3:16-­cv-­
00119 (E.D. Ark. Nov 1 2016); memorandum by plaintiffs' attorney
Kevin De Liban, “Algorithm Absurdities—RUGs as Implemented in
Arkansas” (on file with author).
8	Samantha A. v. Department of Social & Health Services, 171 Wash. 2d
623, 256 P.3d 1138, 1142 (2011) (citing Jenkins v. Department of Social
& Health Services, 160 Wn.2d 287, 157 P.3d 388 (2007)).
9	D.B. v. Dreyfus, 2012 U.S. Dist. LEXIS 69957, *2–4, 2012 WL 1821241
(W.D. Wash. May 18 2012); M.T.E. v. Washington State Department of
Social & Health Services, 2011 U.S. Dist. Lexis 107,095, *2, 2011 WL
4403025 (W.D. Wash. Sept 21 2011).
10	Bauserman v. Unemployment Ins. Agency, No. 333181, 2019 WL
6622945 (Mich. Ct. App. 2019); Cahoo v. SAS Inst. Inc., 377 F. Supp.
3d 769, 771–72 (E.D. Mich. 2019).
11	Brandy C. v. Palmer, 2018 WL 4689464 (N.D.Fla. 2018). Expert Report
dated October 23, 2017, and 2016 direct examination testimony (on
file with author).
12	Barry v. Lyon, 834 F.3d 706 (6th Cir. 2016).
13	Bauserman v. Unemployment Ins. Agency, No. 333181, 2019 WL
6622945 (Mich. Ct. App. 2019); Cahoo v. SAS Inst. Inc., 377 F. Supp.
3d 769, 771–72 (E.D. Mich. 2019).
References
Angwin, J., J. Larson, and S. Mattu. 2016. “Machine Bias.” https://​
www.​propu​blica.​org/​artic​le/​machi​ne-­​bias-­​risk-­​asses​sment​s-­​in-­​crimi​
nal-­​sente​ncing​.
Bannister, F., and R. Connolly. 2020. “Administration by Algorithm: A
Risk Management Framework.” Information Polity 25, no. 4: 471–490.
Bovens, M., and S. Zouridis. 2002. “From Street-­Level to System-­Level
Bureaucracies: How Information and Communication Technology Is
Transforming Administrative Discretion and Constitutional Control.”
Public Administration Review 62, no. 2: 174–184. https://​doi.​org/​10.​
1111/​0033-­​3352.​00168​.
Brauneis, R., and E. P. Goodman. 2018. “Algorithmic Transparency for
the Smart City.” Yale Journal of Law and Technology 20: 103–174.
Brown, L., M. Richardson, R. Shetty, and A. Crawford. 2020.
“Challenging the Use of Algorithm-­Driven Decision-­Making in
Benefits Determinations Affecting People With Disabilities.” Center for


## Page 11

381
Public Administration Review, 2026
Democracy & Technology. https://​cdt.​org/​insig​hts/​repor​t-­​chall​engin​g-­​
the-­​use-­​of-­​algor​ithm-­​drive​n-­​decis​ion-­​makin​g-­​in-­​benef​its-­​deter​minat​
ions-­​affec​ting-­​peopl​e-­​with-­​disab​iliti​es/​.
Bullock, J. B. 2014. “Theory of Bureaucratic Error.” Academy of
Management Proceedings 2014, no. 1: 17469. https://​doi.​org/​10.​5465/​
ambpp.​2014.​17469​abstract.
Busuioc, M. 2021. “Accountable Artificial Intelligence: Holding
Algorithms to Account.” Public Administration Review 81, no. 5: 825–
836. https://​doi.​org/​10.​1111/​puar.​13293​.
Calo, R., and D. K. Citron. 2020. “The Automated Administrative State:
A Crisis of Legitimacy.” Emory Law Journal 70: 797.
Coglianese, C., and A. Lai. 2021. “Algorithm vs. Algorithm.” Duke Law
Journal 72: 1282–1340.
Compton, M. E., M. M. Young, J. B. Bullock, and R. Greer. 2023.
“Administrative Errors and Race: Can Technology Mitigate Inequitable
Administrative Outcomes?” Journal of Public Administration Research
and Theory 33, no. 3: 512–528.
Deborah Raji, I., E. Kumar, A. Horowitz, and A. Selbst. 2022. “The
Fallacy of AI Functionality.” In 2022 ACM Conference on Fairness,
Accountability, and Transparency (FAccT '22), June 21–24, 2022,
Seoul, Republic of Korea,  14. ACM. https://​doi.​org/​10.​1145/​35311​46.​
3533158.
Dwivedi, Y. K., L. Hughes, E. Ismagilova, et  al. 2021. “Artificial
Intelligence
(AI):
Multidisciplinary
Perspectives
on
Emerging
Challenges, Opportunities, and Agenda for Research, Practice and
Policy.” International Journal of Information Management 57: 101994.
https://​doi.​org/​10.​1016/j.​ijinf​omgt.​2019.​08.​002.
Eubanks, V. 2018. Automating Inequality. Macmillan.
Glaze, K., D. E. Ho, G. Ray, and C. Tsang. 2021. “Artificial Intelligence
for Adjudication: The Social Security Administration and AI
Governance.” SSRN Electronic Journal. https://​doi.​org/​10.​2139/​ssrn.​
3935950.
Gomes, R. C., and F. D. Domingos. 2025. “Herbert Simon's Legacy for
Public Administration.” Public Administration 1, no. 14. https://​doi.​org/​
10.​1111/​padm.​13051​.
Green, B. 2022. “The Flaws of Policies Requiring Human Oversight of
Government Algorithms.” Computer Law and Security Review 45, no.
7: 105681.
Greer, R. A., and J. B. Bullock. 2018. “Decreasing Improper Payments
in a Complex Federal Program.” Public Administration Review 78, no.
1: 14–23.
Hoynes, H. W., N. Maestas, and A. Strand. 2022. “Legal Representation
in Disability Claims.” National Bureau of Economic Research. https://​
www.​nber.​org/​papers/​w29871.
Jorna, F., and P. Wagenaar. 2007. “The ‘Iron Cage’ Strengthened?
Discretion and Digital Discipline.” Public Administration 85, no. 1:
189–214.
Kleinberg, J., H. Lakkaraju, J. Leskovec, J. Ludwig, and S.
Mullainathan. 2018. “Human Decisions and Machine Predictions.”
Quarterly Journal of Economics 133, no. 1: 237–293. https://​doi.​org/​
10.​1093/​qje/​qjx032.
Larsson, K. K. 2021. “Digitization or Equality: When Government
Automation Covers Some, but Not All Citizens.” Government
Information Quarterly 38, no. 1: 101547.
Lin, C. K., and S. J. Jackson. 2023. “From Bias to Repair: Error as a
Site of Collaboration and Negotiation in Applied Data Science Work.”
Proceedings of the ACM on Human-­Computer Interaction 7, no. CSCW1:
1–32. https://​doi.​org/​10.​1145/​3579607.
Lynn, J., and E. Laurence. 2009. “Restoring the Rule of Law to Public
Administration: What Frank Goodnow Got Right and Leonard White
Didn't.” Public Administration Review 69, no. 5: 803–813.
Madan, R., and M. Ashok. 2023. “AI Adoption and Diffusion in Public
Administration: A Systematic Literature Review and Future Research
Agenda.” Government Information Quarterly 40, no. 1: 101774.
Mergel, I., H. Dickinson, J. Stenvall, and M. Gasco. 2023. “Implementing
AI in the Public Sector.” Public Management Review 1:  1–14. https://​doi.​
org/​10.​1080/​14719​037.​2023.​2231950.
Moe, R. C., and R. S. Gilmour. 1995. “Rediscovering Principles of Public
Administration: The Neglected Foundation of Public Law.” Public
Administration Review 55, no. 2: 135.
Morley, J., L. Floridi, L. Kinsey, and A. Elhalal. 2020. “From What to
How: An Initial Review of Publicly Available AI Ethics Tools, Methods
and Research to Translate Principles Into Practices.” Science and
Engineering Ethics 26, no. 4: 2141–2168. https://​doi.​org/​10.​1007/​s1194​
8-­​019-­​00165​-­​5.
Patton, M. Q. 2014. Qualitative Research & Evaluation Methods:
Integrating Theory and Practice. Sage publications.
Peeters, R., and A. C. Widlak. 2023. “Administrative Exclusion in the
Infrastructure-­Level Bureaucracy: The Case of the Dutch Daycare
Benefit Scandal.” Public Administration Review 83, no. 4: 863–877.
https://​doi.​org/​10.​1111/​puar.​13615​.
Pencheva, I., M. Esteve, and S. J. Mikhaylov. 2020. “Big Data and AI – A
Transformational Shift for Government: So, What Next for Research?”
Public Policy and Administration 35, no. 1: 24–44. https://​doi.​org/​10.​
1177/​09520​76718​780537.
Raso, J. 2021. “Implementing Digitalization in an Administrative
Justice Context.” In Oxford Handbook of Administrative Justice. Oxford
University Press.
Roehl, U. B. U., and M. B. Hansen. 2024. “Automated, Administrative
Decision-­Making and Good Governance: Synergies, Trade-­Offs, and
Limits.” Public Administration Review 84: 1184–1199. https://​doi.​org/​
10.​1111/​puar.​13799​.
Russell, S., and P. Norvig. 2021. Artificial Intelligence: A Modern
Approach. Pearson Series in Artifical Intelligence.
Schwarz, G., T. Christensen, and X. Zhu. 2022. “Bounded Rationality,
Satisficing, Artificial Intelligence, and Decision-­Making in Public
Organizations:
The
Contributions
of
Herbert
Simon.”
Public
Administration Review 82, no. 5: 902–904. https://​doi.​org/​10.​1111/​puar.​
13540​.
Simon, H. A. 1967. Administrative Behavior: A Study of Decision-­Making
Processes in Administrative Organizations. 2nd ed. Free Press.
Stake, R. E. 2013. Multiple Case Study Analysis. Guilford Press.
Stewart, J. 2012. “Multiple-­Case Study Methods in Governance-­Related
Research.” Public Management Review 14, no. 1: 67–82. https://​doi.​org/​
10.​1080/​14719​037.​2011.​589618.
Sunstein, C. R. 2021. “Governing by Algorithm? No Noise and
(Potentially) Less Bias Automating the Administrative State.” Duke Law
Journal 71, no. 6: 1175–1206.
Valle-­Cruz, D., R. García-­Contreras, and J. R. Gil-­Garcia. 2024.
“Exploring the Negative Impacts of Artificial Intelligence in
Government: The Dark Side of Intelligent Algorithms and Cognitive
Machines.” International Review of Administrative Sciences 90, no. 2:
353–368.
Wang, A., S. Kapoor, S. Barocas, and A. Narayanan. 2024. “Against
Predictive Optimization: On the Legitimacy of Decision-­Making
Algorithms That Optimize Predictive Accuracy.” ACM Journal
on Responsible Computing 1, no. 1: 1–45. https://​doi.​org/​10.​1145/​
3636509.
Wirtz, B. W., P. F. Langer, and C. Fenner. 2021. “Artificial Intelligence in
the Public Sector -­ a Research Agenda.” International Journal of Public
Administration 44, no. 13: 1103–1128.
Yin, R. K. 2018. Case Study Research: Design and Methods. Vol. 6. SAGE.


## Page 12

382
Public Administration Review, 2026
Young, M. M., M. Compton, J. B. Bullock, and R. Greer. 2023.
“Complexity, Errors, and Administrative Burdens.” Public Management
Review 26, no. 10: 2847–2867. https://​doi.​org/​10.​1080/​14719​037.​2023.​
2288247.
Zouridis, S., M. van Eck, and M. Bovens. 2020. “Automated Discretion.”
In Discretion and the Quest for Controlled Freedom, edited by T. Evans
and P. Hupe, 313–329. Springer International Publishing. https://​doi.​
org/​10.​1007/​978-­​3-­​030-­​19566​-­​3_​20.
Supporting Information
Additional supporting information can be found online in the Supporting
Information section. Appendix S1: Supporting Information.
Biography
Esra Gules-­Guctas is an Assistant Professor at The Ohio State
University, holding a joint appointment at the John Glenn College of
Public Affairs and the Translational Data Analytics Institute. Her re-
search bridges law, technology, and public administration, examin-
ing how public agencies govern and use algorithmic decision-­making
systems.

