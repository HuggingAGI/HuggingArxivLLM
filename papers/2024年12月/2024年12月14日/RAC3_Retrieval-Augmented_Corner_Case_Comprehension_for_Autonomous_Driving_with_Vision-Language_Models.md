# RAC3: 利用视觉-语言模型进行检索增强的自动驾驶角点案例理解

发布时间：2024年12月14日

`RAG

理由：这篇论文提出了RAC3框架，该框架集成了检索增强生成（RAG）技术，通过动态整合上下文相关的外部知识来缓解视觉-语言模型（VLMs）在处理极端情况时的幻觉问题。RAG是论文的核心技术，因此将其分类为RAG是合适的。` `自动驾驶` `视觉-语言模型`

> RAC3: Retrieval-Augmented Corner Case Comprehension for Autonomous Driving with Vision-Language Models

# 摘要

> # 摘要
理解和应对极端情况是确保自动驾驶系统安全可靠的关键。视觉-语言模型（VLMs）在提升场景理解能力方面至关重要，但它们面临幻觉和现实基础不足等挑战，影响其在关键驾驶场景中的表现。本研究提出RAC3框架，旨在提升VLMs处理极端情况的能力。RAC3集成了检索增强生成（RAG），通过动态整合上下文相关的外部知识来缓解幻觉。其核心是跨模态对齐微调，利用对比学习将图像-文本对嵌入统一语义空间，实现类似场景的稳健检索。我们通过精心设计的极端情况数据集进行广泛实验，验证了RAC3在增强语义对齐、缓解幻觉及提升性能指标（如余弦相似度和ROUGE-L分数）方面的显著效果。例如，LLaVA-v1.6-34B VLM的生成文本与参考文本的余弦相似度提升了5.22%，ROUGE-L的F1分数提升了39.91%，精确度提升了55.80%，召回率提升了13.74%。这项研究展示了检索增强VLMs在复杂环境中提升自动驾驶鲁棒性和安全性的巨大潜力。

> Understanding and addressing corner cases is essential for ensuring the safety and reliability of autonomous driving systems. Vision-Language Models (VLMs) play a crucial role in enhancing scenario comprehension, yet they face significant challenges, such as hallucination and insufficient real-world grounding, which compromise their performance in critical driving scenarios. In this work, we propose RAC3, a novel framework designed to improve VLMs' ability to handle corner cases effectively. The framework integrates Retrieval-Augmented Generation (RAG) to mitigate hallucination by dynamically incorporating context-specific external knowledge. A cornerstone of RAC3 is its cross-modal alignment fine-tuning, which utilizes contrastive learning to embed image-text pairs into a unified semantic space, enabling robust retrieval of similar scenarios. We evaluate RAC3 through extensive experiments using a curated dataset of corner case scenarios, demonstrating its ability to enhance semantic alignment, improve hallucination mitigation, and achieve superior performance metrics, such as Cosine Similarity and ROUGE-L scores. For example, for the LLaVA-v1.6-34B VLM, the cosine similarity between the generated text and the reference text has increased by 5.22\%. The F1-score in ROUGE-L has increased by 39.91\%, the Precision has increased by 55.80\%, and the Recall has increased by 13.74\%. This work underscores the potential of retrieval-augmented VLMs to advance the robustness and safety of autonomous driving in complex environments.

[Arxiv](https://arxiv.org/abs/2412.11050)