---
title: The telepresence contact hypothesis
author: Avner Peled
date: 04/2020
documentclass: cas-dc
indent: true
biblio-style: cas-model2-names
bibliography: aalto.bib   
abstract: Abstract goes here Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here  Abstract goes here       
header-includes: |
    \usepackage[square,numbers]{natbib}
...
---

\title[mode=title]{}

\author[1,2]{Avner Peled}[type=editor,
    auid=000,bioid=1,
    prefix=Sir,
    role=Researcher,
    orcid=0000-0001-7511-2910,
    facebook=<facebook id>,
    twitter=<twitter id>,
    linkedin=<linkedin id>,
    gplus=<gplus id>]

\begin{keywords}
 Soft robotics \sep Second keyword \sep Third keyword \sep Fourth keyword
\end{keywords}

\maketitle

General introduction paragraph  
Recognizing other uses for robots in contact, such as FtF mediator and simulated contact.
Defining the scope of the work:

- Intergroup contact with emphasis on prejudice in asymmetric, conflicted groups.
- At least one group member is physically interacting with a robot in a shared space, which is operated by a member of the opposing group.


# 1. Intergroup contact hypothesis

## 1.1 Contact hypothesis

Review, leading into the need and rise of mediated contact, of which online is most prominent



## 1.2 Online contact

Review, leading into the issues with current online contact:

## 1.3 Issues with online contact

1. Lack of self-accountability

"individuals may feel less accountable for the content they post online or underestimate the social sanctioning of their behavior" [@whiteImprovingIntergroupRelations2015]

2.  Lack of engagement with a reduced social presence

 “Out-group members' reduced social presence was further associated with negative out-group attitudes, notably because the intergroup interaction itself was considered as less interesting, satisfying, cheerful, and involving” [@schumannWhenComputermediatedIntergroup2017]

3. Lack of physical turn taking cues.

"a delayed response in an interaction can also work to incite tension in the intergroup relationship...This is particularly pertinent point for online interactions where there can be a lack of physical cues" [@whiteImprovingIntergroupRelations2015]

4. Lack of opportunity for contact 
Not much opportunities for online contact, especially in the age of filter bubbles and echo chambers.

Leading into proposing telepresence robot contact as a midway between online and face to face which could solve a lot of the issues with online contact but preserve some of its benefits.

# 2. Telepresence robots

History and terminology:

- telerobot, telepresence, tele-operation, avatar, re-embodiment.
 
-  fully operated / semi-autonomous functions

# 3. A path model for telepresence contact

Previous research on intergroup contact provides us with conceptual and computational tools which we can use to model the path from initial contact to the eventual reduction of prejudice toward the generalized out-group. The stages model suggested by Pettigrew [@pettigrewIntergroupContactTheory1998] outlines the path to prejudice reduction: contact initially _decategorizes_ the individual out-group member from its group, then reduces prejudice from the general out-group, and finally dissolves the border between in-group and out-group. Researches have also shown empirically verifiable models for various mediators and moderators involved in prejudice reduction [@vociIntergroupContactPrejudice2003;@brownIntegrativeTheoryIntergroup2005;@pagottoEffectivenessIntergroupContact2010].

Inspired by those findings, we suggest a conceptual model for telepresence contact. Due to the presence of the telerobot, we add another stage on the path to prejudice reduction [@fig:path_model]. We hypothesize that an in-group member first develops an attitude toward the robot itself before projecting it on the operating out-group member. Attitude toward the robot could be influenced by previous bias on robots or by characteristics of the particular robot which we will analyze in this article. We estimate that the perception of the robot as a representation of the operator's agency is moderated by the degree of _co-presence_. Initially formulated by Goffman as a measure of our awareness to another human being in our physical space [@goffmanBehaviorPublicPlaces2008], the term is now used in literature to measure the feeling of "togetherness" in mediated communication. Co-presence is mostly discussed in relation to virtual environments and online avatars [@soeffnerCopresenceSharedVirtual2007;@casanuevaEffectsAvatarsCopresence2001;@benteAvatarMediatedNetworkingIncreasing2008], but has also been briefly addressed in telepresence robot scenarios [@hwangAugmentedRobotAgent2008;@choiWhoThisIdentity2017]. A high level of co-presence with the remote operator in robot-mediated communication would indicate that they are being veritably transported to the physical space of the interlocutor. It requires a willing, or spontaneous, _suspension of misbelief_ by the interlocutor that they ar talking to a human consciousness that is embodied within the robot. Finally, as previous research on intergroup contact suggests, a generalized attitude toward the out-group will be moderated by the level of group salience apparent in the conversation. The following sections mention various methods in which group salience could be highlighted in a telepresence robot scenario.

