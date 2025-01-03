# 基于图神经网络与LLM驱动的多智能体系统，实现快速自动化合金设计

发布时间：2024年10月17日

`Agent

理由：这篇论文描述了一个多智能体AI系统，该系统整合了多模态数据和外部知识，用于自动化发现新型金属合金。系统包含多个AI智能体，这些智能体能够动态协作，并且由LLM驱动的AI智能体协作探索设计空间。此外，系统还使用了图神经网络（GNN）模型来快速检索关键物理属性。这些特征表明该论文主要关注多智能体系统的设计和应用，因此应归类为Agent。` `材料科学` `人工智能`

> Rapid and Automated Alloy Design with Graph Neural Network-Powered LLM-Driven Multi-Agent Systems

# 摘要

> # 摘要
多智能体AI模型用于自动化发现新型金属合金，整合了多模态数据和外部知识，包括通过原子模拟获得的物理见解。我们的系统包含三个核心组件：(a) 一套负责推理和规划等任务的LLMs，(b) 一组具备不同专长的AI智能体，能够动态协作，(c) 一个新开发的图神经网络（GNN）模型，用于快速检索关键物理属性。一组由LLM驱动的AI智能体协作探索MPEAs的广阔设计空间，由GNN的预测指导。我们专注于NbMoTa家族的面心立方（bcc）合金，使用基于ML的原子间势进行建模，并瞄准两个关键属性：Peierls势垒和溶质/螺位错相互作用能。GNN模型准确预测了这些原子尺度属性，为昂贵的暴力计算提供了更快的替代方案，并减少了多智能体系统在物理检索上的计算负担。该AI系统通过减少对人类专业知识的依赖并克服直接全原子模拟的局限性，彻底改变了材料发现。通过将GNN的预测能力与基于LLM的智能体的动态协作相结合，该系统自主导航广阔的合金设计空间，识别原子尺度材料属性的趋势并预测宏观机械强度，如多个计算实验所示。这种方法加速了先进合金的发现，并为其他复杂系统的更广泛应用提供了希望，标志着自动化材料设计的重要一步。

> A multi-agent AI model is used to automate the discovery of new metallic alloys, integrating multimodal data and external knowledge including insights from physics via atomistic simulations. Our multi-agent system features three key components: (a) a suite of LLMs responsible for tasks such as reasoning and planning, (b) a group of AI agents with distinct roles and expertise that dynamically collaborate, and (c) a newly developed graph neural network (GNN) model for rapid retrieval of key physical properties. A set of LLM-driven AI agents collaborate to automate the exploration of the vast design space of MPEAs, guided by predictions from the GNN. We focus on the NbMoTa family of body-centered cubic (bcc) alloys, modeled using an ML-based interatomic potential, and target two key properties: the Peierls barrier and solute/screw dislocation interaction energy. Our GNN model accurately predicts these atomic-scale properties, providing a faster alternative to costly brute-force calculations and reducing the computational burden on multi-agent systems for physics retrieval. This AI system revolutionizes materials discovery by reducing reliance on human expertise and overcoming the limitations of direct all-atom simulations. By synergizing the predictive power of GNNs with the dynamic collaboration of LLM-based agents, the system autonomously navigates vast alloy design spaces, identifying trends in atomic-scale material properties and predicting macro-scale mechanical strength, as demonstrated by several computational experiments. This approach accelerates the discovery of advanced alloys and holds promise for broader applications in other complex systems, marking a significant step forward in automated materials design.

[Arxiv](https://arxiv.org/abs/2410.13768)