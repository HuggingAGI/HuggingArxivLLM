# FaceShield：基于多模态大语言模型的可解释性面部反欺骗系统

发布时间：2025年05月14日

`LLM应用

论文摘要：面部反欺骗攻击（FAS）是保护面部识别系统免受攻击的关键。传统方法将其视为分类问题，但缺乏对预测结果的解释性和推理能力。近年来，多模态大型语言模型（MLLMs）在视觉任务中展现出强大的感知、推理和决策能力。然而，目前尚未有专门针对FAS任务的通用MLLM和数据集。为此，我们提出了FaceShield——一款专为FAS设计的MLLM，以及配套的预训练数据集FaceShield-pre10K和监督微调（SFT）数据集FaceShield-sft45K。FaceShield不仅能判断面部的真实性，还能识别欺骗攻击类型、提供推理依据，并定位攻击区域。具体而言，我们采用了结合原始图像和先验知识辅助信息的欺骗感知视觉感知（SAVP），并通过提示引导视觉标记遮蔽（PVTM）策略随机遮蔽视觉标记，从而提升模型的泛化能力。我们在三个基准数据集上进行了大量实验，结果显示FaceShield在粗粒度分类、细粒度分类、推理和攻击定位等四个FAS任务上，显著优于传统深度学习模型和通用MLLMs。我们的数据集、协议和代码即将开源。

LLM应用` `面部识别` `计算机视觉`

> FaceShield: Explainable Face Anti-Spoofing with Multimodal Large Language Models

# 摘要

> 面部反欺骗攻击（FAS）是保护面部识别系统免受攻击的关键。传统方法将其视为分类问题，但缺乏对预测结果的解释性和推理能力。近年来，多模态大型语言模型（MLLMs）在视觉任务中展现出强大的感知、推理和决策能力。然而，目前尚未有专门针对FAS任务的通用MLLM和数据集。为此，我们提出了FaceShield——一款专为FAS设计的MLLM，以及配套的预训练数据集FaceShield-pre10K和监督微调（SFT）数据集FaceShield-sft45K。FaceShield不仅能判断面部的真实性，还能识别欺骗攻击类型、提供推理依据，并定位攻击区域。具体而言，我们采用了结合原始图像和先验知识辅助信息的欺骗感知视觉感知（SAVP），并通过提示引导视觉标记遮蔽（PVTM）策略随机遮蔽视觉标记，从而提升模型的泛化能力。我们在三个基准数据集上进行了大量实验，结果显示FaceShield在粗粒度分类、细粒度分类、推理和攻击定位等四个FAS任务上，显著优于传统深度学习模型和通用MLLMs。我们的数据集、协议和代码即将开源。

> Face anti-spoofing (FAS) is crucial for protecting facial recognition systems from presentation attacks. Previous methods approached this task as a classification problem, lacking interpretability and reasoning behind the predicted results. Recently, multimodal large language models (MLLMs) have shown strong capabilities in perception, reasoning, and decision-making in visual tasks. However, there is currently no universal and comprehensive MLLM and dataset specifically designed for FAS task. To address this gap, we propose FaceShield, a MLLM for FAS, along with the corresponding pre-training and supervised fine-tuning (SFT) datasets, FaceShield-pre10K and FaceShield-sft45K. FaceShield is capable of determining the authenticity of faces, identifying types of spoofing attacks, providing reasoning for its judgments, and detecting attack areas. Specifically, we employ spoof-aware vision perception (SAVP) that incorporates both the original image and auxiliary information based on prior knowledge. We then use an prompt-guided vision token masking (PVTM) strategy to random mask vision tokens, thereby improving the model's generalization ability. We conducted extensive experiments on three benchmark datasets, demonstrating that FaceShield significantly outperforms previous deep learning models and general MLLMs on four FAS tasks, i.e., coarse-grained classification, fine-grained classification, reasoning, and attack localization. Our instruction datasets, protocols, and codes will be released soon.

[Arxiv](https://arxiv.org/abs/2505.09415)