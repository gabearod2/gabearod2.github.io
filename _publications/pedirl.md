---
title: "Affordance-Based Hierarchical Reinforcement Learning for Quadruped Pedipulation"
collection: publications
category: preprints
permalink: /publication/pedirl
date: 2026-06-05
venue: 'preprint'
authors: '<a href="https://www.linkedin.com/in/gulsum-tuba-cibuk/">Tuba Girgin</a>, <a href="https://www.linkedin.com/in/jose-castelblanco-002640195/">Jose Castelblanco</a>, Gabriel Rodriguez, <a href="https://www.linkedin.com/in/girgin-emre/">Emre Girgin</a>, <a href="https://www.linkedin.com/in/kcagri/">Cagri Kilic</a>'
paperurl: 'https://arxiv.org/abs/2606.07506'
tldr: 'A hierarchical reinforcement learning framework enables quadruped robots to autonomously choose where to stand and how to interact with objects, eliminating the need for hand-designed manipulation trajectories.'
---

## Abstract

The object manipulation capabilities of quadruped robots is an open research
challenge. While previous studies have focused on low-level policy learning,
task execution still relies on expert-designed high-level trajectories.
Autonomous selection of both an affordable interaction point on the target
object and an affordable robot base pose removes the need for pre-designed
trajectories. This study proposes a three-level hierarchical reinforcement
learning (RL) framework that utilizes pose affordances to guide the navigation
policy, while the navigation policy drives the locomotion policy. In addition,
the pedipulation policy is guided by interaction-point affordances, enabling
object-centric pose alignment of the quadruped robot and effective end-effector
manipulation planning. We train the proposed framework in the IsaacSim ecosystem
and evaluate it in both simulation and real-world settings. We investigate the
effectiveness of pose affordance across multiple scenarios in simulation while
various object interaction tasks are validated on real-world setting forming an
object-interaction dataset. The results show that the proposed framework can
autonomously identify candidate poses based on their affordance and successfully
execute object manipulation tasks in the real world without human guidance. 