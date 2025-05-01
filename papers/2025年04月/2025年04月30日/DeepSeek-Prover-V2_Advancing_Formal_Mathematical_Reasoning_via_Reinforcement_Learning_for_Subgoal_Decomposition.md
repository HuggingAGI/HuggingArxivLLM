# DeepSeek-Prover-V2: 利用强化学习实现子目标分解，助力形式数学推理能力的提升

发布时间：2025年04月30日

`LLM应用

理由：这篇论文讨论了DeepSeek-Prover-V2在形式化定理证明中的应用，展示了其在数学推理中的实际效果，属于大型语言模型的具体应用案例。` `数学定理证明` `数学竞赛`

> DeepSeek-Prover-V2: Advancing Formal Mathematical Reasoning via Reinforcement Learning for Subgoal Decomposition

# 摘要

> 我们推出 DeepSeek-Prover-V2，一款专为 Lean 4 环境下的形式化定理证明设计的开源大型语言模型。该模型的初始化数据由 DeepSeek-V3 驱动的递归式定理证明流水线收集而来。我们的冷启动训练流程首先利用 DeepSeek-V3 将复杂问题分解为一系列子目标，然后将这些子目标的证明整合成链式思维过程，结合 DeepSeek-V3 的逐步推理，为强化学习构建初始冷启动。这一创新方法使我们成功将非正式与正式数学推理融合于同一模型。最终，DeepSeek-Prover-V2-671B 在神经定理证明领域达到顶尖水平，于 MiniF2F-test 上取得 88.9% 的通过率，并解决 PutnamBench 中的 49 个问题。除了标准测试集，我们还推出了包含 325 个形式化问题的 ProverBench，其中包括精选自 AIME 竞赛（24-25 年）的 15 个问题，进一步丰富了评估维度。在 AIME 问题的评估中，模型成功解决 6 个问题，而 DeepSeek-V3 则通过多数投票方法解决了其中 8 个。这表明大型语言模型在正式与非正式数学推理之间的差距正在显著缩小。

> We introduce DeepSeek-Prover-V2, an open-source large language model designed for formal theorem proving in Lean 4, with initialization data collected through a recursive theorem proving pipeline powered by DeepSeek-V3. The cold-start training procedure begins by prompting DeepSeek-V3 to decompose complex problems into a series of subgoals. The proofs of resolved subgoals are synthesized into a chain-of-thought process, combined with DeepSeek-V3's step-by-step reasoning, to create an initial cold start for reinforcement learning. This process enables us to integrate both informal and formal mathematical reasoning into a unified model. The resulting model, DeepSeek-Prover-V2-671B, achieves state-of-the-art performance in neural theorem proving, reaching 88.9% pass ratio on the MiniF2F-test and solving 49 out of 658 problems from PutnamBench. In addition to standard benchmarks, we introduce ProverBench, a collection of 325 formalized problems, to enrich our evaluation, including 15 selected problems from the recent AIME competitions (years 24-25). Further evaluation on these 15 AIME problems shows that the model successfully solves 6 of them. In comparison, DeepSeek-V3 solves 8 of these problems using majority voting, highlighting that the gap between formal and informal mathematical reasoning in large language models is substantially narrowing.

[Arxiv](https://arxiv.org/abs/2504.21801)