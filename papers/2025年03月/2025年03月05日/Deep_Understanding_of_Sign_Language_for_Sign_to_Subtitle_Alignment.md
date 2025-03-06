# # 手语与字幕对齐的深度理解

发布时间：2025年03月05日

`其他` `计算机视觉`

> Deep Understanding of Sign Language for Sign to Subtitle Alignment

# 摘要

> 本研究旨在利用有限的标注数据，对含手语视频中的异步字幕进行精准对齐。为此，我们提出了一种创新性框架，主要贡献包括：(1) 基于英国手语（BSL）的基本语法规则对输入字幕进行预处理；(2) 设计了一种选择性对齐损失函数，用于优化模型仅在手语实际出现时预测其时间位置；(3) 采用基于优化伪标签的自训练方法，这些伪标签比传统的启发式音频对齐标签更准确。通过这些方法，我们的模型不仅能够更好地理解文本与手语之间的关联，还为手语翻译提供了新的可能性，特别是在大规模手语数据人工标注不切实际或具有挑战性的场景下。大量实验结果表明，我们的方法在帧级准确率和F1值方面均显著超越了现有基准模型，达到了当前最优水平。这充分展现了我们框架在推动手语视频对齐与翻译领域发展方面的有效性与实用性。

> The objective of this work is to align asynchronous subtitles in sign language videos with limited labelled data. To achieve this goal, we propose a novel framework with the following contributions: (1) we leverage fundamental grammatical rules of British Sign Language (BSL) to pre-process the input subtitles, (2) we design a selective alignment loss to optimise the model for predicting the temporal location of signs only when the queried sign actually occurs in a scene, and (3) we conduct self-training with refined pseudo-labels which are more accurate than the heuristic audio-aligned labels. From this, our model not only better understands the correlation between the text and the signs, but also holds potential for application in the translation of sign languages, particularly in scenarios where manual labelling of large-scale sign data is impractical or challenging. Extensive experimental results demonstrate that our approach achieves state-of-the-art results, surpassing previous baselines by substantial margins in terms of both frame-level accuracy and F1-score. This highlights the effectiveness and practicality of our framework in advancing the field of sign language video alignment and translation.

[Arxiv](https://arxiv.org/abs/2503.03287)