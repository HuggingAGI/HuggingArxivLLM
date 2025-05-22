# CRAFT：无需训练的级联检索技术实现表格问答

发布时间：2025年05月20日

`LLM应用` `问答系统`

> CRAFT: Training-Free Cascaded Retrieval for Tabular QA

# 摘要

> 表格问答系统 (TQA) 旨在从大规模语料库中检索相关表格，以回答自然语言问题。传统密集检索模型如DTR和ColBERT，不仅计算成本高昂，且需要针对新数据集进行重新训练或微调，这限制了它们在动态变化领域的适应性。为此，我们提出了$	extbf{CRAFT}$，一种级联检索方法：首先利用稀疏检索模型筛选候选表格，再应用计算开销更大的密集模型和神经重排序器。实验表明，$	extbf{CRAFT}$在检索性能上超越现有最优的稀疏、密集和混合检索方法。我们进一步通过 Gemini Flash 1.5 生成表格描述和标题，增强表格表示能力。在自然问答数据集子集 NQ-Tables 上，使用多种大型语言模型 (LLMs) 进行的端到端 TQA 实验，充分验证了$	extbf{CRAFT}$的显著优势。

> Table Question Answering (TQA) involves retrieving relevant tables from a large corpus to answer natural language queries. Traditional dense retrieval models, such as DTR and ColBERT, not only incur high computational costs for large-scale retrieval tasks but also require retraining or fine-tuning on new datasets, limiting their adaptability to evolving domains and knowledge. In this work, we propose $\textbf{CRAFT}$, a cascaded retrieval approach that first uses a sparse retrieval model to filter a subset of candidate tables before applying more computationally expensive dense models and neural re-rankers. Our approach achieves better retrieval performance than state-of-the-art (SOTA) sparse, dense, and hybrid retrievers. We further enhance table representations by generating table descriptions and titles using Gemini Flash 1.5. End-to-end TQA results using various Large Language Models (LLMs) on NQ-Tables, a subset of the Natural Questions Dataset, demonstrate $\textbf{CRAFT}$ effectiveness.

[Arxiv](https://arxiv.org/abs/2505.14984)