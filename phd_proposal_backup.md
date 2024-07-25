---
title: Doctoral Candidate in Digital Learning
subtitle: Research Plan
author: Avner Peled
date: 11/2019
documentclass: article
indent: true
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
With great determination and humility, I am applying for the position of Doctoral Candidate in Digital Learning in the Learning Environments research group at the Aalto Media Lab. Following the completion of my Master's thesis at the media lab: _Soft Robotic Incarnation_ [@peledSoftRoboticIncarnation2019], that incorporated a wide range of philosophical and scientific explorations, I wish to now focus on depth rather than breadth and perform actual field work in education and conflict resolution. The motivation that brought me to the media lab in the first place: the dire need for creative and technological solutions in the Israeli-Palestinian conflict, remains to be my main motivation. I am hoping that during my doctoral studies I will be able to catalyze tectonic changes in this area. 

With lessons learned from the production of the soft robotic telepresence: HITODAMA, I aim to produce a new toolkit that will allow participants in a workshop scenario to design and produce their own soft avatar, deploy it in a public space and manage interactions through their mobile devices or desktops. By opening the soft robot's production to a participatory workshop in an inter-group conflict context [@tajfelIntegrativeTheoryIntergroup1979], I hope to achieve two main outcomes: 1) Proliferation of technical and scientific knowledge in minority groups. 2) Maximum artistic and emotional expression in mediated inter-group conflict encounters. Research will be divided into milestones in which design decisions and hypotheses would put to the test and publication would be released with the results. First, I will justify and optimize the use of soft robotics as a medium for conflict resolution and participatory projects. Second, I will evaluate the advantages of designing your own robotic avatar compared to using a pre-designed solution. Finally, I will conduct workshops and deploy solutions in conflict situations, focusing on the Israeli-Palestinian conflict, and gather the results. 

# Research overview
 
## From reification to incarnation through expressiveness and corporeality
The notion of reification was popularized by Lukács' interpretation [-@lukacsHistoryClassConsciousness1971] of Marx's commodity fetishism [@marxCapitalCritiquePolitical2015]. Marx wrote about the transition that occurred in how society values objects: While at first objects were valued by their essence, their objective nature and their use-value, capitalist society 'fetishizes' objects by assigning them abstract properties that are not a part of the actual object, i.e their exchange-value. Lukács took this one step further and showed how the entire organization of society and human consciousness get 'reified'. Wage labour in effect transforms the human into a commodity and societal process are rationalized under arbitrary systems of value. Adorno and Horkheimer of the Frankfurt school of critical theory took these theories as the basis for the moral deterioration of society and the loss of our raw human nature into rationalized systems of rules such as those that emerged in World War II [@adornoDialecticEnlightenment1997].

There is a clear connection between reification, rationalization and prejudice toward humans such as racial bias. Sarah Ahmed, for instance, developed a theory of _Stranger Fetishism_ [-@ahmedStrangeEncountersEmbodied2000], demonstrating the clear connection between prejudice and commodity fetishism. In Ahmed's opinion, abstract information about the stereotypical figure of the stranger circulates through mass-media, intensifying as it is exchanged from source to source, creating a fetishism toward the _other_. Another angle could be approached through Jürgen Habermas' thesis of colonization [-@habermasTheoryCommunicativeAction1984a] of the _Lifeworld_. Habermas views invasive _steering media_ such as money and power as an interference to the process of reaching a rational agreement inter-subjectively; a process that is required for having a productive political discussion.

Since this research deals with technological mediation in inter-group conflict, I am interested both in identifying the reifiying forces in current communication technology (Such as social media as in [@heymanSocialMediaDelinguistification2015]), and the technologies that could be used to mitigate those forces. Borrowing from the writings of Simone Weil [-@weilGravityGrace2002] and Edgar Orion [-@edgarThingsSeenUnseen2012], I have dubbed the name _incarnation_ as a reversal of reification [@peledSoftRoboticIncarnation2019] in a conversation between in-group and out-group members; a conversation that exposes a depth of irreducible human qualities among the interlocutors. I hypothesize that an incarnation could be achieved via two main factors: 1) Expressiveness and 2) Corporeality. In contrast to technological initiatives that attempt to expose nuanced human qualities in mediated interaction using biofeedback sensors, I would take the approach of maximum active expression by interlocutors. In a robotic telepresence scenario, this would first manifest by allowing the creator of the avatar to design their own appearance and movements. The potential for custom designed social robots was already demonstrated by Suguitan and Hoffman [-@suguitanBlossomHandcraftedOpenSource2019]. I would like take this further and examine the therapeutic benefits of designing a representation of yourself as an avatar, when guided by principles of expressive art therapy. In addition to designing the looks of the robot, the participants would also be able to customize certain movements, as they will be manufacturing the robot's soft actuators. The movements could then be actively triggered by the controllers using a web interface that I will provide. 

