# THOR：面向数学推理的强化学习（RL）工具集成式分层优化

发布时间：2025年09月17日

`强化学习` `基础理论`

> THOR: Tool-Integrated Hierarchical Optimization via RL for Mathematical Reasoning

# 摘要

> 大型语言模型（LLMs）在数学推理领域已取得显著进步，但面对数值计算、形式符号操作等高精度任务时，依旧力不从心。集成外部工具成为了填补这一短板的有效途径，前景广阔。尽管近年来有所突破，现有方法仍面临三大核心挑战：工具集成推理数据的构建、细粒度优化的实施以及推理能力的增强。为解决这些问题，我们提出THOR（基于强化学习的工具集成分层优化框架）。首先，我们开发了TIRGen——一个基于多智能体演员-评论家的生成管道，用于构建高质量工具集成推理路径数据集。该数据集与策略高度对齐，并能在各类模型中实现良好泛化。其次，针对细粒度分层优化需求，我们提出了一种强化学习策略，可同时优化轨迹级问题求解与步骤级代码生成。这一设计源于我们的核心发现：中间工具调用的成功与否，是最终答案正确性的强预测指标。最后，THOR内置了自校正机制，能够利用工具即时反馈，在推理过程中动态修正错误推理路径。我们的方法泛化能力突出，在推理型与非推理型模型中均表现优异。在多个数学基准测试中，该方法为同规模模型带来了当前最优性能；在代码基准测试中，也实现了持续改进。相关代码将在https://github.com/JingMog/THOR开源发布。

> Large Language Models (LLMs) have made remarkable progress in mathematical reasoning, but still continue to struggle with high-precision tasks like numerical computation and formal symbolic manipulation. Integrating external tools has emerged as a promising approach to bridge this gap. Despite recent advances, existing methods struggle with three key challenges: constructing tool-integrated reasoning data, performing fine-grained optimization, and enhancing inference. To overcome these limitations, we propose THOR (Tool-Integrated Hierarchical Optimization via RL). First, we introduce TIRGen, a multi-agent actor-critic-based pipeline for constructing high-quality datasets of tool-integrated reasoning paths, aligning with the policy and generalizing well across diverse models. Second, to perform fine-grained hierarchical optimization, we introduce an RL strategy that jointly optimizes for both trajectory-level problem solving and step-level code generation. This is motivated by our key insight that the success of an intermediate tool call is a strong predictor of the final answer's correctness. Finally, THOR incorporates a self-correction mechanism that leverages immediate tool feedback to dynamically revise erroneous reasoning paths during inference. Our approach demonstrates strong generalization across diverse models, performing effectively in both reasoning and non-reasoning models. It further achieves state-of-the-art performance for models of a similar scale on multiple mathematical benchmarks, while also delivering consistent improvements on code benchmarks. Our code will be publicly available at https://github.com/JingMog/THOR.

[Arxiv](https://arxiv.org/abs/2509.13761)