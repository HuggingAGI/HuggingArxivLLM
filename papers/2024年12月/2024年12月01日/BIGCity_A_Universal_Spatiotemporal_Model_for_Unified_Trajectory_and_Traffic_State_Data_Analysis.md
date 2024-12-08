# BIGCity：一个用于统一轨迹和交通状态数据分析的通用时空模型

发布时间：2024年12月01日

`其他` `数据分析`

> BIGCity: A Universal Spatiotemporal Model for Unified Trajectory and Traffic State Data Analysis

# 摘要

> 典型的动态 ST 数据涵盖轨迹数据（体现个体层面的移动性）和交通状态数据（展现群体层面的移动性）。传统研究往往把轨迹和交通状态数据当作不同且独立的模式，每种模式都专为单一模式内的特定任务而设。然而，像导航应用这类现实场景，需要对轨迹和交通状态数据进行联合分析。把这些数据类型视作两个独立的领域，可能致使模型性能欠佳。尽管 ST 数据预训练和 ST 基础模型的最新进展意在为 ST 数据分析开发通用模型，但多数现有模型属于“多任务、单一数据模式”（MTSM），即它们能处理轨迹数据或交通状态数据中的多项任务，却无法同时处理两者。为填补这一空缺，本文推出了 BIGCity，这是首个用于 ST 数据分析的多任务、多数据模式（MTMD）模型。该模型瞄准了设计 MTMD ST 模型的两大关键挑战：（1）统一不同 ST 数据模式的表示，（2）统一异构 ST 分析任务。为攻克第一个挑战，BIGCity 引入了新颖的 ST 单元，以统一格式呈现轨迹和交通状态。另外，针对第二个挑战，BIGCity 采用了带有 ST 任务导向提示的可调大型模型，使其能够执行一系列异构任务，无需微调。在真实世界数据集上开展的大量实验表明，BIGCity 在 8 项任务中达成了最先进的性能，超越 18 个基线。据我们所知，BIGCity 是首个能够应对多种异构任务的轨迹和交通状态的模型。我们的代码可在 https://github.com/bigscity/BIGCity 获取。

> Typical dynamic ST data includes trajectory data (representing individual-level mobility) and traffic state data (representing population-level mobility). Traditional studies often treat trajectory and traffic state data as distinct, independent modalities, each tailored to specific tasks within a single modality. However, real-world applications, such as navigation apps, require joint analysis of trajectory and traffic state data. Treating these data types as two separate domains can lead to suboptimal model performance. Although recent advances in ST data pre-training and ST foundation models aim to develop universal models for ST data analysis, most existing models are "multi-task, solo-data modality" (MTSM), meaning they can handle multiple tasks within either trajectory data or traffic state data, but not both simultaneously. To address this gap, this paper introduces BIGCity, the first multi-task, multi-data modality (MTMD) model for ST data analysis. The model targets two key challenges in designing an MTMD ST model: (1) unifying the representations of different ST data modalities, and (2) unifying heterogeneous ST analysis tasks. To overcome the first challenge, BIGCity introduces a novel ST-unit that represents both trajectories and traffic states in a unified format. Additionally, for the second challenge, BIGCity adopts a tunable large model with ST task-oriented prompt, enabling it to perform a range of heterogeneous tasks without the need for fine-tuning. Extensive experiments on real-world datasets demonstrate that BIGCity achieves state-of-the-art performance across 8 tasks, outperforming 18 baselines. To the best of our knowledge, BIGCity is the first model capable of handling both trajectories and traffic states for diverse heterogeneous tasks. Our code are available at https://github.com/bigscity/BIGCity

[Arxiv](https://arxiv.org/abs/2412.00953)