---
title: "Plug-and-Play Sparse Inertial Motion Tracking With Sim-to-Real Transfer"
collection: publications
category: manuscripts
permalink: /publication/sensors
date: 2023-08-21
venue: 'IEEE Sensors Letters'
paperurl: 'https://doi.org/10.1109/LSENS.2023.3307122'
---

We propose a magnetometer-free, sparse IMU-based inertial motion tracking (IMT) method using a recurrent neural network observer (RNNo) trained on simulated data, achieving plug-and-play generalizability and robust tracking with a <4 degree error in complex kinematic chains.

Inertial measurement units (IMUs) are used for inertial motion tracking (IMT) in a growing number of applications as sensor fusion methods are being advanced in three directions: Magnetometer-free IMT methods that eliminate the effect of magnetic disturbances; sparse IMT approaches that lead to reduced setup complexity; automatic self-calibration of sensor-to-segment positions or orientations. We propose an approach that combines all three achievements and, for the first time, enables plug-and-play, magnetometer-free, and sparse IMT. This is accomplished by training a recurrent neural network-based observer (RNNo) on just-in-time generated simulated motion data of kinematic chains. We demonstrate that domain-specific training data augmentations lead to a trained RNNo that zero-shot generalizes to previously unseen experimental data and thus overcomes the sim-to-real gap. The trained RNNo achieves a tracking error of <4 degrees when estimating the relative pose of a three-segment kinematic chain with two hinge joints. The proposed method offers a novel simulation-data-driven approach for solving complex sparse sensing problems, whilst assuring robust and plug-and-play generalizability to experimental data.