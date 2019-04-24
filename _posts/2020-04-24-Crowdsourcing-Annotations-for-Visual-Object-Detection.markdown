---
layout: post
title:  "Crowdsourcing Annotations for Visual Object Detection"
date:   2019-04-24 23:52:32 +0900
categories: welcome
---

Today, I've read a paper about anotation.
The title is `"Crowdsourcing Annotations for Visual Object Detection"`.


What it is doing isn't super new, just saying that dividing annotation work into three parts will save time as well as improve accuracy.

* Drawing: A worker draws one bounding box around one instance of the given image.
* Quality verification: A second worker verifies whether a bounding box is correctly drawn.
* Coverage verification: A third worker verifies whether all object instances have bounding boxes.

The architecture of their task division goes like this.

<img src="/assets/images/architecture1.png" width="75%">


The results are kind of obvious, but I'll post them.
<img src="/assets/images/results1.png" width="100%">
