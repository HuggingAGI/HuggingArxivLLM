# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月11日

`LLM理论

理由：这篇论文探讨了语言模型的决策机制，特别是其是否具备贝叶斯推理能力。论文挑战了传统的采样假设，并提出了新的见解，这些都属于对语言模型理论层面的研究。因此，它属于LLM理论类别。` `人工智能`

> Do Language Models Have Bayesian Brains? Distinguishing Stochastic and Deterministic Decision Patterns within Large Language Models

# 摘要

> 语言模型本质上是关于令牌序列的概率分布。自回归模型通过迭代计算并从下一个令牌的分布中采样来生成句子。这种迭代采样引入了随机性，导致人们假设语言模型做出的是概率性决策，类似于从未知分布中采样。基于这一假设，先前的研究受到启发，设计了模拟人类先验的实验，并使用模拟的吉布斯采样来推断语言模型的先验。在这篇文章中，我们重新审视一个关键问题：语言模型是否具有贝叶斯推理能力？我们的研究结果表明，在特定条件下，语言模型可以展现出近确定性的决策模式，例如生成最大似然估计，即使采样温度不为零。这一发现挑战了传统的采样假设，并削弱了之前用于推断类人先验的方法。此外，我们还证明，未经适当审查的具有确定性行为的系统在进行模拟吉布斯采样时，可能会收敛到一个“错误的先验”。为了解决这一问题，我们提出了一种简单直接的方法，用于区分吉布斯采样中的随机与确定性决策模式，从而有助于防止推断出误导性的语言模型先验。我们在多种大型语言模型上进行了实验，以识别它们在不同情况下的决策模式。我们的研究结果为理解大型语言模型的决策机制提供了重要的见解。

> Language models are essentially probability distributions over token sequences. Auto-regressive models generate sentences by iteratively computing and sampling from the distribution of the next token. This iterative sampling introduces stochasticity, leading to the assumption that language models make probabilistic decisions, similar to sampling from unknown distributions. Building on this assumption, prior research has used simulated Gibbs sampling, inspired by experiments designed to elicit human priors, to infer the priors of language models. In this paper, we revisit a critical question: Do language models possess Bayesian brains? Our findings show that under certain conditions, language models can exhibit near-deterministic decision-making, such as producing maximum likelihood estimations, even with a non-zero sampling temperature. This challenges the sampling assumption and undermines previous methods for eliciting human-like priors. Furthermore, we demonstrate that without proper scrutiny, a system with deterministic behavior undergoing simulated Gibbs sampling can converge to a "false prior." To address this, we propose a straightforward approach to distinguish between stochastic and deterministic decision patterns in Gibbs sampling, helping to prevent the inference of misleading language model priors. We experiment on a variety of large language models to identify their decision patterns under various circumstances. Our results provide key insights in understanding decision making of large language models.

[Arxiv](https://arxiv.org/abs/2506.10268)