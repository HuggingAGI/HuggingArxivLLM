# Libra：借助时间图像开展生物医学放射学分析

发布时间：2024年11月28日

`LLM应用` `放射学`

> Libra: Leveraging Temporal Images for Biomedical Radiology Analysis

# 摘要

> 放射学报告生成（RRG）是个颇具挑战的任务，因其需要深度理解医学图像、整合多个时间输入并精确生成报告。比如，对胸部 X 光（CXRs）等医学图像的有效解读，需要复杂的视觉语言推理，以将视觉发现转化为结构化报告。近期研究显示，多模态大型语言模型（MLLMs）能通过与预训练的视觉编码器对齐获取多模态能力。然而，当下的方法多聚焦于单图像分析，或利用基于规则的符号处理来应对多个图像，进而忽略了通过对比当前图像与先前图像所得出的关键时间信息。为突破这一重要局限，我们推出了 Libra，这是一个专为利用时间图像生成 CXR 报告而打造的具有时间感知能力的 MLLM。Libra 将放射学专用的图像编码器与 MLLM 相融合，并采用一种新颖的时间对齐连接器，以前所未有的精度捕获和合成不同时间点图像的时间信息。大量实验表明，在 MIMIC-CXR 上的 RRG 任务中，Libra 在相同参数规模的 MLLMs 里达到了全新的最先进水平。具体来说，Libra 让 RadCliQ 指标提升了 12.9%，且在所有词汇指标上较之前的模型都有显著进步。

> Radiology report generation (RRG) is a challenging task, as it requires a thorough understanding of medical images, integration of multiple temporal inputs, and accurate report generation. Effective interpretation of medical images, such as chest X-rays (CXRs), demands sophisticated visual-language reasoning to map visual findings to structured reports. Recent studies have shown that multimodal large language models (MLLMs) can acquire multimodal capabilities by aligning with pre-trained vision encoders. However, current approaches predominantly focus on single-image analysis or utilise rule-based symbolic processing to handle multiple images, thereby overlooking the essential temporal information derived from comparing current images with prior ones. To overcome this critical limitation, we introduce Libra, a temporal-aware MLLM tailored for CXR report generation using temporal images. Libra integrates a radiology-specific image encoder with a MLLM and utilises a novel Temporal Alignment Connector to capture and synthesise temporal information of images across different time points with unprecedented precision. Extensive experiments show that Libra achieves new state-of-the-art performance among the same parameter scale MLLMs for RRG tasks on the MIMIC-CXR. Specifically, Libra improves the RadCliQ metric by 12.9% and makes substantial gains across all lexical metrics compared to previous models.

[Arxiv](https://arxiv.org/abs/2411.19378)