---
title: "ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork"
collection: publications
permalink: /publications/rotate
excerpt: 'We formulate ad hoc teamwork as an open-ended learning process between a regret-maximizing teammate generator and an ad hoc teamwork agent.'
date: 2025-08-05
venue: 'arXiv preprint arXiv:2505.23686'
award: '<a href="https://openreview.net/forum?id=2WW5SXXHn4">Oral spotlight at CoCoMARL 2025</a>'
paperurl: 'https://arxiv.org/abs/2505.23686'
citation: 'Caroline Wang, Arrasy Rahman, Jiaxun Cui, Yoonchang Sung, Peter Stone. &quot;ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork.&quot; <i>arXiv preprint arXiv:2505.23686</i>.'
slides: '/files/slides/rotate_slides.pdf'
bibtex: |-
  @misc{wang2025rotate,
    title={ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork},
    author={Wang, Caroline and Rahman, Arrasy and Cui, Jiaxun and Sung, Yoonchang and Stone, Peter},
    year = 2025,
    month = may,
    number = {arXiv:2505.23686},
    eprint = {2505.23686},
    primaryclass = {cs},
    publisher = {arXiv},
    doi = {10.48550/arXiv.2505.23686},
    archiveprefix = {arXiv}
  }
code: 'https://github.com/carolinewang01/rotate'
abstract: "Learning to collaborate with previously unseen partners is a fundamental generalization challenge in multi-agent learning, known as Ad Hoc Teamwork (AHT). Existing AHT approaches often adopt a two-stage pipeline, where first, a fixed population of teammates is generated with the idea that they should be representative of the teammates that will be seen at deployment time, and second, an AHT agent is trained to collaborate well with agents in the population. To date, the research community has focused on designing separate algorithms for each stage. This separation has led to algorithms that generate teammates with limited coverage of possible behaviors, and that ignore whether the generated teammates are easy to learn from for the AHT agent. Furthermore, algorithms for training AHT agents typically treat the set of training teammates as static, thus attempting to generalize to previously unseen partner agents without assuming any control over the set of training teammates. This paper presents a unified framework for AHT by reformulating the problem as an open-ended learning process between an AHT agent and an adversarial teammate generator. We introduce ROTATE, a regret-driven, open-ended training algorithm that alternates between improving the AHT agent and generating teammates that probe its deficiencies. Experiments across diverse two-player environments demonstrate that ROTATE significantly outperforms baselines at generalizing to an unseen set of evaluation teammates, thus establishing a new standard for robust and generalizable teamwork."
pdfurl: 'https://arxiv.org/pdf/2505.23686.pdf'
---
