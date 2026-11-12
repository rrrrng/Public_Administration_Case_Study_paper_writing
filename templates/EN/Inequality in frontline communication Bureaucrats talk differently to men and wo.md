# Inequality in frontline communication Bureaucrats talk differently to men and wo

## Page 1

Journal of Public Administration Research and Theory, 2026, 00, 1–15
https://doi.org/10.1093/jopart/muaf036
Advance access publication 27 December 2025
Article
Inequality in frontline communication: bureaucrats talk
differently to men and women
Laurin Friedrich1,2,* and Steffen Eckhard2
1Institute of Political Science, University of Duisburg-Essen, Duisburg 47057, Germany
2Chair of Public Administration and Public Policy, Zeppelin University, Friedrichshafen 88045, Germany
*Corresponding author: Institute of Political Science, University of Duisburg-Essen, Forsthausweg 2, 47057 Duisburg, Germany. Email: laurin.friedrich@
uni-due.de.
Abstract
While gender biases in public service delivery are well-established, we still lack empirical insights on the underlying behavioral micro-mechanisms.
This article contributes toward closing this perennial gap by investigating gender differences in the complexity and emotionality of verbal
bureaucrat-client communication. We build on a dataset comprising 154 dialogs recorded across different local public services in Germany. Com­
bining rule-based and machine learning classification, we analyze differences in verbal administrative communication across 20,000 utterances.
We find no association between bureaucrats’ gender and their communication. Conversely, clients’ gender yields a significant difference, with
officials communicating more complexly and emotionally when interacting with male clients. No differences prevail for gender-matching. As the
first study to systematically examine implicit (gender) biases in bureaucrats’ communication, the article advances our existing understanding of
the micro-mechanisms of administrative inequality: The findings contradict expectations from gender socialization theory, they confirm expectations
linked to gender stereotypes, and they challenge the idea that in-group settings reduce stereotypical biases at the level of communication.
Key words: public service encounters; gender biases; administrative inequality; natural language processing
Introduction
Gender differences in public service delivery are well docu­
mented across a large number of public service domains, such
as health, social services, education and justice (e.g., Assouline
and Gilad 2022; Bisgaard and Pedersen 2022; Bontrager, Bar­
rick, and Stupi 2013; Fagerlund 2021; McCrea 2021; Kullberg
2005). Also beyond gender, a wealth of studies explore how
unequal administrative treatment can perpetuate systemic ineq­
uities, hinder the fair and effective delivery of essential services,
and ultimately undermine trust in public institutions (Einstein
and Glick 2017; Grohs, Adam, and Knill 2016; Hemker and
Rink 2017; Jilke, Van Dooren, and Rys 2018; Olsen, Kyhse‐
Andersen, and Moynihan 2022; Raaphorst et al. 2025;
Thomann, James, and Deruelle 2025; Tummers et al. 2015).
Less well understood are the actual behaviors of bureaucrats
toward citizens that sustain administrative inequality.
First, the street-level bureaucracy literature offers various
conceptualizations of the behavioral patterns in frontline work,
such as coping (Tummers et al. 2015) or different enforcement
styles (de Boer 2019). These, however, are mostly descriptive
and used to examine bureaucrats’ attitudes and perceptions
but not to systematically study administrative behaviors (Mose­
ley and Thomann 2021). Second, a large literature on bureau­
cratic discrimination tests whether biases induced by citizen
characteristics lead to unequal treatment (e.g., Adam et al.
2021; Assouline, Gilad, and Ben-Nun Bloom 2022; Einstein
and Glick 2017; Hemker and Rink 2017; Thomann and Rapp
2018). This research is dominated by experimental methods
and analyses of administrative records, but it lacks authentic
direct insights on (interpersonal) bureaucrat–client interactions.
Lastly, although representative bureaucracy literature recently
shifted from organizational analyses to individual-level studies
(Eckhard 2021; Headley and Wright 2020; McCrea 2021;
Nicholson-Crotty et al. 2016), this field still has a “laser-like”
focus on administrative outcomes, while the underlying behav­
iors among bureaucrats remain usually unobserved (Meier
2023, p. 15).
In this article, we address these gaps with a focus on bureau­
crats’ behavior during personal interactions with citizens,
which mediates the relationship between biases and unequal
administrative treatment in at least three important ways.
Firstly, when making service decisions during the encounter,
systematic differences in bureaucrats’ behavior may directly
generate discriminatory outcomes (Lipsky [1980] 2010;
Maynard-Moody and Musheno 2000). Secondly, they may
create unequal burdens to formally accessing services (Bell and
Smith 2022; Jilke, Van Dooren, and Rys 2018). And thirdly,
irrespective of its material repercussions, bureaucrats’ inapt
behavior during an encounter may have negative effects on the
public legitimacy of the entire political system (Hansen 2022;
Kumlin and Rothstein 2005).
Specifically, we study the verbal communication during
encounters, which recent scholarship expects to profoundly
define the inner dynamics and outcomes of bureaucrat–client
interactions (Bartels 2013; Eckhard and Friedrich 2024; Hand
2021; Nielsen 2007; Raaphorst, Groeneveld, and Van de Walle
© The Author(s) (2025). Published by Oxford University Press on behalf of the Public Management Research Association.
This is an Open Access article distributed under the terms of the Creative Commons Attribution-NonCommercial License (https://creativecommons.org/
licenses/by-nc/4.0/), which permits non-commercial re-use, distribution, and reproduction in any medium, provided the original work is properly cited. For
commercial re-use, please contact reprints@oup.com for reprints and translation rights for reprints. All other permissions can be obtained through our
RightsLink service via the Permissions link on the article page on our site—for further information please contact journals.permissions@oup.com.


## Page 2

2
Friedrich and Eckhard
2018). Language use is a central means by which individuals’
judgements and perceptions of others translate into interper­
sonal interactions. We therefore assume that the study of com­
munication offers to gain a more substantive and authentic
understanding of whether and how systematic biases among
bureaucrats influence their behavior (Moseley and Thomann
2021). It thereby allows us to explore forms of administrative
inequality that are not necessarily visible in the material distri­
bution of services but nonetheless importantly shape citizens’
relationship with the state (Eckhard and Friedrich 2024).
Administrative communication consists of relational and
informational dimensions, such as the complexity and emo­
tionality of a speech act (Eckhard et al. 2024). And variation
along these dimensions affects citizen satisfaction and behavior
(Eckhard and Friedrich 2024; Zhou et al. 2025). Drawing on
such early insights, this article asks whether gender-specific
differences prevail in the verbal administrative communication
of street-level bureaucrats.
In answering this question, we test three hypotheses derived
from established theoretical perspectives: Referring to gender
socialization theory, we first test whether men and women
bureaucrats communicate differently. Second, combining the­
ory on gender stereotypes and deservingness cues, we anticipate
that officials may communicate differently with clients who are
male or female. Last, social identity (in- vs. outgroups) and
bureaucratic representation theory suggests that communica­
tion in encounters should differ depending on a match or mis­
match in the gender of client and official.
The empirical analysis draws on a dataset with transcripts
of 154 public service encounters in three different public service
areas, which were recorded at four local agencies in Germany
between 2021 and 2023 (Espinoza et al. 2024). We measure
the linguistic complexity and emotionality in administrative
communication, using a mixture of machine learning-based
text classification and rule-based indicators as validated previ­
ously (Eckhard and Friedrich 2025) . Analyzing our data at the
level of roughly 20,000 single utterances, we estimate multiple
linear regression models to study whether gender induced dif­
ferences in bureaucratic communication exist.
Overall, we observe no statistically significant associations
between bureaucrats’ gender and their communication which
speaks to linguistic findings that the context of conversations
matters much more than speakers’ own gender (Plug et al.
2021). In line with this context argument, we find correlations
for clients’ gender: When talking to male clients, bureaucrats
communicate more complex and emotional compared to inter­
actions with female clients. This result is in line with theory
about stereotypes and gendered deservingness heuristics (Elle­
mers 2018; Jilke and Tummers 2018). It thereby suggests that
bureaucrats perceive female clients as less competent and male
clients as less compassionate which leads them to adapt their
communication to the needs associated with these stereotypical
traits. Lastly, the analysis yields no correlations for gender
matching and bureaucrats’ communication. Gender matching
does not reduce stereotypical biases which implies that women
and men also act upon societal stereotypes linked to their
respective gender, suggesting that the in- versus outgroup
expectations derived from social identity and bureaucratic rep­
resentation theory do not matter for bureaucrats’ communica­
tion (Tajfel and Turner 2004; Meier 2019).
Given that, thus far, scholars have not systematically
explored the link between administrative inequality and
variation in frontline communication, and bearing remaining
limitations in mind, we offer four important theoretical con­
tributions. First, our findings add to literature suggesting that
bureaucrats’ gender may serve as a source of administrative
inequality due to varying work-related abilities and motiva­
tions, such as research on emotional labor (e.g., Meier, Mas­
tracci, and Wilson 2006; Zhang 2025). When it comes to
communication with citizens, these gender differences do not
seem to matter. Second, the finding that clients’ gender is asso­
ciated with bureaucrats’ language use points to the presence of
gendered stereotypes in the behavior of street-level bureaucrats.
This suggests that administrative communication may act as a
micro-mechanism contributing to biased service outcomes, an
aspect largely overlooked in current theorizing on administra­
tive inequality and discrimination (e.g., Adam, Grohs, and Knill
2022; Einstein and Glick 2017; Olsen, Kyhse‐Andersen, and
Moynihan 2022; Thomann, James, and Deruelle 2025). Third,
our analysis shows that in- versus out-group settings do not
significantly condition biased communication styles. This find­
ing has implications for the literature on representative bureau­
cracy, showing that active representation behaviors by
individual bureaucrats do not extend to their communication
with citizens (Meier 2019; Raaphorst, Ashikali, and Groeneveld
2025; Webeck and Lee 2022). Finally, our findings also add to
the literature that seeks to theorize the communicative dynam­
ics of bureaucratic encounters (Eckhard and Friedrich 2024;
Hand 2021; Hand and Catlaw 2019; Holzinger 2020; Kasdorp
and Schakel 2022; Raaphorst and Groeneveld 2018), demon­
strating conditions under which language can become a step­
ping stone toward administrative inequality and burdens (Bell
and Smith 2022; Halling and Petersen 2024; Moynihan, Herd,
and Harvey 2014).
This article is structured as follows. We begin by reviewing
literature on gender biases in public service delivery and on
gender and communication to formulate our hypotheses. We
then present our data and the linguistic measures of complexity
and emotionality. After explaining our research design, we
present and discuss our findings and offer conclusions that
expand on the theoretical contribution of the study.
Gender biases and administrative inequality
Systematic biases in the judgements of street-level bureaucrats
pose a ubiquitous impediment to realizing administrative
equality in citizen treatment. While these frontline public ser­
vants are charged with applying abstract policies to the diverse
realities of individual citizens, they are granted substantial dis­
cretion over the final dispensation of public services. Yet, rather
than neatly tailoring policies to citizens’ situation, they must
often “use their discretion to survive in adverse work settings”
(Keiser 1999, p. 89). Limited time, high caseloads, vague direc­
tives, and human unpredictability create conditions of bounded
rationality (Simon 1947), where officials must “act without
even being able to consider whether an investment in searching
for more information would be profitable” (Lipsky [1980]
2010, p. 29). They are thus left with relying on cognitive
shortcuts—or heuristics—that serve to assess citizens based on
simplifying categorizations, causing “systematic deviations
from the optimal or rational course of action” (Moseley and
Thomann 2021, p. 50). Once these heuristics intertwine with
bureaucrats’ or clients’ personal attributes, “unaccounted-for
disparities” (Raaphorst 2022, p. 398) occur, that is, inequalities


