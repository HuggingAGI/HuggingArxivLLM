# 利用预训练大型语言模型实现机器人流水线实时控制

发布时间：2025年03月05日

`LLM应用` `制造业` `机器人`

> Pretrained LLMs as Real-Time Controllers for Robot Operated Serial Production Line

# 摘要

> 制造业正迎来一场由5G、AI和云计算等尖端技术引领的变革。尽管技术飞速发展，但要实现高效的系统控制——这对于优化生产效率至关重要——依然面临巨大挑战。这主要是因为制造过程本身的复杂性和知识依赖性，以及对特定领域专业知识的依赖。传统控制方法通常需要大量定制，消耗大量计算资源，且在决策过程中缺乏透明度。在本研究中，我们探讨了使用大型语言模型（LLMs），特别是GPT-4，作为一种简单灵活的解决方案来控制制造系统，具体而言是移动机器人调度。我们提出了一种基于LLM的控制框架，用于将移动机器人分配到机器人辅助的串行生产线上的不同机器上，并评估其在系统吞吐量方面的表现。我们的框架在性能上优于传统的调度方法，如先到先得（FCFS）、最短处理时间（SPT）和最长处理时间（LPT）。虽然其性能与多智能体强化学习（MARL）等最先进的方法相当，但它无需大量重新训练即可实现类似的吞吐量，这是其独特优势。这些结果表明，所提出的基于LLM的解决方案非常适合技术专业知识、计算资源和资金投入有限，但需要决策透明和系统可扩展性关键的场景。

> The manufacturing industry is undergoing a transformative shift, driven by cutting-edge technologies like 5G, AI, and cloud computing. Despite these advancements, effective system control, which is crucial for optimizing production efficiency, remains a complex challenge due to the intricate, knowledge-dependent nature of manufacturing processes and the reliance on domain-specific expertise. Conventional control methods often demand heavy customization, considerable computational resources, and lack transparency in decision-making. In this work, we investigate the feasibility of using Large Language Models (LLMs), particularly GPT-4, as a straightforward, adaptable solution for controlling manufacturing systems, specifically, mobile robot scheduling. We introduce an LLM-based control framework to assign mobile robots to different machines in robot assisted serial production lines, evaluating its performance in terms of system throughput. Our proposed framework outperforms traditional scheduling approaches such as First-Come-First-Served (FCFS), Shortest Processing Time (SPT), and Longest Processing Time (LPT). While it achieves performance that is on par with state-of-the-art methods like Multi-Agent Reinforcement Learning (MARL), it offers a distinct advantage by delivering comparable throughput without the need for extensive retraining. These results suggest that the proposed LLM-based solution is well-suited for scenarios where technical expertise, computational resources, and financial investment are limited, while decision transparency and system scalability are critical concerns.

[Arxiv](https://arxiv.org/abs/2503.03889)