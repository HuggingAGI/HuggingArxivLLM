# LyapLock: 在序列大型语言模型编辑中的有界知识保存

发布时间：2025年05月21日

`LLM理论` `模型优化` `模型编辑`

> LyapLock: Bounded Knowledge Preservation in Sequential Large Language Model Editing

# 摘要

> 大型语言模型 (LLMs) 经常包含事实性错误或过时的知识，催生了用于精确知识更新的模型编辑方法。然而，现有的主流定位-编辑方法在连续编辑过程中表现出性能逐渐下降的现象，这是由于缺乏有效的长期知识保存机制。为解决这一问题，我们将连续编辑建模为一个约束随机规划问题。鉴于累积保存误差约束以及逐步揭示的编辑任务所带来的挑战，我们提出了	extbf{LyapLock}。它结合了排队论和Lyapunov优化，将长期约束规划分解为可处理的分步子问题，从而实现高效求解。这是首个具有严格理论保证的模型编辑框架，在满足长期知识保存约束的同时，实现了渐近最优的编辑性能。实验结果表明，我们的框架将连续编辑容量扩展至超过10,000次编辑，同时稳定了模型的一般能力，并将平均编辑效率较最先进基线提升了11.89\%。此外，它还可以用于增强基线方法的性能。我们的代码已发布在https://github.com/caskcsg/LyapLock。


> Large Language Models often contain factually incorrect or outdated knowledge, giving rise to model editing methods for precise knowledge updates. However, current mainstream locate-then-edit approaches exhibit a progressive performance decline during sequential editing, due to inadequate mechanisms for long-term knowledge preservation. To tackle this, we model the sequential editing as a constrained stochastic programming. Given the challenges posed by the cumulative preservation error constraint and the gradually revealed editing tasks, \textbf{LyapLock} is proposed. It integrates queuing theory and Lyapunov optimization to decompose the long-term constrained programming into tractable stepwise subproblems for efficient solving. This is the first model editing framework with rigorous theoretical guarantees, achieving asymptotic optimal editing performance while meeting the constraints of long-term knowledge preservation. Experimental results show that our framework scales sequential editing capacity to over 10,000 edits while stabilizing general capabilities and boosting average editing efficacy by 11.89\% over SOTA baselines. Furthermore, it can be leveraged to enhance the performance of baseline methods. Our code is released on https://github.com/caskcsg/LyapLock.

[Arxiv](https://arxiv.org/abs/2505.15702)