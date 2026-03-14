---
title: "DM$^2$: Distributed multi-agent reinforcement learning via distribution matching"
collection: publications
permalink: /publications/dm2
excerpt: 'We propose DM$^2$, an algorithm that allows a team of agents to perform cooperative tasks by independently imitating corresponding experts agents from a team of experts.'
date: 2023-02-14
venue: 'AAAI'
paperurl: 'https://doi.org/10.1609/aaai.v37i10.26382'
citation: 'Caroline Wang*, Ishan Durugkar*, Elad Liebman*, Peter Stone. &quot;DM$^2$: Distributed Multi-Agent Reinforcement Learning via Distribution Matching.&quot; <i>AAAI 2023</i>.'
slides: '/files/slides/dm2_slides.pdf'
bibtex: |-
  @inproceedings{wang2023dm2,
    title = {{$DM^2$}: Decentralized Multi-Agent Reinforcement Learning via Distribution Matching},
    shorttitle = {{$DM^2$}},
    booktitle = {Proceedings of the Thirty-Seventh AAAI Conference on Artificial Intelligence and Thirty-Fifth Conference on Innovative Applications of Artificial Intelligence and Thirteenth Symposium on Educational Advances in Artificial Intelligence},
    author = {Wang, Caroline and Durugkar, Ishan and Liebman, Elad and Stone, Peter},
    year = 2023,
    month = feb,
    series = {AAAI'23/IAAI'23/EAAI'23},
    volume = {37},
    pages = {11699--11707},
    publisher = {AAAI Press},
    doi = {10.1609/aaai.v37i10.26382},
    isbn = {978-1-57735-880-0}
  }
code: 'https://github.com/carolinewang01/dm2'
abstract: "Current approaches to multi-agent cooperation rely heavily on centralized mechanisms or explicit communication protocols to ensure convergence. This paper studies the problem of distributed multi-agent learning without resorting to explicit coordination schemes. The proposed algorithm (DM$^2$) leverages distribution matching to facilitate independent agents' coordination. Each individual agent matches a target distribution of concurrently sampled trajectories from a joint expert policy. The theoretical analysis shows that under some conditions, if each agent optimizes their individual distribution matching objective, the agents increase a lower bound on the objective of matching the joint expert policy, allowing convergence to the joint expert policy. Further, if the distribution matching objective is aligned with a joint task, a combination of environment reward and distribution matching reward leads to the same equilibrium. Experimental validation on the StarCraft domain shows that combining the reward for distribution matching with the environment reward allows agents to outperform a fully distributed baseline. Additional experiments probe the conditions under which expert demonstrations need to be sampled in order to outperform the fully distributed baseline."
pdfurl: '/files/papers/dm2_aaai23.pdf'
---
