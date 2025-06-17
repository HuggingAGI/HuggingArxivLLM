# TimeMaster：通过强化学习训练时间序列多模态大语言模型进行推理

发布时间：2025年06月16日

`LLM应用` `时间序列分析`

> TimeMaster: Training Time-Series Multimodal LLMs to Reason via Reinforcement Learning

# 摘要

> # 摘要
时间序列推理在多模态大语言模型（MLLMs）中仍是重大挑战，主要源于动态时间模式、模糊语义及缺乏时间先验。本文提出TimeMaster，一种基于强化学习（RL）的方法，使时间序列MLLMs能直接对可视化时间序列输入和任务提示进行结构化、可解释推理。TimeMaster采用三部分结构化输出格式：推理、分类和领域扩展，并通过综合奖励函数优化，平衡格式遵循、预测准确性和开放性见解质量。模型训练分为两阶段：先用监督微调（SFT）建立良好初始化，再用组相对策略优化（GRPO）在标记级别实现稳定、有针对性的奖励驱动改进。我们在基于Qwen2.5-VL-3B-Instruct的TimerBed基准上，针对六个真实世界分类任务评估了TimeMaster。TimeMaster表现最优，分别比传统时间序列模型和少量样本GPT-4o高出14.6%和7.3%。值得注意的是，TimeMaster不仅超越时间序列分类：它还表现出专家级推理行为，生成上下文感知解释，并提供领域对齐见解。我们的结果表明，基于奖励的RL是将时间理解整合到时间序列MLLMs中的可扩展、有前途方法。


> Time-series reasoning remains a significant challenge in multimodal large language models (MLLMs) due to the dynamic temporal patterns, ambiguous semantics, and lack of temporal priors. In this work, we introduce TimeMaster, a reinforcement learning (RL)-based method that enables time-series MLLMs to perform structured, interpretable reasoning directly over visualized time-series inputs and task prompts. TimeMaster adopts a three-part structured output format, reasoning, classification, and domain-specific extension, and is optimized via a composite reward function that aligns format adherence, prediction accuracy, and open-ended insight quality. The model is trained using a two-stage pipeline: we first apply supervised fine-tuning (SFT) to establish a good initialization, followed by Group Relative Policy Optimization (GRPO) at the token level to enable stable and targeted reward-driven improvement in time-series reasoning. We evaluate TimeMaster on the TimerBed benchmark across six real-world classification tasks based on Qwen2.5-VL-3B-Instruct. TimeMaster achieves state-of-the-art performance, outperforming both classical time-series models and few-shot GPT-4o by over 14.6% and 7.3% performance gain, respectively. Notably, TimeMaster goes beyond time-series classification: it also exhibits expert-like reasoning behavior, generates context-aware explanations, and delivers domain-aligned insights. Our results highlight that reward-driven RL can be a scalable and promising path toward integrating temporal understanding into time-series MLLMs.

[Arxiv](https://arxiv.org/abs/2506.13705)