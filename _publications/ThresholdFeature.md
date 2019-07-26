---
title: "Thresholded Features with Sparse Support Recovery"
collection: publications
permalink: /publications/ThresholdFeature
venue: "IEEE Transactions on Circuits and Systems for Video Technology"
date: 2019-2-26
citation: '<b>Hongyu Xu</b>*, Zhangyang Wang*, Haichuan Yang, Ding Liu and Ji Liu. <i>Arxiv Preprint</i>. <b>IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)</b>. (* equal contribution)'
---
[[PDF]](https://ieeexplore.ieee.org/document/8653305)
[[ArXiv]](https://arxiv.org/abs/1804.05515)


## Abstract
The thresholded feature has recently emerged as an extremely efficient, yet rough empirical approximation, of the time-consuming sparse coding inference process. Such an approximation has not yet been rigorously examined, and standard dictionaries often lead to non-optimal performance when used for computing thresholded features. In this paper, we first present two theoretical recovery guarantees for the thresholded feature to exactly recover the nonzero support of the sparse code. Motivated by them, we then formulate the Dictionary Learning for Thresholded Features (DLTF) model, which learns an optimized dictionary for applying the thresholded feature. In particular, for the (k,2) norm involved, a novel proximal operator with log-linear time complexity O(mlogm) is derived. We evaluate the performance of DLTF on a vast range of synthetic and real-data tasks, where DLTF demonstrates remarkable efficiency, effectiveness and robustness in all experiments. In addition, we briefly discuss the potential link between DLTF and deep learning building blocks.
