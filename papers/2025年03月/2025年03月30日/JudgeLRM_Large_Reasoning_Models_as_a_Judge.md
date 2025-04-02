# # JudgeLRM：让大型推理模型担任裁判

发布时间：2025年03月30日

`LLM应用

摘要：论文探讨了大型语言模型在评估任务中的应用，特别是通过强化学习提升其推理能力，属于LLM的应用研究。` `人工智能` `评估系统`

> JudgeLRM: Large Reasoning Models as a Judge

# 摘要

> 大型语言模型（LLMs）作为评估者的兴起为替代人工标注提供了一种可扩展的解决方案，但现有的监督微调（SFT）方法在需要复杂推理的领域中往往表现不足。本研究探讨了LLM评估器是否真正受益于增强的推理能力。通过对各类评估任务中推理需求的详细分析，我们发现SFT性能提升与需要推理的样本比例之间存在负相关关系，这凸显了SFT在这些场景中的局限性。为了解决这一问题，我们引入了JudgeLRM——一个专注于判断任务的LLM家族，通过强化学习（RL）采用基于裁判视角的、结果导向的奖励机制进行训练。JudgeLRM模型在各项评估任务中始终超越了经过SFT微调的模型以及现有的先进推理模型。值得注意的是，JudgeLRM-3B在与GPT-4的对比中表现更优，而JudgeLRM-7B在F1分数上比DeepSeek-R1高出2.79%，尤其在需要深度推理的裁判任务中表现出色。

> The rise of Large Language Models (LLMs) as evaluators offers a scalable alternative to human annotation, yet existing Supervised Fine-Tuning (SFT) for judges approaches often fall short in domains requiring complex reasoning. In this work, we investigate whether LLM judges truly benefit from enhanced reasoning capabilities. Through a detailed analysis of reasoning requirements across evaluation tasks, we reveal a negative correlation between SFT performance gains and the proportion of reasoning-demanding samples - highlighting the limitations of SFT in such scenarios. To address this, we introduce JudgeLRM, a family of judgment-oriented LLMs trained using reinforcement learning (RL) with judge-wise, outcome-driven rewards. JudgeLRM models consistently outperform both SFT-tuned and state-of-the-art reasoning models. Notably, JudgeLRM-3B surpasses GPT-4, and JudgeLRM-7B outperforms DeepSeek-R1 by 2.79% in F1 score, particularly excelling in judge tasks requiring deep reasoning.

[Arxiv](https://arxiv.org/abs/2504.00050)