![Telepresence Contact: Conceptual path model](./path_model_v2.jpg){#fig:path_model} 


# 4. Telepresence systems

A communication event that is mediated by telepresence robots could manifest in one of many different architectures. A single architecture  could be defined as a _telepresence system_. 

## 4.1 Signal and physical interactions

Before presenting the systems in focus for intergroup contact, we define two types of interactions that can exist within such system. 
Utilizing concepts from Paynter's generalized systems theory [@paynterAnalysisDesignEngineering1961], Hannaford has distinguished between the two types of interaction that occur in telepresence, _information_ and _energetic_ [@hannafordFeelingBelievingHistory2000]. We will  refer to them simply as _signal_ and _physical_ interactions. _Physical_ interactions refer to real word interactions between elements sharing a physical environment, such as a hand-shake or holding an object. In physical terms, a bidirectional _energy bond_ is formed between the interacting elements. _Signal_ interactions, on the other hand, occur on an abstract level. They represent a unidirectional logical flow of cause and effect; for example, text that is typed on one end of an online communication and appears on the other end. Intuitively, a physical interaction appears closer and more significant than a flow of signals because it involves our body. The tight bond between our cognition and our physicality is shown in a variety of conceptual frameworks [@deweyExperienceEducation1986;
@gallagherHowBodyShapes2006
@malafourisHowThingsShape2013] that reject the old cartesian dualism of a mind that is separated from the body. 

In online communication, a signal would always be a reduction and an abstraction of the physical action that caused it. When operating a telerobot through a remote control interface, the flow consists of three stages:
1. Beginning with an intent for action, a physical interaction occurs between the operator and a local control interface. 
2. Control signals are sent through a communication medium to the robot. 
3. The robot receives the signal, processes it and performs an physical interaction with its own environment. 

According to Minsky, when the control interaction is so seamless and synchronous with the robot in terms of responsiveness and feedback, the operator may feel as if they are physically present in the remote environment, i.e  _telepresence_.

## 4.2 Types of systems

If we consider solely the condition of _telepresence_, that is, having a telerobot operated remotely and used for communication, we identify three different systems of communication [see @fig:sym_asym]:

1. _Asymmetric_: The most commonly used system for telepresence communication. One participant is represented by a telerobot and is operating it from a remote location, typically their home, using a computer or mobile device. The other participant is interacting with the robot in a shared physical space. The system is asymmetric because the interaction experience is qualitatively different for the operator and the interlocutor. Common implementations include industry robots, surgical robots, office-based telepresence and social service robots.

2. _Symmetric bidirectional_: In this system both participants are operating a telerobot, which serves both as an avatar for their conversation partner as well a control interface for their telerobot. The interface, in that case, is completely transparent to the operator and typically uses body tracking. No control feedback is available to the operator and operation may commence without any knowledge of the remote telerobot by the participants. This type of system is more resource-heavy than the asymmetric type, and currently only a few implementations exist as prototypes and proofs-of-concept [@nagendranSymmetricTelepresenceUsing2015]. The lack of feedback in this system also heavily restricts the ability of the operator to travel around the space, as they are unable to see the remote environment.

3. _Symmetric unidirectional_: In this system both participants are operating a telerobot via a control interface, without physically interacting with an avatar. The two robots share the same space, while the participants are separated. Common implementations of this system include cooperative multi-robot tasks [@sirouspourMultioperatorMultirobotTeleoperation2005] and _Robot combat_ competitions [@clarksonBattleBotsOfficialGuide2002].As in the asymmetric system, operation is usually performed from a computer or mobile device. 

