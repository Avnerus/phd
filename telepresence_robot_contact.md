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

Inspired by those findings, we suggest a conceptual model for telepresence conact. Due to the presence of the telerobot, we add another stage on the path to prejudice reduction [@fig:path_model]. We hypothesize that an in-group member first develops an attitude toward the robot itself before projecting it on operator, the out-group member. Attitude toward the robot could be influenced by previous bias on robots or by characteristics of the particular robot which we will address in this article. We estimate that the projection of the robot on the operator will be moderated by the degree of how much the robot is perceived as an avatar of the operator, or as a simple medium of communication. Finally, a generalized attitude toward the out-group will be moderated by the level of group salience apparent in the conversation with the telepresence robot.

![Telepresence Contact: Conceptual path model](./path_model.jpg){#fig:path_model} 


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

2. _Symmetric bidirectional_: In this system both participants are operating a telerobot, which serves both as an avatar for their conversation partner as well a control interface for their telerobot. The interface, in that case, is completely transparent to the operator and typically uses body tracking. No control feedback is available to the operator and operation may commence without any knowledge of the remote telerobot by the participants. This type of system is more resource-heavy than the asymmetric type, and currently only a few implementations exist as prototypes and proofs-of-concept [@nagendranSymmetricTelepresenceUsing2015].

3. _Symmetric unidirectional_: In this system both participants are operating a telerobot via a control interface, without physically interacting with an avatar. The two robots share the same space, while the participants are separated. Common implementations of this system include cooperative multi-robot tasks [@sirouspourMultioperatorMultirobotTeleoperation2005] and _Robot combat_ competitions [@clarksonBattleBotsOfficialGuide2002].As in the asymmetric system, operation is usually performed from a computer or mobile device. 

![Systems of telepresence communication](sym_asym_v4.jpg){#fig:sym_asym}


While the _symmetric unidirectional_ system may facilitate contact in cooperative or confrontational events in front of an audience, since the scope of this article involves at least one person physically interacting with a robot, we would turn the focus toward the first two systems.

## 4.3 The handshake paradigm

To further illustrate the mechanics of the two systems, we will use the common example of the handshake. The handshake is an important and common social gesture in most parts of the world [@schiffrinHandworkCeremonyCase1974]. It is a reciprocal action, beginning with one person reaching out in an open request and then reciprocated by the partner. It is also a haptic gesture in which subtle forms of touch can have a great social significance [@hillewaertTacticsTactilitySensory2016].

In an asymmetric system, the telerobot is usually equipped with a camera that streams the robot's vision back to the operator. When the interaction partner reaches out their hand, the operator will see this via the interface. The operator uses the control interface to reciprocate and have the robot reach out its hand. Movement is initiated with the push of a button in the most basic interface, or by moving a motion tracking device in a more advanced one. Once the interaction partner touches the robot, the handshake is picked up via a pressure sensor on the robot's palm and is transmitted back to the control interface. The touch could manifest as a screen flicker or a sound effect on the operator's computer, or as a vibration in a motion tracking device. 

In a symmetric system, both of the participants interact only with the telerobot in front of them. The handshake is initiated when one participant reaches their hand toward the robot. The gesture is picked up by a body tracker and causes the opposing robot to mirror the behavior of its operator and reach out its hand to the interaction partner on the other side. The partner reciprocates and now both robots have their hands reached out. When touch sensors on the robots detect that both participants are now shaking their respective robot's hand, a squeezing actuation commences in both robots to generate the feeling of the handshake for both partners.

# 4.4 A CMC component in asymmetric systems

Whether participant is interacting with a telerobot, or with a control interface in a symmetric or asymmetric system, telepresence communication is always mediated by a computer (CMC: _Computer Mediated Communication_). Interactions can be therefore anonymous, visibility and identity can be manipulated and conversation content can be augmented. There is still, however, a qualitative difference between an experience of physically interacting with a robot and that of operating one via an interface. When interacting with a telerobot, the perception of it as an avatar could suspend the participant's disbelief and regard the avatar as a present social agent [@banksAvatarsAreSometimes2016]. In that moment, interaction with the avatar becomes directly embodied and the robot's function as a medium is nearly transparent. One may argue that a similar suspension could be achieved in an immersive virtual reality environment, but the depth and richness of sensory feedback when operating in a real environment is still measures beyond what can be provided by a virtual one [@borgmannInformationNearnessFarness2000].  

Taking this difference into account implies that some social psychology models that apply to CMC, would apply to one side of an asymmetric telepresence system, the side that is operating the robot via a control interface. The participants that are interacting with the robot (both sides in case of a symmetric system), are experiencing an interaction that resembles more of an FtF encounter than a mediated one. Insomuch as the robot is perceived as an avatar rather than a medium, we hypothesize that the experience would drift further away from CMC and closer to FtF. Factors that may moderate this effect are discussed in following sections.

A number of CMC models that affect the outcome of contact and the reduction of prejudice in conversation have been identified by researchers[@waltherComputermediatedCommunicationReduction2015]. The _deindividuation_ model warns that anonymity may release a person from social regulation and norms, leading to a negative effect on the conversation. The SIDE theory [@spearsWhenAreNet2002] provides a contrasting view in which a depersonalized encounter increases group salience, as it motivates individuals to act under a group context while pronouncing enhanced norms and tropes. Models such as SIP and _hyperpersonal_ communication 
[@waltherComputermediatedCommunicationImpersonal1996] advocate that more intimate interpersonal relations may form in online contact because of the need for the participants to make up for the lack of non-verbal cues. Having a strong CMC component only on one end of an asymmetric system could create a mix of behaviors in which one side experiences stronger senses of _agency_ in _ownership_ in the conversation than the other [@gallagherPhilosophicalConceptionsSelf2000]. Ideally, this could evolve into a positive outcome in which an out-group member on the side of the operator enjoys the benefits of anonymity and distance, while the in-group member is fully engaged in physical contact, assimilating new meanings and dissolves existing bias. Realistically however, the asymmetric nature of the conversation alone can have implications on contact, as we hypothesize in the following section.

# 4.5 Equality in telepresence systems

One of Allport’s basic conditions for positive intergroup contact is having an equal status between group members, such as an equal position in a workplace context (Allport 1954, 274). While the general idea was verified in multiple studies [@pettigrewMetaanalyticTestIntergroup2006], the condition can be further differentiated to equality in status or in _situation_, i.e in contact only; a more realistic condition when group members carry persistent power differences and are in long-lasting and deep-rooted conflicts [@maozDoesContactWork2011].

It was shown that having symmetry and equality in communication, such as equal turn-taking and mutual respect, is beneficial for contact in groups that are in asymmetric conflict such as Israelis and Palestinians [@maozEvaluatingCommunicationGroups2005]. However, this does not mean that existing power relations should be ignored during contact. In fact, it was found that a communication model that “emphasizes the conflict and power relations between the sides”, although more risky, produces a higher equality within the contact [@maozDoesContactWork2011]. Furthermore, equality emerges when the interaction focuses on fulfilling the different needs of the group members. While an advantaged group member needs to feel morally acceptance, a disadvantaged group requires a feeling of empowerment [@shnabelNeedsbasedModelReconciliation2008]. A failure to address inequality in status during contact may even hinder ensuing motivation for social change [@saguyIronyHarmonyIntergroup2009]. 

Symmetric telepresence systems provide the hardware foundation for equal contact. As will be shown in the proceeding sections, it is up to the software and organizational implementation to make sure that the conversation is handled in an equal manner. An asymmetric system, however, tilts the balance toward one end, and may have implications for contact. 

Consider the situation in which a disadvantaged-group member is operating a telerobot anonymously from their home, while the advantaged-group member is interacting with it in a public space. The operator may feel free of social anxiety in their comfort zone, and empowered by the ability to see through the robot's camera and not be seen. This in turn may encourage bringing up more difficult topics related to conflict during the conversation. Alternatively, the asymmetry in the participant's visibility may also bring up anxiety and discomfort. In our initial test for intergroup telepresence contact, participants of both sides expressed discomfort regarding the unequal asymmetric setting. One member of a minority group noted that they felt as if they are a government official investigating their exposed partners.

Conversely, in an an asymmetric system inequality may surface due to a difference in freedom of movement and in appearance between the robotic avatar and the human interlocutor. While some have raised concerns of social robots restricting the freedom of humans [@whitby15YouWant2011;@hoornTheoryRobotCommunication2018a], the opposite is also possible, as humans are in many cases more free and resilient than their robotic counterparts. Moreover, in the case of oppressed group members that are experiencing day-to-day restrictions on movement, an asymmetric system may highlight the power relations and reduce the sense of equality in the conversation. To summarize, the easier to implement asymmetric telepresence system may create both negative and positive perturbances in contact, and therefore should be designed with great consideration.

# 4. Operator visibility

A key question in telepresence systems concerns the visibility level of the operator; how much of the operator's real-time body, actions and intentions are exposed through the avatar? This concerns not only visual sensibilities, but also auditory: exposing the operator's voice. We examine the implications of visibility on intergroup contact in detail in this section.

## 4.1 Face visibility

The telepresence robot market is rapidly growing, and is predicted to accelerate even more in the upcoming years with increase needs for remote working and social services. Telerobot forms are continuously branching into new directions, but as of 2020 the dominant form remains to be that of a tablet device attached to a motoric vehicle such as robots by market leaders _Double Robotics_ ^[https://www.doublerobotics.com/].     

The 'ipad on segway' form is now the most common form of telepresence. It's not really an avatar incarnated. There is no suspension of disbelief that the robot _is_ the operator.

![Telepresence ipad](telepresence_ipad.jpg){#fig:telepresnce_ipad}

From the operator's side, exposing of the face could increase anxiety and reduce hyperpersonal behavior, but may increase accountability.

From the partner side, seeing the operator's face could create a more personal connection with the operator, but because it challenges the belief of the robot being an avatar, the partner perceives the robot as a communication device. This reduces the efficacy of embodied interaction. In fact, using any type of display can subvert the perception of the avatar [Can I reference the qualitative research of my own MA?]
    

## 4.2 Using the operator's voice VS an artificial voice

Using the operator's voice might have similar effects on individuation as using the face, but adding an artificial voice also provides the ability to speak in many languages The operator's voice can even be cloned. However, mistakes in translation my increase anxiety in both sides.

# 5. Appearance of the telepresence robot

## 5.1 Humanoid vs non-humanoid

Using a humanoid telerobot could increase the connection between the participant and the telerobot and could help in increasing group salience.

It could however evoke the uncanny effect.

Using non-human embodied imagery for the the operator affects group identity and anxiety [@kimTwoRoutesLeading2011]

A non-humanoid would have to work harder for emotional expression and empathy, if there are no human facial expressions, but using animalistic expressive movement or semi-anthropomorphic gestures is possible 

## 5.2 A combined approach: Group markers on a non-humanoid form

We are not limited to forms that exist in real life. It is possible to include various identifying markers on the non-humanoid avatar to increase group salience during contact. Markers such as:

 - Group symbols
 - Typical name/nickname
 - Native language
 - Other conversation content



# 6. Embodied interaction

## 6.1 Non-verbal cues in tele-operation

A robot can show non verbal cues such as: body
attitude, gaze, head nods, and facial expression (as the model allows it). They could smoothen the turn taking in the conversation and increase empathy.

However, such tacit queues are not actively initiated by the operator and would require a certain autonomous algorithm to generate them. This depends on the interface being used and is liable for glitches, abstractions and loss of information.

In asymmetrical form that involves a camera, gaze can be operated by controlling the camera and changing where the robot looks.

## 6.2 Bodily expressions

An operator could have the robot show bodily expressions. Depending on the operating interface, these could be actively initiated or captured by a gesture sensor. The active method is less prone to mistakes which could reduce anxiety.

Active bodily expressions could be triggered for example by a simple click on an emoji, or using more sophisticated forms such as body tracking, or using the phone's accelerometer.

## 6.3 Interaction with the robot

A robot could have sensors that pick up the interaction of the partner with the robot and sends it back to the operator. In the symmetric form this is the only type of interaction possible, but in asymmetric form it is possible to use a camera to capture interaction.

# 6.4 Feedback in operation

When operating a robot it is helpful to get feedback on actions chosen. It increases the smoothness of operation and reduces anxiety of appearing wrong.

In asymmetric form the operation can have visual feedback. It is possible to use mirrors, or a camera set in space (or on another robot if they are in group). Can use haptic feedback if possible.

In symmetric form there is no feedback, but there is also no real sensation of operating a robot as it is completely transparent.


# 7. Materiality and movement
Have great effect on expression, anxiety, empathy. We suggest the use of soft robotics for telepresence.

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