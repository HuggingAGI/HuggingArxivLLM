# RM-R1：奖励建模即推理

发布时间：2025年05月05日

`LLM应用` `人工智能` `机器学习`

> RM-R1: Reward Modeling as Reasoning

# 摘要

> 奖励建模是将大型语言模型（LLMs）与人类偏好对齐的关键，尤其是在通过强化学习从人类反馈（RLHF）中学习时。为了提供准确的奖励信号，奖励模型（RM）需要激发深度思考，并在赋分或做出判断前进行可解释的推理。然而，现有的RMs要么生成不透明的标量分数，要么直接生成偏好答案的预测，这使得它们难以整合自然语言批评，从而缺乏可解释性。受到近期在需要推理的任务中长链式推理（CoT）取得的进展启发，我们假设并验证了将推理能力整合到奖励建模中可以显著提升RM的可解释性和性能。在本研究中，我们引入了一类新的生成式奖励模型——推理奖励模型（ReasRMs），它将奖励建模视为一个推理任务。我们提出了一种以推理为导向的训练 pipeline，并训练了一组ReasRMs，即RM-R1。训练包括两个关键阶段：（1）高质量推理链的蒸馏；（2）具有可验证奖励的强化学习。RM-R1通过自动生成推理轨迹或聊天特定的评分标准，并根据这些标准评估候选响应来提升LLM的输出质量。实证结果显示，我们的模型在多个全面的奖励模型基准测试中达到了生成式RMs的最先进或接近最先进性能，比更大规模的开源模型（如Llama3.1-405B）和专有模型（如GPT-4o）高出13.8%。除了最终性能，我们还进行了彻底的实证分析，以理解成功训练ReasRM的关键要素。为了促进未来研究，我们在https://github.com/RM-R1-UIUC/RM-R1发布了六个ReasRM模型，以及相应的代码和数据。


> Reward modeling is essential for aligning large language models (LLMs) with human preferences, especially through reinforcement learning from human feedback (RLHF). To provide accurate reward signals, a reward model (RM) should stimulate deep thinking and conduct interpretable reasoning before assigning a score or a judgment. However, existing RMs either produce opaque scalar scores or directly generate the prediction of a preferred answer, making them struggle to integrate natural language critiques, thus lacking interpretability. Inspired by recent advances of long chain-of-thought (CoT) on reasoning-intensive tasks, we hypothesize and validate that integrating reasoning capabilities into reward modeling significantly enhances RM's interpretability and performance. In this work, we introduce a new class of generative reward models -- Reasoning Reward Models (ReasRMs) -- which formulate reward modeling as a reasoning task. We propose a reasoning-oriented training pipeline and train a family of ReasRMs, RM-R1. The training consists of two key stages: (1) distillation of high-quality reasoning chains and (2) reinforcement learning with verifiable rewards. RM-R1 improves LLM rollouts by self-generating reasoning traces or chat-specific rubrics and evaluating candidate responses against them. Empirically, our models achieve state-of-the-art or near state-of-the-art performance of generative RMs across multiple comprehensive reward model benchmarks, outperforming much larger open-weight models (e.g., Llama3.1-405B) and proprietary ones (e.g., GPT-4o) by up to 13.8%. Beyond final performance, we perform thorough empirical analysis to understand the key ingredients of successful ReasRM training. To facilitate future research, we release six ReasRM models along with code and data at https://github.com/RM-R1-UIUC/RM-R1.

[Arxiv](https://arxiv.org/abs/2505.02387)