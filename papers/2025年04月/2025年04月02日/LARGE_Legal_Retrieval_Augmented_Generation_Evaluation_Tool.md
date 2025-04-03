# LARGE：法律检索增强生成评测工具

发布时间：2025年04月02日

`RAG` `人工智能`

> LARGE: Legal Retrieval Augmented Generation Evaluation Tool

# 摘要

> 近年来，构建检索增强生成（RAG）系统以提升大型语言模型（LLMs）的能力已成为普遍实践。特别是在法律领域，基于先例约束原则，先前的司法判决具有重要参考价值。然而，RAG系统的整体性能取决于五个关键组件：（1）检索语料库，（2）检索算法，（3）重排序器，（4）LLM主干，（5）评估指标。为此，我们推出了LRAGE——一个专注于法律领域的开源RAG系统整体评估工具。LRAGE配备GUI和CLI双界面，便于用户轻松开展实验，探究上述五个组件的调整如何影响系统整体准确性。我们通过多语言法律基准（包括韩语（KBL）、英语（LegalBench）和中文（LawBench））验证了LRAGE的效果，展示了各组件变化对整体准确性的影响。LRAGE的源代码已开源，访问地址为https://github.com/hoorangyee/LRAGE。

> Recently, building retrieval-augmented generation (RAG) systems to enhance the capability of large language models (LLMs) has become a common practice. Especially in the legal domain, previous judicial decisions play a significant role under the doctrine of stare decisis which emphasizes the importance of making decisions based on (retrieved) prior documents. However, the overall performance of RAG system depends on many components: (1) retrieval corpora, (2) retrieval algorithms, (3) rerankers, (4) LLM backbones, and (5) evaluation metrics. Here we propose LRAGE, an open-source tool for holistic evaluation of RAG systems focusing on the legal domain. LRAGE provides GUI and CLI interfaces to facilitate seamless experiments and investigate how changes in the aforementioned five components affect the overall accuracy. We validated LRAGE using multilingual legal benches including Korean (KBL), English (LegalBench), and Chinese (LawBench) by demonstrating how the overall accuracy changes when varying the five components mentioned above. The source code is available at https://github.com/hoorangyee/LRAGE.

[Arxiv](https://arxiv.org/abs/2504.01840)