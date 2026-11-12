# SaferAg Engineering Safety in Emerging Agricultural Machinery Risk Assessment Da

## Page 1

Journal of Agricultural Safety and Health
31(4): 311-324               © 2025 ASABE   ISSN 1074-7583   https://doi.org/10.13031/jash.16516
311
SaferAg – Engineering Safety
in Emerging Agricultural
Machinery: Risk Assessment,
Data Needs, and Standards
John M. Shutske1,*,  Salah F. Issa2,  Farzaneh Khorsandi3,
Michael L. Pate4,  Serap Gorucu5,  Jean Walsh6,
Aaron M. Yoder7,  Guy R. Aby8,  Sihan Li2
Collection
Research
1 University of Wisconsin—Madison, Madison, Wisconsin, USA.
2 Department of Agricultural & Biological Engineering, University of Illinois, Urbana, Illinois, USA.
3 Cooperative Extension, Department of Biological and Agricultural Engineering, University of California,
Davis, California, USA.
4 Department of Applied Sciences Technology and Education, College of Agriculture and Applied Sciences,
Utah State University, Logan, Utah, USA.
5 Department of Agricultural and Biological Engineering, University of Florida, Gainesville, Florida, USA.
6 American Society of Agricultural & Biological Engineers, St. Joseph, Michigan, USA.
7 Environmental, Agricultural and Occupational Health, University of Nebraska Medical Center, Omaha,
Nebraska, USA.
8 National Farm Medicine Center, Marshfield Clinic Research Institute, Marshfield Clinic Health System,
Marshfield, Wisconsin, USA.
* Correspondence: shutske@wisc.edu
HIGHLIGHTS
• Autonomous and highly automated agricultural machines require data-informed risk as-
sessment integrated into design.
• Long-term incident data gaps for risk assessment necessitate alternative, creative solu-
tions and data sharing.
• Consensus, voluntary engineering standards should guide safe design for all types of
machines, but often lag behind rapid technological change.
• Broader awareness, access, and alignment of engineering design standards with emerg-
ing risks are essential for safe adoption.
The authors have paid for open access for this article. This work is licensed under a Creative
Commons Attribution-NonCommercial-NoDerivatives 4.0 International License https://creative
commons.org/licenses/by-nc-nd/4.0/
Submitted for review on 11 August 2025 as manuscript number JASH 16516; approved for publication as a
Research Article and as part of the Safety for Emerging Robotics & Autonomous Agriculture Collection by
Community Editor Dr. Dennis Murphy of the Ergonomics, Safety, & Health Community of ASABE on
18 October 2025.
SAFER AG 2.0 workshop activity and publication support provided by the intramural research program of
the U.S. Department of Agriculture, National Institute of Food and Agriculture, proposal # 2025-67021-44040 /
accession # 1033371. Additional faculty and graduate research support provided through USDA National Institute
of Food and Agriculture, Hatch Project 1022349 and the University of Wisconsin-Madison Agricultural
Experiment Station.  The findings and conclusions in this publication have not been formally disseminated by the
U.S. Department of Agriculture and should not be construed to represent any agency determination or policy.
Citation: Shutske, J. M., Issa, S. F., Khorsandi, F., Pate, M. L., Gorucu, S., Walsh, J., … Li, S. (2025). SaferAG
– Engineering safety in emerging agricultural machinery: Risk assessment, data needs, and standards. J. Agric.
Saf. Health, 31(4), 311-324. https://doi.org/10.13031/jash.16516


## Page 2

312
Journal of Agricultural Safety and Health
ABSTRACT. The introduction of highly automated and autonomous agricultural machinery
has led to concerns about the availability of appropriate historical data for engineering
design risk assessment to ensure protection from injury and other unexpected events. Dur-
ing the transition period from traditional farm tractors and machines to those more highly
automated, industry-based, consensus standards remain a vital tool in the design process.
This paper examines the role of risk assessment methods and consensus-based standards
in improving safety for these technologies. It includes cited literature presented in the form
of a primer or overview at the request of participants at the 2022 SaferAg workshop. It re-
views key risk assessment concepts, common methodologies, and the specific data needs
and limitations that arise when historical incident records are unavailable. The paper also
outlines how standards are developed, their connection to regulation, and recent updates
to ISO 18497 relevant to autonomous agricultural equipment. Key challenges include lag
times in standard development, uneven access to standards, and gaps in awareness among
both designers and policymakers engaged in new regulatory efforts. Addressing these chal-
lenges will require coordinated efforts in data collection, standard refinement, and stake-
holder education to ensure safe and effective deployment of emerging agricultural machine
forms.
Keywords. Agricultural, Autonomous, Autonomy, Equipment, Highly automated, Machin-
ery, Public policy, Regulation, Risk assessment, Safety, Standards.
his paper builds on insights from the 2022 SaferAg workshop, where researchers,
manufacturers, regulators, and safety professionals developed recommendations for
improving the safety of highly automated and autonomous agricultural equipment.
It focuses on the role of risk assessment and engineering standards as foundational tools
for implementing those recommendations. We first describe basic concepts of risk assess-
ment, including its purpose, an overview of some of the common tools used in machine
design risk assessment, and the critical data needs for estimating risk-related variables such
as incident frequency, probability, severity, hazard detectability, and controllability. Then,
a broad overview of consensus-based engineering design and safety standards is presented,
including why they are important, how they are developed, and their relationship to risk
assessment, as well as future regulation. Because of its critical nature to safety in new au-
tonomous and highly automated equipment design, this section also includes a detailed
update on the content found in a recently revised and significantly upgraded standard, ISO
18497, and its various parts. Finally, the paper concludes with a discussion of the intercon-
nections and relationships between risk assessment methods and processes, standards, and
some of the key issues for consideration.
Overviews
Risk Assessment
Purpose of Risk Assessment
The purpose of conducting a risk assessment for any product or component is to identify
and quantify specific ways in which the product or its components might cause harm, such
as injury or property damage. The goal is to reduce harm. Risk assessment assumes that all
products, their components, and the person-machine-environment systems in which these
products are used contain potential hazards. Risk assessment helps the designer to prioritize
T


