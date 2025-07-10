# # FuDoBa：基于贝叶斯优化融合文档与知识图谱表示

发布时间：2025年07月09日

`LLM应用` `信息检索`

> FuDoBa: Fusing Document and Knowledge Graph-based Representations with Bayesian Optimisation

# 摘要

> 基于大型语言模型（LLMs）的成功，LLM 基础的表示方法在文档表示领域占据主导地位，并在文档嵌入基准上取得了优异性能。然而，LLMs 的高维、计算代价高昂的嵌入往往过于通用，或者对于特定领域应用而言不够高效。为了解决这些限制，我们引入了 FuDoBa，这是一种基于贝叶斯优化的方法，将 LLM 基础的嵌入与特定领域的结构化知识相结合，这些知识既来自本地，也来自 WikiData 等外部存储库。这种融合产生了低维、任务相关的表示，同时降低了训练复杂度，并生成可解释的早期融合权重，从而增强了分类性能。我们证明了我们的方法在两个领域的六个数据集上的有效性，结果显示，当与稳健的 AutoML 基础分类器结合使用时，我们提出的表现学习方法与仅由专有 LLM 基础嵌入基线生成的表现持平或超越。

> Building on the success of Large Language Models (LLMs), LLM-based representations have dominated the document representation landscape, achieving great performance on the document embedding benchmarks. However, the high-dimensional, computationally expensive embeddings from LLMs tend to be either too generic or inefficient for domain-specific applications. To address these limitations, we introduce FuDoBa a Bayesian optimisation-based method that integrates LLM-based embeddings with domain-specific structured knowledge, sourced both locally and from external repositories like WikiData. This fusion produces low-dimensional, task-relevant representations while reducing training complexity and yielding interpretable early-fusion weights for enhanced classification performance. We demonstrate the effectiveness of our approach on six datasets in two domains, showing that when paired with robust AutoML-based classifiers, our proposed representation learning approach performs on par with, or surpasses, those produced solely by the proprietary LLM-based embedding baselines.

[Arxiv](https://arxiv.org/abs/2507.06622)