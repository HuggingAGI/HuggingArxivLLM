# 具身导航基础模型

发布时间：2025年09月15日

`Agent` `交通运输`

> Embodied Navigation Foundation Model

# 摘要

> 导航是具身人工智能的核心能力，体现了遵循语言指令在物理环境中感知与交互的智能水平。尽管大型视觉语言模型（VLMs）已取得显著进展，在通用视觉语言任务上展现出卓越的零样本性能，但其在具身导航中的泛化能力仍大多局限于狭窄的任务场景和特定具身架构。本研究提出跨具身、跨任务的导航基础模型（NavFoM），该模型基于八百万导航样本训练，涵盖四足机器人、无人机、轮式机器人及车辆等多种具身，涉及视觉语言导航、目标搜索、目标跟踪与自动驾驶等多样化任务。NavFoM采用统一架构，可处理不同相机配置与导航视野下的多模态导航输入。为适应多样化的相机设置和时间视野，NavFoM引入标识符令牌，用于嵌入具身的相机视角信息和任务的时间上下文。此外，为满足实际部署需求，NavFoM在有限的令牌长度限制下，通过动态调整的采样策略对所有观察令牌进行控制。公开基准测试的大量评估表明，该模型在多个导航任务和具身上均达到最先进或极具竞争力的性能，且无需特定任务微调。进一步的真实世界实验也证实了该方法强大的泛化能力和实际应用价值。

> Navigation is a fundamental capability in embodied AI, representing the intelligence required to perceive and interact within physical environments following language instructions. Despite significant progress in large Vision-Language Models (VLMs), which exhibit remarkable zero-shot performance on general vision-language tasks, their generalization ability in embodied navigation remains largely confined to narrow task settings and embodiment-specific architectures. In this work, we introduce a cross-embodiment and cross-task Navigation Foundation Model (NavFoM), trained on eight million navigation samples that encompass quadrupeds, drones, wheeled robots, and vehicles, and spanning diverse tasks such as vision-and-language navigation, object searching, target tracking, and autonomous driving. NavFoM employs a unified architecture that processes multimodal navigation inputs from varying camera configurations and navigation horizons. To accommodate diverse camera setups and temporal horizons, NavFoM incorporates identifier tokens that embed camera view information of embodiments and the temporal context of tasks. Furthermore, to meet the demands of real-world deployment, NavFoM controls all observation tokens using a dynamically adjusted sampling strategy under a limited token length budget. Extensive evaluations on public benchmarks demonstrate that our model achieves state-of-the-art or highly competitive performance across multiple navigation tasks and embodiments without requiring task-specific fine-tuning. Additional real-world experiments further confirm the strong generalization capability and practical applicability of our approach.

[Arxiv](https://arxiv.org/abs/2509.12129)