The other important factor that I will focus on is _Corporeality_, or in its inter-subjective form _Intercorporeality_. This term was coined by phenomenologist Maurice Merleau-Ponty and is used to describe the tight physical inter-dependence between humans that is constitutive not only to social cognition but also to the nature of _Being_, the conscious experience. The assumption that I started interrogating in my Master's thesis is that even in a mediated encounter, an interaction that is more physical is more authentic to the interlocutor's _logos_ [@ranciereDisagreementPoliticsPhilosophy1999;@edgarThingsSeenUnseen2012]. As one interlocutor is located in a shared physical space with a robot, representing the other interlocutor, a corporeal experience facilities the assimilation of the controller's veritable logos. On the other hand, a more shallow, flat, virtual, experience could be liable to generating a biased and fetishized figure of the stranger. In this doctoral research I will test the viability of the soft robotics medium to enable an intercorporeal experience, when compared to a traditional motorized robot or to a virtual encounter.

Apart from materiality, design choices carry a crucial role in determining the position of the experience on the intercorporeal scale. The use and location of the digital display, the turn-taking dynamics, modalities of language, the fluidity and dynamic range of the controls and robotic motion, the field of view of the camera, feedback signals - these are all elements that vary the user experience as a whole, shifting the perception of the interlocutors, their view of the medium, and of each-other. Pursuing these questions under the scope of a doctoral dissertation would provide me with ample time to delve into each UX element, placing them on the intercorporeal scale, designing variations and testing them in the field.

## Post-humanoid, web-based, soft robotic toolkit for avatars
The goal of the dissertation is to create a modular, easy to use toolkit for preparation of soft robotic avatars. The toolkit would allow participants to design their own movements using flexible methods such as origami inspired structures [@peraza-hernandezOrigamiinspiredActiveStructures2014]. The modules would then be connected to central pneumatic system and communication controller that automatically provides conversation and actuation capabilities (see [@fig:diagram]).

