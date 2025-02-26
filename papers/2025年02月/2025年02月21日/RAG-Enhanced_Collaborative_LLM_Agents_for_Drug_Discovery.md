# 基于 RAG 的协作式大语言模型代理在药物发现中的应用

发布时间：2025年02月21日

`RAG`

> RAG-Enhanced Collaborative LLM Agents for Drug Discovery

# 摘要

> 大型语言模型（LLMs）在加速药物发现方面展现出巨大潜力。然而，生物化学数据的特殊性质通常需要昂贵的领域特定微调，带来了两大关键挑战。首先，这阻碍了更灵活的通用型LLMs在前沿药物发现任务中的应用。更重要的是，它阻碍了通过实验和研究不断产生的大量科学数据的快速整合。为解决这些挑战，我们提出了CLADD——一个专为药物发现设计的基于检索增强生成（RAG）的智能系统。通过多个LLM代理的合作，CLADD能够从生物医学知识库中动态检索信息，对查询分子进行语境化处理，并整合相关证据以生成响应——所有这些都无需进行领域特定的微调。我们还解决了将RAG工作流程应用于生物化学数据的关键障碍，包括数据异质性、模糊性和多源整合。我们在多种药物发现任务中展示了该框架的灵活性和有效性，结果显示它优于通用型和领域特定的LLMs以及传统深度学习方法。

> Recent advances in large language models (LLMs) have shown great potential to accelerate drug discovery. However, the specialized nature of biochemical data often necessitates costly domain-specific fine-tuning, posing critical challenges. First, it hinders the application of more flexible general-purpose LLMs in cutting-edge drug discovery tasks. More importantly, it impedes the rapid integration of the vast amounts of scientific data continuously generated through experiments and research. To investigate these challenges, we propose CLADD, a retrieval-augmented generation (RAG)-empowered agentic system tailored to drug discovery tasks. Through the collaboration of multiple LLM agents, CLADD dynamically retrieves information from biomedical knowledge bases, contextualizes query molecules, and integrates relevant evidence to generate responses -- all without the need for domain-specific fine-tuning. Crucially, we tackle key obstacles in applying RAG workflows to biochemical data, including data heterogeneity, ambiguity, and multi-source integration. We demonstrate the flexibility and effectiveness of this framework across a variety of drug discovery tasks, showing that it outperforms general-purpose and domain-specific LLMs as well as traditional deep learning approaches.

[Arxiv](https://arxiv.org/abs/2502.17506)