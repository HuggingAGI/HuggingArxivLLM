# 大型语言模型中的系统性异常值研究

发布时间：2025年02月10日

`LLM理论` `模型优化`

> Systematic Outliers in Large Language Models

# 摘要

> 大型语言模型（LLMs）中的异常值现象对模型性能和压缩带来了显著影响，理解其功能与成因至关重要。现有研究多从算法角度减少其影响，而对其本质缺乏深入探讨。本研究详细解析了LLMs中异常值的形成机制、根本原因及其功能，将其分为激活异常值、权重异常值和注意力异常值三类，并揭示了其分布与注意力机制影响间的内在联系。通过理论推导和实验，我们发现这些异常值源于自注意力机制中的softmax操作，充当隐式的上下文感知缩放因子。由于其系统性成因，我们称其为系统性异常值。本研究不仅深化了对Transformer模型的理解，还表明通过结构化消除异常值可加速收敛并提升压缩效果。代码已开源：https://github.com/an-yongqi/systematic-outliers。

> Outliers have been widely observed in Large Language Models (LLMs), significantly impacting model performance and posing challenges for model compression. Understanding the functionality and formation mechanisms of these outliers is critically important. Existing works, however, largely focus on reducing the impact of outliers from an algorithmic perspective, lacking an in-depth investigation into their causes and roles. In this work, we provide a detailed analysis of the formation process, underlying causes, and functions of outliers in LLMs. We define and categorize three types of outliers-activation outliers, weight outliers, and attention outliers-and analyze their distributions across different dimensions, uncovering inherent connections between their occurrences and their ultimate influence on the attention mechanism. Based on these observations, we hypothesize and explore the mechanisms by which these outliers arise and function, demonstrating through theoretical derivations and experiments that they emerge due to the self-attention mechanism's softmax operation. These outliers act as implicit context-aware scaling factors within the attention mechanism. As these outliers stem from systematic influences, we term them systematic outliers. Our study not only enhances the understanding of Transformer-based LLMs but also shows that structurally eliminating outliers can accelerate convergence and improve model compression. The code is avilable at https://github.com/an-yongqi/systematic-outliers.

[Arxiv](https://arxiv.org/abs/2502.06415)