# 目标导向的媒体访问理论：协议设计与分布式多臂老虎机学习

发布时间：2025年08月26日

`Agent` `交通运输`

> A Theory of Goal-Oriented Medium Access: Protocol Design and Distributed Bandit Learning

# 摘要

> 目标导向通信（GoC）范式打破了通信与数据内容的割裂，让通信决策贴合接收方的具体需求，同时聚焦应用性能优化。尽管近期研究在点对点场景中已实现出色的编码性能，但多节点分布式场景却几乎仍是空白。此外，少数相关研究采用集中式无冲突方案，由中央调度器统一安排节点的传输顺序。本研究聚焦目标导向多址接入（GoMA）问题：多个智能体需协同共享无线信道，同时避免相互干扰。我们构建了分布式GoMA分析与优化的理论框架，为全面揭示其特性奠定了基础。研究证明，该问题具有非凸性，且可能存在多个纳什均衡（NE）解。我们明确了每个节点对其他节点策略的最佳响应机制，并提出一种优化方法——该方法能确保收敛到某个NE，性能较集中式方案提升最高达100%，能耗也同步降低。我们还设计了一种分布式学习算法，可在有限反馈、无先验知识的条件下运行。

> The Goal-oriented Communication (GoC) paradigm breaks the separation between communication and the content of the data, tailoring communication decisions to the specific needs of the receiver and targeting application performance. While recent studies show impressive encoding performance in point-to-point scenarios, the multi-node distributed scenario is still almost unexplored. Moreover, the few studies to investigate this consider a centralized collision-free approach, where a central scheduler decides the transmission order of the nodes. In this work, we address the Goal-oriented Multiple Access (GoMA) problem, in which multiple intelligent agents must coordinate to share a wireless channel and avoid mutual interference. We propose a theoretical framework for the analysis and optimization of distributed GoMA, serving as a first step towards its complete characterization. We prove that the problem is non-convex and may admit multiple Nash Equilibrium (NE) solutions. We provide a characterization of each node's best response to others' strategies and propose an optimization approach that provably reaches one such NE, outperforming centralized approaches by up to 100% while also reducing energy consumption. We also design a distributed learning algorithm that operates with limited feedback and no prior knowledge.

[Arxiv](https://arxiv.org/abs/2508.19141)