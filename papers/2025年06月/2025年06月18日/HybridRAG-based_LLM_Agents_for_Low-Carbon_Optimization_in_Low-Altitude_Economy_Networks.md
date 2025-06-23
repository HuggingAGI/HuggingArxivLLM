# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月18日

`RAG` `无人机` `移动边缘计算`

> HybridRAG-based LLM Agents for Low-Carbon Optimization in Low-Altitude Economy Networks

# 摘要

> 低空经济网络（LAENets）正在成为一个有前景的范例，通过综合空地基础设施支持各种低空服务。为了满足低延迟和高计算需求，无人机（UAV）与移动边缘计算（MEC）系统的集成发挥着关键作用，将计算任务从终端设备转移到附近的无人机，从而为地面用户提供灵活且有弹性的服务。为了推动LAENets的发展，实现低碳多无人机辅助的MEC网络至关重要。然而，多维无人机建模的复杂性和多目标耦合优化的难度等挑战阻碍了这一目标的实现。

为此，本文提出了一种基于检索增强生成（RAG）的大语言模型（LLM）代理框架，用于模型构建。具体来说，我们通过结合关键词RAG、向量RAG和图RAG，开发了HybridRAG，使LLM代理能够高效地从专家数据库中检索结构化信息，并与传统RAG基LLM代理相比生成更准确的优化问题。在定制了多无人机辅助MEC网络的碳排放优化问题后，我们提出了一种双正则扩散增强的软 Actor-Critic（R	extsuperscript{2}DSAC）算法来解决所构建的多目标优化问题。R	extsuperscript{2}DSAC 算法引入了扩散熵正则化和动作熵正则化，以提升扩散策略的性能。此外，我们动态屏蔽_actor_网络中的不重要神经元，从而降低模型训练相关的碳排放。仿真结果验证了所提出的基于HybridRAG的LLM代理框架和R	extsuperscript{2}DSAC算法的有效性和可靠性。

> Low-Altitude Economy Networks (LAENets) are emerging as a promising paradigm to support various low-altitude services through integrated air-ground infrastructure. To satisfy low-latency and high-computation demands, the integration of Unmanned Aerial Vehicles (UAVs) with Mobile Edge Computing (MEC) systems plays a vital role, which offloads computing tasks from terminal devices to nearby UAVs, enabling flexible and resilient service provisions for ground users. To promote the development of LAENets, it is significant to achieve low-carbon multi-UAV-assisted MEC networks. However, several challenges hinder this implementation, including the complexity of multi-dimensional UAV modeling and the difficulty of multi-objective coupled optimization. To this end, this paper proposes a novel Retrieval Augmented Generation (RAG)-based Large Language Model (LLM) agent framework for model formulation. Specifically, we develop HybridRAG by combining KeywordRAG, VectorRAG, and GraphRAG, empowering LLM agents to efficiently retrieve structural information from expert databases and generate more accurate optimization problems compared with traditional RAG-based LLM agents. After customizing carbon emission optimization problems for multi-UAV-assisted MEC networks, we propose a Double Regularization Diffusion-enhanced Soft Actor-Critic (R\textsuperscript{2}DSAC) algorithm to solve the formulated multi-objective optimization problem. The R\textsuperscript{2}DSAC algorithm incorporates diffusion entropy regularization and action entropy regularization to improve the performance of the diffusion policy. Furthermore, we dynamically mask unimportant neurons in the actor network to reduce the carbon emissions associated with model training. Simulation results demonstrate the effectiveness and reliability of the proposed HybridRAG-based LLM agent framework and the R\textsuperscript{2}DSAC algorithm.

[Arxiv](https://arxiv.org/abs/2506.15947)