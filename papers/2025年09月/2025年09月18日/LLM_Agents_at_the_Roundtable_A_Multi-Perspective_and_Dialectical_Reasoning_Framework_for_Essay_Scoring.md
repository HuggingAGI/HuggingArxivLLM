# # 圆桌LLM智能体：面向作文评分的多视角辩证推理框架

发布时间：2025年09月18日

`Agent` `教育科技`

> LLM Agents at the Roundtable: A Multi-Perspective and Dialectical Reasoning Framework for Essay Scoring

# 摘要

> 大型语言模型（LLMs）的兴起为自动作文评分（AES）带来了全新范式——AES作为自然语言处理在教育领域的一项长期实用任务，其发展迎来新突破。但要实现人类水平的多维度理解与判断，仍是亟待攻克的难题。为此，本研究提出圆桌作文评分（RES）框架：这一多智能体评估体系，旨在零样本场景下实现精准且高度贴合人类判断的评分。RES依托LLMs构建评估智能体，每个智能体均针对特定提示与主题背景定制，能独立生成基于特质的评分标准并展开多视角评析。随后，通过模拟圆桌研讨机制，RES借助辩证推理整合各方评估，最终生成更贴近人类判断的整体评分。凭借不同视角智能体的协作共识机制，RES性能超越了现有零样本AES方法。在ASAP数据集上，基于ChatGPT和Claude的实验显示：相比直接提示（Vanilla）方法，RES的平均加权Kappa系数（QWK）提升幅度高达34.86%。

> The emergence of large language models (LLMs) has brought a new paradigm to automated essay scoring (AES), a long-standing and practical application of natural language processing in education. However, achieving human-level multi-perspective understanding and judgment remains a challenge. In this work, we propose Roundtable Essay Scoring (RES), a multi-agent evaluation framework designed to perform precise and human-aligned scoring under a zero-shot setting. RES constructs evaluator agents based on LLMs, each tailored to a specific prompt and topic context. Each agent independently generates a trait-based rubric and conducts a multi-perspective evaluation. Then, by simulating a roundtable-style discussion, RES consolidates individual evaluations through a dialectical reasoning process to produce a final holistic score that more closely aligns with human evaluation. By enabling collaboration and consensus among agents with diverse evaluation perspectives, RES outperforms prior zero-shot AES approaches. Experiments on the ASAP dataset using ChatGPT and Claude show that RES achieves up to a 34.86% improvement in average QWK over straightforward prompting (Vanilla) methods.

[Arxiv](https://arxiv.org/abs/2509.14834)