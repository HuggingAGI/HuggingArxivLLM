# ESC-Judge：助力评估情感支持对话机器人性能的框架

发布时间：2025年05月18日

`LLM应用` `心理健康` `人工智能`

> ESC-Judge: A Framework for Comparing Emotional Support Conversational Agents

# 摘要

> 大型语言模型（LLMs）正越来越多地为心理健康聊天机器人提供动力，然而，目前仍缺乏一种可扩展且有理论依据的方法来决定哪种模型最适合部署。我们提出了ESC-Judge，这是首个端到端的评估框架，它基于Clara Hill的探索-领悟-行动咨询模型，为情感支持LLMs的直接对比提供了一个结构化且可解释的视角，并在大规模情况下完全自动化了评估流程。ESC-Judge框架分为三个阶段：首先，它通过采样压力源、个性和生活经历等经验上显著的属性，合成现实的求助者角色；其次，它让两个候选支持代理分别与同一角色进行会话，以孤立模型特定的策略；最后，它要求一个专门的裁判LLM根据涵盖探索、领悟和行动范围的评分标准，表达对各项技能的成对偏好。在我们的研究中，ESC-Judge在85%的探索决策、83%的领悟决策和86%的行动决策上与博士级别的标注员一致，证明了它以极低的成本实现了与人类相当的可靠性。所有代码、提示、合成角色、对话记录和判断脚本均已发布，以推动情感支持AI的透明化进展。

> Large language models (LLMs) increasingly power mental-health chatbots, yet the field still lacks a scalable, theory-grounded way to decide which model is most effective to deploy. We present ESC-Judge, the first end-to-end evaluation framework that (i) grounds head-to-head comparisons of emotional-support LLMs in Clara Hill's established Exploration-Insight-Action counseling model, providing a structured and interpretable view of performance, and (ii) fully automates the evaluation pipeline at scale. ESC-Judge operates in three stages: first, it synthesizes realistic help-seeker roles by sampling empirically salient attributes such as stressors, personality, and life history; second, it has two candidate support agents conduct separate sessions with the same role, isolating model-specific strategies; and third, it asks a specialized judge LLM to express pairwise preferences across rubric-anchored skills that span the Exploration, Insight, and Action spectrum. In our study, ESC-Judge matched PhD-level annotators on 85 percent of Exploration, 83 percent of Insight, and 86 percent of Action decisions, demonstrating human-level reliability at a fraction of the cost. All code, prompts, synthetic roles, transcripts, and judgment scripts are released to promote transparent progress in emotionally supportive AI.

[Arxiv](https://arxiv.org/abs/2505.12531)