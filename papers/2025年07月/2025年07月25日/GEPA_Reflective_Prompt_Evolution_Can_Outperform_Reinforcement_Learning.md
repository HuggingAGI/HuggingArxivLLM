# GEPA：反思式提示进化超越强化学习

发布时间：2025年07月25日

`LLM应用` `AI系统优化`

> GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）正越来越多地通过强化学习（RL）方法（如Group Relative Policy Optimization，GRPO）来适应下游任务，但这些方法往往需要数千次迭代才能掌握新任务。我们认为，与基于稀疏标量奖励的策略梯度相比，语言的可解释性为LLMs提供了更丰富多样的学习媒介。为此，我们提出了GEPA（Genetic-Pareto），一种结合自然语言反思的提示优化器，能够通过试错法提炼高层规则。对于任何包含LLM提示的AI系统，GEPA都会采样系统级轨迹（如推理过程、工具调用及输出），并以自然语言进行反思，以诊断问题、提出和测试提示更新，并从自身尝试的Pareto前沿中汲取互补经验。得益其独特设计，GEPA往往能将少量迭代转化为显著的质量提升。在四项任务中，GEPA平均比GRPO高出10%，最高提升20%，且迭代次数减少35倍。此外，GEPA在两个LLM上超越了领先的提示优化器MIPROv2，高出10%以上，并作为代码优化的推理时搜索策略展现了巨大潜力。

> Large language models (LLMs) are increasingly adapted to downstream tasks via reinforcement learning (RL) methods like Group Relative Policy Optimization (GRPO), which often require thousands of rollouts to learn new tasks. We argue that the interpretable nature of language can often provide a much richer learning medium for LLMs, compared with policy gradients derived from sparse, scalar rewards. To test this, we introduce GEPA (Genetic-Pareto), a prompt optimizer that thoroughly incorporates natural language reflection to learn high-level rules from trial and error. Given any AI system containing one or more LLM prompts, GEPA samples system-level trajectories (e.g., reasoning, tool calls, and tool outputs) and reflects on them in natural language to diagnose problems, propose and test prompt updates, and combine complementary lessons from the Pareto frontier of its own attempts. As a result of GEPA's design, it can often turn even just a few rollouts into a large quality gain. Across four tasks, GEPA outperforms GRPO by 10% on average and by up to 20%, while using up to 35x fewer rollouts. GEPA also outperforms the leading prompt optimizer, MIPROv2, by over 10% across two LLMs, and demonstrates promising results as an inference-time search strategy for code optimization.

[Arxiv](https://arxiv.org/abs/2507.19457)