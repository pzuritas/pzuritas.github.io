---
layout: page
permalink: /research/
nav: true
nav_order: 2
---

_Differential equations in pathophysiology._

The human body is a marvellous collection of systems where different kinds of physics are constantly at play. From cells to full organs, different elements in the body work across scales for the people who inhabit them, enabling them to live good lives. These systems can and do fail, and we can strive for a better understanding of how to fix these systems by looking at their underlying principles. My research is focused on the applications of mathematical analysis (based on differential equations) for the understanding of biophysical principles, and the development of computational tools to explore the functioning of biophysical systems. I am mostly interested in modelling at the tissue level, with multiscale connections to cells and systems.

### Bloodflow and gas exchange

_Porous media fluid mechanics_, _nonlinear elasticity_, _transport phenomena_, _finite element methods_, _nonlinear analysis_.

Alveoli are the little structures in your lungs where oxygen enters the bloodstream and carbon dioxide leaves it. You breathe to make this happen, but nonetheless this process can fail locally for many reasons: if blood isn't flowing, if your red blood cell count is low, if air isn't going to the alveolus, or if the contents of said air are not quite right. These little alveoli are arranged in a fascinatingly intricate fashion, allowing for greater effectiveness and robustness of this crucial process. With [Dr. Daniel E. Hurtado](https://www.researchgate.net/profile/Daniel-Hurtado-4), we [worked](https://www.sciencedirect.com/science/article/pii/S0045782522004686) on developing a fully three-dimensional system of partial differential equations that models this phenomenon, and a straightforward numerical method to approximately solve it.

<!-- The system of equations turned out to be quite interesting, and with the guidance of [Dr. Nicolás A. Barnafi Wittwer](https://nabw.github.io/about.html), we [analysed]() it to uncover some fundamental properties regarding the behaviour of the system and its relationship to biomedical parameters that may be of interest to health professionals. -->

### Cilia coordination

_Low Reynolds number fluid mechanics_, _fluid-structure interaction_, _high performance computing_.

The tissue that comprises your body is made of cells which, more often than not, are lined with tiny appendages called cilia. In some cases, such as your brain and inner airway, these cilia work like little mechanical arms that move surrounding fluid. Every time you inhale, for example, there's a chance that dangerous pathogens flow into your respiratory system. That's why your airways are lined with a complex fluid called mucus, that traps most of these pathogens. The cilia in your lung cells then move the mucus to expel it and keep you safe. It turns out that there are thousands of these little cilia, and it's imperative that they work together; lest the pathogens stay stuck and are able to cause you harm. I'm currently working with [Dr. Eric Keaveny](https://www.ma.imperial.ac.uk/~ekeaveny/) to understand the coordination of cilliated cells: how it comes about and the role that it has on moving biofluids in complex domains. We build dynamical system descriptions of individual cilia dynamics which couple with the Stokes equation that governs surrounding fluid, creating a complex system with emergent properties.
