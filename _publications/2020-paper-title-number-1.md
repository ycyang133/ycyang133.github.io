---
title: "Full-sphere binaural sound source localization using multi-task neural network"
collection: publications
<!--permalink: /publication/2020-paper-title-number-1-->
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.'-->
date: 2009-10-01
<!--venue: 'Journal 1'-->
<!-- slidesurl: 'http://academicpages.github.io/files/slides1.pdf' -->
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9306260/'
citation: 'Y. Yang, J. Xi, W. Zhang, and L. Zhang, “Full-sphere binaural sound source localization using multi-task neural network,” in {\em Proc. APSIPA ASC}, 2020, pp. 432-436.'
---

The accuracy of binaural sound source localization is faced with the challenge of localizing azimuth and elevation simultaneously in noisy and reverberant environments. In this work, a full-sphere binaural sound source localization system is proposed using convolutional neural network and multi-task neural network connected to learn the localization features. The log-magnitudes and interaural phase difference (IPD) of binaural signals are used as inputs to a two-branch convolutional neural network, from which interaural and monaural cues are extracted and combined. Then, the full-sphere localization is formulated as two subtasks of estimating azimuth and elevation separately using multi-task neural network. To reduce reverberation effects, the interaural coherence based pre-processing is used to select the direct-path dominated time-frequency bins for localization. The proposed system is evaluated at a variety of noise and reverberation conditions, in comparison with two baseline systems. The results indicate that the proposed system achieves better localization performance, especially for elevation estimation, at low SNR and strong reverberation conditions.
