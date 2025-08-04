# # 标题
RL-PLUS: 利用混合策略优化在强化学习中缓解大型语言模型 (LLMs) 的能力边界坍塌问题

发布时间：2025年07月31日

`LLM理论` `数学推理`

> RL-PLUS: Countering Capability Boundary Collapse of LLMs in Reinforcement Learning with Hybrid-policy Optimization

# 摘要

> 可验证奖励的强化学习（RLVR）显著推动了大型语言模型（LLMs）复杂推理能力的提升。然而，受限于其与LLM巨大动作空间和稀疏奖励相匹配的在线策略方法，RLVR难以突破基础LLM的固有能力边界。进一步地，RLVR可能导致能力边界坍塌，从而限制LLM的问题解决范围。为了解决这一问题，我们提出了一种全新的方法——RL-PLUS，它通过协同内部利用（即思考）与外部数据（即学习），实现了更强的推理能力，并超越了基础模型的能力边界。RL-PLUS集成了两大核心组件：多重重要性采样，用于解决外部数据带来的分布失配问题；以及基于探索的优势函数，引导模型走向高价值、未被探索的推理路径。我们通过理论分析和大量实验，充分展示了本方法的优越性和通用性。实验结果显示，相较于现有RLVR方法，RL-PLUS在六个数学推理基准测试中均达到了当前最优性能，并在六个分布外推理任务中表现出色。此外，它在各类模型家族中均实现了稳定且显著的提升，平均相对改进幅度介于21.1%至69.2%之间。更重要的是，多个基准测试中的Pass@k曲线表明，RL-PLUS有效解决了能力边界坍塌问题。

> Reinforcement Learning with Verifiable Reward (RLVR) has significantly advanced the complex reasoning abilities of Large Language Models (LLMs). However, it struggles to break through the inherent capability boundaries of the base LLM, due to its inherently on-policy strategy with LLM's immense action space and sparse reward. Further, RLVR can lead to the capability boundary collapse, narrowing the LLM's problem-solving scope. To address this problem, we propose RL-PLUS, a novel approach that synergizes internal exploitation (i.e., Thinking) with external data (i.e., Learning) to achieve stronger reasoning capabilities and surpass the boundaries of base models. RL-PLUS integrates two core components: Multiple Importance Sampling to address for distributional mismatch from external data, and an Exploration-Based Advantage Function to guide the model towards high-value, unexplored reasoning paths. We provide both theoretical analysis and extensive experiments to demonstrate the superiority and generalizability of our approach. The results show that RL-PLUS achieves state-of-the-art performance compared with existing RLVR methods on six math reasoning benchmarks and exhibits superior performance on six out-of-distribution reasoning tasks. It also achieves consistent and significant gains across diverse model families, with average relative improvements ranging from 21.1\% to 69.2\%. Moreover, Pass@k curves across multiple benchmarks indicate that RL-PLUS effectively resolves the capability boundary collapse problem.

[Arxiv](https://arxiv.org/abs/2508.00222)