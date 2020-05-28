---
title: Intergroup Contact via Robot Telepresence | Research Plan
subtitle: Grant application for the Wihuri Foundation
author: Avner Peled
date: 05/2020
documentclass: article
indent: true
csl: apa2.csl
bibliography: [aalto.bib]   
header-includes: |
    \usepackage{xeCJK}
    \usepackage{xelatexemoji}
    \usepackage{float}
    \usepackage{fvextra}
    \DefineVerbatimEnvironment{Highlighting}{Verbatim}{breaklines,breaksymbolleft={\quad},commandchars=\\\{\}}
    \makeatletter
    \def\fps@figure{H}
    \makeatother
...
---

\maketitle
\newpage
\tableofcontents
\pagebreak
    
# Statement
I am a first-year doctoral student at Aalto University’s school in Arts, Design and Architecture; in the department of media. My Master’s thesis: Soft Robotic Incarnation [@peledSoftRoboticIncarnation2019], was done at the same department. There is a dire need for creative and technological solutions in my home country, Israel, and its conflict with the Palestinian people. In the past decade I have been focusing my efforts and navigating prior experience in science and technology  for this purpose. I am hoping that through my doctoral studies I will be able to promote positive social change not only in Israel, but also in other locations suffering from similar issues of prejudice and alienation.

This research deals with intergroup contact; the simple, and yet, elusive idea that in order for two social groups to reduce the prejudice and animosity between them, they have to find a way to meet. Since initiating large-scale face-to-face contact between groups in protracted and violent conflicts is incredibly challenging, conflict resolution efforts have expanded into various forms of indirect contact: second-degree contact through a mutual acquaintance, simulated contact through guided imagination, and different forms of contact mediated by technology. Within the scope of technological mediation, virtual forms of encounter such as online gaming and VR have taken the center stage, whereas little attention has been given to robots. This, despite apparent shortcomings caused by the inherent virtuality and personality abstraction of virtual contact. The following sections outline the research plan for hypothesizing and testing the viability of contact mediated by telepresence robots, acting as corporeal avatars of human individuals, and fabricated in participatory workshops. The research will contribute  three main innovations to the academic community: 1) The first contact hypothesis for telepresence robots; theorizing on the required conditions for a positive outcome , 2) A novel design for a robotic avatar toolkit that is tailored specifically for telepresence contact and is designed to be fabricated by an inexperienced user, and 3) The first ever field test for telepresence robot contact between Israelis and Palestinians.

With lessons learned from the production of my previous soft robotic telepresence: HITODAMA, I will produce a new toolkit that allows inexperienced workshop participants to design and produce their avatar. The robots would be deployed in a public space and operators would manage interactions with passersby through their mobile devices or desktops over the Internet. At the core test case, participants from Palestine would construct their avatars in a workshop and have them pop-up in public spaces in Israel. The Palestinians will be able to converse with Israelis beyond the separation wall without exposing their identity.  By opening the robot’s production to a participatory workshop in an intergroup conflict context, I hope to achieve two main outcomes: 1) Proliferation of technical and scientific knowledge and empowerment in an oppressed group. 2) Personal artistic and emotional expression of the oppressed. The research is divided into milestones in which design decisions and hypotheses would be put to the test and publications would follow.

# Grant request
For the first year of my research, between 02/2020 and 02/2021 I was able to get hired as a paid researcher by Aalto university. However, starting March 2021 I will be without funding. I therefore apply for a 1-year grant between 03/2021 and 03/2022. 

# Research overview

## The Telepresence Contact Hypothesis: Dissolving prejudice with robots

This dissertation focuses on prejudice as a major component of intergroup conflict [@pettigrewIntergroupPrejudiceIts2011], and the dissolution of prejudice as a key for conflict resolution. Gordon Allport’s Nature of Prejudice (1954) lays the foundation for the Contact Hypothesis: A theory suggesting that an interpersonal contact between groups can reduce prejudice. Allport suggests four conditions for an organized encounter that need to be fulfilled for the contact to be effective: equal status, common goals, cooperation, and institutional support. Fifty years later, a meta-analysis conducted by Pettigrew and Tropp was able to validate the hypothesis across a large number of studies (2006). It was  shown, however, that Allport’s conditions are not strictly essential for a positive outcome, rather they are factors among others that facilitate it. Later research focuses on identifying the affective drivers that play a role in contact such as empathy and anxiety , and on conditions that support the generalization of attitudes from the interpersonal level to the group level [@brownIntegrativeTheoryIntergroup2005].

