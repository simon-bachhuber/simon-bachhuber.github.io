---
title: "Recurrent Inertial Graph-Based Estimator (RING): A Single Pluripotent Inertial Motion Tracking Solution"
collection: publications
category: manuscripts
permalink: /publication/ring
date: 2024-10-01
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/forum?id=h2C3rkn0zR'
---

This paper presents RING, a novel machine learning-based, plug-and-play method for Inertial Motion Tracking (IMT) that eliminates the need for expert knowledge by employing a decentralized network of recurrent neural networks, enabling broad applicability, zero-shot generalization from simulation to experimental data, and high performance across diverse IMT challenges, including magnetometer-free and sparse sensing setups.

This paper introduces a novel ML-based method for Inertial Motion Tracking (IMT) that fundamentally changes the way this technology is used.
The proposed method, named RING\footnote{one to track them all} (Recurrent Inertial Graph-Based Estimator), provides a pluripotent, problem-unspecific plug-and-play IMT solution that, in contrast to conventional IMT solutions, eliminates the need for expert knowledge to identify, select, and parameterize the appropriate method.
RING's pluripotency is enabled by a novel online-capable neural network architecture that uses a decentralized network of message-passing, parameter-sharing recurrent neural networks, which map local IMU measurements and nearest-neighbour messages to local orientations.
This architecture enables RING to address a broad range of IMT problems that vary greatly in aspects such as the number of attached sensors, or the number of segments in the kinematic chain, and even generalize to previously unsolved IMT problems, including the challenging combination of magnetometer-free and sparse sensing with unknown sensor-to-segment parameters.
Remarkably, RING is trained solely on simulated data, yet evaluated on experimental data, which indicates its exceptional ability to zero-shot generalize from simulation to experiment, while outperforming several state-of-the-art problem-specific solutions.
For example, RING can, for the first time, accurately track a four-segment kinematic chain (which requires estimating four orientations) using only two magnetometer-free inertial measurement units. %with a mean orientation error of 6.78 +/- 1.41 degrees.
This research not only makes IMT more powerful and less restrictive in established domains ranging from biomechanics to autonomous systems, but also opens its application to new users and fields previously untapped by motion tracking technology.