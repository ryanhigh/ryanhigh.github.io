---
layout:     post
title:      Multi-Source Adversarial Sample Attack on Autonomous Vehicles
subtitle:   Zuobin Xiong, Honghui Xu, Wei Li, and Zhipeng Cai
date:       2021-02-14
author:     Zuobin Xiong
header-img: img/post-bg.jpg

catalog: true
tags:
    - Generative Adversarial Networks
    - Privacy Protection
    - Adversarial Attacks
---


**Published in IEEE Transactions on Vehicular Technology**

Deep learning has an impressive performance of object detection and classification for autonomous vehicles. Nevertheless, the essential vulnerability of deep learning models to adversarial samples makes the autonomous vehicles suffer severe security and safety issues. Although a number of works have been proposed to study adversarial samples, only a few of them are designated for the scenario of autonomous vehicles. Moreover, the state-of-the-art attack models only focus on a single data source without considering the correlation among multiple data sources. To fill this blank, we propose two multi-source adversarial sample attack models, including the parallel attack model and the fusion attack model to simultaneously attack the image and LiDAR perception systems in the autonomous vehicles. In the parallel attack model, adversarial samples are generated from the original image and LiDAR data separately. In the fusion attack model, the adversarial samples of image and LiDAR can be generated from a low-dimension vector at the same time by fully exploring data correlation for data fusion and adversarial sample generation. Through comprehensive real-data experiments, we validate that our proposed models are more powerful and efficient to break down the perception systems of autonomous vehicles compared with the state-of-the-art. Furthermore, we simulate possible attack scenarios in Vehicular Ad hoc Networks (VANETs) to evaluate the attack performance of our proposed methods.
