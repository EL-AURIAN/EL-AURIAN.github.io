---
title: "DS6, Deformation-Aware Semi-Supervised Learning: Application to Small Vessel Segmentation with Noisy Training Data"
collection: publications
category: manuscripts
permalink: /publication/ds6
excerpt: 'Blood vessels of the brain provide the human brain with the required nutrients and oxygen. As a vulnerable part of the cerebral blood supply, pathology of small vessels can cause serious problems such as Cerebral Small Vessel Diseases (CSVD). It has also been shown that CSVD is related to neurodegeneration, such as Alzheimer’s disease. With the advancement of 7 Tesla MRI systems, higher spatial image resolution can be achieved, enabling the depiction of very small vessels in the brain. Non-Deep Learning-based approaches for vessel segmentation, e.g., Frangi’s vessel enhancement with subsequent thresholding, are capable of segmenting medium to large vessels but often fail to segment small vessels. The sensitivity of these methods to small vessels can be increased by extensive parameter tuning or by manual corrections, albeit making them time-consuming, laborious, and not feasible for larger datasets. This paper proposes a deep learning architecture to automatically segment small vessels in 7 Tesla 3D Time-of-Flight (ToF) Magnetic Resonance Angiography (MRA) data. The algorithm was trained and evaluated on a small imperfect semi-automatically segmented dataset of only 11 subjects; using six for training, two for validation, and three for testing. The deep learning model based on U-Net Multi-Scale Supervision was trained using the training subset and was made equivariant to elastic deformations in a self-supervised manner using deformation-aware learning to improve the generalisation performance. The proposed technique was evaluated quantitatively and qualitatively against the test set and achieved a Dice score of 80.44 ± 0.83. Furthermore, the result of the proposed method was compared against a selected manually segmented region (62.07 resultant Dice) and has shown a considerable improvement (18.98%) with deformation-aware learning.'
date: 2022-09-22
venue: 'Journal of Imaging'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
projectpage: 'https://soumickmj.github.io/DS6/'
paperurl: 'https://www.mdpi.com/2313-433X/8/10/259/pdf?version=1663934698'
citation: 'Chatterjee, Soumick, et al. (2022). &quot;Ds6, deformation-aware semi-supervised learning: Application to small vessel segmentation with noisy training data.&quot; <i>Journal of Imaging </i>. 8.10 (259).'
---

