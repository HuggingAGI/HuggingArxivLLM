# CrystalFormer-RL：面向材料设计的强化微调方法

发布时间：2025年04月03日

`LLM应用` `材料科学` `机器学习`

> CrystalFormer-RL: Reinforcement Fine-Tuning for Materials Design

# 摘要

> 强化微调显著提升了大型语言模型的指令遵循和推理能力。本研究将强化微调应用于基于自回归变压器的材料生成模型 CrystalFormer（arXiv:2403.15734），结合分子间势能和性质预测模型等判别式机器学习模型进行实验。通过优化奖励信号（如凸包上的能量和材料性能指标），强化微调成功将判别模型的知识融入生成模型。优化后的 CrystalFormer-RL 模型在生成晶体的稳定性方面表现出色，并成功发现同时具备显著介电常数和带隙等理想但相互矛盾材料特性的晶体。值得注意的是，强化微调不仅提升了生成预训练模型在性质引导下的新型材料设计能力，还解锁了从无监督预训练数据集中基于性质驱动的材料检索功能。利用判别模型提供的奖励信号来微调材料生成模型，为机器学习生态系统在材料科学中的协同作用开启了一个令人兴奋的新方向。

> Reinforcement fine-tuning has instrumental enhanced the instruction-following and reasoning abilities of large language models. In this work, we explore the applications of reinforcement fine-tuning to the autoregressive transformer-based materials generative model CrystalFormer (arXiv:2403.15734) using discriminative machine learning models such as interatomic potentials and property prediction models. By optimizing reward signals-such as energy above the convex hull and material property figures of merit-reinforcement fine-tuning infuses knowledge from discriminative models into generative models. The resulting model, CrystalFormer-RL, shows enhanced stability in generated crystals and successfully discovers crystals with desirable yet conflicting material properties, such as substantial dielectric constant and band gap simultaneously. Notably, we observe that reinforcement fine-tuning enables not only the property-guided novel material design ability of generative pre-trained model but also unlocks property-driven material retrieval from the unsupervised pre-training dataset. Leveraging rewards from discriminative models to fine-tune materials generative models opens an exciting gateway to the synergies of the machine learning ecosystem for materials.

[Arxiv](https://arxiv.org/abs/2504.02367)