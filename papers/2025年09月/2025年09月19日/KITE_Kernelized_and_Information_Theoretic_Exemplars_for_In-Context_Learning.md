# KITE：面向上下文学习的核化与信息论示例

发布时间：2025年09月19日

`LLM理论` `基础理论`

> KITE: Kernelized and Information Theoretic Exemplars for In-Context Learning

# 摘要

> 上下文学习（ICL）凭借仅在提示中加入少量精心挑选的特定任务示例，就能让大型语言模型（LLMs）适配新的、数据稀缺的任务，已然成为一种强大范式。但LLMs的上下文长度有限，由此引出一个核心问题：如何选择示例才能最大化特定用户查询的性能？尽管KATE等基于最近邻的方法已被广泛采用，但这类方法在高维嵌入空间中存在泛化能力弱、多样性不足等公认缺陷。为此，本研究从信息论驱动的原则性角度，深入探究ICL中的示例选择问题。我们首先将LLM建模为输入嵌入的线性函数，进而将示例选择任务转化为特定查询的优化问题——从大型示例库中挑选子集，以最小化特定查询的预测误差。这一构建思路与传统聚焦泛化的学习理论方法不同，其核心在于实现特定查询实例的精准预测。我们推导出一个原则性的代理目标函数，该函数近似满足次模性，因此可采用具有近似保证的贪心算法。我们进一步从两方面改进方法：（i）引入核技巧，实现高维特征空间的无显式映射运算；（ii）设计基于最优设计的正则化器，增强所选示例的多样性。实验结果表明，在一系列分类任务中，我们的方法显著优于标准检索方法，充分彰显了在现实世界标签稀缺场景下，ICL采用结构感知、多样化示例选择的优势。

> In-context learning (ICL) has emerged as a powerful paradigm for adapting large language models (LLMs) to new and data-scarce tasks using only a few carefully selected task-specific examples presented in the prompt. However, given the limited context size of LLMs, a fundamental question arises: Which examples should be selected to maximize performance on a given user query? While nearest-neighbor-based methods like KATE have been widely adopted for this purpose, they suffer from well-known drawbacks in high-dimensional embedding spaces, including poor generalization and a lack of diversity. In this work, we study this problem of example selection in ICL from a principled, information theory-driven perspective. We first model an LLM as a linear function over input embeddings and frame the example selection task as a query-specific optimization problem: selecting a subset of exemplars from a larger example bank that minimizes the prediction error on a specific query. This formulation departs from traditional generalization-focused learning theoretic approaches by targeting accurate prediction for a specific query instance. We derive a principled surrogate objective that is approximately submodular, enabling the use of a greedy algorithm with an approximation guarantee. We further enhance our method by (i) incorporating the kernel trick to operate in high-dimensional feature spaces without explicit mappings, and (ii) introducing an optimal design-based regularizer to encourage diversity in the selected examples. Empirically, we demonstrate significant improvements over standard retrieval methods across a suite of classification tasks, highlighting the benefits of structure-aware, diverse example selection for ICL in real-world, label-scarce scenarios.

[Arxiv](https://arxiv.org/abs/2509.15676)