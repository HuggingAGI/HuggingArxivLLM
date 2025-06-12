# DreamCS：几何感知的文本到3D生成，采用无配对3D奖励监督方法。

发布时间：2025年06月11日

`LLM应用

理由：这篇论文展示了大型语言模型在3D生成任务中的应用，特别是在数据标注和偏好建模方面，属于LLM的具体应用案例。` `计算机图形学` `生成模型`

> DreamCS: Geometry-Aware Text-to-3D Generation with Unpaired 3D Reward Supervision

# 摘要

> 文本到3D生成技术虽备受关注，但现有方法难以生成符合人类偏好的3D资产。传统偏好对齐技术依赖难以获取的多视图2D图像对来训练2D奖励模型，这些模型指导3D生成时往往因2D偏见导致几何失真。为解决这一问题，我们构建了首个大规模无配对3D偏好数据集3D-MeshPref，其中包含由大型语言模型标注并经人工优化的多样化3D网格。随后，我们开发了RewardCS，这是首个直接基于3D-MeshPref数据训练的奖励模型，采用创新的Cauchy-Schwarz散度目标函数，在无需配对比较的情况下有效学习与人类偏好对齐的3D几何偏好。在此基础上，我们提出了DreamCS，一个整合RewardCS的统一文本到3D框架，通过引入人类偏好反馈，显著提升了隐式和显式3D生成效果。实验结果表明，DreamCS超越现有方法，生成的3D资产既保真又符合人类偏好。相关代码和模型即将公开发布。

> While text-to-3D generation has attracted growing interest, existing methods often struggle to produce 3D assets that align well with human preferences. Current preference alignment techniques for 3D content typically rely on hardly-collected preference-paired multi-view 2D images to train 2D reward models, when then guide 3D generation -- leading to geometric artifacts due to their inherent 2D bias. To address these limitations, we construct 3D-MeshPref, the first large-scale unpaired 3D preference dataset, featuring diverse 3D meshes annotated by a large language model and refined by human evaluators. We then develop RewardCS, the first reward model trained directly on unpaired 3D-MeshPref data using a novel Cauchy-Schwarz divergence objective, enabling effective learning of human-aligned 3D geometric preferences without requiring paired comparisons. Building on this, we propose DreamCS, a unified framework that integrates RewardCS into text-to-3D pipelines -- enhancing both implicit and explicit 3D generation with human preference feedback. Extensive experiments show DreamCS outperforms prior methods, producing 3D assets that are both geometrically faithful and human-preferred. Code and models will be released publicly.

[Arxiv](https://arxiv.org/abs/2506.09814)