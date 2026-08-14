---
title:          "AI-Based Pipeline for the Segmentation of White Matter Hypoattenuations in CT Scans: A Design-Choice Validation Study"
date:           2026-03-11 00:01:00 +0000
selected:       false
pub:            "medRxiv"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2026"
semantic_scholar_id: 6023d946a18ba301feb36daa60a351343903fd21  # use this to retrieve citation count
abstract: >-
  Purpose White matter hyperintensities are a key imaging marker of vascular pathology, defined on brain magnetic resonance imaging (MRI) and typically manifesting on non-contrast computed tomography (CT) as subtle white matter hypoattenuation (WMH). Accurately segmenting WMH in CT scans remains challenging due to their low contrast with the surrounding tissue. This work presents an end-to-end framework for WMH segmentation in CT scans and validates the design choices in each step of the processing pipeline. We leverage a state-of-the-art deep-learning method combined with manually annotated and pseudo-labelled datasets from paired CT-MRI scans from different clinical scanners to deliver reliable outcomes. Approach Our framework includes DICOM data curation, sequence selection, and automatic label generation as preparation steps. Preprocessing includes z-score intensity normalisation, skull stripping, CT windowing and two-step CT-MRI registration to accurately transfer MRI-derived labels into the CT space. Further processing involves the use of a 3D nnU-Net initially trained on CT images with aligned MRI-based WMH manually derived (n=91) and fine-tuned with two additional pseudolabelled datasets (n=191). Findings CT-based WMH volumes showed a near-perfect correlation with ground-truth MRI WMH volumes (r = 0.98), with a systematic overestimation (mean difference = 2.40 mL; 95% limits of agreement: -8.31 to 13.11 mL) that may be adjustable in downstream tasks. This overestimation reflected challenges in the precise delineation of small WMH lesions and confounding from other imaging markers of brain disease. Across the evaluated cohort, ground-truth WMH volumes ranged from 1.02 to 149.34 mL. The best-performing configuration achieved a mean absolute error below 3 mL, corresponding to approximately 17% of the mean WMH volume, and a mean Dice similarity coefficient of 0.57. Segmentation accuracy decreased in the presence of stroke lesions. Models trained on single-pathology datasets, as well as approaches relying on template-based spatial normalisation, did not achieve satisfactory performance despite using the same backbone network configuration. Conclusion Using a multi-centre dataset and a multi-modal approach with expert-annotated data combined with pseudo-labelled data for training can substantially narrow the performance gap between CT- and MRI-based WMH segmentation. The framework proposed provides a generalisable solution that underscores the practical viability of CT for evaluating WMH burden in clinical and research scenarios—particularly where MRI is unavailable or contraindicated—thereby broadening access to small-vessel disease assessment.
cover:          /assets/images/covers/wmh_ct_scans.png
authors:
  - Nada Alamoudi
  - Maria del C. Valdés Hernández
  - Benjamin Jin
  - Eleni Sakka
  - Carmen Arteaga-Reyes
  - Daniela Jaime García
  - Yajun Cheng
  - Angela C.C. Jochems
  - Grant Mair
  - Joanna M. Wardlaw
  - Miguel O. Bernabeu
links:
  Paper: https://doi.org/10.64898/2026.03.10.26348006
---
