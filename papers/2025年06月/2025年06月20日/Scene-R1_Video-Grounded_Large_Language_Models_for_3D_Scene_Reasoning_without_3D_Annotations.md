# # Scene-R1：无需三维标注的视频 grounding 大型语言模型，用于三维场景推理

发布时间：2025年06月20日

`LLM应用` `计算机视觉` `人工智能`

> Scene-R1: Video-Grounded Large Language Models for 3D Scene Reasoning without 3D Annotations

# 摘要

> 如今，利用大型语言模型理解三维世界日益流行。然而，现有的3D感知大型语言模型（LLMs）如同黑箱：它们输出边界框或文本答案，却无法揭示决策过程，仍依赖预训练的3D检测器提供目标建议。我们推出Scene-R1——一个基于视频的框架，通过结合强化学习驱动的推理与两阶段定位管道，在无需任何逐点3D实例监督的情况下学习推理3D场景。在时间定位阶段，我们明确分析视频内容，挑选与开放性查询最相关的片段。随后的图像定位阶段，我们解析图像，预测2D边界框。之后，借助SAM2追踪目标，在RGB帧中生成像素级精确的掩膜，并将其投影回3D空间，从而摆脱对3D检测器建议的依赖，同时捕捉精细的几何和材质特征。Scene-R1还可应用于3D视觉问答任务，直接从视频中回答自由形式的问题。我们的训练管道仅需任务级的2D边界框或文本标签，无需密集的3D逐点标注。Scene-R1在多个数据集上超越了现有的开放词汇基线，同时提供透明、逐步的推理过程。这些结果表明，基于强化学习的推理与仅使用RGB-D视频相结合，为可信的3D场景理解提供了一条实用且标注高效的途径。

> Currently, utilizing large language models to understand the 3D world is becoming popular. Yet existing 3D-aware LLMs act as black boxes: they output bounding boxes or textual answers without revealing how those decisions are made, and they still rely on pre-trained 3D detectors to supply object proposals. We introduce Scene-R1, a video-grounded framework that learns to reason about 3D scenes without any point-wise 3D instance supervision by pairing reinforcement-learning-driven reasoning with a two-stage grounding pipeline. In the temporal grounding stage, we explicitly reason about the video and select the video snippets most relevant to an open-ended query. In the subsequent image grounding stage, we analyze the image and predict the 2D bounding box. After that, we track the object using SAM2 to produce pixel-accurate masks in RGB frames, and project them back into 3D, thereby eliminating the need for 3D detector-based proposals while capturing fine geometry and material cues. Scene-R1 can also adapt to the 3D visual question answering task to answer free-form questions directly from video. Our training pipeline only needs task-level 2D boxes or textual labels without dense 3D point-wise labels. Scene-R1 surpasses existing open-vocabulary baselines on multiple datasets, while delivering transparent, step-by-step rationales. These results show that reinforcement-learning-based reasoning combined with RGB-D video alone offers a practical, annotation-efficient route to trustworthy 3D scene understanding.

[Arxiv](https://arxiv.org/abs/2506.17545)