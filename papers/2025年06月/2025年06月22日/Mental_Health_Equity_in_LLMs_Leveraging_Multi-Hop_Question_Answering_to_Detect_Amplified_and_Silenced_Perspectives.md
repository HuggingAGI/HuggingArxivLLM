# 大型语言模型中的心理健康公平：利用多跳问答技术检测被放大的和被忽视的观点

发布时间：2025年06月22日

`LLM应用

理由：该论文探讨了大型语言模型在心理健康领域的应用及其潜在的偏见问题，属于LLM的实际应用和伦理影响分析。` `心理健康` `偏见检测`

> Mental Health Equity in LLMs: Leveraging Multi-Hop Question Answering to Detect Amplified and Silenced Perspectives

# 摘要

> 大型语言模型（LLMs）在心理健康领域的应用可能加剧偏见，进而强化污名并伤害边缘群体。尽管已有研究发现了一些令人担忧的趋势，但针对交叉性偏见的系统性检测方法仍显不足。本研究提出了一种多跳问答（MHQA）框架，用于深入探索LLM在心理健康讨论中的偏见回应。我们基于可解释心理健康指令（IMHI）数据集，从症状表现、应对机制和治疗方式三个维度展开分析。通过在年龄、种族、性别和社会经济地位等多个维度进行系统性标注，我们揭示了交叉人口统计学中的偏见模式。我们对Claude 3.5 Sonnet、Jamba 1.6、Gemma 3 和 Llama 4四个大型语言模型进行了评估，发现了在情感倾向、人口统计学特征和心理健康状况方面的系统性差异。与传统方法相比，我们的MHQA方法在偏见检测方面表现更优，能够识别出偏见通过顺序推理被放大的关键点。我们还实现了两种去偏见技术：角色扮演模拟和显式偏见减少，通过使用BBQ数据集示例的少量样本提示，成功实现了66-94%的偏见减少。这些发现不仅揭示了LLMs在心理健康护理中再现偏见的关键领域，更为实现公平的人工智能发展提供了切实可行的见解。

> Large Language Models (LLMs) in mental healthcare risk propagating biases that reinforce stigma and harm marginalized groups. While previous research identified concerning trends, systematic methods for detecting intersectional biases remain limited. This work introduces a multi-hop question answering (MHQA) framework to explore LLM response biases in mental health discourse. We analyze content from the Interpretable Mental Health Instruction (IMHI) dataset across symptom presentation, coping mechanisms, and treatment approaches. Using systematic tagging across age, race, gender, and socioeconomic status, we investigate bias patterns at demographic intersections. We evaluate four LLMs: Claude 3.5 Sonnet, Jamba 1.6, Gemma 3, and Llama 4, revealing systematic disparities across sentiment, demographics, and mental health conditions. Our MHQA approach demonstrates superior detection compared to conventional methods, identifying amplification points where biases magnify through sequential reasoning. We implement two debiasing techniques: Roleplay Simulation and Explicit Bias Reduction, achieving 66-94% bias reductions through few-shot prompting with BBQ dataset examples. These findings highlight critical areas where LLMs reproduce mental healthcare biases, providing actionable insights for equitable AI development.

[Arxiv](https://arxiv.org/abs/2506.18116)