# 扩展高效推理的语言模型

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要讨论了扩展定律的改进，特别是针对推理成本的考量，提出了推理感知的扩展定律和模型训练方法。这些内容属于对大型语言模型（LLM）的理论研究和优化，因此应归类为“LLM理论”。` `人工智能` `模型优化`

> Scaling Inference-Efficient Language Models

# 摘要

> # 摘要
扩展定律是预测大型语言模型性能的利器，但现有扩展定律对推理成本的考量不足。本文首先揭示了模型架构对推理延迟的影响，相同规模的模型延迟差异可达3.5倍。为此，我们改进了Chinchilla扩展定律，实现了模型参数、训练令牌数和架构的联合优化。鉴于训练损失相近的模型在下游任务中表现不一，我们还提出了一种基于新扩展定律的推理高效模型训练方法。通过大量实验，我们拟合并验证了推理感知扩展定律，训练了63个模型，参数范围从80M到1B，训练令牌数从1.6B到30B，模型形状各异。基于推理高效扩展定律和模型选择方法，我们推出了Morph-1B模型，在保持下游任务准确性的同时，推理延迟比开源模型提升了1.8倍，进一步优化了准确性与延迟的权衡。

> Scaling laws are powerful tools to predict the performance of large language models. However, current scaling laws fall short of accounting for inference costs. In this work, we first show that model architecture affects inference latency, where models of the same size can have up to 3.5x difference in latency. To tackle this challenge, we modify the Chinchilla scaling laws to co-optimize the model parameter count, the number of training tokens, and the model architecture. Due to the reason that models of similar training loss exhibit gaps in downstream evaluation, we also propose a novel method to train inference-efficient models based on the revised scaling laws. We perform extensive empirical studies to fit and evaluate our inference-aware scaling laws. We vary model parameters from 80M to 1B, training tokens from 1.6B to 30B, and model shapes, training a total of 63 models. Guided by our inference-efficient scaling law and model selection method, we release the Morph-1B model, which improves inference latency by 1.8x while maintaining accuracy on downstream tasks compared to open-source models, pushing the Pareto frontier of accuracy-latency tradeoff.

[Arxiv](https://arxiv.org/abs/2501.18107)