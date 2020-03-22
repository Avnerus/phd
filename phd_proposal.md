---
title: Doctoral Candidate in Digital Learning
subtitle: Soft Robotic Telepresence in Conflict Resolution | Research Plan
author: Avner Peled
date: 11/2019
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
I am applying for the position of Doctoral Candidate in Digital Learning in the Learning Environments research group at the Aalto Media Lab. My Master's thesis at the Aalto Media Lab: _Soft Robotic Incarnation_ [@peledSoftRoboticIncarnation2019] incorporated a wide range of theoretical and engineering explorations. Now, I wish to focus on depth rather than breadth and perform fieldwork in education and conflict resolution. The same motivation that brought me to the Media Lab in the first place: the dire need for creative and technological solutions in the Israeli-Palestinian conflict, remains to be my main motivation. I am hoping that through my doctoral studies I will be able to promote positive social change in not only in my home country but also in other locations suffering from similar issues of prejudice and isolation.

With lessons learned from the production of the soft robotic telepresence: HITODAMA, I will produce a new toolkit that allows inexperienced workshop participants to design and produce their soft avatar. The robots would be deployed in a public space and controllers will manage interactions with passersby through their mobile devices or desktops. At the core test case, participants from Palestine would construct their avatars in a workshop, and have them pop-up in public spaces in Israel.  The Palestinians will be able to converse with Israelis beyond the separation wall without exposing their identity. Due to the wall and cultural alienation, encounters between Israelis and Palestinians are scarce and very difficult to organize. This research asks the question of whether a soft telerobot might help in facilitating contact.

By opening the soft robot's production to a participatory workshop in an intergroup conflict context [@tajfelIntegrativeTheoryIntergroup1979], I hope to achieve two main outcomes: 1) Proliferation of technical and scientific knowledge and empowerment in minority groups. 2) Maximum artistic and emotional expression in mediated encounters. The research will be divided into milestones in which design decisions and hypotheses would be put to the test and a publication would follow. First, I will analyze and optimize the use of soft robotics as a medium for intergroup contact. Second, I will evaluate the advantages of designing your own robotic avatar compared to using a pre-designed solution. Finally, I will conduct workshops and deploy solutions in conflict situations, focusing on the Israeli-Palestinian conflict, and analyze the results. 

# Research overview

## Conflict resolution through the release of prejudice

This dissertation will focus on prejudice as a major component in intergroup conflict [@pettigrewIntergroupPrejudiceIts2011]; identifying the major drivers of prejudice, and therefore the possible paths for mitigation. The research will be approached from two different schools of thoughts: That of social psychology and that of metaphysics and phenomenology. From a metaphysical perspective, prejudice could be seen as a particular case of _Reification_. From a social psychology perspective, research will follow Gordon Allport's _Nature of Prejudice_ and the theories that follow.

### Metaphysics of prejudice: From reification to incarnation


The notion of reification was popularized by Lukács' interpretation [-@lukacsHistoryClassConsciousness1971] of Marx's commodity fetishism [@marxCapitalCritiquePolitical2015]. Marx wrote about the transition that occurred in how society values objects: While at first objects were valued by their essence, their objective nature and their use-value; capitalist society 'fetishized' objects by assigning them abstract properties that are not a part of the actual object, i.e their exchange-value. Lukács took this one step further and showed how the entire organization of society and human consciousness gets 'reified'. Wage labor in effect transforms the human into a commodity and societal processes are rationalized under arbitrary systems of value. Adorno and Horkheimer of the Frankfurt school of critical theory took these theories as the basis for the moral deterioration of society and the loss of our raw human nature into rationalized systems of rules such as those that emerged in World War II [@adornoDialecticEnlightenment1997].

