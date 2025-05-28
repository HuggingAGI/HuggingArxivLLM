# # 测试时学习的大型语言模型

发布时间：2025年05月26日

`LLM理论` `领域适应` `多语言`

> Test-Time Learning for Large Language Models

# 摘要

> 大型语言模型 (LLMs) 虽在广泛预训练中展现出了惊人能力，但面对专门领域和多样的语言变体（即分布偏移）时，仍存在关键局限。本文提出了一种名为 TLM 的测试时学习 (TTL) 范式，利用测试过程中的未标记数据，动态适应目标领域。具体而言，我们通过实证和理论分析发现，通过最小化测试数据的输入困惑度，可显著提升 LLMs 的预测精度。基于此，我们将测试时学习过程定义为输入困惑度最小化，实现自监督性能提升。进一步研究发现，困惑度高的样本对模型优化更具价值。为此，我们提出了一种样本高效学习策略，主动选择并强调这些高困惑度样本用于更新。为确保模型更新的稳定性和避免灾难性遗忘，我们采用低秩适应（LoRA）技术，实现轻量级更新同时保留原有知识。我们还引入了适应评估（AdaptEval）基准用于测试时学习评估，并通过实验验证，TLM 相较原始 LLM，在领域知识适应方面性能提升至少 20%。

> While Large Language Models (LLMs) have exhibited remarkable emergent capabilities through extensive pre-training, they still face critical limitations in generalizing to specialized domains and handling diverse linguistic variations, known as distribution shifts. In this paper, we propose a Test-Time Learning (TTL) paradigm for LLMs, namely TLM, which dynamically adapts LLMs to target domains using only unlabeled test data during testing. Specifically, we first provide empirical evidence and theoretical insights to reveal that more accurate predictions from LLMs can be achieved by minimizing the input perplexity of the unlabeled test data. Based on this insight, we formulate the Test-Time Learning process of LLMs as input perplexity minimization, enabling self-supervised enhancement of LLM performance. Furthermore, we observe that high-perplexity samples tend to be more informative for model optimization. Accordingly, we introduce a Sample Efficient Learning Strategy that actively selects and emphasizes these high-perplexity samples for test-time updates. Lastly, to mitigate catastrophic forgetting and ensure adaptation stability, we adopt Low-Rank Adaptation (LoRA) instead of full-parameter optimization, which allows lightweight model updates while preserving more original knowledge from the model. We introduce the AdaptEval benchmark for TTL and demonstrate through experiments that TLM improves performance by at least 20% compared to original LLMs on domain knowledge adaptation.

[Arxiv](https://arxiv.org/abs/2505.20633)