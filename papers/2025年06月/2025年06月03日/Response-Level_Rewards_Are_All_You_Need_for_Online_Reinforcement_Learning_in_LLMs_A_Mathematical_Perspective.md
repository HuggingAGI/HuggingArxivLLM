# # 基于响应的奖励机制是大型语言模型在线强化学习中唯一所需：从数学角度解析

发布时间：2025年06月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在强化学习中的理论挑战，特别是零奖励假设及其对策略梯度的影响。通过引入轨迹策略梯度定理和提出新算法TRePO，论文主要贡献在于理论层面，因此归类为LLM理论。`

> Response-Level Rewards Are All You Need for Online Reinforcement Learning in LLMs: A Mathematical Perspective

# 摘要

> 我们研究了大型语言模型 (LLMs) 强化学习中的一个关键挑战：零奖励假设。在这种假设下，非终止动作（即中间生成的标记）不会获得任何特定任务的即时奖励，只有最终标记为整个响应提供奖励。这一假设在实际应用中非常常见，因为在 LLM 应用中，精确的标记级奖励往往难以获取或不可行。在本研究中，我们提供了一个统一的理论视角。

我们引入了轨迹策略梯度定理，该定理表明：对于 REINFORCE 和 Actor-Critic 家族中的算法，即使零奖励假设是否成立，也可以仅使用响应级奖励模型来无偏估计基于真实、未知标记级奖励的策略梯度。这一发现揭示了 PPO、GRPO、ReMax 和 RLOO 等广泛应用的方法本质上具备建模标记级奖励信号的能力，为响应级奖励方法提供了理论依据。

我们的研究为更实用、高效的 LLM 微调开辟了道路，使开发者能够将训练算法视为黑箱，专注于通过辅助子模型改进响应级奖励模型。我们还对流行 RL 和非 RL 方法进行了详细分析，比较了它们在常见 LLM 任务中的理论基础和实际优势。最后，我们提出了一种新算法：Token-Reinforced Policy Optimization (TRePO)。这是一种基于理论的方法，比 PPO 更简单，与 GRPO 在内存效率上相匹配，并且具有广泛适用性的潜力。

> We study a common challenge in reinforcement learning for large language models (LLMs): the Zero-Reward Assumption, where non-terminal actions (i.e., intermediate token generations) receive zero task-specific immediate reward, while only the final token receives a reward for the entire response. This assumption arises frequently in practice, as precise token-level rewards are often difficult or infeasible to obtain in LLM applications. In this work, we provide a unifying theoretical perspective. We introduce the Trajectory Policy Gradient Theorem, which shows that the policy gradient based on true, unknown token-level rewards can be unbiasedly estimated using only a response-level reward model, regardless of whether the Zero-Reward Assumption holds or not, for algorithms in the REINFORCE and Actor-Critic families. This result reveals that widely used methods such as PPO, GRPO, ReMax, and RLOO inherently possess the capacity to model token-level reward signals, offering a theoretical justification for response-level reward approaches. Our findings pave the way for more practical, efficient LLM fine-tuning, allowing developers to treat training algorithms as black boxes and focus on improving the response-level reward model with auxiliary sub-models. We also offer a detailed analysis of popular RL and non-RL methods, comparing their theoretical foundations and practical advantages across common LLM tasks. Finally, we propose a new algorithm: Token-Reinforced Policy Optimization (TRePO), a theoretically grounded method that is simpler than PPO, matches GRPO in memory efficiency, and holds promise for broad applicability.

[Arxiv](https://arxiv.org/abs/2506.02553)