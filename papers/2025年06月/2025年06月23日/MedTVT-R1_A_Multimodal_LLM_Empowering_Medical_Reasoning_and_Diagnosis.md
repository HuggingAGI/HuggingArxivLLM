# MedTVT-R1：多模态大语言模型助力医学推理与诊断

发布时间：2025年06月23日

`LLM应用

理由：这篇论文介绍了MedTVT-R1，一个多模态大语言模型框架，用于整合临床多模态数据进行推理和多疾病诊断。虽然涉及模型结构和优化方法，但重点在于模型在医学诊断中的实际应用，属于LLM应用类别。` `多模态`

> MedTVT-R1: A Multimodal LLM Empowering Medical Reasoning and Diagnosis

# 摘要

> # 摘要
多疾病诊断的准确性和可解释性仍是医学研究中的重大挑战，特别是在利用异质性多模态医学数据时。现有方法往往依赖单一模态数据，限制了对复杂疾病全面理解的能力。为此，我们提出了MedTVT-R1——一个新型多模态大语言模型（MLLM）框架，专为整合临床多模态数据进行推理和多疾病诊断而设计。我们构建了MedTVT-QA——一个经过精心整理的指令数据集，提供生理学层面的解释和疾病层面诊断的问题-答案对，并采用证据链方法。MedTVT-R1集成了模态感知层，能够捕获跨模态依赖关系并自适应调整各模态贡献权重。此外，我们采用基于组相对策略优化（GRPO）的强化微调方法，并结合Jaccard奖励函数，以增强诊断推理能力。实验结果表明，MedTVT-R1在多模态特征利用和多疾病诊断方面表现优异，为诊断报告生成和共病推理等临床应用提供了重要潜力。数据集和代码可在https://github.com/keke-nice/MedTVT-R1获取。

> Accurate and interpretable multi-disease diagnosis remains a critical challenge in medical research, particularly when leveraging heterogeneous multimodal medical data. Current approaches often rely on single-modal data, limiting their ability to comprehensively understand complex diseases. To address this, we propose MedTVT-R1, a novel Multimodal Large Language Model (MLLM) framework designed to integrate clinical multimodal data for reasoning and diagnosing multiple diseases. We construct MedTVT-QA, a curated instruction dataset that provides question-answer pairs for physiological-level interpretations and disease-level diagnoses with a Chain of Evidence approach. MedTVT-R1 incorporates a modality perception layer to capture inter-modal dependencies and adaptively weight modality contributions. Additionally, we employ Group Relative Policy Optimization (GRPO)-based Reinforcement Fine-Tuning with a Jaccard Reward function to enhance diagnostic reasoning. Experimental results demonstrate MedTVT-R1's superiority in multimodal feature utilization and multi-disease diagnosis, offering significant potential for clinical applications such as diagnostic report generation and comorbidity reasoning. The dataset and code are available at https://github.com/keke-nice/MedTVT-R1.

[Arxiv](https://arxiv.org/abs/2506.18512)