## Page 3

31(4): 311-324
313
where safety engineering design efforts and investment will have the greatest positive im-
pact. Once hazards, potential harm, or failure possibilities are identified and prioritized,
risk assessment helps the developer to refine further and iterate on the design to mitigate
risk to an acceptable level (Popov et al., 2016).
Frequently cited definitions and risk assessment processes break risk down into different
components. These include the frequency of occurrence of failures, injuries, breakdowns,
other losses, or simply the likelihood of exposure to identified hazards (Haimes, 2009).
The idea of quantifying the frequency of exposure assumes that exposure is a precursor to
an adverse event. For example, if an operator is exposed to a rotating, unshielded drive
component, there is a non-zero probability that the exposure could result in an entangle-
ment injury or death. Minimizing or eliminating exposure or failure probability thus re-
duces risk.
Risk assessment methods also often consider the severity of an event that might be pre-
dicted to occur because of exposure or failure. As figure 1 shows, a high probability event
that has low severity or does not result in significant harm or loss will be of a relatively
lower quantified risk level than something that occurs with high probability with cata-
strophic consequences (high severity). The converse also applies. Low probability events
that result in catastrophic loss, such as individual or multiple deaths, are higher risk than
low probability, minor consequence events. With these methods, quantifying risk can in-
volve a function that conceptually includes multiplying probability by severity. Another
way to consider this relationship is that if an engineer or other responsible developer can
make either probability or severity levels approach zero, risk levels will also approach zero
(Haimes, 2009).
Some risk assessment methods incorporate other categories of data. For example, “de-
tectability” is sometimes included in the failure modes and effects risk assessment (FMEA)
method (Mikulak et al., 2017). The rationale is that a hazard that is present and can cause
harm should contribute more significantly and negatively (higher level of risk) to a
Figure 1. A conceptual view of risk as a function of probability and severity.


## Page 4

314
Journal of Agricultural Safety and Health
quantitative risk assessment if that hazard or failure mode is hidden, difficult to detect, or
“unknowable” until it is realized or encountered. This is why nearly all vehicles have a
temperature or oil gauge. Detecting an abnormally high temperature or oil leak while op-
erating the engine of any vehicle is difficult for an average operator while driving, so we
provide them with an additional means to recognize an unsafe condition, reducing overall
risk of an engine failure or fire. In the case of an autonomous machine operating in a field
or orchard, it is similarly difficult for a bystander to detect a malfunctioning object detec-
tion sensor, so the “detectability” part of risk assessment will suggest that the engineer
must account for the potential risk through redundancies or fail-safe actions in their object
detection design.
Another factor often considered in risk assessment methods, particularly with mechan-
ical equipment, is “controllability” (De Gelder et al., 2021). Controllability is a measure of
how well a human operator can “control” a machine if the hazard or failure being analyzed
is realized. A simple example would be a situation in which a regular passenger vehicle for
on-road use is being driven, if one compares the incident-related “controllability” risk of a
catastrophic tire blowout versus the failure of an electronically actuated rear trunk latch.
A tire failure will create much greater risk based on the controllability of the vehicle if it
fails, versus a latch malfunction. In the case of an autonomous machine, if controllability
is difficult when a machine detects an obstacle or unknown condition, controllability risk
might be alleviated by simply stopping the machine’s movement until the unsafe or un-
known condition can be remedied.
Data Needs for Risk Assessment
Table 1 provides additional background on several of the common risk assessment
methods used by engineers, including the name of the method, cited literature, method
description, and types of data needed to use the method. The table only provides a sampling
of methods. Note that sometimes individual companies or organizations develop proprie-
tary risk assessment methods, which may be rooted in methodologies shown in the table.
Similarly, software companies whose products can be used to support risk assessment
methods often develop their unique renditions of software. However, these are often based
on these same concepts and methods with slight adjustments, additions, or terminology.
As table 1 shows, a significant quantity and diversity of data are needed to inform any
risk assessment process in an accurate and meaningful way. In the case of mature designs
of traditional machines (such as a common, non-autonomous farm tractor with few auto-
mated features), it is possible to predict or estimate the probabilities of machine or human
failure, such as a rollover or other type of event. This is because engineers have access to
over 100 years of historical injury data from tractor and machine rollover incidents,
runovers, or component entanglements collected both internally as well as through organ-
izations like universities, research groups, government, and others. We have similar data
for many other types of agricultural machines that involve a human operator at the controls
of the machine.
In addition, the physics of the design for a traditional machine and its known hazards
are often such that if an engineer knows the mass of a machine, the location of its center of
gravity, the dimensions of its baseline of stability, the velocity during operation, the load
being carried or pulled, the terrain on which the machine is being operated (slope, sur-
face/soil conditions, obstacles, etc.), the tire condition, and other factors, it is possible to
mathematically predict the occurrence of an event such as a rollover potential given the


## Page 5

