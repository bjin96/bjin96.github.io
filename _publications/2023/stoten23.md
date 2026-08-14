---
title:          "Airborne pollen grain detection from partially labelled data utilising semi-supervised learning"
date:           2023-09-15 00:01:00 +0000
selected:       false
pub:            "Science of The Total Environment"
pub_date:       "2023"
semantic_scholar_id: 741e4250e81372d3d21893f8755d311c8ab2666b  # use this to retrieve citation count
abstract: >-
    Airborne pollen monitoring has been conducted for more than a century now, as knowledge of the quantity and periodicity of airborne pollen has diverse use cases, like reconstructing historic climates and tracking current climate change, forensic applications, and up to warning those affected by pollen-induced respiratory allergies. Hence, related work on automation of pollen classification already exists. In contrast, detection of pollen is still conducted manually, and it is the gold standard for accuracy. So, here we used a new-generation, automated, near-real-time pollen monitoring sampler, the BAA500, and we used data consisting of both raw and synthesised microscope images. Apart from the automatically generated, commercially-labelled data of all pollen taxa, we additionally used manual corrections to the pollen taxa, as well as a manually created test set of bounding boxes and pollen taxa, so as to more accurately evaluate the real-life performance. For the pollen detection, we employed two-stage deep neural network object detectors. We explored a semi-supervised training scheme to remedy the partial labelling. Using a teacher-student approach, the model can add pseudo-labels to complete the labelling during training. To evaluate the performance of our deep learning algorithms and to compare them to the commercial algorithm of the BAA500, we created a manual test set, in which an expert aerobiologist corrected automatically annotated labels. For the novel manual test set, both the supervised and semi-supervised approaches clearly outperform the commercial algorithm with an F1 score of up to 76.9 % compared to 61.3 %. On an automatically created and partially labelled test dataset, we obtain a maximum mAP of 92.7 %. Additional experiments on raw microscope images show comparable performance for the best models, which potentially justifies reducing the complexity of the image generation process. Our results bring automatic pollen monitoring a step forward, as they close the gap in pollen detection performance between manual and automated procedure.
cover:          /assets/images/covers/stoten23.png
authors:
  - Benjamin Jin
  - Manuel Milling
  - Maria Pilar Plaza
  - Jens O. Brunner
  - Claudia Traidl-Hoffmann
  - Björn W. Schuller
  - Athanasios Damialis
links:
  Paper: https://doi.org/10.1016/j.scitotenv.2023.164295
  Code: https://github.com/bjin96/ssl-pollen-detection
---