## Page 3

Inequality in frontline communication
3
in administrative treatment of citizens that are unrelated to
policy goals and citizens’ actual needs.
One of such attributes, triggering biased judgements, can be
bureaucrats’ and clients’ gender. As a social construct grounded
in dominant beliefs and expectations about “the psychological,
social, cultural, and behavioral characteristics associated with
being female or male” (Wienclaw 2011, p. 33), gender shapes
our dispositions and behavior as well as how we perceive and
deal with others. Combining insights from different literatures
on gender with extant findings from public administration
research, we identify three ways through which gender may
bias bureaucrats’ behaviors and thus lead to unequal adminis­
trative treatment: through bureaucrats’ own gender socializa­
tion, stereotypes toward male and female clients, and through
the in- and outgroup dynamics in the use of gender stereotypes.
Systematic variation in treatment might thus occur along
bureaucrats’ gender, clients’ gender as well as the match of both
(fig. 1).
Firstly, irrespective of their own gender, citizens might receive
differential treatment due to the gender of the bureaucrat they
are interacting with. In attempting to explain “how men and
women become different”, scholars in sociology and psychol­
ogy have emphasized the formative influence of gender social­
ization (Kretchmar 2011, p. 50). Accordingly, historically
grown gender roles prescribe norms that associate men with
task performance and place women in a relational sphere.
These norms build a “diffuse system of social control” (Lee
Badgett and Folbre 2003, p. 273) that leads people to internal­
ize gendered identities as they grow up and adapt to their social
environment throughout adulthood. Resulting from these
processes, studies argue that men tend to show higher orienta­
tion toward risk-taking, competition and self-enhancement,
whereas women are more communal and concerned with the
welfare of others (Costa, Terracciano, and McCrae 2001; Cro­
son and Gneezy 2009; Schwartz and Rubel 2005).
In public administration, gender socialization may also cause
systematic variation in how male and female bureaucrats deal
with citizens. In a study on street-level bureaucracies in
Denmark, Nielsen (2015, p. 1024) finds that gender-dependent
differences in frontline workers’ empathy, systematic thinking
and competitiveness affect their discretion use so that “varia­
tions in gender-based personal attributes contribute to explain­
ing behavioral variation” in frontline administrative acting.
Literature on public service motivation also “support[s] a gen­
der socialization perspective” (Bright 2005, p. 146), showing
that female bureaucrats are more compassionate (DeHart‐
Davis, Marlowe, and Pandey 2006), more care-oriented toward
clients (Stensöta 2010) and that they make more elaborate
moral judgements of others (White Jr 1999). Further, research
on emotional labor in public services suggests that women
“both provide more emotional labor and are subject to expec­
tations that they will do so” (Meier, Mastracci, and Wilson
2006, p. 900; cf, Guy and Newman 2004; Zhang 2025).
Second, drawing on insights from gender stereotype theory
(Ellemers 2018; Lindsey, Cremeens, and Caldera 2010), the
gender of the client may also be a potential avenue for unequal
citizen treatment. The theory posits that gender norms lead to
the formation of specific stereotypes that “implicitly impact the
expectations we have about the qualities, priorities, and needs
of individual men and women, as well as the standards to
which we hold them” (Ellemers 2018, p. 280). Studies identi­
fied several stereotypical expectations about men, including
higher professional achievement, qualification and competence
than women (Joshi, Son, and Roh 2015; Moss-Racusin et al.
2012). Conversely, due to stereotypical images of women as
caring and relational, others often expected them to prioritize
family responsibilities over paid work (Correll, Benard, and
Paik 2007; Eagly and Steffen 1984) and deem women unsuit­
able for competitive positions (Elder 2004; Fox and Law­
less 2003).
In public administration, gender stereotypes should also
influence public servants’ discretionary judgements about cit­
izens, leading to unequal treatment of male and female citizens.
For example, studies on welfare services found that eligibility
decisions and the enforcement of job search requirements fol­
low stereotypes about men’s and women’s engagement in care­
giving and paid work (Assouline and Gilad 2022; Jaehrling
2015; Kullberg 2005; Pedersen and Nielsen 2020). Such ste­
reotypical categorizations of clients are typically explained by
the use of deservingness heuristics among frontline officials,
triggering cues about which specific treatment a male or female
client is worthy of (Maynard-Moody and Musheno 2000; van
Oorschot 2000).
Third, following social identity theory (Hogg, Terry, and
White 1995; Tajfel and Turner 2004), gender stereotype-induced
biases should be less prevalent when interactants share the same
gender. The theory claims that individuals form social identities
as they categorize themselves and others into social groups. As
a consequence, stereotypes are “more salient in judgements of
out-group members than in-group members” (Turner et al.
1994, p. 456). Based thereupon, social psychology has docu­
mented an “out-group homogeneity effect” in the use of gender
stereotypes (Coats and Smith 1999, p. 518). When evaluating
another gender, people often rely on societal stereotypes,
whereas judgments of the same gender are based more on indi­
vidual impressions.
Echoing this notion, public administration research on rep­
resentative bureaucracy suggests that the correspondence
between bureaucrats’ and clients’ gender might mitigate gender
stereotyping. The key argument in this literature is that when
Figure 1.  Structure of the theoretical argument and hypotheses.


## Page 4

4
Friedrich and Eckhard
mirroring the demographic diversity of their clientele admin­
istrations may “lessen the inherent biases of the bureaucracy”
(Meier 2019, p. 43). Studies have shown that a proper gender
balance in frontline administrations’ workforce leads to more
balanced service delivery in areas such as welfare (Guul 2018)
or health services (McCrea 2021). One plausible explanation
is that when bureaucrats’ gender aligns with that of clients they
are more likely to make unbiased discretionary judgements.
Scholars have recently argued that due to shared lived experi­
ences in in-group settings bureaucrats have a better understand­
ing and knowledge of their clients’ individual situation
(Eckhard 2021; Lofaro and Sapat 2025; Meier 2023;
Raaphorst, Ashikali, and Groeneveld 2025), leading to “a more
constructive interaction between bureaucrat and citizen” (Guul
2018, p. 400).
A theory of gender biases in frontline
communication
One central venue through which gender biases both emerge
and affect service delivery, is the personal interaction between
bureaucrats and citizens. Face-to-face contacts with clients
serve as the most influential “frame of reference” for how cit­
izens’ appearance and behavior as well as bureaucrats’ own
social norms and identities may guide their judgements
(Maynard-Moody and Musheno 2000, p. 349). Since the
nature of frontline bureaucrats’ tasks typically requires them
to “make decisions on the spot” (Lipsky [1980] 2010, p. 8),
the behavior they adopt based on these judgements during the
interaction can have substantive consequences in at least three
ways: Biased behavior may cause discrimination in service out­
comes (Assouline, Gilad, and Ben-Nun Bloom 2022; Andersen
and Guul 2019), it may unequally cause burdens when citizens
try to access services (Jilke, Van Dooren, and Rys 2018; Moyni­
han, Herd, and Harvey 2014), and, through experiences of
lacking procedural justice, the perception of biases matters for
citizens’ trust in government as a whole (Hansen 2022; Kumlin
and Rothstein 2005).
One way to gain more meaningful insights into bureaucrats’
interactions with citizens, is to look at the “communicative
in-between of public professionals and citizens” (Bartels 2013,
p. 470). Viewing encounters as a distinct phenomenon of its
own, a burgeoning literature points to the centrality of the com­
municative dynamics driving interpersonal bureaucrat–client
interactions. Scholars have shown how bureaucrats’ discretion­
ary decisions may directly emerge from the “collaborative,
negotiated process” through which they personally communi­
cate with a citizen (Hand and Catlaw 2019, p. 126; cf, Bruhn
and Ekström 2017; Raaphorst and Loyens 2020; Raaphorst,
Groeneveld, and Van de Walle 2018; Nielsen 2007; Döring,
Drathschmidt, and Nielsen 2025; Dose and Strüngmann 2025).
Further, Eckhard and Friedrich (2024) show that bureaucrats’
communication has an independent impact on citizen percep­
tions of the encounter.
Studying language use then offers deeper insight into how
implicit bias drives bureaucrats’ behavior during encounters.
Linguistic and psychological research has shown that subtle
elements like word choice or politeness reflect unconscious
stereotypes (Pennebaker, Mehl, and Niederhoffer 2003; Gre­
enwald and Banaji 1995). These verbal cues, often more reveal­
ing than self-reports, expose the cognitive schemas and social
stereotypes that speakers may not be able to articulate or even
recognize (De Houwer et al. 2009; Bargh and Chartrand 1999).
We thus consider the choice of words1 in an encounter a rep­
resentation of an official’s inner self which they can only par­
tially control and define gender biases in administrative
communication as systematic differences in the use of termi­
nology due to bureaucrats’ own gender, the gender of the client,
or the match of both.
Most scholars capture encounter communication as they
map characteristics of interactions based on the level of direct­
ness (Raaphorst, Groeneveld, and Van de Walle 2018), nego­
tiation and cooperation (Nielsen 2007; Kasdorp and Schakel
2022), bureaucrats’ and clients’ preparedness (Döring, Drath­
schmidt, and Nielsen 2025) or through analyses of communi­
cative strategies among bureaucrats, such as offering assistance
(Thunman, Ekström, and Bruhn 2020) or giving space to speak
(Hand and Catlaw 2019). The work by Eckhard et al. (2024)
conceptualizes such single practices and integrates them into a
comprehensive framework. Their taxonomy suggests that, at
the most abstract level, administrative speech acts either serve
an informational or a relational purpose. These two levels each
divide into two dimensions. Administrative language then
serves citizen information needs depending on the complexity
of administrative speech acts and the extent of reification. The
relational level, on the other hand, consists of the emotionality
and complaisance (helpfulness) of administrative speech acts.
Using the taxonomy to systematically study variation in admin­
istrative language, recent studies have shown that these dimen­
sions affect citizen perceptions and behavior (Eckhard and
Friedrich 2024; Zhou et al. 2025).
In this analysis, we focus on the dimensions of complexity
and emotionality, as linguistic measures for the other dimen­
sions do not exist. Low levels of complexity make “adminis­
trative procedures and regulations understandable,” enabling
citizens to comprehend “how exactly the service in question
applies to their specific life situation” (Eckhard and Friedrich
2024, p. 125). Meanwhile, emotional administrative language
shapes the degree to which bureaucrats express appreciation
and active commitment to the clients’ individual concerns (Eck­
hard and Friedrich 2024, p. 126). This follows a basic defini­
tion in psychology, where emotionality in communication is
an “evaluating statement” that serves to convey the speaker’s
appraisal of a given situation, including positive and negative
assessments (Fiehler 2002, p. 85). As such, it contributes
toward establishing personal closeness and appreciation
between interactants.
Following the above outlined model on gender biases, our
theory yields three groups of expectations: First, the literature
is disunited regarding whether we should expect differences
in the degree of complex and emotional communication
according to the gender of the speaker: One the one hand,
looking back at several decades of socio-linguistic research
Coates (2015, p. 169; see also Tannen 1990 ) concludes that
gender socialization is inextricably linked with “learning to
use gender-appropriate language,” leading individuals to com­
municate differently depending on their gender. In line with
1  Such verbal or spoken administrative language can be defined as “the
distinctive practices of verbal interpersonal communication upon which
bureaucrats rely during a conversation with citizens” (Eckhard and Frie­
drich 2024, p. 124). We thus focus on spoken language as one specific
aspect of communication which does not include non-verbal cues, such
as gestures, facial expressions or tone.


