# RbFT: 检索增强生成的鲁棒微调，应对检索缺陷

发布时间：2025年01月30日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）系统的性能提升问题，特别是通过鲁棒微调（RbFT）来增强LLMs对检索缺陷的抵抗力。因此，它属于RAG分类。` `人工智能`

> RbFT: Robust Fine-tuning for Retrieval-Augmented Generation against Retrieval Defects

# 摘要

> 检索增强生成（RAG）通过整合外部知识库中的信息来增强LLMs的性能。然而，其效果受限于检索器和知识库的可靠性。现实中，这些组件的不完美常导致检索到无关或误导性信息，影响RAG系统的可信度。为此，我们提出了鲁棒微调（RbFT），通过两个微调任务提升LLMs对检索缺陷的抵抗力。实验表明，RbFT在各种检索条件下显著提升了RAG系统的鲁棒性，超越了现有方法，同时保持了高效推理并兼容其他鲁棒性技术。

> Retrieval-augmented generation (RAG) enhances large language models (LLMs) by integrating external knowledge retrieved from a knowledge base. However, its effectiveness is fundamentally constrained by the reliability of both the retriever and the knowledge base. In real-world scenarios, imperfections in these components often lead to the retrieval of noisy, irrelevant, or misleading counterfactual information, ultimately undermining the trustworthiness of RAG systems. To address this challenge, we propose Robust Fine-Tuning (RbFT), a method designed to enhance the resilience of LLMs against retrieval defects through two targeted fine-tuning tasks. Experimental results demonstrate that RbFT significantly improves the robustness of RAG systems across diverse retrieval conditions, surpassing existing methods while maintaining high inference efficiency and compatibility with other robustness techniques.

[Arxiv](https://arxiv.org/abs/2501.18365)