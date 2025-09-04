# 面向PDE基础模型的推理：奖励模型驱动的推理时间缩放算法

发布时间：2025年09月02日

`LLM应用` `工业与制造`

> Towards Reasoning for PDE Foundation Models: A Reward-Model-Driven Inference-Time-Scaling Algorithm

# 摘要

> 偏微分方程（PDEs）是现代计算科学与工程的基石，但其计算成本极高。尽管PDE基础模型在模拟这类复杂时空现象时展现出巨大潜力，但现有模型仍受限于预训练数据集，在自回归展开性能上表现不佳，尤其是在分布外（OOD）场景中。此外，这些模型对计算资源和训练数据的要求极高，限制了它们在众多关键应用中的普及。受大型语言模型（LLMs）中“思考”策略最新进展的启发，我们首次提出了适用于PDE的测试时计算（TTC）策略——该策略在推理阶段利用计算资源，用更少的训练样本和更小的模型就能实现更精准的预测。我们通过两种奖励模型实现了这一目标，它们负责评估基于随机模型的预测结果的时空一致性。我们在PDEGym基准的可压缩欧拉方程模拟中验证了该方法，结果显示TTC相比标准非自适应自回归推理，预测精度得到显著提升。该TTC框架为更先进的推理算法和PDE建模奠定了基础，包括构建基于强化学习的方法，有望彻底改变物理与工程领域的计算工作流程。

> Partial Differential Equations (PDEs) are the bedrock for modern computational sciences and engineering, and inherently computationally expensive. While PDE foundation models have shown much promise for simulating such complex spatio-temporal phenomena, existing models remain constrained by the pretraining datasets and struggle with auto-regressive rollout performance, especially in out-of-distribution (OOD) cases. Furthermore, they have significant compute and training data requirements which hamper their use in many critical applications. Inspired by recent advances in ``thinking" strategies used in large language models (LLMs), we introduce the first test-time computing (TTC) strategy for PDEs that utilizes computational resources during inference to achieve more accurate predictions with fewer training samples and smaller models. We accomplish this with two types of reward models that evaluate predictions of a stochastic based model for spatio-temporal consistency. We demonstrate this method on compressible Euler-equation simulations from the PDEGym benchmark and show that TTC captures improved predictions relative to standard non-adaptive auto-regressive inference. This TTC framework marks a foundational step towards more advanced reasoning algorithms or PDE modeling, inluding building reinforcement-learning-based approaches, potentially transforming computational workflows in physics and engineering.

[Arxiv](https://arxiv.org/abs/2509.02846)