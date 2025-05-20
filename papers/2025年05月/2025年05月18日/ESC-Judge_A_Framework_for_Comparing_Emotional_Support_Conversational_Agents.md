# ESC-Judge：用于评估情感支持对话机器人性能的框架

发布时间：2025年05月18日

`LLM应用` `心理健康` `AI评估`

> ESC-Judge: A Framework for Comparing Emotional Support Conversational Agents

# 摘要

> 大型语言模型（LLMs）正越来越多地赋能心理健康聊天机器人，但目前仍缺乏一种可扩展且基于理论的方法来选择最有效的模型。为此，我们提出了ESC-Judge——首个端到端评估框架，它(i)基于Clara Hill的探索-洞察-行动咨询模型，对情感支持型LLMs进行结构化、可解释的一对一比较；(ii)实现了大规模自动化评估流程。ESC-Judge分为三步：首先，通过采样压力源、人格和生活经历等关键属性，生成现实的求助者角色；其次，让两个候选支持代理分别与同一角色进行会话，以隔离模型策略；最后，借助专门的法官LLM，根据探索、洞察和行动三大维度的评分标准，评估各项技能。实验表明，ESC-Judge在探索、洞察和行动决策上的准确率分别达到85%、83%和86%，以极低的成本实现了与人类专家相当的可靠性。所有相关代码、提示、角色设定、对话记录和判断脚本均已公开，助力情感支持型AI的透明化发展。

> Large language models (LLMs) increasingly power mental-health chatbots, yet the field still lacks a scalable, theory-grounded way to decide which model is most effective to deploy. We present ESC-Judge, the first end-to-end evaluation framework that (i) grounds head-to-head comparisons of emotional-support LLMs in Clara Hill's established Exploration-Insight-Action counseling model, providing a structured and interpretable view of performance, and (ii) fully automates the evaluation pipeline at scale. ESC-Judge operates in three stages: first, it synthesizes realistic help-seeker roles by sampling empirically salient attributes such as stressors, personality, and life history; second, it has two candidate support agents conduct separate sessions with the same role, isolating model-specific strategies; and third, it asks a specialized judge LLM to express pairwise preferences across rubric-anchored skills that span the Exploration, Insight, and Action spectrum. In our study, ESC-Judge matched PhD-level annotators on 85 percent of Exploration, 83 percent of Insight, and 86 percent of Action decisions, demonstrating human-level reliability at a fraction of the cost. All code, prompts, synthetic roles, transcripts, and judgment scripts are released to promote transparent progress in emotionally supportive AI.

[Arxiv](https://arxiv.org/abs/2505.12531)