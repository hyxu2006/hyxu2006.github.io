---
title: "Bridging the Domain Shift by Domain Adaptive Dictionary Learning"
collection: publications
permalink: /publications/DADL
venue: "British Machine Vision Conference (BMVC)"
date: 2015-9-5
citation: '<b>Hongyu Xu</b>, Jingjing Zheng and Rama Chellappa. <i>British Machine Vision Conference</i>. <b>BMVC 2015</b>. <b> <span style="color:red">Oral Presentation</span> </b>'
---
[[PDF]](https://hyxu2006.github.io/files/DADL_BMVC2015.pdf)


## Abstract
Domain adaptation (DA) tackles the problem where data from the training set (source domain) and test set (target domain) have different underlying distributions. In this paper, we propose a novel domain-adaptive dictionary learning framework to generate a set of intermediate domains. These intermediate domains form a smooth path and bridge the gap between the source and target domains. Specifically, we not only learn a common dictionary to encode the domain-shared features, but also learn a set of domain-specific dictionaries to model the domain shift. The separation of the common and domain-specific dictionaries enables us to learn more compact and reconstructive dictionaries for domain adaptation. These dictionaries are learned by alternating between domain-adaptive sparse coding and dictionary updating steps. Meanwhile, our approach gradually recovers the feature representations of both source and target data along the domain path. By aligning all the recovered domain data, we derive the final domain-adaptive features for recognition. Extensive experiments on cross-domain face and object recognition show that our approach significantly outperforms state-of-the-art methods.
