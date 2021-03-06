---
title: "Delving into Robust Object Detection from Unmanned Aerial Vehicles: A Deep Nuisance Disentanglement Approach"
collection: publications
permalink: /publications/DeepNuisance
venue: "International Conference on Computer Vision"
date: 2019-7-22
citation: 'Zhenyu Wu, Karthik Suresh, Priya Narayanan, <b>Hongyu Xu</b>, Heesung Kwon and Zhangyang Wang. <i>In International Conference on Computer Vision</i>. <b>ICCV 2019</b>.'
---
[[PDF]](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wu_Delving_Into_Robust_Object_Detection_From_Unmanned_Aerial_Vehicles_A_ICCV_2019_paper.pdf)
[[ArXiv]](https://arxiv.org/abs/1908.03856)


## Abstract
Object detection from images captured by Unmanned Aerial Vehicles (UAVs) is becoming increasingly useful. Despite the great success of the generic object detection methods trained on ground-to-ground images, a huge performance drop is observed when they are directly applied to images captured by UAVs. The unsatisfactory performance is owing to many UAV-specific nuisances, such as varying flying altitudes, adverse weather conditions, dynamically changing viewing angles, etc. Those nuisances constitute a large number of fine-grained domains, across which the detection model has to stay robust. Fortunately, UAVs will record meta-data that depict those varying attributes, which are either freely available along with the UAV images, or can be easily obtained. We propose to utilize those free meta-data in conjunction with associated UAV images to learn domain-robust features via an adversarial training framework dubbed Nuisance Disentangled Feature Transform (NDFT), for the specific challenging problem of object detection in UAV images, achieving a substantial gain in robustness to those nuisances. We demonstrate the effectiveness of our proposed algorithm, by showing state-of-the-art performance (single model) on two existing UAV-based object detection benchmarks. The code is available at this https URL(https://github.com/TAMU-VITA/UAV-NDFT).
