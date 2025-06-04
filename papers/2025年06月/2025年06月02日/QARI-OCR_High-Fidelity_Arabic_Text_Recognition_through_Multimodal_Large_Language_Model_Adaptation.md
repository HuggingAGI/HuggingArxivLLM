# QARI-OCR：基于多模态大型语言模型的调整，实现高精度的阿拉伯文文本识别

发布时间：2025年06月02日

`LLM应用` `文档处理`

> QARI-OCR: High-Fidelity Arabic Text Recognition through Multimodal Large Language Model Adaptation

# 摘要

> 阿拉伯语文字的固有复杂性，包括其连写特性、音素符号（tashkeel）和多样的排版，为光学字符识别（OCR）带来了持续性的挑战。我们推出了Qari-OCR，这是一系列基于Qwen2-VL-2B-Instruct的视觉语言模型，通过在特定合成数据集上进行迭代微调，逐步针对阿拉伯语进行了优化。我们的领先模型QARI v0.2在包含丰富音素符号的文本上实现了词错误率（WER）0.160、字符错误率（CER）0.061以及BLEU分数0.737，树立了开源领域的全新标杆。Qari-OCR在处理tashkeel、多样字体、文档版式以及低分辨率图像方面表现出色。进一步的探索（QARI v0.3）则展现了在结构化文档理解和手写文本识别方面的强大潜力。这项研究显著提升了阿拉伯语OCR的准确性和效率，所有模型和数据集均已公开发布，以推动相关领域的进一步研究。

> The inherent complexities of Arabic script; its cursive nature, diacritical marks (tashkeel), and varied typography, pose persistent challenges for Optical Character Recognition (OCR). We present Qari-OCR, a series of vision-language models derived from Qwen2-VL-2B-Instruct, progressively optimized for Arabic through iterative fine-tuning on specialized synthetic datasets. Our leading model, QARI v0.2, establishes a new open-source state-of-the-art with a Word Error Rate (WER) of 0.160, Character Error Rate (CER) of 0.061, and BLEU score of 0.737 on diacritically-rich texts. Qari-OCR demonstrates superior handling of tashkeel, diverse fonts, and document layouts, alongside impressive performance on low-resolution images. Further explorations (QARI v0.3) showcase strong potential for structural document understanding and handwritten text. This work delivers a marked improvement in Arabic OCR accuracy and efficiency, with all models and datasets released to foster further research.

[Arxiv](https://arxiv.org/abs/2506.02295)