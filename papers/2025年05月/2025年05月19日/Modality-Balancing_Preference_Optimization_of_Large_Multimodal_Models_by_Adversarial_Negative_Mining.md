# 模态平衡偏好优化：对抗负样本挖掘在大规模多模态模型中的应用

发布时间：2025年05月19日

`LLM应用` `人工智能` `多模态`

> Modality-Balancing Preference Optimization of Large Multimodal Models by Adversarial Negative Mining

# 摘要

> 大型多模态模型（LMMs）的任务适应和对齐在指令微调的推动下取得了显著进展，而最近的偏好优化进一步增强了这一能力。然而，大多数LMMs在推理过程中仍然面临严重的模态失衡问题，即过度依赖语言先验偏见而忽视视觉输入，这限制了它们在下游任务中的泛化能力并导致幻觉现象。现有的LMMs偏好优化方法并未关注在训练数据整理过程中限制其大型语言模型（LLM）主干的内部偏见。此外，它们严重依赖离线数据，缺乏在训练过程中探索适应动态分布变化的多样化响应的能力。与此同时，最近使用在线生成数据和经过验证的奖励来提升推理能力的组相对策略优化（GRPO）方法，在LMM对齐中的应用仍鲜有探索。

本文中，我们提出了一种新颖的偏好学习框架——模态平衡偏好优化（MBPO），以解决LMMs中的模态失衡问题。MBPO通过对抗性扰动输入图像生成困难负样本，即由于视觉信息使用有限而被LLM偏见误导的被拒绝响应，从而构建一个更有效的离线偏好数据集。此外，MBPO利用闭合任务易于验证的特性，生成具有经过验证奖励的在线响应。随后，采用GRPO对模型进行离线-在线混合数据训练。大量实验表明，MBPO可以提升LMM在具有挑战性的视觉-语言任务中的性能，并有效减少幻觉现象。

> The task adaptation and alignment of Large Multimodal Models (LMMs) have been significantly advanced by instruction tuning and further strengthened by recent preference optimization. Yet, most LMMs still suffer from severe modality imbalance during reasoning, i.e., outweighing language prior biases over visual inputs, which bottlenecks their generalization to downstream tasks and causes hallucinations. However, existing preference optimization approaches for LMMs do not focus on restraining the internal biases of their Large Language Model (LLM) backbones when curating the training data. Moreover, they heavily rely on offline data and lack the capacity to explore diverse responses adaptive to dynamic distributional shifts during training. Meanwhile, Group Relative Policy Optimization (GRPO), a recent method using online-generated data and verified rewards to improve reasoning capabilities, remains largely underexplored in LMM alignment. In this paper, we propose a novel preference learning framework, Modality-Balancing Preference Optimization (MBPO), to address the modality imbalance in LMMs. MBPO constructs a more effective offline preference dataset by generating hard negatives, i.e., rejected responses misled by LLM biases due to limited usage of visual information, through adversarial perturbation of input images. Moreover, MBPO leverages the easy-to-verify nature of close-ended tasks to generate online responses with verified rewards. GRPO is then employed to train the model with offline-online hybrid data. Extensive experiments demonstrate that MBPO can enhance LMM performance on challenging vision-language tasks and effectively reduce hallucinations.

[Arxiv](https://arxiv.org/abs/2506.08022)