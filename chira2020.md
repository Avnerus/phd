---
title: THE TELEPRESENCE ROBOT CONTACT HYPOTHESIS
date: 08/2020
author:
 \authorname{Avner Peled  \sup{1}\orcidAuthor{0000-0002-0525-6385}, Teemu Leinonen\sup{1}\orcidAuthor{0000-0002-6227-052X} and Béatrice Hasler\sup{2}\orcidAuthor{0000-0002-3251-4677}}
 \affiliation{\sup{1}Department of Media, Aalto University, Espoo, Finland}
 \affiliation{\sup{2}Sammy Ofer School of Communications, Interdisciplinary Center Herzliya, Herzliya, Israel}
 \email{\{f\_author, s\_author\}@aalto.fi, t\_author@idc.ac.il}
documentclass: scitepress-article
classoption:
  - twoside
  - a4paper
biblio-style: apalike
bibliography: aalto.bib       
header-includes: |
   \usepackage{epsfig}
   \usepackage{calc}
   \usepackage{amssymb}
   \usepackage{amstext}
   \usepackage{amsmath}
   \usepackage{amsthm}
   \usepackage{multicol}
   \usepackage{pslatex}
   \usepackage{apalike}
   \usepackage{SCITEPRESS}

   \keywords{Intergroup Contact,Human-Robot Interaction,Conflict Resolution}

   \abstract{We propose the use of telepresence robots as a medium for intergroup contact, reducing prejudice between social groups. In this conceptual work, we argue for robots as a midpoint between online communication and a face-to-face meeting, combining the flexibility of the virtual world and the depth of physical interactions. We outline a path model for evaluating the result of robot-mediated encounters and define the basic architecture of telepresence systems. We then provide basic design guidelines for telepresence systems with intergroup contact in mind. Emphasis is placed on achieving equality, avoiding dehumanization, maintaining group salience, and enabling translated communication.}
...
---

# INTRODUCTION
The pervasive role of technology in intensifying the ability of humans to harm one another is well known; the use of technology to promote peace at both the collective and personal levels is considerably more modest. Over the years there have been calls within the Human-Computer Interaction research community to promote the use of technology to support peace in world conflicts [@hourcadeHCIPeaceCall2011;@eckertIndustryTrends20402019]. Often when people think of a technological contribution to conflict resolution, the emphasis is placed on decision support and negotiation for policymakers and national leaders. A different approach that is taken in the current paper, is using technology to reconcile the ‘common’ people in a situation of conflict and build more positive intergroup relations from the bottom up.
 
One of the most prominent models that act as a guideline for this approach is the contact hypothesis [@allportNaturePrejudice1954], which states that under the right conditions, encounters with members of the opposing group (i.e., the outgroup) can lead to reduced prejudice and more harmonious intergroup relations. We propose using robots as a communication medium for such contact, as they combine both the flexibility and accessibility of online communication and the corporeality of face-to-face encounters in a shared physical space.

# 1. Intergroup contact hypothesis
 
The contact hypothesis as formulated by Gordon Allport in his seminal book _The Nature of Prejudice_ [-@allportNaturePrejudice1954] specifies four conditions that need to be fulfilled during positive intergroup contact: equal status, having common goals, active cooperation, and institutional support. Fifty years later, a meta-analysis across more than 500 studies in a variety of intergroup contexts [@pettigrewMetaanalyticTestIntergroup2006] has revealed that contact is an effective means to reduce prejudice. However, the meta-analysis has also shown that Allport’s conditions are not strictly essential for a positive outcome, rather they are factors among others that facilitate it. Later research focused on expanding the theory to more conditions such as forming cross-group friendships [@cookSystematicAnalysisSocially1962] and identified affective drivers, such as empathy and anxiety, that play a mediating role in contact interventions [@pettigrewRecentAdvancesIntergroup2011;@brownIntegrativeTheoryIntergroup2005]. An additional factor that moderates the outcome of contact is _group salience_, the degree in which the participants' group identity is salient. A high level of group salience facilitates the generalization of attitudes from the interpersonal level to the group level [@vociIntergroupContactPrejudice2003].
 
  
## 1.1 Online contact
 
