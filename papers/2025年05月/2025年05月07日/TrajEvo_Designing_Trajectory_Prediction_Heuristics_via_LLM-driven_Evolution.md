# TrajEvo: 基于LLM驱动演化的轨迹预测启发式设计

发布时间：2025年05月07日

`LLM应用` `自动驾驶` `机器人`

> TrajEvo: Designing Trajectory Prediction Heuristics via LLM-driven Evolution

# 摘要

> 轨迹预测在社交机器人和自动驾驶导航等领域中至关重要。传统启发式方法准确性不足，深度学习方法又受限于计算成本和可解释性。本文提出TrajEvo框架，利用大型语言模型自动设计预测启发式方法。通过进化算法和跨代精英采样，提升种群多样性，结合统计反馈循环优化预测。实验显示，TrajEvo在ETH-UCY数据集表现优异，并在SDD数据集上显著超越传统方法。我们开源代码，推动研究发展。

> Trajectory prediction is a crucial task in modeling human behavior, especially in fields as social robotics and autonomous vehicle navigation. Traditional heuristics based on handcrafted rules often lack accuracy, while recently proposed deep learning approaches suffer from computational cost, lack of explainability, and generalization issues that limit their practical adoption. In this paper, we introduce TrajEvo, a framework that leverages Large Language Models (LLMs) to automatically design trajectory prediction heuristics. TrajEvo employs an evolutionary algorithm to generate and refine prediction heuristics from past trajectory data. We introduce a Cross-Generation Elite Sampling to promote population diversity and a Statistics Feedback Loop allowing the LLM to analyze alternative predictions. Our evaluations show TrajEvo outperforms previous heuristic methods on the ETH-UCY datasets, and remarkably outperforms both heuristics and deep learning methods when generalizing to the unseen SDD dataset. TrajEvo represents a first step toward automated design of fast, explainable, and generalizable trajectory prediction heuristics. We make our source code publicly available to foster future research at https://github.com/ai4co/trajevo.

[Arxiv](https://arxiv.org/abs/2505.04480)