# 用于弱监督视频异常检测的跨模态融合与注意力机制

发布时间：2024年12月29日

`其他` `视频检测` `异常检测`

> Cross-Modal Fusion and Attention Mechanism for Weakly Supervised Video Anomaly Detection

# 摘要

> 最近，弱监督视频异常检测（WS-VAD）成为了当代的一个研究方向，其仅依靠视频级标签就能识别视频中的暴力、裸体等异常事件。不过，此任务面临诸多重大挑战，比如解决模态信息不均衡以及持续区分正常与异常特征。在本文中，我们直面这些挑战，提出了一个多模态的WS-VAD框架，用于精准检测像暴力和裸体这样的异常情况。在该框架内，我们引入了一种名为跨模态融合适配器（CFA）的新融合机制，它能动态选择并增强与视觉模态高度相关的视听特征。另外，我们还引入了双曲洛伦兹图注意力（HLGAtt），有效捕捉正常和异常表示之间的层次关系，进而提高特征分离的准确性。通过大量实验，我们表明所提出的模型在暴力和裸体检测的基准数据集上取得了领先的成果。

> Recently, weakly supervised video anomaly detection (WS-VAD) has emerged as a contemporary research direction to identify anomaly events like violence and nudity in videos using only video-level labels. However, this task has substantial challenges, including addressing imbalanced modality information and consistently distinguishing between normal and abnormal features. In this paper, we address these challenges and propose a multi-modal WS-VAD framework to accurately detect anomalies such as violence and nudity. Within the proposed framework, we introduce a new fusion mechanism known as the Cross-modal Fusion Adapter (CFA), which dynamically selects and enhances highly relevant audio-visual features in relation to the visual modality. Additionally, we introduce a Hyperbolic Lorentzian Graph Attention (HLGAtt) to effectively capture the hierarchical relationships between normal and abnormal representations, thereby enhancing feature separation accuracy. Through extensive experiments, we demonstrate that the proposed model achieves state-of-the-art results on benchmark datasets of violence and nudity detection.

[Arxiv](https://arxiv.org/abs/2412.20455)