# RLHF 中的能量损失现象：应对奖励攻击的新思路

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在人类反馈强化学习（RLHF）中的能量损失现象及其与奖励黑客行为的关联，并提出了理论基础和解决方案。论文不仅进行了实证分析，还提供了理论证明，并提出了新的算法（EPPO）来缓解奖励黑客行为。这些内容主要涉及LLM的理论分析和算法改进，因此归类为“LLM理论”。` `人工智能`

> The Energy Loss Phenomenon in RLHF: A New Perspective on Mitigating Reward Hacking

# 摘要

> # 摘要
本研究揭示了人类反馈强化学习（RLHF）中的能量损失现象及其与奖励黑客行为的关联。具体而言，大型语言模型（LLM）最后一层的能量损失在强化学习过程中逐渐增加，能量损失的过度增加是奖励黑客行为的标志。除了实证分析，我们还提供了理论基础，证明在温和条件下，能量损失的增加会降低LLM中上下文相关性的上限，这是奖励黑客行为的关键特征，因为上下文相关性的降低通常意味着对奖励模型偏好的模式过度拟合。为解决这一问题，我们提出了一种能量损失感知的PPO算法（EPPO），该算法在奖励计算中惩罚LLM最后一层能量损失的增加，以防止能量损失过度，从而缓解奖励黑客行为。我们从理论上证明，EPPO可被概念化为一种熵正则化的强化学习算法，这为理解其有效性提供了更深入的见解。在各种LLM和任务上的广泛实验表明，能量损失现象普遍存在，且	exttt{EPPO}在减轻奖励黑客行为和提高RLHF性能方面效果显著。

> This work identifies the Energy Loss Phenomenon in Reinforcement Learning from Human Feedback (RLHF) and its connection to reward hacking. Specifically, energy loss in the final layer of a Large Language Model (LLM) gradually increases during the RL process, with an excessive increase in energy loss characterizing reward hacking. Beyond empirical analysis, we further provide a theoretical foundation by proving that, under mild conditions, the increased energy loss reduces the upper bound of contextual relevance in LLMs, which is a critical aspect of reward hacking as the reduced contextual relevance typically indicates overfitting to reward model-favored patterns in RL. To address this issue, we propose an Energy loss-aware PPO algorithm (EPPO) which penalizes the increase in energy loss in the LLM's final layer during reward calculation to prevent excessive energy loss, thereby mitigating reward hacking. We theoretically show that EPPO can be conceptually interpreted as an entropy-regularized RL algorithm, which provides deeper insights into its effectiveness. Extensive experiments across various LLMs and tasks demonstrate the commonality of the energy loss phenomenon, as well as the effectiveness of \texttt{EPPO} in mitigating reward hacking and improving RLHF performance.

[Arxiv](https://arxiv.org/abs/2501.19358)