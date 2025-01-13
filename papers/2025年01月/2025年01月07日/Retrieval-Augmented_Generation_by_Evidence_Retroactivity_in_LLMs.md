# 基于证据回溯的检索增强生成在LLMs中的应用

发布时间：2025年01月07日

`RAG

理由：这篇论文主要讨论了检索增强生成（RetroRAG）方法，通过回溯推理范式来修正和更新证据，重新导向推理链，从而提升LLMs的响应准确性和可靠性。这属于RAG（Retrieval-Augmented Generation）领域的研究，因为它涉及如何通过检索外部知识来增强生成过程。` `信息检索`

> Retrieval-Augmented Generation by Evidence Retroactivity in LLMs

# 摘要

> 检索增强生成因其整合外部知识、提升LLMs响应准确性和可靠性的能力而备受瞩目。现有方法多采用动态多重检索-生成过程，通过分解多跳复杂问题来解决。然而，这些方法依赖单向前向推理，推理步骤不足或检索系统固有缺陷导致的错误不可逆，可能破坏整个推理链。本文首次提出回溯检索增强生成（RetroRAG），构建回溯推理范式。RetroRAG修正并更新证据，重新导向推理链。它通过证据整理-发现框架搜索、生成和精炼可信证据，综合问题中关键实体的推理证据，并制定搜索查询以发现更多信息。随着新证据的发现，RetroRAG不断更新和组织信息，增强定位必要证据的能力。与生成和评估输出的回答器配对，RetroRAG能迭代精炼推理过程，直至获得可靠答案。实证评估显示，RetroRAG显著优于现有方法。

> Retrieval-augmented generation has gained significant attention due to its ability to integrate relevant external knowledge, enhancing the accuracy and reliability of the LLMs' responses. Most of the existing methods apply a dynamic multiple retrieval-generating process, to address multi-hop complex questions by decomposing them into sub-problems. However, these methods rely on an unidirectional forward reasoning paradigm, where errors from insufficient reasoning steps or inherent flaws in current retrieval systems are irreversible, potentially derailing the entire reasoning chain. For the first time, this work introduces Retroactive Retrieval-Augmented Generation (RetroRAG), a novel framework to build a retroactive reasoning paradigm. RetroRAG revises and updates the evidence, redirecting the reasoning chain to the correct direction. RetroRAG constructs an evidence-collation-discovery framework to search, generate, and refine credible evidence. It synthesizes inferential evidence related to the key entities in the question from the existing source knowledge and formulates search queries to uncover additional information. As new evidence is found, RetroRAG continually updates and organizes this information, enhancing its ability to locate further necessary evidence. Paired with an Answerer to generate and evaluate outputs, RetroRAG is capable of refining its reasoning process iteratively until a reliable answer is obtained. Empirical evaluations show that RetroRAG significantly outperforms existing methods.

[Arxiv](https://arxiv.org/abs/2501.05475)