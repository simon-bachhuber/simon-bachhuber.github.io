---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a System Engineer at [KEEQuant](https://www.keequant.com/), working on quantum cryptography and quantum key distribution systems. Before, i was a researcher at LUH (University of Hanover) and FAU (University of Erlangen), developing plug-and-play, ML-based methods for state estimation and motion control. I want to achieve solutions that eliminate the need for expert knowledge to identify, select, and configure suitable methods; solutions that are less restrictive and simultaneously more accessible!

![gait-example](https://simon-bachhuber.github.io/files/gait_demo.gif)
<div style="text-align: center; margin-top: -10px;">
<p><em>Animation: Gait motion tracking using inertial sensors (visualised with orange boxes). The predicted pose (blue) accurately tracks the pose of the system.</em></p>
</div>

<div style="display: flex; font-size: 1em;">
<div style="flex: 1; padding: 10px;">
    For example, Inertial Motion Tracking (IMT) uses wearable inertial sensors to estimate the motion of humans and robots. Unfortunately, current methods require careful selection and precise calibration; effectively, IMT users must be IMT experts!<br><br>
    <a href="https://openreview.net/forum?id=h2C3rkn0zR" target="_blank">RING</a> is a single neural network that achieves IMT for a broad range of systems, without relying on magnetometers and without calibration efforts. RING receives all available raw IMU data that are attached to the system and predicts the pose, i.e., the orientations of all bodies in the system.
</div>
<div style="flex: 1; padding: 10px;">
<div style="text-align: center; margin-bottom: 0px; margin-top: 0px;">
    <img src="https://simon-bachhuber.github.io/files/IMG_6607_nobg.png" alt="Image not found" width="150"/>
    <p><em>Figure: Motion tracking with wearable IMUs.</em></p>
</div>
</div>
</div>

![gait-example](https://simon-bachhuber.github.io/files/imt_demo.gif)
<div style="text-align: center; margin-top: -10px;">
<p><em>Animation: Plug-and-play method tracking the knee joint (left) and shoulder joint (right) without magnetometer, calibration, or configuration.</em></p>
</div>

<div style="text-align: center;">
  <video style="max-width: 100%; height: auto;" controls>
    <source src="https://simon-bachhuber.github.io/files/sidebyside_with_labels.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
    <p><em>Video: RING's ability, before and after training, to predict the pose (visualized in blue) of kinematic chains from inertial data (IMUs are orange).</em></p>
</div>

---
My research also focuses on developing plug-and-play motion control methods that enable systems to autonomously learn to perform agile motions.

<div style="text-align: center; margin-top: 0px;">
  <video style="max-width: 100%; height: auto;" controls>
    <source src="https://simon-bachhuber.github.io/files/soft_robot_control.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
    <p><em>Video: ANODEC has enabled agile motion control of a soft pnemuatic actuator from only 30 seconds of input-output data and without any model information.</em></p>
</div>

---
If these topics interest you, please feel free to reach out to me :blush:!