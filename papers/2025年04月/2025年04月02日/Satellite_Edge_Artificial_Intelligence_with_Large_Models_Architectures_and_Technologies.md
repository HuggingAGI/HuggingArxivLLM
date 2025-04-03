# # 卫星边缘人工智能基于大型模型：架构与技术

发布时间：2025年04月02日

`LLM应用`

> Satellite Edge Artificial Intelligence with Large Models: Architectures and Technologies

# 摘要

> # 摘要
随着智能遥感应用需求的激增，大规模AI模型通过在大规模无标签数据集上预训练并针对下游任务微调，凭借其强大的泛化能力显著提升了各类下游任务的学习性能。然而，许多特定下游任务，如极端天气短临预报（例如下击暴流和龙卷风）、灾害监测和战场 surveillance，需要实时数据处理。传统方法通过将原始数据传输到地面站进行处理，常常面临延迟和可信度问题。为解决这些挑战，卫星边缘AI通过利用空间计算能力网络（Space-CPN）中的通信与计算一体化能力，实现了从基于地面到基于星载的数据处理范式转变，从而提升了遥感下游任务的时效性、有效性和可信度。

此外，卫星边缘大规模AI模型（LAM）涉及训练（即微调）和推理两个阶段，其中关键挑战在于开发计算任务分解原则，以支持在资源受限且拓扑动态变化的空间网络中实现可扩展的LAM部署。本文首先提出了一种卫星联邦微调架构，用于将LAM的模块拆分并部署在空间和地面网络中，以实现高效的LAM微调。然后，我们引入了一种基于微服务的卫星边缘LAM推理架构，将LAM组件虚拟化为轻量级微服务，专门针对多任务多模态推理进行优化。最后，我们探讨了提升卫星边缘LAM效率和扩展性的未来方向，包括面向任务的通信、类脑计算和卫星边缘AI网络优化。

> Driven by the growing demand for intelligent remote sensing applications, large artificial intelligence (AI) models pre-trained on large-scale unlabeled datasets and fine-tuned for downstream tasks have significantly improved learning performance for various downstream tasks due to their generalization capabilities. However, many specific downstream tasks, such as extreme weather nowcasting (e.g., downburst and tornado), disaster monitoring, and battlefield surveillance, require real-time data processing. Traditional methods via transferring raw data to ground stations for processing often cause significant issues in terms of latency and trustworthiness. To address these challenges, satellite edge AI provides a paradigm shift from ground-based to on-board data processing by leveraging the integrated communication-and-computation capabilities in space computing power networks (Space-CPN), thereby enhancing the timeliness, effectiveness, and trustworthiness for remote sensing downstream tasks. Moreover, satellite edge large AI model (LAM) involves both the training (i.e., fine-tuning) and inference phases, where a key challenge lies in developing computation task decomposition principles to support scalable LAM deployment in resource-constrained space networks with time-varying topologies. In this article, we first propose a satellite federated fine-tuning architecture to split and deploy the modules of LAM over space and ground networks for efficient LAM fine-tuning. We then introduce a microservice-empowered satellite edge LAM inference architecture that virtualizes LAM components into lightweight microservices tailored for multi-task multimodal inference. Finally, we discuss the future directions for enhancing the efficiency and scalability of satellite edge LAM, including task-oriented communication, brain-inspired computing, and satellite edge AI network optimization.

[Arxiv](https://arxiv.org/abs/2504.01676)