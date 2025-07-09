# TextPixs：结合字符感知注意力与OCR引导监督的字符条件扩散模型。

发布时间：2025年07月08日

`其他

理由：这篇论文主要探讨了文本到图像的扩散模型在生成图像时的文本生成问题，并提出了一种新的框架来改进生成图像中可读文本的质量。虽然它涉及到生成模型的应用，但并没有直接涉及大型语言模型（LLM）的理论或应用，因此更适合归类到“其他”类别中。` `创意设计`

> TextPixs: Glyph-Conditioned Diffusion with Character-Aware Attention and OCR-Guided Supervision

# 摘要

> 现代文本到图像的扩散模型的繁荣开启了数字内容生产的新纪元。这些模型能够基于自然语言描述生成令人惊叹的 photorealistic 和多样化风格的图像，然而它们却无法在生成的图像中生成可读、有意义且正确拼写的文本，这大大限制了其在广告、教育和创意设计等实际场景中的应用。

本文提出了一种全新的框架——Glyph-Conditioned字符感知扩散模型（GCDA），通过三个精心设计的模块扩展了传统的扩散模型架构。首先，GCDA采用了双流文本编码器，能够同时捕捉语义上下文信息和显式的Glyph特征，从而生成丰富的字符感知文本表示。其次，我们引入了一种创新的字符感知注意力机制，并设计了新的注意力分离损失函数，通过独立控制每个字符的注意力分布来避免图像失真。最后，GCDA创新性地引入了OCR-in-the-loop微调阶段，通过端到端的文本感知损失优化，显著提升了生成文本的可读性和准确性。

在MARIO-10M和T2I-CompBench等大规模基准数据集上的实验结果表明，GCDA在文本渲染质量、人类感知体验和图像合成保真度等多个关键指标上均达到了新的最先进水平。具体而言，GCDA在字符错误率（0.08 vs 0.21）和单词错误率（0.15 vs 0.25）上大幅优于现有方法，同时保持了与最优模型相当的图像生成质量（FID:14.3）。


> The modern text-to-image diffusion models boom has opened a new era in digital content production as it has proven the previously unseen ability to produce photorealistic and stylistically diverse imagery based on the semantics of natural-language descriptions. However, the consistent disadvantage of these models is that they cannot generate readable, meaningful, and correctly spelled text in generated images, which significantly limits the use of practical purposes like advertising, learning, and creative design. This paper introduces a new framework, namely Glyph-Conditioned Diffusion with Character-Aware Attention (GCDA), using which a typical diffusion backbone is extended by three well-designed modules. To begin with, the model has a dual-stream text encoder that encodes both semantic contextual information and explicit glyph representations, resulting in a character-aware representation of the input text that is rich in nature. Second, an attention mechanism that is aware of the character is proposed with a new attention segregation loss that aims to limit the attention distribution of each character independently in order to avoid distortion artifacts. Lastly, GCDA has an OCR-in-the-loop fine-tuning phase, where a full text perceptual loss, directly optimises models to be legible and accurately spell. Large scale experiments to benchmark datasets, such as MARIO-10M and T2I-CompBench, reveal that GCDA sets a new state-of-the-art on all metrics, with better character based metrics on text rendering (Character Error Rate: 0.08 vs 0.21 for the previous best; Word Error Rate: 0.15 vs 0.25), human perception, and comparable image synthesis quality on high-fidelity (FID: 14.3).

[Arxiv](https://arxiv.org/abs/2507.06033)