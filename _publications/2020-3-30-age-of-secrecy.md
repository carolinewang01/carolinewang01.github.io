---
title: "The age of secrecy and unfairness in recidivism prediction"
collection: publications
permalink: /publication/2020-03-30-age-of-secrecy
<!-- excerpt: 'Looking deeper into the COMPAS model (a black-box recidivism prediction model used widely in America's justice systems).' -->
excerpt: 'testtesttesttesttest'
date: 2020-03-31
venue: 'Harvard Data Science Review'
paperurl: 'https://hdsr.mitpress.mit.edu/pub/7z10o269/release/3'
citation: 'Cynthia Rudin, Caroline Wang, and Beau Coker. (2020). &quot;The age of secrecy and unfairness in recidivism prediction.&quot; <i>HDSR</i>. 2(1).'
---

[Download paper here](http://carolinewang01.github.io/files/age_of_secrecy_hdsr_final.pdf)

Abstract:
======
In our current society, secret algorithms make important decisions about individuals. There has been substantial discussion about whether these algorithms are unfair to groups of individuals. While noble, this pursuit is complex and ultimately stagnating because there is no clear definition of fairness and competing definitions are largely incompatible. We argue that the focus on the question of fairness is misplaced, as these algorithms fail to meet a more important and yet readily obtainable goal: transparency. As a result, creators of secret algorithms can provide incomplete or misleading descriptions about how their models work, and various other kinds of errors can easily go unnoticed. By trying to partially reconstruct the COMPAS model—a recidivism risk-scoring model used throughout the criminal justice system—we show that it does not seem to depend linearly on the defendant’s age, despite statements to the contrary by the model’s creator. This observation has not been made before despite many recently published papers on COMPAS. Furthermore, by subtracting from COMPAS its (hypothesized) nonlinear age component, we show that COMPAS does not necessarily depend on race other than through age and criminal history. This contradicts ProPublica’s analysis, which made assumptions about age that disagree with what we observe in the data. In other words, faulty assumptions about a proprietary model led to faulty conclusions that went unchecked until now. Were the model transparent in the first place, this likely would not have occurred. We demonstrate other issues with definitions of fairness and lack of transparency in the context of COMPAS, including that a simple model based entirely on a defendant’s age is as ‘unfair’ as COMPAS by ProPublica’s chosen definition. We find that there are many defendants with low risk scores but long criminal histories, suggesting that data inconsistencies occur frequently in criminal justice databases. We argue that transparency satisfies a different notion of procedural fairness by providing both the defendants and the public with the opportunity to scrutinize the methodology and calculations behind risk scores for recidivism.