# # **HIRAG：层次化思考指令微调的检索增强生成**

发布时间：2025年07月08日

`RAG` `问答系统`

> HIRAG: Hierarchical-Thought Instruction-Tuning Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为解决大型语言模型在实时信息和领域特定问题处理方面挑战的基本范式。传统RAG系统主要依赖大型语言模型本身的上下文学习（ICL）能力。然而，关于RAG生成模型所需具体能力的深入研究仍然不足，导致文档质量不一致和检索系统不完善的问题。即使是那些微调RAG生成模型的有限研究，也往往	extit{缺乏对RAG任务的细致关注}或	extit{未能充分利用思维链过程}。为了解决这一问题，我们提出RAG模型应具备三种渐进式分层能力：（1）过滤：选择相关信息的能力；（2）组合：跨段落整合语义信息的能力；（3）RAG特定推理：利用内部知识进一步处理外部知识的能力。因此，我们引入了新的RAG指令微调方法——分层思维指令调优的检索增强生成（HIRAG），该方法采用"先思考后回答"策略。通过多层级的渐进式思维链，该方法提升了模型的开卷考试能力。实验表明，HIRAG训练策略显著提升了模型在RGB、PopQA、MuSiQue、HotpotQA和PubmedQA等数据集上的性能表现。

> Retrieval-augmented generation (RAG) has become a fundamental paradigm for addressing the challenges faced by large language models in handling real-time information and domain-specific problems. Traditional RAG systems primarily rely on the in-context learning (ICL) capabilities of the large language model itself. Still, in-depth research on the specific capabilities needed by the RAG generation model is lacking, leading to challenges with inconsistent document quality and retrieval system imperfections. Even the limited studies that fine-tune RAG generative models often \textit{lack a granular focus on RAG task} or \textit{a deeper utilization of chain-of-thought processes}. To address this, we propose that RAG models should possess three progressively hierarchical abilities (1) Filtering: the ability to select relevant information; (2) Combination: the ability to combine semantic information across paragraphs; and (3) RAG-specific reasoning: the ability to further process external knowledge using internal knowledge. Thus, we introduce our new RAG instruction fine-tuning method, Hierarchical-Thought Instruction-Tuning Retrieval-Augmented Generation (HIRAG) incorporates a "think before answering" strategy. This method enhances the model's open-book examination capability by utilizing multi-level progressive chain-of-thought. Experiments show that the HIRAG training strategy significantly improves the model's performance on datasets such as RGB, PopQA, MuSiQue, HotpotQA, and PubmedQA.

[Arxiv](https://arxiv.org/abs/2507.05714)