There is a clear connection between reification, rationalization, and intergroup prejudice. Sarah Ahmed, for instance, developed a theory of _Stranger Fetishism_ [-@ahmedStrangeEncountersEmbodied2000], demonstrating the clear connection between prejudice and commodity fetishism. In Ahmed's view, abstract information about the stereotypical figure of the stranger circulates through mass-media, intensifying as it is exchanged from source to source. This wounds up creating an emotional fetishism toward the figure of the _other_. We can also approach the same scenario through Jürgen Habermas' thesis of the colonization [-@habermasTheoryCommunicativeAction1984a] of the _Lifeworld_. Habermas views invasive _steering media_, such as money and power, as an interference to the process of reaching a rational agreement inter-subjectively. Without a mutual agreement on rationality, Habermas asserts, political discussion is not possible.

Since this research deals with technological mediation in intergroup conflict, I am interested both in identifying the reifying forces in current communication technology, such as social media [@heymanSocialMediaDelinguistification2015], and the technologies that could be used to mitigate those forces. Borrowing from the writings of Simone Weil [-@weilGravityGrace2002] and Edgar Orion [-@edgarThingsSeenUnseen2012], I have dubbed the name _incarnation_ as a reversal of reification [@peledSoftRoboticIncarnation2019]. In a conversation between individuals of different groups, a conversation that exposes a depth of irreducible human qualities among the interlocutors is likely to reduce fetishism. I hypothesize that an incarnation could be achieved via two main factors: 1) Expressiveness and 2) Corporeality. In contrast to technological initiatives that attempt to expose nuanced human qualities in mediated interaction using biofeedback sensors, I opt for active expression by the interlocutors. In a robotic telepresence scenario, this means allowing the creator of the avatar to design the appearance and movements of their robot, and trigger those movements only when intended. The potential for custom-designed social robots was demonstrated by Suguitan and Hoffman [-@suguitanBlossomHandcraftedOpenSource2019], and I wish to take this further into designing actuation and behavior. 

The other important factor that I will focus on is _Corporeality_, or in its inter-subjective form _Intercorporeality_. This term was coined by phenomenologist Maurice Merleau-Ponty [-@merleau-pontyVisibleInvisibleFollowed1968] and is used to describe the tight physical inter-dependence between humans that is constitutive not only to social cognition but also to the nature of _Being_, the conscious experience. I hypothesize that in a  mediated encounter, more physical interaction is more authentic to the interlocutors' _logos_ - the essence of their social being, their voice [@ranciereDisagreementPoliticsPhilosophy1999;@edgarThingsSeenUnseen2012]. On the other hand, an abstract, flat, and virtual experience could be liable for generating a biased and fetishized figure of the stranger in the interlocutors' mind. I will test the viability of the soft robotics medium, with its organic and nonlinear style of movement, to enable an intercorporeal experience when compared to a traditional motorized robot or a virtual encounter.

Apart from the soft materiality of the robot, design choices carry a crucial role in determining the position of the experience on the intercorporeal scale. The use and location of a display, turn-taking dynamics, modalities of language, the fluidity and dynamic range of the controls and robotic motion, the field of view of the camera, feedback signals - these are all elements that vary the user experience as a whole, shifting the perception of the interlocutors, their view of the robot, and their view of each other. Pursuing these questions under the scope of a doctoral dissertation would provide me with ample time to delve into each UX element, placing them on the intercorporeal scale, designing variations and testing them in the field.

## Social psychology and the Contact Hypothesis
Gordon Allport's _Nature of Prejudice_ from 1954 [@allportNaturePrejudice1954] lays the foundation for the _Contact Hypothesis_: A theory suggesting that an interpersonal contact between groups can reduce prejudice. Allport suggests four conditions for an organized encounter that need to be fulfilled for the contact to be effective: equal status, common goals, cooperation, and institutional support.50 years later, a meta-analysis conducted by Pettigrew and Tropp was able to validate the hypothesis across a large number of studies [-@pettigrewMetaanalyticTestIntergroup2006].

