# SceneAware：基于场景约束的行人轨迹预测与LLM引导的可步行性分析

发布时间：2025年06月16日

`LLM应用` `机器人` `监控系统`

> SceneAware: Scene-Constrained Pedestrian Trajectory Prediction with LLM-Guided Walkability

# 摘要

> 精准预测行人轨迹对于机器人和监控系统应用至关重要。现有方法虽关注行人互动，却忽视了环境因素对行为模式的巨大影响。本文提出SceneAware框架，通过显式引入场景理解能力，显著提升了轨迹预测的准确性。我们采用Vision Transformer（ViT）处理场景图像，结合多模态大语言模型生成可行走性掩膜，区分可通行与受限区域。框架融合了基于Transformer的轨迹编码器和ViT场景编码器，捕捉时序动态与空间约束。集成的碰撞惩罚机制确保预测结果的物理合理性。SceneAware提供确定性和随机性两种实现方式。在ETH/UCY数据集上的实验显示，我们的方法超越现有最优模型，预测精度提升超50%。分析表明，模型在各类行人运动中均表现优异，证明场景感知方法的有效性和可靠性。代码已开源：https://github.com/juho127/SceneAware。

> Accurate prediction of pedestrian trajectories is essential for applications in robotics and surveillance systems. While existing approaches primarily focus on social interactions between pedestrians, they often overlook the rich environmental context that significantly shapes human movement patterns. In this paper, we propose SceneAware, a novel framework that explicitly incorporates scene understanding to enhance trajectory prediction accuracy. Our method leverages a Vision Transformer~(ViT) scene encoder to process environmental context from static scene images, while Multi-modal Large Language Models~(MLLMs) generate binary walkability masks that distinguish between accessible and restricted areas during training. We combine a Transformer-based trajectory encoder with the ViT-based scene encoder, capturing both temporal dynamics and spatial constraints. The framework integrates collision penalty mechanisms that discourage predicted trajectories from violating physical boundaries, ensuring physically plausible predictions. SceneAware is implemented in both deterministic and stochastic variants. Comprehensive experiments on the ETH/UCY benchmark datasets show that our approach outperforms state-of-the-art methods, with more than 50\% improvement over previous models. Our analysis based on different trajectory categories shows that the model performs consistently well across various types of pedestrian movement. This highlights the importance of using explicit scene information and shows that our scene-aware approach is both effective and reliable in generating accurate and physically plausible predictions. Code is available at: https://github.com/juho127/SceneAware.

[Arxiv](https://arxiv.org/abs/2506.14144)