31(4): 311-324
315
combination of parameters. In terms of the outcome or severity of an event, we can also
estimate and quantify the outcome if a 6000 kg tractor rolls on top of a person. The severity
of the resulting event is highly likely to be catastrophic and result in death.
The data required for these risk assessment exercises that are completed in the design
process is important and can come (as the above example shows) from historical incidents
and epidemiological analyses that have statistically identified risk factors. In the case of
manufacturers, often, known incidents have been investigated over time, resulting in “in-
house” data and collective knowledge and experience that engineers can use internally as
a data source in future risk assessment.
As we consider both the probability of exposure/failure as well as the severity, we also
need to think beyond human injuries or fatalities. Object detection with autonomous and
highly automated machines is important, but there are other potential categories of poten-
tial incidents and losses to be considered in risk assessment. Table 2 shows some of these.
Risk assessment activities are often best performed in the early phases of design and
conceptualization of machines, processes, or components. It is highly preferred that engi-
neers work to design systems that eliminate or reduce hazards and exposure to hazards
versus trying to later protect users from previously unforeseen hazards through strategies
Table 1. Common risk assessment methods used in engineering with data requirements.
Risk Assessment Method
Brief Description
Types of Data Required
Qualitative Risk
Assessment
(Tiusanen, 2017)
Involves subjective evaluation of
risks based on expert judgment,
experience, and intuition.
Expert opinions, historical
data, industry standards
Failure Mode and Effects
Analysis (FMEA)
(Mikulak et al., 2017)
Identifies potential failures in a
system and assesses their impact on
the basis of likelihood and severity.
System specifications, probabilities,
and associated severity levels for
failures/hazard encounters – some
FMEA efforts include detectability
measures as a factor
Hazard and Risk
Assessment (HARA)
(De Gelder et al., 2021)
Identifies, evaluates, and prioritizes
risk for system, similar to FMEA,
adding controllability assessment.
Hazard, exposure, severity
estimates, as well as the
degree of controllability
Hazard and Operability
Study (HAZOP)
(Crawly and Tyler, 2015)
Identifies hazards and
operability issues in complex
process-oriented facilities.
Process diagrams, operational
data, safety standards, team
knowledge and input
Fault Tree Analysis (FTA)
(Yazdi et al., 2023)
Uses tree diagrams and failure
probabilities to understand the
causes, critical relationships, and
probabilities of high-level failures.
System specifications, failure rates,
models that describe the
relationships and interplay between
system components and processes
Event Tree Analysis (ETA)
(Ferdous et al., 2009)
Uses tree diagrams to analyze
the potential outcomes
of an initiating event.
Event data, probability
data, impact data
Bow-Tie Analysis
(Ferdous et al., 2012)
Visualizes the cause-and-effect
relationships of a hazardous event.
Hazard data, barrier data,
consequence data
Monte Carlo Simulation
(Rezaie et al., 2007)
Uses statistical models and
probability distributions to
statistically evaluate the overall
probability of certain outcomes.
Probability distributions, numerical
data, statistical models
Risk Matrix
(Ristić, 2013)
Uses a simple matrix to
rank risks based on their
severity and likelihood.
Risk data, severity ratings,
likelihood ratings
SWIFT (Structured
What-If Technique)
(Card et al., 2012)
Uses structured brainstorming
process of experts/designers/users
to identify potential risks.
Expert opinions, process data,
system specifications


## Page 6

316
Journal of Agricultural Safety and Health
that might be far less effective—such as warnings, reliance on personnel training, or re-
quirements of PPE (Barnett, 2020).
Because of the desirability of doing risk assessment early, those who lead risk assess-
ment activities must be intimately familiar with all aspects of the machine, its parts, the
function and limitations of each component or subsystem, and how the system works. It is
also vital that engineers have a basic understanding of how, where, and in what conditions
their product will be deployed and used by the customer or others who might encounter it,
such as repair and maintenance/service personnel. The risk assessment method that was
shown previously in table 1, known as HAZOP, shows the importance of intimate
knowledge when complex processes and the mass flow of inputs, products, or data are
involved and requires a team working together to analyze potential operability problems
and to evaluate the causes and consequences associated with a process or system deviating
from its normal and designed-for operation.
Summarizing, keys to good risk assessment as we consider the various methods, such
as those shown in table 1 and many other methods:
1. Risk assessment must be done early and fully integrated into design.
2. Risk assessment is often best done by imaginative, multidisciplinary teams with deep
knowledge and understanding of all aspects of design as well as the real-world use of a
product or system. This includes machine/component/system knowledge as well as hu-
man operator understanding and foreseeable uses and misuses.
3. Data for conducting robust risk assessment processes is often required but not always
available and can sometimes be supplemented with modeling, simulation, and imagina-
tive thinking to predict how and how frequently a product might fail or be misused and
what the consequences might be.
Table 2. Types of losses and consequences and examples of possible harm with autonomous agricultural
machines.[a]
Category
Example
Injury/damage to livestock,
wildlife, pets, etc.
A dairy cow is injured because of contact with
an autonomous feeding or milking system.
Property damage to
surrounding structures
An autonomous tractor snags a fence or the frame
of a storage shed door, causing property damage
Fire
(Tomašková et al., 2020)
An autonomous harvester catches fire in the
field due to a fuel or oil hose/line failure
Environmental damage/contamination
(Tegtmeier and Duffy, 2004)
A highly automated sprayer or manure applicator rolls
in the field, spilling contaminants into soil or water
Downtime (economic) loss
(Kipriyanov et al., 2019)
A software or hardware system failure occurs during
busy planting or harvest season and cannot be
repaired in a timely way, causing costly delays
Data-related harm caused by
data loss, misuse, error, etc.
(Freyhof, 2022)
Data is lost or a machine is misdirected
during a system crash, failure, or
deliberate cybersecurity incident
Reputational risk (for operator,
manufacturer, product sector)
(Larkin, 2022)
An autonomous machine consistently has
difficulties based on the design of hardware or
software, creating a negative perception that impacts
attitudes and buying decisions for all stakeholders
[a] Categories are not shown to reflect any level of quantified probability or severity.


