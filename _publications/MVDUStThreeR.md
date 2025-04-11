---
title: "MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds"
collection: publications
permalink: /publications/MVDUStThreeR
venue: "The IEEE/CVF Conference on Computer Vision and Pattern Recognition"
date: 2025-02-28
citation: 'Zhenggang Tang, Yuchen Fan, Dilin Wang, <b>Hongyu Xu</b>, Rakesh Ranjan, Alexander Schwing, Zhicheng Yan. <i>The IEEE/CVF Conference on Computer Vision and Pattern Recognition</i>. <b>CVPR 2025</b>. <b> <span style="color:red">Oral Presentation</span> </b>'
---
[[Paper]](https://arxiv.org/abs/2412.06974)
[[Video Results]](https://www.youtube.com/watch?v=LBvnuKQ8Rso)
[[Code Released!]](https://github.com/facebookresearch/mvdust3r)


## Abstract
Recent sparse multi-view scene reconstruction advances like DUSt3R and MASt3R no longer require camera calibration and camera pose estimation. However, they only process a pair of views at a time to infer pixel-aligned pointmaps. When dealing with more than two views, a combinatorial number of error prone pairwise reconstructions are usually followed by an expensive global optimization, which often fails to rectify the pairwise reconstruction errors. To handle more views, reduce errors, and improve inference time, we propose the fast single-stage feed-forward network MV-DUSt3R. At its core are multi-view decoder blocks which exchange information across any number of views while considering one reference view. To make our method robust to reference view selection, we further propose MV-DUSt3R+, which employs cross-reference-view blocks to fuse information across different reference view choices. To further enable novel view synthesis, we extend both by adding and jointly training Gaussian splatting heads. Experiments on multi-view stereo reconstruction, multi-view pose estimation, and novel view synthesis confirm that our methods improve significantly upon prior art. Code will be released.
