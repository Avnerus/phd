---
title: Doctoral Candidate in Digital Learning
subtitle: Applicant statement
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
With great determination and humility, I am applying for the position of Doctoral Candidate in Digital Learning in the Learning Environments research group at the Aalto Media Lab. Following the completion of my Master's thesis at the media lab: _Soft Robotic Incarnation_ [@peledSoftRoboticIncarnation2019], I wish to carry on the same research path that brought me to my current state, but to expand on it, and induce bifurcations that would lead me to unexplored territories of soft robot mediation. I intend to persist with an active and exploratory approach that adjoins scientific research with philosophy and philosophy with design and artistic practices; not forgetting the initial motivation that brought me to the media lab, the dire need for creative and technological solutions in the Israeli-Palestinian conflict. 

During my doctoral studies, I aim to design and produce the next generation of my soft robotic telepresence: HITODAMA, as well as deploy it in public spaces both in Israel and in Palestine. At the same time, I will perform local case studies in Finland to asses UX and technological strategies, targeting public spaces and educational systems. I hope to initiate international research collaborations, not only in Japan as I have already done in my Master's thesis, but also in Israel, where cutting edge research in the psychology of conflict and expressive robotics is taking place, and in Palestine, where emerging artists and technologists are dealing with the conflict from personal and informed perspectives. I have devised the following draft for a research plan based on the conclusions and evaluations of my Master's thesis, as well as my future aspirations for the field.

# Research overview
 
## From reification to incarnation through user experience
Robotic telepresence is experienced both by the local interlocutor who is interacting with the mediating robot, and the remote individual taking control of the robot. The depth, authenticity, and presence of the users' irreducible human qualities vary against the natue of the medium and its user interface. These notions are expressed nominally through phenomenological terms [@] such as _flesh_ [@merleau-pontyVisibleInvisibleFollowed1968], _logos_ [@ranciereDisagreementPoliticsPhilosophy1999;@edgarThingsSeenUnseen2012] and _intercorporeality_ [@merleau-pontyVisibleInvisibleFollowed1968;@meyerIntercorporealityEmergingSocialities2017]. A spectrum could be thought-of (see @fig:incarnation), describing the range of phenomena within individuals on both sides of the conversation in relation to the depth and corporeality of the interaction. As the local interlocutor incorporates the embodied figure of the stranger into their mind as it is represented by a robot, the experience ranges between two phenomenological endpoints: When it is a shallow, flat, virtual, experience, I hypothesize that the interlocutor is liable to generate a biased and fetishized figure of the stranger [@ahmedStrangeEncountersEmbodied2000]; a reification of predispositions that stick to the body of the stranger. When the interaction, however, has corporeal depth, the veritable logos of the stranger is assimilated into the body of the interlocutor. At the same time, a spectrum of experience exists for the controller, in which I hypothesize that the sense of agency and ownership [@dolezalRemoteBodyPhenomenology2009] rises in relation to the depth of the interaction. This affects the controller's ability to express themselves; when they experience an increased sense of ownership, they are more accountable to their actions but are then more cautions in expressing deeper and more controversial opinions.

Design choices carry a crucial role in determining the position of the experience on the intercorporeal scale. The use and location of the digital display, the turn-taking dynamics, modalities of language, the fluidity and dynamic range of the controls and robotic motion, the field of view of the camera, feedback signals - these are all elements that vary the user experience as a whole, shifting the perception of the interlocutors, their view of the medium, and    of each-other. Pursuing these questions under the scope of a doctoral dissertation would provide me with ample time to delve into each UX element, placing them on the intercorporeal scale, designing variations and testing them in the field.

