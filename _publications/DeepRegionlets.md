---
title: "Deep Regionlets for Object Detection"
collection: publications
permalink: /publications/DeepRegionlets
venue: "Arxiv"
citation: '<b>Hongyu Xu</b>, Xutao Lv, Xiaoyu Wang, Zhou Ren, Navaneeth Bodla and Rama Chellappa. <i>Arxiv Preprint</i>. <b>Tech Report</b>.'
---
[[ArXiv]](https://arxiv.org/abs/1712.02408)


## Abstract
In this paper, we propose a novel object detection framework named "Deep Regionlets" by establishing a bridge between deep neural networks and conventional detection schema for accurate generic object detection. Motivated by the advantages of regionlets on modeling object deformation and multiple aspect ratios, we incorporate regionlet into an end-to-end trainable deep learning framework. The deep regionlets framework consists of a region selection network and a deep regionlet learning module. Specifically, given a detection bounding box proposal, the region selection network serves as a guidance on where to select regions to learn the features from. The regionlet learning module focuses on local feature selection and transformation to alleviate local variations. To this end, we first realize non-rectangular region selection within the detection framework to accommodate variations in object appearance. Moreover, we further design a "gating network" within the regionlet leaning module to enable soft regionlet selection and pooling. The Deep Regionlets framework is trained end-to-end without additional efforts. We perform ablation studies on its behavior and conduct extensive experiments on the PASCAL VOC and Microsoft COCO dataset. The proposed framework outperforms state-of-the-art algorithms, such as RetinaNet and Mask R-CNN, even without additional segmentation labels.
