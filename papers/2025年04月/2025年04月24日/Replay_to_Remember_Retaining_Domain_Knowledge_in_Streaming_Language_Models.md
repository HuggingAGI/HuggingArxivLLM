# 回放以铭记：流式语言模型中保留领域知识

发布时间：2025年04月24日

`LLM理论` `领域适应`

> Replay to Remember: Retaining Domain Knowledge in Streaming Language Models

# 摘要

> 大型语言模型 (LLMs) 的持续学习常面临灾难性遗忘的挑战，即接触新数据后，原有知识逐渐退化。尽管已有回放缓存和参数高效微调技术（如 LoRA）等方法，但少有研究探讨在严格计算和数据流约束下实现实时领域自适应。本文提出了一种结合 LoRA 和最小回放机制的轻量级方法，并在医疗问答、遗传学和法律三个领域的真实流式场景中进行了验证。通过困惑度、语义相似性和基于 GPT 的人类似性评估指标，我们量化了模型在时间维度上的适应、遗忘与恢复能力。实验结果表明，尽管灾难性遗忘难以避免，但即使是最小的回放机制也能显著稳定并部分恢复特定领域的知识。这项研究为在资源受限的现实场景中部署可适应的 LLM 提供了重要参考。

> Continual learning in large language models (LLMs) typically encounters the critical challenge of catastrophic forgetting, where previously acquired knowledge deteriorates upon exposure to new data. While techniques like replay buffers and parameter-efficient tuning (e.g., Low-Rank Adaptation or LoRA) have been proposed, few studies investigate real-time domain adaptation under strict computational and data-stream constraints. In this paper, we demonstrate a lightweight method combining LoRA and a minimal replay mechanism in a realistic streaming setting across three diverse knowledge domains: medical question answering, genetics, and law. Using perplexity, semantic similarity, and GPT-based human-like evaluation metrics, we quantify the model's adaptation, forgetting, and recovery over time. Our experiments reveal that while catastrophic forgetting naturally occurs, even minimal replay significantly stabilizes and partially restores domain-specific knowledge. This study contributes practical insights for deploying adaptable LLMs in resource-constrained, real-world scenarios.

[Arxiv](https://arxiv.org/abs/2504.17780)