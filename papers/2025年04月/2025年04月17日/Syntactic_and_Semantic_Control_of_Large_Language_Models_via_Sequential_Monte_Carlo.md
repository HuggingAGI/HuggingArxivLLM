# 通过序列蒙特卡洛方法对大型语言模型的句法和语义进行控制。

发布时间：2025年04月17日

`LLM应用` `数据科学`

> Syntactic and Semantic Control of Large Language Models via Sequential Monte Carlo

# 摘要

> 广泛的语言模型 (LM) 应用需要生成符合句法或语义约束的文本。施加这些约束可以自然地被建模为概率条件化，但从这种分布中进行精确生成通常是不可行的，因为这种分布可能与 LM 的基础分布有显著差异。在这项工作中，我们开发了一种基于序列蒙特卡洛 (SMC) 的控制 LM 生成架构。我们的 SMC 框架允许我们在推理时灵活地整合特定领域和问题的约束，并在生成过程中根据新信息有效地重新分配计算资源。通过在四个具有挑战性的领域中与多种替代方法和消融实验进行比较——数据科学的 Python 代码生成、文本到 SQL、目标推断以及分子合成——我们展示了，仅需少量额外计算开销，我们的方法即可使小型开源语言模型超越规模超过 8 倍的模型，以及经过微调的闭源模型。为了支持概率视角，我们证明了这些性能提升源于对后验分布的更好近似。我们的系统基于 Lew et al. (2023) 的框架，并与其语言模型概率编程语言集成，为用户提供了一种简单、可编程的方式来将 SMC 应用于各种控制生成问题。

> A wide range of LM applications require generating text that conforms to syntactic or semantic constraints. Imposing such constraints can be naturally framed as probabilistic conditioning, but exact generation from the resulting distribution -- which can differ substantially from the LM's base distribution -- is generally intractable. In this work, we develop an architecture for controlled LM generation based on sequential Monte Carlo (SMC). Our SMC framework allows us to flexibly incorporate domain- and problem-specific constraints at inference time, and efficiently reallocate computational resources in light of new information during the course of generation. By comparing to a number of alternatives and ablations on four challenging domains -- Python code generation for data science, text-to-SQL, goal inference, and molecule synthesis -- we demonstrate that, with little overhead, our approach allows small open-source language models to outperform models over 8x larger, as well as closed-source, fine-tuned ones. In support of the probabilistic perspective, we show that these performance improvements are driven by better approximation to the posterior distribution. Our system builds on the framework of Lew et al. (2023) and integrates with its language model probabilistic programming language, giving users a simple, programmable way to apply SMC to a broad variety of controlled generation problems.

[Arxiv](https://arxiv.org/abs/2504.13139)