Communication technologies expand the models of contact and add new modalities of interaction while compromising on the benefits of traditional face-to-face (FtF) encounters. Research on online intergroup contact has shown its potential to reduce prejudice and aid in conflict resolution [@amichai-hamburgerStructuredUnstructuredIntergroup2015;@haslerOnlineIntergroupContact2013;@waltherComputermediatedCommunicationReduction2015]. However, online contact is not always constructive. The distant nature of the remote medium makes participants less accountable for their actions and less engaged in the conversation [@whiteImprovingIntergroupRelations2015;@schumannWhenComputermediatedIntergroup2017]. The lack of non-verbal cues [@burgoonNonverbalSignals1994] obstructs the path to a mutual understanding and impairs the turn-taking process, which may evoke negative feelings between the group members such as anger and frustration [@johnsonAngerFlamingComputermediated2009].
 
Virtual reality (VR) has been studied as a medium that offers an immersive communication experience that increases the user’s sense of involvement in the situation [@kilteniSenseEmbodimentVirtual2012]. It was positively evaluated for use in intergroup contact, both as a space for dialog [@haslerVirtualPeacemakersMimicry2014], and as a tool that allows individuals to immerse themselves in the perspective of the other side [@hassonEnemyGazeImmersive2019;@kabiljoVirtualRealityFostering2019]. However, along with its promise, VR also raises a number of ethical and moral concerns. While the experience of ‘being’ in the virtual space intensifies as the technology develops, our corporeal body is ‘left behind’ as we subsume an abstract representation as our new reality [@pennyVirtualBodybuilding1993]. This quintessential mind-body split may alter one’s relation to corporeality, leading to mental disorders such as _depersonalization_ and _derealization_ or bodily neglect [@spiegelEthicsVirtualReality2018]. Additionally, immersive perspective-taking risks in assuming an ‘improper distance’ [@chouliarakiImproperDistanceCritical2011;@nashVirtualRealityWitness2018] between the viewer and the out-group member, in which one subordinates the other, incorporating their representation, rather than recognizing their irreducible alterity.  
 
Critical theorists have long warned against an abstraction of human nature. Terms such as _reification_, _rationalization_, and _fetishism_ are used to describe the underlying condition of prejudice, where virtual, invisible properties are incorrectly assigned to a material being [@marxCapitalCritiquePolitical2015;@lukacsReificationConsciousnessProletariat2017;@silvaReificationFetishismProcesses2013;@horkheimerEclipseReason2004;@juttenColonizationThesisHabermas2011;@ahmedStrangeEncountersEmbodied2000]. At the same time, the constituting role of the body in forming social cognition is highlighted across a variety of disciplines
[@deweyExperienceEducation1986;
@gallagherHowBodyShapes2006;
@malafourisHowThingsShape2013]. Yet, despite these intuitions and the inherent abstraction of virtual mediums, little attention has been given to robots as a tool for intergroup contact. Remotely controlled robots (telerobots) are a communication medium nonetheless, but they exist and interact with the physical world; we use our body to interact with robots as we would with a living being. Robots provide at least partial corporeal depth to mediated contact, setting a midpoint between online communication and an FtF meeting.
 
Robots can also occupy public spaces, transcending both physical borders and virtual bubbles, allowing spontaneous and organic encounters to occur without authoritative regulation. Users of social media are typically exposed to like-minded people and consume biased news items that contribute to group polarization and an increase of prejudice [@delvicarioEchoChambersEmotional2016]. By opening intergroup contact to remote public spaces, this phenomenon known as ‘echo chambers’ can be mitigated. We consider the above advantages sufficient to introduce and evaluate the use of robots for intergroup contact, and for this first milestone, we formulate a conceptual framework for telepresence intergroup contact and propose initial design considerations.
 
# 2. Terminology and scope

Originally, the term _telepresence_ was used by Marvin Minsky and Patrick Gunkel to describe a vision of a futuristic economy in which people perform manual, physical labor from remote locations [@minskyTelepresence1980]. Although the term is also used nowadays to describe a human's presence in a virtual environment [@steuerDefiningVirtualReality1992], telepresence originally refers to the experience of being in a remote environment that is _real_ and mediated by a physical sensing agent, i.e, a _telerobot_. [@campanellaEdenWireWebcameras2000; @kacTelepresenceBioArt2005]. In phenomenological terms, the experience of operating a telerobot is dubbed _re-embodiment_ [@dolezalRemoteBodyPhenomenology2009]. Today's telerobots go beyond industrial use and are deployed in social care [@michaudTelepresenceRobotHome2007], education [@tanakaTelepresenceRobotHelps2014], and interpersonal communication [@ogawaTelenoidTelepresenceAndroid2011], utilizing the internet as the medium for tele-operation.
 
