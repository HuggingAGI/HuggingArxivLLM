# 基于粒子蒙特卡罗方法的概率推理：LLMs推理时扩展的新思路

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要讨论了在推理时扩展计算量的新方法，提出了一种基于概率推理的推理时扩展方法，并将其应用于大型语言模型（LLMs）。论文的核心在于提出了一种新的理论框架，将概率推理与LLMs的推理时扩展相结合，并进行了实证评估。因此，这篇论文更侧重于LLM的理论研究和方法创新，而不是具体的应用或代理（Agent）技术。` `人工智能` `数学推理`

> A Probabilistic Inference Approach to Inference-Time Scaling of LLMs using Particle-Based Monte Carlo Methods

# 摘要

> # 摘要
大型语言模型（LLMs）通过扩大模型规模和数据量取得了显著性能提升，但近期研究表明，这种方法的回报正在递减，促使我们在推理时扩展计算量。现有方法通常依赖奖励模型，将任务视为搜索问题，但容易因奖励模型的近似误差而受到奖励黑客攻击。本文提出了一种新方法，将推理时扩展视为概率推理任务，利用基于采样的技术探索状态空间模型的典型状态分布，而非直接优化其模式。我们通过将基于粒子的蒙特卡罗方法应用于此任务，提出了一种新的推理时扩展方法。实证评估显示，在各种复杂数学推理任务中，我们的方法比确定性搜索方法具有4-16倍的扩展率。使用该方法，Qwen2.5-Math-1.5B-Instruct在仅4次迭代中即可超越GPT-4o的准确性，而Qwen2.5-Math-7B-Instruct在32次迭代中即可达到o1级别的准确性。我们的工作不仅提出了一种有效的推理时扩展方法，还将概率推理的丰富文献与LLMs的推理时扩展相结合，为未来开发更稳健的算法奠定了基础。代码和更多信息请访问https://probabilistic-inference-scaling.github.io。

> Large language models (LLMs) have achieved significant performance gains via scaling up model sizes and/or data. However, recent evidence suggests diminishing returns from such approaches, motivating scaling the computation spent at inference time. Existing inference-time scaling methods, usually with reward models, cast the task as a search problem, which tends to be vulnerable to reward hacking as a consequence of approximation errors in reward models. In this paper, we instead cast inference-time scaling as a probabilistic inference task and leverage sampling-based techniques to explore the typical set of the state distribution of a state-space model with an approximate likelihood, rather than optimize for its mode directly. We propose a novel inference-time scaling approach by adapting particle-based Monte Carlo methods to this task. Our empirical evaluation demonstrates that our methods have a 4-16x better scaling rate over our deterministic search counterparts on various challenging mathematical reasoning tasks. Using our approach, we show that Qwen2.5-Math-1.5B-Instruct can surpass GPT-4o accuracy in only 4 rollouts, while Qwen2.5-Math-7B-Instruct scales to o1 level accuracy in only 32 rollouts. Our work not only presents an effective method to inference-time scaling, but also connects the rich literature in probabilistic inference with inference-time scaling of LLMs to develop more robust algorithms in future work. Code and further information is available at https://probabilistic-inference-scaling.github.io.

[Arxiv](https://arxiv.org/abs/2502.01618)