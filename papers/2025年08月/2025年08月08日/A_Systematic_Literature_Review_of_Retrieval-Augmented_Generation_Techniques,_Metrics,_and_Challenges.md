# 生成式检索增强技术的系统综述——方法、挑战与评估指标

发布时间：2025年08月08日

`RAG

理由：这篇论文是关于检索增强生成（RAG）的系统综述，分析了相关文献，探讨了RAG的架构、数据集、评估方法以及其有效性和局限性，属于RAG领域。` `信息检索` `问答系统`

> A Systematic Literature Review of Retrieval-Augmented Generation: Techniques, Metrics, and Challenges

# 摘要

> 本系统综述聚焦分析了2020年至2025年5月期间发表的高被引检索增强生成（RAG）研究文献，共筛选出128篇符合标准的文章。研究数据来源于ACM数字图书馆、IEEE Xplore、Scopus、ScienceDirect及DBLP。RAG通过结合神经检索器与生成式语言模型，在保持模型语义泛化能力的同时，使输出基于最新非参数记忆。遵循PRISMA 2020框架，我们（i）制定了基于被引次数和研究问题的明确纳入排除标准，（ii）分类整理了数据集、架构及评估实践，（iii）综合了RAG有效性和局限性的实证证据。为缓解引文滞后偏见，我们对2025年论文采用了较低引文阈值，确保新兴突破被纳入考量。本综述阐明了当前研究格局，突出了方法学差距，并为未来研究指明了方向。

> This systematic review of the research literature on retrieval-augmented generation (RAG) provides a focused analysis of the most highly cited studies published between 2020 and May 2025. A total of 128 articles met our inclusion criteria. The records were retrieved from ACM Digital Library, IEEE Xplore, Scopus, ScienceDirect, and the Digital Bibliography and Library Project (DBLP). RAG couples a neural retriever with a generative language model, grounding output in up-to-date, non-parametric memory while retaining the semantic generalisation stored in model weights. Guided by the PRISMA 2020 framework, we (i) specify explicit inclusion and exclusion criteria based on citation count and research questions, (ii) catalogue datasets, architectures, and evaluation practices, and (iii) synthesise empirical evidence on the effectiveness and limitations of RAG. To mitigate citation-lag bias, we applied a lower citation-count threshold to papers published in 2025 so that emerging breakthroughs with naturally fewer citations were still captured. This review clarifies the current research landscape, highlights methodological gaps, and charts priority directions for future research.

[Arxiv](https://arxiv.org/abs/2508.06401)