When a telerobot poses as a remote manifestation of a human operator, it is referred to as its _avatar_; the human operator could then be referred to as the _inhabiter_ of that avatar. An avatar is an antonym for _agent_, a computer-controlled entity that acts autonomously without any human intervention. A telerobot is usually, however, _semi-autonomous_: its actions are predominantly decided by the human operator, but at the same time are supported by machine-controlled algorithms. A semi-autonomous telerobot is sometimes referred to as a _surrogate_ [@hughesHumanSurrogatesRemote2014;@nagendranSymmetricTelepresenceUsing2015], a combination of agent and avatar.
 
# 3. A path model for telepresence contact
 
Previous research on intergroup contact provides us with conceptual and computational tools that we can use to model the path from initial contact to the eventual reduction of prejudice toward the out-group. The model suggested by Pettigrew [-@pettigrewIntergroupContactTheory1998] outlines a longitudinal path to prejudice reduction over time: contact initially _decategorizes_ the individual out-group member from its group, then reduces prejudice from the general out-group, and finally dissolves the border between in-group and out-group. Researchers have also formulated empirical models that can predict and verify the link between common mediators such as anxiety and empathy, or mediators such as group salience to the outcome of the contact [@vociIntergroupContactPrejudice2003;@brownIntegrativeTheoryIntergroup2005;@pagottoEffectivenessIntergroupContact2010].
 
Based on these models, we suggest a conceptual model for telepresence contact. Due to the presence of the telerobot, we add another stage on the path to prejudice reduction (see [@fig:path_model]). We hypothesize that an in-group member first develops an attitude toward the robot representing the out-group member, before projecting it onto the members. Attitude toward the robot could be influenced by a previous bias towards robots or by characteristics of the particular robot. We expect that the perception of the robot as a representation of the operator's agency is moderated by the degree of perceived _co-presence_. Initially formulated by Goffman as a measure of our awareness of another human being in our physical space [@goffmanBehaviorPublicPlaces2008], the term is now used in literature to measure the feeling of "togetherness" in mediated communication, virtual [@soeffnerCopresenceSharedVirtual2007;@casanuevaEffectsAvatarsCopresence2001;@benteAvatarMediatedNetworkingIncreasing2008], and physical [@hwangAugmentedRobotAgent2008;@choiWhoThisIdentity2017]. Co-presence differs from the term _social presence_ insofar as social presence refers to people's perception of the medium as a social sphere, rather than their recognition of sharing a space with another [@buluPlacePresenceSocial2012;@nowakDefiningDifferentiatingCopresence2001].
Finally, as previous research on intergroup contact suggests [@vociIntergroupContactPrejudice2003;@brownIntegrativeTheoryIntergroup2005;@kenworthyIntergroupContactWhen2005], a generalized attitude toward the out-group will be moderated by the level of group salience apparent in the conversation.

The hypotheses presented in this article are partially based on observations from an initial test we conducted on intergroup telepresence contact [@peledSoftRoboticIncarnation2019]. The test system included one remotely controlled telerobot that facilitated conversations between immigrants and local participants. Qualitative results were analyzed through post-session interviews.
 
