# # BioMol-MQA: 用于大语言模型推理生物分子相互作用的多模态问答数据集

发布时间：2025年06月06日

`RAG` `问答系统`

> BioMol-MQA: A Multi-Modal Question Answering Dataset For LLM Reasoning Over Bio-Molecular Interactions

# 摘要

> 检索增强生成（RAG）在提升大型语言模型（LLMs）方面表现突出。然而，现有基于RAG的LLMs大多专注于单一模态的信息检索，以文本为主。然而，在医疗等现实场景中，相关信息可能以知识图谱、文本（如临床笔记）和复杂分子结构等多种模态呈现。因此，能够检索多模态领域特定信息，并综合多样化知识生成精准回答至关重要。为填补这一空白，我们推出了BioMol-MQA，一个多药问题问答数据集，包含：（i）一个融合文本和分子结构的多模态知识图谱用于信息检索；（ii）一组挑战性问题，旨在测试LLMs在多模态知识图谱中的检索与推理能力。基准测试显示，现有LLMs在回答这些问题时表现不佳，仅在提供必要背景数据时才有所改善，凸显了强大RAG框架的必要性。

> Retrieval augmented generation (RAG) has shown great power in improving Large Language Models (LLMs). However, most existing RAG-based LLMs are dedicated to retrieving single modality information, mainly text; while for many real-world problems, such as healthcare, information relevant to queries can manifest in various modalities such as knowledge graph, text (clinical notes), and complex molecular structure. Thus, being able to retrieve relevant multi-modality domain-specific information, and reason and synthesize diverse knowledge to generate an accurate response is important. To address the gap, we present BioMol-MQA, a new question-answering (QA) dataset on polypharmacy, which is composed of two parts (i) a multimodal knowledge graph (KG) with text and molecular structure for information retrieval; and (ii) challenging questions that designed to test LLM capabilities in retrieving and reasoning over multimodal KG to answer questions. Our benchmarks indicate that existing LLMs struggle to answer these questions and do well only when given the necessary background data, signaling the necessity for strong RAG frameworks.

[Arxiv](https://arxiv.org/abs/2506.05766)