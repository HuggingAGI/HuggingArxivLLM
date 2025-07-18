# Bradley-Terry 与多目标奖励模型相辅相成

发布时间：2025年07月09日

`LLM理论

摘要讨论了在人类反馈强化学习（RLHF）框架下，奖励模型如何与大型语言模型（LLMs）对齐，并提出了一种新的奖励建模框架来应对奖励黑客攻击的问题。这属于大型语言模型（LLM）的理论和方法改进，因此分类为LLM理论。` `奖励建模`

> Bradley-Terry and Multi-Objective Reward Modeling Are Complementary

# 摘要

> 基于人类偏好数据训练的奖励模型在人类反馈强化学习 (RLHF) 框架下，能够有效将大型语言模型 (LLMs) 与人类意图对齐。然而，RLHF 仍面临奖励黑客攻击的挑战，即策略可能利用奖励函数的不完美性而非真正学习预期行为。尽管已有大量研究致力于缓解这一问题，但现有方法主要针对同分布场景，即奖励模型的训练与测试数据分布一致。我们通过实证研究表明，现有先进方法在更具挑战性的异分布 (OOD) 场景下表现欠佳。我们发现，引入细粒度多属性评分有助于应对这一挑战。然而，高质量数据的匮乏常导致多目标奖励函数性能受限，可能成为整体表现的瓶颈。为此，我们提出了一种统一的奖励建模框架，通过共享嵌入空间联合训练 Bradley--Terry (BT) 单目标和基于回归的多目标奖励函数。我们从理论上揭示了 BT 损失与回归目标之间的联系，并展示了它们的互补优势：回归任务增强了单目标奖励函数在 OOD 场景下缓解奖励黑客攻击的能力，而 BT 训练提升了多目标奖励函数的评分能力，使 70亿参数模型超越了 700亿参数基线。大量实验结果表明，我们的框架显著提升了奖励模型的鲁棒性和评分性能。

> Reward models trained on human preference data have demonstrated strong effectiveness in aligning Large Language Models (LLMs) with human intent under the framework of Reinforcement Learning from Human Feedback (RLHF). However, RLHF remains vulnerable to reward hacking, where the policy exploits imperfections in the reward function rather than genuinely learning the intended behavior. Although significant efforts have been made to mitigate reward hacking, they predominantly focus on and evaluate in-distribution scenarios, where the training and testing data for the reward model share the same distribution. In this paper, we empirically show that state-of-the-art methods struggle in more challenging out-of-distribution (OOD) settings. We further demonstrate that incorporating fine-grained multi-attribute scores helps address this challenge. However, the limited availability of high-quality data often leads to weak performance of multi-objective reward functions, which can negatively impact overall performance and become the bottleneck. To address this issue, we propose a unified reward modeling framework that jointly trains Bradley--Terry (BT) single-objective and multi-objective regression-based reward functions using a shared embedding space. We theoretically establish a connection between the BT loss and the regression objective and highlight their complementary benefits. Specifically, the regression task enhances the single-objective reward function's ability to mitigate reward hacking in challenging OOD settings, while BT-based training improves the scoring capability of the multi-objective reward function, enabling a 7B model to outperform a 70B baseline. Extensive experimental results demonstrate that our framework significantly improves both the robustness and the scoring performance of reward models.

[Arxiv](https://arxiv.org/abs/2507.07375)