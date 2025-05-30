# 对抗对象融合干扰视觉语言模型驱动的导航服务

发布时间：2025年05月29日

`LLM应用` `服务计算` `服务安全`

> Disrupting Vision-Language Model-Driven Navigation Services via Adversarial Object Fusion

# 摘要

> 我们提出了一种全新的攻击框架——Adversarial Object Fusion（AdvOF），通过生成对抗的3D对象，专门针对面向服务环境中的视觉语言导航（VLN）代理设计。尽管大型语言模型（LLMs）和视觉语言模型（VLMs）等基础模型通过提升感知和决策能力显著增强了面向服务的导航系统，但它们的整合也为关键任务服务工作流程带来了新的安全挑战。现有对抗攻击方法未能有效应对服务计算环境，其中可靠性和服务质量（QoS）至关重要。我们利用AdvOF深入研究了对抗环境对VLN代理中基于VLM的感知模块的影响。具体而言，AdvOF首先精确地在2D和3D空间中聚集和对齐目标对象的位置，进而定义并渲染对抗对象。随后，通过在对抗对象和目标对象之间进行物理特性和VLM感知的正则化，我们实现了对抗对象的协同优化。通过为不同视角赋予重要性权重，优化过程通过迭代融合局部更新和验证，确保了稳定且多视角的处理效果。我们的实验结果表明，AdvOF不仅可以在对抗条件下有效降低代理性能，同时对正常导航任务的干扰最小。这项研究不仅深化了对VLM驱动导航系统中服务安全的理解，更为物理世界部署中实现稳健的服务组合提供了重要的计算基础。

> We present Adversarial Object Fusion (AdvOF), a novel attack framework targeting vision-and-language navigation (VLN) agents in service-oriented environments by generating adversarial 3D objects. While foundational models like Large Language Models (LLMs) and Vision Language Models (VLMs) have enhanced service-oriented navigation systems through improved perception and decision-making, their integration introduces vulnerabilities in mission-critical service workflows. Existing adversarial attacks fail to address service computing contexts, where reliability and quality-of-service (QoS) are paramount. We utilize AdvOF to investigate and explore the impact of adversarial environments on the VLM-based perception module of VLN agents. In particular, AdvOF first precisely aggregates and aligns the victim object positions in both 2D and 3D space, defining and rendering adversarial objects. Then, we collaboratively optimize the adversarial object with regularization between the adversarial and victim object across physical properties and VLM perceptions. Through assigning importance weights to varying views, the optimization is processed stably and multi-viewedly by iterative fusions from local updates and justifications. Our extensive evaluations demonstrate AdvOF can effectively degrade agent performance under adversarial conditions while maintaining minimal interference with normal navigation tasks. This work advances the understanding of service security in VLM-powered navigation systems, providing computational foundations for robust service composition in physical-world deployments.

[Arxiv](https://arxiv.org/abs/2505.23266)