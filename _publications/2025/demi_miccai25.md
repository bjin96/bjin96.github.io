---
title:          "Calibrated Self-supervised Vision Transformers Improve Intracranial Arterial Calcification Segmentation from Clinical CT Head Scans"
date:           2025-10-12 00:01:00 +0000
selected:       true
pub:            "Data Engineering in Medical Imaging @ Medical Image Computing and Computer Assisted Interventions (MICCAI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2025"
semantic_scholar_id: 9a5f085562a11173b81f8916ff6fad4903059438  # use this to retrieve citation count
abstract: >-
  Vision Transformers (ViTs) have gained significant popularity in the natural image domain but have been less successful in 3D medical image segmentation. Nevertheless, 3D ViTs are particularly interesting for large medical imaging volumes due to their efficient self-supervised training within the masked autoencoder (MAE) framework, which enables the use of imaging data without the need for expensive manual annotations. intracranial arterial calcification (IAC) is an imaging biomarker visible on routinely acquired CT scans linked to neurovascular diseases such as stroke and dementia, and automated IAC quantification could enable their large-scale risk assessment. We pre-train ViTs with MAE and fine-tune them for IAC segmentation for the first time. To develop our models, we use highly heterogeneous data from a large clinical trial, the third International Stroke Trial (IST-3). We evaluate key aspects of MAE pre-trained ViTs in IAC segmentation, and analyse the clinical implications. We show: 1) our calibrated self-supervised ViT beats a strong supervised nnU-Net baseline by 3.2 Dice points, 2) low patch sizes are crucial for ViTs for IAC segmentation and interpolation upsampling with regular convolutions is preferable to transposed convolutions for ViT-based models, and 3) our ViTs increase robustness to higher slice thicknesses and improve risk group classification in a clinical scenario by 46%.
cover:          /assets/images/covers/demi_miccai2025.png
authors:
  - Benjamin Jin
  - Grant Mair
  - Joanna M. Wardlaw
  - Maria del C. Valdés Hernández
links:
  Paper: https://doi.org/10.1007/978-3-032-08009-7_19
  Code: https://github.com/bjin96/mae-medical-segmentation
---