Communication technology expands the models of contact and adds new modalities of interaction while giving up the benefits of traditional face-to-face encounters. Research on online intergroup contact has shown that despite the obstacles set by the medium, there is potential for online intergroup contact to reduce prejudice and aid in conflict resolution [@amichai-hamburgerStructuredUnstructuredIntergroup2015;@haslerOnlineIntergroupContact2013;@waltherComputermediatedCommunicationReduction2015]. Virtual reality has also been studied as medium, both in dialog as well as in acting as an “empathy machine” that allows intergroup members to immerse themselves in the perspective of the other side [@haslerVirtualPeacemakersMimicry2014;@hassonEnemyGazeImmersive2019;@kabiljoVirtualRealityFostering2019]. Nevertheless, online contact can go wrong. The distant nature of the remote medium reduces our sense of _presence_ in the social situation [@goffmanBehaviorPublicPlaces2008;@nowakDefiningDifferentiatingCopresence], which in turn makes us less accountable for our actions and less engaged in the conversation [@whiteImprovingIntergroupRelations2015;@schumannWhenComputermediatedIntergroup2017]. The lack of subtle non-verbal cues [@burgoonNonverbalSignals1994] also impairs the turn-taking process and may evoke negative feelings such as anger and frustration [@johnsonAngerFlamingComputermediated2009].

The crucial role of the corporeal and the physical in forming sociality has long been advocated by researches and philosophers across disciplines and fields. From the historical materialism of Marx [@marxProcessCapitalistProduction] and Lukacs [@lukacsReificationConsciousnessProletariat2017], through the phenomenology of the intercorporeal [@merleau-pontyVisibleInvisibleFollowed1968] and pedagogical theories of "learning by doing" [@deweyDemocracyEducationIntroduction1923], and up to the four Es of embodied cognition [@gallagherBodyImageBody1995]. Critical theorists have repeatedly warned against an abstraction of the human nature. Terms such as _reification_, _rationalization_, and _fetishism_ are used to describe the condition in which virtual properties are incorrectly assigned to a material being[@silvaReificationFetishismProcesses2013;@horkheimerEclipseReason2004;@juttenColonizationThesisHabermas2011;@ahmedStrangeEncountersEmbodied2000]. Telepresence robots add corporeal depth to mediated contact, as they represent a midway between online communication and face-to-face contact. On one hand the operator is inhabiting their robotic avatar remotely, but on the other hand the interaction partner is physically present with the robot, and using their body as they would when meeting face-to-face. It remains to be asked, how should such interaction be designed to achieve an optimal result? From the design of the robot, to interaction modalities, and scenario planning, we attempt to answer this question in a conceptual paper - the telepresence robot contact hypothesis.


## A toolkit for making soft robotic avatars

Research conducted on my Master's thesis provided initial conclusions on the use of telepresence robots for intergroup contact [@peledSoftRoboticIncarnation2019]. A non-humanoid form made of soft materials was explored and found promising for a neutral yet expressive and organic-looking avatar. A qualitative analysis of user response to numerous design and interaction elements also provided important guidelines for future research.

The potential for custom-designed social robots was demonstrated by Suguitan and Hoffman [-@suguitanBlossomHandcraftedOpenSource2019], and I wish to take this further into designing actuation and behavior. 

Additionally, allowing the out-group members to design their own avatar could utilize principles of expressive art therapy. The participants would get a chance to freely mold their self-image into a non-human avatar, which may have therapeutic benefits (Muri, 2007; Sholt & Gavron, 2006). Applying self-expression techniques with Palestinians in intergroup conflict could also benefit from Boal’s theory of the Theatre of the Oppressed (Boal, 2008). The controllers would be able to design their expressions into the robot, whether it is an offensive hand gesture or an offer for peace. Combining technological and expressive arts techniques with pedagogy and empowerment of the oppressed provides a transdisciplinary approach to conflict resolution in asymmetrical intergroup conflicts.

In this dissertation, I will create a modular, easy to use toolkit for the preparation of remote-controlled soft robotic avatars. The toolkit would allow participants to design their movements using flexible methods such as origami-inspired structures [@peraza-hernandezOrigamiinspiredActiveStructures2014]. The modules would then be connected to a central pneumatic system and communication controller that automatically provides conversation and actuation capabilities, including language translation and remote control via the mobile web (see [@fig:diagram]).

