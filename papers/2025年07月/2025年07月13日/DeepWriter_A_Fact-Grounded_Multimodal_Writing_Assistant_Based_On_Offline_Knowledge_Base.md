# DeepWriter：一款基于离线知识库的多模态事实写作助手。

发布时间：2025年07月13日

`LLM应用` `写作助手`

> DeepWriter: A Fact-Grounded Multimodal Writing Assistant Based On Offline Knowledge Base

# 摘要

> 大型语言模型（LLMs）在多种应用场景中展现出了卓越的能力。然而，它们在金融、医学和法律等专业领域作为写作助手时，往往受限于缺乏深度专业知识和容易产生幻觉的问题。现有的解决方案如检索增强生成（RAG）可能在多个检索步骤中出现不一致，而基于在线搜索的方法则常因网络内容的不可靠性而导致质量下降。为解决这些问题，我们推出了DeepWriter——一款基于策划的离线知识库、定制化且支持多模态的长篇写作助手。DeepWriter采用了创新的任务分解、大纲生成、多模态检索及分节落撰写流水线，并融入了反思机制。通过深度挖掘结构化语料库中的信息，并结合文本与视觉元素，DeepWriter能够生成连贯、事实严谨且达到专业水准的文档。此外，我们还提出了一种层级知识表示方法，以进一步提升检索效率与准确性。实验结果表明，在财务报告生成任务中，DeepWriter不仅能够生成高质量且可验证的文章，其在事实准确性和内容质量上均超越了现有基线模型。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in various applications. However, their use as writing assistants in specialized domains like finance, medicine, and law is often hampered by a lack of deep domain-specific knowledge and a tendency to hallucinate. Existing solutions, such as Retrieval-Augmented Generation (RAG), can suffer from inconsistency across multiple retrieval steps, while online search-based methods often degrade quality due to unreliable web content. To address these challenges, we introduce DeepWriter, a customizable, multimodal, long-form writing assistant that operates on a curated, offline knowledge base. DeepWriter leverages a novel pipeline that involves task decomposition, outline generation, multimodal retrieval, and section-by-section composition with reflection. By deeply mining information from a structured corpus and incorporating both textual and visual elements, DeepWriter generates coherent, factually grounded, and professional-grade documents. We also propose a hierarchical knowledge representation to enhance retrieval efficiency and accuracy. Our experiments on financial report generation demonstrate that DeepWriter produces high-quality, verifiable articles that surpasses existing baselines in factual accuracy and generated content quality.

[Arxiv](https://arxiv.org/abs/2507.14189)