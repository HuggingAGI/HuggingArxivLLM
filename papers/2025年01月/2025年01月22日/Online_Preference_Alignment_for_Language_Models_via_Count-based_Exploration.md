# 基于计数的探索实现语言模型的在线偏好对齐

发布时间：2025年01月22日

`LLM理论

理由：这篇论文主要探讨了基于人类反馈的强化学习（RLHF）在微调大型语言模型（LLMs）中的应用，特别是如何通过在线RLHF进行探索和优化。论文提供了理论依据，并提出了一种新的算法（COPO）来改进LLM的探索和偏好优化。这些内容主要涉及LLM的理论研究和算法设计，因此归类为“LLM理论”。` `人工智能`

> Online Preference Alignment for Language Models via Count-based Exploration

# 摘要

> # 摘要
基于人类反馈的强化学习（RLHF）在微调大型语言模型（LLMs）以与人类偏好对齐方面展现出巨大潜力。现有方法依赖固定数据集进行偏好对齐，数据覆盖有限，且奖励模型在分布外响应中难以泛化。因此，在线RLHF更具优势，它通过迭代收集提示-响应对，使LLM能够在初始数据集之外进行探索。本文研究了在线RLHF的核心问题：\emph{如何探索}LLM。我们在线性奖励假设下提供了理论依据，证明带有上置信界（UCB）项的乐观奖励能带来高效的RLHF策略。随后，我们将目标重新定义为带有探索项的直接偏好优化，UCB项可转化为基于计数的探索奖励。我们提出了一种实用算法——\emph{基于计数的在线偏好优化（COPO）}，它通过简单的硬币翻转计数模块估计提示-响应对的伪计数。COPO鼓励LLMs在迭代中平衡探索与偏好优化，从而扩大探索空间和策略的数据覆盖范围。我们在Zephyr和Llama-3模型上进行了在线RLHF实验，结果表明COPO在指令遵循和标准学术基准测试中显著提升了性能。

> Reinforcement Learning from Human Feedback (RLHF) has shown great potential in fine-tuning Large Language Models (LLMs) to align with human preferences. Existing methods perform preference alignment from a fixed dataset, which can be limited in data coverage, and the resulting reward model is hard to generalize in out-of-distribution responses. Thus, online RLHF is more desirable to empower the LLM to explore outside the support of the initial dataset by iteratively collecting the prompt-response pairs. In this paper, we study the fundamental problem in online RLHF, i.e. \emph{how to explore} for LLM. We give a theoretical motivation in linear reward assumption to show that an optimistic reward with an upper confidence bound (UCB) term leads to a provably efficient RLHF policy. Then, we reformulate our objective to direct preference optimization with an exploration term, where the UCB-term can be converted to a count-based exploration bonus. We further propose a practical algorithm, named \emph{Count-based Online Preference Optimization (COPO)}, which leverages a simple coin-flip counting module to estimate the pseudo-count of a prompt-response pair in previously collected data. COPO encourages LLMs to balance exploration and preference optimization in an iterative manner, which enlarges the exploration space and the entire data coverage of iterative LLM policies. We conduct online RLHF experiments on Zephyr and Llama-3 models. The results on instruction-following and standard academic benchmarks show that COPO significantly increases performance.

[Arxiv](https://arxiv.org/abs/2501.12735)