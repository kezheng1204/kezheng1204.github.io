---
title: "Mining and Transferring Feature-Geometry Coherence for Unsupervised Point Cloud Registration"
collection: publications
category: conferences
permalink: /publication/2024-09-27-neurips2024-integer
excerpt: 'In this paper, we propose a novel unsupervised registration method termed INTEGER to incorporate high-level contextual information for reliable pseudo-label mining.'
date: 2024-09-27
venue: 'NeurIPS 2024 Main Conference'
paperurl: 'http://kezheng1204.github.io/files/neurips-24-integer.pdf'
citation: 'Xiong, Kezheng, et al. "Mining and Transferring Feature-Geometry Coherence for Unsupervised Point Cloud Registration." The Thirty-eighth Annual Conference on Neural Information Processing Systems (2024).'
---

[[NeurIPS 2024]](https://neurips.cc/virtual/2024/poster/95385) [[arXiv]](https://arxiv.org/abs/2411.01870)

## Abstract

Point cloud registration, a fundamental task in 3D vision, has achieved remarkable success with learning-based methods in outdoor environments. Unsupervised outdoor point cloud registration methods have recently emerged to circumvent the need for costly pose annotations. However, they fail to establish reliable optimization objectives for unsupervised training, either relying on overly strong geometric assumptions, or suffering from poor-quality pseudo-labels due to inadequate integration of low-level geometric and high-level contextual information. We have observed that in the feature space, latent new inlier correspondences tend to cluster around respective positive anchors that summarize features of existing inliers. Motivated by this observation, we propose a novel unsupervised registration method termed INTEGER to incorporate high-level contextual information for reliable pseudo-label mining. Specifically, we propose the Feature-Geometry Coherence Mining module to dynamically adapt the teacher for each mini-batch of data during training and discover reliable pseudo-labels by considering both high-level feature representations and low-level geometric cues. Furthermore, we propose Anchor-Based Contrastive Learning to facilitate contrastive learning with anchors for a robust feature space. Lastly, we introduce a Mixed-Density Student to learn density-invariant features, addressing challenges related to density variation and low overlap in the outdoor scenario. Extensive experiments on KITTI and nuScenes datasets demonstrate that our INTEGER achieves competitive performance in terms of accuracy and generalizability.

## Code Release

The code will be available at [INTEGER](https://github.com/kezheng1204/INTEGER).

## Citation

```bibtex
@inproceedings{
xiong2024mining,
title={Mining and Transferring Feature-Geometry Coherence for Unsupervised Point Cloud Registration},
author={KeZheng Xiong and Haoen Xiang and Qingshan Xu and Chenglu Wen and Siqi Shen and Jonathan Li and Cheng Wang},
booktitle={The Thirty-eighth Annual Conference on Neural Information Processing Systems},
year={2024},
url={https://openreview.net/forum?id=OCcfKzXded}
}
```