---
layout:     post
title:      Research on trajectory data releasing method via differential privacy based on spatial partition
subtitle:   Qilong Han, Zuobin Xiong, and Kejia Zhang
date:       2018-11-11
author:     Zuobin Xiong
header-img: img/post-bg.jpg

catalog: true
tags:
    - Differential Privacy
    - Trajactory Data
---


**Published in Security and Communication Networks**

A number of security and privacy challenges of cyber system are arising due to the rapidly evolving scale and complexity of modern system and networks. The cyber system is a fundamental ingredient for Internet of Things (IoT) and smart city which are driven by huge amount of data. These data carry a lot of information for mining and analysis, especially trajectory data. If unprotected trajectory data is released, it may disclose user’s personal privacy, such as home, religion, and behavior mode, which will endanger their personal security. Until now, many methods for protecting trajectory information have been proposed. However, these methods have the following deficiencies: (i) they cannot defend against speculative attacks if the attacker’s background knowledge is maximized; (ii) when studying the problem, they made some strong assumptions that did not match the reality; (iii) the implementation algorithm is complicated and the time complexity is high, which means that data cannot be executed quickly when the amount is large. So, in this paper, we propose a spatial partition based method to publish trajectory data via differential privacy. First, by exponential mechanism, we divide location set at the same time into different partitions fast and accurately. Then we propose another effective method to release trajectory in a differential private manner. We design experiment based on the real-life dataset and compare it with existing method. The results show that the trajectory dataset released by our algorithm has better usability while ensuring privacy.
