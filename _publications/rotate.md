---
title: "ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork"
collection: publications
permalink: /publications/rotate
excerpt: 'We formulate ad hoc teamwork as an open-ended learning process between a regret-maximizing teammate generator and an ad hoc teamwork agent.'
date: 2026-09-25
venue: 'NeurIPS 2026'
venue_short: 'NeurIPS'
timeline_text: "ROTATE accepted to NeurIPS as a spotlight. Instead of training against a fixed population of teammates, we alternate between improving the ad hoc teamwork agent and generating new teammates that probe its weaknesses."
award: 'Spotlight (top 2%) at NeurIPS 2026; oral spotlight at CoCoMARL 2025'
paperurl: 'https://openreview.net/forum?id=h76k7u9S4o'
arxiv: 'https://arxiv.org/abs/2505.23686'
# pdfurl: ''
citation: 'Caroline Wang, Muhammad Arrasy Rahman, Benjamin Nativi, Johnny Liu, Jiaxun Cui, Yoonchang Sung, Peter Stone. &quot;ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork.&quot; <i>NeurIPS 2026</i> (Spotlight).'
slides: '/files/slides/rotate_slides.pdf'
bibtex: |-
  @inproceedings{wang2026rotate,
    title = {{{ROTATE}}: Regret-driven Open-ended Training for Ad Hoc Teamwork},
    booktitle = {Advances in {{Neural Information Processing Systems}}},
    author = {Wang, Caroline and Rahman, Muhammad Arrasy and Nativi, Benjamin and Liu, Johnny and Cui, Jiaxun and Sung, Yoonchang and Stone, Peter},
    year = 2026
  }
code: 'https://github.com/carolinewang01/rotate'
abstract: "Learning to collaborate with previously unseen partners is a fundamental generalization challenge in multi-agent learning, known as Ad Hoc Teamwork (AHT). Existing AHT approaches often adopt a two-stage pipeline, where first, a fixed population of teammates is generated with the idea that they should be representative of the teammates that will be seen at deployment time, and second, an AHT agent is trained to collaborate well with agents in the population. To date, the research community has focused on designing separate algorithms for each stage. This separation has led to algorithms that generate teammates with limited coverage of possible behaviors, and that ignore whether the generated teammates are easy to learn from for the AHT agent. Furthermore, algorithms for training AHT agents typically treat the set of training teammates as static, thus attempting to generalize to previously unseen partner agents without assuming any control over the set of training teammates. This paper presents a unified framework for AHT by reformulating the problem as an open-ended learning process between an AHT agent and an adversarial teammate generator. We introduce ROTATE, a regret-driven, open-ended training algorithm that alternates between improving the AHT agent and generating teammates that probe its deficiencies. Experiments across diverse two-player environments demonstrate that ROTATE significantly outperforms baselines at generalizing to an unseen set of evaluation teammates, thus establishing a new standard for robust and generalizable teamwork."
---
