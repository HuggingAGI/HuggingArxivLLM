# 借助大型语言模型实现移动边缘计算的检索增强生成

发布时间：2024年12月30日

`RAG` `移动边缘计算` `无线通信`

> Retrieval-Augmented Generation for Mobile Edge Computing via Large Language Model

# 摘要

> 移动边缘计算（MEC）的迅猛发展，给高度动态的无线通信系统中的资源优化分配带来了重大挑战，其中任务卸载决策得实时做出。然而，现有的资源分配策略因缺乏可扩展性、上下文感知和可解释性，难以适应 MEC 系统的动态及异构特性。为应对这些问题，本文提出一种新颖的检索增强生成（RAG）方法，以提升 MEC 系统的性能。具体来说，先是提出一个延迟最小化问题，共同优化数据卸载率、传输功率分配和计算资源分配。接着，提出一种基于 LLM 的信息检索机制，有效解决该问题。在多用户、多任务和高度动态的卸载场景中开展的大量实验表明，与几种基于深度学习的方法相比，所提方法持续降低了延迟，在不同用户计算能力下提升了 57%，在不同服务器下提升了 86%，在不同传输功率下提升了 30%，在不同数据量下提升了 42%。这些结果显示出 LLM 驱动的解决方案在解决 MEC 系统资源分配问题上的有效性。

> The rapid evolution of mobile edge computing (MEC) has introduced significant challenges in optimizing resource allocation in highly dynamic wireless communication systems, in which task offloading decisions should be made in real-time. However, existing resource allocation strategies cannot well adapt to the dynamic and heterogeneous characteristics of MEC systems, since they are short of scalability, context-awareness, and interpretability. To address these issues, this paper proposes a novel retrieval-augmented generation (RAG) method to improve the performance of MEC systems. Specifically, a latency minimization problem is first proposed to jointly optimize the data offloading ratio, transmit power allocation, and computing resource allocation. Then, an LLM-enabled information-retrieval mechanism is proposed to solve the problem efficiently. Extensive experiments across multi-user, multi-task, and highly dynamic offloading scenarios show that the proposed method consistently reduces latency compared to several DL-based approaches, achieving 57% improvement under varying user computing ability, 86% with different servers, 30% under distinct transmit powers, and 42% for varying data volumes. These results show the effectiveness of LLM-driven solutions to solve the resource allocation problems in MEC systems.

[Arxiv](https://arxiv.org/abs/2412.20820)