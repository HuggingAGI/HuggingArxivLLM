# GOLFer: 一款更精简的基于LM生成文档的幻觉过滤与组合工具，专为信息检索中的查询扩展设计。

发布时间：2025年06月05日

`LLM应用` `搜索引擎` `信息管理系统`

> GOLFer: Smaller LM-Generated Documents Hallucination Filter & Combiner for Query Expansion in Information Retrieval

# 摘要

> 基于大型语言模型（LLMs）的查询扩展方法通过生成假设性文档来增强信息检索，但其效果严重依赖于模型规模，需要更大、更先进的LLMs。这种方法成本高昂、计算密集且难以获取。为了解决这些问题，我们提出了GOLFer——一种基于小型开源LM的全新查询扩展方法。GOLFer包含两个模块：幻觉过滤器和文档组合器。前者用于检测并移除生成文档中不真实和不一致的句子；后者通过权重向量将过滤后的内容与查询相结合，平衡其影响。我们在三个网络搜索数据集和十个低资源数据集上，将GOLFer与主流的基于LLM的查询扩展方法进行了对比评估。实验结果表明，GOLFer在使用小型LM时始终优于其他方法，并在与使用大型LM的方法对比中保持了竞争力，证明了其有效性。

> Large language models (LLMs)-based query expansion for information retrieval augments queries with generated hypothetical documents with LLMs. However, its performance relies heavily on the scale of the language models (LMs), necessitating larger, more advanced LLMs. This approach is costly, computationally intensive, and often has limited accessibility. To address these limitations, we introduce GOLFer - Smaller LMs-Generated Documents Hallucination Filter & Combiner - a novel method leveraging smaller open-source LMs for query expansion. GOLFer comprises two modules: a hallucination filter and a documents combiner. The former detects and removes non-factual and inconsistent sentences in generated documents, a common issue with smaller LMs, while the latter combines the filtered content with the query using a weight vector to balance their influence. We evaluate GOLFer alongside dominant LLM-based query expansion methods on three web search and ten low-resource datasets. Experimental results demonstrate that GOLFer consistently outperforms other methods using smaller LMs, and maintains competitive performance against methods using large-size LLMs, demonstrating its effectiveness.

[Arxiv](https://arxiv.org/abs/2506.04762)