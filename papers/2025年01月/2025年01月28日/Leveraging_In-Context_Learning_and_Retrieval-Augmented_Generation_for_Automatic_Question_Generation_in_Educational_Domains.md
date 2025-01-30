# 结合上下文学习与检索增强生成，实现教育领域的自动问题生成

发布时间：2025年01月28日

`RAG

理由：这篇论文主要探讨了在教育场景下使用检索增强生成（RAG）和上下文学习（ICL）技术来生成高质量的问题。虽然也提到了GPT-4（LLM），但研究的核心是RAG技术的应用和改进，因此将其归类为RAG更为合适。` `问题生成`

> Leveraging In-Context Learning and Retrieval-Augmented Generation for Automatic Question Generation in Educational Domains

# 摘要

> # 摘要
教育领域的问题生成既耗时又费脑，因为它需要创建既贴合上下文又符合教育学原理的问题。然而，现有的自动化方法常常生成与上下文脱节的问题。本研究探索了教育场景下的高级问题生成技术，重点研究了上下文学习（ICL）、检索增强生成（RAG）以及一种结合两者的新型混合模型。我们使用少量示例实现了GPT-4的ICL，并通过带有检索模块的BART实现了RAG。混合模型结合了RAG和ICL的优势，有效提升了问题质量。评估采用自动化指标和人工评估相结合的方式。结果显示，ICL方法和混合模型在生成更准确、更相关的问题方面表现优异，远超基线模型。

> Question generation in education is a time-consuming and cognitively demanding task, as it requires creating questions that are both contextually relevant and pedagogically sound. Current automated question generation methods often generate questions that are out of context. In this work, we explore advanced techniques for automated question generation in educational contexts, focusing on In-Context Learning (ICL), Retrieval-Augmented Generation (RAG), and a novel Hybrid Model that merges both methods. We implement GPT-4 for ICL using few-shot examples and BART with a retrieval module for RAG. The Hybrid Model combines RAG and ICL to address these issues and improve question quality. Evaluation is conducted using automated metrics, followed by human evaluation metrics. Our results show that both the ICL approach and the Hybrid Model consistently outperform other methods, including baseline models, by generating more contextually accurate and relevant questions.

[Arxiv](https://arxiv.org/abs/2501.17397)