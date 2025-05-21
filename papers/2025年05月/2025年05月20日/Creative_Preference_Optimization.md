# 优化创意倾向

发布时间：2025年05月20日

`LLM应用` `创意产业`

> Creative Preference Optimization

# 摘要

> 大型语言模型（LLMs）在自然语言生成任务中表现卓越，但在生成真正具有创意的内容方面仍有局限。现有方法往往仅关注单一维度或特定任务，难以全面提升创造力。我们提出了一种名为创意偏好优化（CrPO）的新方法，通过模块化整合多维度创意信号，优化模型的偏好目标。借助覆盖20余万条人类生成回复及30多项心理评估数据的MuCE数据集，我们对多款模型进行了创意增强训练与评估。结果显示，我们的模型在保持高质量输出的同时，生成内容更具新颖性、多样性和惊喜感，并超越了包括GPT-4o在内的多种基线模型。进一步的NoveltyBench评估也验证了方法的通用性。这表明，在偏好框架下直接优化创造力是提升LLMs创意能力的可行且有效途径。

> While Large Language Models (LLMs) have demonstrated impressive performance across natural language generation tasks, their ability to generate truly creative content-characterized by novelty, diversity, surprise, and quality-remains limited. Existing methods for enhancing LLM creativity often focus narrowly on diversity or specific tasks, failing to address creativity's multifaceted nature in a generalizable way. In this work, we propose Creative Preference Optimization (CrPO), a novel alignment method that injects signals from multiple creativity dimensions into the preference optimization objective in a modular fashion. We train and evaluate creativity-augmented versions of several models using CrPO and MuCE, a new large-scale human preference dataset spanning over 200,000 human-generated responses and ratings from more than 30 psychological creativity assessments. Our models outperform strong baselines, including GPT-4o, on both automated and human evaluations, producing more novel, diverse, and surprising generations while maintaining high output quality. Additional evaluations on NoveltyBench further confirm the generalizability of our approach. Together, our results demonstrate that directly optimizing for creativity within preference frameworks is a promising direction for advancing the creative capabilities of LLMs without compromising output quality.

[Arxiv](https://arxiv.org/abs/2505.14442)