## Page 7

31(4): 311-324
317
Lack of Data and Recommended Solutions for
Risk Assessment in Novel Machinery Design
When SaferAg 1.0 was completed in 2022, little or no injury and fatality surveillance
data were available to describe incidents involving autonomous agricultural machines in
the U.S. To date, this lack of data has created challenges in applying conventional risk
assessment methods, necessitating the use of alternative data and information sources.
However, Lincoln et al. (2025) described recent revisions to the Occupational Injury and
Illness Classification System (OIICS) that recognize changes in agricultural technology,
including potential incidents involving robots and autonomous machines. The OIICS
changes show promise in facilitating better tracking of injuries involving these new ma-
chine forms. Over time, these changes will add to the data used in the risk assessment
phases of machine design.
In the future, there will most likely be incidents that occur as new machine forms like
robots and autonomous mobile equipment are deployed into agricultural production situa-
tions. These incidents and the details that surround them may or may not end up being
disclosed and fully known, but if they are, it will allow engineers to inform future-looking
risk assessments. In the event of an incident that results in significant injury, loss of life,
property damage, or other loss, it is foreseeable that the manufacturer will be made aware
of the incident, as is the case with similar events that now occur with traditional equipment.
This will rely on the development of future surveillance efforts similar to what we now
have to monitor traditional farm machine injuries and deaths. Equipment manufacturers
may also have their data from internal product safety investigations and actions.
So, for the foreseeable future, we are unlikely to have traditional surveillance data from
incidents to fully inform risk assessment processes with novel forms of farm technology.
Data collection protocols and incident coding systems are evolving, but it will take years,
if not decades, for incidents to show up in these data. It is possible that the industry could
agree to share the incident data that it collects through internal investigations in a way that
removes all brand names, company specifics, and other identifiers from the dataset to pro-
tect the reputation of the company and to disconnect the data from possible liability-related
risk. Such an approach has evolved over decades for incidents involving air travel and
flights to allow aircraft manufacturers, regulators, and other interested entities to share in-
cident data as is outlined by the National Academies of Sciences, Engineering, and Medi-
cine, and the Aviation Safety Assurance Committee (2018).
The background that has been presented in this section on risk assessment, the gaps in
data availability, and specific data needs for new forms of highly automated and autono-
mous equipment is the information that had set the stage for the recommendations pre-
sented in the companion paper SaferAg—Risk Assessment, Data, Design Standards, and
Regulation: Needs and Recommendations by Shutske et al. (2025).
Engineering Design Standards
Basic Information About Standards
Engineering standards are documents published (promulgated) and maintained by engi-
neering organizations such as ASABE, SAE, ASME, and others. There are also national
and international standards organizations such as ANSI and ISO. These organizations pro-
vide the structure and administrative support systems that facilitate a “consensus” devel-
opment process and act as a hub, drawing experts and stakeholders to participate in the
consensus-based processes required to develop a standard (Marpet, 1998). These


## Page 8

318
Journal of Agricultural Safety and Health
developmental processes include in-person and virtual meetings, working group sessions,
individual analysis, travel, and considerable commitment of time by experts from all sec-
tors. There are several benefits associated with engineering standards. According to the
National Institute of Standards and Technology (NIST, 2022), these documents:
•
Provide a common language to measure and evaluate performance,
•
Make interoperability of components made by different companies possible, and
•
Protect consumers by ensuring safety, durability, and market equity.
Standards development is detailed work that involves a wide range of individuals and
the groups that they represent. This ideally includes product end-users, engineers, scien-
tists, university faculty, personnel who represent manufacturers, government agency per-
sonnel, trade association representatives, non-government organization personnel, and oth-
ers. Standards originate from an identified need (ISO, 2023a). Over time, these documents
are drafted, circulated, added to, and continuously evolve to encompass the necessary view-
points that allow for consensus. Original standards and their revisions take considerable
time to emerge and develop. The consensus process requires multiple drafts and iterations,
and it is not unusual for a standard to take multiple years to go from the initial need iden-
tification and conceptualization to the final draft (ISO, 2023b).
Most engineering design consensus standards are “voluntary” in their original form.
That said, there are numerous examples of standards being incorporated into laws, statutes,
and regulatory standards. To show the connection and value between research that informs
standards and regulations, a study by Ramirez et al. (2016) found a direct statistical asso-
ciation between the state-level regulatory alignment with farm lighting and marking poli-
cies and the ASABE standard 279 (ASABE, 2013) and highway crash rates. Their analysis
showed that modest efforts to bring individual state highway regulations in closer align-
ment with the ASABE standard could result in double-digit reductions in crash rates. These
and other data collected over time supported the move by the federal government in 2012
through the development of the Agricultural Machinery Illumination and Safety Act. This
federal law now integrates ASABE standard S279.14 into the federal regulations of the
National Highway Traffic Safety Administration for farm tractors and many forms of ma-
chinery manufactured on or after 22 June 2017 (NHTSA, 2016). This alignment of re-
search, engineering standards, and harmonized regulatory efforts has the potential to ben-
efit all involved, including regulators, agricultural machinery operators, the motoring pub-
lic, equipment dealers, manufacturers, and others.
Another example is rollover protective structures on tractors. Work by Hard and Myers
(2011) had shown the efficacy of rollover protective structures (ROPS) to prevent tractor
rollover deaths over a period of more than two decades. ROPS design is guided by consen-
sus standards that include SAE J1194, Rollover Protective Structures (ROPS) for Wheeled
Agricultural Tractors (SAE, 2016). But similar to the machinery lighting and marking
standard and the connection between an engineering standard and a regulation (regulatory
standard), OSHA 1928.51—Roll-over protection structures (ROPS) for tractors used in
agricultural operations requires that employees operating tractors manufactured after
25 October 1976 be protected with a standard-compliant ROPS and seatbelt on the tractor
(OSHA, 1976).
Existing and Forthcoming Standards and Revisions
Previous sections of this article have explored risk assessment as a process and the im-
portance of standards as a key tool used by engineers and other stakeholders to improve