## Page 5

Inequality in frontline communication
5
this, women are found to exhibit a more cooperative and
supportive communication style whereas men seem to resort
to a more authoritarian style of talk (e.g., Holmes 1999;
Lakoff 1973).
On the other hand, in a review of fifteen empirical studies,
Plug et al. (2021, p. 43) report only “few robust differences
between women and men in the use of linguistic variables.”
They and others argue that gendered language use varies
“depending on context” (Waara and Shaw 2006, p. 131). This
can firstly concern the demographic features of the other
speaker in a dyadic setting, such as ethnicity or gender (see our
H2). But it can also apply to situations where interlocutors
have institutionalized positions and adopt distinct “communi­
cative roles” that tie their language use to their respective status
and knowledge (Giles and Ogay 2007, p. 302). This pattern
has been observed in linguistic analyses of courtroom and
doctor–patient interactions, where institutional roles cancel out
the correlation of speakers’ gender with their communication
(O’Barr and Atkins 2005; Sleath and Rubin 2002; Waara and
Shaw 2006). Public service encounters also qualify as such
asymmetrical interactions since, contrary to clients, bureaucrats
are administrative experts and assume a naturally superior
position toward them. In light of the state of the art, we thus
formulate two competing hypotheses:
H1a: The communication of frontline bureaucrats differs
depending on their gender, with female bureaucrats com­
municating less complex and more emotional than their
male counterparts.
H1b: The communication of frontline bureaucrats does not
differ depending on their gender.
As the second expectation, a range of linguistic studies
demonstrate that “speakers, regardless of gender, accommo­
dated their styles to the gender of the conversational partner”
(Lindvall-Östling, Deutschmann, and Steinvall 2020, p. 569).
For example, linguistic research found that during conversa­
tions with women, speakers interrupt more often and use more
dependent clauses and questions compared to interactions with
men (Hancock and Rubin 2015; Waara and Shaw 2006; Sleath
and Rubin 2002). As another important context factor, the role
of opponent’s gender may remain entirely unaffected by the
influence of institutional contexts discussed with the H1 (Han­
cock and Rubin 2015; Hildebrand-Edgar and Ehrlich 2017;
Waara and Shaw 2006). It is hence plausible that the degree of
complexity and emotionality in frontline communication is
stable across bureaucrats’ gender and simultaneously varies
across clients’ gender. How exactly might such unequal com­
municative treatment of male and female citizens align with
gender stereotype theory?
Low complexity matters for citizens due to their need for
information during encounters. Gender stereotypes may then
evoke the use of need-based deservingness heuristics in bureau­
crats’ communication. As one particularly influential cue
“needed deservingness” leads bureaucrats to treat citizens
based on stereotypical images about the need for support of
societal groups (Jilke and Tummers 2018, p. 227). Given that
gender stereotypes depict men as more independent and com­
petent than women, the latter might be perceived as being in
greater need of an intellectually less demanding encounter.
Consequently, bureaucrats should provide female clients with
less complex communication.
When it comes to emotionality, however, gendered deserving­
ness cues might work in two different directions. Emotionality
serves to convey solicitude and personal closeness to the client.
Following from stereotypical images of women being more rela­
tional, bureaucrats might view female clients as having generally
a higher need for emotional communication when encountering
a bureaucrat. But the same could also be true for males, who, due
to their stereotypically assertive characteristics, are believed to be
less inclined to engage in intimate personal exchange (Gaia 2013).
In this case, officials might associate male clients with “neglected
needs” for interpersonal connections (Ellemers 2018, p. 281) and
may therefore resort to a more emotional communication style.
Our hypothesis thus reads:
H2: The communication of frontline bureaucrats differs
depending on the clients’ gender, with female clients receiving
less complex and more emotional (H2a) or less emotional com­
munication than male clients (H2b).
The last expectation is that the gender match between
bureaucrat and client should lead to “a more constructive inter­
action between bureaucrat and citizen” which is accompanied
by “better verbal and nonverbal communication” (Guul 2018,
p. 400). This follows from social identity and bureaucratic
representation theory which expect that individuals in in-group
settings—with more advanced knowledge about their
opponent—should be less inclined to stereotype-induced
behavior. The reason is that language use reflects how strongly
simplifying gender categorizations affect our perceptions and
actions (Beukeboom and Burgers 2019, p. 25). This expecta­
tion is in line with existing work in linguistics, showing that in
mixed-gender settings men dominate the conversation by inter­
rupting women, taking more talking time and controlling top­
ics of conversation (Coates 2015). We thus anticipate that
gender matching countervails the hypothesized stereotypical
biases (H2) in the complexity and emotionality toward male
and female clients. However, to what extent bureaucrats’ insti­
tutionalized roles supersede these dynamics is an open question.
Also in this case, we thus formulate two competing hypotheses:
H3a: The communication of frontline bureaucrats differs
depending on whether there is a match or mismatch in their
gender, with a match decreasing variations in complexity
and emotionality across male and female clients.
H3b: The communication of frontline bureaucrats does not
differ depending on whether there is a match or mismatch
in their gender.
Research design
Data
To study gender-related differences in administrative communica­
tion, we use a dataset that offers an anonymized text corpus of
154 conversations between bureaucrats and citizens (Espinoza et
al. 2024). It covers 20,000 utterances from 28 bureaucrats (40,000
in sum) as well as a survey with 20 of them. They were recorded
between 2021 and 2023 at two local jobcentres (113 conversa­
tions), a civil registry office (19) and a social office (22) (for an
overview, see Supplementary Appendix 4).


## Page 6

6
Friedrich and Eckhard
The data thus cover three different service areas. Jobcentres
implement the so-called basic income for unemployed which
grants a means-tested minimum income and offers labor market
services based on a workfare logic. We recorded conversations
between case managers and recipients. Through career coun­
seling and training measures, these encounters serve to support
recipients in finding ordinary work but also to monitor their
efforts in doing so. When the case managers consider these
efforts to be insufficient, they may temporarily cut the mini­
mum income payments. The participating bureaucrats in the
social office deal with citizen requests for local public childcare.
In the recorded conversations, they advised parents on the
application process. Lastly, in the civil registry office citizens
met with bureaucrats for the issuance of, for instance, death
and marriage certificates or to register their land and residence.
Espinoza et al. (2024, p. 13317) report a lengthy data col­
lection procedure associated “with an enormous amount of
work.” To recruit agencies, local administrations all across
Germany were contacted who interact with citizens daily.
Administrations that showed interest received additional infor­
mation on the project. At this point, some agencies opted out
because of concerns regarding resource scarcity, employee pro­
tection, or data privacy. In cases where agencies remained
engaged, the next step included information meetings to recruit
individual officials. For the data collection, employees first filled
out an online survey. They were then handed out recording
devices and subsequently started recording conversations with
their clients over a period of one to three months without a
researcher being on-site. Participation in the recordings was
always based on informed consent of citizens, documented
either in written form or in the audio recording. Officials were
asked to record as many conversations as possible. The devices
were prepared in a way that the recordings could not be listened
to, changed or deleted afterwards. Upon completion of data
collection, recordings were transmitted to a professional tran­
scription service and subsequently anonymized by removing
all names and physical locations. The resulting available text
corpus is fully anonymized.
While the data collection procedure sought to avoid reactiv­
ity biases among officials and citizens, it does not allow to
establish how many citizens eventually participated relative to
all encounters and employees. Given these restrictions, our
analysis builds on a convenience sample that comes with lim­
itations as further discussed below. But similar to linguistic
studies using data from police officer body cams (Voigt et al.
2017), undistorted observations on administrative behavior
are possible since our measures apply at a highly disaggregated
linguistic level which study participants are unlikely to manip­
ulate, as discussed next.
Measures and analytical strategy
When inspecting our hypotheses, the dependent variables are
complexity and emotionality in frontline communication. To
empirically assess them, we use a set of text-based measures
that classify different degrees of complexity and emotionality
of verbal administrative language by means of natural language
processing (for a comprehensive overview and validation, see
Eckhard and Friedrich 2025).2 Thereby, complexity is assessed
2  A summary of the results of the validation process is further provided
in Appendix 2.
through a dictionary-based score that we derived from guide­
lines for plain language in German written communication and
systematically refined for an application to verbal administra­
tive communication (Siskou et al. 2022). It covers linguistic
features at the level of words, morphology and syntax (for an
overview of the single features, see Supplementary Appendix
1). Its overall aim is to establish how easy it is for citizens to
understand the content of the encounter.
Emotionality is operationalized through a combination of
seven dictionary and nine machine-learning based features,
including a diverse range of different emotions (see Supplemen­
tary Appendix 1). The latter are originally obtained from the
BERT-based GoEmotions model that has been fine-tuned for
emotion detection with Reddit comments. It offers a “granular”
automated classification of in sum 27 verbal emotional expres­
sions (Demszky et al. 2020, p. 2). The dictionary-based features
originate from linguistic analyses of the quality of political
discourses (Gold et al. 2017). The measure’s overall aim is to
establish to what degree bureaucratic communication conveys
commitment and appreciation of the citizen’s concerns.
The classifications of the single features are made on the level
of utterances. For operationalizing them, we follow common
approaches in linguistics that define utterances as “those chunks
of talk that are marked off by a shift of speaker” (Traum and
Heeman 1996, p. 125). An utterance thus starts and ends when­
ever turn-taking occurs and may consist of several sentences or
only fragments, in case one speaker cuts off the other. In line
with our above definition of spoken administrative language,
the classification does not take account of phonetic character­
istics. In our data, the conversations consist of 224 speaker turns
on average, while the mean utterance length is 14 words, with
a minimum of one and a maximum of 929.
The two measures yield a metric value for each of the
bureaucrats’ utterances constructed through an additive index
built from the z-transformed values of the single features. The
value for a given utterance obtained from the indices then
reflects the summed ratios of the values of the features to their
respective distribution. A disproportionally high share of the
overall measures for both complexity and emotionality is neg­
ative and close to zero, while positive values spread widely
(see fig. 2 and Supplementary Appendix 7). That is because
most of the single features constitute sparse labels, that is, they
naturally occur only irregularly. Consequently, in the raw dis­
tribution of most features, between 50 and 90 percent of the
values are zero.
Table 1 shows utterances that received high values for com­
plexity and emotionality (a comprehensive selection can be
found in Supplementary Appendix 3). The first was made by
a jobcentre employee in the context of the client’s intention to
transition from unemployment to pension benefits. It exhibits
a convoluted sentence structure (syntax) and a repeated use of
the technical term ‘reduced income pension’ (word-level) which
further entails a participle (morphology). Due to the joint
occurrence and frequency of these three features, the utterance
is classified as highly complex. In the second example an official
explained to a client how to obtain an ID for his children. The
utterance contains several genitives and is fully in passive voice,
being morphological and syntactical features that make lan­
guage more difficult to understand.
The first utterance for emotionality was made as a jobcentre
employee discussed possible training programs with a client.
The score is driven by high degrees of optimism as one


