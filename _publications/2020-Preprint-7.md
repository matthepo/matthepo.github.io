---
title: "Detecting Deception Attacks on Autonomous Vehicles via Linear Time-Varying Dynamic Watermarking"
authors: "M. Porter, S. Dey, A. Joshi, P. Hespanhol, A. Aswani, M. Johnson-Roberson, R. Vasudevan, A. Aswani"
collection: publications
permalink: /publication/2020-Preprint-7
year: 2020
venue: 'arXiv preprint arXiv:2001.09859'
preprint: 'https://arxiv.org/abs/2001.09859'
techreport:
video:
abstract: "Cyber-physical systems (CPS) such as autonomous vehicles rely on both on-board sensors and external communications to estimate their state. Unfortunately, these communications render the system vulnerable to cyber-attacks. While many attack detection methods have begun to address these concerns, they are limited to linear time-invariant (LTI) systems. Though LTI system models provide accurate approximations for CPS such as autonomous vehicles at constant speed and turning radii, they are inaccurate for more complex motions such as lane changes, turns, and changes in velocity. Since these more complex motions are more suitably described by linear time-varying (LTV) system models rather than LTI models, Dynamic Watermarking, which adds a private excitation to the input signal to validate measurements, has recently been extended to LTV systems. However, this extension does not allow for LTV systems that require several steps before the effect of a given control input can be seen in the measurement signal. Additionally, there is no consideration for the time-varying effects of auto-correlation. Furthermore, a proof of concept was only provided using simulations of a simplified model.
This paper relaxes the requirement for inputs to be visible in a single step and constructs an auto-correlation normalizing factor to remove the effects of auto-correlation. In addition, Dynamic Watermarking is applied to a high-fidelity vehicle model in carsim and a 1/10 scale autonomous rover to further reinforce the proof of concept for realistic systems. In each case, the vehicle follows a predefined path with time-varying velocity and turning radii. A replay attack, which replays previously recorded measurements, is shown to be detectable using LTV Dynamic Watermarking in a quick and repeatable manner."
---
<p>@article{porter2020deception,<br>
&nbsp;&nbsp;&nbsp;&nbsp;title={Detecting Deception Attacks on Autonomous Vehicles via Linear Time-Varying Dynamic Watermarking},<br>
&nbsp;&nbsp;&nbsp;&nbsp;author={Porter, Matthew and Dey, Sidhartha and Joshi, Arnav and Hespanhol, Pedro and Aswani, Anil and Johnson-Roberson, Matthew and Vasudevan, Ram},<br>
&nbsp;&nbsp;&nbsp;&nbsp;journal={arXiv preprint arXiv:2001.09859},<br>
&nbsp;&nbsp;&nbsp;&nbsp;year={2020}<br>
}
</p>
