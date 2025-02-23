# 基于大型语言模型的零样本面部情绪标注基准测试：日常生活中的多类与多帧方法

发布时间：2025年02月17日

`LLM应用

论文摘要：本研究探讨了在日常场景中利用大型语言模型（LLMs）自动标注人类情绪的可行性和性能表现。我们在公开的 FERV39k 数据集 DailyLife 子集上开展实验，采用 GPT-4o-mini 模型对视频片段中的关键帧进行快速零样本标注。在七类情绪分类体系下（"愤怒"、"厌恶"、"恐惧"、"快乐"、"中性"、"悲伤"、"惊讶"），模型达到了约 50% 的平均精度。当简化为三元情绪分类（负面/中性/正面）时，平均精度提升至约 64%。此外，我们还提出了一种通过整合 1-2 秒视频片段内多帧信息来提升标注精度并降低成本的策略。实验结果表明，该方法可小幅提高标注精度。总体而言，本研究初步揭示了零样本 LLM 在人类面部情绪标注任务中的应用潜力，为降低标注成本并拓展 LLM 在复杂多模态环境中的应用提供了新思路。

LLM应用` `情绪分析` `视频分析`

> Benchmarking Zero-Shot Facial Emotion Annotation with Large Language Models: A Multi-Class and Multi-Frame Approach in DailyLife

# 摘要

> 本研究探讨了在日常场景中利用大型语言模型（LLMs）自动标注人类情绪的可行性和性能表现。我们在公开的 FERV39k 数据集 DailyLife 子集上开展实验，采用 GPT-4o-mini 模型对视频片段中的关键帧进行快速零样本标注。在七类情绪分类体系下（"愤怒"、"厌恶"、"恐惧"、"快乐"、"中性"、"悲伤"、"惊讶"），模型达到了约 50% 的平均精度。当简化为三元情绪分类（负面/中性/正面）时，平均精度提升至约 64%。此外，我们还提出了一种通过整合 1-2 秒视频片段内多帧信息来提升标注精度并降低成本的策略。实验结果表明，该方法可小幅提高标注精度。总体而言，本研究初步揭示了零样本 LLM 在人类面部情绪标注任务中的应用潜力，为降低标注成本并拓展 LLM 在复杂多模态环境中的应用提供了新思路。

> This study investigates the feasibility and performance of using large language models (LLMs) to automatically annotate human emotions in everyday scenarios. We conducted experiments on the DailyLife subset of the publicly available FERV39k dataset, employing the GPT-4o-mini model for rapid, zero-shot labeling of key frames extracted from video segments. Under a seven-class emotion taxonomy ("Angry," "Disgust," "Fear," "Happy," "Neutral," "Sad," "Surprise"), the LLM achieved an average precision of approximately 50%. In contrast, when limited to ternary emotion classification (negative/neutral/positive), the average precision increased to approximately 64%. Additionally, we explored a strategy that integrates multiple frames within 1-2 second video clips to enhance labeling performance and reduce costs. The results indicate that this approach can slightly improve annotation accuracy. Overall, our preliminary findings highlight the potential application of zero-shot LLMs in human facial emotion annotation tasks, offering new avenues for reducing labeling costs and broadening the applicability of LLMs in complex multimodal environments.

[Arxiv](https://arxiv.org/abs/2502.12454)