---
layout: page
title: 6DoF Object Pose Estimation
description: Keypoint voting methods for RGB-D, point cloud, and self-supervised pose estimation.
img: assets/img/portfolio/merged.gif
importance: 2
category: research
related_publications: true
---

Research from my PhD at Queen's University on 6DoF object pose estimation for robot perception. This line of work includes RCVPose, RCVPose3D, KeyGNet, and RKHSPose.

Core topics:

- Radial keypoint voting for RGB-D 6DoF pose estimation.
- Cascaded keypoint voting for point-cloud-only pose estimation.
- Learned keypoint selection for multi-object settings.
- Self-supervised sim-to-real pose estimation with pseudo-keypoints and RKHS learning.

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/portfolio/merged.gif" title="Pose estimation portfolio clip" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

Project links: [RCVPose code](https://github.com/aaronWool/rcvpose), [RCVPose paper](https://arxiv.org/abs/2104.02527), [RCVPose3D paper](https://arxiv.org/abs/2210.08123), [RKHSPose paper](https://arxiv.org/abs/2311.09500).
