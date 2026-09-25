---
title: "Cross-Modal Prior-Guided Training with Visual Foundation Models for Unsupervised LiDAR Point Cloud Registration"
collection: publications
category: conferences
permalink: /publication/2026-09-25-neurips2026-integer
excerpt: 'We introduce PROMOTER, a novel method leveraging Visual Foundation Models for unsupervised learning of LiDAR point cloud registration, which is capable of training various registration models and scales well with stronger VFMs.'
date: 2026-09-25
venue: 'NeurIPS 2026 Main Conference'
paperurl: 'example.com'
citation: 'Coming Soon'
---

## Abstract

Visual Foundation Models (VFMs) have demonstrated strong capabilities in visual-geometric tasks such as image matching and 3D reconstruction. Recent work has revealed the potential of VFMs in label-free indoor RGB-D registration, where the visual modality is intrinsic to the task. A natural question follows: can this success extend to more challenging outdoor scenarios characterized by sparse, irregular LiDAR data with only partial visual coverage? We answer this with PROMOTER, a novel teacher–student framework for unsupervised LiDAR registration that bridges visual priors and sparse LiDAR geometry. To leverage pre-trained geometric priors for 3D registration, we must disentangle them from confounding signals introduced by modality and task gaps under partial visual coverage. To this end, we introduce a lightweight Adaptive Prior Integrator that extracts and integrates these priors into an enhanced teacher, together with a Perceptual-Geometric Labeler that produces high-quality pseudo-labels. For student training, we propose Matchability-Anchored Training to improve robustness under noisy supervision. Experiments on KITTI and nuScenes demonstrate state-of-the-art performance and improved scalability across registration models and VFMs, while incurring no additional parameters at inference. Code will be released.

## Code Release

Coming Soon

## Citation

Coming Soon
