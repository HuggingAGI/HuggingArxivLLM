# 为何不确定性估计方法在RAG中表现不足？一项公理化分析

发布时间：2025年05月12日

`LLM应用` `生成模型` `不确定性估计`

> Why Uncertainty Estimation Methods Fall Short in RAG: An Axiomatic Analysis

# 摘要

> 大型语言模型（LLMs）因其强大的性能而受到重视，但它们也可能生成不准确或误导性的输出。不确定性估计（UE）量化了模型的置信度，帮助用户评估响应的可靠性。然而，现有的UE方法尚未在检索增强生成（RAG）等场景中得到充分研究，这些场景中输入提示包含非参数化知识。本文表明，当前的UE方法无法在RAG设置中可靠地评估正确性。我们进一步提出了一种公理化框架，用于识别现有方法的不足，并指导改进方法的开发。我们的框架引入了五个约束条件，这些条件是将检索到的文档纳入LLM提示后，有效UE方法应满足的要求。实验结果表明，现有的UE方法无法完全满足所有公理，这解释了它们在RAG中的次优性能。我们还基于我们的框架引入了一种简单而有效的校准函数，它不仅比基线方法满足更多公理，还提高了不确定性估计与正确性之间的相关性。

> Large Language Models (LLMs) are valued for their strong performance across various tasks, but they also produce inaccurate or misleading outputs. Uncertainty Estimation (UE) quantifies the model's confidence and helps users assess response reliability. However, existing UE methods have not been thoroughly examined in scenarios like Retrieval-Augmented Generation (RAG), where the input prompt includes non-parametric knowledge. This paper shows that current UE methods cannot reliably assess correctness in the RAG setting. We further propose an axiomatic framework to identify deficiencies in existing methods and guide the development of improved approaches. Our framework introduces five constraints that an effective UE method should meet after incorporating retrieved documents into the LLM's prompt. Experimental results reveal that no existing UE method fully satisfies all the axioms, explaining their suboptimal performance in RAG. We further introduce a simple yet effective calibration function based on our framework, which not only satisfies more axioms than baseline methods but also improves the correlation between uncertainty estimates and correctness.

[Arxiv](https://arxiv.org/abs/2505.07459)