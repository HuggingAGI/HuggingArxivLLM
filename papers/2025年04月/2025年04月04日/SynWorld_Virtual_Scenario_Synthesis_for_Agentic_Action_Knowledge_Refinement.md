# SynWorld：通过虚拟场景合成实现智能体动作知识的精炼

发布时间：2025年04月04日

`Agent` `人工智能`

> SynWorld: Virtual Scenario Synthesis for Agentic Action Knowledge Refinement

# 摘要

> 智能体通过与环境的互动来扩展能力，但基于LLM的智能体在面对新环境或非常规动作空间时往往力不从心。为了解决这一问题，我们提出了SynWorld框架。该框架使智能体能够合成多步动作调用的场景，并通过蒙特卡洛树搜索（MCTS）探索来优化动作知识。实验表明，SynWorld是一种高效且通用的解决方案。代码已开源，地址为https://github.com/zjunlp/SynWorld。

> In the interaction between agents and their environments, agents expand their capabilities by planning and executing actions. However, LLM-based agents face substantial challenges when deployed in novel environments or required to navigate unconventional action spaces. To empower agents to autonomously explore environments, optimize workflows, and enhance their understanding of actions, we propose SynWorld, a framework that allows agents to synthesize possible scenarios with multi-step action invocation within the action space and perform Monte Carlo Tree Search (MCTS) exploration to effectively refine their action knowledge in the current environment. Our experiments demonstrate that SynWorld is an effective and general approach to learning action knowledge in new environments. Code is available at https://github.com/zjunlp/SynWorld.

[Arxiv](https://arxiv.org/abs/2504.03561)