Despite Pettigrew and Tropp's conclusions, applying the contact hypothesis to the Israeli-Palestinian conflict is more complicated, as suggested by Maoz [-@maozDoesContactWork2011]: "The majority of existing research does not study the effectiveness of intergroup contact interventions in conditions of acute asymmetrical violent conflict". Maoz reviewed a variety of conflict resolution initiatives and categorized them into four models: the Coexistence Model, the Joint Projects Model, the Confrontational Model, and the Narrative-Story-Telling Model. While every model had its advantages and disadvantages, it was clear that the Israeli-Palestinian conflict, with its deep-rooted prejudice and persistent state of power relation between the colonizer and the colonized, does not always bode well with the contact hypothesis.
 
Communication technology expands the aforementioned models of contact and adds new modalities of interaction while giving up the benefits of face-to-face contact. Research on online intergroup contact [@haslerOnlineIntergroupContact2013;@amichai-hamburgerStructuredUnstructuredIntergroup2015] has shown that while there are obstacles and challenges in implementations, there is a  potential for online intergroup contact to reduce prejudice and aid in conflict resolution. I have experienced this myself once, in a chat roulette website that popped up during war-time between Israel and Gaza. The website allowed right-wing and left-wing Israelis to fight about politics anonymously; I was surprised in how meaningful some of the encounters were [@peledSoftRoboticIncarnation2019, p. 43]. Other encounters, however, were antagonistic and offensive by nature and could have contributed to an increase in prejudice. As shown also in Walther et al [-@waltherComputermediatedCommunicationReduction2015], the mere contact is not enough, but the content and context of the contact determine whether the result would be positive or negative.

