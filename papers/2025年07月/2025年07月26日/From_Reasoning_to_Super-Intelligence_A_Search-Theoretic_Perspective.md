# 从推理到超智能：基于搜索理论的视角

发布时间：2025年07月26日

`LLM理论` `人工智能` `认知科学`

> From Reasoning to Super-Intelligence: A Search-Theoretic Perspective

# 摘要

> Chain-of-Thought (CoT) 推理已成为提升大型语言模型 (LLMs) 解决问题能力的强大力具。然而，从 CoT 数据中学习的理论基础仍显不足，现有方法 -- 如监督微调 (SFT)、强化学习 (RL)、思路树 (ToT) 和蒙特卡洛树搜索 (MCTS) -- 在处理复杂推理任务时表现欠佳。本研究识别出阻碍有效 CoT 学习的三大核心障碍：分布漂移、缺乏嵌入式搜索以及推理成本呈指数级增长。我们提出了一种全新的学习范式 -- Diligent Learner，它将推理建模为一种由验证器引导的深度优先搜索，并在推理失败时支持回溯。在两个温和且现实的假设下，我们证明了 Diligent Learner 可以高效地从 CoT 数据中学习，而现有方法则无法实现这一目标。这一框架为构建基于自然产生的不完整数据训练的可扩展且可靠的推理系统铺平了道路，为开发具有强大、可解释问题解决能力的大规模推理模型 (LRMs) 奠定了基础。

> Chain-of-Thought (CoT) reasoning has emerged as a powerful tool for enhancing the problem-solving capabilities of large language models (LLMs). However, the theoretical foundations of learning from CoT data remain underdeveloped, and existing approaches -- such as Supervised Fine-Tuning (SFT), Reinforcement Learning (RL), Tree-of-Thoughts (ToT), and Monte Carlo Tree Search (MCTS) -- often fail on complex reasoning tasks. In this work, we identify core obstacles that hinder effective CoT learning, including distribution drift, lack of embedded search, and exponential inference costs. We introduce the Diligent Learner, a new learning paradigm that explicitly models reasoning as a depth-first search guided by a validator and supports backtracking upon failure. Under two mild and realistic assumptions, we prove that the Diligent Learner can efficiently learn from CoT data while existing methods fail to do so. This framework offers a path toward building scalable and reliable reasoning systems trained on naturally occurring, incomplete data -- paving the way for the development of Large Reasoning Models (LRMs) with robust, interpretable problem-solving abilities.

[Arxiv](https://arxiv.org/abs/2507.15865)