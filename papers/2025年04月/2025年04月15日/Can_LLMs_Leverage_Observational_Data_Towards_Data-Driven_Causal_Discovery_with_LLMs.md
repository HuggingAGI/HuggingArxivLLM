# LLMs能否善用观察数据？迈向数据驱动因果发现之路

发布时间：2025年04月15日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在因果发现中的应用，研究了LLMs如何通过观察数据进行因果推理，并提出了两种基于提示的方法来提升因果发现的效果。这属于LLMs在具体任务中的应用研究，因此归类为LLM应用。` `因果发现` `数据分析`

> Can LLMs Leverage Observational Data? Towards Data-Driven Causal Discovery with LLMs

# 摘要

> 因果发现传统上依赖于统计方法处理观察数据，通常需要大量数据和对潜在因果结构的假设。近期，大型语言模型（LLMs）的进步为因果发现提供了新可能，通过提供领域专业知识来实现。然而，LLMs是否能有效处理观察数据进行因果发现，仍是一个待解决的问题。在本研究中，我们探索了LLMs在数据驱动因果发现中的潜力，通过整合观察数据进行基于LLM的推理。具体而言，我们研究了LLMs是否能通过两种提示策略有效利用观察数据：成对提示和基于广度优先搜索（BFS）的提示。在两种方法中，我们直接将观察数据整合到提示中，以评估LLMs从数据中推断因果关系的能力。在基准数据集上的实验表明，整合观察数据可以显著提升因果发现的效果，使用成对和BFS两种基于LLM的提示方法，F1分数分别提升了0.11个百分点，同时相比传统统计因果发现基线模型，最多提升了0.52个百分点。我们的研究结果凸显了LLMs在数据驱动因果发现中的潜力与局限性，展示了它们超越文本元数据的能力，能够有效解读和利用观察数据，从而实现更全面的因果推理。我们的研究为未来实现完全基于LLM的因果发现奠定了基础。


> Causal discovery traditionally relies on statistical methods applied to observational data, often requiring large datasets and assumptions about underlying causal structures. Recent advancements in Large Language Models (LLMs) have introduced new possibilities for causal discovery by providing domain expert knowledge. However, it remains unclear whether LLMs can effectively process observational data for causal discovery. In this work, we explore the potential of LLMs for data-driven causal discovery by integrating observational data for LLM-based reasoning. Specifically, we examine whether LLMs can effectively utilize observational data through two prompting strategies: pairwise prompting and breadth first search (BFS)-based prompting. In both approaches, we incorporate the observational data directly into the prompt to assess LLMs' ability to infer causal relationships from such data. Experiments on benchmark datasets show that incorporating observational data enhances causal discovery, boosting F1 scores by up to 0.11 point using both pairwise and BFS LLM-based prompting, while outperforming traditional statistical causal discovery baseline by up to 0.52 points. Our findings highlight the potential and limitations of LLMs for data-driven causal discovery, demonstrating their ability to move beyond textual metadata and effectively interpret and utilize observational data for more informed causal reasoning. Our studies lays the groundwork for future advancements toward fully LLM-driven causal discovery.

[Arxiv](https://arxiv.org/abs/2504.10936)