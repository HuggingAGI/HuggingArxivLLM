# 从结果到过程：通过ORM指导PRM学习实现推理时间对齐

发布时间：2025年06月14日

`LLM理论

摘要中的论文主要探讨了大型语言模型（LLMs）与人类偏好对齐的方法，特别是通过引入过程奖励模型（PRMs）来解决现有方法中的粒度不匹配问题。该研究提出了新的理论框架（SP-PRM），并进行了理论上的分析和实验验证，属于对LLM理论的深入研究。因此，分类为LLM理论。` `对话系统`

> From Outcomes to Processes: Guiding PRM Learning from ORM for Inference-Time Alignment

# 摘要

> 推理时的对齐方法在将大型语言模型（LLMs）与人类偏好对齐方面展现了显著优势。然而，现有方法主要依赖结果奖励模型（ORMs），这些模型与基于奖励的搜索方法（RGS）存在关键的粒度不匹配问题：ORMs专为完整响应设计，而RGS依赖过程奖励，导致评分不一致和对齐效果欠佳。为此，我们引入了过程奖励模型（PRMs），提出理想的PRM应满足评分一致性和偏好一致性两大目标。基于此，我们创新性地提出了SP-PRM框架，整合了评分一致性和偏好一致性模块，且无需人工标注。实验表明，SP-PRM显著提升了现有RGS方法的性能，在对话、总结和推理任务中使GPT-4评估分数提升了3.6%-10.3%。

> Inference-time alignment methods have gained significant attention for their efficiency and effectiveness in aligning large language models (LLMs) with human preferences. However, existing dominant approaches using reward-guided search (RGS) primarily rely on outcome reward models (ORMs), which suffer from a critical granularity mismatch: ORMs are designed to provide outcome rewards for complete responses, while RGS methods rely on process rewards to guide the policy, leading to inconsistent scoring and suboptimal alignment. To address this challenge, we introduce process reward models (PRMs) into RGS and argue that an ideal PRM should satisfy two objectives: Score Consistency, ensuring coherent evaluation across partial and complete responses, and Preference Consistency, aligning partial sequence assessments with human preferences. Based on these, we propose SP-PRM, a novel dual-consistency framework integrating score consistency-based and preference consistency-based partial evaluation modules without relying on human annotation. Extensive experiments on dialogue, summarization, and reasoning tasks demonstrate that SP-PRM substantially enhances existing RGS methods, achieving a 3.6%-10.3% improvement in GPT-4 evaluation scores across all tasks.

[Arxiv](https://arxiv.org/abs/2506.12446)