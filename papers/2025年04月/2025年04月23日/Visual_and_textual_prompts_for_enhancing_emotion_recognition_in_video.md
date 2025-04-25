# 提升视频情绪识别的视觉与文本提示

发布时间：2025年04月23日

`LLM应用` `视频分析` `情感识别`

> Visual and textual prompts for enhancing emotion recognition in video

# 摘要

> 视觉大型语言模型（VLLMs）在多模态理解方面潜力巨大，但视频情感识别能力受限于空间和上下文感知不足。传统方法专注于孤立面部特征提取，往往忽视肢体语言、环境背景及社交互动等关键非语言线索，导致实际应用中的鲁棒性不足。为解决这一问题，我们提出了一种名为视觉-文本提示集框架（Set-of-Vision-Text Prompting, SoVTP）的创新方案。该框架通过整合空间标注（如边界框、面部关键点）、生理信号（面部动作单元）及情境线索（肢体姿态、场景动态、他人情绪）等多维度信息，形成统一的提示策略，显著提升零样本情感识别能力。SoVTP不仅保留了整体场景信息，还实现了面部肌肉运动及人际互动的精细化分析。大量实验结果表明，相较于现有视觉提示方法，SoVTP在视频情感识别任务中取得了显著提升，充分证明了其对增强VLLMs视频情感识别能力的有效性。

> Vision Large Language Models (VLLMs) exhibit promising potential for multi-modal understanding, yet their application to video-based emotion recognition remains limited by insufficient spatial and contextual awareness. Traditional approaches, which prioritize isolated facial features, often neglect critical non-verbal cues such as body language, environmental context, and social interactions, leading to reduced robustness in real-world scenarios. To address this gap, we propose Set-of-Vision-Text Prompting (SoVTP), a novel framework that enhances zero-shot emotion recognition by integrating spatial annotations (e.g., bounding boxes, facial landmarks), physiological signals (facial action units), and contextual cues (body posture, scene dynamics, others' emotions) into a unified prompting strategy. SoVTP preserves holistic scene information while enabling fine-grained analysis of facial muscle movements and interpersonal dynamics. Extensive experiments show that SoVTP achieves substantial improvements over existing visual prompting methods, demonstrating its effectiveness in enhancing VLLMs' video emotion recognition capabilities.

[Arxiv](https://arxiv.org/abs/2504.17224)