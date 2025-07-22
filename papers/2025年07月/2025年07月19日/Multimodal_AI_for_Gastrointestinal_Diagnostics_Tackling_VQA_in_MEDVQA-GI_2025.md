# # 多模态 AI 在胃肠诊断中的应用：MEDVQA-GI 2025 中的视觉问答挑战

发布时间：2025年07月19日

`LLM应用` `医学影像`

> Multimodal AI for Gastrointestinal Diagnostics: Tackling VQA in MEDVQA-GI 2025

# 摘要

> 本文介绍了我们在ImageCLEFmed MEDVQA 2025挑战赛子任务1中的解决方案，专注于胃肠内窥镜检查中的视觉问答（VQA）任务。我们采用Florence模型——一个大规模多模态基础模型——作为VQA流水线的核心架构，通过结合强大的视觉编码器与文本编码器，有效解析内窥镜图像并生成具有临床意义的回答。为提升模型的泛化能力，我们引入了特定领域的数据增强方法，在保持医学特征的同时丰富了训练数据的多样性。实验结果表明，在KASVIR数据集上微调Florence模型可获得在官方挑战指标上的优异表现。我们的研究不仅展示了大规模多模态模型在医学VQA中的巨大潜力，还为未来在可解释性、鲁棒性及临床应用整合方面的工作提供了坚实的基础。代码已公开发布，地址为：https://github.com/TiwariLaxuu/VQA-Florence.git

> This paper describes our approach to Subtask 1 of the ImageCLEFmed MEDVQA 2025 Challenge, which targets visual question answering (VQA) for gastrointestinal endoscopy. We adopt the Florence model-a large-scale multimodal foundation model-as the backbone of our VQA pipeline, pairing a powerful vision encoder with a text encoder to interpret endoscopic images and produce clinically relevant answers. To improve generalization, we apply domain-specific augmentations that preserve medical features while increasing training diversity. Experiments on the KASVIR dataset show that fine-tuning Florence yields accurate responses on the official challenge metrics. Our results highlight the potential of large multimodal models in medical VQA and provide a strong baseline for future work on explainability, robustness, and clinical integration. The code is publicly available at: https://github.com/TiwariLaxuu/VQA-Florence.git

[Arxiv](https://arxiv.org/abs/2507.14544)