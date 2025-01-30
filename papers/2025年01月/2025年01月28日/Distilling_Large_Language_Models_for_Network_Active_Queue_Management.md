# 网络主动队列管理中的大型语言模型蒸馏

发布时间：2025年01月28日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进主动队列管理（AQM）系统，特别是在低延迟、低丢包和可扩展吞吐量的场景中。论文提出了AQM-LLM方法，通过少样本学习、上下文理解和模式识别来提炼LLMs，以提升网络性能。这属于LLM在实际应用中的使用，因此分类为LLM应用。` `网络通信` `队列管理`

> Distilling Large Language Models for Network Active Queue Management

# 摘要

> 随着网络流量的日益复杂和对超低延迟通信的需求，智能数据包流量管理变得至关重要。现有的基于深度学习的排队方法在动态网络场景中表现不佳，且需要大量工程投入。我们提出了AQM-LLM，通过少样本学习、上下文理解和模式识别来提炼大型语言模型（LLMs），以最小的手动努力改进主动队列管理（AQM）[RFC 9330]。我们特别关注低延迟、低丢包和可扩展吞吐量（L4S）的AQM场景，并通过推测解码和基于强化的LLM提炼，利用显式拥塞通知（ECN）[RFC 9331]和周期性丢包来解决L4S架构中的拥塞预防问题。我们在FreeBSD-14上开发了一个新的开源实验平台，提供可互操作的模块以支持LLM集成，并通过更广泛的测试促进IETF的认可。广泛的评估表明，L4S-LLM显著提升了队列管理，预防了拥塞，减少了延迟，并提高了网络性能，充分展示了LLMs在提升AQM系统方面的适应性和效率。

> The growing complexity of network traffic and demand for ultra-low latency communication require smarter packet traffic management. Existing Deep Learning-based queuing approaches struggle with dynamic network scenarios and demand high engineering effort. We propose AQM-LLM, distilling Large Language Models (LLMs) with few-shot learning, contextual understanding, and pattern recognition to improve Active Queue Management (AQM) [RFC 9330] with minimal manual effort. We consider a specific case where AQM is Low Latency, Low Loss, and Scalable Throughput (L4S) and our design of AQM-LLM builds on speculative decoding and reinforcement-based distilling of LLM by tackling congestion prevention in the L4S architecture using Explicit Congestion Notification (ECN) [RFC 9331] and periodic packet dropping. We develop a new open-source experimental platform by executing L4S-AQM on FreeBSD-14, providing interoperable modules to support LLM integration and facilitate IETF recognition through wider testing. Our extensive evaluations show L4S-LLM enhances queue management, prevents congestion, reduces latency, and boosts network performance, showcasing LLMs' adaptability and efficiency in uplifting AQM systems.

[Arxiv](https://arxiv.org/abs/2501.16734)