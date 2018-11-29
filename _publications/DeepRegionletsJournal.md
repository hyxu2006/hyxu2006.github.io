---
title: "Deep Regionlets: Blended Representation and Deep Learning for Generic Object Detection"
collection: publications
permalink: /publications/DeepRegionletsJournal
venue: "Arxiv"
date: 2018-11-28
citation: '<b>Hongyu Xu</b>, Xutao Lv, Xiaoyu Wang, Zhou Ren and Rama Chellappa. <i>Arxiv Preprint</i>. <b>Submitted to IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</b>.'
---

[[ArXiv]](https://arxiv.org/abs/1811.11318)
[[Conference Paper]](http://openaccess.thecvf.com/content_ECCV_2018/papers/Hongyu_Xu_Deep_Regionlets_for_ECCV_2018_paper.pdf)


## Abstract
In this paper, we propose a novel object detection algorithm named "Deep Regionlets" by integrating deep neural networks and conventional detection schema for accurate generic object detection. Motivated by the advantages of regionlets on modeling object deformation and multiple aspect ratios, we incorporate regionlets into an end-to-end trainable deep learning framework. The deep regionlets framework consists of a region selection network and a deep regionlet learning module. Specifically, given a detection bounding box proposal, the region selection network provides guidance on where to select regions from which features can be learned from. The regionlet learning module focuses on local feature selection and transformation to alleviate the effects of appearance variations. To this end, we first realize non-rectangular region selection within the detection framework to accommodate variations in object appearance. Moreover, we design a "gating network" within the regionlet leaning module to enable soft regionlet selection and pooling. The Deep Regionlets framework is trained end-to-end without additional efforts. We present the results of ablation studies and extensive experiments on PASCAL VOC and Microsoft COCO datasets. The proposed algorithm outperforms state-of-the-art algorithms, such as RetinaNet and Mask R-CNN, even without additional segmentation labels.
