---
title: "Creating LEGO Figurines from Single Images"
collection: publications
permalink: /publications/LEGO-Figurines
excerpt: 'Jiahao Ge, Mingjun Zhou, Wenrui Bao, Hao Xu, and Chi-Wing Fu'
category: manuscripts
date: 2024-05-01
venue: 'ACM Transactions on Graphics (TOG) (SIGGRAPH 2024)'
paperurl: 'https://dl.acm.org/doi/10.1145/3658167'
citation: 'Jiahao Ge, Mingjun Zhou, Wenrui Bao, Hao Xu, and Chi-Wing Fu. 2024. Creating LEGO Figurines from Single Images. ACM Transactions on Graphics (TOG) 43, 4 (2024), 1-16'
---

Jiahao Ge, **Mingjun Zhou**, Wenrui Bao, Hao Xu, and Chi-Wing Fu

<a href='https://dl.acm.org/doi/10.1145/3658167'>Access paper here</a>

## Abstract
This paper presents a computational pipeline for creating personalized, physical LEGO®1 figurines from user-input portrait photos. The generated figurine is an assembly of coherently-connected LEGO® bricks detailed with uv-printed decals, capturing prominent features such as hairstyle, clothing style, and garment color, and also intricate details such as logos, text, and patterns. This task is non-trivial, due to the substantial domain gap between unconstrained user photos and the stylistically-consistent LEGO® figurine models. To ensure assemble-ability by LEGO® bricks while capturing prominent features and intricate details, we design a three-stage pipeline: (i) we formulate a CLIP-guided retrieval approach to connect the domains of user photos and LEGO® figurines, then output physically-assemble-able LEGO® figurines with decals excluded; (ii) we then synthesize decals on the figurines via a symmetric U-Nets architecture conditioned on appearance features extracted from user photos; and (iii) we next reproject and uv-print the decals on associated LEGO® bricks for physical model production. We evaluate the effectiveness of our method against eight hundred expert-designed figurines, using a comprehensive set of metrics, which include a novel GPT-4V-based evaluation metric, demonstrating superior performance of our method in visual quality and resemblance to input photos. Also, we show our method's robustness by generating LEGO® figurines from diverse inputs and physically fabricating and assembling several of them.
