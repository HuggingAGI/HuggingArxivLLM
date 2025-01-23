# Kimi k1.5: 利用LLMs扩展强化学习

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了通过强化学习（RL）训练多模态大型语言模型（LLM）的实践，并展示了其在多个基准和模态上的最先进推理性能。论文的重点在于如何通过RL扩展和改进LLM的训练和应用，属于LLM在实际应用中的优化和扩展，因此分类为LLM应用。` `人工智能`

> Kimi k1.5: Scaling Reinforcement Learning with LLMs

# 摘要

> # 摘要
通过下一个词预测进行语言模型预训练已被证明对扩展计算有效，但受限于可用训练数据的数量。扩展强化学习（RL）为人工智能的持续改进开辟了一个新的维度，承诺大型语言模型（LLMs）可以通过学习探索奖励来扩展其训练数据。然而，之前发表的工作并未产生有竞争力的结果。鉴于此，我们报告了Kimi k1.5的训练实践，这是我们最新的多模态LLM，使用RL进行训练，包括其RL训练技术、多模态数据配方和基础设施优化。长上下文扩展和改进的策略优化方法是我们方法的关键要素，它建立了一个简单有效的RL框架，而不依赖于更复杂的技术，如蒙特卡洛树搜索、价值函数和过程奖励模型。值得注意的是，我们的系统在多个基准和模态上实现了最先进的推理性能——例如，AIME上的77.5，MATH 500上的96.2，Codeforces上的94百分位，MathVista上的74.9——与OpenAI的o1相匹配。此外，我们提出了有效的长到短方法，使用长链思维（CoT）技术来改进短链思维模型，产生了最先进的短链思维推理结果——例如，AIME上的60.8，MATH500上的94.6，LiveCodeBench上的47.3——大幅超越了现有的短链思维模型，如GPT-4o和Claude Sonnet 3.5（高达+550%）。

> Language model pretraining with next token prediction has proved effective for scaling compute but is limited to the amount of available training data. Scaling reinforcement learning (RL) unlocks a new axis for the continued improvement of artificial intelligence, with the promise that large language models (LLMs) can scale their training data by learning to explore with rewards. However, prior published work has not produced competitive results. In light of this, we report on the training practice of Kimi k1.5, our latest multi-modal LLM trained with RL, including its RL training techniques, multi-modal data recipes, and infrastructure optimization. Long context scaling and improved policy optimization methods are key ingredients of our approach, which establishes a simplistic, effective RL framework without relying on more complex techniques such as Monte Carlo tree search, value functions, and process reward models. Notably, our system achieves state-of-the-art reasoning performance across multiple benchmarks and modalities -- e.g., 77.5 on AIME, 96.2 on MATH 500, 94-th percentile on Codeforces, 74.9 on MathVista -- matching OpenAI's o1. Moreover, we present effective long2short methods that use long-CoT techniques to improve short-CoT models, yielding state-of-the-art short-CoT reasoning results -- e.g., 60.8 on AIME, 94.6 on MATH500, 47.3 on LiveCodeBench -- outperforming existing short-CoT models such as GPT-4o and Claude Sonnet 3.5 by a large margin (up to +550%).

[Arxiv](https://arxiv.org/abs/2501.12599)