# 一种用于SIBT的迭代式LLM框架：采用基于RAG的自适应权重优化

发布时间：2025年09月10日

`LLM应用` `医疗健康`

> An Iterative LLM Framework for SIBT utilizing RAG-based Adaptive Weight Optimization

# 摘要

> 种子植入近距离放射治疗（SIBT）是一种有效的癌症治疗手段，但临床计划制定常需人工调整目标函数权重，不仅效率低下，结果也不尽理想。本研究提出了一种基于大型语言模型（LLMs）的SIBT计划自适应权重优化框架：将本地部署的DeepSeek-R1大型语言模型与自动计划算法集成，形成迭代循环。从固定权重出发，模型会评估当前计划质量，并为下一轮迭代推荐新权重；这一过程持续至满足收敛条件，随后模型通过全面评估选出最优计划。研究还借助检索增强生成（RAG）构建并查询临床知识库，以增强模型的领域专属推理能力。该方法在23例患者病例中验证显示：在临床靶区（CTV）的剂量均匀性和危及器官（OARs）的保护效果上，LLM辅助生成的计划与临床批准的固定权重计划相当，甚至更优。这项研究证实，LLMs在SIBT计划自动化中具有广阔的应用潜力。

> Seed implant brachytherapy (SIBT) is an effective cancer treatment modality; however, clinical planning often relies on manual adjustment of objective function weights, leading to inefficiencies and suboptimal results. This study proposes an adaptive weight optimization framework for SIBT planning, driven by large language models (LLMs). A locally deployed DeepSeek-R1 LLM is integrated with an automatic planning algorithm in an iterative loop. Starting with fixed weights, the LLM evaluates plan quality and recommends new weights in the next iteration. This process continues until convergence criteria are met, after which the LLM conducts a comprehensive evaluation to identify the optimal plan. A clinical knowledge base, constructed and queried via retrieval-augmented generation (RAG), enhances the model's domain-specific reasoning. The proposed method was validated on 23 patient cases, showing that the LLM-assisted approach produces plans that are comparable to or exceeding clinically approved and fixed-weight plans, in terms of dose homogeneity for the clinical target volume (CTV) and sparing of organs at risk (OARs). The study demonstrates the potential use of LLMs in SIBT planning automation.

[Arxiv](https://arxiv.org/abs/2509.08407)