## Page 7

Inequality in frontline communication
7
emotion-feature. Additionally, it exhibits a linguistically pro­
nounced degree of command, expressing the expectation that
the client should be motivated. The last example is a jobcentre
official’s response to a client lamenting the non-responsiveness
of employers. It received a high value for emotionality because
it conveys considerable levels of sadness and politeness but also
common ground as another feature, strongly confirming the
client’s assessment.
Information on the independent variables bureaucrats’ and
clients’ gender as well as gender match were extracted from
the survey with officials and the gender-specific address and
suffixes used in each conversation. Clients’ gender specifies for
each statement by an official whether it was made toward a
male or female client, while gender match indicates whether it
matches with the bureaucrats’ gender.3 Roughly seventy percent
of the bureaucrats’ utterances are from women. Approximately
twenty percent of the bureaucrats’ utterances were made
toward a male client with matching gender and forty percent
toward female clients with a matching gender, whereas roughly
ten percent are from bureaucrats interacting with a female cli­
ent not matching their gender and thirty percent with a male
client not matching bureaucrats’ gender (for a more detailed
overview, see Supplementary Appendix 5).
For detecting the statistical relationship between complexity
and emotionality in frontline communication and gender, we
estimate multiple linear regression models building on single
utterances as the unit of analysis. We thereby need to take
account of the hierarchical data structure. As is reported in
3  In 25 conversations, two bureaucrats or clients with different genders
participated. In these cases, we relied on the gender of the speaker with
more utterances to obtain a dichotomous variable. The analysis will test
whether the ensuing loss of information biased the results once we find
correlations for gender.
Supplementary Appendix 8, only between two and eight per­
cent of the variance are explained by differences between con­
versations and bureaucrats, respectively. We hence decided to
abstain from multi-level modeling and treated the single utter­
ances as independent observations while including a wide vari­
ety of controls at all layers of the data structure (see below) to
obtain unbiased estimates. Moreover, while the distribution of
the two dependent variables is both left-skewed and leptokurtic
(see fig. 2 and Supplementary Appendix 7), we use bootstrap­
ping as a non-parametric alternative to ordinary least squares
for calculating confidence intervals (Mooney 1996).
We firstly consider potential confounders as control vari­
ables that vary at the level of utterances and conversations.
To acknowledge the specific dynamic any single utterance is
embedded in within a conversation, presumably giving rise
to different degrees of complexity and emotionality, we
include the conversation period. It is assessed through the
ratio of the position of a given utterance to the total number
of utterances in the respective conversation, hence ranging
from zero to one. As conversation-level feature, we consider
the conversation length, operationalized through the number
of utterances.4 Further, while the bureaucrats’ language use
can be expected to partly be a function of the clients’ com­
municative input, we assign each of their utterances with the
clients’ mean complexity and mean emotionality in a conver­
sation, representing another control variable that differs
across conversations.
Moreover, due to potentially stable communication styles
across officials, we take a range of their characteristics,
4  For the analysis, we form a categorical variable with four groups
derived from the quartiles of the original distribution since the bare
number ranges from 16 to 1,157.
Figure 2.  Violin plots of complexity and emotionality in frontline communication.
Table 1.  Utterances with high values for complexity and emotionality.
Complexity
This is also much more detailed, and then I will invite you again and we will talk about what it says, and then we will see in how far we will try it
again with the reduced income pension, or that you – you tried the fully reduced income pension, right? – that we then try partly reduced income
pension. (68.48)
Then, for the ID application, the signature of the mother and the father is needed. The signature of the father, if he is not present at all, can be
replaced only by a power of attorney or a copy of his ID. (53.18)
Emotionality
I think that if the motivation is there, it will work out. (28.89)
The trend is indeed going in that direction, Ms. [name], you are not alone in this, that employers are responding less and less. It is a very sad
development, but you do not have to necessarily blame yourself. Others in your situation make similar experiences. (18.38)


## Page 8

8
Friedrich and Eckhard
attitudes and perceptions into account.5 In the survey, we firstly
measured their age, educational background and identification,
migration experience and tenure.6 Second, we control for
work-related attitudes. While street-level bureaucrats’ motiva­
tion and satisfaction with their tasks are associated with the
quality of citizen treatment (Petrovsky, Xin, and Yu 2023; An,
Yu, and Tan 2025), they might also matter for levels of com­
plexity and emotionality in communication. We therefore con­
sider their commitment to public interest7 and job satisfaction.
Moreover, since the use of biases is contingent upon how front­
line officials perceive and react to the many stressors in their
working conditions, we control for their perceived adversity
and overstrain during encounters as well as their self-efficacy
and emotional exhaustion (Ropes and de Boer 2021; Tummers
et al. 2015). Thirdly, we include their aversion and empathic
concern toward clients, based on the recognition that these
attitudes lead to a less responsive citizen treatment (Baviskar
and Winter 2017) which might also be reflected in different
communication practices. Finally, the encounters in our sample
come from three different service contexts, which might be
associated with different patterns of frontline communication.
To control for this, we form the dichotomous agency-level vari­
able encounter extent8 which categorizes encounters as having
either wide or limited “duration and scope” (Goodsell
1981, p. 6).
Since survey responses are not available for all bureaucrats,
we estimate two separate models for each dependent variable
and hypothesis. The first builds on the entire speech-data sam­
ple without including the survey measures, while the second
further entails the bureaucrat-variables. We only confirm each
hypothesis once we find statistically significant correlations for
the independent variable in both models. Moreover, we can use
encounter extent only in the models on clients’ gender (H2)
since in two agencies only one and, respectively, two partici­
pating bureaucrats were male. Lastly, we only include controls
that exhibit statistically significant correlations with the respec­
tive dependent variable (Becker 2005) (see Supplementary
Appendix 9).
Results
Table 2 reports the results for the associations between bureau­
crats’ gender and their communication toward citizens. In the
first model predicting complexity with only utterance- and
conversation-level controls, the coefficient for male bureaucrats
is close to zero and statistically not significant, whereas when
5  For a detailed overview of the operationalization, see Appendix 6.
6  In the analysis, educational background specifies whether a bureaucrat
has completed an education program specialized in training administra­
tive personnel, while educational identification denotes a self-assessed
classification of whether the education is related to public administration
or social work. Migration experience indicates whether a respondent’s
parents grew up in a country other than Germany.
7  This is a single dimension of the overall concept of public service
motivation.
8  In jobcentres, interactions have a sweeping impact on clients’ lives,
affecting their economic existence and employment prospect and are part
of a long-term relationship with multiple meetings. Conversely, the con­
versations in the social office and the civil registry office are typically
singular meetings and the overarching services are strongly standardized
so that the nature of the interaction has only a limited influence on their
claims.
adding the bureaucrat-level variables it falls noticeably below
zero and becomes significant (see model 2). Thus, while only
one model yields significant differences, the analysis does not
sufficiently verify that the degree of complexity in the bureau­
crats’ communication depends on their own gender. Similarly,
when inspecting emotionality as dependent variable, model 1
yields a statistically significant negative relation for male
bureaucrats, but in model 2 it is not significant and nearly zero.
In sum, given that these results do not indicate different com­
munication behaviors between male and female bureaucrats,
they lend support for H1b.
Next, we examine the correlation between the clients’ gender
and complexity and emotionality in frontline communication.
As is shown in Table 3, once they talk to male clients, bureau­
crats communicate more complex than when interacting with
female clients. In both models 1 and 2, the coefficient is statis­
tically significant, indicating that the complexity in adminis­
trative communication experienced by male clients is, on
average, roughly 0.25 and 0.26 points higher. Given that in the
overall distribution of complexity single values for utterances
can reach up to seventy but that a large share is below zero,
we interpret the strength of these associations as moderate, that
is, noticeable and meaningful but not fairly large. In the same
vein, compared to female clients, male clients face more emo­
tional administrative language. In both models, we observe
statistically significant positive associations for male clients and
emotionality in frontline communication. Their strength ranges
from about 0.25 to 0.60 and should thus also be classified as
moderate since emotionality follows a similar distribution as
complexity. Accordingly, the analysis confirms hypothesis H2b
given that females receive moderately lower levels of complex
and emotional communication.
In terms of robustness, these associations also prevail when
using alternative measures and models. Firstly, as is reported
in Supplementary Appendix 10, a comparison of only those
conversations where bureaucrats and clients with different
genders participated as well as an alternative regression anal­
ysis, including only conversations where the gender was
unequivocal, point in the same direction as the main analysis.
Secondly, male clients experience significantly higher levels of
both positive and negative emotionality in administrative com­
munication (see Supplementary Appendix 11). Thirdly, models
with bureaucrat-level fixed slopes (see Supplementary Appen­
dix 12) as well as estimations including each clients’ mean
complexity and emotionality in the models for both dependent
variables yield no alterations (see Supplementary Appendix 13).
Last, we inspect whether gender matching mitigates the
observed biases in administrative language. To test the H3, we
therefore assess for the groups of male clients and female clients
respectively, whether a match with the gender of the official is
associated with fewer biases in communication, thus reducing
the disparities that we observed with the H2. This would be
indicated by a negative correlation of a match with the com­
plexity and emotionality of bureaucrats’ language within the
group of male clients and a positive association within the
subsample of female clients. However, findings from H1
already suggest that such dynamics are unlikely. Indeed, as
Table 4 reports, compared to a non-match, a match between
clients’ and bureaucrats’ gender does not seem to be related
with changes in communication of the latter in either of the
four subgroups, which holds true for both complexity and
emotionality. Although some of the estimations yield


## Page 9

