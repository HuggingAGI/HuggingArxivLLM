# 语言模型能否自我评估？研究检索增强生成在BioASQ 2025中的自我反馈机制

发布时间：2025年08月07日

`LLM应用` `生物医学` `信息检索`

> Can Language Models Critique Themselves? Investigating Self-Feedback for Retrieval Augmented Generation at BioASQ 2025

# 摘要

> 智能检索增强生成（RAG）和“深度研究”系统旨在实现大型语言模型（LLMs）迭代优化输出的自主搜索过程。然而，将这些系统应用于特定领域的专业搜索，如生物医学研究，则面临挑战，因为自动化系统可能会减少用户参与并偏离专家信息需求。专业搜索任务通常需要用户具备高水平的专业知识和透明度。BioASQ CLEF 2025挑战赛，通过专家设计的问题，可以作为一个研究这些问题的平台。

我们探索了当前推理和非推理大型语言模型（如Gemini-Flash 2.0、o3-mini、o4-mini和DeepSeek-R1）的表现。我们方法的一个关键方面是自我反馈机制，其中LLMs生成、评估并优化其输出，用于查询扩展和多种答案类型（是/否、事实性、列表、理想型）。我们研究了这种迭代自我纠正是否能提升性能，以及推理模型是否更擅长生成有用的反馈。初步结果表明，自我反馈策略在不同模型和任务中的表现差异显著。

这项工作为理解LLM自我纠正提供了见解，并为未来研究中比较LLM生成反馈与直接人工专家输入在这些搜索系统中的有效性提供了参考。

> Agentic Retrieval Augmented Generation (RAG) and 'deep research' systems aim to enable autonomous search processes where Large Language Models (LLMs) iteratively refine outputs. However, applying these systems to domain-specific professional search, such as biomedical research, presents challenges, as automated systems may reduce user involvement and misalign with expert information needs. Professional search tasks often demand high levels of user expertise and transparency. The BioASQ CLEF 2025 challenge, using expert-formulated questions, can serve as a platform to study these issues. We explored the performance of current reasoning and nonreasoning LLMs like Gemini-Flash 2.0, o3-mini, o4-mini and DeepSeek-R1. A key aspect of our methodology was a self-feedback mechanism where LLMs generated, evaluated, and then refined their outputs for query expansion and for multiple answer types (yes/no, factoid, list, ideal). We investigated whether this iterative self-correction improves performance and if reasoning models are more capable of generating useful feedback. Preliminary results indicate varied performance for the self-feedback strategy across models and tasks. This work offers insights into LLM self-correction and informs future work on comparing the effectiveness of LLM-generated feedback with direct human expert input in these search systems.

[Arxiv](https://arxiv.org/abs/2508.05366)