# 基于多模态大型语言模型生成标准化文本的超声报告

发布时间：2025年05月13日

`LLM应用` `人工智能`

> Ultrasound Report Generation with Multimodal Large Language Models for Standardized Texts

# 摘要

> 超声（US）报告生成面临诸多挑战，包括图像变异性大、操作依赖性强以及对标准化文本的要求。与X光和CT不同，超声成像缺乏一致的数据集，这使得自动化生成报告更加困难。针对这些挑战，我们提出了一种统一的多器官和多语言超声报告生成框架。该框架整合了基于片段的多语言训练，并充分利用超声报告的标准化特性。通过将模块化文本片段与多样化的影像数据对齐，并整理一个中英双语数据集，该方法在不同器官部位和语言之间实现了稳定且临床准确的文本生成。此外，通过选择性解冻视觉变换器（ViT）进行微调，进一步提升了文本与图像的对齐效果。与之前的最先进KMVE方法相比，我们的方法在BLEU分数上相对提高了约【数学公式】2%，ROUGE-L提高了约【数学公式】3%，CIDEr提高了约【数学公式】15%，同时显著减少了内容缺失或错误。这项工作将多器官和多语言报告生成统一到一个可扩展的单一框架中，展示了在真实临床工作流程中应用的强劲潜力。

> Ultrasound (US) report generation is a challenging task due to the variability of US images, operator dependence, and the need for standardized text. Unlike X-ray and CT, US imaging lacks consistent datasets, making automation difficult. In this study, we propose a unified framework for multi-organ and multilingual US report generation, integrating fragment-based multilingual training and leveraging the standardized nature of US reports. By aligning modular text fragments with diverse imaging data and curating a bilingual English-Chinese dataset, the method achieves consistent and clinically accurate text generation across organ sites and languages. Fine-tuning with selective unfreezing of the vision transformer (ViT) further improves text-image alignment. Compared to the previous state-of-the-art KMVE method, our approach achieves relative gains of about 2\% in BLEU scores, approximately 3\% in ROUGE-L, and about 15\% in CIDEr, while significantly reducing errors such as missing or incorrect content. By unifying multi-organ and multi-language report generation into a single, scalable framework, this work demonstrates strong potential for real-world clinical workflows.

[Arxiv](https://arxiv.org/abs/2505.08838)