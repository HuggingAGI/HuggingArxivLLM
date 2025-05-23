# MixAT：融合连续与离散对抗训练，赋能大语言模型

发布时间：2025年05月22日

`LLM理论` `对抗训练`

> MixAT: Combining Continuous and Discrete Adversarial Training for LLMs

# 摘要

> 尽管最近在LLMs安全与对齐方面的努力取得了进展，前沿LLMs依然面临着一致性的有害生成问题。虽然对抗训练在提升传统机器学习模型的鲁棒性方面已被广泛研究并取得了显著成效，但其在LLMs场景下的优缺点仍不明确。具体而言，尽管现有的离散对抗攻击能够有效生成有害内容，但使用具体的对抗提示对LLMs进行训练通常计算成本高昂，这导致了对连续松弛方法的依赖。然而，这些松弛方法并不对应于离散输入令牌，因此这些潜在的训练方法往往使模型容易受到多种离散攻击的侵害。本研究旨在通过引入MixAT填补这一空白，这是一种在训练过程中结合更强离散攻击和更快连续攻击的新型方法。我们对MixAT进行了全面的评估，涵盖了各种最先进的攻击手段，并提出了“至少一次攻击成功率”（ALO-ASR）这一指标，以衡量模型在最坏情况下的脆弱性。实验结果表明，与先前的防御方法相比，MixAT在保持与基于连续松弛方法相当的运行时间的同时，实现了显著更好的鲁棒性（ALO-ASR < 20% vs. >50%）。我们进一步在实际部署场景中分析了MixAT，探讨了聊天模板、量化、低秩适配器和温度等因素对对抗训练和评估的影响，揭示了当前方法论中的一些盲点。我们的研究结果表明，MixAT的离散-连续防御方法提供了一种原理性更强且优越的鲁棒性-准确性权衡，且计算开销极低，这凸显了其在构建更安全LLMs方面的巨大潜力。我们已在https://github.com/insait-institute/MixAT公开了代码和模型。

> Despite recent efforts in Large Language Models (LLMs) safety and alignment, current adversarial attacks on frontier LLMs are still able to force harmful generations consistently. Although adversarial training has been widely studied and shown to significantly improve the robustness of traditional machine learning models, its strengths and weaknesses in the context of LLMs are less understood. Specifically, while existing discrete adversarial attacks are effective at producing harmful content, training LLMs with concrete adversarial prompts is often computationally expensive, leading to reliance on continuous relaxations. As these relaxations do not correspond to discrete input tokens, such latent training methods often leave models vulnerable to a diverse set of discrete attacks. In this work, we aim to bridge this gap by introducing MixAT, a novel method that combines stronger discrete and faster continuous attacks during training. We rigorously evaluate MixAT across a wide spectrum of state-of-the-art attacks, proposing the At Least One Attack Success Rate (ALO-ASR) metric to capture the worst-case vulnerability of models. We show MixAT achieves substantially better robustness (ALO-ASR < 20%) compared to prior defenses (ALO-ASR > 50%), while maintaining a runtime comparable to methods based on continuous relaxations. We further analyze MixAT in realistic deployment settings, exploring how chat templates, quantization, low-rank adapters, and temperature affect both adversarial training and evaluation, revealing additional blind spots in current methodologies. Our results demonstrate that MixAT's discrete-continuous defense offers a principled and superior robustness-accuracy tradeoff with minimal computational overhead, highlighting its promise for building safer LLMs. We provide our code and models at https://github.com/insait-institute/MixAT.

[Arxiv](https://arxiv.org/abs/2505.16947)