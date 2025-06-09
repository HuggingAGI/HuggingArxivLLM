# 超越 RAG：临床笔记的强化推理增强生成技术

发布时间：2025年06月03日

`LLM应用`

> Beyond RAG: Reinforced Reasoning Augmented Generation for Clinical Notes

# 摘要

> 临床笔记生成的目标是自动创建患者状况和诊断过程的自由文本摘要，其中出院指示是一个典型的长文本示例。尽管基于大型语言模型（LLM）并在通用临床语料库上预训练的方法在临床文本生成方面显示出潜力，但它们在从有限的患者信息生成长文本笔记方面仍存在不足。本文中，我们提出了R2AG，这是首个基于入院前数据的长文本出院指示生成强化检索器。通过强化学习训练，R2AG从医疗知识图谱中检索推理路径，为LLM提供明确的语义指导。为弥补信息差距，我们提出了基于组的检索器优化（GRO），通过组相对奖励提升检索质量，鼓励LLM进行更深入的推理。在MIMIC-IV-Note数据集上的全面实验表明，R2AG在临床效果和自然语言生成指标上均优于基线模型。进一步分析显示，R2AG在稀疏输入场景下有效填补语义空白，检索到的推理路径帮助LLM通过关注关键证据并遵循连贯推理来避免临床误读。


> Clinical note generation aims to automatically produce free-text summaries of a patient's condition and diagnostic process, with discharge instructions being a representative long-form example. While recent large language model (LLM)-based methods pre-trained on general clinical corpora show promise in clinical text generation, they fall short in producing long-form notes from limited patient information. In this paper, we propose R2AG, the first reinforced retriever for long-form discharge instruction generation based on pre-admission data. R2AG is trained with reinforcement learning to retrieve reasoning paths from a medical knowledge graph, providing explicit semantic guidance to the LLM. To bridge the information gap, we propose Group-Based Retriever Optimization (GRO) which improves retrieval quality with group-relative rewards, encouraging reasoning leaps for deeper inference by the LLM. Comprehensive experiments on the MIMIC-IV-Note dataset show that R2AG outperforms baselines in both clinical efficacy and natural language generation metrics. Further analysis reveals that R2AG fills semantic gaps in sparse input scenarios, and retrieved reasoning paths help LLMs avoid clinical misinterpretation by focusing on key evidence and following coherent reasoning.

[Arxiv](https://arxiv.org/abs/2506.05386)