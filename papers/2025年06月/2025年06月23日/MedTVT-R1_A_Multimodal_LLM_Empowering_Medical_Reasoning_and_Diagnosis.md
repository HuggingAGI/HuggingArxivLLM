# MedTVT-R1: 一个多模态大型语言模型，助力医学推理与诊断

发布时间：2025年06月23日

`LLM应用

理由：这篇论文提出了一种多模态大型语言模型（MLLM）框架，用于整合临床多模态数据以实现多疾病的推理和诊断。它详细介绍了模型的构建和优化方法，并展示了其在医学诊断中的应用潜力。因此，它属于LLM应用类别。` `问答系统`

> MedTVT-R1: A Multimodal LLM Empowering Medical Reasoning and Diagnosis

# 摘要

> # 摘要  
    准确且可解释的多疾病诊断一直是医学研究中的重要挑战，尤其是在利用异质性多模态医疗数据时。当前方法多依赖单一模态数据，限制了对复杂疾病的全面理解。为此，我们提出了 MedTVT-R1，一个创新的多模态大型语言模型（MLLM）框架，旨在整合临床多模态数据以实现多疾病的推理和诊断。  
    我们构建了 MedTVT-QA，这是一个经过整理的指令数据集，提供基于证据链方法的生理水平解释和疾病水平诊断的问答对。MedTVT-R1 配备了一个模态感知层，用于捕捉跨模态依赖关系并自适应地调整模态贡献权重。此外，我们采用了基于 Jaccard 奖励函数的组相对策略优化（GRPO）强化微调方法，以增强诊断推理能力。  
    实验结果表明，MedTVT-R1 在多模态特征利用和多疾病诊断方面表现出色，为临床应用（如诊断报告生成和共病推理）提供了巨大潜力。数据集和代码可在 https://github.com/keke-nice/MedTVT-R1 获取。

> Accurate and interpretable multi-disease diagnosis remains a critical challenge in medical research, particularly when leveraging heterogeneous multimodal medical data. Current approaches often rely on single-modal data, limiting their ability to comprehensively understand complex diseases. To address this, we propose MedTVT-R1, a novel Multimodal Large Language Model (MLLM) framework designed to integrate clinical multimodal data for reasoning and diagnosing multiple diseases. We construct MedTVT-QA, a curated instruction dataset that provides question-answer pairs for physiological-level interpretations and disease-level diagnoses with a Chain of Evidence approach. MedTVT-R1 incorporates a modality perception layer to capture inter-modal dependencies and adaptively weight modality contributions. Additionally, we employ Group Relative Policy Optimization (GRPO)-based Reinforcement Fine-Tuning with a Jaccard Reward function to enhance diagnostic reasoning. Experimental results demonstrate MedTVT-R1's superiority in multimodal feature utilization and multi-disease diagnosis, offering significant potential for clinical applications such as diagnostic report generation and comorbidity reasoning. The dataset and code are available at https://github.com/keke-nice/MedTVT-R1.

[Arxiv](https://arxiv.org/abs/2506.18512)