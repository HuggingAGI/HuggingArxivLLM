# 面向RAG的LLM集成：上下文长度在BioASQ挑战赛零样本问答任务中的作用

发布时间：2025年09月10日

`RAG` `医疗健康`

> LLM Ensemble for RAG: Role of Context Length in Zero-Shot Question Answering for BioASQ Challenge

# 摘要

> 生物医学问答（QA）颇具挑战：其核心在于需从海量、复杂且快速更新的专业语料中精准解读特定知识。本研究探索了大型语言模型（LLMs）在信息检索（IR）中的应用，并验证了零样本模型集成在特定领域是/否问答任务上的最先进性能。在BioASQ挑战任务上的评估显示，模型集成不仅优于单个LLM，在部分场景下甚至可媲美或超越领域微调系统——且全程保持泛化能力，无需高昂的微调成本或标记数据。我们的方法通过聚合多个LLM变体（包括Anthropic和Google的模型）的输出，合成更准确、更稳健的答案。此外，研究还揭示了上下文长度与性能的关联：扩展上下文虽能提供更多有效证据，却可能导致信息稀释和模型“迷失方向”。这些发现表明，信息检索（IR）是生物医学问答系统中检索增强生成（RAG）方法的核心基础。精确聚焦的检索对于确保LLM在生成答案时不超出检索文档的相关信息边界至关重要。研究结果证实，基于集成的零样本方法与高效RAG管道结合，可作为生物医学问答领域微调系统的实用且可扩展替代方案。

> Biomedical question answering (QA) poses significant challenges due to the need for precise interpretation of specialized knowledge drawn from a vast, complex, and rapidly evolving corpus. In this work, we explore how large language models (LLMs) can be used for information retrieval (IR), and an ensemble of zero-shot models can accomplish state-of-the-art performance on a domain-specific Yes/No QA task. Evaluating our approach on the BioASQ challenge tasks, we show that ensembles can outperform individual LLMs and in some cases rival or surpass domain-tuned systems - all while preserving generalizability and avoiding the need for costly fine-tuning or labeled data. Our method aggregates outputs from multiple LLM variants, including models from Anthropic and Google, to synthesize more accurate and robust answers. Moreover, our investigation highlights a relationship between context length and performance: while expanded contexts are meant to provide valuable evidence, they simultaneously risk information dilution and model disorientation. These findings emphasize IR as a critical foundation in Retrieval-Augmented Generation (RAG) approaches for biomedical QA systems. Precise, focused retrieval remains essential for ensuring LLMs operate within relevant information boundaries when generating answers from retrieved documents. Our results establish that ensemble-based zero-shot approaches, when paired with effective RAG pipelines, constitute a practical and scalable alternative to domain-tuned systems for biomedical question answering.

[Arxiv](https://arxiv.org/abs/2509.08596)