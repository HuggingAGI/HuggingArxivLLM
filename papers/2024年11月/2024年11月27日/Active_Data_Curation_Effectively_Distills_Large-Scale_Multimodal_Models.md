# 主动的数据管理能够有效地提炼大规模的多模态模型

发布时间：2024年11月27日

`其他` `计算机视觉` `模型压缩`

> Active Data Curation Effectively Distills Large-Scale Multimodal Models

# 摘要

> 摘要：知识蒸馏（KD）已然成为将大规模模型压缩为较小模型的通行标准。此前的研究探索了愈发复杂的 KD 策略，涵盖不同的目标函数、教师集合以及权重继承。在本项工作中，我们探寻了一种别样却简单的途径——主动数据整理，作为对比多模态预训练的有效蒸馏手段。我们简便的在线批量选择方法 ACID，在各类模型、数据和计算配置下，表现均优于强劲的 KD 基线。而且，我们发现这种主动数据整理策略实际上与标准 KD 互为补充，能够有效结合以训练出高性能且推理高效的模型。我们简单且可扩展的预训练框架 ACED，在 27 个零样本分类和检索任务中达成了前沿成果，推理 FLOPs 最多减少 11％。我们进一步表明，我们的 ACED 模型在 LiT-Decoder 设定下为训练生成多模态模型产出了强大的视觉编码器，在图像字幕和视觉问答任务中胜过更大的视觉编码器。

> 
Abstract:Knowledge distillation (KD) is the de facto standard for compressing large-scale models into smaller ones. Prior works have explored ever more complex KD strategies involving different objective functions, teacher-ensembles, and weight inheritance. In this work we explore an alternative, yet simple approach -- active data curation as effective distillation for contrastive multimodal pretraining. Our simple online batch selection method, ACID, outperforms strong KD baselines across various model-, data- and compute-configurations. Further, we find such an active data curation strategy to in fact be complementary to standard KD, and can be effectively combined to train highly performant inference-efficient models. Our simple and scalable pretraining framework, ACED, achieves state-of-the-art results across 27 zero-shot classification and retrieval tasks with upto 11% less inference FLOPs. We further demonstrate that our ACED models yield strong vision-encoders for training generative multimodal models in the LiT-Decoder setting, outperforming larger vision encoders for image-captioning and visual question-answering tasks.
    

[Arxiv](https://arxiv.org/pdf/2411.18674)