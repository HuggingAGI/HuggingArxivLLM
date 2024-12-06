# 分子动力学轨迹的生成式建模

发布时间：2024年09月26日

`其他` `分子动力学` `蛋白质设计`

> Generative Modeling of Molecular Dynamics Trajectories

# 摘要

> 摘要：分子动力学（MD）是研究微观现象的有力手段，但其高昂的计算成本使得基于深度学习的替代模型的开发备受关注。我们引入分子轨迹的生成式建模，作为从数据中学习灵活的多任务 MD 替代模型的范例。通过对轨迹中恰当选取的帧进行条件设定，此类生成模型能够适应诸如正向模拟、过渡路径采样和轨迹上采样等多样任务。通过交替对分子系统的部分进行条件设定并补全其余部分，我们还迈出了动力学条件分子设计的第一步。我们在四肽模拟中验证了这一系列能力，表明我们的模型能够生成合理的蛋白质单体集合。总之，我们的工作展示了生成式建模如何从 MD 数据中挖掘价值，以应对现有方法甚至 MD 本身难以直接处理的各类下游任务。代码可在该 https URL 获取。

> 
Abstract:Molecular dynamics (MD) is a powerful technique for studying microscopic phenomena, but its computational cost has driven significant interest in the development of deep learning-based surrogate models. We introduce generative modeling of molecular trajectories as a paradigm for learning flexible multi-task surrogate models of MD from data. By conditioning on appropriately chosen frames of the trajectory, we show such generative models can be adapted to diverse tasks such as forward simulation, transition path sampling, and trajectory upsampling. By alternatively conditioning on part of the molecular system and inpainting the rest, we also demonstrate the first steps towards dynamics-conditioned molecular design. We validate the full set of these capabilities on tetrapeptide simulations and show that our model can produce reasonable ensembles of protein monomers. Altogether, our work illustrates how generative modeling can unlock value from MD data towards diverse downstream tasks that are not straightforward to address with existing methods or even MD itself. Code is available at this https URL.
    

[Arxiv](https://arxiv.org/pdf/2409.17808)