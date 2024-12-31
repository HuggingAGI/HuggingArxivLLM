# 大型语言模型边缘推理的分布式代理混合体

发布时间：2024年12月30日

`Agent` `分布式计算` `语言模型`

> Distributed Mixture-of-Agents for Edge Inference with Large Language Models

# 摘要

> 最近，混合物代理（MoA）被提出作为提升大型语言模型（LLMs）性能的方法，能让多个单独的LLMs协同工作进行推理。这种协同方式相比依赖单个LLM，能为用户提示提供更优的响应。在本文中，我们探讨了分布式环境下的这种MoA架构，其中LLMs在各个边缘设备上运行，每个设备都与唯一的用户相关联，并具备自身的分布式计算能力。这些设备通过去中心化的八卦算法交换信息，使得不同设备节点无需中央服务器监管就能交流。在这种设定下，不同用户拥有各自的LLM模型来处理用户提示。而且，设备要么传递自身用户特定的提示，要么传递增强提示，以生成对某些查询更精准的答案。当对应的LLM忙碌时，用户提示会暂时存于设备队列中。鉴于边缘设备的内存限制，保证系统中的平均队列规模保持有限至关重要。本文中，我们在合理假设下通过理论计算设备队列的排队稳定性条件来解决此问题，并通过实验进行了验证。此外，我们通过实验表明，利用开源LLMs实现分布式MoA，在AlpacaEval 2.0基准评估中，某些MoA配置生成的响应质量高于其他配置。实现可在以下网址获取：https://github.com/purbeshmitra/distributed_moa。

> Mixture-of-Agents (MoA) has recently been proposed as a method to enhance performance of large language models (LLMs), enabling multiple individual LLMs to work together for collaborative inference. This collaborative approach results in improved responses to user prompts compared to relying on a single LLM. In this paper, we consider such an MoA architecture in a distributed setting, where LLMs operate on individual edge devices, each uniquely associated with a user and equipped with its own distributed computing power. These devices exchange information using decentralized gossip algorithms, allowing different device nodes to talk without the supervision of a centralized server. In the considered setup, different users have their own LLM models to address user prompts. Additionally, the devices gossip either their own user-specific prompts or augmented prompts to generate more refined answers to certain queries. User prompts are temporarily stored in the device queues when their corresponding LLMs are busy. Given the memory limitations of edge devices, it is crucial to ensure that the average queue sizes in the system remain bounded. In this paper, we address this by theoretically calculating the queuing stability conditions for the device queues under reasonable assumptions, which we validate experimentally as well. Further, we demonstrate through experiments, leveraging open-source LLMs for the implementation of distributed MoA, that certain MoA configurations produce higher-quality responses compared to others, as evaluated on AlpacaEval 2.0 benchmark. The implementation is available at: https://github.com/purbeshmitra/distributed_moa.

[Arxiv](https://arxiv.org/abs/2412.21200)