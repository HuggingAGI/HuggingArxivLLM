# 针对癌症患者问答系统的查询管道优化

发布时间：2024年12月19日

`RAG` `生物医学`

> Query pipeline optimization for cancer patient question answering systems

# 摘要

> 检索增强生成（RAG）借助查询管道来检索相关外部信息，并以检索到的知识为基础生成响应，从而减少了大型语言模型（LLMs）中的幻觉现象。然而，针对癌症患者问答（CPQA）系统的查询管道优化，需要结合领域特定因素分别对多个组件进行优化。我们为 CPQA 系统中的 RAG 查询管道提出了一种创新的三方面优化方法，利用了诸如 PubMed 和 PubMed Central 等公共生物医学数据库。我们的优化涵盖：（1）文档检索，通过对 NCBI 资源的对比分析引入混合语义实时文档检索（HSRDR）；（2）段落检索，确定密集检索器与重排器的最优组合；（3）语义表示，引入语义增强重叠分割（SEOS）以增强上下文理解。在为癌症相关问询专门开发的数据集上，我们优化后的 RAG 方法使 Claude-3-haiku 的答案准确率相比思维链提示提高了 5.24％，比原始的 RAG 配置提高了约 3％。本研究凸显了领域特定查询优化对于充分挖掘 RAG 潜力的重要性，为构建更精准可靠的 CPQA 系统提供了有力框架，推动了基于 RAG 的生物医学系统的发展。

> Retrieval-augmented generation (RAG) mitigates hallucination in Large Language Models (LLMs) by using query pipelines to retrieve relevant external information and grounding responses in retrieved knowledge. However, query pipeline optimization for cancer patient question-answering (CPQA) systems requires separately optimizing multiple components with domain-specific considerations. We propose a novel three-aspect optimization approach for the RAG query pipeline in CPQA systems, utilizing public biomedical databases like PubMed and PubMed Central. Our optimization includes: (1) document retrieval, utilizing a comparative analysis of NCBI resources and introducing Hybrid Semantic Real-time Document Retrieval (HSRDR); (2) passage retrieval, identifying optimal pairings of dense retrievers and rerankers; and (3) semantic representation, introducing Semantic Enhanced Overlap Segmentation (SEOS) for improved contextual understanding. On a custom-developed dataset tailored for cancer-related inquiries, our optimized RAG approach improved the answer accuracy of Claude-3-haiku by 5.24% over chain-of-thought prompting and about 3% over a naive RAG setup. This study highlights the importance of domain-specific query optimization in realizing the full potential of RAG and provides a robust framework for building more accurate and reliable CPQA systems, advancing the development of RAG-based biomedical systems.

[Arxiv](https://arxiv.org/abs/2412.14751)