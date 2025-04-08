# SDEIT：基于语义的电阻抗成像技术

发布时间：2025年04月05日

`其他` `医学成像` `生成模型`

> SDEIT: Semantic-Driven Electrical Impedance Tomography

# 摘要

> 在解决电阻抗层析成像（EIT）等不适定反问题时，基于先验知识的正则化方法至关重要。然而，由于解剖结构的复杂性和可变性，设计有效的正则化方法并将其整合到EIT中仍具挑战性。本文提出了一种名为SDEIT的新型语义驱动框架，首次将Stable Diffusion 3.5引入EIT领域。通过使用自然语言提示作为语义先验，SDEIT能够更智能地引导图像重建过程。该框架结合了隐式神经表示（INR）网络和一种即插即用的优化方案，利用SD生成的图像作为生成先验，从而显著提升了图像的结构一致性和细节恢复能力。值得注意的是，SDEIT无需依赖配对的训练数据集，大大增强了其在不同EIT场景中的适用性。通过在模拟和实验数据上的大量实验，我们证明了SDEIT在准确性和鲁棒性方面均优于现有最先进的技术。这项研究为将多模态先验整合到如EIT等不适定反问题开辟了全新路径。

> Regularization methods using prior knowledge are essential in solving ill-posed inverse problems such as Electrical Impedance Tomography (EIT). However, designing effective regularization and integrating prior information into EIT remains challenging due to the complexity and variability of anatomical structures. In this work, we introduce SDEIT, a novel semantic-driven framework that integrates Stable Diffusion 3.5 into EIT, marking the first use of large-scale text-to-image generation models in EIT. SDEIT employs natural language prompts as semantic priors to guide the reconstruction process. By coupling an implicit neural representation (INR) network with a plug-and-play optimization scheme that leverages SD-generated images as generative priors, SDEIT improves structural consistency and recovers fine details. Importantly, this method does not rely on paired training datasets, increasing its adaptability to varied EIT scenarios. Extensive experiments on both simulated and experimental data demonstrate that SDEIT outperforms state-of-the-art techniques, offering superior accuracy and robustness. This work opens a new pathway for integrating multimodal priors into ill-posed inverse problems like EIT.

[Arxiv](https://arxiv.org/abs/2504.04185)