![Systems of telepresence communication](sym_asym_v4.jpg){#fig:sym_asym}


While the _symmetric unidirectional_ system may facilitate contact in cooperative or confrontational events in front of an audience, since the scope of this article involves at least one person physically interacting with a robot, we would turn the focus toward the first two systems.

## 4.3 The handshake paradigm

To further illustrate the mechanics of the two systems, we will use the common example of the handshake. The handshake is an important and common social gesture in most parts of the world [@schiffrinHandworkCeremonyCase1974]. It is a reciprocal action, beginning with one person reaching out in an open request and then reciprocated by the partner. It is also a haptic gesture in which subtle forms of touch can have a great social significance [@hillewaertTacticsTactilitySensory2016].

In an asymmetric system, the telerobot is usually equipped with a camera that streams the robot's vision back to the operator. When the interaction partner reaches out their hand, the operator will see this via the interface. The operator uses the control interface to reciprocate and have the robot reach out its hand. Movement is initiated with the push of a button in the most basic interface, or by moving a motion tracking device in a more advanced one. Once the interaction partner touches the robot, the handshake is picked up via a pressure sensor on the robot's palm and is transmitted back to the control interface. The touch could manifest as a screen flicker or a sound effect on the operator's computer, or as a vibration in a motion tracking device. 

In a symmetric system, both of the participants interact only with the telerobot in front of them. The handshake is initiated when one participant reaches their hand toward the robot. The gesture is picked up by a body tracker and causes the opposing robot to mirror the behavior of its operator and reach out its hand to the interaction partner on the other side. The partner reciprocates and now both robots have their hands reached out. When touch sensors on the robots detect that both participants are now shaking their respective robot's hand, a squeezing actuation commences in both robots to generate the feeling of the handshake for both partners.

# 4.4 A CMC component in asymmetric systems

Whether participant is interacting with a telerobot, or with a control interface in a symmetric or asymmetric system, telepresence communication is always mediated by a computer (CMC: _Computer Mediated Communication_). Interactions can be therefore anonymous, visibility and identity can be manipulated and conversation content can be augmented. There is still, however, a qualitative difference between an experience of physically interacting with a robot and that of operating one via an interface. When interacting with a telerobot, the perception of it as an avatar could suspend the participant's disbelief and regard the avatar as a present social agent [@banksAvatarsAreSometimes2016]. In that moment, interaction with the avatar becomes directly embodied and the robot's function as a medium is nearly transparent. One may argue that a similar suspension could be achieved in an immersive virtual reality environment, but the depth and richness of sensory feedback when operating in a real environment is still measures beyond what can be provided by a virtual one [@borgmannInformationNearnessFarness2000].  

Taking this difference into account implies that some social psychology models that apply to CMC, would apply to one side of an asymmetric telepresence system, the side that is operating the robot via a control interface. The participants that are interacting with the robot (both sides in case of a symmetric system), are experiencing an interaction that resembles more of an FtF encounter than a mediated one. Insofar as the robot is perceived as an avatar rather than a medium, we hypothesize that the experience would drift further away from CMC and closer to FtF. Factors that may moderate this effect are discussed in following sections.

A number of CMC models that affect the outcome of contact and the reduction of prejudice in conversation have been identified by researchers[@waltherComputermediatedCommunicationReduction2015]. The _deindividuation_ model warns that anonymity may release a person from social regulation and norms, leading to a negative effect on the conversation. The SIDE theory [@spearsWhenAreNet2002] provides a contrasting view in which a depersonalized encounter increases group salience, as it motivates individuals to act under a group context while pronouncing enhanced norms and tropes. Models such as SIP and _hyperpersonal_ communication 
[@waltherComputermediatedCommunicationImpersonal1996] advocate that more intimate interpersonal relations may form in online contact because of the need for the participants to make up for the lack of non-verbal cues. Having a strong CMC component only on one end of an asymmetric system could create a mix of behaviors in which one side experiences stronger senses of _agency_ in _ownership_ in the conversation than the other [@gallagherPhilosophicalConceptionsSelf2000]. Ideally, this could evolve into a positive outcome in which an out-group member on the side of the operator enjoys the benefits of anonymity and distance, while the in-group member is fully engaged in physical contact, assimilating new meanings and dissolves existing bias. Realistically however, the asymmetric nature of the conversation alone can have implications on contact, as we hypothesize in the following section.

# 4.5 Equality in telepresence systems

One of Allport’s basic conditions for positive intergroup contact is having an equal status between group members, such as an equal position in a workplace context (Allport 1954, 274). While the general idea was verified in multiple studies [@pettigrewMetaanalyticTestIntergroup2006], the condition can be further differentiated to equality in status or in _situation_, i.e in contact only; a more realistic condition when group members carry persistent power differences and are in long-lasting and deep-rooted conflicts [@maozDoesContactWork2011].

It was shown that having symmetry and equality in communication, such as equal turn-taking and mutual respect, is beneficial for contact in groups that are in asymmetric conflict such as Israelis and Palestinians [@maozEvaluatingCommunicationGroups2005]. However, this does not mean that existing power relations should be ignored during contact. In fact, it was found that a communication model that “emphasizes the conflict and power relations between the sides”, although more risky, produces a higher equality within the contact [@maozDoesContactWork2011]. Furthermore, equality emerges when the interaction focuses on fulfilling the different needs of the group members. While an advantaged group member needs to feel morally acceptance, a disadvantaged group requires a feeling of empowerment [@shnabelNeedsbasedModelReconciliation2008]. A failure to address inequality in status during contact may even hinder ensuing motivation for social change [@saguyIronyHarmonyIntergroup2009]. 

Symmetric telepresence systems provide the hardware foundation for equal contact. As will be shown in the proceeding sections, it is up to the software and organizational implementation to make sure that the conversation is handled in an equal manner. An asymmetric system, however, tilts the balance toward one end, and may have implications for contact. 

Consider the situation in which a disadvantaged-group member is operating a telerobot anonymously from their home, while the advantaged-group member is interacting with it in a public space. The operator may feel free of social anxiety in their comfort zone, and empowered by the ability to see through the robot's camera and not be seen. This in turn may encourage bringing up more difficult topics related to conflict during the conversation. However, the asymmetry in the participant's visibility may also bring up anxiety and discomfort. In our initial test for intergroup telepresence contact, participants of both sides expressed discomfort regarding the unequal asymmetric setting. One member of a minority group noted that they felt as if they are a government official investigating their exposed partners [@peledSoftRoboticIncarnation2019, p.132].

Conversely, in an an asymmetric system inequality may surface due to a difference in freedom of movement and in appearance between the robotic avatar and the human interlocutor. While some have raised concerns of social robots restricting the freedom of humans [@whitby15YouWant2011;@hoornTheoryRobotCommunication2018a], the opposite is also possible, as humans are in many cases more free and resilient than their robotic counterparts. Moreover, in the case of oppressed group members that are experiencing day-to-day restrictions on movement, an asymmetric system may highlight the power relations and reduce the sense of equality in the conversation. To summarize, the easier to implement asymmetric telepresence system may create both negative and positive perturbances in contact, and therefore should be designed with great consideration. while a symmetric system provides the foundation for equal grounds, leaving it up to further design choices to maintain this balance.

# 4. The use of a 2D display and the dual-ecologies problem

The telepresence robot market is rapidly growing, and is predicted to accelerate even more in the upcoming years with increase needs for remote working and social services ^[https://www.marketwatch.com/press-release/telepresence-robots-market-size-2020-to-showing-impressive-growth-by-2024-industry-trends-share-size-top-key-players-analysis-and-forecast-research-2020-04-20]. Telerobot forms are continuously branching into new directions, but as of 2020 the dominant form remains to be that of a tablet device attached to a motoric vehicle [@kristofferssonReviewMobileRobotic2013] (See [@fig:double_robot]). The tablet typically displays the operators head, as in a Skype call. Examples from market leaders include _Double Robotics_ ^[https://www.doublerobotics.com/], _Mantaro_ ^[http://www.mantarobot.com/products/teleme-2/index.htm] and Revolve Robotics ^[https://telepresencerobots.com/robots/kubi]. Such telepresence robots are oriented for remote offices and public service environments such as hospitals or schools.    

![The _Double Robotics_ Double 3 telerobot](./double_robot.png){#fig:double_robot width=3   0%}

In a contact situation, it is likely that the telerobot operator would want to remain anonymous, or at least present themselves differently than their actual form. In this case, it is best if the exposure of the face would be optional, or that the operator could manipulate the image. However, there is a more fundamental, ontological issue with using a 2D display on a telepresence robot. The problem was described as the "dual ecologies" problem, and was investigated in a case-study by Choi and Kwak [@choiCanYouFeel2016]. In their study, a remote partner's presence in a tablet-based video call was found to be stronger when it is disembodied (tablet only) than when it was attached to wheeled robotic body. The authors explain this by referring to the different ecologies present on the same robot: One is a 2D projection of the operator's remote location and another is the physical presence of the robotic body in a shared space. They suggest that the receiver of communication experiences confusion, having to interact simultaneously with the immediate environment and with he depiction of the remote environment. 

The dual ecologies problem could be extended further, as our initial test shows that even utilitarian use of a display on the telerobot's body to perform a task, has disrupted the participants' view of the robot as a uniform avatar. Instead, participants reported reverting to the experience of using a phone-like device while they were interacting with the display, despite having to touch the robot to initiate actions in the virtual interface [@peledSoftRoboticIncarnation2019, p.127]. Back projection solutions such as those of _Furhat Robotics_ ^[https://furhatrobotics.com/] attempt to solve this incongruence by projecting 3d-mapped virtual information directly on the robot's surface. While this may moderate the negative effects of the display, it does address entirely the dual ecologies problem of having two different spaces combined into one.  

An interference with the experience interacting with the avatar may negate the positive benefits of physical interaction such as non verbal cues and direct engagement, and disrupt the flow of attitude forming toward the out-group member. Therefore, the use of a display should be planned carefully for intergroup contact. Alternatively, the robot's appearance could be designed with an emphasis on uniformity and consistency. Considerations for appearance are discussed in the following section.


# 5. Telerobot design for contact

## 5.1 An extended uncanny valley

The affect of a robot's design on a human's attitude toward it has been studied extensively in literature, predominantly in studies of Human-Robot Interaction (HRI) and social robotics [@hancockMetaAnalysisFactorsAffecting2011]. A pivotal discussion revolves around the question of _anthropomorphism_: the degree in which a robot's appearance and behavior resembles that of a human. Current literature paints a picture that is manifold [@finkAnthropomorphismHumanLikeness2012]; while anthropomorphic features may increase a human's empathy and acceptance of the robot, the effect is context-dependent, culture-dependent, and works only to some extent. In some cases, people have preferred pet-shaped over human-like robots, and in other cases a human shape generated a negative attitude toward the robot. One over-reaching theory on robot-human-likeness has been largely ratified in literature - Mori's theory of the _Uncanny valley_  [@moriUncannyValleyField2012]. The theory suggest that a human's affinity toward a robot grows as it displays more human-like features, but at some point falls into a valley of uncanniness when the robot is _too human_ yet noticeably _inhuman_. The affinity rises back up only when theoretically no difference between the robot and a human can be discerned.

The theories above assume that the robot in question is fully autonomous, with no human controller in the loop. The context of telepresence naturally adds another element of complexity to the matter at hand and research specific to this question is more scant. A review by Lee et al [@leeDesigningAppearanceTelepresence2015] set to find an optimal design for a telepresence robot, recommended a mid-point between human and nonhuman with a caricatured nature. While keeping the uncanny valley in mind, adding some human-like aspects is justified by common research of affinity to anthropomorphic features. The argument for using a nonhuman form was based on research by Groom et al [@groomAmMyRobot2009]. The authors showed that robot operators have a greater sense of _self extension_ on their avatar when it is nonhuman. They explain this finding by the fact that a humanoid robot assumes its own identity, making it harder for the operators to project themselves on the robot. However, the study by Groom et al did not measure the effect of the non-humanoid form on the conversation from the side of the interlocutor, the person interacting with the robot. Research by Kuwamura et al [@kuwamuraPersonalityDistortionCommunication2012] found that the interlocutors experience a distortion of their partner's personality when it is conveyed through a nonhuman. Compared to a humanoid telerobot, participants interacting with a stuffed-bear felt confused, and had difficulty imagining that they are talking to a human.

Taking us back to the context of intergroup contact, the findings above have great significance. First, the uncanny, as it was originally described by Freud [@freudUncanny1919], invokes emotions as _morbid anxiety_; anxiety being a known mediator for the outcome of contact [@pettigrewMetaanalyticTestIntergroup2006, p.767]. 
Furthermore, the findings in regards to self extension and personality distortion also hold a potential to mediate the result. Nevertheless, as discussed previously, it is not a given that an attitude formed toward the telerobot would naturally project onto the operator. We therefore suggest to extend the model of the uncanny to support telepresence by adding another dimension to the equation. As noted, the level of Avatar WSOD moderates the transference of affect from the avatar to the inhabiter. Adding another multiplier to the uncanny valley equation would then reflect the estimated positive effect of avatar WSOD (see @fig:extended_uncanny). Assuming a high avatar WSDO also implies that the problems of personality distortion presented by Kuwamara et al are mitigated. It should be noted, however, that even with WSOD in place, not all nonhuman forms may fit the context of intergroup contact, especially in the context of conflict. Some caricatured forms may undermine the statue of the participant or even invoke a sense of disrespect. To summarize, we conclude that a midpoint between human and non-human may be suited for intergroup contact, but only if avatar WSOD is maintained, for example through outside cues, avoiding dual ecologies, etc, and if the form does not demean the participants. Another moderating variable that is interrelated in the design process is group salience.


![From left to right: Telenoid, Elfoid, Hugvie by Ishiguro labs. Retreived from http://www.geminoid.jp/en/robots.html](telenoid.png){#fig:telenoid width=50%}

![Geminoid and Professor Hisroshi Ishiguro. Retreived from http://www.geminoid.jp/projects/kibans/resources.html](geminoid.jpg){#fig:geminoid width=50%}


## 5.2 Designing with group salience in mind

Naturally, the process toward forming a generalized opinion toward the out-group does not end at the interpersonal level. The most widely agreed-upon moderator for generalizing a positive attitude to the intergroup level is _group salience_, the degree in which the participants' group identity is salient during contact.  Earlier research on contact found a bipolar, antagonistic correlation between group identity salience and interpersonal relationship [@brownInterpersonalIntergroupBehaviour1981]: When the group identity is so present, it is harder for the participants to find their commonalities and create new bonds and friendships. Later research, however, suggests that there is now a sufficient evidence that group and interpersonal salience can remain high simultaneously [@brownIntegrativeTheoryIntergroup2005]. One approach,suggested by Pettigrew [@pettigrewIntergroupContactTheory1998], is to expose group identities gradually, starting with a low salience, allowing initial contact to form, and increasing it over time.

Group identity can be transmitted through a variety of channels in telepresence, beginning with the design of the avatar itself and its surroundings, and proceeding into the content of the interaction. Although the physical medium is not as easily manipulated as a virtual environment [@haslerOnlineIntergroupContact2013], there is still room for creativity in the way group identity is revealed during contact. For example, an avatar may have a non-humanoid appearance, but still maintain group identity through group symbols, cues, language, and so forth. It may speak in an accent, wear typical accessories or flaunt national colors. The freedom to use material objects brings up new design possibilities that are not available in an online encounter. Group cues could be positioned in subtle ways, so that they are gradually revealed by the interlocutor. If the initial appearance and behavior of the robot is engaging enough, an interpersonal bond may be formed despite the presence of group-related cues.

```{#fig:extended_uncanny .pyplot caption="Extended uncanny valley model for intergroup contact" links=false}
import numpy as np
from matplotlib import pyplot as plt
from mpl_toolkits.mplot3d import Axes3D

x = np.arange(0., 7., 0.1)
y = np.arange(0., 7., 0.1)

X, Y = np.meshgrid(x, y)

def uncanny_function(t):
    return 1/(1 + np.exp(-(t-4)) ) - 1.2 * np.exp(-(t-6) ** 2)

def avatar_function(t):
    return t / 8.

plt.figure()

Z = uncanny_function(X) * avatar_function(Y)

ax = plt.axes(projection="3d")

ax.plot_wireframe(X, Y, Z)
ax.set_xlabel('Human Likeness')
ax.set_ylabel('Avatar WSOD')
ax.set_zlabel('Attitude toward out-group member')


ax.xaxis.set_tick_params(labelsize=0)
ax.zaxis.set_tick_params(labelsize=0)
ax.yaxis.set_tick_params(labelsize=0)

```

## 5.3 Materiality and movement

An important factor in robot design is the choice of materials. In industrial robots, the material would be chosen _functionally_, in accordance with the task at hand. In robots designated for human interaction, instead of materials, we examine _materiality_, conceptualized by N. Katherine Hayle as "physical qualities that present themselves to us"[@haylesSpeculativeAestheticsObjectoriented2014]. Materiality comes into play in two main aspects of a robot's constitution: 1) The outer skin: the part of the robot that touches and is being touched, and 2) Actuation: the material that actuates, generating the robot's movements. With the former, we can place materials on a scale of firmness and rigidness; how soft it feels to touch the material. With the latter, we can define a scale of flexibility and linearity, describing the nature of the material's movement.

Previous research in social robotics supports the use of soft materials for the outer skin of robots, especially in interaction with children [@kozimaSocialRobotsChildren2006] and in elderly care [@broekensAssistiveSocialRobots2009;@kiddSociableRobotEncourage2006]. The reason being the presence of _affective touch_ between the robot and humans [@kerruishAffectiveTouchSocial;@stiehlDesignTherapeuticRobotic2005]. The human body and another natural forms are inherently soft, and co-exist better with other materials that are soft [@daneseSoftMachine2003]. Nevertheless, here too, carrying an object closer to the realm of the living may invoke an uncanny feeling, for example when touching a smooth, soft, material that is also cold [@willemseAffectiveBehavioralResponses2017;@nieCanYouHold2012].

A soft touch on the surface doesn't necessarily imply a softness as a whole. For example, a gripping robotic hand made from powerful servo motors that are wrapped in a soft skin could still easily, and inadvertently, crush soft tissue. _Soft Robotics_ is a rapidly developing research field for robots that operate on soft materials down the level of actuation [@baoSoftRoboticsAcademic2018]. Research is often, but not always, bio-inspired; commonly used materials are fabrics and silicone rubbers while the most common form of actuation is pneumatic: applying air pressure or vacuum. Presently, the largest consumers of soft robotics are the medical industry, utilizing the soft materials for invasive and surgical procedures. Nevertheless, uses and appeal of soft robots for human interaction are being studied [@bewleyDesigningBlonutDesign2018;@jorgensenAppealPerceivedNaturalness2018;@zhengSoftGrippersNot], uniformly arriving to the conclusion that the smooth, organic-like motion of soft actuators has an expressive quality, and affects humans in a manner highly different from traditional robotics. Our small-scale test on soft robotic telepresence has reached similar conclusions [@peledSoftRoboticIncarnation2019, p.126]. As predicted by Mori, movement has an effect on the uncanny, and soft actuation has potential to fall into the a negative category. If designed correctly, movmement can bestow a robot with a relatable, expressive quality, despite it having a  non-anthropomorphic appearance [@hoffmanDesigningRobotsMovement2014].  

All things considered, a soft approach deems appropriate for telepresence contact. Insofar as the presentation of the avatar remains balanced in respet to the principles outlined in this section, adding soft movement and touch may increase empathy and initmacy in contact and lead to a more positive outcome. A soft approach also presents a notion of safety, and an inability to cause harm; a desirable climate in situations of intergroup conflict.


Robot’s Height

Using non-human embodied imagery for the the operator affects group identity and anxiety [@kimTwoRoutesLeading2011]

# 6. Physical interaction modalities

As described in the beginning of this article, the term _physical interaction_ delineates the missing element in a signal-based, online interaction. Physical interactions occurs in a real environment where matter creates an energy bond with matter. This includes _embodied interactions_ : subject-to-object interactions between a human body and an object such as a robot, and object-to-object interactions, e.g when the robot is interacting with other objects in the environment. In telepresence contact, we want to create a real sense of intersubjectivity between human and avatar, as close as possible to situated FtF encounter. Phenomelogist Merlau-Ponty coined the term _intercorporeality_ to describe the strong and co-dependent physical nature of intersubjectivity [@merleau-pontyVisibleInvisibleFollowed1968]. Today, researchers in the field of emobided cognition are studying the specific mechanisms behind this phenomenon. 

In this section we explore possible affordances [@gibsonSensesConsideredPerceptual1966, p.285] in telerobot design, and theorize over different modalities [@kressMultimodalitySocialSemiotic2009]: modes for interaction, that may assist in intergroup contat. We detail suggestions toward implementation in the two types of systems discussed: symmetric and asymmetric. For every implementation, we consider the level of agency alloted to the operator, and conversely the level of autonomy required from the robot. While we strive to grant full agency to the operator, some modalities require an intervention from the robot to ensure a smooth exprience, while other modalities may benefit from being augmented with the robot's capabilities.

A robot can theoretically do anything that a human can do, and more, but 


## 4.2 Using the operator's voice VS an artificial voice

Using the operator's voice might have similar effects on individuation as using the face, but adding an artificial voice also provides the ability to speak in many languages The operator's voice can even be cloned. However, mistakes in translation my increase anxiety in both sides.

## 6.1 Non-verbal cues in tele-operation

A robot can show non verbal cues such as: body
attitude, gaze, head nods, and facial expression (as the model allows it). They could smoothen the turn taking in the conversation and increase empathy.

However, such tacit queues are not actively initiated by the operator and would require a certain autonomous algorithm to generate them. This depends on the interface being used and is liable for glitches, abstractions and loss of information.

In asymmetrical form that involves a camera, gaze can be operated by controlling the camera and changing where the robot looks.

## 6.2 Bodily expressions

An operator could have the robot show bodily expressions. Depending on the operating interface, these could be actively initiated or captured by a gesture sensor. The active method is less prone to mistakes which could reduce anxiety.

Active bodily expressions could be triggered for example by a simple click on an emoji, or using more sophisticated forms such as body tracking, or using the phone's accelerometer.

## 6.3 Interaction with the robot

A robot could have sensors that pick up the interaction of the partner 
with the robot and sends it back to the operator. In the symmetric form this is the only type of interaction possible, but in asymmetric form it is possible to use a camera to capture interaction.

# 6.4 Feedback in operation

When operating a robot it is helpful to get feedback on actions chosen. It increases the smoothness of operation and reduces anxiety of appearing wrong.

In asymmetric form the operation can have visual feedback. It is possible to use mirrors, or a camera set in space (or on another robot if they are in group). Can use haptic feedback if possible.

In symmetric form there is no feedback, but there is also no real sensation of operating a robot as it is completely transparent.


# 8. Interaction scenarios

## 8.1 Public space intervention

The operator can 'intervene' in a public space and confront passersby. In the asymmetric form would require an interface to 'call' a stranger, such as playing a sound or performing a gesture. In the symmetric form it would be a station that can be occupied by a participant, and when to participants are sitting they would start interaction.

Without interrupting the perception of avatar, the robot or the interface design could contain cues that encourage talk about the conflict and promote self-disclosure. It is also possible to place instructions for a cooperative action near the site of the robot, which would require participants to 'play' some scenario together, in which conflict-related content could be inserted.

The use of a display for showing relevant content is also possible, but could evoke disbelief in the avatar

## 8.3 Private/structured communication

In an organized contact, that is suitable both for the symmetric and asymmetric forms, the moderators can direct the conversation.


# 9. Real-world conflict considerations

## 9.1 Empowerment via education in robotics
Art therapy, theater of the oppressed.

## 9.2 Legal and ethical considerations
Border crossing, normalization, social pressure.

## 9.3 Israel-Palestine test case

# References