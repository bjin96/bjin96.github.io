---
title:          "Automated Distinction of Intimal and Medial Intracranial Arterial Calcification from CT Head"
date:           2026-09-26 00:01:00 +0000
selected:       true
pub:            "arXiv"
pub_pre:        "Accepted at SWITCH+ @ MICCAI 2026"
# pub_post:       'Under review.'
pub_date:       "2026"
semantic_scholar_id: 8d77ef63fbb8914b0bee04adc266a8106ad10b25  # use this to retrieve citation count
abstract: >-
  Intracranial arterial calcifications (IACs) are a common finding on clinical non-contrast enhanced head CT scans and are associated with neurovascular disease. Calcifications can occur in the intimal or medial layer of the arterial wall, subtypes that differ in aetiology and may have distinct clinical relevance. These subtypes can be visually distinguished by radiologists based on the shape of the calcifications. We investigate three automated approaches for subtype classification of IAC from head CT-derived segmentation masks: (1) an automated adaptation of the established radiological visual score, (2) a sphericity-based method, and (3) a method based on shape embeddings extracted by a medical shape foundation model. All approaches use the same lightweight classification pipeline on top of the features they compute and are evaluated using 5-fold cross-validation. The three methods achieved comparable performance, with the embedding-based approach yielding the best overall results with a weighted F1 (mean ± SD) of up to 71.5 ± 3.7 for a single artery and 59.8 ± 1.7 for the joint artery classification. Performance was largely preserved when using automated instead of manual IAC segmentation masks, and we found the difference in weighted F1 not significant. Our results show that fully automated IAC subtype quantification from head CT is feasible and remains robust to the use of manual and automated IAC segmentation masks.
cover:          /assets/images/covers/switch_miccai_2026.png
authors:
  - Benjamin Jin
  - Maria del C. Valdés Hernández
  - Richard Bortsov
  - Joanna M. Wardlaw
  - Daniel Bos
  - Grant Mair
links:
  Paper: https://doi.org/10.48550/arXiv.2609.16035
  Code: https://github.com/bjin96/iac-subtyping
---
