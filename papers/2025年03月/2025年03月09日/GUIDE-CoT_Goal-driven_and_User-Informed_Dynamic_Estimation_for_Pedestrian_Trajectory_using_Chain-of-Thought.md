# # GUIDE-CoT：目标驱动、用户导向的行人轨迹动态估计方法，采用思维链推理技术。

发布时间：2025年03月09日

`LLM应用` `计算机视觉` `人工智能`

> GUIDE-CoT: Goal-driven and User-Informed Dynamic Estimation for Pedestrian Trajectory using Chain-of-Thought

# 摘要

> 尽管大型语言模型（LLMs）在推理任务中表现出了令人瞩目的成果，但将其应用于行人轨迹预测仍面临两大关键挑战：视觉信息的利用不足以及完整轨迹预测的难度。为了解决这些问题，我们提出了基于思维链（CoT）的目标驱动用户知情动态估计方法（GUIDE-CoT）。我们的方法整合了两个创新模块：(1) 目标导向的视觉提示，通过结合视觉提示与预训练的视觉编码器，提升目标预测的准确性；(2) 基于思维链（CoT）的大语言模型用于轨迹生成，能够生成趋向预测目标的现实轨迹。此外，我们的方法引入了可控的轨迹生成机制，允许对预测路径进行灵活且用户导向的修改。在ETH/UCY基准数据集上的广泛实验表明，我们的方法实现了最先进的性能，在行人轨迹预测中既达到了高精度，又展现了更强的适应性。我们的代码已公开，可在https://github.com/ai-kmu/GUIDE-CoT获取。

> While Large Language Models (LLMs) have recently shown impressive results in reasoning tasks, their application to pedestrian trajectory prediction remains challenging due to two key limitations: insufficient use of visual information and the difficulty of predicting entire trajectories. To address these challenges, we propose Goal-driven and User-Informed Dynamic Estimation for pedestrian trajectory using Chain-of-Thought (GUIDE-CoT). Our approach integrates two innovative modules: (1) a goal-oriented visual prompt, which enhances goal prediction accuracy combining visual prompts with a pretrained visual encoder, and (2) a chain-of-thought (CoT) LLM for trajectory generation, which generates realistic trajectories toward the predicted goal. Moreover, our method introduces controllable trajectory generation, allowing for flexible and user-guided modifications to the predicted paths. Through extensive experiments on the ETH/UCY benchmark datasets, our method achieves state-of-the-art performance, delivering both high accuracy and greater adaptability in pedestrian trajectory prediction. Our code is publicly available at https://github.com/ai-kmu/GUIDE-CoT.

[Arxiv](https://arxiv.org/abs/2503.06832)