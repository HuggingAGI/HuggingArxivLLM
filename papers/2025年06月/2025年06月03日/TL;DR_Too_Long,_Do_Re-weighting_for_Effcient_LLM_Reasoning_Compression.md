# TL;DR: 内容过长，试试重新加权，让大语言模型推理压缩更高效

发布时间：2025年06月03日

`LLM应用

理由：这篇论文专注于优化大型语言模型的推理过程，提出了一种新的训练方法，旨在提高效率并减少输出长度，属于模型的应用层面改进。` `人工智能`

> TL;DR: Too Long, Do Re-weighting for Effcient LLM Reasoning Compression

# 摘要

> 大型语言模型（LLMs）借助强化学习和扩展链式思维（CoT）技术取得了显著进展。然而，在推理过程中生成极长输出时的高效语言推理挑战，正日益受到研究界关注。本研究提出了一种无需依赖复杂数据标注或多个模型插值的动态比例训练pipeline。我们持续平衡模型System-1与System-2数据的权重，消除冗余推理过程的同时保留推理能力。我们在DeepSeek-R1-Distill-7B和DeepSeek-R1-Distill-14B模型上进行了验证，并在难度各异的基准测试中测试。结果表明，我们的方法在保持推理准确性的同时，将输出令牌数量减少了近40%。我们的代码和数据即将公开。

> Large Language Models (LLMs) have recently achieved remarkable progress by leveraging Reinforcement Learning and extended Chain-of-Thought (CoT) techniques. However, the challenge of performing efficient language reasoning--especially during inference with extremely long outputs--has drawn increasing attention from the research community. In this work, we propose a dynamic ratio-based training pipeline that does not rely on sophisticated data annotations or interpolation between multiple models. We continuously balance the weights between the model's System-1 and System-2 data to eliminate redundant reasoning processes while preserving the model's reasoning capability. We validate our approach across models on DeepSeek-R1-Distill-7B and DeepSeek-R1-Distill-14B and on a diverse set of benchmarks with varying difficulty levels. Our method significantly reduces the number of output tokens by nearly 40% while maintaining the accuracy of the reasoning. Our code and data will be available soon.

[Arxiv](https://arxiv.org/abs/2506.02678)