# QLLM：在多智能体强化学习中，是否真的需要混合网络来进行信用分配？

发布时间：2025年04月17日

`Agent` `多智能体强化学习` `人工智能`

> QLLM: Do We Really Need a Mixing Network for Credit Assignment in Multi-Agent Reinforcement Learning?

# 摘要

> 信用分配一直是多智能体强化学习（MARL）中的核心难题。以往研究主要通过集中训练与分散执行范式下的价值分解方法来解决这一问题，其中神经网络被用于近似个体Q值与全局Q值之间的非线性关系。尽管这些方法在各种基准任务中取得了显著成功，但仍存在诸多限制，包括贡献归属不精确、解释性不足以及在高维状态空间中扩展性差。

为应对这些挑战，我们提出了一种全新算法	extbf{QLLM}，该算法利用大型语言模型（LLMs）自动构建信用分配函数。具体而言，我们引入了	extbf{TFCAF}的概念，其中信用分配过程被表示为一种直接且富有表现力的非线性函数形式。此外，我们设计了一种定制的	extit{coder-evaluator}框架，用于指导LLMs生成、验证和优化可执行代码，从而显著缓解了推理过程中幻觉和浅层推理等问题。

在多个标准MARL基准上的大量实验表明，所提方法始终优于现有最先进的基线。此外，QLLM展现出强大的泛化能力，并与使用混合网络的多种MARL算法兼容，使其成为复杂多智能体场景中极具前景和 versatile 的解决方案。

> Credit assignment has remained a fundamental challenge in multi-agent reinforcement learning (MARL). Previous studies have primarily addressed this issue through value decomposition methods under the centralized training with decentralized execution paradigm, where neural networks are utilized to approximate the nonlinear relationship between individual Q-values and the global Q-value. Although these approaches have achieved considerable success in various benchmark tasks, they still suffer from several limitations, including imprecise attribution of contributions, limited interpretability, and poor scalability in high-dimensional state spaces. To address these challenges, we propose a novel algorithm, \textbf{QLLM}, which facilitates the automatic construction of credit assignment functions using large language models (LLMs). Specifically, the concept of \textbf{TFCAF} is introduced, wherein the credit allocation process is represented as a direct and expressive nonlinear functional formulation. A custom-designed \textit{coder-evaluator} framework is further employed to guide the generation, verification, and refinement of executable code by LLMs, significantly mitigating issues such as hallucination and shallow reasoning during inference. Extensive experiments conducted on several standard MARL benchmarks demonstrate that the proposed method consistently outperforms existing state-of-the-art baselines. Moreover, QLLM exhibits strong generalization capability and maintains compatibility with a wide range of MARL algorithms that utilize mixing networks, positioning it as a promising and versatile solution for complex multi-agent scenarios.

[Arxiv](https://arxiv.org/abs/2504.12961)