# 连接偏好对齐与机器遗忘：填补研究空白

发布时间：2025年04月09日

`LLM理论` `人工智能`

> Bridging the Gap Between Preference Alignment and Machine Unlearning

# 摘要

> 尽管大型语言模型（LLMs）的偏好对齐（PA）已取得进展，但主流方法如人类反馈的强化学习（RLHF）仍面临显著挑战。这些方法需要高质量的正向偏好示例数据集，获取成本高昂且计算密集，因训练不稳定而难以在资源有限场景中应用。LLM无学习技术提供了一个有前景的替代方案，通过直接移除负面示例的影响。然而，当前研究主要集中在经验验证上，缺乏系统性的定量分析。为填补这一空白，我们提出了一种框架来探索PA与LLM无学习之间的关系。具体而言，我们引入了一种基于双层优化的方法，量化无学习特定负面示例对PA性能的影响。我们的分析表明，无学习并非所有负面示例对对齐改进的贡献相同，且不同示例的效果差异显著。基于这一发现，我们提出了一个关键问题：如何最优地选择和加权负面示例进行无学习，以最大化PA性能？为解答此问题，我们提出了一个名为“无学习以对齐”（U2A）的框架，该框架利用双层优化高效地选择和无学习示例，以实现最优的PA性能。我们通过大量实验验证了所提方法，结果证实了其有效性。

> Despite advances in Preference Alignment (PA) for Large Language Models (LLMs), mainstream methods like Reinforcement Learning with Human Feedback (RLHF) face notable challenges. These approaches require high-quality datasets of positive preference examples, which are costly to obtain and computationally intensive due to training instability, limiting their use in low-resource scenarios. LLM unlearning technique presents a promising alternative, by directly removing the influence of negative examples. However, current research has primarily focused on empirical validation, lacking systematic quantitative analysis. To bridge this gap, we propose a framework to explore the relationship between PA and LLM unlearning. Specifically, we introduce a bi-level optimization-based method to quantify the impact of unlearning specific negative examples on PA performance. Our analysis reveals that not all negative examples contribute equally to alignment improvement when unlearned, and the effect varies significantly across examples. Building on this insight, we pose a crucial question: how can we optimally select and weight negative examples for unlearning to maximize PA performance? To answer this, we propose a framework called Unlearning to Align (U2A), which leverages bi-level optimization to efficiently select and unlearn examples for optimal PA performance. We validate the proposed method through extensive experiments, with results confirming its effectiveness.

[Arxiv](https://arxiv.org/abs/2504.06659)