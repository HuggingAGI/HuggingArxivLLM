# MultiRAG：一个多源检索增强生成的知识引导框架，致力于缓解生成中的幻觉问题。

发布时间：2025年08月05日

`RAG` `信息检索` `知识图谱`

> MultiRAG: A Knowledge-guided Framework for Mitigating Hallucination in Multi-source Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）作为一种有前景的解决方案，旨在解决大型语言模型（LLMs）中的幻觉问题。然而，尽管整合多源检索信息可能更具信息量，但这带来了新的挑战，这些挑战可能反而加剧幻觉问题。这些问题主要体现在两个方面：多源数据的稀疏分布阻碍了逻辑关系的捕捉，以及不同来源之间固有的不一致性导致信息冲突。为应对这些挑战，我们提出了一种名为MultiRAG的新框架，该框架旨在通过知识引导的方法来减轻多源检索增强生成中的幻觉问题。我们的框架引入了两大关键创新：(1) 一个知识构建模块，该模块利用多源线图高效聚合不同知识源之间的逻辑关系，有效解决了数据分布稀疏的问题；(2) 一个复杂的检索模块，该模块实现了一种多层次置信度计算机制，在图级别和节点级别进行评估，以识别并消除不可靠的信息节点，从而减少因来源间不一致导致的幻觉。在四个多领域查询数据集和两个多跳问答数据集上的广泛实验表明，MultiRAG显著提升了复杂多源场景下知识检索的可靠性和效率。我们的代码可在https://github.com/wuwenlong123/MultiRAG获取。


> Retrieval Augmented Generation (RAG) has emerged as a promising solution to address hallucination issues in Large Language Models (LLMs). However, the integration of multiple retrieval sources, while potentially more informative, introduces new challenges that can paradoxically exacerbate hallucination problems. These challenges manifest primarily in two aspects: the sparse distribution of multi-source data that hinders the capture of logical relationships and the inherent inconsistencies among different sources that lead to information conflicts. To address these challenges, we propose MultiRAG, a novel framework designed to mitigate hallucination in multi-source retrieval-augmented generation through knowledge-guided approaches. Our framework introduces two key innovations: (1) a knowledge construction module that employs multi-source line graphs to efficiently aggregate logical relationships across different knowledge sources, effectively addressing the sparse data distribution issue; and (2) a sophisticated retrieval module that implements a multi-level confidence calculation mechanism, performing both graph-level and node-level assessments to identify and eliminate unreliable information nodes, thereby reducing hallucinations caused by inter-source inconsistencies. Extensive experiments on four multi-domain query datasets and two multi-hop QA datasets demonstrate that MultiRAG significantly enhances the reliability and efficiency of knowledge retrieval in complex multi-source scenarios. \textcolor{blue}{Our code is available in https://github.com/wuwenlong123/MultiRAG.

[Arxiv](https://arxiv.org/abs/2508.03553)