Inequality in frontline communication
9
statistically significant coefficients, none of them remains sig­
nificant across the two different models. Overall, we hence
maintain H3b. For the degree of complexity and emotionality
clients experience, it does not make a difference whether they
have the same gender as the bureaucrat.
Discussion
This article aims at advancing our understanding of
micro-mechanisms leading to “unaccounted-for disparities”
(Raaphorst 2022, p. 398) in administrative treatment of citi­
zens. Toward this end, we derived three hypotheses linked to
bureaucrats’ gender socialization, gender stereotyping, and in-
versus outgroup dynamics and applied them to the context of
administrative communication. We now offer an interpretation
of the empirical analysis based on gender-group differences in
the frontline communication of 20 public servants in 154 cit­
izen encounters in Germany.
Regarding the first hypothesis, we find no systematic differ­
ences between the speech acts of male and female bureaucrats
in our study. This is in line with recent studies in linguistics,
emphasizing the context-dependency of gendered language (Plug
et al. 2021; Hancock and Rubin 2015; Waara and Shaw 2006).
Seemingly, frontline public servants assume distinct “communi­
cative roles” based on their knowledge and status—similar to
situations observed in the courtroom or medical context—which
foster the formation of consistent communication practices
(H1b). This notion also resonates with insights from the
street-level bureaucracy literature, suggesting that due to their
education and organizational socialization frontline bureaucrats
develop distinct professional identities that shape their discretion
use (Friedrich 2025; Oberfield 2014; Thomann, Hupe, and Sager
2018). Additionally, especially since many clients in our sample
are welfare recipients, the encounters might be influenced by
class-dependent “symbolic and moral boundaries” (Harrits and
Møller 2014, p. 452; e.g., Watkins-Hayes 2011). Bureaucrats’
membership in a more privileged social group might then lead
them to identify with their class rather than their gender. Overall,
the gender of bureaucrats thus appears no source for inequality
in administrative communication.
Our finding that the gender of the client makes a difference
is also in line with the linguistic claim that “context matters”
and further speaks to the recognition that frontline bureaucrats’
treatment of citizens often builds on stereotyping judgements.
We found that male citizens in our sample experience moder­
ately higher levels of complex and emotional administrative
language, which is in line with H1b. This finding is consistent
with linguistic studies which also observed that the gender of
the interlocutor is associated with speaker’s verbal communi­
cation, irrespective of speakers’ communicative roles (Hancock
and Rubin 2015; Mulac et al. 2013). It further confirms our
expectation that the frequently documented biases along cli­
ents’ gender also translate into bureaucrats’ communication,
suggesting that it adheres to gender-stereotypical beliefs about
clients’ attributes. Just like, for instance, decisions on welfare
benefits (Assouline and Gilad 2022), this dynamic is driven by
gendered deservingness cues. Given that we observe higher
levels of emotionality among male clients, this dimension
Table 2.  Regression analyses for the correlation of bureaucrats’ gender with communicative complexity and emotionality.
Independent variables
Dependent variable: complexity in frontline
communication
Dependent variable: emotionality in
frontline communication
Model 1
Model 2
Model 1
Model 2
Male bureaucrat
−0.07 (0.07) [0.32]
−0.46 (0.20) [0.03]
−0.15 (0.06) [0.02]
−0.01 (0.11) [0.93]
Utterance-level control
Conversation perioda
0.23 (0.11) [0.03]
0.36 (0.12) [0.01]
0.95 (0.10) [0.00]
1.02 (0.14) [0.00]
Conversation-level controls
Conversation lengthb
−0.31 (0.03) [0.00]
−0.25 (0.04) [0.00]
−0.19 (0.03) [0.00]
−0.21 (0.05) [0.00]
Mean complexity in the client’s communication
0.33 (0.03) [0.00]
0.15 (0.05) [0.00]
Mean emotionality in the client’s communication
0.48 (0.03) [0.00]
0.28 (0.06) [0.00]
Bureaucrat-level controls
Agec
0.12 (0.09) [0.17]
Educational backgroundd
0.41 (0.44) [0.36]
Educational identificationd
1.28 (0.63) [0.04]
Migration experienced
−0.34 (0.38) [0.37]
Tenure (years)
−0.06 (0.02) [0.00]
Commitment to public intereste
−0.35 (0.07) [0.00]
0.08 (0.08) [0.30]
Emotional exhaustione
−0.30 (0.08) [0.00]
−0.26 (0.11) [0.02]
Job satisfactione
−0.22 (0.07) [0.00]
−0.14 (0.10) [0.10]
Self-efficacyb
1.29 (0.51) [0.02]
Perceived adversitya
−3.30 (0.44) [0.00]
0.26 (0.65) [0.71]
Perceived overstraine
0.30 (0.17) [0.09]
0.39 (0.09) [0.00]
Client aversione
−0.05 (0.09) [0.58]
0.83 (0.16) [0.00]
Empathic concerne
0.48 (0.06) [0.00]
Number of observations
20,032
14,749
20,032
11,199
Adjusted R2
0.02
0.04
0.02
0.03
aScaled from zero to one, bScaled from one to four, cScaled from one to five, dDichotomous, eScaled from one to eleven.
Confidence intervals estimated from bootstrap with 1,000 samples. Unstandardized regression coefficients depicted, standard errors in parentheses,
P-values in squared brackets. Significant correlations in bold (P ≤ .05).


## Page 10

10
Friedrich and Eckhard
appears to be patterned along stereotypical neglected needs.
Seemingly, female clients evoke judgements associating them
with fewer competencies for navigating administrative rules
and procedures and hence higher need for plain communica­
tion, whereas male clients activate cues about lacking capabil­
ities in building interpersonal relations and thus trigger more
emotional communication.
Further, as suggested by social identity and representative
bureaucracy theory, gender matching should render commu­
nication practices less biased when bureaucrats talk to a client
with the same gender. Yet, our findings show no differences in
the complexity and emotionality of administrative utterances
between mixed gender and homogenous settings. This implies
that, male and female bureaucrats communicate based on sim­
ilar gendered stereotypes, irrespective of whether they encoun­
ter their own or another gender. Gender matching thus does
not reduce stereotypical communication. Following the repre­
sentative bureaucracy literature and in line with our findings
on H1, it might therefore be that, when it comes to language
use, bureaucrats’ professional role supresses the salience of a
shared gender identity with the client (Webeck and Lee 2022;
Wilkins and Williams 2008). Further, also in this case,
Table 3.  Regression analyses for the correlation of clients’ gender with communicative complexity and emotionality.
Independent variables
Dependent variable: complexity in frontline
communication
Dependent variable: emotionality in
frontline communication
Model 1
Model 2
Model 1
Model 2
Male client
0.26 (0.07) [0.00]
0.25 (0.10) [0.02]
0.25 (0.06) [0.00]
0.60 (0.10) [0.00]
Utterance-level control
Conversation perioda
0.22 (0.11) [0.05]
0.34 (0.12) [0.01]
0.94 (0.10) [0.00]
1.00 (0.14) [0.00]
Conversation-level controls
Conversation lengthb
−0.32 (0.03) [0.00]
−0.30 (0.04) [0.00]
−0.19 (0.03) [0.00]
−0.26 (0.05) [0.00]
Mean complexity in the client’s communication
0.31 (0.03) [0.00]
0.03 (0.05) [0.57]
Mean emotionality in the client’s communication
0.42 (0.04) [0.00]
0.20 (0.06) [0.00]
Bureaucrat-level controls
Agec
−0.38 (0.10) [0.00]
Educational backgroundd
1.08 (0.41) [0.01]
Educational identificationd
0.21 (0.60) [0.73]
Migration experienced
−0.97 (0.40) [0.02]
Tenure (years)
0.09 (0.03) [0.00]
Commitment to public intereste
−0.33 (0.07) [0.00]
0.00 (0.07) [0.98]
Emotional exhaustione
−0.01 (0.11) [0.97]
−0.23 (0.12) [0.05]
Job satisfactione
0.15 (0.11) [0.17]
−0.05 (0.12) [0.66]
Self-efficacyb
2.10 (0.51) [0.00]
Perceived adversitya
−0.20 (0.76) [0.79]
−0.35 (0.65) [0.55]
Perceived overstraine
0.34 (0.16) [0.03]
0.41 (0.11) [0.00]
Client aversione
−0.22 (0.10) [0.02]
0.86 (0.19) [0.00]
Empathic concerne
0.46 (0.06) [0.00]
Agency-level control
Encounter extentd
−0.13 (0.08) [0.10]
3.51 (0.76) [0.00]
0.14 (0.07) [0.05]
−0.20 (0.27) [0.43]
Number of observations
19,915
14,630
19,915
11,080
Adjusted R2
0.02
0.04
0.03
0.04
aScaled from zero to one, bScaled from one to four, cScaled from one to five, dDichotomous, eScaled from one to eleven.
Confidence intervals estimated from bootstrap with 1,000 samples. Unstandardized regression coefficients depicted, standard errors in parentheses,
P-values in squared brackets. Significant correlations in bold (P ≤ .05).
Table 4.  Regression analyses for the correlation of gender match with complexity and emotionality in frontline communication within the subsamples of
male and female clients.
Independent variable
Dependent variable: complexity in frontline
communication
Dependent variable: emotionality in frontline
communication
Model 1
Model 2
Model 1
Model 2
Match
Subsample: Male clients
−0.18 (0.10) [0.06]
0.55 (0.42) [0.19]
−0.25 (0.09) [0.01]
−0.11 (0.17) [0.53]
Subsample: Female clients
−0.18 (0.13) [0.16]
−0.89 (0.40) [0.03]
0.06 (0.11) [0.61]
−0.42 (0.17) [0.01]
Number of observations
10,288/9,627
7,950/6,680
10,288/9,627
5,550/5,530
Adjusted R2
0.02/0.02
0.04/0.03
0.02/0.03
0.03/0.04
Model 1 each includes the utterance- and conversation-level controls and model 2 further includes bureaucrat-level controls. Confidence intervals
estimated from bootstrap with 1,000 samples. Unstandardized regression coefficients depicted, standard errors in parentheses, P-values in squared
brackets. Significant correlations in bold (P ≤ .05).


## Page 11

