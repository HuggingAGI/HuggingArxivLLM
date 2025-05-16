# # J1: 利用强化学习激发 LLM 作为裁判的思考能力

发布时间：2025年05月15日

`LLM理论

理由：这篇论文探讨了如何通过强化学习训练大型语言模型（LLM）作为评判模型，以提升其评估能力。研究集中在模型的训练方法、奖励策略和结构优化上，属于LLM理论的研究范畴。` `人工智能` `人工智能`

> J1: Incentivizing Thinking in LLM-as-a-Judge via Reinforcement Learning

# 摘要

> AI 的发展受限于评估质量，而强大的 LLM 作为评判模型是核心解决方案。更强大的链式推理能力提升了判断能力，促使我们寻找训练这些模型进行思考的最佳方法。在这项工作中，我们引入了 J1，这是一种通过强化学习方法训练此类模型的方法。我们的方法将可验证和不可验证的提示转化为具有可验证奖励的判断任务，激励思考并缓解判断偏差。特别地，当在这些规模上进行训练时，我们的方法优于所有其他现有的 8B 或 70B 模型，包括从 DeepSeek-R1 蒸馏出的模型。J1 还优于 o1-mini，甚至在某些基准测试中优于 R1，尽管训练的是一个较小的模型。我们提供了分析和消融实验，比较了 Pairwise-J1 与 Pointwise-J1 模型、离线与在线训练方法、奖励策略、种子提示以及思考长度和内容的变化。我们发现，我们的模型通过学习概述评估标准、与自动生成的参考答案进行比较以及重新评估模型响应的正确性，做出了更好的判断。

> The progress of AI is bottlenecked by the quality of evaluation, and powerful LLM-as-a-Judge models have proved to be a core solution. Improved judgment ability is enabled by stronger chain-of-thought reasoning, motivating the need to find the best recipes for training such models to think. In this work we introduce J1, a reinforcement learning approach to training such models. Our method converts both verifiable and non-verifiable prompts to judgment tasks with verifiable rewards that incentivize thinking and mitigate judgment bias. In particular, our approach outperforms all other existing 8B or 70B models when trained at those sizes, including models distilled from DeepSeek-R1. J1 also outperforms o1-mini, and even R1 on some benchmarks, despite training a smaller model. We provide analysis and ablations comparing Pairwise-J1 vs Pointwise-J1 models, offline vs online training recipes, reward strategies, seed prompts, and variations in thought length and content. We find that our models make better judgments by learning to outline evaluation criteria, comparing against self-generated reference answers, and re-evaluating the correctness of model responses.

[Arxiv](https://arxiv.org/abs/2505.10320)