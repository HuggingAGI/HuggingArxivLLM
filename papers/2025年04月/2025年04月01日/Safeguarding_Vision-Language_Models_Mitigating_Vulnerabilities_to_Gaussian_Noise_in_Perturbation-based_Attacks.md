# # 保护视觉-语言模型：抵御基于扰动攻击中的高斯噪声漏洞

发布时间：2025年04月01日

`其他` `计算机视觉`

> Safeguarding Vision-Language Models: Mitigating Vulnerabilities to Gaussian Noise in Perturbation-based Attacks

# 摘要

> 视觉语言模型（VLMs）通过整合视觉信息扩展了大型语言模型（LLMs）的能力，然而它们仍然容易受到越狱攻击，尤其是在处理噪声或损坏的图像时。尽管现有的VLMs在训练过程中采取了安全措施以缓解此类攻击，但与噪声增强的视觉输入相关的漏洞却被忽视了。在本研究中，我们发现缺少噪声增强的训练会导致严重的安全漏洞：许多VLMs甚至对简单的扰动（如高斯噪声）都十分敏感。为了解决这一挑战，我们提出了Robust-VLGuard，这是一个包含对齐/错位图像-文本对的多模态安全数据集，并结合噪声增强微调，既降低了攻击成功率，又保留了VLM的功能性。对于更强大的基于优化的视觉扰动攻击，我们提出了DiffPure-VLM，利用扩散模型将对抗性扰动转换为类似高斯噪声的形式，这些噪声可以通过噪声增强安全微调的VLM进行防御。实验结果表明，扩散模型的分布转移特性与我们的微调VLMs非常契合，显著缓解了不同强度的对抗性扰动。数据集和代码可在https://github.com/JarvisUSTC/DiffPure-RobustVLM获取。

> Vision-Language Models (VLMs) extend the capabilities of Large Language Models (LLMs) by incorporating visual information, yet they remain vulnerable to jailbreak attacks, especially when processing noisy or corrupted images. Although existing VLMs adopt security measures during training to mitigate such attacks, vulnerabilities associated with noise-augmented visual inputs are overlooked. In this work, we identify that missing noise-augmented training causes critical security gaps: many VLMs are susceptible to even simple perturbations such as Gaussian noise. To address this challenge, we propose Robust-VLGuard, a multimodal safety dataset with aligned / misaligned image-text pairs, combined with noise-augmented fine-tuning that reduces attack success rates while preserving functionality of VLM. For stronger optimization-based visual perturbation attacks, we propose DiffPure-VLM, leveraging diffusion models to convert adversarial perturbations into Gaussian-like noise, which can be defended by VLMs with noise-augmented safety fine-tuning. Experimental results demonstrate that the distribution-shifting property of diffusion model aligns well with our fine-tuned VLMs, significantly mitigating adversarial perturbations across varying intensities. The dataset and code are available at https://github.com/JarvisUSTC/DiffPure-RobustVLM.

[Arxiv](https://arxiv.org/abs/2504.01308)