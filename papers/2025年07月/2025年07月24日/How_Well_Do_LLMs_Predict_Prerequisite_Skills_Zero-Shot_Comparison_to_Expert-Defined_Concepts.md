# LLMs预测先决技能的能力如何？零样本与专家定义概念的对比分析。

发布时间：2025年07月24日

`LLM应用` `人工智能`

> How Well Do LLMs Predict Prerequisite Skills? Zero-Shot Comparison to Expert-Defined Concepts

# 摘要

> 先决技能是掌握高级概念的基础能力，对于有效学习、评估和技能差距分析至关重要。传统上，这些关系由领域专家整理，但维护成本高且难以扩展。本文探讨大型语言模型（LLMs）是否能在零-shot设置中，仅使用自然语言描述而无需特定任务微调来预测先决技能。我们引入ESCO-PrereqSkill基准数据集，该数据集基于ESCO taxonomy构建，包含3,196项技能及其专家定义的先决关系。通过标准化提示策略，我们评估了13个最先进的LLMs，包括GPT-4、Claude 3、Gemini、LLaMA 4、Qwen2和DeepSeek，在语义相似度、BERTScore和推理延迟方面的表现。结果显示，LLaMA4-Maverick、Claude-3-7-Sonnet和Qwen2-72B等模型生成的预测与专家真实数据高度一致，展现出强大的语义推理能力，无需监督学习。这些发现凸显了LLMs在支持可扩展的先决技能建模方面的潜力，可用于个性化学习、智能辅导和基于技能的推荐系统等应用。

> Prerequisite skills - foundational competencies required before mastering more advanced concepts - are important for supporting effective learning, assessment, and skill-gap analysis. Traditionally curated by domain experts, these relationships are costly to maintain and difficult to scale. This paper investigates whether large language models (LLMs) can predict prerequisite skills in a zero-shot setting, using only natural language descriptions and without task-specific fine-tuning. We introduce ESCO-PrereqSkill, a benchmark dataset constructed from the ESCO taxonomy, comprising 3,196 skills and their expert-defined prerequisite links. Using a standardized prompting strategy, we evaluate 13 state-of-the-art LLMs, including GPT-4, Claude 3, Gemini, LLaMA 4, Qwen2, and DeepSeek, across semantic similarity, BERTScore, and inference latency. Our results show that models such as LLaMA4-Maverick, Claude-3-7-Sonnet, and Qwen2-72B generate predictions that closely align with expert ground truth, demonstrating strong semantic reasoning without supervision. These findings highlight the potential of LLMs to support scalable prerequisite skill modeling for applications in personalized learning, intelligent tutoring, and skill-based recommender systems.

[Arxiv](https://arxiv.org/abs/2507.18479)