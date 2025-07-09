# Transformer模型与推荐系统相遇：探索基于自注意力的序列推荐与微调LLMs的融合之道。

发布时间：2025年07月08日

`LLM应用` `推荐系统` `电子商务`

> When Transformers Meet Recommenders: Integrating Self-Attentive Sequential Recommendation with Fine-Tuned LLMs

# 摘要

> 自注意力序列推荐 (SASRec) 通过历史交互中的注意力机制，有效捕捉用户的长期偏好。与此同时，大型语言模型 (LLMs) 的崛起推动了基于 LLM 的推荐研究，这类方法充分利用了 LLM 强大的泛化和语言理解能力。然而，仅依赖文本提示的 LLM 通常缺乏实现高质量推荐所需的领域知识和协同信号。为解决这一问题，本研究提出了一种名为 SASRecLLM 的新颖框架，它将 SASRec 作为协同编码器，并与通过低秩适配 (LoRA) 微调的 LLM 相结合。通过映射层连接各组件以对齐其维度空间，并设计了三种针对性训练策略来优化混合架构。在多个数据集上的广泛实验表明，SASRecLLM 在冷启动和热启动场景下均显著优于现有强基线模型。这项工作通过提出一种模块化且有效的范式，将结构化的协同过滤与微调 LLM 的语义能力相结合，推动了基于 LLM 的推荐领域的发展。实现代码可在 GitHub 上获取：https://github.com/kechenkristin/RecLLM

> Self-Attentive Sequential Recommendation (SASRec) effectively captures long-term user preferences by applying attention mechanisms to historical interactions. Concurrently, the rise of Large Language Models (LLMs) has motivated research into LLM-based recommendation, which leverages their powerful generalization and language understanding capabilities. However, LLMs often lack the domain-specific knowledge and collaborative signals essential for high-quality recommendations when relying solely on textual prompts. To address this limitation, this study proposes SASRecLLM, a novel framework that integrates SASRec as a collaborative encoder with an LLM fine-tuned using Low-Rank Adaptation (LoRA). The components are connected via a mapping layer to align their dimensional spaces, and three targeted training strategies are designed to optimize the hybrid architecture. Extensive experiments on multiple datasets demonstrate that SASRecLLM achieves robust and consistent improvements over strong baselines in both cold-start and warm-start scenarios. This work advances the field of LLM-based recommendation by presenting a modular and effective paradigm for fusing structured collaborative filtering with the semantic power of fine-tuned LLMs. The implementation is available on GitHub: https://github.com/kechenkristin/RecLLM

[Arxiv](https://arxiv.org/abs/2507.05733)