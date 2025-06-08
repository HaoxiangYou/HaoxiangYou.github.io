---
layout: page
title: MPC-RL
description: Developing a novel method taht combining RL with MPC for improved sample efficiency
img: assets/img/mpc_ppo/PPO_MPC_demos.gif
importance: 3
category: work
---

In this project, we developed a novel approach that integrates Proximal Policy Optimization (PPO) with a parameterized Model Predictive Control (MPC) policy. By using MPC as the actor in the reinforcement learning loop, our method improves sample efficiency.

<h3>Learning Curves</h3>
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.html path="assets/img/mpc_ppo/Data_efficiency.png" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<h3>Animation</h3>
<div class="row justify-content-sm-center">
  <div class="col-sm-10 mt-3 mt-md-0">
    {% include figure.html path="assets/img/mpc_ppo/PPO_MPC_demos.gif" class="img-fluid rounded z-depth-1" %}
  </div>
</div>