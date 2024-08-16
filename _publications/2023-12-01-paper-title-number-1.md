---
title: "Computational Design of LEGO Sketch Art"
collection: publications
category: manuscripts
permalink: /publications/LEGO-Sketch-Art
excerpt: 'Mingjun Zhou, Jiahao Ge, Hao Xu, and Chi-Wing Fu'
date: 2023-12-01
venue: 'ACM Transactions on Graphics (TOG) (SIGGRAPH Asia 2023)'
paperurl: 'https://dl.acm.org/doi/10.1145/3618306'
citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

**Mingjun Zhou**, Jiahao Ge, Hao Xu, and Chi-Wing Fu

<a href='https://dl.acm.org/doi/10.1145/3618306'>Access paper here</a>

## Abstract
This paper presents computational methods to aid the creation of LEGO®1 sketch models from simple input images. Beyond conventional LEGO® mosaics, we aim to improve the expressiveness of LEGO® models by utilizing LEGO® tiles with sloping and rounding edges, together with rectangular bricks, to reproduce smooth curves and sharp features in the input. This is a challenging task, as we have limited brick shapes to use and limited space to place bricks. Also, the search space is immense and combinatorial in nature. We approach the task by decoupling the LEGO® construction into two steps: first approximate the shape with a LEGO®-buildable contour then filling the contour polygon with LEGO® bricks. Further, we formulate this contour approximation into a graph optimization with our objective and constraints and effectively solve for the contour polygon that best approximates the input shape. Further, we extend our optimization model to handle multi-color and multi-layer regions, and formulate a grid alignment process and various perceptual constraints to refine the results. We employ our method to create a large variety of LEGO® models and compare it with humans and baseline methods to manifest its compelling quality and speed.

