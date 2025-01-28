# URAG: 在大学招生聊天机器人中实现统一混合RAG，精准解答 -- HCMUT案例研究

发布时间：2025年01月27日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）技术在教育问答系统中的应用，特别是通过提出统一RAG（URAG）框架来提升回答的准确性。论文的核心内容围绕RAG技术的改进和应用，因此应归类为RAG。` `问答系统`

> URAG: Implementing a Unified Hybrid RAG for Precise Answers in University Admission Chatbots -- A Case Study at HCMUT

# 摘要

> 随着人工智能，尤其是自然语言处理的飞速发展，大型语言模型（LLMs）在教育问答系统中扮演了关键角色，特别是在大学招生聊天机器人中。检索增强生成（RAG）等先进技术通过整合特定大学的数据，显著提升了这些系统的性能，使LLMs能够提供精准的招生和学术咨询回答。然而，这些增强的RAG技术往往伴随着高昂的运营成本和复杂的专门模块训练，给实际部署带来了挑战。此外，在教育场景中，提供准确答案以防止错误信息至关重要，而基于LLM的系统在没有适当策略和方法的情况下难以胜任这一任务。本文提出了统一RAG（URAG）框架，这一混合方法显著提升了回答的准确性，特别是在处理关键查询时。实验结果显示，URAG使我们内部的轻量级模型能够与顶尖商业模型相媲美。此外，我们在教育机构进行的案例研究也获得了积极反馈，进一步验证了URAG的实际应用价值。这项研究不仅证明了URAG的有效性，还展示了其在教育环境中实际部署的可行性。

> With the rapid advancement of Artificial Intelligence, particularly in Natural Language Processing, Large Language Models (LLMs) have become pivotal in educational question-answering systems, especially university admission chatbots. Concepts such as Retrieval-Augmented Generation (RAG) and other advanced techniques have been developed to enhance these systems by integrating specific university data, enabling LLMs to provide informed responses on admissions and academic counseling. However, these enhanced RAG techniques often involve high operational costs and require the training of complex, specialized modules, which poses challenges for practical deployment. Additionally, in the educational context, it is crucial to provide accurate answers to prevent misinformation, a task that LLM-based systems find challenging without appropriate strategies and methods. In this paper, we introduce the Unified RAG (URAG) Framework, a hybrid approach that significantly improves the accuracy of responses, particularly for critical queries. Experimental results demonstrate that URAG enhances our in-house, lightweight model to perform comparably to state-of-the-art commercial models. Moreover, to validate its practical applicability, we conducted a case study at our educational institution, which received positive feedback and acclaim. This study not only proves the effectiveness of URAG but also highlights its feasibility for real-world implementation in educational settings.

[Arxiv](https://arxiv.org/abs/2501.16276)