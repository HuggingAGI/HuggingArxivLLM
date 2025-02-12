# # 摘要  
基于多模态大型语言模型的零样本异常检测与推理探索

发布时间：2025年02月11日

`LLM应用` `异常检测`

> Towards Zero-Shot Anomaly Detection and Reasoning with Multimodal Large Language Models

# 摘要

> 零样本异常检测（ZSAD）作为一种新兴的检测范式，相较于传统无监督方法，无需大量正常样本训练，特别适用于数据受限的场景。近期，多模态大型语言模型（MLLMs）在视觉任务中展现出强大的推理能力，但在图像异常推理方面仍显不足，主要受限于数据集和基准的缺乏。为推动该领域研究，我们创建了首个视觉指令微调数据集Anomaly-Instruct-125k及评估基准VisA-D&R。研究发现，现有MLLMs如GPT-4o在检测和描述图像中的细粒度异常方面表现欠佳。为此，我们推出Anomaly-OneVision（Anomaly-OV）——首个专注于ZSAD与推理的专用视觉助手。受人类视觉检查行为启发，Anomaly-OV采用双看特征匹配（LTFM）机制，可自适应选择并强调异常视觉标记。实验结果表明，Anomaly-OV在检测与推理能力上显著优于现有通用模型。我们还为医学和3D异常检测提供了扩展方向，供未来研究参考。了解更多：https://xujiacong.github.io/Anomaly-OV/

> Zero-Shot Anomaly Detection (ZSAD) is an emerging AD paradigm. Unlike the traditional unsupervised AD setting that requires a large number of normal samples to train a model, ZSAD is more practical for handling data-restricted real-world scenarios. Recently, Multimodal Large Language Models (MLLMs) have shown revolutionary reasoning capabilities in various vision tasks. However, the reasoning of image abnormalities remains underexplored due to the lack of corresponding datasets and benchmarks. To facilitate research in AD & reasoning, we establish the first visual instruction tuning dataset, Anomaly-Instruct-125k, and the evaluation benchmark, VisA-D&R. Through investigation with our benchmark, we reveal that current MLLMs like GPT-4o cannot accurately detect and describe fine-grained anomalous details in images. To address this, we propose Anomaly-OneVision (Anomaly-OV), the first specialist visual assistant for ZSAD and reasoning. Inspired by human behavior in visual inspection, Anomaly-OV leverages a Look-Twice Feature Matching (LTFM) mechanism to adaptively select and emphasize abnormal visual tokens. Extensive experiments demonstrate that Anomaly-OV achieves significant improvements over advanced generalist models in both detection and reasoning. Extensions to medical and 3D AD are provided for future study. The link to our project page: https://xujiacong.github.io/Anomaly-OV/

[Arxiv](https://arxiv.org/abs/2502.07601)