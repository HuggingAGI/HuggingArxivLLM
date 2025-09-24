# Baseer：面向阿拉伯语文档转Markdown的视觉-语言OCR模型

发布时间：2025年09月17日

`LLM应用` `媒体与娱乐`

> Baseer: A Vision-Language Model for Arabic Document-to-Markdown OCR

# 摘要

> 阿拉伯语文档OCR仍是一项极具挑战的任务，因其连笔书写、字体多样、包含变音符号且采用从右到左的书写方向。尽管现代多模态大型语言模型（MLLMs）已推动高资源语言的文档理解取得进展，但其在阿拉伯语上的表现仍有局限。为此，我们提出了Baseer——一种专为阿拉伯语文档OCR微调的视觉-语言模型。Baseer利用包含合成与真实文档的大规模数据集，通过仅解码器微调策略对预训练MLLM进行适配训练，同时保留通用视觉特征。我们还构建了Misraj-DocOCR——一个高质量、经专家验证的基准数据集，用于对阿拉伯语OCR系统进行严格评估。实验结果表明，Baseer显著优于现有的开源及商业解决方案，词错误率（WER）低至0.25，在阿拉伯语文档OCR领域树立了新的技术标杆。研究结果突显了通用MLLMs进行特定领域适配的优势，并为阿拉伯语等形态丰富语言的高精度OCR任务奠定了坚实基准。

> Arabic document OCR remains a challenging task due to the language's cursive script, diverse fonts, diacritics, and right-to-left orientation. While modern Multimodal Large Language Models (MLLMs) have advanced document understanding for high-resource languages, their performance on Arabic remains limited. In this work, we introduce Baseer, a vision-language model fine- tuned specifically for Arabic document OCR. Leveraging a large-scale dataset combining synthetic and real-world documents, Baseer is trained using a decoder-only fine-tuning strategy to adapt a pre-trained MLLM while preserving general visual features. We also present Misraj-DocOCR, a high-quality, expert-verified benchmark designed for rigorous evaluation of Arabic OCR systems. Our experiments show that Baseer significantly outperforms existing open-source and commercial solutions, achieving a WER of 0.25 and establishing a new state-of-the-art in the domain of Arabic document OCR. Our results highlight the benefits of domain-specific adaptation of general-purpose MLLMs and establish a strong baseline for high-accuracy OCR on morphologically rich languages like Arabic.

[Arxiv](https://arxiv.org/abs/2509.18174)