![Modular Soft robotic control: Architecture diagram](images/diagram.jpg){#fig:diagram}

 Research will focus on methods that exploit the full range of possibilities enabled by the soft medium. A fluid web-based remote control, one that does not rely on passive sensing, but encourages active expression using lowest-denominator devices such as low-tier smartphones and desktops, stands as the holy grail of soft telepresence. As a ground plan, the complexity of the soft body parts used for HITODAMA could be drastically reduced, opting for smaller, more abstract shapes that still convey organic characteristics and enable fluid control, then new fabrication methods would be developed,for optimizing the response time and fluidity of the resulting product.

The soft robotic medium is largely based on pneumatics, requiring the robot to be connected by air tubes to an array of pneumatic circuits. This, however, limits the mobility of the experience, forcing the interaction to occur within the limited range of the tubes, but also frames the experience to a specific site and context. Untethered solutions for soft robots do exist, however, whether they are using enclosed pneumatic micro-circuits, or completely different actuation methods such as dielectric elastomers [@richUntetheredSoftRobotics2018]. The viability, cost, and complexity of those solutions should be measured against the advantages of a more mobile experience.

## Robotic mediation for conflict resolution
The primary goal that was stated for HITODAMA is mediation in conflict resolution when a face-to-face meeting between the adversaries is not possible or highly unlikely. In my Master's thesis, however, the scope of the tests was limited to interactions between Finnish locales and foreign immigrants. Furthermore, I did not have time for a deep investigation of conflict resolution methodologies and their juxtaposition with telerobotic mediation. One vantage point comes from the research of Professor Ruth Feldman, who formulates connections between haptic sociality, neuroscience, and approaches to conflict resolution in the Israeli-Palestinian conflict [@influsSocialNeuroscienceApproach2018]. I have contacted Professor Feldman regarding my project and was invited to visit her lab. I asked her whether she collaborated with the MILab ^[http://milab.idc.ac.il/], a human-computer interaction lab under the same academic institution as Feldman that specializes in innovation in the field of robotic movement [@hoffmanDesigningRobotsMovement2014]. Feldman has responded that they were, in fact, planning a collaboration, but were so far not able to realize it due to time constraints. It is my hope that I would be able to act as a bridge between those two disciplines, perhaps with the help of IDC's 
Global Affairs and Conflict Resolution Cluster^[https://www.idc.ac.il/en/schools/rris/undergraduate/pages/global-conflict.aspx]. Naturally, scholars specializing in conflict resolution are abundant in Israel and there are multiple pathways for collaboration. One point of interface could occur with Dr. Yael Berda, who specializes in freedom of movement and the bureaucracy that manages it. In an interview in _Haaretz_ newspaper ^[https://www.haaretz.co.il/magazine/.premium-MAGAZINE-1.5975041 (In Hebrew and for subscribers only)], Berda discussed the embodied cognitive effects of the occupation and the bodily experience of crossing the separation barrier. In addition to Israeli connections, it is imperative to involve the Palestinian art and science scene in the process. Before starting my Master's thesis, I had a chance to meet an artist and maker from Ramallah with whom I shared my vision for this project. He was very excited to participate, but because HITODAMA never made it to the final goal, we never carried through with our plans for collaboration. This time, however, I will commit to realizing the project in Israel and Palestine and will pursue the involvement of Palestinian partners as early as possible.

# Advisors 

I have so far contacted two potential advisors for my work: 1) Mia Muurimäki: A former Aalto Media Lab faculty and now a service designer team leader in Futurice. Mia has helped me during my Master's thesis in a multitude of ways. She directed me to relevant literature, suggested design changes and advised me on project management and schedules. Mia has been conducting participatory and co-design workshops in Futurice and I am sure she will also be able to advise me in that field.



# Bifurcations into other fields

## AI

## Bio-Art


# Time-line

I propose to divide my studies into four milestones in four years. Three milestones will produce a publication, and the final production is the dissertation, 
hello[@peledSoftRoboticIncarnation2019]
aggregating and concluding the research. The milestones suggested are as follows:

1. **Fluid web-based control for soft robotics**: The biggest technical challenge lies in the control methods for soft robotics. How do we allow a fluid and authentic transference of the controller's _flesh_ through web-based soft robotics control? The goal is to optimize the soft robotics medium for fluid remote control while still maintaining an accessible web-based interface. The technological research would be accompanied by phenomenological research, to match the right technology to the right experience, and budget planning for the required technological resources.

2. **Designing an avatar for incarnation**: Based on the results from the previous stage and the conclusions from the Master's thesis, design an avatar that maintains agency and presence, while still providing ample interaction features. The goal is to provide a flexible interaction platform but without losing the perception of the medium as an incarnation of the controller, reducing it to a simple communication device. The research would incorporate design methodologies backed by phenomenological investigations. 

3. **Designing a telerobot for conflict resolution**: After the fundamental components that make up a meaningful and fluid telerobotic interaction are decided, the implementation would focus on the scenario of conflict resolution and tackling prejudice and bias. Preliminary research for this task would begin early on, to make sure that the chosen solutions for interaction are able to afford the necessary modalities for conflict resolution (for example, might it be necessary to allow presenting internet media and resources during the conversation?).

4. **Final experiment: Israel & Palestine**: The final implementation would be tested and documented on the field in Israel and Palestine, followed by an exhibition of the results and the release of the final dissertation.

Parallel to the above-mentioned milestones, collaboration, and residency opportunities would be sought after. According to the availability and research-focus of partners in Israel and Palestine, the right time for a residency would be chosen. The following graph outlines the planned schedule for the studies on a month-by-month basis:

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
x_arr[22] = 24
x_arr[24] = -24
x_arr[26] = 24
x_arr[28] = -24
x_arr[30] = 24
x_arr[32] = 24
x_arr[34] = -24
x_arr[38] = 24
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
ax.annotate("Fluid control:\nphenomenological research", xy=(24, 1), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Fluid control:\ntechnological research+\nbudget planning", xy=(-24, 2), xytext=(0,-43), textcoords="offset points", fontsize='large')
ax.annotate("Planning Israel-Palestine\nresidencies", xy=(-24, 6), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Fluid control:\nbeginning of implementaiton", xy=(24, 5), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Fluid control:\nimplementation experiment", xy=(-24, 10), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Fluid control:\npublish paper+exhibition", xy=(24, 12), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Incarnation avatar:\ndesign research", xy=(-24, 14), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Incarnation avatar:\nphenomenlogical investigations", xy=(24, 15), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Incarnation avatar:\nbeginning implementation", xy=(-24, 18), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Incarnation avatar:\nimplementation experiment", xy=(24, 22), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Incarnation avatar:\npublish paper+exhibition", xy=(-24, 24), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\nresearch", xy=(24, 26), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\nfinal implementation design +\nbudget planning", xy=(-24, 28), xytext=(0,-43), textcoords="offset points", fontsize='large')
ax.annotate("Initiating Palestine collboration", xy=(24, 30), xytext=(-180,-17), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\nbeginning implementation", xy=(24, 32), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\ndocumentation planning", xy=(-24, 34), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\nexperiment", xy=(24, 38), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("Conflict resolution:\npublish paper+exhibition", xy=(-24, 41), xytext=(0,-30), textcoords="offset points", fontsize='large')
ax.annotate("Finalizing dissertation\nmanuscript", xy=(24, 42), xytext=(-180,-30), textcoords="offset points", fontsize='large')
ax.annotate("End of studies", xy=(24, 47), xytext=(-80, -17), textcoords="offset points", fontsize='large')

ax.axes.get_xaxis().set_ticks([])

fig = plt.gcf()
fig.set_size_inches(8, 12)
```

# References