Recently, there have been attempts to bring virtual reality into conflict resolution. Most of the research focused on using VR as an empathy machine; allowing intergroup members to immerse themselves in perspective of the other side. Other research focused on simulated, pre-recorded contact that was optimized for making one side feeling empathy toward another [@haslerVirtualPeacemakersMimicry2014;@kabiljoVirtualRealityFostering2019;@hassonEnemyGazeImmersive2019]. Not much research was done on the effects of VR on organic intergroup contact events, such as in the popular application _VR Chat_ ^[https://vrchat.com/], a form of _Second Life_ tailored for VR. In this dissertation, however, I would focus on another form of organic, intergroup, contact: one that is based on robotic telepresence. As mentioned in the previous section, soft robotic telepresence adds an _intercorporeal_ dimension to the contact which may increase the efficacy of the encounter and help with the release of prejudice. No attempt has been done yet to bring the contact hypothesis to the field of robotic telepresence; finding out whether such an encounter would be beneficial for conflict resolution could contribute greatly to the academic and peace-activist community.

Additionally, allowing the out-group members to design their own avatar could utilize principles of expressive art therapy. The participants would get a chance to freely mold their self-image into a non-human avatar, which may have therapeutic benefits [@muriFaceArtTherapy2007;@sholtTherapeuticQualitiesClaywork2006]. Applying self-expression techniques with Palestinians in intergroup conflict could benefit from  Boal's theory of the  _Theatre of the Oppressed_ [@boalTheatreOppressed2008]. The controllers would be able to design their expressions into the robot, whether it is an offensive hand gesture or an offer for peace. Combining technological and expressive arts techniques with pedagogy and empowering the oppressed provides a transdisciplinary approach to conflict resolution in asymmetrical intergroup conflicts.

## Post-humanoid, web-based, soft robotic toolkit for telepresence


In this dissertation, I will create a modular, easy to use toolkit for the preparation of remote-controlled soft robotic avatars. The toolkit would allow participants to design their movements using flexible methods such as origami-inspired structures [@peraza-hernandezOrigamiinspiredActiveStructures2014]. The modules would then be connected to a central pneumatic system and communication controller that automatically provides conversation and actuation capabilities, including language translation and remote control via the mobile web (see [@fig:diagram]).

![Modular Soft robotic control: Architecture diagram](diagram.jpg){#fig:diagram}


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

The majority of the technology for the central communication controller was already developed during the Master's thesis. Upcoming technical research will focus on new soft actuator designs that favor simplicity and flexibility over strength and precision. The actuators need to be easily produced in a workshop scenario with inexperienced participants and inexpensive materials. Insofar as the avatar is designed for expressiveness and social communication rather than explicit functional tasks, organic mistakes and deformations are a welcomed addition and not a mark of failure. I draw inspiration from the maker culture and the _Hebocon_ robot competition ^[https://spectrum.ieee.org/automaton/robotics/diy/hebocon-the-best-worst-robot-competition], as well as from on my own experience in delivering workshops ^[https://vimeo.com/210919628]. Additional research will be dedicated to developing remote control methods that take better advantage of the soft medium and allow for more fluid control. On example could be the use of the phone's accelerometer or finger-sliding, to control the pneumatic system in real-time, producing a fluid motion.

# Advisors 

I have confirmed the availability of three advisors for my studies: 

1. Prof. Teemu Leinonen: Head of the Learning Environments research group and supervisor of my studies.

2. Dr. Mia Muurimäki: A former Aalto Media Lab faculty and now a service designer team leader in Futurice. Mia has helped me during my Master's thesis in a multitude of ways. She directed me to relevant literature, suggested design changes and advised me on project management and schedules. Mia has been conducting participatory and co-design workshops in Futurice and I am sure she will also be able to advise me in that field.

3. Dr. Béatrice Hasler: Founder of VR-CORE: Virtual Reality Lab for Conflict Research in IDC Herzilya research school in Israel. Béatrice has years of experience researching virtual intergroup contact in the Israeli-Palestinian conflict and has studied online collaboration. Beatrice graciously offered to advise and participate in this research and has introduced me to missing links in social psychology that are essential for this dissertation.

# Time-line

I propose to divide my studies into four milestones in four years. Three milestones will produce a publication, and the final product is the dissertation, aggregating and concluding the research. The milestones suggested are as follows:

1. **Soft Robotic Telepresence for intergroup contact**: A literature review of social-psychology, phenomenology and critical theory evaluating the potential of soft robotic telepresence for fulfilling the contact hypothesis. The study would include a comparison to other forms of intergroup contact, and if possible a prototype and test for a simple soft robot that could test the hypothesis. _Due to the COVID-19 pandemic^[https://www.who.int/emergencies/diseases/novel-coronavirus-2019], practical tests might not be possible_

2. **A modular, DIY soft robotic avatar**: I will present a pedagogical and therapeutic toolkit for creating your soft robotic avatar and evaluate it with a test group study.

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
Over the past year, I have been involved as a co-creator in the _Marrow_ project with Shirin Anlen^[https://shirin.works/Marrow-dev-phase-Machine-learning-immersive-theater-WIP]. The project speculates about the possibility of mental illness occurring in AIs and uses storytelling and theatrical methods to discuss its research findings. While the skills I have acquired during working on _Marrow_ could be useful in augmenting robotic mediation by adding supporting layers to intergroup contact, the main inspiration I draw from this project is a critical perspective on AI. Machine learning systems are increasingly prevalent in society, acting as a _steering media_, increasing rationalization and reification in interpersonal relations. AI should be used cautiously and critically, with high awareness of the learning process behind the machine.

## Bio-Art
I have always been interested in and involved in Bio-Art initiatives. My main curiosity revolves around the combination of biological elements and machine logic, both practically and conceptually. A project that I never got around to implement involved the extraction of human DNA and transplanting it into plants ^[http://avner.js.org/#jewish-roots]. In the context of robotic telepresence, I am interested in the possibilities of encoding parts of our DNA into avatars. Deriving from that is also the need for community-based knowledge in human genome sequencing [@jainNanoporeSequencingAssembly2018]. I hope to pursue this side project as I progress in my dissertation.

# Teaching
Teaching is very important and meaningful to me. I was already teaching during my Master's, designing and lecturing the first Media Lab course on Contemporary Web Development^[https://mycourses.aalto.fi/course/view.php?id=20797]. I would love to have the opportunity to teach more during my doctoral studies. Other than web development, x options for teaching include 1) Soft Robotics workshop, 2) Studies of prejudice, 3) Workshop for self-hosting your cloud, 4) Python and Machine Learning, and 5) DNA Sequencing workshop.

# References
