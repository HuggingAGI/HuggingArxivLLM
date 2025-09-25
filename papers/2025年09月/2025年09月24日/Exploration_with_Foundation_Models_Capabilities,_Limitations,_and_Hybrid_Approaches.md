# # 借助基础模型的探索：能力、局限与混合方法

发布时间：2025年09月24日

`强化学习` `基础理论`

> Exploration with Foundation Models: Capabilities, Limitations, and Hybrid Approaches

# 摘要

> 强化学习（RL）中的探索仍是一大难题，尤其在稀疏奖励场景下。基础模型虽具备强大的语义先验，但其在经典RL基准测试中作为零样本探索智能体的能力尚不明确。为此，我们在多臂老虎机、网格世界和稀疏奖励Atari游戏上对LLM和VLM展开基准测试，以检验其零样本探索表现。研究发现一个关键局限：VLM虽能从视觉输入推断高层目标，却始终无法实现精确的低层控制——这就是“知易行难鸿沟”。为探索弥合这一鸿沟的可能路径，我们在受控的理想场景下研究了一种简单的在线混合框架。结果显示，在这种理想化环境中，VLM指导能显著提升早期样本效率，清晰阐明了基础模型用于指导探索而非端到端控制的潜力与局限。

> Exploration in reinforcement learning (RL) remains challenging, particularly in sparse-reward settings. While foundation models possess strong semantic priors, their capabilities as zero-shot exploration agents in classic RL benchmarks are not well understood. We benchmark LLMs and VLMs on multi-armed bandits, Gridworlds, and sparse-reward Atari to test zero-shot exploration. Our investigation reveals a key limitation: while VLMs can infer high-level objectives from visual input, they consistently fail at precise low-level control: the "knowing-doing gap". To analyze a potential bridge for this gap, we investigate a simple on-policy hybrid framework in a controlled, best-case scenario. Our results in this idealized setting show that VLM guidance can significantly improve early-stage sample efficiency, providing a clear analysis of the potential and constraints of using foundation models to guide exploration rather than for end-to-end control.

[Arxiv](https://arxiv.org/abs/2509.19924)