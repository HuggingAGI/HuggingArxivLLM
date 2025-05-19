# 基于语言模型的开放世界组合零样本学习可行性研究

发布时间：2025年05月16日

`LLM应用` `计算机视觉` `零样本学习`

> Feasibility with Language Models for Open-World Compositional Zero-Shot Learning

# 摘要

> 人类很容易判断一个属性对某个物体是否现实可行，例如火可以是热的，但不能是湿的。在开放世界组合零样本学习中，当所有可能的状态-物体组合都被视为未见类别时，零样本预测器的表现往往不尽如人意。我们提出了一种利用外部辅助知识判断状态-物体组合可行性的方法。我们的可行性语言模型（FLM）是一种简单而有效的方法，它利用大型语言模型（LLMs）更好地理解状态与物体之间的语义关系。FLM通过向LLM查询给定组合的可行性，并检索正向回答的输出对数几率来实现。为了缓解LLM可能带来的潜在误导，因为我们观察到许多状态-物体组合都是罕见的或完全不可行的，我们发现LLM的上下文学习能力至关重要。我们进行了广泛的研究，发现Vicuna和ChatGPT表现最佳，并且我们证明我们的FLM在所有三个基准测试中都能持续提升OW-CZSL的性能。

> Humans can easily tell if an attribute (also called state) is realistic, i.e., feasible, for an object, e.g. fire can be hot, but it cannot be wet. In Open-World Compositional Zero-Shot Learning, when all possible state-object combinations are considered as unseen classes, zero-shot predictors tend to perform poorly. Our work focuses on using external auxiliary knowledge to determine the feasibility of state-object combinations. Our Feasibility with Language Model (FLM) is a simple and effective approach that leverages Large Language Models (LLMs) to better comprehend the semantic relationships between states and objects. FLM involves querying an LLM about the feasibility of a given pair and retrieving the output logit for the positive answer. To mitigate potential misguidance of the LLM given that many of the state-object compositions are rare or completely infeasible, we observe that the in-context learning ability of LLMs is essential. We present an extensive study identifying Vicuna and ChatGPT as best performing, and we demonstrate that our FLM consistently improves OW-CZSL performance across all three benchmarks.

[Arxiv](https://arxiv.org/abs/2505.11181)