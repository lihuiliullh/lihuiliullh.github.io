---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

### Books

1. **Neural Symbolic Knowledge Graph Reasoning: A Pathway Towards Neural Symbolic AI.** *Springer, 2026.* Lihui Liu, Hanghang Tong.

### Journals

1. **Unifying Knowledge in Agentic LLMs: Concepts, Methods, and Recent Advancements.** *KDD Exploration, 2025.* Lihui Liu, Kai Shu.
1. **Neural-Symbolic Reasoning over Knowledge Graphs: A Survey from a Query Perspective.** *KDD Exploration, 2025.* Lihui Liu, Zihao Wang, Hanghang Tong.
1. **Knowledge Graph Comparative Reasoning for Fact Checking: Problem Definition and Algorithms.** *Data Engineering, 2022.* Lihui Liu, Ruining Zhao, Boxin Du, Yi Ren Fung, Heng Ji, Jiejun Xu, Hanghang Tong.

### Preprint


1. **Personalized Large Language Models for Healthcare: A Comprehensive Survey**
1. **LLM Agents for Healthcare: Concepts, Methods, and Applications**
1. **A Survey of Large Language Models in Education: Perspectives from Students and Teachers**
1. **A Survey of Unifying Large Language Models with Graph Learning: Concepts, Methods, and Recent Advancements for Text-attributed Graph**
1. **A Survey of Process Reward Models in the Lifecycle of Large Language Models**

1. **Universal Knowledge Base: A New Generation of Knowledge Management in the Era of Large Language Models**
1. **HiKGC: Hyper-Relational Knowledge Graphs Completion with Neural Logical Operators**
1. **Robust Conformal Consensus: Multi-Agent LLM-as-a-Judge Interval Evaluation with Conformal Prediction**

1. **Scaling Enterprise Agent Deployment: A Survey of LLM-Based Operational Grounding Construction**
1. **Reinforcement Learning for Large Language Model Post-Training, Reasoning, and Data Generation: A Survey**

### Conferences

