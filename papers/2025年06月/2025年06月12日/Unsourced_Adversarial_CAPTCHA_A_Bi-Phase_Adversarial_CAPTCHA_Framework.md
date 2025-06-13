# 无源式对抗CAPTCHA：一种双阶段对抗式CAPTCHA框架

发布时间：2025年06月12日

`LLM应用` `网络安全` `人工智能`

> Unsourced Adversarial CAPTCHA: A Bi-Phase Adversarial CAPTCHA Framework

# 摘要

> 随着深度学习的迅猛发展，传统的 CAPTCHA 正面临深度神经网络 (DNN) 驱动的自动化攻击的严峻挑战。现有的对抗攻击方法往往依赖于原始图像特征，导致图像失真，既影响了人类的识别，也限制了其在缺乏初始图像场景中的应用。为应对这些挑战，我们提出了一种全新的无源对抗 CAPTCHA (UAC) 框架，它能够根据攻击者指定的文本提示生成高保真对抗样本。借助大型语言模型 (LLM)，UAC 不仅提升了 CAPTCHA 的多样性，还支持目标攻击和非目标攻击。针对目标攻击，我们采用 EDICT 方法，通过优化扩散模型中的双重潜在变量，显著提升了生成图像的质量。在非目标攻击，尤其是黑盒场景下，我们提出了双路径无源对抗 CAPTCHA (BP-UAC)，这是一种结合多模态梯度和双路径优化的两步优化策略，能够高效实现误分类。实验结果表明，BP-UAC 在多种系统中实现了极高的攻击成功率，生成的自然 CAPTCHA 几乎无法被人类和 DNN 区分。

> With the rapid advancements in deep learning, traditional CAPTCHA schemes are increasingly vulnerable to automated attacks powered by deep neural networks (DNNs). Existing adversarial attack methods often rely on original image characteristics, resulting in distortions that hinder human interpretation and limit applicability in scenarios lacking initial input images. To address these challenges, we propose the Unsourced Adversarial CAPTCHA (UAC), a novel framework generating high-fidelity adversarial examples guided by attacker-specified text prompts. Leveraging a Large Language Model (LLM), UAC enhances CAPTCHA diversity and supports both targeted and untargeted attacks. For targeted attacks, the EDICT method optimizes dual latent variables in a diffusion model for superior image quality. In untargeted attacks, especially for black-box scenarios, we introduce bi-path unsourced adversarial CAPTCHA (BP-UAC), a two-step optimization strategy employing multimodal gradients and bi-path optimization for efficient misclassification. Experiments show BP-UAC achieves high attack success rates across diverse systems, generating natural CAPTCHAs indistinguishable to humans and DNNs.

[Arxiv](https://arxiv.org/abs/2506.10685)