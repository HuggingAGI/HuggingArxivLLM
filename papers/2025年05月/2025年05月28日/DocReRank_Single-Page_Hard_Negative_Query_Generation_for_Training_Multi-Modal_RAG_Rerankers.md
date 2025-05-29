# DocReRank：单页困难负查询生成，用于训练多模态RAG重排器

发布时间：2025年05月28日

`RAG` `信息检索` `多模态`

> DocReRank: Single-Page Hard Negative Query Generation for Training Multi-Modal RAG Rerankers

# 摘要

> 重排器在多模态检索增强生成（RAG）中发挥关键作用，通过优化初始检索文档的排名来提升生成质量。传统方法中，重排器通常采用硬负挖掘进行训练，旨在为每个查询选择那些排名靠前但实际无关的页面。然而，这种被动选择过程受限于检索器的能力，导致了多重局限：多样性不足、负样本强度不够、可控性低，以及频繁的误判负样本影响训练效果。针对这些问题，我们提出了一种开创性的方法：单页硬负查询生成。与传统方法不同，我们不是为每个查询寻找负样本页面，而是为每个页面生成硬负查询。通过自动化LLM-VLM流水线，给定一个页面及其正向查询，我们会将其改写为形式和上下文相似但无法从页面中获得答案的查询。这种范式实现了对生成查询的精细控制，生成多样、困难且有针对性的负样本，同时支持高效的误判负样本验证。实验结果表明，采用我们方法生成的数据训练的重排器显著超越现有模型，并在检索性能上带来显著提升。

> Rerankers play a critical role in multimodal Retrieval-Augmented Generation (RAG) by refining ranking of an initial set of retrieved documents. Rerankers are typically trained using hard negative mining, whose goal is to select pages for each query which rank high, but are actually irrelevant. However, this selection process is typically passive and restricted to what the retriever can find in the available corpus, leading to several inherent limitations. These include: limited diversity, negative examples which are often not hard enough, low controllability, and frequent false negatives which harm training. Our paper proposes an alternative approach: Single-Page Hard Negative Query Generation, which goes the other way around. Instead of retrieving negative pages per query, we generate hard negative queries per page. Using an automated LLM-VLM pipeline, and given a page and its positive query, we create hard negatives by rephrasing the query to be as similar as possible in form and context, yet not answerable from the page. This paradigm enables fine-grained control over the generated queries, resulting in diverse, hard, and targeted negatives. It also supports efficient false negative verification. Our experiments show that rerankers trained with data generated using our approach outperform existing models and significantly improve retrieval performance.

[Arxiv](https://arxiv.org/abs/2505.22584)