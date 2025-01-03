# 基于过程监督的代码生成策略优化

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何通过强化学习（RL）和过程奖励模型（PRM）来提升大型语言模型（LLM）在代码生成任务中的性能。虽然涉及强化学习，但其核心目标是优化LLM在代码生成中的应用，因此应归类为“LLM应用”。` `软件开发`

> Process Supervision-Guided Policy Optimization for Code Generation

# 摘要

> # 强化学习与单元测试反馈的结合虽然提升了LLMs的代码生成能力，但其依赖的稀疏奖励机制限制了学习效率。为解决这一问题，我们提出了过程奖励模型（PRM），在代码生成过程中提供密集的行级反馈，模拟人类代码精炼过程并给予即时指导。通过多种策略训练PRM并将其集成到RL框架中，我们发现PRM作为密集奖励和价值函数初始化能显著提升性能。实验结果显示，PRM有效增强了RL驱动的代码生成，特别是在长期任务中，我们内部LLM的通过率在LiveCodeBench上从28.2%提升至29.8%，内部基准测试中从31.8%提升至35.8%。

> Reinforcement Learning (RL) with unit test feedback has enhanced large language models (LLMs) code generation, but relies on sparse rewards provided only after complete code evaluation, limiting learning efficiency and incremental improvements. When generated code fails all unit tests, no learning signal is received, hindering progress on complex tasks. To address this, we propose a Process Reward Model (PRM) that delivers dense, line-level feedback on code correctness during generation, mimicking human code refinement and providing immediate guidance. We explore various strategies for training PRMs and integrating them into the RL framework, finding that using PRMs both as dense rewards and for value function initialization significantly boosts performance. Our approach increases our in-house LLM's pass rate from 28.2% to 29.8% on LiveCodeBench and from 31.8% to 35.8% on our internal benchmark. Our experimental results highlight the effectiveness of PRMs in enhancing RL-driven code generation, especially for long-horizon scenarios.

[Arxiv](https://arxiv.org/abs/2410.17621)