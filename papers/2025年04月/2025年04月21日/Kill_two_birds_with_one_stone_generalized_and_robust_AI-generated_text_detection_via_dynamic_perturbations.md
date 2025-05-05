# 一石二鸟：借助动态扰动实现通用且稳健的AI生成文本检测方法

发布时间：2025年04月21日

`LLM应用` `人工智能` `文本检测`

> Kill two birds with one stone: generalized and robust AI-generated text detection via dynamic perturbations

# 摘要

> 随着大型语言模型的普及，AI生成文本（AIGT）可能被滥用的风险引发了广泛关注。因此，开发一种兼具高泛化性和鲁棒性的优秀AIGT检测方法变得尤为重要。然而，现有方法往往侧重于模型泛化能力或鲁棒性，难以兼顾。本文提出，鲁棒性可被视为领域迁移的一种特定形式，并揭示了AIGT检测任务中模型泛化的内在机制。基于此，我们提出了一种新颖的AIGT检测方法（DP-Net），该方法通过引入强化学习中的精心设计的奖励和动作，利用动态扰动生成。实验结果表明，在三个跨领域场景下，DP-Net在泛化能力上显著优于现有AIGT检测方法。同时，DP-Net在两种文本对抗攻击中也展现了最佳的鲁棒性。代码已在https://github.com/CAU-ISS-Lab/AIGT-Detection-Evade-Detection/tree/main/DP-Net公开发布。

> The growing popularity of large language models has raised concerns regarding the potential to misuse AI-generated text (AIGT). It becomes increasingly critical to establish an excellent AIGT detection method with high generalization and robustness. However, existing methods either focus on model generalization or concentrate on robustness. The unified mechanism, to simultaneously address the challenges of generalization and robustness, is less explored. In this paper, we argue that robustness can be view as a specific form of domain shift, and empirically reveal an intrinsic mechanism for model generalization of AIGT detection task. Then, we proposed a novel AIGT detection method (DP-Net) via dynamic perturbations introduced by a reinforcement learning with elaborated reward and action. Experimentally, extensive results show that the proposed DP-Net significantly outperforms some state-of-the-art AIGT detection methods for generalization capacity in three cross-domain scenarios. Meanwhile, the DP-Net achieves best robustness under two text adversarial attacks. The code is publicly available at https://github.com/CAU-ISS-Lab/AIGT-Detection-Evade-Detection/tree/main/DP-Net.

[Arxiv](https://arxiv.org/abs/2504.21019)