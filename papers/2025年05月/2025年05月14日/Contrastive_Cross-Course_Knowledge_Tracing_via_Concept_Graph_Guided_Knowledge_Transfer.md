# 基于概念图的跨课程知识追踪对比

发布时间：2025年05月14日

`LLM应用` `知识图谱`

> Contrastive Cross-Course Knowledge Tracing via Concept Graph Guided Knowledge Transfer

# 摘要

> 知识追踪 (KT)旨在通过分析学习者的历史互动数据预测其未来表现。然而，现有方法主要局限于单一课程的数据，难以全面捕捉学习者知识状态。本文提出了一种基于对比学习的跨课程知识追踪方法——TransKT，通过概念图引导的知识转移，建模跨课程学习行为关系，从而提升知识状态估计。具体来说，TransKT利用零样本大型语言模型 (LLM) 提示，构建跨课程概念图，建立不同课程间相关概念的隐含链接，为知识转移提供基础，整合并增强学习者跨课程互动的语义特征。此外，TransKT还引入了LLM到LM的管道，将总结后的语义特征融入图卷积网络 (GCNs)，显著提升了知识转移的性能。通过对比学习，TransKT使单一课程与跨课程的知识状态保持一致，从而更精准地刻画学习者整体知识状态。

> Knowledge tracing (KT) aims to predict learners' future performance based on historical learning interactions. However, existing KT models predominantly focus on data from a single course, limiting their ability to capture a comprehensive understanding of learners' knowledge states. In this paper, we propose TransKT, a contrastive cross-course knowledge tracing method that leverages concept graph guided knowledge transfer to model the relationships between learning behaviors across different courses, thereby enhancing knowledge state estimation. Specifically, TransKT constructs a cross-course concept graph by leveraging zero-shot Large Language Model (LLM) prompts to establish implicit links between related concepts across different courses. This graph serves as the foundation for knowledge transfer, enabling the model to integrate and enhance the semantic features of learners' interactions across courses. Furthermore, TransKT includes an LLM-to-LM pipeline for incorporating summarized semantic features, which significantly improves the performance of Graph Convolutional Networks (GCNs) used for knowledge transfer. Additionally, TransKT employs a contrastive objective that aligns single-course and cross-course knowledge states, thereby refining the model's ability to provide a more robust and accurate representation of learners' overall knowledge states.

[Arxiv](https://arxiv.org/abs/2505.13489)