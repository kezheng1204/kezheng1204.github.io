---
title: "Mining and Transferring Feature-Geometry Coherence for Unsupervised Point Cloud Registration"
collection: publications
category: conferences
permalink: /publication/2024-09-27-neurips2024-integer
excerpt: '..., Motivated by this observation, we propose a novel unsupervised registration method termed INTEGER to incorporate high-level contextual information for reliable pseudo-label mining.'
date: 2024-09-27
venue: 'Accepted to NeurIPS 2024 Main Conference'
paperurl: 'http://kezheng1204.github.io/files/paper_placeholder.pdf'
citation: 'Coming Soon.'
---

## Abstract
Point cloud registration, a fundamental task in 3D vision, has achieved remarkable success with learning-based methods in outdoor environments. Unsupervised outdoor point cloud registration methods have recently emerged to circumvent the need for costly pose annotations. However, they suffer from the poor quality of pseudo-labels due to inadequate integration of low-level geometric and high-level contextual information while discovering latent correspondences. We have observed that in the feature space, points of latent new inlier correspondences tend to cluster around respective positive anchors that summarize features of existing inliers. Motivated by this observation, we propose a novel unsupervised registration method termed INTEGER to incorporate high-level contextual information for reliable pseudo-label mining. Specifically, we propose the Feature-Geometry Coherence Mining module to dynamically adapt the teacher for each mini-batch of data during training and discover reliable pseudo labels by considering both high-level feature representations and low-level geometric cues. Furthermore, we propose Anchor-Based Contrastive Learning to facilitate contrastive learning with anchors for a robust feature space. Lastly, we introduce a Mix-Density Student to learn density-invariant features, addressing challenges related to density variation and low overlap in the outdoor scenario. Extensive experiments on KITTI and nuScenes datasets demonstrate that our INTEGER achieves competitive performance in terms of accuracy and generalizability.

## Code Release

Coming Soon.

## Citation

Coming Soon