# 面向复杂领域增强检索增强生成的上下文自适应合成与压缩

发布时间：2025年08月26日

`RAG` `基础理论`

> Context-Adaptive Synthesis and Compression for Enhanced Retrieval-Augmented Generation in Complex Domains

# 摘要

> 大型语言模型（LLMs）虽在语言任务中表现卓越，却常受幻觉和知识陈旧问题困扰。检索增强生成（RAG）通过将LLMs与外部知识关联，有效缓解了这些问题。但在涉及多份、冗长或存在冲突文档的复杂领域，传统RAG常因信息过载和合成低效，产出不准确、不可信的答案。为此，我们提出CASC（上下文自适应合成与压缩）——一种能智能处理检索上下文的新型框架。CASC引入上下文分析与合成器（CAS）模块，由微调的小型LLM提供支持，可执行关键信息提取、跨文档一致性检查与冲突解决，以及面向问题的结构化合成。该过程将原始、零散的信息转化为高度浓缩、结构化且语义丰富的上下文，大幅降低了最终Reader LLM的标记量和认知负荷。我们在SciDocs-QA数据集上对CASC进行了评估——这是一个全新的挑战性多文档问答数据集，专为存在固有冗余和冲突的复杂科学领域设计。大量实验证实，CASC性能持续优于强基线模型。

> Large Language Models (LLMs) excel in language tasks but are prone to hallucinations and outdated knowledge. Retrieval-Augmented Generation (RAG) mitigates these by grounding LLMs in external knowledge. However, in complex domains involving multiple, lengthy, or conflicting documents, traditional RAG suffers from information overload and inefficient synthesis, leading to inaccurate and untrustworthy answers. To address this, we propose CASC (Context-Adaptive Synthesis and Compression), a novel framework that intelligently processes retrieved contexts. CASC introduces a Context Analyzer & Synthesizer (CAS) module, powered by a fine-tuned smaller LLM, which performs key information extraction, cross-document consistency checking and conflict resolution, and question-oriented structured synthesis. This process transforms raw, scattered information into a highly condensed, structured, and semantically rich context, significantly reducing the token count and cognitive load for the final Reader LLM. We evaluate CASC on SciDocs-QA, a new challenging multi-document question answering dataset designed for complex scientific domains with inherent redundancies and conflicts. Our extensive experiments demonstrate that CASC consistently outperforms strong baselines.

[Arxiv](https://arxiv.org/abs/2508.19357)