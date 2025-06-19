# LLM 智能体实现超参数优化

发布时间：2025年06月18日

`LLM应用

理由：这篇论文主要讨论了如何利用大语言模型（LLM）作为代理，自动调整超参数以优化通信算法性能。研究重点在于将LLM应用于超参数调优，展示了其在实际问题中的有效性，属于LLM的应用层面。` `通信技术` `无人机通信`

> LLM Agent for Hyper-Parameter Optimization

# 摘要

> 超参数对通信算法性能至关重要。目前，针对基于无线电地图的无人机轨迹和通信的带交叉与变异的暖启动粒子群优化算法（WS-PSO-CM），超参数调整主要依赖启发式方法，存在自动化水平低且效果不理想的问题。本文设计了一种基于大语言模型（LLM）的代理，用于自动超参数调优，其中应用了迭代框架和模型上下文协议（MCP）。具体来说，首先通过配置文件设置LLM代理，明确任务、背景和输出格式。然后，LLM代理根据提示需求驱动，并通过迭代调用WS-PSO-CM算法进行探索。最后，LLM代理自主终止循环并返回一组超参数。实验结果表明，通过我们的LLM代理生成的超参数所达到的最小总速率显著高于人工启发式方法和随机生成方法。这表明，具备PSO知识和WS-PSO-CM算法背景的LLM代理在寻找高性能超参数方面具有实用价值。

> Hyper-parameters are essential and critical for the performance of communication algorithms. However, current hyper-parameters tuning methods for warm-start particles swarm optimization with cross and mutation (WS-PSO-CM) algortihm for radio map-enabled unmanned aerial vehicle (UAV) trajectory and communication are primarily heuristic-based, exhibiting low levels of automation and unsatisfactory performance. In this paper, we design an large language model (LLM) agent for automatic hyper-parameters-tuning, where an iterative framework and model context protocol (MCP) are applied. In particular, the LLM agent is first setup via a profile, which specifies the mission, background, and output format. Then, the LLM agent is driven by the prompt requirement, and iteratively invokes WS-PSO-CM algorithm for exploration. Finally, the LLM agent autonomously terminates the loop and returns a set of hyper-parameters. Our experiment results show that the minimal sum-rate achieved by hyper-parameters generated via our LLM agent is significantly higher than those by both human heuristics and random generation methods. This indicates that an LLM agent with PSO knowledge and WS-PSO-CM algorithm background is useful in finding high-performance hyper-parameters.

[Arxiv](https://arxiv.org/abs/2506.15167)