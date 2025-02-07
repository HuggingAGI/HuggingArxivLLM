# 大型语言模型在闭源仿真软件中的检索增强生成实验

发布时间：2025年02月06日

`RAG

理由：这篇论文主要探讨了检索增强生成（RAG）方法在闭源仿真软件中的应用，展示了RAG系统在创建仿真模型方面的潜力。虽然论文也涉及大型语言模型（LLMs）的应用，但其核心关注点是RAG方法在特定领域的应用和效果，因此更适合归类为RAG。` `知识产权`

> Experiments with Large Language Models on Retrieval-Augmented Generation for Closed-Source Simulation Software

# 摘要

> 大型语言模型（LLMs）在文本生成方面日益强大，甚至能根据自然语言提示编写代码。它们还被用于从自然语言生成多体系统的仿真模型。研究表明，LLMs不仅能复制现有代码，某些LLMs还在开源的多体仿真代码上进行了训练。然而，对于闭源仿真软件，由于它们的理念和概念可能与公开的不同，这样的结果难以预期。LLMs在知识密集型任务（如模型创建）中可能会出现幻觉，导致错误响应，尤其是在处理未知的闭源仿真软件时。同样，为保护知识产权或数据隐私而保密的内部知识也存在类似问题。检索增强生成（RAG）方法可能为这些任务提供解决方案。本文探讨了RAG在闭源仿真软件中的应用，并展示了初步实验。在简要介绍LLMs、RAG方法及闭源仿真软件的仿真方法后，通过多个示例测试了LLMs对仿真软件的知识及其使用RAG系统创建仿真模型的能力。这些示例展示了RAG系统在闭源仿真软件中的应用潜力，但也揭示了信息差距，并提出了进一步研究的开放性问题。

> Large Language Models (LLMs) are increasingly helpful in text generation, even writing code in programming languages based on user prompts written in natural language. They are even applied to generate simulation models for multibody systems from natural language. Research results suggest that LLMs surpass the mere replication of existing code examples, where some LLMs have been trained on an open-source multibody simulation code. However, for closed-source simulation software, such results are not to be expected as their ideas and concepts might differ from other publicly available ones. LLMs can hallucinate for knowledge-intensive tasks, such as model creation, which can lead to wrong responses. This is especially the case for the LLM unknown closed-source simulation software. The same applies to other internal knowledge kept private to protect intellectual property or data privacy. The Retrieval-Augmented Generation (RAG) approach might yield a solution for these knowledge-intensive tasks. This paper explores the application of RAG to closed-source simulation software and presents first experiments. After a brief introduction to LLMs, the RAG approach, and the simulation method applied by the close-source simulation software, several examples are provided to test LLMs' knowledge of the simulation software and the creation of simulation models using two RAG systems. The examples show promising results indicating the benefits of applying RAG systems to closed-source simulation software, helping to access their knowledge. Nevertheless, they also reveal gaps in the applied information and open questions for further research.

[Arxiv](https://arxiv.org/abs/2502.03916)