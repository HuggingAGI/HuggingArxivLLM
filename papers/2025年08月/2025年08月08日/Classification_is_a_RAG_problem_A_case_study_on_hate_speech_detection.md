# 分类任务中的 RAG 问题：仇恨言论检测案例研究

发布时间：2025年08月08日

`RAG` `内容审核` `社交媒体`

> Classification is a RAG problem: A case study on hate speech detection

# 摘要

> 内容审核需要分类系统快速适应政策变化，同时避免昂贵的重新训练。我们提出了一种基于检索增强生成（RAG）的分类方法，将传统分类任务从依赖预训练参数判断类别，转变为结合推理过程中检索到的上下文知识进行内容评估。在仇恨言论检测中，这将任务从“这是仇恨言论吗？”转变为“这违反政策吗？”我们的上下文策略引擎（CPE）——一种具备主动性的RAG系统——展示了这一方法，并提供了三个关键优势：（1）与领先商业系统相当的分类准确率，（2）通过检索到的政策段落实现可解释性，（3）无需重新训练即可实现动态政策更新。实验表明，该系统能够通过调整对特定身份群体的保护级别，实现细粒度的政策控制，同时保持高性能。这些发现证明，RAG能够将分类过程转变为更灵活、透明且适应性强的内容审核工具，同时为更广泛的分类问题提供解决方案。

> Robust content moderation requires classification systems that can quickly adapt to evolving policies without costly retraining. We present classification using Retrieval-Augmented Generation (RAG), which shifts traditional classification tasks from determining the correct category in accordance with pre-trained parameters to evaluating content in relation to contextual knowledge retrieved at inference. In hate speech detection, this transforms the task from "is this hate speech?" to "does this violate the hate speech policy?"
  Our Contextual Policy Engine (CPE) - an agentic RAG system - demonstrates this approach and offers three key advantages: (1) robust classification accuracy comparable to leading commercial systems, (2) inherent explainability via retrieved policy segments, and (3) dynamic policy updates without model retraining. Through three experiments, we demonstrate strong baseline performance and show that the system can apply fine-grained policy control by correctly adjusting protection for specific identity groups without requiring retraining or compromising overall performance. These findings establish that RAG can transform classification into a more flexible, transparent, and adaptable process for content moderation and wider classification problems.

[Arxiv](https://arxiv.org/abs/2508.06204)