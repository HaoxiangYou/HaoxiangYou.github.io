---
layout: page
title: End-to-end implementation for UAV system
description: Comprehensive development and integration of planning, control, and VIO for UAVs
img: assets/img/uav/hardware_maze.gif
importance: 1
category: work
---

In this project, I develop a UAV system from scratch. The system includes a geometry-inspired PID controller, a Dijkstra path search algorithm, minimal snap trajectory optimization, and a visual-inertial odometry module for state estimation.

<h3>Simulation results</h3>
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/uav/sim_maze.gif" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/uav/sim_over_under.gif" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<h3>Real-world results</h3>
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/uav/hardware_maze.gif" title="Hardware: Maze Flight" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.html path="assets/img/uav/hardware_square.gif" title="Hardware: Square Path Flight" class="img-fluid rounded z-depth-1" %}
  </div>
</div>