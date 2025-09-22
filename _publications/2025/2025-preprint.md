---
title:          "Path-Tracking Hybrid A* and Hierarchical MPC Framework for Autonomous Agricultural Vehicles"
date:           2025-05-17 00:01:00 +0800
year_label:     Preprint
selected:       false
pub:            "arxiv"
pub_date:       "2024"
abstract: >-
  We propose a Path-Tracking Hybrid A* planner
  coupled with a hierarchical Model Predictive Control (MPC)
  framework for path smoothing in agricultural vehicles. The goal
  is to minimize deviation from reference paths during cross-furrow
  operations, thereby optimizing operational efficiency, preventing
  crop and soil damage, while also enforcing curvature constraints
  and ensuring full-body collision avoidance. Our contributions
  are threefold: (1) We develop the Path-Tracking Hybrid A*
  algorithm to generate smooth trajectories that closely adhere to
  the reference trajectory, respect strict curvature constraints, and
  satisfy full-body collision avoidance. The adherence is achieved by
  designing novel cost and heuristic functions to minimize tracking
  errors under nonholonomic constraints. (2) We introduce an
  online replanning strategy as an extension that enables real
  time avoidance of unforeseen obstacles, while leveraging pruning
  techniques to enhance computational efficiency. (3) We design
  a hierarchical MPC framework that ensures tight path adherence and real-time satisfaction of vehicle constraints, including
  nonholonomic dynamics and full-body collision avoidance. By
  using linearized MPC to warm-start the nonlinear solver, the
  framework improves the convergence of nonlinear optimization
  with minimal loss in accuracy. Simulations on real-world farm
  datasets demonstrate superior performance compared to baseline
  methods in safety, path adherence, computation speed, and real
  time obstacle avoidance.

cover:          /assets/images/covers/cover3.jpg
authors:
  - Mingke Lu
  - Han Gao
  - Haijie Dai
  - Qianli Lei
  - Chang Liu
links:
  Paper: https://arxiv.org/abs/2411.14086
---