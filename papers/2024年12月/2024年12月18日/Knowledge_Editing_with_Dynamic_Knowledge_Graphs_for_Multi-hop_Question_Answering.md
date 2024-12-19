# 利用动态知识图谱进行知识编辑以实现多跳问答

发布时间：2024年12月18日

`LLM应用` `问答系统` `知识编辑`

> Knowledge Editing with Dynamic Knowledge Graphs for Multi-hop Question Answering

# 摘要

> 多跳问答（MHQA）因所需知识广泛，给大型语言模型（LLMs）带来了重大挑战。知识编辑旨在精准修改LLMs以融入特定知识，且不影响其他无关知识，为应对LLMs的MHQA难题提供了可能的解决办法。然而，现有的方案难以有效化解知识冲突问题。多数保留参数的编辑方法受不准确检索的阻碍，还忽视了二次编辑问题，这可能给LLMs的推理过程引入噪声。在本文中，我们推出了KEDKG，这是一种用于MHQA的新型知识编辑方法，借助动态知识图来保障答案的可靠性。KEDKG包含两个主要步骤：动态知识图构建和知识图增强生成。首先，KEDKG自主构建动态知识图来存储修订信息，并解决潜在的知识冲突。接着，它采用精细的检索策略以及实体和关系检测器，以提升LLM生成时的图检索准确性。在基准测试中的实验结果显示，KEDKG超越了以往的最先进模型，在动态信息环境中给出了更准确、更可靠的答案。

> Multi-hop question answering (MHQA) poses a significant challenge for large language models (LLMs) due to the extensive knowledge demands involved. Knowledge editing, which aims to precisely modify the LLMs to incorporate specific knowledge without negatively impacting other unrelated knowledge, offers a potential solution for addressing MHQA challenges with LLMs. However, current solutions struggle to effectively resolve issues of knowledge conflicts. Most parameter-preserving editing methods are hindered by inaccurate retrieval and overlook secondary editing issues, which can introduce noise into the reasoning process of LLMs. In this paper, we introduce KEDKG, a novel knowledge editing method that leverages a dynamic knowledge graph for MHQA, designed to ensure the reliability of answers. KEDKG involves two primary steps: dynamic knowledge graph construction and knowledge graph augmented generation. Initially, KEDKG autonomously constructs a dynamic knowledge graph to store revised information while resolving potential knowledge conflicts. Subsequently, it employs a fine-grained retrieval strategy coupled with an entity and relation detector to enhance the accuracy of graph retrieval for LLM generation. Experimental results on benchmarks show that KEDKG surpasses previous state-of-the-art models, delivering more accurate and reliable answers in environments with dynamic information.

[Arxiv](https://arxiv.org/abs/2412.13782)