# 两阶段表示学习分析痴呆症患者运动行为动态

发布时间：2025年02月13日

`LLM应用`

> Two-Stage Representation Learning for Analyzing Movement Behavior Dynamics in People Living with Dementia

# 摘要

> 远程医疗监护中，时间序列表示学习从高频数据中揭示关键患者行为模式。针对痴呆症患者的居家活动数据，我们提出了一种两阶段自监督学习方法，专门用于挖掘低秩结构。第一阶段将时间序列活动转换为由预训练语言模型编码的文本序列，通过基于PageRank的方法构建丰富且高维的潜在状态空间。该PageRank向量捕捉潜在状态转移，将复杂行为数据压缩为简洁形式，提升可解释性。此低秩表示不仅增强了模型可解释性，还促进了聚类和转移分析，揭示与临床指标（如MMSE和ADAS-COG评分）相关的关键行为模式。研究结果表明，该框架在支持认知状态预测、个性化护理干预及大规模健康管理方面具有潜力。

> In remote healthcare monitoring, time series representation learning reveals critical patient behavior patterns from high-frequency data. This study analyzes home activity data from individuals living with dementia by proposing a two-stage, self-supervised learning approach tailored to uncover low-rank structures. The first stage converts time-series activities into text sequences encoded by a pre-trained language model, providing a rich, high-dimensional latent state space using a PageRank-based method. This PageRank vector captures latent state transitions, effectively compressing complex behaviour data into a succinct form that enhances interpretability. This low-rank representation not only enhances model interpretability but also facilitates clustering and transition analysis, revealing key behavioral patterns correlated with clinicalmetrics such as MMSE and ADAS-COG scores. Our findings demonstrate the framework's potential in supporting cognitive status prediction, personalized care interventions, and large-scale health monitoring.

[Arxiv](https://arxiv.org/abs/2502.09173)