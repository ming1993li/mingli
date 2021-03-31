---
title: "Discovering Discriminative Geometric Features with Self-Supervised Attention for Vehicle Re-Identification and Beyond"
collection: publications
permalink: /publication/geometric
<!-- excerpt: 'This paper is about the number 1. The number 2 is left for future work.' -->
date: 2021-01-18
venue: "arXiv"
paperurl: ""
citation: '<b>Ming Li</b>, Xinming Huang, Ziming Zhang. "Discovering Discriminative Geometric Features with Self-Supervised Attention for Vehicle Re-Identification and Beyond". <i>arXiv</i>. 2021.'
---
# Discovering Discriminative Geometric Features with Self-Supervised Attention for Vehicle Re-Identification and Beyond

[<a href="https://arxiv.org/pdf/2010.09221.pdf">Paper</a>]

## Abstract
In the literature of vehicle re-identification (ReID), in-tensive manual 
labels such as landmarks, critical parts orsemantic segmentation masks 
are often required to improvethe performance. Such extra information 
helps to detect lo-cally geometric features as a part of representation 
learningfor vehicles. In contrast, in this paper, we aim to address the
challenge ofautomaticallylearning to detect geometric fea-tures as 
landmarkswith no extra labels.  To the best of ourknowledge, we are 
the first to successfully learn discrimi-native geometric features for 
vehicle ReID based on self-supervised attention. Specifically, we implement 
an end-to-end trainable deep network architecture consisting of threebranches:  
(1) a global branch as backbone for image fea-ture extraction, (2) an attentional 
branch for producing at-tention masks,  and (3) a self-supervised branch for 
regu-larizing the attention learning with rotated images to locategeometric 
features. We conduct comprehensive experimentson three benchmark datasets 
for vehicle ReID,i.e.,VeRi-776, CityFlow-ReID, and VehicleID, and demonstrate 
ourstate-of-the-art performance. We also show the good gener-alization of our 
approach in other ReID tasks such as per-son ReID and multi-target multi-camera 
(MTMC) vehicletracking.Our demo code is attached in the supplementaryfile.
