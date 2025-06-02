# # BiasFilter：专为大型语言模型打造的推理时去偏见框架

发布时间：2025年05月28日

`LLM应用`

> BiasFilter: An Inference-Time Debiasing Framework for Large Language Models

# 摘要

> 在大型语言模型中缓解社会偏见已成为一项日益重要的研究目标。然而，现有去偏方法不仅成本高昂、效果有限，还难以扩展到大规模模型和开放生成任务。本文提出了一种名为BiasFilter的创新解决方案——这是一个模型不可知的推理时去偏框架，能够轻松集成到开源和基于API的LLMs中。与依赖平衡数据再训练或修改模型参数的方法不同，BiasFilter通过实时过滤生成输出来实现公平性。具体而言，它每隔几个token就会评估中间输出，维护一组候选延续，并根据公平奖励信号逐步完成生成。为了支持这一过程，我们构建了一个公平偏好数据集，并训练了一个隐式奖励模型，用于评估生成响应中token级别的公平性。实验结果表明，BiasFilter在多种LLMs上均能有效缓解社会偏见，同时保持了生成质量。

> Mitigating social bias in large language models (LLMs) has become an increasingly important research objective. However, existing debiasing methods often incur high human and computational costs, exhibit limited effectiveness, and struggle to scale to larger models and open-ended generation tasks. To address these limitations, this paper proposes BiasFilter, a model-agnostic, inference-time debiasing framework that integrates seamlessly with both open-source and API-based LLMs. Instead of relying on retraining with balanced data or modifying model parameters, BiasFilter enforces fairness by filtering generation outputs in real time. Specifically, it periodically evaluates intermediate outputs every few tokens, maintains an active set of candidate continuations, and incrementally completes generation by discarding low-reward segments based on a fairness reward signal. To support this process, we construct a fairness preference dataset and train an implicit reward model to assess token-level fairness in generated responses. Extensive experiments demonstrate that BiasFilter effectively mitigates social bias across a range of LLMs while preserving overall generation quality.

[Arxiv](https://arxiv.org/abs/2505.23829)