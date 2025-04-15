# FVQ：大型面部视频质量评估数据集及LMM方法

发布时间：2025年04月12日

`LLM应用` `视频处理` `社交媒体`

> FVQ: A Large-Scale Dataset and A LMM-based Method for Face Video Quality Assessment

# 摘要

> 除了通用视频质量评估（VQA），面部视频质量评估（FVQA）同样值得深入研究。这不仅因为面部视频是社交媒体的核心内容，更因为人类视觉系统（HVS）对人脸图像尤其敏感。然而，由于缺乏大规模FVQA数据集，这一领域的研究一直进展缓慢。为填补这一空白，我们推出了首个大规模真实场景FVQA数据集FVQ-20K，其中包含20,000个真实场景下的面部视频及其对应的平均意见分数（MOS）标注。

与FVQ-20K数据集一同，我们还提出了一种专门的FVQA方法FVQ-Rater，旨在实现对人脸视频的人类级别评分和打分。这是首次尝试探索大型多模态模型（LMMs）在FVQA任务中的潜力。具体来说，我们提取了多维度特征，包括空间特征、时间特征和特定于面部的特征（如人像特征和面部嵌入），以提供全面的视觉信息。同时，我们利用基于LoRA的指令微调技术实现特定质量的微调。实验结果表明，该方法在FVQ-20K和CFVQA数据集上均表现出色。

通过大量实验和全面分析，我们证明了FVQ-20K数据集和FVQ-Rater方法在推动FVQA领域发展方面具有巨大潜力。

> Face video quality assessment (FVQA) deserves to be explored in addition to general video quality assessment (VQA), as face videos are the primary content on social media platforms and human visual system (HVS) is particularly sensitive to human faces. However, FVQA is rarely explored due to the lack of large-scale FVQA datasets. To fill this gap, we present the first large-scale in-the-wild FVQA dataset, FVQ-20K, which contains 20,000 in-the-wild face videos together with corresponding mean opinion score (MOS) annotations. Along with the FVQ-20K dataset, we further propose a specialized FVQA method named FVQ-Rater to achieve human-like rating and scoring for face video, which is the first attempt to explore the potential of large multimodal models (LMMs) for the FVQA task. Concretely, we elaborately extract multi-dimensional features including spatial features, temporal features, and face-specific features (i.e., portrait features and face embeddings) to provide comprehensive visual information, and take advantage of the LoRA-based instruction tuning technique to achieve quality-specific fine-tuning, which shows superior performance on both FVQ-20K and CFVQA datasets. Extensive experiments and comprehensive analysis demonstrate the significant potential of the FVQ-20K dataset and FVQ-Rater method in promoting the development of FVQA.

[Arxiv](https://arxiv.org/abs/2504.09255)