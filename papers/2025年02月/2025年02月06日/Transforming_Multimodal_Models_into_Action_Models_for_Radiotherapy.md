# 打造放射治疗的行动模型：多模态模型的转化与应用

发布时间：2025年02月06日

`LLM应用

论文摘要讨论了将大型多模态基础模型（MLM）应用于放射治疗计划的创新框架，利用强化学习和小样本学习提升模型能力，优化治疗方案。这属于将大型模型应用于具体领域，因此归类为LLM应用。` `放射治疗`

> Transforming Multimodal Models into Action Models for Radiotherapy

# 摘要

> 放射治疗是癌症治疗中的重要手段，其核心在于精确规划以实现肿瘤消融与健康组织保护的平衡。传统治疗计划（TP）是一个耗时且依赖人工经验的迭代过程，这可能导致效率低下和结果偏差。我们提出了一种创新框架，通过小样本强化学习（RL）方法将大型多模态基础模型（MLM）转化为TP的动作模型。本方法充分利用MLM在物理学、辐射学和解剖学领域的广泛知识储备，并通过小样本学习过程进一步提升其能力，使其能够借助蒙特卡罗模拟器不断优化治疗方案。实验结果表明，与传统基于RL的方法相比，本方法在治疗计划质量和效率上均有显著提升。在前列腺癌数据的模拟测试中，模型不仅获得更高的奖励分数，还实现了更优的剂量分布。这一概念验证为将高级AI模型融入临床工作流程提供了令人鼓舞的方向，未来有望显著提升放射治疗计划的速度、精确性和标准化水平。

> Radiotherapy is a crucial cancer treatment that demands precise planning to balance tumor eradication and preservation of healthy tissue. Traditional treatment planning (TP) is iterative, time-consuming, and reliant on human expertise, which can potentially introduce variability and inefficiency. We propose a novel framework to transform a large multimodal foundation model (MLM) into an action model for TP using a few-shot reinforcement learning (RL) approach. Our method leverages the MLM's extensive pre-existing knowledge of physics, radiation, and anatomy, enhancing it through a few-shot learning process. This allows the model to iteratively improve treatment plans using a Monte Carlo simulator. Our results demonstrate that this method outperforms conventional RL-based approaches in both quality and efficiency, achieving higher reward scores and more optimal dose distributions in simulations on prostate cancer data. This proof-of-concept suggests a promising direction for integrating advanced AI models into clinical workflows, potentially enhancing the speed, quality, and standardization of radiotherapy treatment planning.

[Arxiv](https://arxiv.org/abs/2502.04408)