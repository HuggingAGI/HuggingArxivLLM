# # 推理核心：面向LLM符号推理的可扩展强化学习环境

发布时间：2025年09月22日

`强化学习` `基础理论`

> Reasoning Core: A Scalable RL Environment for LLM Symbolic Reasoning

# 摘要

> 我们推出了Reasoning Core——一个全新的可扩展强化学习环境，专为具有可验证奖励的强化学习（RLVR）设计，旨在推动大型语言模型（LLMs）的基础符号推理能力发展。与现有专注于游戏或孤立谜题的基准不同，Reasoning Core能程序化生成跨核心形式化领域的问题，涵盖PDDL规划、一阶逻辑、上下文无关语法解析、因果推理及系统方程求解等。该环境基于三大关键设计原则构建：高通用性问题分布、外部工具验证以及难度连续控制，这些原则共同提供了近乎无限的全新训练实例。通过前沿LLMs进行的初步零样本评估证实，Reasoning Core的任务极具挑战性，这也使其成为提升未来模型推理能力的潜力资源。

> We introduce Reasoning Core, a new scalable environment for Reinforcement Learning with Verifiable Rewards (RLVR), designed to advance foundational symbolic reasoning in Large Language Models (LLMs). Unlike existing benchmarks that focus on games or isolated puzzles, Reasoning Core procedurally generates problems across core formal domains, including PDDL planning, first-order logic, context-free grammar parsing, causal reasoning, and system equation solving. The environment is built on key design principles of high-generality problem distributions, verification via external tools, and continuous difficulty control, which together provide a virtually infinite supply of novel training instances. Initial zero-shot evaluations with frontier LLMs confirm the difficulty of Reasoning Core's tasks, positioning it as a promising resource to improve the reasoning capabilities of future models.

[Arxiv](https://arxiv.org/abs/2509.18083)