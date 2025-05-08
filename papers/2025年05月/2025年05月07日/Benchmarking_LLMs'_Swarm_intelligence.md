# # 评估 LLM 的群体智能表现

发布时间：2025年05月07日

`LLM应用` `多智能体系统`

> Benchmarking LLMs' Swarm intelligence

# 摘要

> 大型语言模型（LLMs）在复杂推理方面展现出潜力，但它们在多智能体系统（MAS）中面对严格约束（如有限的局部感知和通信）时的协调能力尚未得到充分探索，尤其是群智的细微差别。现有基准测试往往未能捕捉到智能体在时空信息不完整情况下的独特挑战。为填补这一空白，我们推出了SwarmBench——首个系统评估LLMs作为去中心化智能体群智能力的基准测试。SwarmBench在可配置的2D网格环境中设置了五个基础MAS协调任务，强制智能体仅依赖局部感官输入（k x k视野）和局部通信。我们提出了协调有效性指标，并深入分析了群体动态。在零-shot设置下评估多个领先LLMs发现，其在不同任务中的表现差异显著，凸显了局部信息约束带来的挑战。尽管出现了一些协调行为，但结果表明LLMs在去中心化场景下的稳健规划和策略形成能力仍有待提升。在群智条件下评估LLMs对于释放其在去中心化系统中的潜力至关重要。SwarmBench作为一个开放且可扩展的工具包，基于具有定义机械特性的可定制和可扩展物理系统构建，提供了环境、提示、评估脚本和全面实验数据集，旨在推动基于LLM的MAS协调研究及其理论基础的发展。我们的代码库可在https://github.com/x66ccff/swarmbench获取。

> Large Language Models (LLMs) show potential for complex reasoning, yet their capacity for emergent coordination in Multi-Agent Systems (MAS) when operating under strict constraints-such as limited local perception and communication, characteristic of natural swarms-remains largely unexplored, particularly concerning the nuances of swarm intelligence. Existing benchmarks often do not fully capture the unique challenges of decentralized coordination that arise when agents operate with incomplete spatio-temporal information. To bridge this gap, we introduce SwarmBench, a novel benchmark designed to systematically evaluate the swarm intelligence capabilities of LLMs acting as decentralized agents. SwarmBench features five foundational MAS coordination tasks within a configurable 2D grid environment, forcing agents to rely primarily on local sensory input (k x k view) and local communication. We propose metrics for coordination effectiveness and analyze emergent group dynamics. Evaluating several leading LLMs in a zero-shot setting, we find significant performance variations across tasks, highlighting the difficulties posed by local information constraints. While some coordination emerges, results indicate limitations in robust planning and strategy formation under uncertainty in these decentralized scenarios. Assessing LLMs under swarm-like conditions is crucial for realizing their potential in future decentralized systems. We release SwarmBench as an open, extensible toolkit-built upon a customizable and scalable physical system with defined mechanical properties. It provides environments, prompts, evaluation scripts, and the comprehensive experimental datasets generated, aiming to foster reproducible research into LLM-based MAS coordination and the theoretical underpinnings of Embodied MAS. Our code repository is available at https://github.com/x66ccff/swarmbench.

[Arxiv](https://arxiv.org/abs/2505.04364)