## Page 9

31(4): 311-324
319
safety for products and to inform other needs, including regulation, in cases where there is
an identified need for policy. Several existing engineering design standards assist in direct-
ing the efforts of engineers designing highly automated and autonomous agricultural ma-
chinery. A few of these examples are shown in table 3 which also serves the purpose of
categorizing different types of standards that are connected to safety as type A, B, or C.
Additional information on the integration of standards, risk assessment methods, and
practices being used currently by industry engineers during product design is found in
Shutske and Sandner (2023). This study, involving a survey of engineers designing auton-
omous agricultural machinery, showed that the use of newer standards that indicate the
need for specific risk assessment methods is limited in part because the industry-based
efforts in autonomy or highly automated machine forms is such a new area. The authors
discuss the fact that many of the risk assessment methods that are prescribed by these
standards are currently imperfect, largely because they specify the use of historical data
(which do not yet exist). And, through their scope, some of the potential non-human targets,
such as animals, structures, or environmental resources, and others previously mentioned
in table 2 are sometimes explicitly excluded from the scopes of several important standards.
Since the 2022 SaferAG conference, the industry and other stakeholders now have ac-
cess to a significant and highly pertinent standard revision–ISO 18497, a type B-1 standard
(ISO, 2024). This standard is titled “Agricultural machinery and tractors—Safety of par-
tially automated, semi-autonomous, and autonomous machinery.” The standard represents
a significant step forward for the industry. It has four parts. The original version of ISO
18497, published in 2018, had one part and was 18 pages long (ISO, 2018). One highly
notable change to the standard is that it provides a more robust and complete set of “terms
used for combinations of functions and modes,” a feature that was described as lacking in
past published and agreed-upon definitions in the explanatory work by Shutske and Sand-
ner (2023). An overview of the four parts of the 2024 version of ISO 18497 is shown in
table 4.
Discussion and Issues – Standards & Risk Assessment
From an engineering design perspective, with new autonomous and highly automated
agricultural machines, risk assessment and consensus-based engineering standards focused
on safety are tightly intertwined (Etherton, 2007). As mentioned, many engineering stand-
ards that address the safety of these machines incorporate or recommend techniques for
Table 3. Standards by type that include risk assessment for traditional and new agricultural machinery
forms.
Type of
Standard
Description
Examples
Type-A
(Basic safety
standards)
Standards give basic concepts, principles
for design, and general aspects that can
apply to machinery.
ISO 12100: Safety of machinery -
Basic concepts, general principles
for design. (ISO, 2010)
Type-B
(Generic safety
standards)
Standards deal with one safety aspect,
or a type of safeguard used across a
wide range of machinery. Type-B
standards are further divided into
two categories: B1 (“safety aspects”)
and B2 (“safeguards”).
B1: ISO 13849-1: Safety of machinery -
Safety-related parts of control systems.
B2: ISO 13857: Safety of machinery -
Safety distances to prevent hazard
zones being reached by upper
and lower limbs. (ISO, 2012)
Type-C
(Machine safety
standards)
Standards deal with detailed safety
requirements for a particular
machine or group of machines.
ISO 4254-9: Agricultural machinery -
Safety - Part 9: Rotary disc and drum
mowers and flail mowers. (ISO, 2021)


## Page 10

