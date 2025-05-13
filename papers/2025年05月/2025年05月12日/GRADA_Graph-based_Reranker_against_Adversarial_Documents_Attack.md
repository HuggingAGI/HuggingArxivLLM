# GRADA：基于图的对抗性文档攻击重排序器

发布时间：2025年05月12日

`RAG`

> GRADA: Graph-based Reranker against Adversarial Documents Attack

# 摘要

> 检索增强生成（RAG）框架通过整合外部知识显著提升了大型语言模型（LLMs）的准确性，突破了模型静态知识的局限。然而，这些系统易受对抗攻击，攻击者通过引入与查询语义相似但具有对抗性的文档来操纵检索过程。值得注意的是，尽管这些对抗性文档与查询相似，但它们与检索集中良性文档的相似度较低。因此，我们提出了一种简单而有效的基于图的对抗性文档攻击重排序框架（GRADA），旨在在显著降低攻击成功率的同时，保持检索质量。我们通过在五种大型语言模型上进行实验来评估方法的有效性：GPT-3.5-Turbo、GPT-4o、Llama3.1-8b、Llama3.1-70b 和 Qwen2.5-7b。使用三个数据集评估性能，来自自然问题数据集的结果显示，攻击成功率降低了高达80%，同时保持了极小的准确性损失。

> Retrieval Augmented Generation (RAG) frameworks improve the accuracy of large language models (LLMs) by integrating external knowledge from retrieved documents, thereby overcoming the limitations of models' static intrinsic knowledge. However, these systems are susceptible to adversarial attacks that manipulate the retrieval process by introducing documents that are adversarial yet semantically similar to the query. Notably, while these adversarial documents resemble the query, they exhibit weak similarity to benign documents in the retrieval set. Thus, we propose a simple yet effective Graph-based Reranking against Adversarial Document Attacks (GRADA) framework aiming at preserving retrieval quality while significantly reducing the success of adversaries. Our study evaluates the effectiveness of our approach through experiments conducted on five LLMs: GPT-3.5-Turbo, GPT-4o, Llama3.1-8b, Llama3.1-70b, and Qwen2.5-7b. We use three datasets to assess performance, with results from the Natural Questions dataset demonstrating up to an 80% reduction in attack success rates while maintaining minimal loss in accuracy.

[Arxiv](https://arxiv.org/abs/2505.07546)