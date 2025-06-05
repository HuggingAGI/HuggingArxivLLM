# # EpiCoDe：通过外推能力与对比解码，增强模型性能表现

发布时间：2025年06月03日

`LLM应用` `数据稀缺`

> EpiCoDe: Boosting Model Performance Beyond Training with Extrapolation and Contrastive Decoding

# 摘要

> 大型语言模型（LLMs）的卓越性能依赖于大量高质量训练数据的获取。然而，标注数据的高昂成本常常限制了模型在下游任务中的能力。本文提出了一种创新方法 EpiCoDe，能够在无需额外训练的情况下提升模型在数据稀缺场景下的表现。我们首先通过模型外推技术增强微调模型，随后采用对比解码方法，通过比较外推模型和基础微调模型的 logit 分数，进一步降低预测误差。实验结果表明，在四个不同 LLM 上进行的三项任务中，EpiCoDe 一致优于现有方法，展现出显著且稳健的性能提升。此外，我们还提出了一种新的理论框架，揭示了数据稀缺场景下对比解码的内在机制，进一步帮助我们深入理解 EpiCoDe 的有效性。

> The remarkable performance of Large language models (LLMs) relies heavily on the availability of abundant high-quality training data. However, the high cost of acquiring annotated data often prevents models from obtaining capabilities to tackle downstream tasks. In this paper, we introduce a novel method, EpiCoDe that boosts model performance in data-scarcity scenarios without extra training. We first employ model extrapolation to enhance a finetuned model with its inferior version, and then adopt contrastive decoding to further reduce predicted errors, by comparing the logit scores given by the extrapolated and the vanilla finetuned model. Experiments across three tasks over four different LLMs show that EpiCoDe consistently outperforms existing methods with significant and robust improvement. We also propose a new theoretical framework to reveal the mechanism behind contrastive decoding in data-scarcity scenarios, which further helps us better understand the effectiveness of EpiCoDe.

[Arxiv](https://arxiv.org/abs/2506.03489)