320
Journal of Agricultural Safety and Health
conducting risk assessment as part of the design process (Shutske and Sandner, 2023).
As has been discussed, if we expect robust risk assessment processes as part of safe design,
we need accurate data to inform variables such as probabilities of hazard exposure. The
ISO 18497 standard starts in its “safety requirements and protective or risk reduction
measures” section 4.1, indicating the importance of evaluating risk reduction measures in
ways consistent with ISO 12100:2010 titled Safety of machinery—General principles for
design—Risk assessment and risk reduction. The referenced ISO 12100 standard relies
heavily on historical data sources, representing the dilemma of not having such data on
novel machine designs. This is a central issue addressed in Shutske et al. (2025), in which
recommendations are presented for types and methods of data that could be collected in
the development, prototyping, and early use phases to document exposures and incursions
into defined hazard zones.
Engineering consensus standards represent the “best of” in contemporary thinking for
engineering design and practice applied to agricultural technology and machine design
(Murphy and Yates, 2009). Because of the nature of the consensus development processes
used to create standards, these documents incorporate the existing knowledge, ideas, data,
and practices of expert users, designers, researchers, and other critical and affected stake-
holders (Lindøe and Baram, 2019). Yet, standards are not perfect. They take considerable
time to develop and to be published (promulgated) into an officially approved and acces-
sible format where they will be found and used (Marpet, 1998). Conversely, advancements
in technology are occurring at an accelerating pace.
The presence of standards is not always known or understood by those who design ma-
chines and other technologies. Often, non-engineers working on design projects are not
exposed to standards via their formal education or experiential learning, even though they
Table 4. The ISO 18497 standard’s content (ISO, 2024).
Part Title
Purpose
Major Headings in the Standard Part
ISO 18497-1:
Machine design
principles and
vocabulary
Specifies principles for design
of agricultural machinery and
tractors used in agricultural
applications and that have
partially automated,
semi-autonomous and
autonomous functions.
General information
Design principles (for safety and risk
reduction), including operator presence,
states/modes, etc.
Visual and audible alarms
Labeling and identification
Information for use
ISO 18497-2:
Design principles for
obstacle protection
systems
Specifies principles for
the design of obstacle
protective systems.
General information
Design principles for obstacle detection
including detection, operational limits,
visual/audible indications, etc.
Monitoring and handling faults and failures
Labeling and identification
Information for use
ISO 18497-3:
Autonomous
operating zones
Specifies principles for the design
of agricultural machinery and
tractors utilizing systems
(perception, supervisory, or other)
to prevent unintended excursions
beyond the boundary of the
autonomous operating zone.
General information
Design principles for boundary detection,
operational limits, monitoring, faults, and
failures
Information for use
ISO 18497-4:
Verification methods
and validation
principles
Specifies principles for
verification methods and
validation principles to ensure
appropriate level of safety.
General information
Verification methods
Validation principles


## Page 11

31(4): 311-324
321
may be engaged in engineering-related tasks. In many cases, commonly used engineering
design standards must be purchased from the organization that developed and published
them (ISO, ASABE, ANSI, etc.). The costs for a complete set of standards that apply to a
specific type of agricultural machine can be prohibitive, especially for smaller companies
or individual design engineers. These and other factors sometimes lead to differential
standard access and usage issues. In SaferAg 2.0, a similar workshop held in December
2024, organizers led a comprehensive standards overview professional development ses-
sion for participants, addressing many of the issues outlined here.
Likewise, it is probable that as new forms of agricultural equipment become more com-
mon, we will see efforts by governmental agencies or individual elected officials to regu-
late highly automated or autonomous agricultural machines in the U.S. (California OSHA
Standards Board, 2023) and other countries worldwide (Rainbow, 2021). The chance of a
strong push toward regulation is greater if there are one or more high-profile or highly
“memorable” incidents that result in significant loss (injury, death, property loss, environ-
mental damage, etc.) from one of these new agricultural machine forms. It is foreseeable
that an autonomous or robotic agricultural machine incident could engender a higher de-
gree of “outrage,” a risk perception, and communication consideration based on several
factors as identified in the classical work in risk communication by Sandman (1989).
In the same way that smaller companies or people who practice product design and
development may not be fully aware of standards, the individuals and groups who are in-
volved in regulatory efforts or policy development may be even less likely to be aware of
the existence of pertinent engineering standards. There are examples and cases of excellent
engineering standards that have pointed a path toward informed and meaningful public
policy (Ma et al., 2022; Seneff, 2017). In cases where individuals, groups, or society felt
the need to use regulation as an intervention method, those involved were able to use the
past work that went into standards-making, leveraging state-of-the-art knowledge gathered
and curated through research and scientific and engineering data that are deeply embedded
within standards. Previous examples connected to machinery lighting and marking and
ROPS are examples.
So, standards must serve as bedrock for all aspects of safety. This includes design, ap-
propriate machine use, and all aspects of a product’s deployment in a workplace or market,
including in situations where specific categories of products eventually become regulated.
Often, safety-related standards specify risk assessment methods and processes that the
design engineer and manufacturer need to consider to improve the safety of a new machine.
However, an important issue is that these types of standards can significantly lag behind
new technology developments, inventions, and the introduction of products into the mar-
ketplace. To some extent, this will always be a given because of the careful and deliberate
pace with which standards are developed and promulgated. The creation of good standards
takes time. Whereas there is competitive pressure and a strong human desire to push inno-
vation on new equipment forms as quickly as possible (Manu, 2010).
Another issue that deserves further consideration in the future is that historical risk data
is needed to inform the policies and actuarial practices of insurance companies and others
who provide financial means of risk management to support those who purchase and use
new technologies (Blakesly and Yallop, 2020). For entities like insurance companies, it is
difficult to set rates, predict future losses (property, injury, lost time, etc.), and operate an
insurance business without the historical data that actuaries and underwriters use (Hassani,
2020). Those in the insurance business will almost always want the premiums for specific


## Page 12

