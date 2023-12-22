---
abstract: The electrocardiogram (ECG) remains the cornerstone of diagnosis in cardiology
  where, pathologies uniquely impact its appearance, permitting the identification
  of underlying electrical or structural abnormalities. Notably, multiple deep learning
  approaches have demonstrated that disease prediction could be performed with high
  accuracy using ECG waveforms. However, this signal-rich modality has also demonstrated
  the potential to be predictive of a patient’s private attributes such as biological
  sex and age. More importantly, recent research has demonstrated that many medical
  data modalities could allow patient re-identification with only the modality of
  interest despite anonymization through current paradigms, raising important privacy
  concerns. In this paper, we propose a novel approach to anonymize the ECG waveforms
  themselves while maximizing the privacy-utility trade-off. We describe PrivECG1,
  a generative adversarial network (GAN) framework capable of privatizing 12-lead
  ECGs while conserving their disease-descriptive features. PrivECG significantly
  decreases patient validation performances by targeting sex-linked features. Our
  approach reduces sex prediction accuracy from 0.876 to near-random 0.529, by permitting
  greater variability of the ECG’s R-wave morphology, as well as bringing the equal
  error rate (EER) from 0.098 to 0.251 on individual validation tasks. Moreover, the
  regenerated ECGs maintain a majority of their disease-predicting potential, with
  an F1 score of 0.885 from the baseline’s 0.931 on a multilabel disease prediction
  task. We further demonstrate that reintroducing sex-linked information downstream
  in the network allows recuperating performances with an F1 score of 0.893 proving
  our loss of performance is due to the privatization of the sex-linked features,
  as well as serves as a disambiguation tool to evaluate the impact of sex information
  on prediction performances. Our results suggest that our approach could allow improved
  anonymization of a large ECG database in minutes without strongly impacting downstream
  clinically-relevant tasks in a task-independent manner.
booktitle: Proceedings of the 8th Machine Learning for Healthcare Conference
title: 'PrivECG: generating private ECG for end-to-end anonymization'
volume: '219'
year: '2023'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: nolin-lapalme23a
month: 0
tex_title: 'PrivECG: generating private ECG for end-to-end anonymization'
firstpage: 509
lastpage: 528
page: 509-528
order: 509
cycles: false
bibtex_author: Nolin-Lapalme, Alexis and Avram, Robert and Julie, Hussin
author:
- given: Alexis
  family: Nolin-Lapalme
- given: Robert
  family: Avram
- given: Hussin
  family: Julie
date: 2023-12-22
address:
container-title: Proceedings of the 8th Machine Learning for Healthcare Conference
genre: inproceedings
issued:
  date-parts:
  - 2023
  - 12
  - 22
pdf: https://proceedings.mlr.press/v219/nolin-lapalme23a/nolin-lapalme23a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
