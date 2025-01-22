# 更懂“不”：数据驱动方法提升CLIP的否定感知能力

发布时间：2025年01月18日

`LLM应用` `计算机视觉`

> Know "No" Better: A Data-Driven Approach for Enhancing Negation Awareness in CLIP

# 摘要

> 尽管CLIP在视觉与语言的结合上取得了显著进展，但其无法理解否定（如区分“停车”与“禁止停车”）带来了巨大挑战。通过分析CLIP预训练数据，我们认为这一缺陷源于缺乏包含否定的数据。为此，我们设计了数据生成管道，利用LLM和多模态LLM生成包含否定的描述。基于这些数据微调CLIP后，我们开发了NegationCLIP，它在保持通用性的同时提升了否定感知能力。此外，我们提出了NegRefCOCOg基准，专门用于评估视觉语言模型在句子中不同位置和表达下理解否定的能力。实验表明，我们的数据生成管道有效提升了CLIP的否定感知能力。NegationCLIP的增强能力在文本生成图像和参考图像分割等任务中展现了实际应用价值。

> While CLIP has significantly advanced multimodal understanding by bridging vision and language, the inability to grasp negation - such as failing to differentiate concepts like "parking" from "no parking" - poses substantial challenges. By analyzing the data used in the public CLIP model's pre-training, we posit this limitation stems from a lack of negation-inclusive data. To address this, we introduce data generation pipelines that employ a large language model (LLM) and a multimodal LLM to produce negation-inclusive captions. Fine-tuning CLIP with data generated from our pipelines, we develop NegationCLIP, which enhances negation awareness while preserving the generality. Moreover, to enable a comprehensive evaluation of negation understanding, we propose NegRefCOCOg-a benchmark tailored to test VLMs' ability to interpret negation across diverse expressions and positions within a sentence. Experiments on various CLIP architectures validate the effectiveness of our data generation pipelines in enhancing CLIP's ability to perceive negation accurately. Additionally, NegationCLIP's enhanced negation awareness has practical applications across various multimodal tasks, demonstrated by performance gains in text-to-image generation and referring image segmentation.

[Arxiv](https://arxiv.org/abs/2501.10913)