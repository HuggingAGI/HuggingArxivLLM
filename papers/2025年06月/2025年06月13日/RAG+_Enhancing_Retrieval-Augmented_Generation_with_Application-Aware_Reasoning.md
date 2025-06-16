# RAG+：增强检索增强生成，融入应用感知推理

发布时间：2025年06月13日

`RAG`

> RAG+: Enhancing Retrieval-Augmented Generation with Application-Aware Reasoning

# 摘要

> 检索增强生成（RAG）通过整合外部知识，已成为提升大型语言模型（LLMs）在知识密集型任务中性能的关键。然而，现有RAG方法往往忽视了知识应用这一认知环节，导致检索到的事实与具体任务推理之间存在断层。针对这一问题，我们提出RAG+，这是一个有原则且模块化的扩展方案，将具有应用意识的推理明确融入RAG流程。RAG+构建了一个包含知识和对齐应用示例的双语料库，这些语料可通过手动或自动方式生成，并在推理过程中联合检索。这一设计不仅让LLMs能够获取相关信息，更能在结构化、目标导向的推理过程中有效应用这些信息。跨数学、法律和医疗领域、多模型的实验结果表明，RAG+较标准RAG变体表现出显著优势，平均提升3-5%，在复杂场景下峰值提升高达7.5%。通过将检索与可操作的应用相结合，RAG+构建了更符合认知规律的知识整合框架，标志着LLMs向更可解释、更强大的方向迈进了一步。

> The integration of external knowledge through Retrieval-Augmented Generation (RAG) has become foundational in enhancing large language models (LLMs) for knowledge-intensive tasks. However, existing RAG paradigms often overlook the cognitive step of applying knowledge, leaving a gap between retrieved facts and task-specific reasoning. In this work, we introduce RAG+, a principled and modular extension that explicitly incorporates application-aware reasoning into the RAG pipeline. RAG+ constructs a dual corpus consisting of knowledge and aligned application examples, created either manually or automatically, and retrieves both jointly during inference. This design enables LLMs not only to access relevant information but also to apply it within structured, goal-oriented reasoning processes. Experiments across mathematical, legal, and medical domains, conducted on multiple models, demonstrate that RAG+ consistently outperforms standard RAG variants, achieving average improvements of 3-5%, and peak gains up to 7.5% in complex scenarios. By bridging retrieval with actionable application, RAG+ advances a more cognitively grounded framework for knowledge integration, representing a step toward more interpretable and capable LLMs.

[Arxiv](https://arxiv.org/abs/2506.11555)