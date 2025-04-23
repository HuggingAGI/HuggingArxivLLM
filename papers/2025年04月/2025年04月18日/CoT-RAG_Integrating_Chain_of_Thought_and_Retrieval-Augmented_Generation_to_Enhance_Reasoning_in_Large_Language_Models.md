# # CoT-RAG：融合思维链与增强检索生成，助力提升大型语言模型的推理能力

发布时间：2025年04月18日

`RAG` `知识图谱` `信息检索`

> CoT-RAG: Integrating Chain of Thought and Retrieval-Augmented Generation to Enhance Reasoning in Large Language Models

# 摘要

> 尽管链式思维（CoT）推理在提升大型语言模型（LLMs）处理复杂任务的能力方面表现出色，但其可靠性低和推理链干扰两大挑战仍待解决。为此，我们提出了CoT-RAG框架，该框架包含三项创新设计：(i) 知识图谱驱动的CoT生成，通过知识图谱优化LLMs的推理链生成，提升推理可信度；(ii) 可学习的知识案例感知RAG，将增强型检索生成（RAG）与知识图谱结合，帮助LLMs获取可学习信息；(iii) 假设程序提示执行，促使LLMs以更严谨的逻辑执行推理任务。我们在涵盖三种推理问题的九个公开数据集上进行了全面测试，结果显示，与现有最优方法相比，CoT-RAG的准确率提升了4.0%到23.0%。此外，在四个特定领域数据集上的测试进一步证明了CoT-RAG的高效性和实用性，展现了其强大的应用潜力和可扩展性。

> While chain-of-thought (CoT) reasoning improves the performance of large language models (LLMs) in complex tasks, it still has two main challenges: the low reliability of relying solely on LLMs to generate reasoning chains and the interference of natural language reasoning chains on the inference logic of LLMs. To address these issues, we propose CoT-RAG, a novel reasoning framework with three key designs: (i) Knowledge Graph-driven CoT Generation, featuring knowledge graphs to modulate reasoning chain generation of LLMs, thereby enhancing reasoning credibility; (ii) Learnable Knowledge Case-aware RAG, which incorporates retrieval-augmented generation (RAG) into knowledge graphs to retrieve relevant sub-cases and sub-descriptions, providing LLMs with learnable information; (iii) Pseudo-Program Prompting Execution, which encourages LLMs to execute reasoning tasks in pseudo-programs with greater logical rigor. We conduct a comprehensive evaluation on nine public datasets, covering three reasoning problems. Compared with the-state-of-the-art methods, CoT-RAG exhibits a significant accuracy improvement, ranging from 4.0% to 23.0%. Furthermore, testing on four domain-specific datasets, CoT-RAG shows remarkable accuracy and efficient execution, highlighting its strong practical applicability and scalability.

[Arxiv](https://arxiv.org/abs/2504.13534)