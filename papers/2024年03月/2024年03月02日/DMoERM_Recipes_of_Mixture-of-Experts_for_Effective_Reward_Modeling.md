# DMoERM：揭秘混合专家模型在高效奖励建模中的秘籍

发布时间：2024年03月02日

`LLM应用`

> DMoERM: Recipes of Mixture-of-Experts for Effective Reward Modeling

# 摘要

> 在提升大型语言模型（LLM）对齐微调效能的过程中，奖励模型（RM）的表现起着决定性作用。然而，在训练RM时，有两个棘手的问题亟待解决：一方面，利用多种类型数据训练同一个RM可能导致其在处理多任务时出现泛化性能下降；另一方面，人工标注的一致性仅维持在60%至75%，使得训练数据饱含噪音。为应对这两项挑战，我们创新性地将“混合专家”(MoE)架构首次引入RM领域，设计出双层MoE奖励模型（DMoERM）。外层MoE作为稀疏模型，负责将输入按任务类别划分并引导至对应的内层任务特化模型；内层MoE则是一个密集模型，它将特定任务拆解为多个能力维度，并运用LoRA专家逐一精调各个维度。各维度专家的输出经由MLP融合计算得出最终奖励值。为了节约成本，我们采用公开LLM API获取能力偏好标签信息。经过手动标注数据集的验证，证实了我们的模型能够实现与人类偏好更优的一致性，并在众多先进生成方法中脱颖而出。此外，结合BoN抽样及强化学习实验，进一步揭示了我们的模型不仅超越了现有的RM顶尖集成方法，还有效减轻了过优化现象。项目代码与数据集已开源，访问地址为：https://github.com/quanshr/DMoERM-v1。

> The performance of the reward model (RM) is a critical factor in improving the effectiveness of the large language model (LLM) during alignment fine-tuning. There remain two challenges in RM training: 1) training the same RM using various categories of data may cause its generalization performance to suffer from multi-task disturbance, and 2) the human annotation consistency rate is generally only $60\%$ to $75\%$, causing training data to contain a lot of noise. To tackle these two challenges, we introduced the idea of Mixture-of-Experts (MoE) into the field of RM for the first time. We propose the Double-Layer MoE RM (DMoERM). The outer layer MoE is a sparse model. After classifying an input into task categories, we route it to the corresponding inner layer task-specific model. The inner layer MoE is a dense model. We decompose the specific task into multiple capability dimensions and individually fine-tune a LoRA expert on each one. Their outputs are then synthesized by an MLP to compute the final rewards. To minimize costs, we call a public LLM API to obtain the capability preference labels. The validation on manually labeled datasets confirms that our model attains superior consistency with human preference and outstrips advanced generative approaches. Meanwhile, through BoN sampling and RL experiments, we demonstrate that our model outperforms state-of-the-art ensemble methods of RM and mitigates the overoptimization problem. Our code and dataset are available at: https://github.com/quanshr/DMoERM-v1.

[Arxiv](https://arxiv.org/abs/2403.01197)