---
title: "DM$^2$: Distributed multi-agent reinforcement learning via distribution matching"
collection: publications
permalink: /publication/dm2
excerpt: 'DM$^2$ allows a team of agents to perform cooperative tasks by independently imitating corresponding experts agents from a team of experts.'
date: 2022-06-01
venue: 'Preprint'
paperurl: ''
citation: 'Caroline Wang, Ishan Durugkar, Elad Liebman, Peter Stone (2022). &quot;DM$^2$: Distributed multi-agent reinforcement learning via distribution matching&quot; <i>arXiv preprint</i>.'
---

[Download paper here](http://carolinewang01.github.io/files/dm2_full.pdf)

Abstract:
======
Current approaches to multi-agent cooperation rely heavily on centralized mechanisms or explicit communication protocols to ensure convergence. This paper studies the problem of distributed multi-agent learning without resorting to explicit coordination schemes. The proposed algorithm (DM$^2$) leverages distribution matching to facilitate independent agents' coordination. Each individual agent matches a target distribution of concurrently sampled trajectories from a joint expert policy. The theoretical analysis shows that under some conditions, if each agent optimizes their individual distribution matching objective, the agents increase a lower bound on the objective of matching the joint expert policy, allowing convergence to the joint expert policy. Further, if the distribution matching objective is aligned with a joint task, a combination of environment reward and distribution matching reward leads to the same equilibrium. Experimental validation on the StarCraft domain shows that combining the reward for distribution matching with the environment reward allows agents to outperform a fully distributed baseline. Additional experiments probe the conditions under which expert demonstrations need to be sampled in order to outperform the fully distributed baseline.
