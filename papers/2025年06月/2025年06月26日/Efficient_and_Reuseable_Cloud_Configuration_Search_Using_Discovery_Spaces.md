# 高效且可重用的云配置搜索，利用发现空间

发布时间：2025年06月26日

`其他` `云计算` `资源优化`

> Efficient and Reuseable Cloud Configuration Search Using Discovery Spaces

# 摘要

> 在云计算环境中，寻找一个能够在满足既定服务级别协议（SLA）的前提下以最低成本部署给定工作负载的最优云资源集合，是一个活跃的研究领域。由于需要结合云服务提供商提供的计算、存储和服务中数十个适用参数，以及同样数量的应用特定参数，这导致配置空间中出现了数百万种部署选项。

在这篇论文中，我们提出了Discovery Space这一抽象概念，它能够形式化地描述工作负载配置问题，并展示了一组用于在大规模搜索空间中进行结构化、稳健和分布式研究所需的特性。我们描述了Discovery Space抽象的具体实现，并证明了它能够跨多种多样的工作负载（如大型语言模型推理和大数据分析）实现泛化应用。

我们展示了我们的方法如何支持不同最优配置器执行之间的安全透明数据共享，从而提高大规模搜索空间中最优配置检测的效率。我们还展示了Discovery Spaces如何实现相似搜索空间之间的知识迁移与复用，从而实现超过90%的配置搜索速度提升。


> Finding the optimal set of cloud resources to deploy a given workload at minimal cost while meeting a defined service level agreement is an active area of research. Combining tens of parameters applicable across a large selection of compute, storage, and services offered by cloud providers with similar numbers of application-specific parameters leads to configuration spaces with millions of deployment options.
  In this paper, we propose Discovery Space, an abstraction that formalizes the description of workload configuration problems, and exhibits a set of characteristics required for structured, robust and distributed investigations of large search spaces. We describe a concrete implementation of the Discovery Space abstraction and show that it is generalizable across a diverse set of workloads such as Large Language Model inference and Big Data Analytics.
  We demonstrate that our approach enables safe, transparent sharing of data between executions of best-of-breed optimizers increasing the efficiency of optimal configuration detection in large search spaces. We also demonstrate how Discovery Spaces enable transfer and reuse of knowledge across similar search spaces, enabling configuration search speed-ups of over 90%.

[Arxiv](https://arxiv.org/abs/2506.21467)