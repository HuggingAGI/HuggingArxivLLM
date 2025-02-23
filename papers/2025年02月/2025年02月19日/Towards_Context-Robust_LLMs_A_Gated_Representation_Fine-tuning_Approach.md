# 构建上下文鲁棒的LLMs：基于门控机制的表征微调方法

发布时间：2025年02月19日

`LLM应用` `人工智能`

> Towards Context-Robust LLMs: A Gated Representation Fine-tuning Approach

# 摘要

> 大型语言模型（LLMs）结合外部上下文（如检索增强生成RAG）时，往往难以应对不完美的证据。它们容易过度依赖外部知识，导致模型易受误导或无用上下文的影响。为解决这一问题，我们提出了上下文鲁棒的LLMs概念，这类模型能够像人类认知一样，在内部知识与外部上下文之间实现有效平衡。具体而言，上下文鲁棒的LLMs应仅在内部知识不足时依赖外部上下文，识别内部与外部知识的矛盾，并忽略无用的上下文。为此，我们提出了一种轻量级、即插即用的门控表示微调方法——Grft。Grft包含两个关键组件：用于检测和过滤问题输入的门控机制，以及用于调整隐藏表示的低秩表示适配器。通过仅在不到200个示例上训练一个占模型大小0.0004%的轻量级干预函数，Grft能够有效引导LLMs实现上下文鲁棒的行为。

> Large Language Models (LLMs) enhanced with external contexts, such as through retrieval-augmented generation (RAG), often face challenges in handling imperfect evidence. They tend to over-rely on external knowledge, making them vulnerable to misleading and unhelpful contexts. To address this, we propose the concept of context-robust LLMs, which can effectively balance internal knowledge with external context, similar to human cognitive processes. Specifically, context-robust LLMs should rely on external context only when lacking internal knowledge, identify contradictions between internal and external knowledge, and disregard unhelpful contexts. To achieve this goal, we introduce Grft, a lightweight and plug-and-play gated representation fine-tuning approach. Grft consists of two key components: a gating mechanism to detect and filter problematic inputs, and low-rank representation adapters to adjust hidden representations. By training a lightweight intervention function with only 0.0004\% of model size on fewer than 200 examples, Grft can effectively adapt LLMs towards context-robust behaviors.

[Arxiv](https://arxiv.org/abs/2502.14100)