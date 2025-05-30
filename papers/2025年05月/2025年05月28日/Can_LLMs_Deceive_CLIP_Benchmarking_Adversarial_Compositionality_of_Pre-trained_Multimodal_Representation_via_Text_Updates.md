# # LLMs能否蒙骗CLIP？通过文本更新评估预训练多模态表示的对抗组合性
大型语言模型（LLMs）能否欺骗CLIP？通过文本更新的方式，我们对预训练多模态表示的对抗组合性进行了基准测试。

发布时间：2025年05月28日

`LLM应用` `人工智能`

> Can LLMs Deceive CLIP? Benchmarking Adversarial Compositionality of Pre-trained Multimodal Representation via Text Updates

# 摘要

> 预训练的多模态表示（如 CLIP）虽表现出色，但存在显著的组合漏洞，导致判断违背直觉。我们提出多模态对抗性组合性（MAC），这是一个利用大型语言模型（LLMs）生成欺骗性文本样本以在不同模态中触发漏洞的基准测试，通过样本攻击成功率和群体多样性进行评估。为提升零样本方法，我们提出结合拒绝采样微调和多样性促进过滤的自训练方法，显著提升了攻击成功率和样本多样性。使用较小的模型如 Llama-3.1-8B，我们的方法在揭示图像、视频和音频等多种多模态表示的组合漏洞方面表现优异。

> While pre-trained multimodal representations (e.g., CLIP) have shown impressive capabilities, they exhibit significant compositional vulnerabilities leading to counterintuitive judgments. We introduce Multimodal Adversarial Compositionality (MAC), a benchmark that leverages large language models (LLMs) to generate deceptive text samples to exploit these vulnerabilities across different modalities and evaluates them through both sample-wise attack success rate and group-wise entropy-based diversity. To improve zero-shot methods, we propose a self-training approach that leverages rejection-sampling fine-tuning with diversity-promoting filtering, which enhances both attack success rate and sample diversity. Using smaller language models like Llama-3.1-8B, our approach demonstrates superior performance in revealing compositional vulnerabilities across various multimodal representations, including images, videos, and audios.

[Arxiv](https://arxiv.org/abs/2505.22943)