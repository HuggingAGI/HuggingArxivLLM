# 精细建模手-物互动动态，助力第一人称视频表征学习

发布时间：2025年03月02日

`LLM应用` `计算机视觉` `机器人`

> Modeling Fine-Grained Hand-Object Dynamics for Egocentric Video Representation Learning

# 摘要

> 自我中心视频理解中，手部与物体的运动及其互动天然扮演着关键角色。然而，现有方法多聚焦于视频表征与高层叙述的对齐，忽视了手物间复杂动态关系的建模。本研究致力于将精细的手物动态建模融入视频表征学习。针对数据缺口，我们提出了HOD管道，结合手物检测器与大型语言模型，生成详尽描述手物动态的高质量叙述。为捕捉这些精细动态，我们开发了EgoVideo模型，配备新型轻量级运动适配器，专为精细手物运动信息设计。借助协同训练策略，EgoVideo有效挖掘HOD数据中的手物动态价值。实验结果表明，我们的方法在多个自我中心任务中达到新高度：零样本设置下，EK-100多实例检索提升6.3%，EK-100分类提升5.7%，EGTEA分类提升16.3%。同时，模型在手物互动与机器人操作任务中展现出强大的泛化能力。代码与数据已开源，访问https://github.com/OpenRobotLab/EgoHOD/即可获取。

> In egocentric video understanding, the motion of hands and objects as well as their interactions play a significant role by nature. However, existing egocentric video representation learning methods mainly focus on aligning video representation with high-level narrations, overlooking the intricate dynamics between hands and objects. In this work, we aim to integrate the modeling of fine-grained hand-object dynamics into the video representation learning process. Since no suitable data is available, we introduce HOD, a novel pipeline employing a hand-object detector and a large language model to generate high-quality narrations with detailed descriptions of hand-object dynamics. To learn these fine-grained dynamics, we propose EgoVideo, a model with a new lightweight motion adapter to capture fine-grained hand-object motion information. Through our co-training strategy, EgoVideo effectively and efficiently leverages the fine-grained hand-object dynamics in the HOD data. Extensive experiments demonstrate that our method achieves state-of-the-art performance across multiple egocentric downstream tasks, including improvements of 6.3% in EK-100 multi-instance retrieval, 5.7% in EK-100 classification, and 16.3% in EGTEA classification in zero-shot settings. Furthermore, our model exhibits robust generalization capabilities in hand-object interaction and robot manipulation tasks. Code and data are available at https://github.com/OpenRobotLab/EgoHOD/.

[Arxiv](https://arxiv.org/abs/2503.00986)