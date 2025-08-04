# # R1-ACT：借助安全知识激活实现高效推理模型安全对齐

发布时间：2025年08月01日

`LLM理论` `人工智能安全` `模型安全`

> R1-ACT: Efficient Reasoning Model Safety Alignment by Activating Safety Knowledge

# 摘要

> 大型推理模型（LRMs）在复杂任务中表现出色，但近期研究表明，它们常常执行有害指令，引发严重安全担忧。本文深入研究了LRM的安全风险根源，发现模型本身具备足够的安全知识，但在推理时未能有效激活。基于此，我们提出了一种简单高效的后训练方法——R1-Act。该方法通过结构化的推理过程，显式触发安全知识，显著提升安全性能，同时保持推理能力。与之前方法相比，R1-Act表现更优，且仅需1,000个样本和单个RTX A6000 GPU上的90分钟训练。在多个LRM模型上的广泛实验验证了该方法的鲁棒性、可扩展性和实际效率。

> Although large reasoning models (LRMs) have demonstrated impressive capabilities on complex tasks, recent studies reveal that these models frequently fulfill harmful user instructions, raising significant safety concerns. In this paper, we investigate the underlying cause of LRM safety risks and find that models already possess sufficient safety knowledge but fail to activate it during reasoning. Based on this insight, we propose R1-Act, a simple and efficient post-training method that explicitly triggers safety knowledge through a structured reasoning process. R1-Act achieves strong safety improvements while preserving reasoning performance, outperforming prior alignment methods. Notably, it requires only 1,000 training examples and 90 minutes of training on a single RTX A6000 GPU. Extensive experiments across multiple LRM backbones and sizes demonstrate the robustness, scalability, and practical efficiency of our approach.

[Arxiv](https://arxiv.org/abs/2508.00324)