# FedTDP: 通过联邦学习实现的隐私保护与统一轨迹数据准备框架

发布时间：2025年05月08日

`LLM应用` `城市规划`

> FedTDP: A Privacy-Preserving and Unified Framework for Trajectory Data Preparation via Federated Learning

# 摘要

> 轨迹数据记录了人们和车辆的时空移动模式，对交通优化和城市规划等应用至关重要。然而，噪声和不完整性等问题常常导致数据质量下降，进而影响轨迹分析的准确性，限制了这些应用的潜力。尽管轨迹数据准备（TDP）能够提升数据质量，但现有方法存在两大关键问题：一是未能解决数据隐私问题，特别是在禁止共享轨迹数据的联邦设置中；二是通常设计特定任务的模型，缺乏在多样化TDP场景中的通用性。

为克服这些挑战，我们提出FedTDP，一个隐私保护且统一的框架，利用大型语言模型（LLMs）在联邦环境中的TDP能力。具体来说，我们：（i）设计了一种轨迹隐私自动编码器，以确保数据传输安全并保护隐私；（ii）引入了轨迹知识增强器，以提升模型对TDP相关知识的学习，从而开发出面向TDP的LLMs；（iii）提出了联邦并行优化，通过减少数据传输并实现模型并行训练，从而提高训练效率。

在6个真实数据集和10个主流TDP任务上的实验表明，FedTDP在13个现有最优基线方法中表现一致优异。

> Trajectory data, which capture the movement patterns of people and vehicles over time and space, are crucial for applications like traffic optimization and urban planning. However, issues such as noise and incompleteness often compromise data quality, leading to inaccurate trajectory analyses and limiting the potential of these applications. While Trajectory Data Preparation (TDP) can enhance data quality, existing methods suffer from two key limitations: (i) they do not address data privacy concerns, particularly in federated settings where trajectory data sharing is prohibited, and (ii) they typically design task-specific models that lack generalizability across diverse TDP scenarios. To overcome these challenges, we propose FedTDP, a privacy-preserving and unified framework that leverages the capabilities of Large Language Models (LLMs) for TDP in federated environments. Specifically, we: (i) design a trajectory privacy autoencoder to secure data transmission and protect privacy, (ii) introduce a trajectory knowledge enhancer to improve model learning of TDP-related knowledge, enabling the development of TDP-oriented LLMs, and (iii) propose federated parallel optimization to enhance training efficiency by reducing data transmission and enabling parallel model training. Experiments on 6 real datasets and 10 mainstream TDP tasks demonstrate that FedTDP consistently outperforms 13 state-of-the-art baselines.

[Arxiv](https://arxiv.org/abs/2505.05155)