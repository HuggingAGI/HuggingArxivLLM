# GeoLLaVA-8K：提升遥感多模态大语言模型至8K分辨率

发布时间：2025年05月27日

`LLM应用

摘要中提到的论文主要专注于在遥感领域应用多模态大型语言模型，开发了一个专门针对遥感数据的模型，并在特定任务中取得了先进成果。这属于LLM的应用层面。` `地理信息`

> GeoLLaVA-8K: Scaling Remote-Sensing Multimodal Large Language Models to 8K Resolution

# 摘要

> 超高分辨率 (UHR) 遥感 (RS) 图像为地球观测提供了宝贵的数据，但因两个关键瓶颈给现有的多模态基础模型带来了巨大挑战：首先是 UHR 训练数据的稀缺性，其次是因图像尺寸过大导致的“token爆炸”问题。为了解决数据不足的问题，我们推出了 SuperRS-VQA（平均分辨率 8,376×8,376）和 HighRS-VQA（平均分辨率 2,000×1,912），这是目前分辨率最高的 RS 视觉语言数据集，涵盖了 22 个真实世界的对话任务。针对“token爆炸”，我们发现 RS 图像中存在显著冗余：关键信息集中在少量以对象为中心的 token 中，而剪裁背景 token（例如海洋或森林）甚至可以提升性能。基于这些发现，我们提出了两种策略：背景 Token 剪裁和锚定 Token 选择，以减少内存占用同时保留关键语义。结合这些技术，我们开发了 GeoLLaVA-8K，这是首个专注于 RS 的多模态大型语言模型，能够处理高达 8K×8K 分辨率的输入，基于 LLaVA 框架构建。在 SuperRS-VQA 和 HighRS-VQA 上进行训练后，GeoLLaVA-8K 在 XLRS-Bench 上取得了新的最先进水平。

> Ultra-high-resolution (UHR) remote sensing (RS) imagery offers valuable data for Earth observation but pose challenges for existing multimodal foundation models due to two key bottlenecks: (1) limited availability of UHR training data, and (2) token explosion caused by the large image size. To address data scarcity, we introduce SuperRS-VQA (avg. 8,376$\times$8,376) and HighRS-VQA (avg. 2,000$\times$1,912), the highest-resolution vision-language datasets in RS to date, covering 22 real-world dialogue tasks. To mitigate token explosion, our pilot studies reveal significant redundancy in RS images: crucial information is concentrated in a small subset of object-centric tokens, while pruning background tokens (e.g., ocean or forest) can even improve performance. Motivated by these findings, we propose two strategies: Background Token Pruning and Anchored Token Selection, to reduce the memory footprint while preserving key semantics.Integrating these techniques, we introduce GeoLLaVA-8K, the first RS-focused multimodal large language model capable of handling inputs up to 8K$\times$8K resolution, built on the LLaVA framework. Trained on SuperRS-VQA and HighRS-VQA, GeoLLaVA-8K sets a new state-of-the-art on the XLRS-Bench.

[Arxiv](https://arxiv.org/abs/2505.21375)