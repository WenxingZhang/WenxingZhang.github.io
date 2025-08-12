---
title: "Unsupervised diffusion method with null space learning for cloud removal in remote sensing images"
collection: publications
category: manuscripts
permalink: /publication/2024-12-01-paper-title-number-1
date: 2024-12-01
venue: 'under review'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
#paperurl: 'http://academicpages.github.io/files/paper1.pdf'
#bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Y.X. Zhang, L.W. Xu, J.P. Yin, W.X. Zhang. (2025). <i>under review</i>. 1-26.'
---
Clouds are ubiquitous in remote sensing images, and most of the existing methods for cloud removal are limited to either implementing multispectral images or exploiting supervised learning techniques. In this paper, we propose an unsupervised diffusion method by adapting the null space learning. The proposed method is built upon two trained denoising diffusion probabilistic models on diverse remote sensing datasets so as to cope with the mixed data from different sources. The matrices involving simplified degradation and  ``self-adaptive'' generalized inverse are devised for the null space decomposition. For the diffusion model with null space decomposition, we derive its continuous reverse-time stochastic differential equation (SDE) and prove its variance-preserving property. Furthermore, we formulate  explicitly the expectation of  reverse-time SDE, which expedites  the numerical efficiency of the proposed method. Numerical experiments on some remote sensing images are implemented to demonstrate the performance of the proposed method.
