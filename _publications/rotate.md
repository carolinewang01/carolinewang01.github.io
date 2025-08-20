---
title: "ROTATE: Regret-driven Open-ended Training for Ad Hoc Teamwork"
collection: publications
permalink: /publications/rotate
excerpt: 'We formulate ad hoc teamwork as an open-ended learning process between a regret-maximizing teammate generator and an ad hoc teamwork agent.'
date: 2025-08-05
venue: 'CoCoMARL Workshop at RLC'
award: 'Oral spotlight'
paperurl: 'https://openreview.net/forum?id=2WW5SXXHn4'
citation: 'Caroline Wang, Arrasy Rahman, Jiaxun Cui, Yoonchang Sung, Peter Stone. &quot;ROTATE: Regret-Driven Open-ended Training for Ad Hoc Teamwork.&quot; <i>CoCoMARL Workshop at RLC 2025</i>.'
---
Download [paper]({{ "/files/papers/rotate_cocomarl.pdf" | relative_url }}).

Abstract:
======
Developing AI agents capable of collaborating with previously unseen partners is a fundamental generalization challenge in multi-agent learning, known as Ad Hoc Teamwork (AHT). Existing AHT approaches often adopt a two-stage pipeline, where first, a fixed population of teammates is generated with the idea that they should be representative of the teammates that will be seen at deployment time, and second, an AHT agent is trained to collaborate well with agents in the population. To date, the research community has focused on designing separate algorithms for each stage. This separation has led to algorithms that generate teammates with limited coverage of possible behaviors, and that ignore whether the generated teammates are easy to learn from for the AHT agent. Furthermore, algorithms for training AHT agents typically treat the set of training teammates as static, thus attempting to generalize to previously unseen partner agents without assuming any control over the distribution of training teammates. This paper presents a unified framework for AHT by reformulating the problem as an open-ended learning process between an ad hoc agent and an adversarial teammate generator. We introduce ROTATE, a regret-driven, open-ended training algorithm that alternates between improving the AHT agent and generating teammates that probe its deficiencies. Extensive experiments across diverse AHT environments demonstrate that ROTATE significantly outperforms baselines at generalizing to an unseen set of evaluation teammates, thus establishing a new standard for robust and generalizable teamwork.