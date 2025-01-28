# PISCO: 检索增强生成的简洁压缩方案

发布时间：2025年01月27日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）管道的可扩展性问题，并提出了一种新的文档压缩方法PISCO，以提高RAG在问答任务中的效率和准确性。因此，该论文应归类为RAG。` `问答系统`

> PISCO: Pretty Simple Compression for Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）管道通过检索相关文档来增强大型语言模型（LLMs），但高推理成本和有限的上下文大小使其面临可扩展性问题。文档压缩是一种实用解决方案，但现有软压缩方法存在准确性损失，且需要大量预训练。本文提出PISCO，一种新颖方法，在多种基于RAG的问答（QA）任务中实现16倍压缩率，且准确性损失仅为0-3%。与现有方法不同，PISCO无需预训练或注释数据，仅依赖基于文档问题的序列级知识蒸馏。PISCO能在单个A100 GPU上48小时内微调7-10B的LLM，提供高效且可扩展的解决方案。实验表明，PISCO在准确性上比现有压缩模型高出8%。

> Retrieval-Augmented Generation (RAG) pipelines enhance Large Language Models (LLMs) by retrieving relevant documents, but they face scalability issues due to high inference costs and limited context size. Document compression is a practical solution, but current soft compression methods suffer from accuracy losses and require extensive pretraining. In this paper, we introduce PISCO, a novel method that achieves a 16x compression rate with minimal accuracy loss (0-3%) across diverse RAG-based question-answering (QA) tasks. Unlike existing approaches, PISCO requires no pretraining or annotated data, relying solely on sequence-level knowledge distillation from document-based questions. With the ability to fine-tune a 7-10B LLM in 48 hours on a single A100 GPU, PISCO offers a highly efficient and scalable solution. We present comprehensive experiments showing that PISCO outperforms existing compression models by 8% in accuracy.

[Arxiv](https://arxiv.org/abs/2501.16075)