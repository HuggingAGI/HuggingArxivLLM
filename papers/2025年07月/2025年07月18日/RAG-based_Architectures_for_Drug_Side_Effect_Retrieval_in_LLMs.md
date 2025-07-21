# 基于RAG的架构用于大型语言模型中的药物不良反应检索

发布时间：2025年07月18日

`RAG` `知识图谱`

> RAG-based Architectures for Drug Side Effect Retrieval in LLMs

# 摘要

> 药物不良反应是全球健康领域的重要问题，亟需先进的方法来进行准确的检测与分析。大型语言模型（LLMs）虽然提供了有前景的对话界面，但其固有的局限性，包括对黑箱训练数据的依赖、容易产生幻觉以及缺乏特定领域的专业知识，限制了其在药物警戒等专业领域的可靠性。为了解决这一问题，我们提出了检索增强生成（RAG）和图RAG两种架构，将全面的药物不良反应知识整合到Llama 3 8B语言模型中。通过在19,520个药物不良反应关联（涵盖976种药物和3,851个不良反应术语）上的广泛评估，我们的结果显示，图RAG在药物不良反应检索中达到了近乎完美的准确率。这一框架提供了一种高度准确且可扩展的解决方案，标志着在利用大型语言模型进行关键药物警戒应用方面取得了重大进展。

> Drug side effects are a major global health concern, necessitating advanced methods for their accurate detection and analysis. While Large Language Models (LLMs) offer promising conversational interfaces, their inherent limitations, including reliance on black-box training data, susceptibility to hallucinations, and lack of domain-specific knowledge, hinder their reliability in specialized fields like pharmacovigilance. To address this gap, we propose two architectures: Retrieval-Augmented Generation (RAG) and GraphRAG, which integrate comprehensive drug side effect knowledge into a Llama 3 8B language model. Through extensive evaluations on 19,520 drug side effect associations (covering 976 drugs and 3,851 side effect terms), our results demonstrate that GraphRAG achieves near-perfect accuracy in drug side effect retrieval. This framework offers a highly accurate and scalable solution, signifying a significant advancement in leveraging LLMs for critical pharmacovigilance applications.

[Arxiv](https://arxiv.org/abs/2507.13822)