# 一种基于图的方法，用于在现实应用中实现会话式人工智能驱动的个人记忆捕获与检索

发布时间：2024年12月06日

`RAG` `移动应用` `个人记忆`

> A Graph-Based Approach for Conversational AI-Driven Personal Memory Capture and Retrieval in a Real-world Application

# 摘要

> TOBU 是一款新颖的移动应用，它通过用户参与的 AI 引导式对话来捕获和检索“个人记忆”（包括图片/视频以及相关时刻的故事和背景）。我们的初始原型显示，现有的检索技术，如检索增强生成（RAG）系统，因在理解记忆关系上存在局限，表现欠佳，导致召回率低、产生幻觉以及用户体验差。我们设计了 TOBUGraph，这是一种全新的基于图的检索方法。在捕获时，TOBUGraph 借助大型语言模型（LLMs）自动创建记忆的动态知识图，确立这些记忆的背景和关系。在检索时，TOBUGraph 将 LLMs 与记忆图相结合，通过图遍历实现全面召回。我们基于真实用户数据的评估表明，TOBUGraph 在精度和召回率上均优于多个 RAG 实现，通过提升检索准确性和减少幻觉，显著改善了用户体验。

> TOBU is a novel mobile application that captures and retrieves `personal memories' (pictures/videos together with stories and context around those moments) in a user-engaging AI-guided conversational approach. Our initial prototype showed that existing retrieval techniques such as retrieval-augmented generation (RAG) systems fall short due to their limitations in understanding memory relationships, causing low recall, hallucination, and unsatisfactory user experience. We design TOBUGraph, a novel graph-based retrieval approach. During capturing, TOBUGraph leverages large language models (LLMs) to automatically create a dynamic knowledge graph of memories, establishing context and relationships of those memories. During retrieval, TOBUGraph combines LLMs with the memory graph to achieve comprehensive recall through graph traversal. Our evaluation using real user data demonstrates that TOBUGraph outperforms multiple RAG implementations in both precision and recall, significantly improving user experience through improved retrieval accuracy and reduced hallucination.

[Arxiv](https://arxiv.org/abs/2412.05447)