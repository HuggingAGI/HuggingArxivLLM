# 对抗引导扩散的多模态大语言模型攻击

发布时间：2025年07月30日

`LLM应用

摘要讨论了利用扩散模型生成对抗图像以欺骗多模态大语言模型（MLLMs）生成特定响应的方法。这属于LLM应用，因为它探讨了对抗攻击在实际应用中的效果和防御鲁棒性。` `人工智能`

> Adversarial-Guided Diffusion for Multimodal LLM Attacks

# 摘要

> 本文提出了一种利用扩散模型生成对抗图像以欺骗多模态大语言模型（MLLMs）生成特定响应的方法，同时保持图像质量不受显著影响。我们设计了一种对抗引导扩散（AGD）方法，通过引入对抗引导噪声确保攻击的有效性。与传统对抗攻击直接在图像中添加高频扰动不同，AGD将目标语义注入到反向扩散过程中的噪声组件。由于扩散模型的噪声覆盖了整个频率范围，嵌入其中的对抗信号也具备全频谱特性。在反向扩散过程中，对抗图像由干净图像和噪声的线性组合构成。因此，当应用如低通滤波等防御措施时，噪声组件中的对抗信号不会局限于高频带，从而更难被抑制。这使得AGD具有天然的防御鲁棒性。实验结果表明，我们的AGD在攻击效果和模型对某些防御的鲁棒性方面均超越了现有最优方法。

> This paper addresses the challenge of generating adversarial image using a diffusion model to deceive multimodal large language models (MLLMs) into generating the targeted responses, while avoiding significant distortion of the clean image. To address the above challenges, we propose an adversarial-guided diffusion (AGD) approach for adversarial attack MLLMs. We introduce adversarial-guided noise to ensure attack efficacy. A key observation in our design is that, unlike most traditional adversarial attacks which embed high-frequency perturbations directly into the clean image, AGD injects target semantics into the noise component of the reverse diffusion. Since the added noise in a diffusion model spans the entire frequency spectrum, the adversarial signal embedded within it also inherits this full-spectrum property. Importantly, during reverse diffusion, the adversarial image is formed as a linear combination of the clean image and the noise. Thus, when applying defenses such as a simple low-pass filtering, which act independently on each component, the adversarial image within the noise component is less likely to be suppressed, as it is not confined to the high-frequency band. This makes AGD inherently robust to variety defenses. Extensive experiments demonstrate that our AGD outperforms state-of-the-art methods in attack performance as well as in model robustness to some defenses.

[Arxiv](https://arxiv.org/abs/2507.23202)