# PSALM-V：借助大型语言模型，在交互式视觉环境中自动实现符号规划

发布时间：2025年06月24日

`LLM应用` `机器人` `人工智能`

> PSALM-V: Automating Symbolic Planning in Interactive Visual Environments with Large Language Models

# 摘要

> 我们提出了一种名为PSALM-V的首个自主神经符号学习系统，它能够在视觉环境中通过交互诱导符号动作语义（即前置和后置条件）。PSALM-V无需专家定义动作，利用大型语言模型生成启发式计划和候选符号语义，从而实现可靠地符号规划。此前的研究探索了使用大型语言模型为基于Planning Domain Definition Language (PDDL)的符号规划器生成动作语义。然而，这些方法主要集中在文本领域，或者依赖不切实际的假设，如访问预定义的问题文件、完全可观测性或明确的错误信息。相比之下，PSALM-V通过分析执行结果和综合可能的错误解释，动态推断PDDL问题文件和领域动作语义。该系统会迭代生成并执行计划，同时为每个动作维护一个树状结构的可能动作语义信念，并在迭代中不断优化这些信念，直到达到目标状态。在ALFRED中的任务完成模拟实验表明，PSALM-V在部分可观测设置中将计划成功率从37%（Claude-3.7）提升至74%。在两个2D游戏环境RTFM和Overcooked-AI上的实验结果表明，PSALM-V提高了步骤效率，并在多智能体设置中成功实现了领域归纳。尽管机器人在低级操作中存在失败，PSALM-V仍能正确推导出真实世界机器人BlocksWorld任务中的PDDL前置和后置条件。

> We propose PSALM-V, the first autonomous neuro-symbolic learning system able to induce symbolic action semantics (i.e., pre- and post-conditions) in visual environments through interaction. PSALM-V bootstraps reliable symbolic planning without expert action definitions, using LLMs to generate heuristic plans and candidate symbolic semantics. Previous work has explored using large language models to generate action semantics for Planning Domain Definition Language (PDDL)-based symbolic planners. However, these approaches have primarily focused on text-based domains or relied on unrealistic assumptions, such as access to a predefined problem file, full observability, or explicit error messages. By contrast, PSALM-V dynamically infers PDDL problem files and domain action semantics by analyzing execution outcomes and synthesizing possible error explanations. The system iteratively generates and executes plans while maintaining a tree-structured belief over possible action semantics for each action, iteratively refining these beliefs until a goal state is reached. Simulated experiments of task completion in ALFRED demonstrate that PSALM-V increases the plan success rate from 37% (Claude-3.7) to 74% in partially observed setups. Results on two 2D game environments, RTFM and Overcooked-AI, show that PSALM-V improves step efficiency and succeeds in domain induction in multi-agent settings. PSALM-V correctly induces PDDL pre- and post-conditions for real-world robot BlocksWorld tasks, despite low-level manipulation failures from the robot.

[Arxiv](https://arxiv.org/abs/2506.20097)