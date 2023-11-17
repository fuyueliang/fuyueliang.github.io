---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
---
I am a graduating PhD student of Matar Fluid Group in the department of Chemical Engineering at Imperial College London. My main research topics focus on Computational Fluid Dynamics (CFD) in multi-phase flow mixing (i.e., oil-water emulsion) and the applications of machine learning-based techniques in this community. 

## CFD in multi-phase flow mixing
------
This part of work are dedicated to understand complex dynamics involved in oil-water emulsification inside a stirred vessel, based on a well-developed numerical simulator where a state-of-art hybrid front-tracking/level-set interface capturing algorithm is embedded. This scenario encompasses multiple non-idealities which are common in practice, such as high turbulence, high volume fraction of dispersed phase, the presence of contaminants (e.g., surfactants). Through this project, I provided a clear inspection of vortical structures and interface singularities within such a mixing system which has never been achieved via previous experiments or numerical studies.
<span style="display:block; ">
![Example of my CFD simulations](/images/interface.png)
</span>

## Machine learning-based techniques in mixing
------
Currently, I am taking advantage of the rich data obtained from the high-fidelity CFD simulations to train a time series prediction model, Long Short-Term Memory (LSTM) nerual nets, with the aim of predicting temporal mixing performance metrics (i.e., drop count, interfacial area and drop size distribution) without carrying out expensive numerical simulations, in other words, developing a cheaper yet reliable surrogate model to carry out performance predictions which can be relevant for industrial operation and equipment design. The next step of my work is to map mixer geometry and surfactant physiochemical properties to the abovementioned metrics via regression models with the use of active learning sampling techniques, hence characterizing mixing systems through ML techniques and providing a robust predictive framework that departs from conventional CFD.
<span style="display:block; ">
![Example of the rollout](/images/rollout.png)
</span>
