# 多智能体LLM系统中的响应一致性建模：共享与独立上下文方法的比较分析

发布时间：2025年04月09日

`LLM应用

摘要讨论了大型语言模型（LLMs）在多智能体系统（MAS）中的应用，分析了上下文管理、响应一致性和扩展性挑战，并提出了一种概率框架来优化系统性能。研究重点在于LLM在MAS中的应用和优化，属于LLM应用类别。` `多智能体系统` `系统架构`

> Modeling Response Consistency in Multi-Agent LLM Systems: A Comparative Analysis of Shared and Separate Context Approaches

# 摘要

> 大型语言模型（LLMs）在多智能体系统（MAS）中的应用日益广泛，旨在提升协作问题解决与交互式推理能力。近期进展使LLMs能够作为自主智能体，理解多主题间的复杂交互。然而，将LLMs部署于MAS中带来了与上下文管理、响应一致性及扩展性相关的挑战，尤其在智能体需在内存限制下运行并处理噪声输入时。尽管先前研究探讨了优化LLM驱动MAS中的上下文共享与响应延迟，但这些努力往往聚焦于完全集中式或分散式配置，各具不同的权衡。

本文中，我们开发了一种概率框架，用于分析共享上下文配置与独立上下文配置对LLM基础MAS中响应一致性和响应时间的影响。我们引入了响应一致性指数（RCI）作为评估上下文限制、噪声及智能体间依赖对系统性能影响的指标。我们的方法不同于现有研究，侧重于内存约束与噪声管理的交互作用，为在具有相互依赖主题的环境中优化扩展性和响应时间提供了洞见。通过这一分析，我们全面理解了不同配置如何影响LLM驱动多智能体系统的效率，从而指导更稳健架构的设计。

> Large Language Models (LLMs) are increasingly utilized in multi-agent systems (MAS) to enhance collaborative problem-solving and interactive reasoning. Recent advancements have enabled LLMs to function as autonomous agents capable of understanding complex interactions across multiple topics. However, deploying LLMs in MAS introduces challenges related to context management, response consistency, and scalability, especially when agents must operate under memory limitations and handle noisy inputs. While prior research has explored optimizing context sharing and response latency in LLM-driven MAS, these efforts often focus on either fully centralized or decentralized configurations, each with distinct trade-offs.
  In this paper, we develop a probabilistic framework to analyze the impact of shared versus separate context configurations on response consistency and response times in LLM-based MAS. We introduce the Response Consistency Index (RCI) as a metric to evaluate the effects of context limitations, noise, and inter-agent dependencies on system performance. Our approach differs from existing research by focusing on the interplay between memory constraints and noise management, providing insights into optimizing scalability and response times in environments with interdependent topics. Through this analysis, we offer a comprehensive understanding of how different configurations impact the efficiency of LLM-driven multi-agent systems, thereby guiding the design of more robust architectures.

[Arxiv](https://arxiv.org/abs/2504.07303)