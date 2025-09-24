# MiniCPM-V 4.5：匠心打造高效多模态大模型——架构、数据与训练方案的融合之道

发布时间：2025年09月16日

`LLM应用` `基础理论`

> MiniCPM-V 4.5: Cooking Efficient MLLMs via Architecture, Data, and Training Recipe

# 摘要

> 多模态大型语言模型（MLLMs）发展迅猛，已成为人工智能领域的前沿方向。但训练与推理效率不足，已成为制约其普及与规模化应用的核心瓶颈。为此，我们推出了MiniCPM-V 4.5——一款80亿参数的模型，专为高效能与强性能设计。我们从模型架构、数据策略和训练方法三大维度进行了核心改进：一是采用统一的3D-Resampler架构，实现图像与视频的高度紧凑编码；二是提出文档知识与文本识别的统一学习范式，省去繁重的数据工程；三是设计混合强化学习策略，以兼顾短推理与长推理能力。OpenCompass综合测评结果显示，MiniCPM-V 4.5性能超越了GPT-4o-latest等主流专有模型，以及Qwen2.5-VL 72B等规模更大的开源模型。尤为关键的是，其高性能背后是极致的效率优势：在主流VideoMME视频基准测试中，MiniCPM-V 4.5在300亿参数以下模型中性能领先，而GPU内存占用仅为Qwen2.5-VL 7B的46.7%，推理耗时更是仅为其8.7%。

> Multimodal Large Language Models (MLLMs) are undergoing rapid progress and represent the frontier of AI development. However, their training and inference efficiency have emerged as a core bottleneck in making MLLMs more accessible and scalable. To address the challenges, we present MiniCPM-V 4.5, an 8B parameter model designed for high efficiency and strong performance. We introduce three core improvements in model architecture, data strategy and training method: a unified 3D-Resampler model architecture for highly compact encoding over images and videos, a unified learning paradigm for document knowledge and text recognition without heavy data engineering, and a hybrid reinforcement learning strategy for proficiency in both short and long reasoning modes. Comprehensive experimental results in OpenCompass evaluation show that MiniCPM-V 4.5 surpasses widely used proprietary models such as GPT-4o-latest, and significantly larger open-source models such as Qwen2.5-VL 72B. Notably, the strong performance is achieved with remarkable efficiency. For example, on the widely adopted VideoMME benchmark, MiniCPM-V 4.5 achieves state-of-the-art performance among models under 30B size, using just 46.7\% GPU memory cost and 8.7\% inference time of Qwen2.5-VL 7B.

[Arxiv](https://arxiv.org/abs/2509.18154)