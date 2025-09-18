# ASTREA：为轨道热自主引入智能体智能

发布时间：2025年09月16日

`Agent` `工业与制造`

> ASTREA: Introducing Agentic Intelligence for Orbital Thermal Autonomy

# 摘要

> 本文介绍了ASTREA——首个在具有飞行遗产的硬件（技术就绪度9级）上部署的自主航天器操作智能体系统。我们以热控制为典型应用场景，将资源受限的大型语言模型（LLM）智能体与强化学习控制器集成，构建了专为航天级平台设计的异步架构。地面实验显示，LLM引导的监督不仅提升了热稳定性，还减少了违规次数，证实了在硬件受限条件下融合语义推理与自适应控制的可行性。然而，在国际空间站（ISS）的在轨验证中发现，推理延迟与低地球轨道（LEO）卫星特有的快速热循环不匹配，导致了性能下降。这些结果既彰显了基于LLM的智能体系统在实际飞行环境中的应用潜力，也揭示了其当前的局限性，为未来太空自主性发展提供了实用的设计指导。

> This paper presents ASTREA, the first agentic system deployed on flight-heritage hardware (TRL 9) for autonomous spacecraft operations. Using thermal control as a representative use case, we integrate a resource-constrained Large Language Model (LLM) agent with a reinforcement learning controller in an asynchronous architecture tailored for space-qualified platforms. Ground experiments show that LLM-guided supervision improves thermal stability and reduces violations, confirming the feasibility of combining semantic reasoning with adaptive control under hardware constraints. However, on-orbit validation aboard the International Space Station (ISS) reveals performance degradation caused by inference latency mismatched with the rapid thermal cycles characteristic of Low Earth Orbit (LEO) satellites. These results highlight both the opportunities and current limitations of agentic LLM-based systems in real flight environments, providing practical design guidelines for future space autonomy.

[Arxiv](https://arxiv.org/abs/2509.13380)