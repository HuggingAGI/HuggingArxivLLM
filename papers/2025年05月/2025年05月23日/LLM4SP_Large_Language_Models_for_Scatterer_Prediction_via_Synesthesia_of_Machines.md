# LLM4SP：借助机器联觉，用大型语言模型预测散射体

发布时间：2025年05月23日

`LLM应用` `智能交通` `智能交通系统`

> LLM4SP: Large Language Models for Scatterer Prediction via Synesthesia of Machines

# 摘要

> 基于机器联觉（SoM），感觉信息与通信信息的非线性映射关系为智能交通系统（ITSs）中的V2V多模态智能信道建模（MMICM）提供了提升精度与泛化能力的有力工具。为探索物理环境与电磁空间的映射关系，构建了多频段、多车辆交通密度（VTDs）场景下的V2V通信智能感知-通信融合数据集V2V-M3。借助大型语言模型（LLMs）的强表征与跨模态推理能力，提出了一种基于LLM的散射体预测方法（LLM4SP），用于从光检测和测距（LiDAR）点云中进行预测。针对多模态数据间的显著差异，通过考虑感知/信道特性和电磁传播机制，设计了协同优化的四模块架构：预处理器、嵌入模块、主干网络和输出模块。基于跨模态表征对齐与位置编码，对LLM4SP网络进行了微调，以捕捉LiDAR点云与散射体间的普遍映射关系。仿真结果表明，LLM4SP在全样本与泛化测试中表现优异，显著超越了不同频率、场景和VTDs下的小型模型。

> Guided by Synesthesia of Machines (SoM), the nonlinear mapping relationship between sensory and communication information serves as a powerful tool to enhance both the accuracy and generalization of vehicle-to-vehicle (V2V) multi-modal intelligent channel modeling (MMICM) in intelligent transportation systems (ITSs). To explore the general mapping relationship between physical environment and electromagnetic space, a new intelligent sensing-communication integration dataset, named V2V-M3, is constructed for multiple scenarios in V2V communications with multiple frequency bands and multiple vehicular traffic densities (VTDs). Leveraging the strong representation and cross-modal inference capabilities of large language models (LLMs), a novel LLM-based method for Scatterer Prediction (LLM4SP) from light detection and ranging (LiDAR) point clouds is developed. To address the inherent and significant differences across multi-modal data, synergistically optimized four-module architecture, i.e., preprocessor, embedding, backbone, and output modules, are designed by considering the sensing/channel characteristics and electromagnetic propagation mechanism. On the basis of cross-modal representation alignment and positional encoding, the network of LLM4SP is fine-tuned to capture the general mapping relationship between LiDAR point clouds and scatterers. Simulation results demonstrate that the proposed LLM4SP achieves superior performance in full-sample and generalization testing, significantly outperforming small models across different frequency bands, scenarios, and VTDs.

[Arxiv](https://arxiv.org/abs/2505.17879)