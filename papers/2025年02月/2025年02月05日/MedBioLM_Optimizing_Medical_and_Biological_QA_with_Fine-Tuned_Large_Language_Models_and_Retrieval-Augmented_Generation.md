# MedBioLM：利用微调大型语言模型与检索增强生成技术，优化医学和生物学问答

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何通过微调和检索增强生成（RAG）技术来优化大型语言模型（LLMs）在生物医学领域的应用。具体来说，论文介绍了MedBioLM模型，该模型专为生物医学问答设计，能够处理短篇和长篇查询，并通过结合微调和RAG技术来提升推理能力和准确性。这些内容明显属于LLM在实际应用中的优化和改进，因此应归类为“LLM应用”。` `生物医学`

> MedBioLM: Optimizing Medical and Biological QA with Fine-Tuned Large Language Models and Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，但在医学和生物学等专业领域的应用仍需优化，以确保准确性、可靠性和深度。我们推出了MedBioLM，一个专为生物医学问答设计的模型，能够处理短篇和长篇查询。通过结合微调和检索增强生成（RAG），MedBioLM动态整合领域知识，提升推理能力和准确性。我们在多种生物医学QA数据集上对模型进行了微调，包括结构化选择题和复杂临床推理任务。微调显著提升了基准数据集的准确性，而RAG则增强了事实一致性。这些成果展示了领域优化LLMs在推动生物医学研究、医学教育和临床决策支持方面的巨大潜力。

> Large Language Models (LLMs) have demonstrated impressive capabilities across natural language processing tasks. However, their application to specialized domains such as medicine and biology requires further optimization to ensure factual accuracy, reliability, and contextual depth. We introduce MedBioLM, a domain-adapted biomedical question-answering model designed to enhance both short-form and long-form queries. By integrating fine-tuning and retrieval-augmented generation (RAG), MedBioLM dynamically incorporates domain-specific knowledge, improving reasoning abilities and factual accuracy. To evaluate its effectiveness, we fine-tuned the model on diverse biomedical QA datasets, covering structured multiple-choice assessments and complex clinical reasoning tasks. Fine-tuning significantly improves accuracy on benchmark datasets, while RAG enhances factual consistency. These results highlight the potential of domain-optimized LLMs in advancing biomedical research, medical education, and clinical decision support.

[Arxiv](https://arxiv.org/abs/2502.03004)