```{#fig:incarnation .pyplot caption="Interaction through robot mediation" links=false}
import matplotlib.pyplot as plt

plt.figure()
fig, axs = plt.subplots(2, 1, sharex=True)
axs[0].plot([0,1,2,3,4], [0,1,2,3,4], marker='o', color='red')
axs[1].plot([0,1,2,3,4], [0,1,2,3,4], marker='o')
plt.xlabel('Depth of intercorporeality')
axs[0].set(ylabel="Controller's experience")
axs[0].set_yticks([])
axs[1].set(ylabel="Interlocutor's experience")
axs[0].text(2.4, 3.8, "Agency & Ownership")
axs[0].text(-0.1, 0.7, "Alienation")
axs[1].text(3., 3.8, "Incarnation")
axs[1].text(-0.1, 0.7, "Reification")
frame1 = plt.gca()
frame1.axes.get_xaxis().set_ticks([])
frame1.axes.get_yaxis().set_ticks([])
```

## Post-humanoid, web-based soft robotics as an expressive medium
 Research on soft robotics will expand beyond the creation of my previous soft robotic prototype, HITODAMA: a post-humanoid robot inspired by Japanese spirit folklore and the regenerative salamander Axolotl. The focus now turns to exploiting the full range of possibilities enabled by the soft medium. A fluid web-based remote control, one that does not rely on passive sensing, but encourages active expression using lowest-denominator devices such as low-tier smartphones and desktops, stands as the holy grail of soft telepresence. As a ground plan, the complexity of the soft body parts used for HITODAMA could be drastically reduced, opting for smaller, more abstract shapes that still convey organic characteristics and enable fluid control, then new fabrication methods would be developed,for optimizing the response time and fluidity of the resulting product.

The soft robotic medium is largely based on pneumatics, requiring the robot to be connected by air tubes to an array of pneumatic circuits. This, however, limits the mobility of the experience, forcing the interaction to occur within the limited range of the tubes, but also frames the experience to a specific site and context. Untethered solutions for soft robots do exist, however, whether they are using enclosed pneumatic micro-circuits, or completely different actuation methods such as dielectric elastomers [@richUntetheredSoftRobotics2018]. The viability, cost, and complexity of those solutions should be measured against the advantages of a more mobile experience.

## Robotic mediation for conflict resolution
The primary goal that was stated for HITODAMA is mediation in conflict resolution when a face-to-face meeting between the adversaries is not possible or highly unlikely. In my Master's thesis, however, the scope of the tests was limited to interactions between Finnish locales and foreign immigrants. Furthermore, I did not have time for a deep investigation of conflict resolution methodologies and their juxtaposition with telerobotic mediation. One vantage point comes from the research of Professor Ruth Feldman, who formulates connections between haptic sociality, neuroscience, and approaches to conflict resolution in the Israeli-Palestinian conflict [@influsSocialNeuroscienceApproach2018]. I have contacted Professor Feldman regarding my project and was invited to visit her lab. I asked her whether she collaborated with the MILab ^[http://milab.idc.ac.il/], a human-computer interaction lab under the same academic institution as Feldman that specializes in innovation in the field of robotic movement [@hoffmanDesigningRobotsMovement2014]. Feldman has responded that they were, in fact, planning a collaboration, but were so far not able to realize it due to time constraints. It is my hope that I would be able to act as a bridge between those two disciplines, perhaps with the help of IDC's 
Global Affairs and Conflict Resolution Cluster^[https://www.idc.ac.il/en/schools/rris/undergraduate/pages/global-conflict.aspx]. Naturally, scholars specializing in conflict resolution are abundant in Israel and there are multiple pathways for collaboration. One point of interface could occur with Dr. Yael Berda, who specializes in freedom of movement and the bureaucracy that manages it. In an interview in _Haaretz_ newspaper ^[https://www.haaretz.co.il/magazine/.premium-MAGAZINE-1.5975041 (In Hebrew and for subscribers only)], Berda discussed the embodied cognitive effects of the occupation and the bodily experience of crossing the separation barrier. In addition to Israeli connections, it is imperative to involve the Palestinian art and science scene in the process. Before starting my Master's thesis, I had a chance to meet an artist and maker from Ramallah with whom I shared my vision for this project. He was very excited to participate, but because HITODAMA never made it to the final goal, we never carried through with our plans for collaboration. This time, however, I will commit to realizing the project in Israel and Palestine and will pursue the involvement of Palestinian partners as early as possible.

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
