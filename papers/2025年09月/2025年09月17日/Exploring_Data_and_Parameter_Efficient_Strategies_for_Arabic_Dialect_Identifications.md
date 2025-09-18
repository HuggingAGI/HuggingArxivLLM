# 探索数据和参数高效的阿拉伯方言识别策略

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Exploring Data and Parameter Efficient Strategies for Arabic Dialect Identifications

# 摘要

> 本文探索了阿拉伯语方言识别（ADI）的多种数据高效与参数高效方法。具体来说，我们研究了多种软提示策略，如前缀调优、提示调优、P-tuning、P-tuning V2，以及LoRA重参数化。在数据高效策略上，我们通过硬提示结合零样本和少样本推理，分析了大型语言模型（LLMs）的方言识别能力。在参数高效的PEFT方法上，我们基于多个主要数据集，采用特定于阿拉伯语的编码器模型开展了实验。我们还分析了开源纯解码器模型、通用多语言模型（Phi-3.5）及特定于阿拉伯语的模型（SILMA）的n样本推理性能。结果显示，在少样本或零样本场景下，大型语言模型往往难以分辨方言间的细微差异；软提示编码器变体表现更优，而基于LoRA的微调模型性能最佳，甚至超越了全量微调。

> This paper discusses our exploration of different data-efficient and parameter-efficient approaches to Arabic Dialect Identification (ADI). In particular, we investigate various soft-prompting strategies, including prefix-tuning, prompt-tuning, P-tuning, and P-tuning V2, as well as LoRA reparameterizations. For the data-efficient strategy, we analyze hard prompting with zero-shot and few-shot inferences to analyze the dialect identification capabilities of Large Language Models (LLMs). For the parameter-efficient PEFT approaches, we conducted our experiments using Arabic-specific encoder models on several major datasets. We also analyzed the n-shot inferences on open-source decoder-only models, a general multilingual model (Phi-3.5), and an Arabic-specific one(SILMA). We observed that the LLMs generally struggle to differentiate the dialectal nuances in the few-shot or zero-shot setups. The soft-prompted encoder variants perform better, while the LoRA-based fine-tuned models perform best, even surpassing full fine-tuning.

[Arxiv](https://arxiv.org/abs/2509.13775)