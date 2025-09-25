# 超越动作标注数据的通用机器人操控

发布时间：2025年09月24日

`Agent` `工业与制造`

> Generalist Robot Manipulation beyond Action Labeled Data

# 摘要

> 通用机器人操作的最新进展借助预训练视觉语言模型（VLMs）和大规模机器人演示数据，实现了对各类任务的零样本处理。但目前仍面临一大挑战：现有方法为确保鲁棒性与泛化能力，需依赖高质量、带动作标签的机器人演示数据，而这类数据的规模化获取难度较大。为此，我们提出一种新方法，无需动作标签即可从包含人类和/或机器人动作的视频中学习，不仅能提升开放词汇性能，还能实现新任务的数据高效学习。该方法会在手部或夹具位置提取密集的动态3D点云，并通过我们提出的3D动力学预测器进行自监督学习。随后，利用较小规模的带标签数据集对该预测器进行微调，将其转化为动作预测器，从而实现动作对齐。

> Recent advances in generalist robot manipulation leverage pre-trained Vision-Language Models (VLMs) and large-scale robot demonstrations to tackle diverse tasks in a zero-shot manner. A key challenge remains: scaling high-quality, action-labeled robot demonstration data, which existing methods rely on for robustness and generalization. To address this, we propose a method that benefits from videos without action labels - featuring humans and/or robots in action - enhancing open-vocabulary performance and enabling data-efficient learning of new tasks. Our method extracts dense, dynamic 3D point clouds at the hand or gripper location and uses a proposed 3D dynamics predictor for self-supervision. This predictor is then tuned to an action predictor using a smaller labeled dataset for action alignment. We show that our method not only learns from unlabeled human and robot demonstrations - improving downstream generalist robot policies - but also enables robots to learn new tasks without action labels (i.e., out-of-action generalization) in both real-world and simulated settings.

[Arxiv](https://arxiv.org/abs/2509.19958)