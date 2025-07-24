# 如何进行强化学习算法的元学习？

发布时间：2025年07月23日

`Agent` `人工智能` `机器学习`

> How Should We Meta-Learn Reinforcement Learning Algorithms?

# 摘要

> 元学习正逐渐成为提升机器学习系统性能的主流范式，其优势在于从数据中自动学习，而非依赖人工设计。在强化学习（RL）领域，元学习展现出巨大潜力，尽管当前算法多从监督学习或无监督学习中借鉴，但其对RL的适用性仍有待提升。然而，不同元学习算法之间的比较研究仍极度匮乏，例如进化算法优化黑箱函数或大型语言模型（LLMs）生成代码等方法。本文对应用于强化学习管道不同环节的各类元学习算法展开了实证对比研究。我们不仅评估了元学习和元测试性能，还深入探讨了每种算法的可解释性、样本成本及训练时间等因素。基于研究发现，我们提出了若干针对新强化学习算法元学习的指导原则，以确保未来开发的算法性能达到最优水平。

> The process of meta-learning algorithms from data, instead of relying on manual design, is growing in popularity as a paradigm for improving the performance of machine learning systems. Meta-learning shows particular promise for reinforcement learning (RL), where algorithms are often adapted from supervised or unsupervised learning despite their suboptimality for RL. However, until now there has been a severe lack of comparison between different meta-learning algorithms, such as using evolution to optimise over black-box functions or LLMs to propose code. In this paper, we carry out this empirical comparison of the different approaches when applied to a range of meta-learned algorithms which target different parts of the RL pipeline. In addition to meta-train and meta-test performance, we also investigate factors including the interpretability, sample cost and train time for each meta-learning algorithm. Based on these findings, we propose several guidelines for meta-learning new RL algorithms which will help ensure that future learned algorithms are as performant as possible.

[Arxiv](https://arxiv.org/abs/2507.17668)