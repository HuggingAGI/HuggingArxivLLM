# 用于幻觉缓解的混合检索方法在大型语言模型中的比较分析

发布时间：2025年02月28日

`RAG` `信息检索` `问答系统`

> Hybrid Retrieval for Hallucination Mitigation in Large Language Models: A Comparative Analysis

# 摘要

> 大型语言模型（LLMs）在语言理解和生成方面表现出色，但容易产生幻觉，输出事实错误或缺乏支持的信息。检索增强生成（RAG）系统通过将外部知识融入LLM的响应来解决这一问题。本研究评估了三种检索方法对LLMs幻觉减少的影响：基于BM25关键词搜索的稀疏检索、使用Sentence Transformers进行语义搜索的密集检索，以及一种新提出的混合检索模块。该混合模块包含查询扩展，并通过动态加权的互惠排名融合得分结合稀疏和密集检索器的结果。利用HaluBench数据集（问答任务中幻觉的基准），我们采用平均平均精度和归一化折扣累积增益等指标评估检索性能，重点关注前三个检索文档的相关性。结果显示，混合检索器在相关性得分上表现更优，超越了稀疏和密集检索器。进一步评估LLM生成答案与真实答案的准确性、幻觉率和拒绝率，发现混合检索器在准确性方面表现最佳，幻觉率和拒绝率最低。这些发现突显了混合检索器在提升检索相关性、降低幻觉率和增强LLM可靠性方面的有效性，强调了先进检索技术在减少幻觉和提高响应准确性中的重要性。

> Large Language Models (LLMs) excel in language comprehension and generation but are prone to hallucinations, producing factually incorrect or unsupported outputs. Retrieval Augmented Generation (RAG) systems address this issue by grounding LLM responses with external knowledge. This study evaluates the relationship between retriever effectiveness and hallucination reduction in LLMs using three retrieval approaches: sparse retrieval based on BM25 keyword search, dense retrieval using semantic search with Sentence Transformers, and a proposed hybrid retrieval module. The hybrid module incorporates query expansion and combines the results of sparse and dense retrievers through a dynamically weighted Reciprocal Rank Fusion score. Using the HaluBench dataset, a benchmark for hallucinations in question answering tasks, we assess retrieval performance with metrics such as mean average precision and normalised discounted cumulative gain, focusing on the relevance of the top three retrieved documents. Results show that the hybrid retriever achieves better relevance scores, outperforming both sparse and dense retrievers. Further evaluation of LLM-generated answers against ground truth using metrics such as accuracy, hallucination rate, and rejection rate reveals that the hybrid retriever achieves the highest accuracy on fails, the lowest hallucination rate, and the lowest rejection rate. These findings highlight the hybrid retriever's ability to enhance retrieval relevance, reduce hallucination rates, and improve LLM reliability, emphasising the importance of advanced retrieval techniques in mitigating hallucinations and improving response accuracy.

[Arxiv](https://arxiv.org/abs/2504.05324)