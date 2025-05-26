# CReSt: 一个针对结构化文档复杂推理的检索增强生成全面评测基准

发布时间：2025年05月23日

`RAG` `检索增强生成` `复杂推理`

> CReSt: A Comprehensive Benchmark for Retrieval-Augmented Generation with Complex Reasoning over Structured Documents

# 摘要

> 大型语言模型（LLMs）近年来取得了长足进步，但在实际的检索增强生成（RAG）场景中，对其能力的评估仍具挑战性。在实际应用中，LLMs需要具备复杂推理、恰当拒绝回答、精准引用以及文档布局理解能力。这些能力对于高级任务处理、不确定性感知、保持可靠性以及结构理解至关重要。虽然一些先前研究分别探讨了这些方面，但目前尚缺乏一个统一框架，能够在实际RAG场景中综合评估这些能力。为解决这一问题，我们推出CReSt（一个针对复杂结构化文档推理的全面检索增强生成基准测试），旨在全面评估这些关键维度。CReSt包含2,245个人工标注的英文和韩文示例，捕捉需要复杂推理的实际RAG场景。它还引入了一种定制评估方法，以全面评估模型在这些关键领域的性能。我们的评估表明，即使是先进的LLMs在这些维度上也难以保持一致的性能，突显了需要改进的关键领域。我们公开发布CReSt，以支持进一步研究并推动更强大的RAG系统开发。数据集和代码可在以下链接获取：https://github.com/UpstageAI/CReSt.

> Large Language Models (LLMs) have made substantial progress in recent years, yet evaluating their capabilities in practical Retrieval-Augmented Generation (RAG) scenarios remains challenging. In practical applications, LLMs must demonstrate complex reasoning, refuse to answer appropriately, provide precise citations, and effectively understand document layout. These capabilities are crucial for advanced task handling, uncertainty awareness, maintaining reliability, and structural understanding. While some of the prior works address these aspects individually, there is a need for a unified framework that evaluates them collectively in practical RAG scenarios. To address this, we present CReSt (A Comprehensive Benchmark for Retrieval-Augmented Generation with Complex Reasoning over Structured Documents), a benchmark designed to assess these key dimensions holistically. CReSt comprises 2,245 human-annotated examples in English and Korean, designed to capture practical RAG scenarios that require complex reasoning over structured documents. It also introduces a tailored evaluation methodology to comprehensively assess model performance in these critical areas. Our evaluation shows that even advanced LLMs struggle to perform consistently across these dimensions, underscoring key areas for improvement. We release CReSt to support further research and the development of more robust RAG systems. The dataset and code are available at: https://github.com/UpstageAI/CReSt.

[Arxiv](https://arxiv.org/abs/2505.17503)