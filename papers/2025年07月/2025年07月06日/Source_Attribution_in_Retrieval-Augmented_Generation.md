# # 检索增强生成中的源归属研究

发布时间：2025年07月06日

`RAG` `可解释性` `RAG系统`

> Source Attribution in Retrieval-Augmented Generation

# 摘要

> 尽管Shapley值等归因方法在传统机器学习中被广泛用于解释特征或训练数据的重要性，但它们在大型语言模型（LLMs）中的应用，尤其是在检索增强生成（RAG）系统中，尚处于起步阶段且充满挑战。主要障碍在于高昂的计算成本：每次效用函数评估都需要一次昂贵的LLM调用，导致直接的金钱和时间成本。本文研究了将基于Shapley的归因方法应用于识别RAG系统中具有影响力的检索文档的可行性和有效性。我们对比了Shapley与其他更易计算的近似方法以及现有的LLM归因方法。我们的研究目标是：(1) 系统性地将已建立的归因原理应用于RAG的文档级别设置；(2) 量化SHAP近似值在减少昂贵的LLM交互的同时，能够多大程度上反映精确归因；(3) 评估它们在识别关键文档（特别是在冗余、互补和协同等复杂文档间关系下）的实际可解释性。本研究旨在弥合强大的归因技术与基于LLM的RAG系统实际约束之间的差距，为实现可靠且经济的RAG可解释性提供见解。

> While attribution methods, such as Shapley values, are widely used to explain the importance of features or training data in traditional machine learning, their application to Large Language Models (LLMs), particularly within Retrieval-Augmented Generation (RAG) systems, is nascent and challenging. The primary obstacle is the substantial computational cost, where each utility function evaluation involves an expensive LLM call, resulting in direct monetary and time expenses. This paper investigates the feasibility and effectiveness of adapting Shapley-based attribution to identify influential retrieved documents in RAG. We compare Shapley with more computationally tractable approximations and some existing attribution methods for LLM. Our work aims to: (1) systematically apply established attribution principles to the RAG document-level setting; (2) quantify how well SHAP approximations can mirror exact attributions while minimizing costly LLM interactions; and (3) evaluate their practical explainability in identifying critical documents, especially under complex inter-document relationships such as redundancy, complementarity, and synergy. This study seeks to bridge the gap between powerful attribution techniques and the practical constraints of LLM-based RAG systems, offering insights into achieving reliable and affordable RAG explainability.

[Arxiv](https://arxiv.org/abs/2507.04480)