Inequality in frontline communication
11
socioeconomic status could matter. The identified stereotypes
might be driven by an intersection of class and gender so that
bureaucrats perceive female clients as less competent and more
emotional than men because they believe these differences pre­
vail especially among low-status citizens. The correspondence
between bureaucrats’ and clients’ gender might then not miti­
gate biases in communication because a class-based social dis­
tance remains (Watkins-Hayes 2009), inhibiting more accurate
judgements during gender-ingroup settings.9
Our results must be interpreted bearing some limitations in
mind. Although our controls represent diverse dimensions of
bureaucratic characteristics and attitudes, the study captures
only a limited number of administrators, organizations and
contextual conditions which has implications for its external
validity. As for the internal validity, it is worth stressing that
due to the composition of the sample the analyses on H1 and
H3 do not control for encounter extent. Therefore, we cannot
directly say whether the presumed relation between bureau­
crats’ gender and their professional position differs between
types of encounters. One might argue that the jobcenter
employees are more strongly influenced by their occupation
than the bureaucrats from the two other agencies. Future
research should address this association with a broader range
of occupational context conditions included.
Another shortcoming is that our approach does not include
non-verbal expressions. Thus, our study offers no implications
for the phonetic characteristics of bureaucrats’ language, such
as voice or tone, or their facial expressions, all being important
elements of interpersonal communication. With respect to our
null-findings for H1 and H3, it is possible that bureaucrats’
gender is not correlated with the choice of words but with how
they are pronounced. Further, we might overestimate the dif­
ferences found for H2. While non-verbal cues might trigger a
certain wording and simultaneously differ systematically across
male and female clients, they possibly operate as confound­
ing factor.
Furthermore, the participants of this study knew that they
were under observation. The recordings hence could have cre­
ated an artificial setting in which bureaucrats and citizens
behaved differently than they usually do. Specifically, given that
administrative equality is a highly salient norm, this could
imply that the bureaucrats were intentionally cautious in treat­
ing clients alike, suggesting that our study underestimates sys­
tematic gender differences. However, it is worth stressing that
the data were collected with as little interference with the
bureaucrats’ daily routines as possible, which should have
reduced the risk of biases. We also expect that it will be difficult
for participants to consciously control their communication at
the highly nuanced level at which our linguistic measures apply
(cf.,Voigt et al. 2017).
Moreover, the interpretation of our findings must acknowl­
edge potential selection biases. Also in this regard, we might
underestimate the prevalence of gender-induced disparities.
While bureaucrats and agencies with high awareness for the
significance of administrative communication and citizen
encounters are certainly overrepresented in the data, they can
be simultaneously expected to be more sensitive to unbiased
citizen treatment. Importantly, however, following the idea of
a ‘Sinatra inference’ (Gerring 2008), the differences we find for
9  We would like to thank Reviewer 3 for hinting us at the issue of
intersectionality.
clients’ gender in such a least-likely setting may provide valu­
able grounds for generalization: If gender biases in administra­
tive language matter in this setting, they are very likely to occur
in the overall universe of frontline administrative acting as well.
Conclusion
In this article, we have presented novel empirical insights on
gender-specific biases in the complexity and emotionality of
verbal administrative language, which adds to the growing
literature that explores the inner workings of verbal commu­
nication in public service encounters (Eckhard and Friedrich
2024; Hand 2021; Hand and Catlaw 2019; Holzinger 2020;
Kasdorp and Schakel 2022; Raaphorst and Groeneveld 2018).
The goal of our study was to contribute toward a deeper under­
standing of the micro-mechanisms underlying biased public
service practices which continue to be a black box in the var­
ious literatures interested in unequal citizen treatment.
With its insights, the study makes important contributions to
the broader (public administration) literature on inequality and
discrimination, burden in public service provision as well as on
how personal experiences with bureaucrats shape citizens’ dispo­
sitions toward the state (e.g., Einstein and Glick 2017; Grohs,
Adam, and Knill 2016; Jilke, Van Dooren, and Rys 2018; Moyni­
han, Herd, and Harvey 2014; Thomann, James, and Deruelle
2025). Unraveling patterns of differential citizen treatment in
street-level bureaucrats’ verbal communication, it offers profound
insights on how the behavioral practices guiding official–client
interactions at the micro-level can cause biased outcomes and per­
ceptions of unfair treatment among citizens. By this, our research
constitutes a major innovation compared to the data scholars typ­
ically draw on, generated from experiments and audit studies,
administrative outputs or qualitative designs.
Regarding the literatures and theories we drew on, we offer three
concluding theoretical contributions: First, our findings contradict
the expectation that bureaucrats’ gender serves as a source of com­
municative inequality, as sometimes suggested by research on pub­
lic service motivation (e.g., Bright 2005; DeHart‐Davis, Marlowe,
and Pandey 2006) or emotional labor (Guy and Newman 2004;
Meier, Mastracci, and Wilson 2006; Zhang 2025). Either such
gender differences in communication do not exist in the German
population at all, or they may be overridden by institutional norms
and role expectations within bureaucracies. While gender differ­
ences in other dimensions of administrative behavior may still exist,
they do not at the level of verbal communication. Given that our
data did not allow us to directly test the link between varying
professional identities, clients’ social status and bureaucrats’ com­
munication, future studies could build on our initial findings to
more systematically scrutinize gendered administrative communi­
cation styles across administrative organizations, tasks, occupa­
tions and different client groups.
Second, the observed correlation of clients’ gender with the
language used by bureaucrats indicates gendered stereotypes
in bureaucratic behavior. This finding underscores the role of
administrative communication as a potential micro-level mech­
anism through which biases are reproduced in public service
delivery—an aspect that has received limited attention in exist­
ing theories of administrative inequality (e.g., Adam, Grohs,
and Knill 2022; Einstein and Glick 2017; Olsen, Kyhse‐Ander­
sen, and Moynihan 2022; Thomann, James, and Deruelle
2025). Our study thereby illustrates the importance of viewing


## Page 12

12
Friedrich and Eckhard
the interaction as a distinct phenomenon of its own (e.g., Bar­
tels 2013; Döring, Drathschmidt, and Nielsen 2025), suggest­
ing that to fully understand citizens’ experiences with the state
we need to consider forms of administrative inequality that
emerge from and manifest during the interactional dynamics
of encounters. Therefore, although the identified biases might
matter for the material service distribution, they should not
simply be seen as potential antecedent of differential decisions
and outcomes. Instead, while bureaucrats’ behavior during
face-to-face interactions independently affects citizen satisfac­
tion and trust (Eckhard and Friedrich 2024; Hansen 2022),
communicative biases should carry unmediated negative con­
sequences for citizen–state relationships. Future research
should explore this expectation more directly and test whether
subtle patterns in bureaucratic language accumulate across
different institutional contexts and client interactions.
Finally, our analysis reveals that in-group versus out-group con­
stellations do not significantly moderate biased communication
styles. This result stands in contrast to the assumptions of repre­
sentative bureaucracy theory, which posits that shared social iden­
tities foster more constructive interactions and improved
communication (Meier 2019; Raaphorst, Ashikali, and Groeneveld
2025; Webeck and Lee 2022; Guul 2018). One possible explana­
tion is a misalignment between different levels of bureaucratic
behavior: while gender stereotypes may subtly shape language use
even in in-group interactions, discretionary decision-making may
operate at a more deliberate, reflective level that allows for greater
cognitive control. To advance this line of inquiry, future research
should disentangle the cognitive and communicative layers of
bureaucratic practice and explore how identity dynamics play out
differently across verbal interactions and formal administrative
decisions.
Acknowledgments
We would like to thank the editors Ole Helby Petersen and
Kim Sass Mikkelsen as well as three anonymous reviewers for
many helpful comments and suggestions. We presented earlier
versions of this article at several conferences and workshops,
where we obtained valuable feedback, which we gratefully
acknowledge. At the 2024 EGPA conference, the paper received
the Behavioral Public Administration Best Paper Award. We
would also like to thank our colleagues from the research proj­
ect “Inequality in Street Level Bureaucracy: Linguistic Analysis
of Public Service Encounters” at the University of Konstanz as
well as from the research project “Biases in Administrative
Service Encounters: Transitioning from Human to Artificial
Intelligence” at the Zeppelin University Friedrichshafen for
their comments and support.
Supplementary material
Supplementary material is available at Journal of Public
Administration Research and Theory online.
Funding
This work was supported by the German Research Foundation
(Deutsche Forschungsgemeinschaft (DFG), EXC-2035/
1–390681379) and the European Union (ERC, BiASE-AI,
101170283). Views and opinions expressed are, however, those
of the author(s) only and do not necessarily reflect those of the
European Union or the European Research Council. Neither
the European Union nor the granting authority can be held
responsible for them.
Conflicts of interest: None declared.
Data availability
The data underlying this article and the syntax and code used
for the analysis are available at https://doi.org/10.7910/
DVN/9NJH9E.
References
Adam, C., X. Fernández-i-Marín, O. James, A. Manatschal, C. Rapp,
and E., Thomann 2021. “Differential Discrimination Against Mobile
EU Citizens: Experimental Evidence from Bureaucratic Choice Set­
tings.” Journal of European Public Policy 28: 742–60.
Adam, C., S. Grohs, and C. Knill. 2022. “Discrimination Based on Polit­
ical Beliefs: A Field Experiment on the Freedom of Assembly.” Public
Policy and Administration 37: 261–82.
An, C., J. Yu, and X. Tan. 2025. “Public Service Motivation and Policy
Implementation Attitudes: Survey Experimental Evidence from
Street-level Bureaucrats in China.” Public Management Review 1–25.
Andersen, S. C., and T. S. Guul. 2019. “Reducing Minority Discrimination
at the Front Line—Combined Survey and Field Experimental Evidence.”
Journal of Public Administration Research and Theory 29: 429–44.
Assouline, M., and S. Gilad. 2022. “The Intersectionality of Deserving­
ness for State Support.” Public Administration Review 82: 487–502.
Assouline, M., S. Gilad, and P. Ben-Nun Bloom. 2022. “Discrimination
of Minority Welfare Claimants in the Real World: The Effect of
Implicit Prejudice.” Journal of Public Administration Research and
Theory 32: 75–96.
Bargh, J. A., and T. L. Chartrand. 1999. “The Unbearable Automaticity
of Being.” American Psychologist 54: 462.
Bartels, K. 2013. “Public Encounters: The History and Future of Face-to-face
Contact between Public Professionals and Citizens.” Public Administra­
tion 91: 469–83. https://doi.org/10.1111/j.1467-9299.2012.02101.x
Baviskar, S., and S. C. Winter. 2017. “Street-Level Bureaucrats as Indi­
vidual Policymakers: The Relationship between Attitudes and Coping
Behavior toward Vulnerable Children and Youth.” International
Public Management Journal 20: 316–53. https://doi.org/10.1080/10
967494.2016.1235641
Becker, T. E. 2005. “Potential Problems in the Statistical Control of
Variables in Organizational Research: A Qualitative Analysis with
Recommendations.” Organizational Research Methods 8: 274–89.
Bell, E., and K. Smith. 2022. “Working within a System of Administrative
Burden: How Street-level Bureaucrats’ Role Perceptions Shape Access
to the Promise of Higher Education.” Administration and Society 54:
167–211.
Beukeboom, C. J., and C. Burgers. 2019. “How Stereotypes are Shared
through Language: A Review and Introduction of the Social Catego­
ries and Stereotypes Communication (SCSC) Framework.” Review
of Communication Research 7: 1–37.
Bisgaard, M., and M. J. Pedersen. 2022. “Women Cry, Men get Angry:
How Street-level Bureaucrats Respond When Clients Exhibit
Counter-stereotypical Behavior.” International Public Management
Journal 25: 280–99.
Bontrager, S., K. Barrick, and E. Stupi. 2013. “Gender and Sentencing:
A Meta-analysis of Contemporary Research.” The Journal of Gender,
Race, and Justice 16: 349.
Bright, L. 2005. “Public Employees with High Levels of Public Service
Motivation: Who are They, Where are They, and What Do They
Want?” Review of Public Personnel Administration 25: 138–54.


## Page 13

