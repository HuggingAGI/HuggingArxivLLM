# # 从三元视角看GraphRAG

发布时间：2025年04月28日

`RAG` `医疗保健` `知识图谱`

> A Tripartite Perspective on GraphRAG

# 摘要

> 大型语言模型（LLMs）在多领域表现出色，但在工业自动化和医疗保健等需要事实准确性的知识密集型领域仍显不足。其主要局限性包括易产生幻觉、缺乏来源可追溯性以及知识更新的及时性问题。将语言模型与知识图谱（GraphRAG）结合为克服这些局限提供了新思路。然而，构建此类知识图谱本身是一项巨大挑战。

我们提出了一种结合LLMs与三元知识图谱表示的新方法。该图谱通过基于精心策划的领域特定概念本体，将复杂、领域特定的对象连接到文本块中相关部分，从初始词汇图开始，通过对源文档进行基于概念的预分析。因此，我们的三元-GraphRAG方法实现了以下功能：i) 针对文本块的概念特定、信息保留的预压缩；ii) 允许基于统计学的概念特定嵌入相似性相关性估计；iii) 避免了与持续扩展相关的常见挑战，例如实体解析和去重的需要。

通过对知识图谱进行变换，我们将LLM提示创建公式化为无监督节点分类问题，借鉴了马尔可夫随机场的思想。我们在医疗保健领域进行了实验验证，涉及基于医学概念和临床文献对患者病史进行多维度分析。实验结果表明，该方法能够优化LLM提示的信息密度、覆盖范围和排列方式，同时缩短提示长度，从而降低成本，并使LLM输出更加一致和可靠。

> Large Language Models (LLMs) have shown remarkable capabilities across various domains, yet they struggle with knowledge-intensive tasks in areas that demand factual accuracy, e.g. industrial automation and healthcare. Key limitations include their tendency to hallucinate, lack of source traceability (provenance), and challenges in timely knowledge updates. Combining language models with knowledge graphs (GraphRAG) offers promising avenues for overcoming these deficits. However, a major challenge lies in creating such a knowledge graph in the first place. Here, we propose a novel approach that combines LLMs with a tripartite knowledge graph representation, which is constructed by connecting complex, domain-specific objects via a curated ontology of corresponding, domain-specific concepts to relevant sections within chunks of text through a concept-anchored pre-analysis of source documents starting from an initial lexical graph. As a consequence, our Tripartite-GraphRAG approach implements: i) a concept-specific, information-preserving pre-compression of textual chunks; ii) allows for the formation of a concept-specific relevance estimation of embedding similarities grounded in statistics; and iii) avoids common challenges w.r.t. continuous extendability, such as the need for entity resolution and deduplication. By applying a transformation to the knowledge graph, we formulate LLM prompt creation as an unsupervised node classification problem, drawing on ideas from Markov Random Fields. We evaluate our approach on a healthcare use case, involving multi-faceted analyses of patient anamneses given a set of medical concepts as well as clinical literature. Experiments indicate that it can optimize information density, coverage, and arrangement of LLM prompts while reducing their lengths, which may lead to reduced costs and more consistent and reliable LLM outputs.

[Arxiv](https://arxiv.org/abs/2504.19667)