# 利用大型语言模型（LLMs）进行多模态传感器后期融合以实现活动识别

发布时间：2025年09月12日

`LLM应用` `工业与制造`

> Using LLMs for Late Multimodal Sensor Fusion for Activity Recognition

# 摘要

> 传感器数据流蕴含着下游应用所需的活动与上下文关键信息，但整合互补信息却颇具难度。研究发现，大型语言模型（LLMs）可实现音频与运动时间序列数据的活动分类后期融合。我们从Ego4D数据集中精选了部分数据，以支持跨场景（如家庭活动、体育运动）的多样化活动识别。实验评估的LLMs在12类零样本和单样本分类任务中，F1分数显著高于随机水平，且无需任何特定任务训练。借助基于LLM的模态特定模型融合实现零样本分类，能够支持多模态时序应用，尤其适用于学习共享嵌入空间时对齐训练数据稀缺的场景。此外，基于LLM的融合还能简化模型部署流程，无需为特定应用场景的多模态模型额外分配内存与计算资源。

> Sensor data streams provide valuable information around activities and context for downstream applications, though integrating complementary information can be challenging. We show that large language models (LLMs) can be used for late fusion for activity classification from audio and motion time series data. We curated a subset of data for diverse activity recognition across contexts (e.g., household activities, sports) from the Ego4D dataset. Evaluated LLMs achieved 12-class zero- and one-shot classification F1-scores significantly above chance, with no task-specific training. Zero-shot classification via LLM-based fusion from modality-specific models can enable multimodal temporal applications where there is limited aligned training data for learning a shared embedding space. Additionally, LLM-based fusion can enable model deploying without requiring additional memory and computation for targeted application-specific multimodal models.

[Arxiv](https://arxiv.org/abs/2509.10729)