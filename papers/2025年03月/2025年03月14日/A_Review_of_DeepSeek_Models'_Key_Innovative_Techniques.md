# # 深度求索模型核心技术深度解析

发布时间：2025年03月14日

`LLM理论` `人工智能`

> A Review of DeepSeek Models' Key Innovative Techniques

# 摘要

> DeepSeek-V3 和 DeepSeek-R1 是两款用于通用任务和推理的领先开源大语言模型，其性能可与 OpenAI 和 Anthropic 等公司的闭源模型相媲美，而训练成本却只有这些模型的九牛一毛。理解 DeepSeek 成功背后的关键创新技术，对推进 LLM 研究至关重要。本文将深入探讨推动这些模型显著有效性和效率的核心技术，包括对 Transformer 架构的改进、多头潜在注意力机制和专家混合机制等创新、多令牌预测、算法、框架和硬件的协同设计、基于组相对策略优化的算法、纯强化学习的后训练以及在监督微调和强化学习之间交替进行的迭代训练。此外，我们还指出了几个开放性问题，并强调了这一快速发展的领域中潜在的研究机会。

> DeepSeek-V3 and DeepSeek-R1 are leading open-source Large Language Models (LLMs) for general-purpose tasks and reasoning, achieving performance comparable to state-of-the-art closed-source models from companies like OpenAI and Anthropic -- while requiring only a fraction of their training costs. Understanding the key innovative techniques behind DeepSeek's success is crucial for advancing LLM research. In this paper, we review the core techniques driving the remarkable effectiveness and efficiency of these models, including refinements to the transformer architecture, innovations such as Multi-Head Latent Attention and Mixture of Experts, Multi-Token Prediction, the co-design of algorithms, frameworks, and hardware, the Group Relative Policy Optimization algorithm, post-training with pure reinforcement learning and iterative training alternating between supervised fine-tuning and reinforcement learning. Additionally, we identify several open questions and highlight potential research opportunities in this rapidly advancing field.

[Arxiv](https://arxiv.org/abs/2503.11486)