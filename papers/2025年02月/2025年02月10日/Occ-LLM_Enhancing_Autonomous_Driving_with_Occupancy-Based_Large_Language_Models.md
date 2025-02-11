# Occ-LLM: 基于占用的大型语言模型助力自动驾驶能力提升

发布时间：2025年02月10日

`LLM应用` `机器人` `自动驾驶`

> Occ-LLM: Enhancing Autonomous Driving with Occupancy-Based Large Language Models

# 摘要

> 大型语言模型（LLMs）在机器人和自动驾驶领域取得了显著进展。本研究首次提出了一种基于占用的大型语言模型（Occ-LLM），标志着LLMs与关键表示方法的开创性结合。为了有效编码占用信息作为LLM的输入并解决与占用相关的类别不平衡问题，我们提出了运动分离变分自编码器（MS-VAE）。这一创新方法利用先验知识在输入变分自编码器（VAE）之前区分动态物体和静态场景。这种分离增强了模型专注于动态轨迹的能力，同时有效重建静态场景。Occ-LLM在关键任务中的有效性得到了验证，包括4D占用预测、自我-ego规划和基于占用的场景问答。全面评估表明，Occ-LLM显著超越现有最先进的方法，在4D占用预测任务中，交并比（IoU）提升了约【数学公式】6%，平均交并比（mIoU）提升了【数学公式】4%。这些发现凸显了Occ-LLM在重塑机器人和自动驾驶领域现有范式的变革潜力。

> Large Language Models (LLMs) have made substantial advancements in the field of robotic and autonomous driving. This study presents the first Occupancy-based Large Language Model (Occ-LLM), which represents a pioneering effort to integrate LLMs with an important representation. To effectively encode occupancy as input for the LLM and address the category imbalances associated with occupancy, we propose Motion Separation Variational Autoencoder (MS-VAE). This innovative approach utilizes prior knowledge to distinguish dynamic objects from static scenes before inputting them into a tailored Variational Autoencoder (VAE). This separation enhances the model's capacity to concentrate on dynamic trajectories while effectively reconstructing static scenes. The efficacy of Occ-LLM has been validated across key tasks, including 4D occupancy forecasting, self-ego planning, and occupancy-based scene question answering. Comprehensive evaluations demonstrate that Occ-LLM significantly surpasses existing state-of-the-art methodologies, achieving gains of about 6\% in Intersection over Union (IoU) and 4\% in mean Intersection over Union (mIoU) for the task of 4D occupancy forecasting. These findings highlight the transformative potential of Occ-LLM in reshaping current paradigms within robotic and autonomous driving.

[Arxiv](https://arxiv.org/abs/2502.06419)