---
title: "RoomDreamer: Text-Driven 3D Indoor Scene Synthesis with Coherent Geometry and Texture"
collection: publications
permalink: /publications/RoomDreamer
venue: "ACM Multimedia"
date: 2023-10-28
citation: 'Liangchen Song, Liangliang Cao, <b>Hongyu Xu</b>, Kai Kang, Feng Tang, Junsong Yuan, Yang Zhao. <i>In the Association for Computing Machinery annual conference on multimedia</i>. <b>ACM Multimedia 2023</b>.'
---
[[ArXiv]](https://arxiv.org/abs/2305.11337)
[[Video Results]](https://www.youtube.com/watch?v=p4xgwj4QJcQ)


## Abstract
The techniques for 3D indoor scene capturing are widely used, but the meshes produced leave much to be desired. In this paper, we propose "RoomDreamer", which leverages powerful natural language to synthesize a new room with a different style. Unlike existing image synthesis methods, our work addresses the challenge of synthesizing both geometry and texture aligned to the input scene structure and prompt simultaneously. The key insight is that a scene should be treated as a whole, taking into account both scene texture and geometry. The proposed framework consists of two significant components: Geometry Guided Diffusion and Mesh Optimization. Geometry Guided Diffusion for 3D Scene guarantees the consistency of the scene style by applying the 2D prior to the entire scene simultaneously. Mesh Optimization improves the geometry and texture jointly and eliminates the artifacts in the scanned scene. To validate the proposed method, real indoor scenes scanned with smartphones are used for extensive experiments, through which the effectiveness of our method is demonstrated.
