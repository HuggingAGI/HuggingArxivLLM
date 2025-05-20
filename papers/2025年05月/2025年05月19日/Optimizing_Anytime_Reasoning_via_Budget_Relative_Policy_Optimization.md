# 优化随时推理的预算相对策略方法

发布时间：2025年05月19日

`LLM应用` `人工智能` `计算机科学`

> Optimizing Anytime Reasoning via Budget Relative Policy Optimization

# 摘要

> # 摘要  
提升大型语言模型 (LLMs) 的推理能力，扩展推理时的计算资源至关重要。现有方法通常采用强化学习 (RL) 来最大化推理轨迹结束时可验证的奖励。然而，此类方法仅在固定且较大的代币预算下优化最终性能，这在训练和部署过程中均限制了效率。本研究提出了一种全新的框架 AnytimeReasoner，旨在优化任意时刻的推理性能，从而在不同代币预算约束下提升代币效率和推理灵活性。为此，我们将完整的思考过程截断，以适应从先前分布中采样的代币预算，迫使模型为每个截断的思考过程总结最优答案供验证。这一过程将可验证的密集奖励引入推理环节，从而在强化学习优化中实现更有效的信用分配。随后，我们以解耦的方式优化思考和总结策略，以最大化累积奖励。此外，我们引入了一种新型方差缩减技术——预算相对策略优化 (BRPO)，在强化思考策略时增强学习过程的稳健性和效率。在数学推理任务中的实证结果表明，相较于 GRPO，我们的方法在各种先前分布下的所有思考预算中均表现更优，同时提升了训练和代币效率。

> Scaling test-time compute is crucial for enhancing the reasoning capabilities of large language models (LLMs). Existing approaches typically employ reinforcement learning (RL) to maximize a verifiable reward obtained at the end of reasoning traces. However, such methods optimize only the final performance under a large and fixed token budget, which hinders efficiency in both training and deployment. In this work, we present a novel framework, AnytimeReasoner, to optimize anytime reasoning performance, which aims to improve token efficiency and the flexibility of reasoning under varying token budget constraints. To achieve this, we truncate the complete thinking process to fit within sampled token budgets from a prior distribution, compelling the model to summarize the optimal answer for each truncated thinking for verification. This introduces verifiable dense rewards into the reasoning process, facilitating more effective credit assignment in RL optimization. We then optimize the thinking and summary policies in a decoupled manner to maximize the cumulative reward. Additionally, we introduce a novel variance reduction technique, Budget Relative Policy Optimization (BRPO), to enhance the robustness and efficiency of the learning process when reinforcing the thinking policy. Empirical results in mathematical reasoning tasks demonstrate that our method consistently outperforms GRPO across all thinking budgets under various prior distributions, enhancing both training and token efficiency.

[Arxiv](https://arxiv.org/abs/2505.13438)