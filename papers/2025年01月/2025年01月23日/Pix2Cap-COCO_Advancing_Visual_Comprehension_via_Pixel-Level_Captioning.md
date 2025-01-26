# Pix2Cap-COCO: 像素级字幕生成助力视觉理解新突破

发布时间：2025年01月23日

`LLM应用

**理由**：这篇论文主要讨论了利用GPT-4V生成图像描述，并基于这些描述进行模型训练和性能提升。这涉及到大型语言模型（LLM）在视觉理解和语言生成任务中的应用，因此归类为LLM应用。` `计算机视觉`

> Pix2Cap-COCO: Advancing Visual Comprehension via Pixel-Level Captioning

# 摘要

> 我们推出了Pix2Cap-COCO，这是首个旨在提升细粒度视觉理解的全景像素级描述数据集。为此，我们设计了一个自动化注释管道，利用GPT-4V为图像中的每个对象生成像素对齐的实例描述，帮助模型更好地理解对象与上下文的关系。该数据集包含167,254条详细描述，平均每条22.94个单词。基于Pix2Cap-COCO，我们提出了全景分割-描述任务，要求模型在识别图像实例的同时生成详细描述。我们基于X-Decoder设计了基线模型，实验表明Pix2Cap-COCO极具挑战性，要求模型在视觉理解和语言生成方面都表现出色。此外，我们利用Pix2Cap-COCO对大型多模态模型（LMMs）进行监督微调，显著提升了GPT4RoI的性能：在Visual Genome数据集上，CIDEr提升+1.4%，ROUGE提升+0.4%，SPICE提升+0.5%；在ViP-BENCH上，区域理解能力整体提升+5.1%，其中识别准确率提升+11.2%，语言生成质量提升+22.2%。

> We present Pix2Cap-COCO, the first panoptic pixel-level caption dataset designed to advance fine-grained visual understanding. To achieve this, we carefully design an automated annotation pipeline that prompts GPT-4V to generate pixel-aligned, instance-specific captions for individual objects within images, enabling models to learn more granular relationships between objects and their contexts. This approach results in 167,254 detailed captions, with an average of 22.94 words per caption. Building on Pix2Cap-COCO, we introduce a novel task, panoptic segmentation-captioning, which challenges models to recognize instances in an image and provide detailed descriptions for each simultaneously. To benchmark this task, we design a robust baseline based on X-Decoder. The experimental results demonstrate that Pix2Cap-COCO is a particularly challenging dataset, as it requires models to excel in both fine-grained visual understanding and detailed language generation. Furthermore, we leverage Pix2Cap-COCO for Supervised Fine-Tuning (SFT) on large multimodal models (LMMs) to enhance their performance. For example, training with Pix2Cap-COCO significantly improves the performance of GPT4RoI, yielding gains in CIDEr +1.4%, ROUGE +0.4%, and SPICE +0.5% on Visual Genome dataset, and strengthens its region understanding ability on the ViP-BENCH, with an overall improvement of +5.1%, including notable increases in recognition accuracy +11.2% and language generation quality +22.2%.

[Arxiv](https://arxiv.org/abs/2501.13893)