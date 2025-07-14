# AgentsNet：多智能体大语言模型中的协调与协作推理。

发布时间：2025年07月11日

`Agent` `多智能体系统` `分布式系统`

> AgentsNet: Coordination and Collaborative Reasoning in Multi-Agent LLMs

# 摘要

> 大型语言模型（LLMs）在多智能体系统中展现出了强大的问题解决能力，但如何有效利用复杂智能体网络的拓扑结构仍是一个挑战。我们提出了AgentsNet，一个多智能体推理的新基准，旨在评估智能体在给定网络拓扑下协作解决问题、自我组织和有效沟通的能力。通过从分布式系统和图论中的经典问题中汲取灵感，AgentsNet为多智能体系统提供了一个全面的测试框架。我们在AgentsNet上评估了多种基线方法，包括智能体的同质网络，这些智能体首先必须就组织和沟通的基本协议达成一致。实验结果表明，前沿的LLMs在小型网络中表现优异，但随着网络规模的扩大，性能逐渐下降。与现有最多涵盖2-5个智能体的多智能体基准不同，AgentsNet在规模上几乎是无限的，能够随着新世代LLMs的发展而扩展。因此，我们还在包含多达100个智能体的设置中对前沿模型进行了测试。


> Large-language models (LLMs) have demonstrated powerful problem-solving capabilities, in particular when organized in multi-agent systems. However, the advent of such systems also raises several questions on the ability of a complex network of agents to effectively self-organize and collaborate. While measuring performance on standard reasoning benchmarks indicates how well multi-agent systems can solve reasoning tasks, it is unclear whether these systems are able to leverage their topology effectively. Here, we propose AgentsNet, a new benchmark for multi-agent reasoning. By drawing inspiration from classical problems in distributed systems and graph theory, AgentsNet measures the ability of multi-agent systems to collaboratively form strategies for problem-solving, self-organization, and effective communication given a network topology. We evaluate a variety of baseline methods on AgentsNet including homogeneous networks of agents which first have to agree on basic protocols for organization and communication. We find that some frontier LLMs are already demonstrating strong performance for small networks but begin to fall off once the size of the network scales. While existing multi-agent benchmarks cover at most 2-5 agents, AgentsNet is practically unlimited in size and can scale with new generations of LLMs. As such, we also probe frontier models in a setup with up to 100 agents.

[Arxiv](https://arxiv.org/abs/2507.08616)