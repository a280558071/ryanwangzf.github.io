---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  -/paper
  -/papers
  -/researches
---

## Learning from Counterfactuals for Fair Recommender System
*Work in progress*

Fair machine learning has been an emerging topic recently, since existing unfair machine learning system appears to confront ethical even legal risk, as well as income or welfare loss. In this work, we study the unfairness caused by missing-notat-random (MNAR) phenomenon that is common in extensive tasks, e.g. ad display and medical treatment, and build our fair machine learning measures, namely Gini index (GI) and Global utility (GU) drawn from Economics. We further propose a novel Learning-from-Counterfactuals (LearnCF) framework for debiasing policy learning, and give its theoretical generalization bound. Besides, our analysis of asymptotics of the uniform policy, which is often employed to generate small randomized controlled trials (RCTs) for counterfactual learning, shows that it is far more than representative for users’ preference, when alternative action space is large. By contrast, our LearnCF is free of expensive RCTs, and empirically proved to benefit the policy utility (GU) and fairness (GI) at the same time.

## Unweighted Data Subsampling via Influence Function [[pdf]]((https://arxiv.org/abs/1912.01321)) [[code]](https://github.com/RyanWangZf/Influence_Subsampling)
*Published in **AAAI 2020**, 2019*

In the time of Big Data, training complex models on large-scale data sets is challenging, making it appealing to reduce data volume for saving computation resources by subsampling. Most previous works in subsampling
are weighted methods designed to help the performance of subset-model approach the full-set-model, hence the weighted methods have no chance to acquire a subsetmodel that is better than the full-set-model. However, we question that how can we achieve better model with less data? In this work, we propose a novel Unweighted Influence Data Subsampling (UIDS) method, and prove that the subset-model acquired through our method can outperform the full-set-model. Besides, we show that overly confident on a given test set for sampling is common in Influence-based subsampling methods, which can eventually cause our subset-model’s failure in outof-sample test. To mitigate it, we develop a probabilistic sampling scheme to control the worst-case risk over all distributions close to the empirical distribution. The experiment results demonstrate our methods superiority over existed subsampling methods in diverse tasks, such as text classification, image classification, click-through prediction, etc.

## RGB-Depth Camera for Semantic Segmentation on Construction Sites
*Submitted to **Automation in Construction**, under review*

Computer vision has been recently explored for a vision-based surveillance system on a construction site to detect workers, machines and third-party intrusion for reducing risk and improving productivity. However, mining deeper pattern for vision understanding of instances in the field, such as semantic segmentation, is hardly mentioned in the literature. The depth image, different from the commonly used RGB (Red, Green, and Blue) image, provides distance information of the objects, and is invariant to lighting or color variations. This paper proposes to employ RGB and depth images with a two-branch encoder-decoder network for semantic segmentation on construction sites. In order to make full use of depth and RGB images, an attention-based fusion layer is incorporated in the network to learn the representations for merging the features from the two branches. Our experiments show that the depth information can discriminate the edges between the instances and the background when they have similar textures, hence leads to better segmentation than using RGB images only. The test results, over the collected pairs of RGB and depth images from a construction site in Shenzhen, China, demonstrate that the fusion network can obtain $0.8383$ mIoU (mean intersection-over-union) and $92.64\%$ mPA (mean pixel accuracy). Besides, the network is capable of processing over $14$ frames per second, which is feasible in real applications.