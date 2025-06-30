# 推理时间扩展中的概率最优性探讨

发布时间：2025年06月27日

`LLM理论` `数学推理`

> Probabilistic Optimality for Inference-time Scaling

# 摘要

> 推理时扩展技术作为一种强大的方法，已被证明可以有效提升大型语言模型（LLMs）的推理性能。然而，现有的方法通常依赖于启发式策略来进行并行采样，缺乏坚实的理论基础。为了解决这一问题，我们提出了一种概率框架，在并行样本独立同分布（i.i.d.）的假设下，形式化地定义了推理时扩展的最优性，并且其中的Best-of-N选择策略遵循一种可估计的概率分布。在此框架下，我们推导出在达到目标性能水平时所需的最小样本数量的理论下界，为计算高效的扩展提供了首个基于原理的指导。基于这一见解，我们开发了	extsc{OptScale}，一个能够动态确定最优采样响应数量的实际算法。该算法采用基于语言模型的预测器来估计概率先验参数，从而决定满足预定义性能阈值和置信水平所需的最小采样数量。在数学推理基准测试（包括MATH-500、GSM8K、AIME和AMC）上的广泛实验表明，	extsc{OptScale}显著降低了采样开销，同时保持了与现有最优推理性能相当或更好的表现。我们的工作为基于原理的推理时扩展提供了理论基础和实际解决方案，填补了在复杂推理任务中高效部署大型语言模型的关键空白。

> Inference-time scaling has emerged as a powerful technique for enhancing the reasoning performance of Large Language Models (LLMs). However, existing approaches often rely on heuristic strategies for parallel sampling, lacking a principled foundation. To address this gap, we propose a probabilistic framework that formalizes the optimality of inference-time scaling under the assumption that parallel samples are independently and identically distributed (i.i.d.), and where the Best-of-N selection strategy follows a probability distribution that can be estimated. Within this framework, we derive a theoretical lower bound on the required number of samples to achieve a target performance level, providing the first principled guidance for compute-efficient scaling. Leveraging this insight, we develop \textsc{OptScale}, a practical algorithm that dynamically determines the optimal number of sampled responses. \textsc{OptScale} employs a language model-based predictor to estimate probabilistic prior parameters, enabling the decision of the minimal number of samples needed that satisfy predefined performance thresholds and confidence levels. Extensive experiments on mathematical reasoning benchmarks (including MATH-500, GSM8K, AIME, and AMC) demonstrate that \textsc{OptScale} significantly reduces sampling overhead while remaining better or on par with state-of-the-art reasoning performance. Our work offers both a theoretical foundation and a practical solution for principled inference-time scaling, addressing a critical gap in the efficient deployment of LLMs for complex reasoning.

[Arxiv](https://arxiv.org/abs/2506.22376)