Inequality in frontline communication
13
Bruhn, A., and M. Ekström. 2017. “Towards a Multi‐level Approach on
Frontline Interactions in the Public Sector: Institutional Transforma­
tions and the Dynamics of Real‐time Interactions.” Social Policy and
Administration 51: 195–215.
Coates, J. 2015. Women, Men and Language: A Sociolinguistic Account
of Gender Differences in Language. New York: Routledge.
Coats, S., and E. R. Smith. 1999. “Perceptions of Gender Subtypes:
Sensitivity to Recent Exemplar Activation and In-group/Out-group
Differences.” Personality and Social Psychology Bulletin 25: 516–26.
Correll, S. J., S. Benard, and I. Paik. 2007. “Getting a Job: Is There a Moth­
erhood Penalty?” American Journal of Sociology 112: 1297–338.
Costa,  P. T.Jr, A. Terracciano, and R. R. McCrae. 2001. “Gender Dif­
ferences in Personality Traits Across Cultures: Robust and Surprising
Findings.” Journal of Personality and Social Psychology 81: 322.
Croson, R., and U. Gneezy. 2009. “Gender Differences in Preferences.”
Journal of Economic Literature 47: 448–74.
de Boer, N. 2019. “Street-level Enforcement Style: A Multidimensional
Measurement Instrument.” International Journal of Public Admin­
istration 42: 380–91.
De Houwer, J., S. Teige-Mocigemba, A. Spruyt, and A. Moors. 2009.
“Implicit Measures: A Normative Analysis and Review.” Psycholog­
ical Bulletin 135: 347.
DeHart‐Davis, L., J. Marlowe, and S. K. Pandey. 2006. “Gender Dimen­
sions of Public Service Motivation.” Public Administration Review
66: 873–87.
Demszky, D., D. Movshovitz-Attias, J. Ko, A. Cowen, G. Nemade, and
S. Ravi. 2020. “GoEmotions: A Dataset of Fine-grained Emotions.”
Proceedings of the 58th Annual Meeting of the Association for Com­
putational Linguistics (ACL 2020), 4040–4054.
Döring, M., N. Drathschmidt, and S. P. P. Nielsen 2025. “It Takes (at least)
Two to Tango: Investigating Interactional Dynamics between Clients and
Caseworkers in Public Encounters.” Public Administration Review
85: 419–35.
Dose, N., and D. Strüngmann. 2025. “Are Great Expectations in Bonn and
Berlin Dashed in North Rhine-Westphalia and Baden-Wuerttemberg?
Findings from a Content Analysis and a QCA of 30 Case Studies on the
Implementation of the German Federal Immission Control Law.”
dms–der moderne staat–Zeitschrift für Public Policy, Recht und Man­
agement 17: 218–39.
Eagly, A. H., and V. J. Steffen. 1984. “Gender Stereotypes Stem from the
Distribution of Women and Men into Social Roles.” Journal of Per­
sonality and Social Psychology 46: 735.
Eckhard, S. 2021. “Bridging the Citizen Gap: Bureaucratic Representa­
tion and Knowledge Linkage in (International) Public Administra­
tion.” Governance 34: 295–314.
Eckhard, S., and L. Friedrich. 2024. “Linguistic Features of Public Service
Encounters: How Spoken Administrative Language Affects Citizen
Satisfaction.” Journal of Public Administration Research and Theory
34: 122–35.
Eckhard, S., and L. Friedrich. 2025. “The Language of Public Encoun­
ters: Computational Measures of Complexity and Emotionality in
Spoken Bureaucratic Communication.” Social Policy and Adminis­
tration: 1–12.
Eckhard, S., L. Friedrich, A. Hautli-Janisz, V. Mueden, and I. Espi­
noza. 2024. “A Taxonomy of Administrative Language in Public
Service Encounters.” International Public Management Journal
27: 60–75.
Einstein, K. L., and D. M. Glick. 2017. “Does Race Affect Access to
Government Services? An Experiment Exploring Street‐level Bureau­
crats and Access to Public Housing.” American Journal of Political
Science 61: 100–16.
Elder, L. 2004. “Why Women don’t Run: Explaining Women’s Under­
representation in America’s Political Institutions.” Women and Pol­
itics 26: 27–56.
Ellemers, N. 2018. “Gender Stereotypes.” Annual Review of Psychology
69: 275–98.
Espinoza, I., S. Frenzel, L. Friedrich, W. Siskou, S. Eckhard, and A.
Hautli. 2024. PSE v1. 0: The First Open Access Corpus of Public
Service Encounters. Proceedings of the 2024 Joint International Con­
ference on Computational Linguistics, Language Resources and
Evaluation (LREC-COLING 2024), 13315–20.
Fagerlund, M. 2021. “Gender and Police Response to Domestic Vio­
lence.” Police Practice and Research 22: 90–108.
Fiehler, R. 2002. “How to do Emotions with Words: Emotionality in
Conversations.” In The Verbal Communication of Emotions, edited
by Fussell, Susan R., 79–106. Psychology Press.
Fox, R. L., and J. L. Lawless. 2003. “Family Structure, Sex-Role Social­
ization, and the Decision to Run for Office.” Women and Politics
24: 19–48.
Friedrich, L. 2025. “Coping With Political‐Ideological Pressure: How
Street‐Level Bureaucrats Shield Policy Implementation From Politi­
cization.” Governance 38: 1–13.
Gaia, A. C. 2013. “The Role of Gender Stereotypes in the Social Accept­
ability of the Expression of Intimacy.” The Social Science Journal 50:
591–602.
Gerring, J. 2008. “Case Selection for Case‐study Analysis: Qualitative
and Quantitative Techniques.” In The Oxford Handbook of Political
Methodology, edited by J. M. Box-Steffensmeier, H. E. Brady, and
D. Collier, 646–84. New York: Oxford University Press.
Giles, H., and T. Ogay. 2007. “Communication Accommodation The­
ory.” In Explaining communication: Contemporary Theories and
Exemplars, edited by Whaley B. B. and Samter W., 293–310. Mah­
wah: Lawrence Erlbaum.
Gold, V., M. A. El-Assady, A. Hautli-Janisz, T. Bögel, C. Rohrdantz,
M. Butt, K. Holzinger, et al. 2017. “Visual Linguistic Analysis of
Political Discussions: Measuring Deliberative Quality.” Digital
Scholarship in the Humanities 32: 141–58. https://doi.org/10.1093/
llc/fqv033
Goodsell, C. T. 1981. “The Public Encounter and Its Study.” In The
Public Encounter: Where State and Citizen Meet, edited by C. T.
Goodsell, 3–20. Bloomington: Indiana University Press.
Greenwald, A. G., and M. R. Banaji. 1995. “Implicit Social Cognition:
Attitudes,
Self-esteem,
and
Stereotypes.”
Psychological
Review 102: 4.
Grohs, S., C. Adam, and C. Knill. 2016. “Are Some Citizens More Equal
Than Others? Evidence from a Field Experiment.” Public Adminis­
tration Review 76: 155–64.
Guul, T. S. 2018. “The Individual-Level Effect of Gender Matching in
Representative Bureaucracy.” Public Administration Review 78:
398–408. doi:https://doi.org/10.1111/puar.12907
Guy, M. E., and M. A. Newman. 2004. “Women’s Jobs, Men’s Jobs: Sex
Segregation and Emotional Labor.” Public Administration Review
64: 289–98.
Halling, A., and N. B. G. Petersen. 2024. “Frontline Employees’
Responses to Citizens’ Communication of Administrative Burdens.”
Public Administration Review 84: 1017–37.
Hancock, A. B., and B. A. Rubin. 2015. “Influence of Communication
Partner’s Gender on Language.” Journal of Language and Social
Psychology 34: 46–64.
Hand, L. C. 2021. “A Virtuous Hearer: An Exploration of Epistemic
Injustice and An Ethic of Care in Public Encounters.” Administrative
Theory and Praxis 43: 117–33.
Hand, L. C., and T. J. Catlaw. 2019. “Accomplishing the Public Encounter:
A Case for Ethnomethodology in Public Administration Research.” Per­
spectives on Public Management and Governance 2: 125–37.
Hansen, F. G. 2022. “How Impressions of Public Employees’ Warmth
and Competence Influence Trust in Government.” International Pub­
lic Management Journal 25: 939–61. https://doi.org/10.1080/10967
494.2021.1963361
Harrits, G. S., and M. Ø. Møller. 2014. “Prevention at the Front Line:
How Home Nurses, Pedagogues, and Teachers Transform Public
Worry into Decisions on Special Efforts.” Public Management Review
16: 447–80.
Headley, A. M., and J. E. Wright. 2020. “Is Representation Enough?
Racial Disparities in Levels of Force and Arrests by Police.” Public
Administration Review 80: 1051–62.


## Page 14

