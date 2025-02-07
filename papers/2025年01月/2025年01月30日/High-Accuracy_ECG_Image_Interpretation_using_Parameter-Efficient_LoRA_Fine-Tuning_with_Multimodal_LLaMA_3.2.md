# 基于参数高效LoRA微调与多模态LLaMA 3.2的高精度ECG图像解析

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何利用多模态LLaMA 3.2模型来增强心电图（ECG）图像的解读能力，并通过低秩适应（LoRA）技术进行参数高效微调。该方法在多种心脏疾病中取得了优异效果，并显著优于基线模型。这属于将大型语言模型（LLM）应用于特定领域（ECG图像解读）的实际应用场景，因此归类为LLM应用。` `心脏诊断`

> High-Accuracy ECG Image Interpretation using Parameter-Efficient LoRA Fine-Tuning with Multimodal LLaMA 3.2

# 摘要

> # 摘要
心电图（ECG）解读是心脏诊断的核心。本文提出了一种基于多模态LLaMA 3.2模型的ECG图像解读增强方法。我们采用低秩适应（LoRA）这一参数高效微调策略，专门设计用于提升模型对ECG图像的理解能力，并在多种心脏疾病中取得优异效果。该方法专为ECG分析设计，并利用了包含100万样本的ECGInstruct数据集。该数据集基于MIMIC-IV ECG和PTB-XL等开源库的原始ECG数据生成，涵盖了从心肌梗死到传导障碍等复杂心脏疾病的多样化解读场景。每个ECG图像均配有专家编写的问题和详细答案。我们的微调方法通过低秩适应技术高效调整LLaMA 3.2模型（基于LLaMA 3），仅更新少量参数，特别跳过了`lm_head`和`embed_tokens`层。本文详细介绍了模型设置、微调方法及实现细节，并通过大量实验验证了其有效性。结果表明，我们的LoRA微调方法在ECG图像解读中表现卓越，显著优于基线模型，并在识别PTB-XL数据集中的70多种心脏异常时，达到了与传统CNN方法相当或更高的准确性。

> Electrocardiogram (ECG) interpretation is a cornerstone of cardiac diagnostics. This paper explores a practical approach to enhance ECG image interpretation using the multimodal LLaMA 3.2 model. We used a parameter-efficient fine-tuning strategy, Low-Rank Adaptation (LoRA), specifically designed to boost the model's ability to understand ECG images and achieve better outcomes across a wide range of cardiac conditions. Our method is tailored for ECG analysis and leverages ECGInstruct, a large-scale instruction dataset with 1 Million samples. This dataset is a rich collection of synthesized ECG images, generated from raw ECG data from trusted open-source repositories like MIMIC-IV ECG and PTB-XL. Each ECG image in ECGInstruct comes with expert-written questions and detailed answers, covering diverse ECG interpretation scenarios, including complex cardiac conditions like Myocardial Infarction and Conduction Disturbances. Our fine-tuning approach efficiently adapts the LLaMA 3.2 model (built upon LLaMA 3) by integrating low-rank adaptation techniques, focusing on efficiency by updating only a small set of parameters, specifically ignoring the `lm_head` and `embed_tokens` layers. This paper details the model setup, our efficient fine-tuning method, and implementation specifics. We provide a thorough evaluation through extensive experiments, demonstrating the effectiveness of our method across various ECG interpretation tasks. The results convincingly show that our parameter-efficient LoRA fine-tuning achieves excellent performance in ECG image interpretation, significantly outperforming baseline models and reaching accuracy comparable to or exceeding traditional CNN-based methods in identifying a wide range of cardiac abnormalities, including over 70 conditions from the PTB-XL dataset.

[Arxiv](https://arxiv.org/abs/2501.18670)