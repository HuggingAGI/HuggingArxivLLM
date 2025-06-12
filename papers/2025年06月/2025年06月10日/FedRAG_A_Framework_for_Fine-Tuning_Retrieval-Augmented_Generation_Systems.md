# FedRAG：一个优化检索增强生成系统的框架

发布时间：2025年06月10日

`RAG` `联邦学习`

> FedRAG: A Framework for Fine-Tuning Retrieval-Augmented Generation Systems

# 摘要

> 检索增强生成（RAG）系统已被证明能有效弥补单纯依赖大型语言模型参数化记忆的诸多不足。近期研究表明，通过微调RAG系统的检索器和生成器模型，可以进一步提升其性能。本文中，我们提出了FedRAG框架，用于在集中式与联邦架构间进行RAG系统的微调。FedRAG支持当前最先进的微调方法，提供简单直观的接口，并实现从集中式到联邦化训练任务的无缝转换。此外，FedRAG深度整合了现代RAG生态系统，填补了现有工具的重要空白。

> Retrieval-augmented generation (RAG) systems have been shown to be effective in addressing many of the drawbacks of relying solely on the parametric memory of large language models. Recent work has demonstrated that RAG systems can be improved via fine-tuning of their retriever and generator models. In this work, we introduce FedRAG, a framework for fine-tuning RAG systems across centralized and federated architectures. FedRAG supports state-of-the-art fine-tuning methods, offering a simple and intuitive interface and a seamless conversion from centralized to federated training tasks. FedRAG is also deeply integrated with the modern RAG ecosystem, filling a critical gap in available tools.

[Arxiv](https://arxiv.org/abs/2506.09200)