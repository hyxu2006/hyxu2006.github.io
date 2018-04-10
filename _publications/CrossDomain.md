---
title: "Cross-Domain Visual Recognition via Domain Adaptive Dictionary Learning"
collection: publications
permalink: /publications/CrossDomain
venue: "Arxiv"
date: 2018-4-8
citation: '<b>Hongyu Xu</b>, Jingjing Zheng, Azadeh Alavi and Rama Chellappa and Rama Chellappa. <i>Arxiv Preprint</i>. <b>Submitted to IEEE TIP</b>.'
---
[[ArXiv]]()


## Abstract
In real-world visual recognition problems, the assumption that the training data (source domain) and test data (target domain) are sampled from the same distribution is often violated. This is known as the domain adaptation problem. In this work, we propose a novel domain-adaptive dictionary learning framework for cross-domain visual recognition. Our method generates a set of intermediate domains. These intermediate domains form a smooth path and bridge the gap between the source and target domains. Specifically, we not only learn a common dictionary to encode the domain-shared features, but also learn a set of domain-specific dictionaries to model the domain shift. The separation of the common and domain-specific dictionaries enables us to learn more compact and reconstructive dictionaries for domain adaptation. These dictionaries are learned by alternating between domain-adaptive sparse coding and dictionary updating steps. Meanwhile, our approach gradually recovers the feature representations of both source and target data along the domain path. By aligning all the recovered domain data, we derive the final domain-adaptive features for cross-domain visual recognition. Extensive experiments on three public datasets demonstrates that our approach outperforms most state-of-the-art methods.
