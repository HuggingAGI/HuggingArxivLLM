# 无穷最佳——测试时计算的渐近性能

发布时间：2025年09月25日

`LLM应用` `基础理论`

> Best-of-$\infty$ -- Asymptotic Performance of Test-Time Compute

# 摘要

> 我们针对大型语言模型（LLMs）研究了基于多数投票的best-of-$N$方法。具体来说，我们分析了$N 	o \infty$的极限场景（记为Best-of-$\infty$）。尽管该方法在极限状态下性能惊艳，但却需要无限的测试时预算。为此，我们提出一种自适应生成方案，能根据答案一致性动态选择$N$，从而高效分配推理阶段的计算资源。除了自适应性，我们还将该框架扩展到多LLM的加权集成，结果显示这类混合模型的性能能够超越任何单一模型。我们通过混合整数线性规划来制定并高效求解最优集成权重，大量实验结果验证了我们方法的有效性。

> We study best-of-$N$ for large language models (LLMs) where the selection is based on majority voting. In particular, we analyze the limit $N \to \infty$, which we denote as Best-of-$\infty$. While this approach achieves impressive performance in the limit, it requires an infinite test-time budget. To address this, we propose an adaptive generation scheme that selects $N$ based on answer agreement, thereby efficiently allocating inference-time computation. Beyond adaptivity, we extend the framework to weighted ensembles of multiple LLMs, showing that such mixtures can outperform any individual model. The optimal ensemble weighting is formulated and efficiently computed as a mixed-integer linear program. Extensive experiments demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.21091)