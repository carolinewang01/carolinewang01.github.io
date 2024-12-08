---
title: "Building Minimal and Reusable Causal State Abstractions for Reinforcement Learning"
collection: publications
permalink: /publications/dshape
excerpt: 'TLDR: We introduce Causal Bisimulation Learning (CBM), a method that learns the causal relationships in the dynamics and reward functions for each task to derive a minimal,  task-specific abstraction.'
date: 2024-02-14
venue: 'AAAI'
paperurl: ''
citation: 'Zizhao Wang*, Caroline Wang*, Xuesu Xiao, Yuke Zhu, Peter Stone (2024). &quot;Building Minimal and Reusable Causal State Abstractions for Reinforcement Learning&quot; <i>AAAI 2024</i>.'
---
<!-- [Download paper here](http://carolinewang01.github.io/files/cbm_aaai24.pdf) -->

[Download paper here]({{"/files/cbm_aaai24.pdf" | relative_url}})

Abstract:
======
Two desiderata of reinforcement learning (RL) algorithms are the ability to learn from relatively little experience and the ability to learn policies that generalize to a rane of problem specifications. In factored state spaces, one approch towards achieving both goals is to learn state abstractions, which only keep the necessary variables for learning the tasks at hand. This paper introduces Causal Bisimulation Modeling (CBM), a method that learns the causal relationships in the dynamics and reward functions for each task to derive a minimal, task-specific abstraction. CBM leverages and improves implicit modeling to train a high-fidelity causal dynamics model that can be reused for all tasks in the same environment. Empirical validation on manipulation environments and Deepmind Control Suite reveals that CBM’s learned implicit dynamics models identify the underlying causal relationships and state abstractions more accurately than explicit ones. Furthermore, the derived state abstractions allow a task learner to achieve near-oracle levels of sample efficiency and outperform baselines on all tasks.