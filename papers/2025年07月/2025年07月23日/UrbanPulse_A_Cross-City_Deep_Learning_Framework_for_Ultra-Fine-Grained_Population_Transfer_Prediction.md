# UrbanPulse: 跨城市超精细人口流动预测的深度学习框架

发布时间：2025年07月23日

`LLM应用` `城市规划` `交通管理`

> UrbanPulse: A Cross-City Deep Learning Framework for Ultra-Fine-Grained Population Transfer Prediction

# 摘要

> 城市人口流动的精准预测对城市规划、交通管理和公共卫生至关重要。然而，现有方法存在诸多局限：传统模型依赖静态空间假设，深度学习模型在跨城泛化上表现不足，而大型语言模型（LLMs）不仅计算成本高昂，还难以捕捉空间结构。此外，许多方法通过聚类兴趣点（POIs）或限制覆盖范围来牺牲分辨率，这限制了它们在城市级分析中的实用性。我们提出了UrbanPulse，一个可扩展的深度学习框架，通过将每个POI视为独立节点，实现超精细、城市级的OD流预测。该框架结合了时间图卷积编码器和基于Transformer的解码器，以建模多尺度时空依赖关系。为了确保在城市环境中的强大泛化能力，UrbanPulse采用了三阶段转移学习策略：在大规模城市图上进行预训练、冷启动适应和强化学习微调。在来自美国加州三个大都市区的1亿多条清洗后的GPS记录上进行评估，UrbanPulse实现了最先进的准确性和可扩展性。通过高效的转移学习，UrbanPulse朝着在不同城市实现高分辨率、AI驱动的城市预测的实际部署迈出了关键一步。

> Accurate population flow prediction is essential for urban planning, transportation management, and public health. Yet existing methods face key limitations: traditional models rely on static spatial assumptions, deep learning models struggle with cross-city generalization, and Large Language Models (LLMs) incur high computational costs while failing to capture spatial structure. Moreover, many approaches sacrifice resolution by clustering Points of Interest (POIs) or restricting coverage to subregions, limiting their utility for city-wide analytics. We introduce UrbanPulse, a scalable deep learning framework that delivers ultra-fine-grained, city-wide OD flow predictions by treating each POI as an individual node. It combines a temporal graph convolutional encoder with a transformer-based decoder to model multi-scale spatiotemporal dependencies. To ensure robust generalization across urban contexts, UrbanPulse employs a three-stage transfer learning strategy: pretraining on large-scale urban graphs, cold-start adaptation, and reinforcement learning fine-tuning.Evaluated on over 103 million cleaned GPS records from three metropolitan areas in California, UrbanPulse achieves state-of-the-art accuracy and scalability. Through efficient transfer learning, UrbanPulse takes a key step toward making high-resolution, AI-powered urban forecasting deployable in practice across diverse cities.

[Arxiv](https://arxiv.org/abs/2507.17924)