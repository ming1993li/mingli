---
title: "LodoNet: A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation"
collection: publications
permalink: /publication/lodo_mm_20
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2020-08-17
venue: "28th ACM International Conference on Multimedia"
paperurl: ""
citation: 'Ce Zheng, Yecheng Lyu, <b>Ming Li</b>, Ziming Zhang. "A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation". <i>ACM MM</i>. 2020.'
---
# A Deep Neural Network with 2D Keypoint Matching for 3D LiDAR Odometry Estimation

[<a href="https://ming1993li.github.io/files/MM20_Lodo.pdf">Paper</a>]

## Abstract
Deep learning based LiDAR odometry (LO) estimation attracts
increasing research interests in the field of autonomous driving and
robotics. Existing works feed consecutive LiDAR frames into neural
networks as point clouds and match pairs in the learned feature
space. In contrast, motivated by the success of image based feature
extractors, we propose to transfer the LiDAR frames to image space
and reformulate the problem as image feature extraction. With
the help of scale-invariant feature transform (SIFT) for feature
extraction, we are able to generate matched keypoint pairs (MKPs)
that can be precisely returned to the 3D space. A convolutional
neural network pipeline is designed for LiDAR odometry estimation
by extracted MKPs. The proposed scheme, namely LodoNet, is then
evaluated in the KITTI odometry estimation benchmark, achieving
on par with or even better results than the state-of-the-art.
