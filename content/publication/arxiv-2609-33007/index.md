---
title: 'CAPEX: Efficiently Distilling Foundation Model Behavior into Deployable Robot Policies through Experience-Adaptive Reasoning'
authors:
  - Shivam Aarya
  - Zhang Xi-Jia
  - Chengyue Huang
  - admin
  - Huishu Xue
  - Hrishit Leen
  - Roman Yakunin
  - Animesh Garg
  - Zsolt Kira
date: '2026-09-26T00:00:00Z'
doi: ''
publishDate: '2026-09-26T00:00:00Z'
publication_types: ['article']
publication: 'arXiv preprint arXiv:2609.33007'
publication_short: 'arXiv:2609.33007'
abstract: "Robot learning has largely relied on human-teleoperated demonstrations to acquire effective learnable behaviors. However, human-operated data collection processes can be unintuitive, difficult to scale, and inherently asynchronous. We explore an alternative: distilling physical behavior from general-purpose multimodal foundation models into deployable robot policies by using the foundation model itself as an autonomous demonstrator. While sufficiently capable models can generate successful zero-shot manipulation trajectories, repeatedly invoking them during physical execution is slow and expensive, limiting their utility as scalable data generators. As a solution, we introduce CAPEX, an experience-conditioned demonstration collection framework that uses execution experience from previous attempts to adapt how frequently the foundation model must observe, reason, and replan. We evaluate across RoboCasa tasks and on physical Franka and bimanual YAM-arm platforms, measuring task success, model calls, token usage, collection time, and cost. We further train Diffusion Policy and ACT on matched sets of human-teleoperated and foundation-model-generated demonstrations to evaluate the downstream learning value of autonomously collected data. We find that CAPEX increases the number of successful demonstrations by 4.3x while reducing the cost per successful demonstration by 80%. Policies trained on CAPEX-generated data approach the performance of those trained on matched human demonstrations; with longer training, this gap largely closes for policies trained from scratch. These results suggest that foundation models can serve as scalable sources of reusable robot experience."
summary: 'An experience-adaptive framework that uses a multimodal foundation model as an autonomous robot demonstrator to collect deployable policy training data at a fraction of the cost.'
tags:
  - Robotics
  - Foundation Models
featured: true
links:
  - name: arXiv
    url: https://arxiv.org/abs/2609.33007
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
image:
  caption: ''
  focal_point: ''
  preview_only: false
projects: []
slides: ''
---
