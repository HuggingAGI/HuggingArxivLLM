# GRAPE：优化数据混合，实现群体稳健的多目标自适应预训练

发布时间：2025年05月26日

`LLM理论` `预训练模型`

> GRAPE: Optimize Data Mixture for Group Robust Multi-target Adaptive Pretraining

# 摘要

> 大型语言模型 (LLMs) 的下游应用性能从根本上取决于预训练数据的质量与构成。现有领域重加权算法主要针对单一目标任务优化数据混合，导致模型在特定目标上过度拟合，同时在其他基准任务上表现显著下降。本文提出了一种新型多源多目标领域重加权框架——Group Robust Multi-target Adaptive PrEtraining (GRAPE)，旨在为多个目标任务同时实现稳健性能的预训练数据混合校准。GRAPE 动态调整源领域（领域权重）的采样权重，同时调节量化每个目标任务相对重要性的任务权重。这种自适应过程在整个训练过程中优先处理基于学习难度的任务。我们将这种交错重加权机制形式化为一个极小化极大优化问题：内部最大化通过组分布鲁棒优化 (DRO) 调整任务权重，优先为在当前数据混合下改进最少的任务分配更高的权重；外部最小化则优化领域权重以最大化优先任务的损失减少。实验结果表明，在 ClimbLab 和 SlimPajama 数据集上，与基线方法相比，GRAPE 在 6 个基准上的推理性能始终更优。此外，当应用于多语言目标时，GRAPE 有效识别主流语言中的最优训练混合，实现跨 8 个低资源目标语言的卓越语言建模能力。

> The performance of large language models (LLMs) across diverse downstream applications is fundamentally governed by the quality and composition of their pretraining corpora. Existing domain reweighting algorithms primarily optimize data mixtures for a single target task, thereby resulting in models that overfit to specialized objectives while exhibiting substantial performance degradation on other benchmarks. This paper introduces Group Robust Multi-target Adaptive PrEtraining (GRAPE), a novel multi-source-multi-target domain reweighting framework designed to calibrate pretraining data mixtures for robust performance across multiple target tasks simultaneously. GRAPE dynamically adjusts sampling weights across source domains (domain weights) while concurrently modulating task weights that quantify the relative importance of each individual target task. This adaptive process prioritizes tasks based on their learning difficulty throughout training. We formulate this interleaved reweighting mechanism as a minimax optimization problem: The inner maximization adjusts task weights leveraging group distributed-robust-optimization (DRO), where those tasks demonstrating the least improvement under the current data mixture are prioritized with higher weights; The outer minimization then optimizes domain weights to maximize loss reduction on the prioritized tasks. Experiments on ClimbLab and SlimPajama datasets demonstrate that GRAPE consistently outperforms baseline methods in terms of reasoning performance across 6 benchmarks. Furthermore, when applied to multilingual targets, GRAPE effectively identifies optimal training mixtures from mainstream languages, achieving superior language modeling capabilities across 8 low-resource target languages.

[Arxiv](https://arxiv.org/abs/2505.20380)