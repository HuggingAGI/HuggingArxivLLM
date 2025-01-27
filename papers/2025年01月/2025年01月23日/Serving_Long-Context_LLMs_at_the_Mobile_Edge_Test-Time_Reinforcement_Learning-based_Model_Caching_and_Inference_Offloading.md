# 移动边缘的长上下文LLMs服务：基于测试时强化学习的模型缓存与推理卸载

发布时间：2025年01月23日

`Agent

理由：这篇论文主要讨论了在资源受限的移动边缘网络中如何优化大型语言模型（LLM）代理的服务部署和执行策略。论文提出了一种联合模型缓存和推理卸载框架，并利用测试时深度强化学习（T2DRL）来优化长上下文LLM服务的部署和执行策略。此外，论文还设计了一种双荷兰拍卖（DDA）机制来动态匹配供需，提升资源分配效率。这些内容主要围绕如何优化和管理LLM代理在边缘计算环境中的服务，因此将其分类为Agent。` `边缘计算` `资源优化`

> Serving Long-Context LLMs at the Mobile Edge: Test-Time Reinforcement Learning-based Model Caching and Inference Offloading

# 摘要

> 大型语言模型（LLMs）能够在未见任务上实现零-shot学习，并在复杂推理任务上实现少-shot学习。然而，资源受限的移动边缘网络在与用户进行多轮交互时，难以支持LLM代理的长上下文服务。与边缘计算中的无状态计算卸载和静态服务卸载不同，优化边缘服务器上的LLM服务颇具挑战，因为LLMs会不断从上下文中学习，从而影响准确性、延迟和资源消耗的动态变化。本文提出了一种联合模型缓存和推理卸载框架，利用测试时深度强化学习（T2DRL）来优化长上下文LLM服务的部署和执行策略。在该框架中，我们分析了性能收敛性，并设计了一个考虑LLMs上下文窗口利用的优化问题。此外，T2DRL算法能够在训练和测试阶段学习，主动管理缓存模型和服务请求，并在执行过程中适应上下文变化和使用模式。为了进一步提升资源分配效率，我们提出了一种双荷兰拍卖（DDA）机制，动态匹配供需，同时最大化社会福利。实验结果表明，与基线相比，T2DRL算法能够将系统成本降低至少30%，同时确保LLM代理在现实世界感知和推理任务中的性能表现。

> Large Language Models (LLMs) can perform zero-shot learning on unseen tasks and few-shot learning on complex reasoning tasks. However, resource-limited mobile edge networks struggle to support long-context LLM serving for LLM agents during multi-round interactions with users. Unlike stateless computation offloading and static service offloading in edge computing, optimizing LLM serving at edge servers is challenging because LLMs continuously learn from context which raises accuracy, latency, and resource consumption dynamics. In this paper, we propose a joint model caching and inference offloading framework that utilizes test-time deep reinforcement learning (T2DRL) to optimize deployment and execution strategies for long-context LLM serving. In this framework, we analyze the performance convergence and design an optimization problem considering the utilization of context windows in LLMs. Furthermore, the T2DRL algorithm can learn in both the training phase and the testing phase to proactively manage cached models and service requests and adapt to context changes and usage patterns during execution. To further enhance resource allocation efficiency, we propose a double Dutch auction (DDA) mechanism, which dynamically matches supply and demand while maximizing social welfare. Finally, experimental results demonstrate that the T2DRL algorithm can reduce system costs by at least 30% compared to baselines while guaranteeing the performance of LLM agents in real-world perception and reasoning tasks.

[Arxiv](https://arxiv.org/abs/2501.14205)