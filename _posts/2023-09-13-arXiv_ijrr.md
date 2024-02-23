---
layout: post
type: paper
title: "MOB-Net: Limb-modularized Uncertainty Torque Learning of Humanoids for Sensorless External Torque Estimation"
author: "<strong>Daegyu Lim</strong>, Myeong-Ju Kim, Junhyeok Cha, Jaeheung Park"
journal: <strong>arXiv (submitted to IJRR)</strong>
tags: [documentation,journal,ijrr]
image: IJRR2023_thumb.png
pdf: IJRR2023_arXiv_version.pdf
---
Momentum observer (MOB) can estimate external joint torque without requiring additional sensors, such as force/torque or joint torque sensors. However, the estimation performance of MOB deteriorates due to the model uncertainty which encompasses the modeling errors and the joint friction. Moreover, the estimation error is significant when MOB is applied to the high-dimensional floating-base humanoids, which prevents the estimated external joint torque from being used for force control or collision detection in the real humanoid robot. In this paper, the pure external joint torque estimation method named MOB-Net is proposed for humanoids. MOB-Net learns the model uncertainty torque and calibrates the estimated signal of MOB. The external joint torque can be estimated in the generalized coordinate including whole-body joints and the virtual joints of the floating-base robot only with internal sensors (an IMU on the pelvis and encoders in the joints). Our method substantially reduces the estimation errors of MOB, and the robust performance of MOB-Net for the unseen data is validated through extensive simulations, real robot experiments, and ablation studies. Finally, various collision handling scenarios are presented using the estimated external joint torque from MOB-Net: contact wrench feedback control for locomotion, collision detection, and collision reaction for safety.

- Extension 1
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/Z8Psm5RKFxk/0.jpg)](http://www.youtube.com/watch?v=Z8Psm5RKFxk)

- Extension 2
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/ZpnMEjvGsaQ/0.jpg)](http://www.youtube.com/watch?v=ZpnMEjvGsaQ)