![Modular Soft robotic control: Architecture diagram](./diagram.jpg){#fig:diagram}


To illustrate the process, a use-case scenario is presented as follows:

1. Participant A from Palestine decides they want to appear as a talking bird, colored according to the flag of Palestine.
2. Participant A creates the body and face of the bird from soft materials such as fabrics and soft plastics and wraps the body around the controller unit.
3. Participant A creates two bending origami actuators ^[https://www.youtube.com/watch?v=3PQT3vRf-qA] as the wings of the bird, covers them with feathers, and attaches their air vent to the main controller unit.
4. The robot bird is placed in a public park in Israel, and participant A connects to the control interface with his mobile phone.
5. Participant A notices through the robot's camera an Israeli couple passing by, and triggers a recording of a bird call that they prepared in advance on the interface.
6. The couple notices the bird and approaches the robot.
7. Participant A types in Arabic "Hello there, would you listen to my story?" and instructs the robot to speak in Hebrew.
8. The couple answers "Yes" in Hebrew and the robot records and translates their response to Arabic before it is shown on Participant A's interface.
9. Participant A flaps the bird's wings using the web interface, the couple approaches and touches the wings.
10. Participant A starts telling their story.

The majority of the technology for the central communication controller was already developed during the Master's thesis. Upcoming technical research will focus on new soft actuator designs that favor simplicity and flexibility over strength and precision. The actuators need to be easily produced in a workshop scenario with inexperienced participants and inexpensive materials. Insofar as the avatar is designed for expressiveness and social communication rather than explicit functional tasks, organic mistakes and deformations are a welcomed addition and not a mark of failure. I draw inspiration from the maker culture and the _Hebocon_ robot competition ^[https://spectrum.ieee.org/automaton/robotics/diy/hebocon-the-best-worst-robot-competition], as well from on my own experience in delivering workshops ^[https://vimeo.com/210919628]. Additional research will be dedicated to developing remote control methods that take better advantage of the soft medium and allow for more fluid control. One example could be the use of the phone's accelerometer or finger-sliding, to control the pneumatic system in real-time, producing a fluid motion.

# Advisors 

I have confirmed the availability of three advisors for my studies: 

1. **Prof. Teemu Leinonen:** Head of the Learning Environments research group and supervisor of my studies.

2. **Dr. Mia Muurimäki:** A former Aalto Media Lab faculty and now a service designer team leader in Futurice. Mia has helped me during my Master's thesis in a multitude of ways. She directed me to relevant literature, suggested design changes and advised me on project management and schedules. Mia has been conducting participatory and co-design workshops in Futurice and I am sure she will also be able to advise me in that field.

3. **Dr. Béatrice Hasler:** Founder of VR-CORE: Virtual Reality Lab for Conflict Research in IDC Herzliya research school in Israel. Béatrice has years of experience researching virtual intergroup contact in the Israeli-Palestinian conflict and has studied online collaboration. Beatrice graciously offered to advise and participate in this research and has introduced me to missing links in social psychology that are essential for this dissertation.

# Time-line

I propose to divide my studies into four milestones in four years. Three milestones will produce a publication, and the final product is the dissertation, aggregating and concluding the research. The milestones suggested are as follows:

1. **Soft Robotic Telepresence for intergroup contact**: A literature review of social-psychology, phenomenology and critical theory evaluating the potential of soft robotic telepresence for fulfilling the contact hypothesis. The study would include a comparison to other forms of intergroup contact, and if possible a prototype and test for a simple soft robot that could test the hypothesis. _Due to the COVID-19 pandemic^[https://www.who.int/emergencies/diseases/novel-coronavirus-2019], practical tests might not be possible_

2. **A modular, DIY soft robotic avatar**: I will present a pedagogical and therapeutic toolkit for creating your soft robotic avatar and evaluate it with a test group study. The expressive and therapeutic advantage of the DIY robot would be tested against a pre-made robot in an intergroup contact scenario.

3. **Intergroup conflict resolution with modular soft robotic avatars**: Based on results from the previous studies, the toolkit would be put to the test in a real-world scenario in Israel-Palestine. I will be conducting workshops in Palestine and place the robots in Israel. The potential for reducing prejudice would be evaluated.

4. **Dissertation**: The final dissertation would aggregate the three papers and invoke an encompassing discussion on the conclusions, suggesting alternatives and devising plans to move forward.

Additionally, during the studies, I will take 60 ECTS of courses. The following graph outlines the planned schedule for the studies on a month-by-month basis. I refer to the four milestones as _Telepresence Contact, Modular Avatar, Workshops, and Dissertation_:

```{#fig:timeline .pyplot caption="Research timeline draft" links=false}
import numpy as np
from matplotlib import pyplot as plt

x_arr = np.zeros(48)
y_arr = np.arange(48)

x_arr[0] = -24
x_arr[1] = 24
x_arr[2] = -24
x_arr[5] = 24
x_arr[6] = -24
x_arr[10] = -24
x_arr[12] = 24
x_arr[14] = -24
x_arr[15] = 24
x_arr[18] = -24
x_arr[19] = 24 
x_arr[21] = -24
x_arr[22] = 24
x_arr[24] = -24
x_arr[26] = 24
x_arr[28] = -24
x_arr[30] = 24
x_arr[32] = 24
x_arr[34] = -24
x_arr[36] = 24
x_arr[41] = -24
x_arr[42] = 24
x_arr[47] = 24

plt.hlines(y_arr, 0, x_arr, color='red')  # Stems
plt.plot(x_arr, y_arr, 'D')  # Stem ends
plt.plot([0, 0], [y_arr.min(), y_arr.max()], '--')  # Middle bar
plt.ylabel("Month")
ax = plt.gca()
ax.invert_yaxis()
ax.annotate("Beginning of studies", xy=(-24, 0), xytext=(0,10), textcoords="offset points", fontsize='large')
ax.annotate("Telepresence contact:\nliterature review", xy=(24, 1), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Courses:\nGeneral doctoral studies", xy=(-24, 2), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Courses:\nWriting", xy=(-24, 6), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Telepresence contact:\nPrototype design", xy=(24, 5), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Telepresence contact:\nProtype experiment", xy=(-24, 10), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Telepresence contact:\nPublish paper", xy=(24, 12), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Modular avatar:\ndesign research", xy=(-24, 14), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Courses:\nMechanical engineering", xy=(24, 15), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Modular avatar:\ntechnical experiments", xy=(-24, 18), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Modular avatar:\nbegin implementation", xy=(24, 19), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Courses:\nArtitsic research", xy=(-24, 21), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Modular avatar:\nimplementation experiment", xy=(24, 22), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Modular avatar:\npublish paper", xy=(-24, 24), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Workshops:\ndesign research", xy=(24, 26), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Workshops:\nfinal implementation design +\nbudget planning", xy=(-24, 28), xytext=(0,-43), textcoords="offset points", fontsize='large')
ax.annotate("Coordinating Palestine collboration", xy=(24, 30), xytext=(-195,-17), textcoords="offset points", fontsize='large')
ax.annotate("Coures:\nGeneral studies", xy=(24, 32), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Workshops:\ndocumentation planning", xy=(-24, 34), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Workshops:\nimplementation rounds", xy=(24, 36), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Workshops:\npublish paper+exhibition", xy=(-24, 41), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Finalizing dissertation\nmanuscript", xy=(24, 42), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("End of studies", xy=(24, 47), xytext=(-80, -17), textcoords="offset points", fontsize='large')

ax.axes.get_xaxis().set_ticks([])

fig = plt.gcf()
fig.set_size_inches(8, 12)
```

# Bifurcations into other fields

Throughout my doctoral studies, I plan to initiate two main bifurcations in the fields of AI and Bio-Art. Those would be side-projects in which I will inspect the potential to incorporate new elements into my research.

## AI
Over the past year, I have been involved as a co-creator in the _Marrow_ project with Shirin Anlen^[https://shirin.works/Marrow-dev-phase-Machine-learning-immersive-theater-WIP]. The project speculates about the possibility of mental illness occurring in AIs and uses storytelling and theatrical methods to discuss its research findings. While the skills I have acquired during working on Marrow could be useful in augmenting robotic mediation by adding supporting layers to intergroup contact, the main inspiration I draw from this project is a critical perspective on AI. Machine learning systems are increasingly prevalent in society, acting as a steering media, increasing rationalization and reification in interpersonal relations. When adding machine learning support to telerobotic mediation, my experience from Marrow teaches me that AI should be used cautiously and critically, with high awareness of the learning process behind the machine. The importance of transparency of AI will be discussed in the research articles exploring the use of telepresence in conflict resolution.  


## Bio-Art
I have always been interested in and involved in Bio-Art initiatives. My main curiosity revolves around the combination of biological elements and machine logic, both practically and conceptually. A project that I never got around to implement involved the extraction of human DNA and transplanting it into plants. ^[http://avner.js.org/#jewish-roots]. In the context of robotic telepresence, I am interested in the possibilities of encoding parts of our DNA into avatars. Deriving from that is also the need for community-based knowledge in human genome sequencing [@jainNanoporeSequencingAssembly2018].  Incorporating biological elements into telerobotic avatars could raise important questions about the relationship between humans and machines. These topics will be part of research and studied more deeply in one of the sub-studies conducted and published in one of the research articles.

#   Funding
Funding for the first year of my studies is secured through a hired doctoral candidate position at the Learning Environments group. Support for the following three years would be obtained either by grant applications or through dedicated research project budgets.

# References
