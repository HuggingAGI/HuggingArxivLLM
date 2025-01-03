# 基于视觉Transformer的一次性多语言字体生成

发布时间：2024年12月15日

`RAG

理由：该论文提出了一种基于视觉Transformer（ViT）的多语言字体生成模型，并引入了检索增强引导（RAG）模块来动态检索并适配风格参考。RAG模块的使用是该论文的核心创新点之一，因此将其分类为RAG是合适的。` `字体设计` `多语言处理`

> One-Shot Multilingual Font Generation Via ViT

# 摘要

> # 摘要
字体设计在中文、日文和韩文（CJK）等表意文字语言中面临独特挑战，因为这些语言包含成千上万的独特字符，每个字符都需要单独设计。本文提出了一种基于视觉Transformer（ViT）的多语言字体生成模型，有效应对了表意文字和字母文字的复杂性。通过结合ViT和掩码自编码（MAE）预训练任务，我们的模型不仅摒弃了传统框架中的复杂设计组件，还实现了更强的泛化能力。特别值得一提的是，该模型能够为未见过的、未知的甚至用户自定义的字符生成高质量的多语言字体。此外，我们还引入了检索增强引导（RAG）模块，动态检索并适配风格参考，显著提升了模型的可扩展性和实际应用性。通过多种字体生成任务的验证，我们证明了该模型的有效性、适应性和可扩展性。

> Font design poses unique challenges for logographic languages like Chinese, Japanese, and Korean (CJK), where thousands of unique characters must be individually crafted. This paper introduces a novel Vision Transformer (ViT)-based model for multi-language font generation, effectively addressing the complexities of both logographic and alphabetic scripts. By leveraging ViT and pretraining with a strong visual pretext task (Masked Autoencoding, MAE), our model eliminates the need for complex design components in prior frameworks while achieving comprehensive results with enhanced generalizability. Remarkably, it can generate high-quality fonts across multiple languages for unseen, unknown, and even user-crafted characters. Additionally, we integrate a Retrieval-Augmented Guidance (RAG) module to dynamically retrieve and adapt style references, improving scalability and real-world applicability. We evaluated our approach in various font generation tasks, demonstrating its effectiveness, adaptability, and scalability.

[Arxiv](https://arxiv.org/abs/2412.11342)