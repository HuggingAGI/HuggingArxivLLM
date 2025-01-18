# 基于知识图谱的检索增强生成在模式匹配中的应用

发布时间：2025年01月15日

`RAG

理由：这篇论文提出了一个基于知识图谱的检索增强生成模型（KG-RAG4SM），该模型结合了向量、图遍历和查询驱动的图检索方法，从外部知识图谱中筛选出最相关的子图，以增强模式匹配的准确性。这种方法属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴，因为它通过检索外部知识来增强生成模型的性能。` `知识图谱`

> Knowledge Graph-based Retrieval-Augmented Generation for Schema Matching

# 摘要

> # 摘要
传统基于相似性的模式匹配方法因缺乏常识和领域知识，难以应对复杂映射场景中的语义歧义和冲突。而大型语言模型（LLMs）的幻觉问题也让基于LLM的模式匹配面临挑战。为此，我们提出了基于知识图谱的检索增强生成模型KG-RAG4SM。该模型创新性地引入了向量、图遍历和查询驱动的图检索方法，结合混合策略和排名机制，从外部大型知识图谱（KGs）中筛选出最相关的子图。实验表明，KG-RAG4SM无需重新训练即可为复杂匹配任务生成更精准的结果。在MIMIC数据集上，KG-RAG4SM的精确度和F1分数分别比LLM的SOTA方法（如Jellyfish-8B）高出35.89%和30.50%；在Synthea数据集上，KG-RAG4SM与GPT-4o-mini的精确度和F1分数分别比PLM的SOTA方法（如SMAT）高出69.20%和21.97%。此外，我们的方法在端到端模式匹配中效率更高，且能扩展到大型KGs的检索。真实场景的案例研究进一步证实，我们的方案有效缓解了LLMs在模式匹配中的幻觉问题。

> Traditional similarity-based schema matching methods are incapable of resolving semantic ambiguities and conflicts in domain-specific complex mapping scenarios due to missing commonsense and domain-specific knowledge. The hallucination problem of large language models (LLMs) also makes it challenging for LLM-based schema matching to address the above issues. Therefore, we propose a Knowledge Graph-based Retrieval-Augmented Generation model for Schema Matching, referred to as the KG-RAG4SM. In particular, KG-RAG4SM introduces novel vector-based, graph traversal-based, and query-based graph retrievals, as well as a hybrid approach and ranking schemes that identify the most relevant subgraphs from external large knowledge graphs (KGs). We showcase that KG-based retrieval-augmented LLMs are capable of generating more accurate results for complex matching cases without any re-training. Our experimental results show that KG-RAG4SM outperforms the LLM-based state-of-the-art (SOTA) methods (e.g., Jellyfish-8B) by 35.89% and 30.50% in terms of precision and F1 score on the MIMIC dataset, respectively; KG-RAG4SM with GPT-4o-mini outperforms the pre-trained language model (PLM)-based SOTA methods (e.g., SMAT) by 69.20% and 21.97% in terms of precision and F1 score on the Synthea dataset, respectively. The results also demonstrate that our approach is more efficient in end-to-end schema matching, and scales to retrieve from large KGs. Our case studies on the dataset from the real-world schema matching scenario exhibit that the hallucination problem of LLMs for schema matching is well mitigated by our solution.

[Arxiv](https://arxiv.org/abs/2501.08686)