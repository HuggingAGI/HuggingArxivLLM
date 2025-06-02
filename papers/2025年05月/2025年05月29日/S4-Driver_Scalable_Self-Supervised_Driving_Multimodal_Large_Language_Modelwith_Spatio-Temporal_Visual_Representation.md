# S4-Driver：结合时空视觉表示的可扩展自监督驾驶多模态大规模语言模型。

发布时间：2025年05月29日

`LLM应用

摘要讨论了多模态大型语言模型（MLLMs）在自动驾驶中的应用，特别是端到端运动规划方法。研究者提出了一种基于MLLMs的自监督算法S4-Driver，用于在3D空间中进行运动规划。这属于LLM在实际任务中的应用。` `自动驾驶`

> S4-Driver: Scalable Self-Supervised Driving Multimodal Large Language Modelwith Spatio-Temporal Visual Representation

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展重新激发了人们对自动驾驶中端到端运动规划方法的浓厚兴趣。许多端到端方法依赖于人工标注来学习中间感知和预测任务，而纯自监督方法——直接从传感器输入中学习生成规划轨迹，无需人工标注，往往无法达到现有最优水平。我们发现输入表示空间中存在一个关键差距：基于MLLMs构建的端到端方法通常是在2D图像空间中进行预训练，而非自动驾驶车辆原生的3D规划空间。为此，我们提出了S4-Driver，一种基于流行PaLI多模态大型语言模型的可扩展自监督运动规划算法，采用时空视觉表示。S4-Driver采用了一种新颖的稀疏体积策略，无需微调视觉编码器，即可将MLLMs强大的视觉表示从视角空间无缝转换到3D空间。这种表示方法聚合了多视角和多帧的视觉输入，并在3D空间中实现了更好的规划轨迹预测。为了验证我们的方法，我们在nuScenes数据集和Waymo开放运动数据集（含内部摄像头数据）上进行了实验。结果显示，S4-Driver在与现有监督多任务方法的对比中表现优异，同时无需任何人工标注。它还在大量未标注的驾驶日志上表现出良好的可扩展性。

> The latest advancements in multi-modal large language models (MLLMs) have spurred a strong renewed interest in end-to-end motion planning approaches for autonomous driving. Many end-to-end approaches rely on human annotations to learn intermediate perception and prediction tasks, while purely self-supervised approaches--which directly learn from sensor inputs to generate planning trajectories without human annotations often underperform the state of the art. We observe a key gap in the input representation space: end-to-end approaches built on MLLMs are often pretrained with reasoning tasks in 2D image space rather than the native 3D space in which autonomous vehicles plan. To this end, we propose S4-Driver, a scalable self-supervised motion planning algorithm with spatio-temporal visual representation, based on the popular PaLI multimodal large language model. S4-Driver uses a novel sparse volume strategy to seamlessly transform the strong visual representation of MLLMs from perspective view to 3D space without the need to finetune the vision encoder. This representation aggregates multi-view and multi-frame visual inputs and enables better prediction of planning trajectories in 3D space. To validate our method, we run experiments on both nuScenes and Waymo Open Motion Dataset (with in-house camera data). Results show that S4-Driver performs favorably against existing supervised multi-task approaches while requiring no human annotations. It also demonstrates great scalability when pretrained on large volumes of unannotated driving logs.

[Arxiv](https://arxiv.org/abs/2505.24139)