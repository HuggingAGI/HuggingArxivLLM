# LLaVA-RadZ：多模态大语言模型能否有效解决零样本放射学识别问题？

发布时间：2025年03月10日

`LLM应用` `计算机视觉`

> LLaVA-RadZ: Can Multimodal Large Language Models Effectively Tackle Zero-shot Radiology Recognition?

# 摘要

> 最近，多模态大型模型（MLLMs）在视觉-语言任务中展现出卓越的能力，但在零样本医学疾病识别方面表现欠佳，因为它们未能充分利用提取到的特征和医学知识。为了解决这一难题，我们提出了LLaVA-RadZ，一个简单而有效的零样本医学疾病识别框架。具体来说，我们设计了一种端到端的训练策略，称为解码器侧特征对齐训练（DFAT），充分利用MLLM解码器架构的特点，并引入了针对不同模态的模态特定令牌，有效整合图像和文本表示，促进跨模态对齐。此外，我们开发了一个领域知识锚定模块（DKAM），挖掘大型模型的内在医学知识，缩小图像-文本对齐中的类别语义差距。通过DKAM，我们显著提升了类别级别的对齐效果，从而实现了更精准的疾病识别。在多个基准测试中的大量实验表明，LLaVA-RadZ在零样本疾病识别中明显优于传统的MLLMs，并且在与成熟且优化的基于CLIP的方法对比中，达到了当前最优的性能水平。

> Recently, multimodal large models (MLLMs) have demonstrated exceptional capabilities in visual understanding and reasoning across various vision-language tasks. However, MLLMs usually perform poorly in zero-shot medical disease recognition, as they do not fully exploit the captured features and available medical knowledge. To address this challenge, we propose LLaVA-RadZ, a simple yet effective framework for zero-shot medical disease recognition. Specifically, we design an end-to-end training strategy, termed Decoding-Side Feature Alignment Training (DFAT) to take advantage of the characteristics of the MLLM decoder architecture and incorporate modality-specific tokens tailored for different modalities, which effectively utilizes image and text representations and facilitates robust cross-modal alignment. Additionally, we introduce a Domain Knowledge Anchoring Module (DKAM) to exploit the intrinsic medical knowledge of large models, which mitigates the category semantic gap in image-text alignment. DKAM improves category-level alignment, allowing for accurate disease recognition. Extensive experiments on multiple benchmarks demonstrate that our LLaVA-RadZ significantly outperforms traditional MLLMs in zero-shot disease recognition and exhibits the state-of-the-art performance compared to the well-established and highly-optimized CLIP-based approaches.

[Arxiv](https://arxiv.org/abs/2503.07487)