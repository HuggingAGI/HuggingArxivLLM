# LOVE：文本生成视频与视频理解的基准评测

发布时间：2025年05月17日

`LLM应用` `视频生成` `视频理解`

> LOVE: Benchmarking and Evaluating Text-to-Video Generation and Video-to-Text Interpretation

# 摘要

> # 摘要  
近年来，大型多模态模型（LMMs）的突破性进展推动了文本到视频（T2V）生成和视频到文本（V2T）理解任务的显著进步。然而，目前生成的AI视频（AIGVs）在感知质量和文图对齐方面仍存在明显局限。因此，开发一个可靠且可扩展的自动评估模型对于AIGV评估至关重要，这需要依赖大量高质量的人工标注。为此，我们推出了AIGVE-60K，一个全面的AI生成视频评估数据集和基准，具有以下特点：（i）全面的任务覆盖，包含20个细粒度任务维度下的3,050个广泛提示；（ii）最大规模的人工标注，包括针对30个T2V模型生成的58,500个视频所标注的120,000个平均意见评分（MOS）和60,000个问答对；（iii）对T2V生成和V2T理解能力的双向基准测试和评估。基于AIGVE-60K，我们提出了LOVE，一个基于LMM的多维度AI视频评估指标，从感知偏好、文图对应和任务特定准确性（涵盖实例级和模型级）等多个维度进行评估。 comprehensive experiments demonstrate that LOVE not only achieves state-of-the-art performance on the AIGVE-60K dataset, but also generalizes effectively to a wide range of other AIGV evaluation benchmarks. These findings highlight the significance of the AIGVE-60K dataset. Database and codes are anonymously available at https://github.com/IntMeGroup/LOVE.

> Recent advancements in large multimodal models (LMMs) have driven substantial progress in both text-to-video (T2V) generation and video-to-text (V2T) interpretation tasks. However, current AI-generated videos (AIGVs) still exhibit limitations in terms of perceptual quality and text-video alignment. Therefore, a reliable and scalable automatic model for AIGV evaluation is desirable, which heavily relies on the scale and quality of human annotations. To this end, we present AIGVE-60K, a comprehensive dataset and benchmark for AI-Generated Video Evaluation, which features (i) comprehensive tasks, encompassing 3,050 extensive prompts across 20 fine-grained task dimensions, (ii) the largest human annotations, including 120K mean-opinion scores (MOSs) and 60K question-answering (QA) pairs annotated on 58,500 videos generated from 30 T2V models, and (iii) bidirectional benchmarking and evaluating for both T2V generation and V2T interpretation capabilities. Based on AIGVE-60K, we propose LOVE, a LMM-based metric for AIGV Evaluation from multiple dimensions including perceptual preference, text-video correspondence, and task-specific accuracy in terms of both instance level and model level. Comprehensive experiments demonstrate that LOVE not only achieves state-of-the-art performance on the AIGVE-60K dataset, but also generalizes effectively to a wide range of other AIGV evaluation benchmarks. These findings highlight the significance of the AIGVE-60K dataset. Database and codes are anonymously available at https://github.com/IntMeGroup/LOVE.

[Arxiv](https://arxiv.org/abs/2505.12098)