---
title: "A Soft Robotic System Automatically Learns Precise Agile Motions Without Model Information"
collection: publications
category: conferences
permalink: /publication/iros
date: 2024-08-01
venue: '2024 IEEE/RSJ international conference on intelligent robots and systems'
paperurl: 'https://doi.org/10.48550/arXiv.2408.03754'
---

This work demonstrates that the Automatic Neural ODE Control (ANODEC) method enables practical and efficient control of pneumatic soft robots (SRs) with hysteresis effects, achieving agile, non-repetitive reference tracking from only 30 seconds of input-output data and outperforming manually tuned PID controllers, thereby advancing the feasibility of data-driven, low-expertise SR control.

Many application domains, e.g., in medicine and manufacturing, can greatly benefit from pneumatic Soft Robots (SRs).
However, the accurate control of SRs has remained a significant challenge to date, mainly due to their nonlinear dynamics and viscoelastic material properties.
Conventional control design methods often rely on either complex system modeling or time-intensive manual tuning, both of which require significant amounts of human expertise and thus limit their practicality.
In recent works, the data-driven method, Automatic Neural ODE Control (ANODEC) has been successfully used to -- fully automatically and utilizing only input-output data -- design controllers for various nonlinear systems \emph{in silico}, and without requiring prior model knowledge or extensive manual tuning.
In this work, we successfully apply ANODEC to automatically learn to perform agile, non-repetitive reference tracking motion tasks in a real-world SR and within a finite time horizon.
To the best of the authors' knowledge, ANODEC achieves, for the first time, performant control of a SR with hysteresis effects from only 30 second of input-output data and without any prior model knowledge.
We show that for multiple, qualitatively different and even out-of-training-distribution reference signals, a single feedback controller designed by ANODEC outperforms a manually tuned PID baseline consistently.
Overall, this contribution not only further strengthens the validity of ANODEC, but it marks an important step towards more practical, easy-to-use SRs that can automatically learn to perform agile motions from minimal experimental interaction time.