---
title: Balancing the Stability-Plasticity Dilemma with Online Stability Tuning for Continual Learning
date: 2022-07-18
authors:
  - Anton Lee
  - Heitor Murilo Gomes
  - Yaqian Zhang
conference: IJCNN 2022
pdf: /papers/conf_ijcnn_LeeGZ22.pdf
doi: 10.1109/IJCNN55064.2022.9892055
source: https://github.com/tachyonicClock/SurpriseNet-CIKM-23
---

Balancing the stability-plasticity dilemma is an omnipresent challenge in continual learning. The dilemma is that the ability of a model to learn new knowledge (plasticity) comes at the expense of the ability to remember past knowledge (stability) and vice versa. Some continual learning algorithms incorporate a constant hyper-parameter to control this trade-off. We argue that the trade-off should be dynamically tuned rather than kept constant. We propose a method to dynamically balance stability and plasticity in a semi-online and fully online manner. Our method is applicable to a range of underlying regularisation based strategies and class incremental problems. Our experiments in three continual learning benchmarks suggest that dynamic stability tuning methods can improve accuracy and decrease forgetting of continual learning strategies throughout their lifetime.