322
Journal of Agricultural Safety and Health
coverages to be greater than what you will be paying out for obvious business reasons to
account for sales, administrative, and other costs, as well as desired profit margins. This
seems an important area for future research, along with other economic considerations re-
lated to the risks, costs, and benefits of autonomous and highly automated agricultural ma-
chines.
Conclusion
Highly automated and autonomous agricultural machines present new safety challenges
that require rigorous and data-informed risk assessment as well as the systematic consid-
eration and application of engineering design and safety standards. Risk assessment and
standards application are best completed early in the design, development, and prototyping
phases with any machine or product. There is also a clear need that these critical tools be
used and fully understood by all stakeholders. This includes engineers and manufacturers,
regulators, and others who share a responsibility in end-user and public safety. We lack
long-term incident data for these novel technologies as key input to risk assessment pro-
cesses, which is what calls for creative interim solutions that are presented in the compan-
ion paper (Shutske et al., 2025). This includes early deployment monitoring and exposure
data collection as well as appropriate ways to share data. Building awareness of standards,
improving access, including for smaller companies and regulators, and aligning standards
with emerging risks will help ensure that innovation does not outpace safety. Continued
collaboration across industry, academia, and regulatory/policy arenas can lead to machines
that deliver needed productivity gains without increasing the burden of injuries, property
damage, or other future losses.
References
ASABE Standards. (2013). S279.17: Lighting and marking of agricultural equipment on highways. St.
Joseph, MI: ASABE.
Barnett, R. L. (2020). On the safety hierarchy and hierarchy of controls. Am. J. Mech. Eng., 8(2), 61-68.
Blakesley, I. R., & Yallop, A. C. (2019). What do you know about me? Digital privacy and online
data sharing in the UK insurance sector. J. Inf. Commun. Ethics Soc., 18(2), 281-303.
https://doi.org/10.1108/jices-04-2019-0046
California OSHA Standards Board. (2023). OSHSB board meeting hearing - March 2023. Retrieved
from https://videobookcase.org/oshsb/2023-03-16/
Card, A. J., Ward, J. R., & Clarkson, P. J. (2012). Beyond FMEA: The structured what-if technique
(SWIFT). J. Healthc. Risk Manag., 31(4), 23-29. https://doi.org/10.1002/jhrm.20101
Crawley, F., & Tyler, B. (2015). HAZOP: Guide to best practice. Elsevier.
de Gelder, E., Elrofai, H., Saberi, A. K., Paardekooper, J. P., den Camp, O. O., & de Schutter, B.
(2021). Risk quantification for automated driving systems in real-world driving scenarios. IEEE
Access, 9, 168953-168970. https://doi.org/10.1109/ACCESS.2021.3136585
Etherton, J. R. (2007). Industrial machine systems risk assessment: A critical review of concepts and
methods. Risk Anal., 27(1), 71-82. https://doi.org/10.1111/j.1539-6924.2006.00860.x
Ferdous, R., Khan, F., Sadiq, R., Amyotte, P., & Veitch, B. (2009). Handling data uncertainties in
event tree analysis. Process Saf. Environ. Prot., 87(5), 283-292.
https://doi.org/10.1016/j.psep.2009.07.003
Ferdous, R., Khan, F., Sadiq, R., Amyotte, P., & Veitch, B. (2012). Handling and updating uncertain
information in bow-tie analysis. J. Loss Prev. Process Ind., 25(1), 8-19.
https://doi.org/10.1016/j.jlp.2011.06.018


## Page 13

31(4): 311-324
323
Freyhof, M. (2022). Cybersecurity of agricultural machinery: Exploring cybersecurity risks and
solutions for secure agricultural machines. MS thesis. University of Nebraska-Lincoln.
Haimes, Y. Y. (2009). On the complex definition of risk: A systems-based approach. Risk Anal.,
29(12), 1647-1654. https://doi.org/10.1111/j.1539-6924.2009.01310.x
Hard, D. L., & Myers, J. R. (2011). Adoption of rollover protective structures (ROPS) on U.S. farm
tractors by state: 1993-1995, 2001, and 2004. J. Agric. Saf. Health, 17(2), 157-172.
https://doi.org/10.13031/2013.36499
Hassani, H., Unger, S., & Beneki, C. (2020). Big data and actuarial science. Big Data Cogn. Comput.,
4(4), 40. https://doi.org/10.3390/bdcc4040040
ISO. (2010). ISO 12100: Safety of machinery - General principles for design - Risk assessment and
risk reduction. Geneva, Switzerland: ISO.
ISO. (2012). ISO 13849-2: Safety of machinery -Safety-related parts of control systems - Part 2:
Validation. Geneva, Switzerland: ISO.
ISO. (2018). ISO 18497:2018: Agricultural machinery and tractors - Safety of highly automated
agricultural machines - Principles for design. Geneva, Switzerland: ISO.
ISO. (2021). ISO 4254-9: Agricultural machinery - Safety - Part 9: Rotary disc and drum mowers and
flail mowers. Geneva, Switzerland: ISO.
ISO. (2023a). Developing standards. Retrieved from https://www.iso.org/developing-standards.html
ISO. (2023b). Stages and resources for standards development. Retrieved from
https://www.iso.org/stages-and-resources-for-standards-development.html
ISO. (2024). ISO 18497: Agricultural machinery and tractors - Safety of partially automated, semi-
autonomous and autonomous machinery - Parts 1-4. Geneva, Switzerland: ISO.
Kipriyanov, F. A., Medvedeva, N. A., & Medvedeva, S. V. (2019). Ensuring the operational reliability
of the tractor fleet. IOP Conf. Ser.: Earth Environ. Sci., 315(6), 062015.
https://doi.org/10.1088/1755-1315/315/6/062015
Larkin, J. (2022). Strategic reputation risk management in the digital era. London: Routledge.
Lincoln, J., Gorucu, S., Khorsandi, F., Aby, G. R., Elliott, K. C., Shutske, J., & Issa, S. F. (2025).
Occupational Safety Research Needs in the Field of Robotics and Autonomous Machines in
Agriculture. J. Agric. Saf. Health, 31(3), 217-230. https://doi.org/10.13031/jash.16216
Lindøe, P. H., & Baram, M. S. (2019). The role of standards in hard and soft approaches to safety
regulation. In O. E. Olsen, K. Juhl, P. H. Lindøe, & O. A. Engen (Eds.), Standardization and risk
governance: A multi-disciplinary approach (1st ed.). London: Routledge.
https://doi.org/10.4324/9780429290817
Ma, Y., & Rong, Y. (2022). Design standards and regulations. In Senior design projects in mechanical
engineering: A guide book for teaching and learning (pp. 361-420). Cham, Switzerland: Springer.
https://doi.org/10.1007/978-3-030-85390-7_16
Manu, A. (2010). Disruptive business: Desire, innovation and the re-design of business. Gower
Publishing, Ltd.
Marpet, M. I. (1998). An ethical issue in voluntary-consensus-standards development: A decision-
science view. J. Bus. Ethics, 17(15), 1701-1716. https://doi.org/10.1023/A:1006088006735
Mikulak, R. J., McDermott, R., & Beauregard, M. (2017). The basics of FMEA. CRC Press.
Murphy, C. N., & Yates, J. (2009). The International Organization for Standardization (ISO): Global
governance through voluntary consensus. London: Routledge.
National Academies of Sciences, Engineering and Medicine & Aviation Safety Assurance Committee.
(2018). In-time aviation safety management: Challenges and research for an evolving aviation
system. Washington, DC: National Academies Press.
NHTSA. (2016). Lighting and marking on agricultural equipment - Machinery illumination safety.
National Highway Traffic Safety Administration. Retrieved from
https://www.federalregister.gov/documents/2016/06/22/2016-14571/lighting-and-marking-on-
agricultural-equipment
NIST. (2022). Standards and measurements. Retrieved from https://www.nist.gov/services-
resources/standards-and-measurements


