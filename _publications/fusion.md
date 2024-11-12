---
title: "RNN-based observability analysis for magnetometer-free sparse inertial motion tracking"
collection: publications
category: conferences
permalink: /publication/fusion
date: 2022-08-09
venue: '2022 25th International Conference on Information Fusion'
paperurl: 'https://doi.org/10.23919/FUSION49751.2022.9841375'
---

We present an RNN-based method for assessing the observability of relative pose in sparse, magnetometer-free inertial motion tracking (IMT) systems, demonstrating that observability and tracking accuracy depend on the kinematic structure, thus advancing reliable and cost-effective IMT solutions for complex kinematic chains.

Inertial measurement units are widely used for motion tracking of kinematic chains in numerous applications. 
While magnetometer-free sensor fusion enables reliably high accuracy in indoor environments and near magnetic disturbances, the use of sparse sensor setups would yield additional advantages in cost, effort, and usability. However, it is unclear which sparse sensor setups can be used to track which motions of which kinematic chains, since observability of the underlying nonlinear dynamics is barely understood to date. 
We propose a method that utilizes recurrent neural networks (RNNs) and automatically generated training data to assess the observability of the relative pose of kinematic chains in sparse inertial motion tracking (IMT) systems.
We apply this method to a range of double-hinge-joint systems that perform fully-exciting random motion. 
Results show how the degree of observability depends on the kinematic structure and that RNN-based observers can achieve small tracking errors in a large range of sparse and magnetometer-free setups.
The proposed methods enable systematic assessment of observability properties in complex nonlinear dynamics and represent a key step toward enabling reliably accurate and non-restrictive IMT solutions.