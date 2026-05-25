---
title: "<span style='font-variant: small-caps'>AcroRL</span>: Learning Aggressive Quadrotor Inversion using Bidirectional Thrust"
collection: publications
category: conferences
permalink: /publication/acrorl
date: 2026-05-22
venue: 'arXiv preprint arXiv:submit/7620198'
authors: 'Gabriel Rodriguez, Henri Sayag, Abhishek Rathod, John Stecklein, Siddharth Saha, Christopher Barngrover, Wennie Tabib'
paperurl: 'https://arxiv.org/abs/submit/7620198'
codeurl: 'https://github.com/rislab/acrorl'
videourl: 'https://youtu.be/7pPTKY5KKtU'
tldr: 'A reinforcement learning framework that trains separate policies for compact, position-constrained quadrotor inversions using bidirectional thrust — reducing position RMSE by 32% and settling time by 57% over the best optimization-based baseline, with successful zero-shot hardware transfer.'
---

## Abstract

Bidirectional thrust grants quadrotors a second equilibrium condition
and increased control authority, expanding the envelope of possible aggressive
maneuvers and enabling inverted flight, perching, and sensing. Prior geometric
control approaches extend differential flatness through Hopf fibration-based
attitude representations to support bidirectional thrust, but struggle with
actuator saturation and motor reversal delay during inversions, requiring
heuristic thrust posture scheduling and waypoint tuning. We propose a
learning-based framework that modulates a constant reference trajectory to
perform compact, positionconstrained quadrotor inversions while remaining
compatible with traditional trajectory generation and tracking across flight
regimes. Separate policies are trained via reinforcement learning for
nominal-to-inverted and inverted-to-nominal transitions. In JAX-based
simulation, the proposed method achieves the lowest position deviation and
settling time across all evaluated baselines, reducing position root mean square
error (RMSE) by 32% and settling time by 57% relative to the strongest
optimization-based baseline. Hardware experiments demonstrate successful
inversion across multiple yaw configurations with position RMSE below 0.35 m,
and compatibility with downstream trajectory generation and control through
circular flight in both regimes. Additionally, we provide an open-source
implementation of the proposed framework.