14
Friedrich and Eckhard
Hemker, J., and A. Rink. 2017. “Multiple Dimensions of Bureaucratic
Discrimination: Evidence from German Welfare Offices.” American
Journal of Political Science 61: 786–803.
Hildebrand-Edgar, N., and S., Ehrlich 2017. “She was Quite Capable of
Asserting Herself”: Powerful Speech Styles and Assessments of Cred­
ibility in a Sexual Assault Trial.” Language and Law/Linguagem e
Direito 4: 89–107.
Hogg, M. A., D. J. Terry, and K. M. White. 1995. “A Tale of Two The­
ories: A Critical Comparison of Identity Theory with Social Identity
Theory.” Social Psychology Quarterly 58: 255–69.
Holmes, J. 1999. “Women at Work: Analysing Women’a Talk in New
Zealand Workplaces.” Australian Review of Applied Linguistics
22: 1–17.
Holzinger, C. 2020. “|‘We don’t Worry That Much About Language’:
Street-Level Bureaucracy in the Context of Linguistic Diversity.”
Journal of Ethnic and Migration Studies 46: 1792–808.
Jaehrling, K. 2015. “Does the New Managerialism Stabilise Gender
Asymmetries in Street-level Interactions? The Case of Germany after
‘Hartz IV’.” Social Work and Society 13: 1–17.
Jilke, S., and L. Tummers. 2018. “Which Clients are Deserving of Help?
A Theoretical Model and Experimental Test.” Journal of Public
Administration Research and Theory 28: 226–38. https://doi.
org/10.1093/jopart/muy002
Jilke, S., W. Van Dooren, and S. Rys. 2018. “Discrimination and Admin­
istrative Burden in Public Service Markets: Does a Public–Private
Difference Exist?” Journal of Public Administration Research and
Theory 28: 423–39.
Joshi, A., J. Son, and H. Roh. 2015. “When can Women Close the Gap?
A Meta-analytic Test of Sex Differences in Performance and
Rewards.” Academy of Management Journal 58: 1516–45.
Kasdorp, A., and L. Schakel. 2022. “Ambiguous Signaling in Regulatory
Conversations How Miscommunication and Hierarchy Hamper Volun­
tary Regulatee Cooperation.” Administration and Society 54: 903–38.
Keiser, L. R. 1999. “State Bureaucratic Discretion and the Administration
of Social Welfare Programs: The Case of Social Security Disability.”
Journal of Public Administration Research and Theory 9: 87–106.
Kretchmar, J. 2011. “Gender Socialization.” In Gender Roles and Equal­
ity, edited by Salem Press, 41–52. Pasadena/Hackensack: Salem Press.
Kullberg, C. 2005. “Differences in the Seriousness of Problems and
Deservingness of Help: Swedish Social Workers’ Assessments of Sin­
gle Mothers and Fathers.” British Journal of Social Work 35: 373–86.
Kumlin, S., and B. Rothstein. 2005. “Making and Breaking Social Cap­
ital: The Impact of Welfare-state Institutions.” Comparative Political
Studies 38: 339–65.
Lakoff, R. 1973. “Language and Woman’s Place.” Language in Society
2: 45–79.
Lee Badgett, M., and N. Folbre. 2003. “Job Gendering: Occupational
Choice and the Marriage Market.” Industrial Relations: A Journal
of Economy and Society 42: 270–98.
Lindsey, E. W., P. R., Cremeens, and Y. M., Caldera 2010. “Gender
Differences in Mother-toddler and Father-toddler Verbal Initiations
and Responses During a Caregiving and Play Context.” Sex Roles
63: 399–411.
Lindvall-Östling, M., M. Deutschmann, and A. Steinvall. 2020. “An
Exploratory Study on Linguistic Gender Stereotypes and Their Effects
on Perception.” Open Linguistics 6: 567–83.
Lipsky, M. [1980] 2010. Street-level Bureaucracy: Dilemmas of the Indi­
vidual in Public Service. New York: Russell Sage Foundation.
Lofaro, R. J., and A. Sapat. 2025. “Race, Lived Experience, Represen­
tation, and Discrimination: Analyzing the Representative Capacities
of the Racial Majority.” The American Review of Public Adminis­
tration 55: 41–64.
Maynard-Moody, S., and M. Musheno. 2000. “State Agent or Citizen
Agent: Two Narratives of Discretion.” Journal of Public Administra­
tion Research and Theory 10: 329–58.
McCrea, A. M. 2021. “The Cost of Representation: Insurance Status,
Gender, and Cardiac Outcomes in Emergency Department Care.”
Public Administration Review 81: 1092–101.
Meier, K. J. 2019. “Theoretical Frontiers in Representative Bureaucracy:
New Directions for Research.” Perspectives on Public Management
and Governance 2: 39–56.
Meier, K. J. 2023. “Representative Bureaucracy and Social Equity: Bias,
Perceived Fairness and Efficacy.” Journal of Social Equity and Public
Administration 1: 23–38.
Meier, K. J., S. H. Mastracci, and K. Wilson. 2006. “Gender and Emotional
Labor in Public Organizations: An Empirical Examination of the Link
to Performance.” Public Administration Review 66: 899–909.
Mooney, C. Z. 1996. “Bootstrap Statistical Inference: Examples and
Evaluations for Political Science.” American Journal of Political Sci­
ence 40: 570–602.
Moseley, A., and E. Thomann. 2021. “A Behavioral Model of Heuristics
and Biases in Frontline Policy Implementation.” Policy and Politics
49: 49–67.
Moss-Racusin, C. A., J. F. Dovidio, V. L. Brescoll, M. J. Graham, and J.
Handelsman. 2012. “Science Faculty’s Subtle Gender Biases Favor
Male Students.” Proceedings of the National Academy of Sciences
109: 16474–79.
Moynihan, D. P., P. Herd, and H. Harvey. 2014. “Administrative Burden: Learn­
ing, Psychological, and Compliance Costs in Citizen-state Interactions.” Jour­
nal of Public Administration Research and Theory 25: 43–69.
Mulac, A., H. Giles, J. J. Bradac, and N. A. Palomares. 2013. The
gender-linked language effect: an empirical test of a general process
model. Language Sciences 38: 22–31.
Nicholson-Crotty, S., J. A. Grissom, J. Nicholson-Crotty, and C. Red­
ding. 2016. “Disentangling the Causal Mechanisms of Representative
Bureaucracy: Evidence from Assignment of Students to Gifted Pro­
grams.” Journal of Public Administration Research and Theory
26: 745–57.
Nielsen, V. L. 2007. “Differential Treatment and Communicative Inter­
actions: Why the Character of Social Interaction Is Important.” Law
and Policy 29: 257–83.
Nielsen, V. L. 2015. “Personal Attributes and Institutions: Gender and
the Behavior of Public Employees. Why Gender Matters to Not Only
‘Gendered Policy Areas’”. Journal of Public Administration Research
and Theory 25: 1005–29.
O’Barr, W., and B. K. Atkins. 2005. “‘Women’s Language’ or ‘Powerless
Language’?” In Language, Communication and Education, edited
by Mayor B. and Pugh A. K., 202–16. London: Routledge.
Oberfield, Z. W. 2014. Becoming Bureaucrats. Socialization at the Front
Lines of Government Service. Pennsylvania: University of Pennsyl­
vania Press.
Olsen, A. L., J. H. Kyhse‐Andersen, and D. Moynihan. 2022. “The
Unequal Distribution of Opportunity: A National Audit Study of
Bureaucratic Discrimination in Primary School Access.” American
Journal of Political Science 66: 587–603.
Pedersen, M. J., and V. L. Nielsen. 2020. “Bureaucratic Decision‐making:
A Multi‐method Study of Gender Similarity Bias and Gender Stereo­
type Beliefs.” Public Administration 98: 424–40.
Pennebaker, J. W., M. R. Mehl, and K. G. Niederhoffer. 2003. “Psycho­
logical Aspects of Natural Language Use: Our Words, Our Selves.”
Annual Review of Psychology 54: 547–77.
Petrovsky, N., G. Xin, and J. Yu. 2023. “Job Satisfaction and Citizen
Satisfaction with Street-Level Bureaucrats: Is There A Satisfaction
Mirror?” Journal of Public Administration Research and Theory
33: 279–95.
Plug, I., W. Stommel, P. L. Lucassen, S. V. Dulmen, and E. Das. 2021.
“Do Women and Men Use Language Differently in Spoken Face-to-
Face Interaction? A Scoping Review.” Review of Communication
Research 9: 43–79.
Raaphorst, N. 2022. Administrative Justice in Street-level Decision Mak­
ing: Equal Treatment and Responsiveness. In The Oxford Handbook
of Administrative Justice, edited by J. Tomlinson, R. Thomas, M.
Hertogh, and R. Kirkham, 397–413. New York: Oxford Univer­
sity Press.
Raaphorst, N., T. Ashikali, and S. Groeneveld. 2025. “Active Represen­
tation and Equal Treatment: The Influence of Bureaucrats’ Social


## Page 15

Inequality in frontline communication
15
Background on Discrimination.” Social Policy and Administration
59: 20–36.
Raaphorst, N., and S. Groeneveld. 2018. “Double Standards in Frontline
Decision Making: A Theoretical and Empirical Exploration.” Admin­
istration and Society 50: 1175–201.
Raaphorst, N., S. Groeneveld, and S. Van de Walle. 2018. “Do Tax
Officials Use Double Standards in Evaluating Citizen-clients? A
Policy-capturing Study among Dutch Frontline Tax Officials.” Public
Administration 96: 134–53. https://doi.org/10.1111/padm.12374
Raaphorst, N., G. Lotta, E. Lavee, I. Espinoza, E. Thomann, S. Eckhard, A.
Masood, et al. 2025. “Equity and Equality in Street-level Public Service
Delivery.” Perspectives on Public Management and Governance: 1–13.
Raaphorst, N., and K. Loyens. 2020. “From Poker Games to Kitchen
Tables: How Social Dynamics Affect Frontline Decision Making.”
Administration and Society 52: 31–56.
Ropes, E., and N. de Boer. 2021. “Compassion Towards Clients: A Scale
and Test on Frontline Workers’ Burnout.” Journal of European Public
Policy 28: 723–41.
Schwartz, S. H., and T. Rubel. 2005. “Sex Differences in Value Priorities:
Cross-cultural and Multimethod Studies.” Journal of Personality and
Social Psychology 89: 1010.
Simon, H. A. 1947. Administrative Behavior: A Study of Decision-Making
Processes in Administrative Organizations. New York: Macmillan.
Siskou, W., L. Friedrich, S. Eckhard, I. Espinoza, and A. Hautli-Janisz.
2022. Measuring Plain Language in Public Service Encounters. Pro­
ceedings of the 2nd Workshop on Computational Linguistics for
Political Text Analysis (CPSS-2022), 27–35.
Sleath, B., and R. H. Rubin. 2002. “Gender, Ethnicity, and
Physician–patient Communication about Depression and Anxiety in
Primary Care.” Patient Education and Counseling 48: 243–52.
Stensöta, H. O. 2010. “The Conditions of Care: Reframing the Debate
About Public Sector Ethic.” Public Administration Review 70: 295–303.
Tajfel, H., and J. C. Turner. 2004. “The Social Identity Theory of Inter­
group Behavior.” In Political Psychology, edited by Jost, J. T. and
Sidanius, J., 276–93. New York: Psychology Press.
Tannen D. 1990. “Gender Differences in Topical Coherence: Creating
Involvement in Best Friends’ Talk.” Discourse Processes 13: 73–90.
Thomann, E., P. Hupe, and F. Sager. 2018. “Serving Many Masters:
Public Accountability in Private Policy Implementation.” Governance
31: 299–319.
Thomann, E., O. James, and T. Deruelle 2025. “Interventions to Reduce
Bureaucratic Discrimination: A Systematic Review of Empirical
Behavioral Research.” Public Management Review 27: 1959–86.
Thomann, E., and C. Rapp. 2018. “Who Deserves Solidarity? Unequal
Treatment of Immigrants in Swiss Welfare Policy Delivery.” Policy
Studies Journal 46: 531–52.
Thunman, E., M. Ekström, and A. Bruhn. 2020. “Dealing with Ques­
tions of Responsiveness in a Low-discretion Context: Offers of
Assistance in Standardized Public Service Encounters.” Administra­
tion and Society 52: 1333–61.
Traum, D. R., and P. A. Heeman. 1996. “Utterance Units in Spoken
Dialogue.” Paper presented at the Workshop on Dialogue Processing
in Spoken Language Systems, Budapest. Retrieved from: https://www.
cs.rochester.edu/research/cisd/pubs/1996/traum-heeman-ecai96.pdf.
Tummers, L., V. Bekkers, E. Vink, and M. Musheno. 2015. “Coping
During Public Service Delivery: A Conceptualization and Systematic
Review of the Literature.” Journal of Public Administration Research
and Theory 25: 1099–26.
Turner, J. C., P. J. Oakes, S. A. Haslam, and C. McGarty. 1994. “Self
and Collective: Cognition and Social Context.” Personality and Social
Psychology Bulletin 20: 454–63.
van Oorschot, W. 2000. “Who Should Get What, and Why? On Deserv­
ingness Criteria and the Conditionality of Solidarity Among the Pub­
lic.” Policy and Politics 28: 33–48.
Voigt, R., N. P. Camp, V. Prabhakaran, W. L. Hamilton, R. C. Hetey, C.
M. Griffiths, D. Jurgens, et al. 2017. “Language from Police Body
Camera Footage Shows Racial Disparities in Officer Respect.” Pro­
ceedings of the National Academy of Sciences 114: 6521–26.
Waara, E., and P. Shaw. 2006. “Male and Female Witnesses’ Speech in
Swedish Criminal Trials.” HERMES-Journal of Language and Com­
munication in Business 19: 129–56.
Watkins-Hayes, C. 2009. The New Welfare Bureaucrats: Entanglements of
Race, Class, and Policy Reform. Chicago: University of Chicago Press.
Watkins-Hayes, C. 2011. “Race, Respect, and Red Tape: Inside the Black
Box of Racially Representative Bureaucracies.” Journal of Public
Administration Research and Theory 21(suppl_2): i233-51. https://
doi.org/10.1093/jopart/muq096
Webeck, S., and H. Lee. 2022. “The Behavioral Foundations of Repre­
sentative Bureaucracy.” Perspectives on Public Management and
Governance 5: 209–21.
White , R. D.Jr 1999. “Are Women More Ethical? Recent Findings on
the Effects of Gender Upon Moral Development.” Journal of Public
Administration Research and Theory 9: 459–72.
Wienclaw, R. A. 2011. “Gender Differences: Biology and Culture.” In
Gender Roles and Equality, edited by Salem Press, 15–23. Pasadena/
Hackensack: Salem Press.
Wilkins, V. M., and B. N. Williams. 2008. “Black or Blue: Racial Profiling
and Representative Bureaucracy.” Public Administration Review
68: 654–64.
Zhang, Y. 2025. “Governance in Layers: How Female Street-level
Bureaucrats Reshape State Power Through Emotional Labor.” Jour­
nal of Public Administration Research and Theory 35: 323–37.
Zhou, M., J. Ju, W. Yuan, L. Liu, and Y. Feng. 2025. “Exploring the
Roles of Informational and Emotional Language in Online Govern­
ment Interactions to Promote Citizens’ Continuous Participation.”
Public Performance and Management Review 48: 1–29.

