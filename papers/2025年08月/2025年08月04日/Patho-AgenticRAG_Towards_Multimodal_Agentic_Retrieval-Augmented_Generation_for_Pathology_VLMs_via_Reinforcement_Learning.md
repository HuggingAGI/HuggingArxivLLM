# Patho-AgenticRAG：迈向病理视觉语言模型的多模态智能体增强生成之路，通过强化学习实现

发布时间：2025年08月04日

`RAG` `医学成像`

> Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs via Reinforcement Learning

# 摘要

> 尽管视觉语言模型（VLMs）在医学成像领域表现优异，但病理学的超高分辨率、复杂组织结构和微妙临床语义带来了独特挑战。这些因素使得病理学VLMs容易产生幻觉，即生成与视觉证据不符的输出，从而削弱临床信任。现有RAG方法主要依赖文本知识库，难以充分利用诊断视觉线索。为此，我们提出了Patho-AgenticRAG，这是一个基于权威病理学教科书页面级嵌入构建数据库的多模态RAG框架。与传统仅基于文本的检索系统不同，它支持联合文本-图像搜索，能够直接检索到同时包含查询文本和相关视觉线索的教科书页面，避免了关键图像信息的丢失。Patho-AgenticRAG还支持推理、任务分解和多轮搜索交互，在复杂诊断场景中显著提高了准确性。实验表明，Patho-AgenticRAG在多选诊断和视觉问答等复杂病理任务中大幅优于现有模型。项目地址：https://github.com/Wenchuan-Zhang/Patho-AgenticRAG.

> Although Vision Language Models (VLMs) have shown strong generalization in medical imaging, pathology presents unique challenges due to ultra-high resolution, complex tissue structures, and nuanced clinical semantics. These factors make pathology VLMs prone to hallucinations, i.e., generating outputs inconsistent with visual evidence, which undermines clinical trust. Existing RAG approaches in this domain largely depend on text-based knowledge bases, limiting their ability to leverage diagnostic visual cues. To address this, we propose Patho-AgenticRAG, a multimodal RAG framework with a database built on page-level embeddings from authoritative pathology textbooks. Unlike traditional text-only retrieval systems, it supports joint text-image search, enabling direct retrieval of textbook pages that contain both the queried text and relevant visual cues, thus avoiding the loss of critical image-based information. Patho-AgenticRAG also supports reasoning, task decomposition, and multi-turn search interactions, improving accuracy in complex diagnostic scenarios. Experiments show that Patho-AgenticRAG significantly outperforms existing multimodal models in complex pathology tasks like multiple-choice diagnosis and visual question answering. Our project is available at the Patho-AgenticRAG repository: https://github.com/Wenchuan-Zhang/Patho-AgenticRAG.

[Arxiv](https://arxiv.org/abs/2508.02258)