1. **RLKGC: Reinforcement Learning Retrieval with Large Language Models for Knowledge Graph Completion.** *PAKDD, 2026.* Urshi Barua Teya, Kai Shu, Lihui Liu.
1. **Neural-Symbolic Logic Query Answering in Non-Euclidean Space.** *PAKDD, 2026.* Lihui Liu.
1. **Prompt-tuning with Attribute Guidance for Low-resource Entity Matching.** *PAKDD, 2026.* Lihui Liu, Carl Yang.
1. **MixRAG: Mixture-of-Experts Retrieval-Augmented Generation for Textual Graph Understanding and Question Answering.** *WWW, 2026.* Lihui Liu, Jiayuan Ding, Subhabrata Mukherjee, Carl Yang.
1. **MORGAN: To Bridge Mixture of Experts and Spectral Graph Neural Network.** *AAAI, 2026.* Lihui Liu, Yuchen Yan.
1. **HyperKGR: Knowledge Graph Reasoning in Hyperbolic Space with Graph Neural Network Encoding Symbolic Path.** *EMNLP, 2025.* Lihui Liu.
1. **Monte Carlo Tree Search for Graph Reasoning in Large Language Model Agents.** *CIKM, 2025.* Lihui Liu.
1. **Few-Shot Knowledge Graph Completion via Transfer from Similar Tasks.** *CIKM, 2025.* Lihui Liu, Zihao Wang, Dawei Zhou, Ruijie Wang, Yuchen Yan, Bo Xiong, Sihong He, Hanghang Tong.
1. **EviNet: Towards Open-World Graph Learning via Evidential Reasoning Network.** *KDD, 2025.* Weijie Guan, Jian Kang, Lihui Liu, Dawei Zhou.
1. **R-KBQA: Revise-once correction for Generate-then-Retrieve KBQA.** *BigData, 2025.* Bowen Huang, Lihui Liu.
1. **TUCKET: A Tensor Time Series Data Structure for Efficient and Accurate Factor Analysis over Time Ranges.** *VLDB, 2024.* Ruzhong Qiu, Jun-Gi Jang, Xiao Lin, Lihui Liu, Hanghang Tong.
1. **Conversational Question Answering with Reformulations over Knowledge Graph.** *ACL 2024 Findings.* Lihui Liu, Blaine Hill, Boxin Du, Hanghang Tong. [paper](https://arxiv.org/abs/2312.17269)
1. **Can contrastive learning refine embedding.** *ESWC, 2024.* Lihui Liu, Jimha Kim, Vidit Bansal.
1. **Ginkgo-P: General Illustrations of Knowledge Graphs for Openness as a Platform.** *WSDM, 2024.* Blaine Hill, Lihui Liu, Hanghang Tong.
1. **PaCEr: Positional Embedding Meets Structural Embedding of Graph Representation Learning.** *WWW, 2024.* Yuchen Yan, Yongyi Hu, Qinghai Zhou, Lihui Liu, Hanghang Tong.
1. **Reconciling Competing Sampling Strategies of Network Embedding.** *NeurIPS, 2023.* Yuchen Yan, Baoyu Jing, Lihui Liu, Ruijie Wang, Jinning Li, Tarek Abdelzaher, Hanghang Tong. [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/15dc2344ea9bdc01ffb8bb2d692e4018-Paper-Conference.pdf)
1. **Knowledge Graph Question Answering with Ambiguous Query.** *WWW, 2023.* Lihui Liu, Yuzhong Chen, Mahashweta Das, Hao Yang, Hanghang Tong. [paper](https://dl.acm.org/doi/abs/10.1145/3543507.3583316)
1. **Comparative Reasoning for Knowledge Graph Fact Checking.** *BigData, 2022.* Lihui Liu, Houxiang Ji, Jiejun Xu, Hanghang Tong. [paper](https://ieeexplore.ieee.org/document/10020991)
1. **Joint Knowledge Graph Completion and Question Answering.** *KDD, 2022.* Lihui Liu, Boxin Du, Jiejun Xu, Yinglong Xia, Hanghang Tong. [paper](https://dl.acm.org/doi/abs/10.1145/3534678.3539289)
1. **ABM: Attention-based Message Passing Network for Knowledge Graph Completion.** *BigData, 2022.* Weikai Xu, Lihui Liu, Hanghang Tong. [paper](https://ieeexplore.ieee.org/document/10021003)
1. **KomPare: A Knowledge Graph Comparative Reasoning System.** *KDD, 2021.* Lihui Liu, Boxin Du, Fung Yi, Heng Ji, Jiejun Xu, Hanghang Tong. [paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467128)
1. **Neural-Answering Logical Queries on Knowledge Graphs.** *KDD, 2021.* Lihui Liu, Boxin Du, Heng Ji, Chengxiang Zhai, Hanghang Tong. [paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467375)
1. **Sylvester Tensor Equation for Multi-Way Association.** *KDD, 2021.* Boxin Du, Lihui Liu, and Hanghang Tong. [paper](https://dl.acm.org/doi/abs/10.1145/3447548.3467336)
1. **Dynamic Knowledge Graph Alignment.** *AAAI, 2021.* Yuchen Yan, Lihui Liu, Hanghang Tong. [paper](https://ojs.aaai.org/index.php/AAAI/article/view/16585)
1. **A Knowledge Graph Reasoning Prototype.** *NeurIPS Demo, 2020.* Lihui Liu, Hanghang Tong.
1. **CANON: Complex Analytics of Network of Networks for Modeling Adversarial Activities.** *BigData, 2020.* S. Roach, C. Ni, A. Kopylov, T. Lu, J. Xu, S. Zhang, B. Du, Dawei Zhou, Jun Wu, Lihui Liu, Yuchen Yan, Jingrui He, Hanghang Tong.
1. **Approximated Attributed Subgraph Matching.** *BigData, 2019.* Lihui Liu, Boxin Du, Jiejun Xu, Hanghang Tong. [paper](https://ieeexplore.ieee.org/document/9006525)
