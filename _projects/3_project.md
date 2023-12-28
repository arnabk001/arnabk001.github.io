---
layout: page
title: Person Re-identification
description: Enhancing cross-camera matching using deep learning for robust surveillance applications
img: assets/img/project3.png
importance: 3
category: work
---


## [Pose Invariant Person Re-identification using robust pose-transformation GAN](https://arxiv.org/pdf/2105.00930)
### Authors: _Arnab Karmakar, Deepak Mishra_

_Abstract:_ The objective of person re-identification (re-ID) is to retrieve a person's images from an image gallery, given a single instance of the person of interest. Despite several advancements, learning discriminative identity-sensitive and viewpoint invariant features for robust Person Re-identification is a major challenge owing to the large pose variation of humans. This paper proposes a re-ID pipeline that utilizes the image generation capability of Generative Adversarial Networks combined with pose clustering and feature fusion to achieve pose invariant feature learning. The objective is to model a given person under different viewpoints and large pose changes and extract the most discriminative features from all the appearances. The pose transformational GAN (pt-GAN) module is trained to generate a person's image in any given pose. In order to identify the most significant poses for discriminative feature extraction, a Pose Clustering module is proposed. The given instance of the person is modelled in varying poses and these features are effectively combined through the Feature Fusion Network. The final re-ID model consisting of these 3 sub-blocks, alleviates the pose dependence in person re-ID. Also, The proposed model is robust to occlusion, scale, rotation and illumination, providing a framework for viewpoint invariant feature learning. The proposed method outperforms the state-of-the-art GAN based models in 4 benchmark datasets. It also surpasses the state-of-the-art models that report higher re-ID accuracy in terms of improvement over baseline.

## [Domain Adaptive Egocentric Person Re-identification](https://arxiv.org/pdf/2103.04870)
### Authors: _Ankit Choudhary, Arnab Karmakar, Deepak Mishra_

_Abstract:_ Person re-identification (re-ID) in first-person (egocentric) vision is a fairly new and unexplored problem. With the increase of wearable video recording devices, egocentric data becomes readily available, and person re-identification has the potential to benefit greatly from this. However, there is a significant lack of large scale structured egocentric datasets for person re-identification, due to the poor video quality and lack of individuals in most of the recorded content. Although a lot of research has been done in person re-identification based on fixed surveillance cameras, these do not directly benefit egocentric re-ID. Machine learning models trained on the publicly available large scale re-ID datasets cannot be applied to egocentric re-ID due to the dataset bias problem. The proposed algorithm makes use of neural style transfer (NST) that incorporates a variant of Convolutional Neural Network (CNN) to utilize the benefits of both fixed camera vision and firstperson vision. NST generates images having features from both egocentric datasets and fixed camera datasets, that are fed through a VGG-16 network trained on a fixed-camera dataset for feature extraction. These extracted features are then used to re-identify individuals. The fixed camera dataset Market-1501 and the first-person dataset EGO Re-ID are applied for this work and the results are on par with the present re-identification models in the egocentric domain.

<!-- Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %} -->