## Page 14

324
Journal of Agricultural Safety and Health
OSHA. (1976). Part 1928.51: Roll-over protective structures (ROPS) for tractors used in agricultural
operations. US DOA, OSHA.
Popov, G., Lyon, B. K., & Hollcroft, B. D. (2016). Risk assessment: A practical guide to assessing
operational risks. Wiley & Sons.
Rainbow, R. (2021). Code of practice - Agricultural mobile field machinery with autonomous
functions in Australia. Grain Producers Australia, Tractor and Machinery Association, Society of
Precision Agriculture Australia. Retrieved from
https://www.grainproducers.com.au/codeofpractice
Ramirez, M., Bedford, R., Wu, H., Harland, K., Cavanaugh, J. E., & Peek-Asa, C. (2016). Lighting
and marking policies are associated with reduced farm equipment-related crash rates: A policy
analysis of nine Midwestern US states. Occup. Environ. Med., 73(9), 621-626.
https://doi.org/10.1136/oemed-2016-103672
Rezaie, K., Amalnik, M. S., Gereie, A., Ostadi, B., & Shakhseniaee, M. (2007). Using extended
Monte Carlo simulation method for the improvement of risk management: Consideration of
relationships between uncertainties. Appl. Math. Comput., 190(2), 1492-1501.
https://doi.org/10.1016/j.amc.2007.02.038
Ristić, D. (2013). A tool for risk assessment. Saf. Eng., 3(3), 121-127.
https://doi.org/10.7562/SE2013.3.03.03
SAE. (2016). SAE J1194 - Rollover Protective Structures (ROPS) for Wheeled Agricultural Tractors.
Retrieved from https://elibrary.asabe.org/abstract.asp?aid=25285&t=3&redir=&redirType=
Sandman, P. M. (1989). Hazard versus outrage in the public perception of risk. In V. T. Covello, D. B.
McCallum, & M. T. Pavlova (Eds.), Effective risk communication: The role and responsibility of
government and nongovernment organizations (pp. 45-49). Boston, MA: Springer.
https://doi.org/10.1007/978-1-4613-1569-8_6
Seneff, M. (2017). Q&A on AMISA: An industry collaboration that became law. Resour. Mag.,
24(6), 16.
Shutske, J. M., Issa, S. F., Johnson, T., Khorsandi, F., Pate, M. L., Gorucu, S.,... Versweyveld, J.
(2025). SAFER AG – Risk assessment, data, design standards, and regulation: Needs and
recommendations. J. Agric. Saf. Health, 31(1), 1-13. https://doi.org/10.13031/jash.15855
Shutske, J. M., Sandner, K. J., & Jamieson, Z. (2023). Risk assessment methods for autonomous
agricultural machines: A review of current practices and future needs. Appl. Eng. Agric., 39(1),
109-120. https://doi.org/10.13031/aea.15281
Tegtmeier, E. M., & Duffy, M. D. (2004). External costs of agricultural production in the United
States. Int. J. Agric. Sustain., 2(1), 1-20. https://doi.org/10.1080/14735903.2004.9684563
Tiusanen, R. (2017). Qualitative risk analysis. In N. Moller, S. O. Hansson, J.-E. Holmberg, & C.
Rollenhagen (Eds.), Handbook of safety principles (pp. 463-492).
https://doi.org/10.1002/9781119443070.ch21
Tomašková, M., Matisková, D., & Balážiková, M. (2020). Case study to determine the causes of fire
in agriculture. Adv. Sci. Technol. Eng. Syst. J., 5(5), 11–15. https://doi.org/10.25046/aj050502
Yazdi, M., Mohammadpour, J., Li, H., Huang, H.-Z., Zarei, E., Pirbalouti, R. G., & Adumene, S.
(2023). Fault tree analysis improvements: A bibliometric analysis and literature review. Qual.
Reliab. Eng. Int., 39(5), 1639-1659. https://doi.org/10.1002/qre.3271

