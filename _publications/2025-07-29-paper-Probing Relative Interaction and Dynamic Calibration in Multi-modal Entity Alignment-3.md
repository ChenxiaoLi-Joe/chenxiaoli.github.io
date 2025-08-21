---
title: "Probing Relative Interaction and Dynamic Calibration in Multi-modal Entity Alignment"
collection: publications
category: conferences
permalink: /publication/2025-07-29-paper-Probing Relative Interaction and Dynamic Calibration in Multi-modal Entity Alignment-number-3
excerpt: 'First Author'
date: 2025-07-29
venue: 'The 63rd Annual Meeting of the Association for Computational Linguistics (ACL 2025 Main)'
---

Multi-modal entity alignment aims to identify equivalent entities between two different multi-modal knowledge graphs. Current methods have made significant progress by improving embedding and cross-modal fusion. However, most of them depend on using loss functions to capture the relationship between modalities or adopt a one-time strategy to directly compute modality weights using attention mechanisms, which overlooks the relative interactions between modalities at the entity level and the accuracy of modality weights, thereby hindering the generalization to diverse entities. To address this challenge, we propose RICEA, a relative interaction and calibration framework for multi-modal entity alignment, which dynamically computes weights based on the relative interaction and recalibrates the weights according to their uncertainties. Among these, we propose a novel method called ADC that utilizes attention mechanisms to perceive the uncertainty of the weight for each modality, rather than directly calculating the weight of each modality as in previous works. Across 5 datasets and 23 settings, our proposed framework significantly outperforms other baselines.
