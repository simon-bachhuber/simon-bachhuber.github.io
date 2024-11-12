---
title: "Neural ODEs for Data-Driven Automatic Self-Design of Finite-Time Output Feedback Control for Unknown Nonlinear Dynamics"
collection: publications
category: manuscripts
permalink: /publication/lcss
date: 2023-07-07
venue: 'IEEE Control System Letters'
paperurl: 'https://doi.org/10.1109/LCSYS.2023.3293277'
---

ANODEC is a data-efficient, learning-based method for automatically designing output feedback controllers for finite-time reference tracking in unknown nonlinear systems, achieving superior accuracy over baselines across diverse reference signals and system dynamics.

Many application fields, e.g., robotic surgery, autonomous piloting, and wearable robotics greatly benefit from advances in robotics and automation. A common task is to control an unknown nonlinear system such that its output tracks a desired reference signal for a finite duration of time. A learning control method that automatically and efficiently designs output feedback controllers for this task would greatly boost practicality over time-consuming and labour-intensive manual system identification and controller design methods. In this contribution we propose Automatic Neural Ordinary Differential Equation Control (ANODEC), a data-efficient automatic design of output feedback controllers for finite-time reference tracking in systems with unknown nonlinear dynamics. 
In a two-step approach, ANODEC first identifies a neural ODE model of the system dynamics from input-output data of the system dynamics and then exploits this data-driven model to learn a neural ODE feedback controller, while requiring no knowledge of the actual system state or its dimensionality. 
In-silico validation shows that ANODEC is able to ---automatically--- design competitive controllers that outperform two controller baselines, and achieves an on average ~30% or 17% lower median RMSE.
This is demonstrated in four different nonlinear systems using multiple, qualitatively different and even out-of-training-distribution reference signals.