# 以自我为中心多视图场景中视觉-语言模型的空间推理

发布时间：2025年09月07日

`LLM应用` `交通运输`

> Spatial Reasoning with Vision-Language Models in Ego-Centric Multi-View Scenes

# 摘要

> 当前视觉语言模型（VLMs）在理解3D空间关系方面仍存在显著局限。以往研究通过构建基于单图像或室内视频的空间问答（QA）数据集来应对这一挑战，然而现实世界中的具身AI智能体（如机器人和自动驾驶汽车）通常依赖以自我为中心的多视角观测数据。为此，我们提出Ego3D-Bench——一个全新基准，专门用于利用以自我为中心的多视角户外数据评估VLMs的空间推理能力。Ego3D-Bench包含8600多个QA对，由人类标注员深度参与构建，确保了数据的高质量和多样性。我们在16个当前最先进的VLMs上进行了基准测试，包括GPT-4o、Gemini1.5-Pro、InternVL3和Qwen2.5-VL。结果显示，人类水平分数与VLM性能之间存在显著差距，表明当前VLMs的空间理解能力仍远未达到人类水平。为弥合这一差距，我们提出Ego3D-VLM——一个用于增强VLMs 3D空间推理能力的后训练框架。该框架通过估计全局3D坐标生成认知地图，在多项选择QA任务上平均提升12%，在绝对距离估计任务上平均提升56%。Ego3D-VLM采用模块化设计，可与任何现有VLM集成。Ego3D-Bench与Ego3D-VLM共同构成了宝贵工具，助力在现实世界多视角环境中实现接近人类水平的空间理解。

> Understanding 3D spatial relationships remains a major limitation of current Vision-Language Models (VLMs). Prior work has addressed this issue by creating spatial question-answering (QA) datasets based on single images or indoor videos. However, real-world embodied AI agents such as robots and self-driving cars typically rely on ego-centric, multi-view observations. To this end, we introduce Ego3D-Bench, a new benchmark designed to evaluate the spatial reasoning abilities of VLMs using ego-centric, multi-view outdoor data. Ego3D-Bench comprises over 8,600 QA pairs, created with significant involvement from human annotators to ensure quality and diversity. We benchmark 16 SOTA VLMs, including GPT-4o, Gemini1.5-Pro, InternVL3, and Qwen2.5-VL. Our results reveal a notable performance gap between human level scores and VLM performance, highlighting that current VLMs still fall short of human level spatial understanding. To bridge this gap, we propose Ego3D-VLM, a post-training framework that enhances 3D spatial reasoning of VLMs. Ego3D-VLM generates cognitive map based on estimated global 3D coordinates, resulting in 12% average improvement on multi-choice QA and 56% average improvement on absolute distance estimation. Ego3D-VLM is modular and can be integrated with any existing VLM. Together, Ego3D-Bench and Ego3D-VLM offer valuable tools for advancing toward human level spatial understanding in real-world, multi-view environments.

[Arxiv](https://arxiv.org/abs/2509.06266)