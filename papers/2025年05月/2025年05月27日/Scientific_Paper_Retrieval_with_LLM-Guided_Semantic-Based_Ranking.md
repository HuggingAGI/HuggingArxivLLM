# # 科学论文检索：LLM引导的语义排序驱动

发布时间：2025年05月27日

`LLM应用` `学术研究` `信息检索`

> Scientific Paper Retrieval with LLM-Guided Semantic-Based Ranking

# 摘要

> 科学论文检索是支持文献发现和研究的关键。虽然密集检索方法在通用任务中表现优异，但它们往往难以捕捉到细粒度的科学概念，而这些概念对于准确理解科学查询至关重要。近期研究尝试利用大型语言模型（LLMs）进行查询理解，但这些方法常常缺乏基于语料库特定知识的支撑，容易生成不可靠或不忠实的内容。为了解决这些问题，我们提出了SemRank——一个结合了LLM引导的查询理解和基于概念的语义索引的有效且高效的论文检索框架。每篇论文都会通过多粒度的科学概念进行索引，包括一般研究主题和详细关键短语。在查询时，LLM能够识别出源自语料库的核心概念，从而精准捕捉查询的信息需求。这些核心概念的引入实现了精确的语义匹配，显著提升了检索准确性。实验结果表明，SemRank不仅显著提升了各种基础检索器的性能，还超越了现有的强LLM基线方法，同时保持了高度的效率。

> Scientific paper retrieval is essential for supporting literature discovery and research. While dense retrieval methods demonstrate effectiveness in general-purpose tasks, they often fail to capture fine-grained scientific concepts that are essential for accurate understanding of scientific queries. Recent studies also use large language models (LLMs) for query understanding; however, these methods often lack grounding in corpus-specific knowledge and may generate unreliable or unfaithful content. To overcome these limitations, we propose SemRank, an effective and efficient paper retrieval framework that combines LLM-guided query understanding with a concept-based semantic index. Each paper is indexed using multi-granular scientific concepts, including general research topics and detailed key phrases. At query time, an LLM identifies core concepts derived from the corpus to explicitly capture the query's information need. These identified concepts enable precise semantic matching, significantly enhancing retrieval accuracy. Experiments show that SemRank consistently improves the performance of various base retrievers, surpasses strong existing LLM-based baselines, and remains highly efficient.

[Arxiv](https://arxiv.org/abs/2505.21815)