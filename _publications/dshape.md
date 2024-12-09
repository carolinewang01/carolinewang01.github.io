---
title: "D-Shape: Demonstration Shaped Reinforcement Learning"
collection: publications
permalink: /publications/dshape
excerpt: 'TLDR: We propose D-Shape, an RL+IL algorithm that allows learning from suboptimal demonstrations while retaining the ability to find the optimal policy with respect to the task reward.'
date: 2023-06-02
venue: 'AAMAS'
paperurl: ''
citation: 'Caroline Wang, Garrett Warnell, Peter Stone (2023). &quot;D-Shape: Demonstration Shaped Reinforcement Learning.&quot; <i>AAMAS 2023</i>.'
---
Download [paper]({{"/files/papers/dshape_aamas23.pdf" | relative_url}}), [slides]({{ "/files/slides/dshape_slides_aamas23.pdf" | relative_url }}).

Abstract:
======
While combining imitation learning (IL) and reinforcement learning (RL) is a promising way to address poor sample efficiency in autonomous behavior acquisition, methods that do so typically assume that the requisite behavior demonstrations are provided by
an expert that behaves optimally with respect to a task reward. If, however, suboptimal demonstrations are provided, a fundamental challenge appears in that the demonstration-matching objective of IL conflicts with the return-maximization objective of RL. This paper introduces D-Shape, a new method for combining IL and RL
that uses ideas from reward shaping and goal-conditioned RL to resolve the above conflict. D-Shape allows learning from suboptimal demonstrations while retaining the ability to find the optimal policy with respect to the task reward. We experimentally validate D-Shape in sparse-reward gridworld domains, showing that it both improves over RL in terms of sample efficiency and converges consistently to the optimal policy in the presence of suboptimal demonstrations.