---
title:          "Pre-processing and Quality Control of Large Clinical CT Head Datasets for Intracranial Arterial Calcification Segmentation"
date:           2024-10-25 00:01:00 +0000
selected:       true
pub:            "Data Engineering in Medical Imaging @ Medical Image Computing and Computer Assisted Interventions (MICCAI)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2024"
semantic_scholar_id: c5540c1c88ba44d1d2621095aa90ffe801f32194  # use this to retrieve citation count
abstract: >-
  As a potential non-invasive biomarker for ischaemic stroke, intracranial arterial calcification (IAC) could be used for stroke risk assessment on CT head scans routinely acquired for other reasons (e.g. trauma, confusion). Artificial intelligence methods can support IAC scoring, but they have not yet been developed for clinical imaging. Large heterogeneous clinical CT datasets are necessary for the training of such methods, but they exhibit expected and unexpected data anomalies. Using CTs from a large clinical trial, the third International Stroke Trial (IST-3), we propose a pipeline that uses as input non-enhanced CT scans to output regions of interest capturing selected large intracranial arteries for IAC scoring. Our method uses co-registration with templates. We focus on quality control, using information presence along the z-axis of the imaging to group and apply similarity measures (structural similarity index measure) to triage assessment of individual image series. Additionally, we propose superimposing thresholded binary masks of the series to inspect large quantities of data in parallel. We identify and exclude unrecoverable samples and registration failures. In total, our pipeline processes 10,659 CT series, rejecting 4,322 (41%) in the entire process, 1,450 (14% of the total) during quality control, and outputting 6,337 series. Our pipeline enables effective and efficient region of interest localisation for targeted IAC segmentation.
cover:          /assets/images/covers/demi_miccai2024.png
authors:
  - Benjamin Jin
  - Maria del C. Valdés Hernández
  - Alessandro Fontanellea
  - Wenwen Li
  - Eleanor Platt
  - Paul Armitage
  - Amos Storkey
  - Joanna M. Wardlaw
  - Grant Mair
links:
  Paper: https://doi.org/10.1007/978-3-031-73748-0_8
  Code: https://github.com/bjin96/ct-processing
---