![Telepresence Contact: Conceptual path model](./path_model_v2.jpg){#fig:path_model}
 
# 4. Telepresence systems
 
A communication event that is mediated by telepresence robots could manifest in different architectures that we define as _telepresence systems_.
 
Utilizing concepts from Paynter's generalized systems theory [@paynterAnalysisDesignEngineering1961;@hannafordFeelingBelievingHistory2000], two types of interaction that occur in telepresence, _signal_, and _physical_. _Physical_ interactions refer to real word interactions between elements sharing a physical environment, such as a hand-shake or holding an object. _Signal_ interactions, on the other hand, occur on an abstract level. They represent a unidirectional logical flow of cause and effect; for example, text that is typed on one end of online communication and appears on the other end.
 
Based on these concepts, we identify three different types of telepresence systems [see @fig:sym_asym]:
 
1. _Asymmetric_: The most commonly used system for telepresence communication. Participant A (operator) is represented by a telerobot and is operating it from a remote location using a computer or mobile device. Participant B (interlocutor) is co-located with the robot, interacting with it in a shared physical environment. Common implementations of this asymmetric scenario include industrial robots, military robots, surgical robots, office work telepresence, and social service robots
 
2. _Symmetric bidirectional_: In this system, both participants are interacting with a co-located telerobot and at the same time operating a remote telerobot. The robot in front of each participant serves both as an avatar for their conversation partner, as well as a control interface for their telerobot on the other side. Since it is not possible to divide one’s attention between interaction and operation without hindering the experience, the operating interface should be transparent for the user, typically using body tracking and other physical sensors. Currently, only a few implementations exist as prototypes and proofs-of-concept [@nagendranSymmetricTelepresenceUsing2015]. 
 
3. _Symmetric unidirectional_: In a symmetric unidirectional system both participants are operating a telerobot via a control interface, without physically interacting with an avatar. The two robots are co-located, while the participants are in separate spaces. Common implementations of this system include cooperative multi-robot tasks [@sirouspourMultioperatorMultirobotTeleoperation2005] and _Robot combat_ competitions [@clarksonBattleBotsOfficialGuide2002].
 
![Systems of telepresence communication](sym_asym_v4.jpg){#fig:sym_asym}
 
# 5. Telepresence design considerations for intergroup contact

Design considerations for robot-mediated intergroup contact partially overlap with those of standard Human-Robot-Interaction (HRI) and telepresence. The following sections emphasize possible pitfalls and opportunities one may encounter while striving for a reduction of prejudice in intergroup contact.

## 5.1 Equality 
 
One of Allport’s basic conditions for positive intergroup contact is having an equal status between group members, such as an equal position in a workplace context [@allportNaturePrejudice1954]. It was shown that having symmetry and equality in communication is beneficial for contact in groups that are in asymmetric conflict such as the Israeli-Palestinian conflict [@maozEvaluatingCommunicationGroups2005]. 
 
Symmetric telepresence systems provide the hardware foundation for equal contact, but asymmetric systems produce an experience that is different in nature on each side. The side that is interacting with the robot may experience stronger senses of _agency_ (the sense
that I am the initiator of an act) and _ownership_ (the sense that it is my body that is moving) in the conversation [@gallagherPhilosophicalConceptionsSelf2000;@coleImmunityPrincipleView2000], while the side that is operating from a distance may exhibit behaviors characterizing anonymous computer-mediated-communication (CMC) such as the _SIDE_ model [@spearsWhenAreNet2002] or the _hyperpersonal_ model
[@waltherComputermediatedCommunicationImpersonal1996].
 
In a plausible scenario, a disadvantaged-group member is operating a telerobot anonymously from their home, while the advantaged-group member is interacting with it in a public space. The operator may feel free of social anxiety in their comfort zone and empowered by the ability to see through the robot's camera and not be seen. This in turn may encourage bringing up more difficult topics related to conflict during the conversation. However, the asymmetry in the participant's agency may also bring up anxiety and discomfort. In our initial test case, participants of both sides expressed discomfort regarding the unequal asymmetric setting. One member of a minority group noted that they felt as if they were a government official investigating their exposed partners [@peledSoftRoboticIncarnation2019, p.132].
 
## 5.2 Anthropomorphism and dehumanization
 
The effect of a robot's appearance on a human's attitude toward it has been studied extensively in the literature, predominantly in studies of Human-Robot Interaction (HRI) and social robotics [@hancockMetaAnalysisFactorsAffecting2011]. A pivotal discussion revolves around the question of _anthropomorphism_: the degree in which a robot's appearance and behavior resemble that of a human. Current literature paints a picture that is manifold [@finkAnthropomorphismHumanLikeness2012]; while anthropomorphic features may increase a human's empathy toward and acceptance of the robot, the effect is context and culturally-dependent. In some cases, people have preferred pet-shaped over human-like robots or developed negative attitudes toward anthropomorphic robots. 
 
The question of anthropomorphism becomes more pertinent in the context of intergroup contact, as dehumanization: seeing an out-group member as non-human or less than human, is both a marker and a driver for intergroup-conflict [@haslamDehumanizationIntegrativeReview2006;@kteilyTheySeeUs2016]. Specifically, group members tend to view the out-group members as either animal-like or mechanistic automata, both common forms for robots. Current research does not yet deal with the effects of avatar anthropomorphism on intergroup conflict, but evidence from video games points out that people find it easier to make immoral decisions toward non-human avatars [@linEffectOpponentType2011]. Additionally, the distance formed by CMC was found to increase dehumanization in decision making [@leeMakingDecisionsDistance2015]. If choosing a zoomorphic, mechanistic, or caricaturistic image for the telerobot, dehumanization trends should be assessed concerning the particular intergroup scenario.

## 5.3 Designing with group salience in mind
 
The process toward forming a generalized opinion toward the out-group does not end at the interpersonal level. The most widely agreed-upon moderator for generalizing a positive attitude to the intergroup level is _group salience_. One approach, suggested by Pettigrew [-@pettigrewIntergroupContactTheory1998], is to expose group identities gradually, starting with a low salience, allowing initial contact to form, and increasing it over time as the interaction partners establish an interpersonal relationship.
 
Group identity can be transmitted through a variety of channels in telepresence, beginning with the design of the avatar; its appearance, voice, and its surroundings, and proceeding into the content of the interaction. An avatar may have a non-humanoid appearance, but still maintain group identity through group symbols, cues, language, and so forth. It may speak in an accent, wear typical accessories or flaunt national colors. The freedom to use material objects brings up new design possibilities that are not available in an online encounter. Group cues could be positioned in subtle ways so that they are gradually revealed by the interlocutor. If the initial appearance and behavior of the robot are engaging enough, an interpersonal bond may be formed despite the presence of group-related cues.

## 5.4 Language translation
 
The outstanding benefit of mediated verbal interaction for intergroup contact is the ability to translate between different languages and dialects [@amichai-hamburgerReducingIntergroupConflict2012]. This has significance since often groups in conflict do not speak a common language and only know about the other side from the mass-media that may propagate biased views. Language translation may also reinforce equality in communication, whereas each group adjusts itself to the native language of the other, and no dominant language is used. Machine translation, however, may also be destructive to cultural and political nuances [@lehman-wilzigTowerBabelVs2000;@croninTranslationDigitalAge2012], and contemporary deep-learning translators exhibit stylistic and gender bias based on their training datasets [@hovyCanYouTranslate2020;@stanovskyEvaluatingGenderBias2019]. Models such as Timo Honkella's "peace machine" [@honkelaRauhankoneTekoalytutkijanTestamentti2017;@kouluHowWillAI2019] attempt to resolve this problem by preserving cultural-dependent meanings within a translation. While no data exist so far on the negative implications of machine translation in intergroup contact, it is known that mediating human translators and interpreters suffer from a lack of trust by the participants who worry that their voice will not be heard [@monzo-nebotTranslatorsInterpretersAgents2019, p.22]. In our initial test for automatic language translation in contact, participants enjoyed their newly acquired ability to speak another language, but have raised concerns of being misrepresented by the machine [@peledSoftRoboticIncarnation2019]. Further research would focus on implementing various feedbacks on the translation process that may help relieve the fear of misrepresentation.

## 5.5 Public space interventions
 
Robots can transcend national borders and occupy spaces, having the potential to reach crowds that wouldn't normally engage in intergroup contact. One might consider whether the group identity of the telerobot's operator should be widely exposed to passersby, allowing them to make a voluntary decision to approach, or whether they would first approach the robot and only realize its group identity during the conversation. A meta-analysis by Pettigrew et al [-@pettigrewRecentAdvancesIntergroup2011] concluded that in contacts that had a negative outcome, it was worse when the contact was initiated involuntarily. However, when the group identity is known, members may avoid interaction [@wesselDoesDiversityUrban2009], which results in a self-selection bias in organized interventions between groups [@maozDoesContactWork2011]. A balanced approach may work well here: Some cues could be exposed, providing only hints about the telerobot's identity, allowing passersby to approach an intergroup encounter voluntarily.

# 6. Discussion

The guidelines set forth in this article provide a foundation for further research and implementation of a new and exciting medium for intergroup contact. While any organized attempt for intergroup contact should always be questioned and scrutinized regarding its internal motivation, this is especially true in the context of violent, asymmetric conflicts, where one group is a dominant majority and another is an oppressed minority, and even more so when technology is involved with its inherent biases and connotations of power. The practice of _Co-Design_ can increase the involvement of minority groups in the process, disseminate technological knowledge, and reduce the notion of a larger power that comes from above to restore peace without perceiving the situation and its nuances.

Moreover, Groom et al showed that operators had a greater sense of self-extension to a robot that was assembled by them, rather than by another [@groomAmMyRobot2009]. Robots were also successfully co-designed with children as the target users [@alves-oliveiraYOLORobotCreativity2017;@henkemansCodesignPalRobot2016], and co-design methods improved the general attitude of students toward robots in educational settings [@reich-stiebertInvolveUserChanging2019]. We look forward to evaluating telepresence robots as a means for positive social change.
 
# References
\bibliographystyle{apalike}
\small