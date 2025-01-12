# 迈向全能RAG：医疗应用中大型语言模型的全面检索增强生成

发布时间：2025年01月05日

`RAG

理由：这篇论文主要讨论了如何通过整合外部医学知识来提升大型语言模型（LLMs）在医疗领域的应用效果。具体来说，论文提出了一个综合知识库（MedOmniKB）和源规划优化（SPO）方法，以优化多源知识的利用效率。这些内容涉及到从外部知识源中检索信息并整合到LLMs中，属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴。因此，这篇论文应被分类为RAG。` `知识库`

> Towards Omni-RAG: Comprehensive Retrieval-Augmented Generation for Large Language Models in Medical Applications

# 摘要

> 大型语言模型（LLMs）在应对医疗挑战方面展现出巨大潜力，但由于医学知识的整合不足，常常产生幻觉。因此，整合外部医学知识显得尤为重要，尤其是考虑到医学内容的广度和复杂性，这需要高效的多源知识获取。我们将这一挑战转化为源规划问题，目标是制定适合上下文的查询，以适应不同知识源的特性。现有方法要么忽略了源规划，要么因模型对知识源的期望与其实际内容不匹配而未能有效实现。为此，我们推出了MedOmniKB，一个涵盖多类型和多结构医学知识源的综合知识库。基于这些知识源，我们提出了源规划优化（SPO）方法，通过显式规划优化提升多源利用效率。我们的方法让专家模型探索和评估潜在计划，同时训练一个小模型通过正负规划样本学习源对齐。实验结果显示，我们的方法显著提升了多源规划性能，使优化后的小模型在利用多样化医学知识源方面达到了业界领先水平。

> Large language models (LLMs) hold promise for addressing healthcare challenges but often generate hallucinations due to limited integration of medical knowledge. Incorporating external medical knowledge is therefore critical, especially considering the breadth and complexity of medical content, which necessitates effective multi-source knowledge acquisition. We address this challenge by framing it as a source planning problem, where the task is to formulate context-appropriate queries tailored to the attributes of diverse knowledge sources. Existing approaches either overlook source planning or fail to achieve it effectively due to misalignment between the model's expectation of the sources and their actual content. To bridge this gap, we present MedOmniKB, a comprehensive repository comprising multigenre and multi-structured medical knowledge sources. Leveraging these sources, we propose the Source Planning Optimisation (SPO) method, which enhances multi-source utilisation through explicit planning optimisation. Our approach involves enabling an expert model to explore and evaluate potential plans while training a smaller model to learn source alignment using positive and negative planning samples. Experimental results demonstrate that our method substantially improves multi-source planning performance, enabling the optimised small model to achieve state-of-the-art results in leveraging diverse medical knowledge sources.

[Arxiv](https://arxiv.org/abs/2501.02460)