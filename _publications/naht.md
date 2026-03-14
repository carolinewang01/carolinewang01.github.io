---
title: "N-Agent Ad Hoc Teamwork"
collection: publications
permalink: /publications/naht
excerpt: 'Existing paradigms for multi-agent coordination are limited by assuming that either all agents are controlled (e.g. the typical cooperative MARL algorithm), or that only a single agent is controlled (ad hoc teamwork / zero shot coordination). We pose the N-Agent Ad Hoc Teamwork (NAHT) problem to the community, to lift these restrictions and pave the path towards more open multi-agent learning paradigms. '
date: 2024-12-15
venue: 'NeurIPS'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2024/hash/cabf611498431ad89a85ace75f790d93-Abstract-Conference.html'
citation: 'Caroline Wang, Arrasy Rahman, Ishan Durugkar, Elad Liebman, Peter Stone. &quot;N-Agent Ad Hoc Teamwork.&quot; <i>NeurIPS 2024</i>.'
slides: '/files/slides/naht_5min_neurips.pdf'
bibtex: |-
  @inproceedings{wang2024naht,
    title = {N-Agent Ad Hoc Teamwork},
    booktitle = {Advances in {{Neural Information Processing Systems}}},
    author = {Wang, Caroline and Rahman, Muhammad Arrasy and Durugkar, Ishan and Liebman, Elad and Stone, Peter},
    year = 2024,
    month = dec,
    volume = {37},
    pages = {111832--111862}
  }
---
Download [paper]({{ "/files/papers/naht_neurips24.pdf" | relative_url }}).

Abstract:
======
Current approaches to learning cooperative multi-agent behaviors assume relatively
restrictive settings. In standard fully cooperative multi-agent reinforcement
learning, the learning algorithm controls all agents in the scenario, while in ad
hoc teamwork, the learning algorithm usually assumes control over only a single
agent in the scenario. However, many cooperative settings in the real world are
much less restrictive. For example, in an autonomous driving scenario, a company
might train its cars with the same learning algorithm, yet once on the road, these
cars must cooperate with cars from another company. Towards expanding the
class of scenarios that cooperative learning methods may optimally address, we
introduce N-agent ad hoc teamwork (NAHT), where a set of autonomous agents
must interact and cooperate with dynamically varying numbers and types of teammates.
This paper formalizes the problem, and proposes the Policy Optimization
with Agent Modelling (POAM) algorithm. POAM is a policy gradient, multi-agent
reinforcement learning approach to the NAHT problem that enables adaptation to
diverse teammate behaviors by learning representations of teammate behaviors.
Empirical evaluation on tasks from the multi-agent particle environment and Star-
Craft II shows that POAM improves cooperative task returns compared to baseline
approaches, and enables out-of-distribution generalization to unseen teammates.