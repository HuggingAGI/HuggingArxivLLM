# 利用排斥视觉提示调优来抵御多模态后门模型

发布时间：2024年12月29日

`LLM应用` `计算机安全` `多模态学习`

> Defending Multimodal Backdoored Models by Repulsive Visual Prompt Tuning

# 摘要

> 多模态对比学习模型（比如 CLIP）能从大规模图像 - 文本数据集中习得高质量的表征，然而它们面对后门攻击时存在明显的脆弱性，引发了严重的安全忧虑。在本文中，我们指出 CLIP 的脆弱性主要源自其对与类别无关特征的过度编码，这会削弱模型对输入干扰的视觉特征抵抗力，使其更易捕捉到后门攻击插入的触发模式。受此发现启发，我们提出了排斥视觉提示调整（RVPT）这一全新的防御手段，它采用专门设计的深度视觉提示调整和特征排斥损失来消除过多的与类别无关的特征，同时优化交叉熵损失以维持纯净准确性。和通常需要有毒数据可用或对整个模型进行微调的现有多模态后门防御方法不同，RVPT 借助少量的下游纯净样本，且只调整少量参数。实证结果显示，相较于 CLIP，RVPT 仅调整 0.27％的参数，却显著优于最先进的基线，将针对 SoTA 攻击的攻击成功率从 67.53％降至 2.76％，并在多个数据集上有效地展现出其防御能力。

> Multimodal contrastive learning models (e.g., CLIP) can learn high-quality representations from large-scale image-text datasets, yet they exhibit significant vulnerabilities to backdoor attacks, raising serious safety concerns. In this paper, we disclose that CLIP's vulnerabilities primarily stem from its excessive encoding of class-irrelevant features, which can compromise the model's visual feature resistivity to input perturbations, making it more susceptible to capturing the trigger patterns inserted by backdoor attacks. Inspired by this finding, we propose Repulsive Visual Prompt Tuning (RVPT), a novel defense approach that employs specially designed deep visual prompt tuning and feature-repelling loss to eliminate excessive class-irrelevant features while simultaneously optimizing cross-entropy loss to maintain clean accuracy. Unlike existing multimodal backdoor defense methods that typically require the availability of poisoned data or involve fine-tuning the entire model, RVPT leverages few-shot downstream clean samples and only tunes a small number of parameters. Empirical results demonstrate that RVPT tunes only 0.27\% of the parameters relative to CLIP, yet it significantly outperforms state-of-the-art baselines, reducing the attack success rate from 67.53\% to 2.76\% against SoTA attacks and effectively generalizing its defensive capabilities across multiple datasets.

[Arxiv](https://arxiv.org/abs/2412.20392)