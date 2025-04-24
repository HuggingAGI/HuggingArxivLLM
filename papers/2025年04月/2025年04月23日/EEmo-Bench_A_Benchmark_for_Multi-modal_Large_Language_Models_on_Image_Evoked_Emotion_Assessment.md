# EEmo-Bench：评估多模态大型语言模型图像诱发情感能力的基准.

发布时间：2025年04月23日

`LLM应用` `人机交互` `广告推荐`

> EEmo-Bench: A Benchmark for Multi-modal Large Language Models on Image Evoked Emotion Assessment

# 摘要

> 多模态大型语言模型（MLLMs）的发展催生了大量基准研究，特别是在评估其感知与理解能力方面。其中，图像引发情绪的理解研究尤为突出，它旨在提升MLLMs的共情能力，在人机交互和广告推荐等领域具有重要应用价值。然而，目前针对这一能力的评估仍显粗放，缺乏系统性和全面性的评估体系。为此，我们推出了EEmo-Bench，一个专注于分析不同内容类别图像引发情绪的新基准。我们的主要贡献包括：1) 在引发情绪的多样性方面，我们采用了情绪排名策略，并以效价-唤醒-优势（VAD）作为情绪属性进行评估。据此，我们收集并手动标注了1960张图像。2) 我们设计了四项任务来评估MLLMs捕捉单张图像及其属性所引发情绪的能力：感知、排名、描述和评估。此外，我们引入了图像配对分析，以探究模型在联合分析和对比分析方面的表现。总共，我们收集了6773对问答，并对19个常用MLLM进行了全面评估。结果显示，尽管部分专有和开源MLLM在整体性能上表现优异，但在某些评估维度的分析能力仍有提升空间。我们的EEmo-Bench为未来研究奠定了基础，旨在提升MLLMs对图像引发情绪的全面感知与理解能力，这对机器中心的情绪感知与理解至关重要。

> The furnishing of multi-modal large language models (MLLMs) has led to the emergence of numerous benchmark studies, particularly those evaluating their perception and understanding capabilities.
  Among these, understanding image-evoked emotions aims to enhance MLLMs' empathy, with significant applications such as human-machine interaction and advertising recommendations. However, current evaluations of this MLLM capability remain coarse-grained, and a systematic and comprehensive assessment is still lacking.
  To this end, we introduce EEmo-Bench, a novel benchmark dedicated to the analysis of the evoked emotions in images across diverse content categories.
  Our core contributions include:
  1) Regarding the diversity of the evoked emotions, we adopt an emotion ranking strategy and employ the Valence-Arousal-Dominance (VAD) as emotional attributes for emotional assessment. In line with this methodology, 1,960 images are collected and manually annotated.
  2) We design four tasks to evaluate MLLMs' ability to capture the evoked emotions by single images and their associated attributes: Perception, Ranking, Description, and Assessment. Additionally, image-pairwise analysis is introduced to investigate the model's proficiency in performing joint and comparative analysis.
  In total, we collect 6,773 question-answer pairs and perform a thorough assessment on 19 commonly-used MLLMs.
  The results indicate that while some proprietary and large-scale open-source MLLMs achieve promising overall performance, the analytical capabilities in certain evaluation dimensions remain suboptimal.
  Our EEmo-Bench paves the path for further research aimed at enhancing the comprehensive perceiving and understanding capabilities of MLLMs concerning image-evoked emotions, which is crucial for machine-centric emotion perception and understanding.

[Arxiv](https://arxiv.org/abs/2504.16405)