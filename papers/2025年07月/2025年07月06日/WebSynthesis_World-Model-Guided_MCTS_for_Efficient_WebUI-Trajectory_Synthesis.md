# # WebSynthesis: 基于世界模型的蒙特卡洛树搜索实现高效WebUI轨迹合成

发布时间：2025年07月06日

`Agent

摘要中讨论了网络代理的改进，特别是通过合成轨迹和虚拟环境模拟来解决真实环境中的挑战。核心贡献在于代理的自我改进方法，属于Agent类别。` `网络技术`

> WebSynthesis: World-Model-Guided MCTS for Efficient WebUI-Trajectory Synthesis

# 摘要

> 大型语言模型（LLMs）的最新进展大大提升了网络代理的能力。然而，要在复杂多变的网络环境中游刃有余，仍需更高级的规划与执行策略。先前的研究通过收集真实环境交互中的大量GUI轨迹来解决自我改进代理的问题。尽管这些方法有效，但它们面临两大关键挑战：(1) 不可控的环境状态，真实或沙盒网络环境常导致不稳定且非确定性的反馈，增加了代理行为的复现和调试难度；(2) 高昂的API成本，因为生成单次交互轨迹可能涉及数百次查询，带来显著的API使用和计算开销。

为克服这些限制并实现代理的可扩展自我改进，我们提出WebSynthesis——一种创新的轨迹合成与训练框架。WebSynthesis利用学习到的环境模型模拟虚拟网络环境，使策略代理能够进行高效且可逆的树状规划。此方法支持大规模生成多样且高质量的轨迹，随后用于优化代理的策略。实验结果表明，基于小型合成数据集通过WebSynthesis训练的代理，其性能可媲美甚至超越基于大规模真实数据训练的模型。

> Recent advancements in large language models (LLMs) have significantly improved the capabilities of web agents. However, effectively navigating complex and dynamic web environments still requires more advanced trajectory-level planning and execution. Prior studies have addressed self-improving agents by collecting extensive GUI trajectories from real-environment interactions. Despite their effectiveness, these approaches encounter two critical challenges: (1) Uncontrollable environment states, where real or sandboxed web environments often yield unstable and non-deterministic feedback, complicating the reproduction and debugging of agent behaviors; and (2) High API costs, as generating even a single interaction trajectory can involve hundreds of queries, leading to considerable API usage and computational expenses. To address these limitations and enable scalable self-improvement for agents, we propose WebSynthesis, a novel framework for trajectory synthesis and training. WebSynthesis leverages a learned world model to simulate virtual web environments, allowing a policy agent to perform efficient and reversible tree-based planning. This approach supports the large-scale generation of diverse and high-quality trajectories, which are subsequently utilized to refine the agent's policy. Experimental results demonstrate that an agent trained using WebSynthesis on a small-scale synthetic dataset achieves performance comparable to or even surpassing that of models trained on large-scale real-world data.

[Arxiv](https://arxiv.org/abs/2507.04370)