# RLBFF：二元灵活反馈——搭建人类反馈与可验证奖励的桥梁

发布时间：2025年09月25日

`强化学习` `基础理论`

> RLBFF: Binary Flexible Feedback to bridge between Human Feedback & Verifiable Rewards

# 摘要

> 基于人类反馈的强化学习（RLHF）与基于可验证奖励的强化学习（RLVR）是大型语言模型（LLM）后训练的主流强化学习范式，二者各有千秋。但RLHF依赖缺乏明确标准的人类判断，因此在可解释性和奖励黑客问题上表现不佳；而RLVR则因聚焦基于正确性的验证器，适用范围受限。为此，我们提出基于二元灵活反馈的强化学习（RLBFF），它融合了人类偏好的灵活性与规则验证的精确性，让奖励模型能够捕捉响应质量中除正确性之外的细微差异。RLBFF从自然语言反馈中提炼出可二元回答的原则（如信息准确性：是/否，代码可读性：是/否），并将这些原则用于奖励模型训练，将其转化为蕴含任务（即判断响应是否满足某一原则）。实验表明，这种方式训练的奖励模型在数据匹配条件下性能超过Bradley-Terry模型，并在RM-Bench（86.2%）和JudgeBench（81.4%，截至2025年9月24日位居榜首）上表现顶尖。此外，与Bradley-Terry模型不同，用户可在推理时指定关注的原则，从而定制奖励模型的评估重点。最后，我们提供了一套完全开源的方案（含数据），通过RLBFF和我们的奖励模型对齐Qwen3-32B，在MT-Bench、WildBench和Arena Hard v2等通用对齐基准上性能达到或超越o3-mini与DeepSeek R1，且推理成本仅为其5%以下。

> Reinforcement Learning with Human Feedback (RLHF) and Reinforcement Learning with Verifiable Rewards (RLVR) are the main RL paradigms used in LLM post-training, each offering distinct advantages. However, RLHF struggles with interpretability and reward hacking because it relies on human judgments that usually lack explicit criteria, whereas RLVR is limited in scope by its focus on correctness-based verifiers. We propose Reinforcement Learning with Binary Flexible Feedback (RLBFF), which combines the versatility of human-driven preferences with the precision of rule-based verification, enabling reward models to capture nuanced aspects of response quality beyond mere correctness. RLBFF extracts principles that can be answered in a binary fashion (e.g. accuracy of information: yes, or code readability: no) from natural language feedback. Such principles can then be used to ground Reward Model training as an entailment task (response satisfies or does not satisfy an arbitrary principle). We show that Reward Models trained in this manner can outperform Bradley-Terry models when matched for data and achieve top performance on RM-Bench (86.2%) and JudgeBench (81.4%, #1 on leaderboard as of September 24, 2025). Additionally, users can specify principles of interest at inference time to customize the focus of our reward models, in contrast to Bradley-Terry models. Finally, we present a fully open source recipe (including data) to align Qwen3-32B using RLBFF and our Reward Model, to match or exceed the performance of o3-mini and DeepSeek R1 on general alignment benchmarks of MT-Bench, WildBench, and Arena Hard v2 (at <5% of the inference cost).

[Arxiv](https://arxiv.org/abs/2509.21319)