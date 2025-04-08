# # SCAM：多模态基础模型在现实世界排版鲁棒性评估中的研究
SCAM 是一项专注于评估多模态基础模型在现实世界排版场景中鲁棒性的研究框架。

发布时间：2025年04月07日

`其他` `网络安全` `人工智能`

> SCAM: A Real-World Typographic Robustness Evaluation for Multimodal Foundation Models

# 摘要

> 排版攻击利用多模态模型中文本与视觉内容的交互作用，当误导性文本嵌入图像时，会导致模型分类错误。然而，现有数据集在规模和多样性上存在局限性，难以深入研究此类漏洞。本文介绍SCAM，这是迄今为止规模最大、多样性最丰富的现实世界排版攻击图像数据集，包含1,162张图像，涵盖数百个物体类别和攻击词。通过对视觉语言模型（VLMs）在SCAM上的广泛基准测试，我们发现排版攻击显著降低了模型性能，并且训练数据和模型架构会影响模型对这些攻击的易感性。我们的研究发现，由于其视觉编码器的选择，排版攻击在最先进的大视觉-语言模型（LVLMs）中仍然存在，尽管大型语言模型（LLMs）主干有助于缓解这一漏洞。此外，我们证明合成攻击与现实世界（手写）攻击非常相似，验证了其在研究中的应用价值。我们的工作提供了一个全面的资源和实证见解，以促进未来研究，构建更健壮和可信的多模态AI系统。我们在https://huggingface.co/datasets/BLISS-e-V/SCAM公开发布了本文介绍的数据集，并在https://github.com/Bliss-e-V/SCAM提供了评估代码。

> Typographic attacks exploit the interplay between text and visual content in multimodal foundation models, causing misclassifications when misleading text is embedded within images. However, existing datasets are limited in size and diversity, making it difficult to study such vulnerabilities. In this paper, we introduce SCAM, the largest and most diverse dataset of real-world typographic attack images to date, containing 1,162 images across hundreds of object categories and attack words. Through extensive benchmarking of Vision-Language Models (VLMs) on SCAM, we demonstrate that typographic attacks significantly degrade performance, and identify that training data and model architecture influence the susceptibility to these attacks. Our findings reveal that typographic attacks persist in state-of-the-art Large Vision-Language Models (LVLMs) due to the choice of their vision encoder, though larger Large Language Models (LLMs) backbones help mitigate their vulnerability. Additionally, we demonstrate that synthetic attacks closely resemble real-world (handwritten) attacks, validating their use in research. Our work provides a comprehensive resource and empirical insights to facilitate future research toward robust and trustworthy multimodal AI systems. We publicly release the datasets introduced in this paper under https://huggingface.co/datasets/BLISS-e-V/SCAM, along with the code for evaluations at https://github.com/Bliss-e-V/SCAM.

[Arxiv](https://arxiv.org/abs/2504.04893)