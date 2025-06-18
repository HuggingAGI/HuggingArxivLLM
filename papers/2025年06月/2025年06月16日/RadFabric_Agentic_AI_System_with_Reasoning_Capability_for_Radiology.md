# RadFabric：面向放射学的推理型智能体AI系统

发布时间：2025年06月16日

`Agent` `医学影像分析`

> RadFabric: Agentic AI System with Reasoning Capability for Radiology

# 摘要

> 胸部X光成像依然是胸腔疾病诊断的重要工具，但现有自动化系统在病理覆盖、诊断准确性和视觉-文本推理整合方面存在明显局限。为此，我们推出了RadFabric——一个基于多智能体的多模态推理框架，通过整合视觉与文本分析实现全面的CXR解读。RadFabric基于模型上下文协议（MCP）构建，支持模块化、互操作性和可扩展性，便于无缝集成新的诊断智能体。系统配备了专门的CXR智能体用于病理检测，解剖解释智能体将视觉发现与精确解剖结构对应，并借助大型多模态推理模型驱动的推理智能体，整合视觉、解剖和临床数据，生成透明且基于证据的诊断。RadFabric在性能上实现了显著提升，对骨折等高难度病理的检测准确率几乎达到完美（1.000），整体诊断准确率（0.799）远超传统系统（0.229至0.527）。通过整合跨模态特征对齐和偏好驱动推理，RadFabric推动了AI驱动的放射学向透明、解剖精确且具有临床指导意义的CXR分析迈进。

> Chest X ray (CXR) imaging remains a critical diagnostic tool for thoracic conditions, but current automated systems face limitations in pathology coverage, diagnostic accuracy, and integration of visual and textual reasoning. To address these gaps, we propose RadFabric, a multi agent, multimodal reasoning framework that unifies visual and textual analysis for comprehensive CXR interpretation. RadFabric is built on the Model Context Protocol (MCP), enabling modularity, interoperability, and scalability for seamless integration of new diagnostic agents. The system employs specialized CXR agents for pathology detection, an Anatomical Interpretation Agent to map visual findings to precise anatomical structures, and a Reasoning Agent powered by large multimodal reasoning models to synthesize visual, anatomical, and clinical data into transparent and evidence based diagnoses. RadFabric achieves significant performance improvements, with near-perfect detection of challenging pathologies like fractures (1.000 accuracy) and superior overall diagnostic accuracy (0.799) compared to traditional systems (0.229 to 0.527). By integrating cross modal feature alignment and preference-driven reasoning, RadFabric advances AI-driven radiology toward transparent, anatomically precise, and clinically actionable CXR analysis.

[Arxiv](https://arxiv.org/abs/2506.14142)