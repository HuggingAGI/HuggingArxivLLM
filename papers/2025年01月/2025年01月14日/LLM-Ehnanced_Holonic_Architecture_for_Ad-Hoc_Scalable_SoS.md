# LLM增强的Holonic架构：面向临时可扩展的SoS

发布时间：2025年01月14日

`Agent

理由：这篇论文主要讨论了系统之系统（SoS）的架构设计，特别是通过引入监督者、规划者、任务和资源holons等专门holons来提升SoS的适应性和可重构性。这些holons在推理层中运用大型语言模型（LLM）来支持决策并确保实时适应性。虽然论文中提到了LLM的应用，但其核心内容是关于如何通过智能体（Agent）的设计来提升系统的整体性能和适应性，因此更适合归类为Agent。` `智能城市` `系统架构`

> LLM-Ehnanced Holonic Architecture for Ad-Hoc Scalable SoS

# 摘要

> 随着现代系统之系统（SoS）日益趋向适应性强和以人为中心，传统架构在支持互操作性、可重构性和有效人机交互方面显得力不从心。本文通过推进SoS的整体架构技术，提出了两项关键贡献。首先，我们设计了一个分层架构，包含推理层、通信层和能力层，通过优化数据交换和集成，实现了异构系统间的无缝互操作。其次，借鉴智能制造理念，我们引入了监督者、规划者、任务和资源holons等专门holons，旨在提升SoS的适应性和可重构性。这些holons在推理层中运用大型语言模型，支持决策并确保实时适应性。我们通过一个智能城市交通的3D移动案例研究，展示了该方法在管理复杂多模式SoS环境中的潜力。此外，我们还提出了评估架构效率和可扩展性的方法，为未来的模拟和实际实施中的实证验证奠定了基础。

> As modern system of systems (SoS) become increasingly adaptive and human centred, traditional architectures often struggle to support interoperability, reconfigurability, and effective human system interaction. This paper addresses these challenges by advancing the state of the art holonic architecture for SoS, offering two main contributions to support these adaptive needs. First, we propose a layered architecture for holons, which includes reasoning, communication, and capabilities layers. This design facilitates seamless interoperability among heterogeneous constituent systems by improving data exchange and integration. Second, inspired by principles of intelligent manufacturing, we introduce specialised holons namely, supervisor, planner, task, and resource holons aimed at enhancing the adaptability and reconfigurability of SoS. These specialised holons utilise large language models within their reasoning layers to support decision making and ensure real time adaptability. We demonstrate our approach through a 3D mobility case study focused on smart city transportation, showcasing its potential for managing complex, multimodal SoS environments. Additionally, we propose evaluation methods to assess the architecture efficiency and scalability,laying the groundwork for future empirical validations through simulations and real world implementations.

[Arxiv](https://arxiv.org/abs/2501.07992)