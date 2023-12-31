---
layout: page
title: Person Re-identification
description: Enhancing cross-camera matching using deep learning for robust surveillance applications
img: assets/img/project3.png
importance: 3
category: work
---


## [Pose Invariant Person Re-identification using robust pose-transformation GAN](https://arxiv.org/pdf/2105.00930)
_Arnab Karmakar, Deepak Mishra_

_Abstract:_ The objective of person re-identification (re-ID) is to retrieve a person's images from an image gallery, given a single instance of the person of interest. Despite several advancements, learning discriminative identity-sensitive and viewpoint invariant features for robust Person Re-identification is a major challenge owing to the large pose variation of humans. This paper proposes a re-ID pipeline that utilizes the image generation capability of Generative Adversarial Networks combined with pose clustering and feature fusion to achieve pose invariant feature learning. The objective is to model a given person under different viewpoints and large pose changes and extract the most discriminative features from all the appearances. The pose transformational GAN (pt-GAN) module is trained to generate a person's image in any given pose. In order to identify the most significant poses for discriminative feature extraction, a Pose Clustering module is proposed. The given instance of the person is modelled in varying poses and these features are effectively combined through the Feature Fusion Network. The final re-ID model consisting of these 3 sub-blocks, alleviates the pose dependence in person re-ID. Also, The proposed model is robust to occlusion, scale, rotation and illumination, providing a framework for viewpoint invariant feature learning. The proposed method outperforms the state-of-the-art GAN based models in 4 benchmark datasets. It also surpasses the state-of-the-art models that report higher re-ID accuracy in terms of improvement over baseline.

## [Domain Adaptive Egocentric Person Re-identification](https://arxiv.org/pdf/2103.04870)
_Ankit Choudhary, Arnab Karmakar, Deepak Mishra_

_Abstract:_ Person re-identification (re-ID) in first-person (egocentric) vision is a fairly new and unexplored problem. With the increase of wearable video recording devices, egocentric data becomes readily available, and person re-identification has the potential to benefit greatly from this. However, there is a significant lack of large scale structured egocentric datasets for person re-identification, due to the poor video quality and lack of individuals in most of the recorded content. Although a lot of research has been done in person re-identification based on fixed surveillance cameras, these do not directly benefit egocentric re-ID. Machine learning models trained on the publicly available large scale re-ID datasets cannot be applied to egocentric re-ID due to the dataset bias problem. The proposed algorithm makes use of neural style transfer (NST) that incorporates a variant of Convolutional Neural Network (CNN) to utilize the benefits of both fixed camera vision and firstperson vision. NST generates images having features from both egocentric datasets and fixed camera datasets, that are fed through a VGG-16 network trained on a fixed-camera dataset for feature extraction. These extracted features are then used to re-identify individuals. The fixed camera dataset Market-1501 and the first-person dataset EGO Re-ID are applied for this work and the results are on par with the present re-identification models in the egocentric domain.

