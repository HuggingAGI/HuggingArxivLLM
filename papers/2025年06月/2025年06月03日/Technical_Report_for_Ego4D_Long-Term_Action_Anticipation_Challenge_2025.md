# # **技术报告：Ego4D 长期行为预测挑战 2025**

发布时间：2025年06月03日

`LLM应用

摘要中提到，论文介绍了一种针对Ego4D长期动作预测任务的三阶段框架，其中使用了微调后的大型语言模型（LLM）来预测未来动作序列。这表明论文的重点在于将LLM应用于具体任务，因此归类为LLM应用。` `计算机视觉` `视频分析`

> Technical Report for Ego4D Long-Term Action Anticipation Challenge 2025

# 摘要

> 本报告介绍了一种针对 Ego4D 长期动作预测 (LTA) 任务的创新三阶段框架。受基础模型最新进展的启发，我们的方法分为特征提取、动作识别和长期动作预测三个阶段。首先，利用高性能视觉编码器提取视觉特征。接着，将特征输入 Transformer 预测动词和名词，并引入动词-名词共现矩阵提升识别精度。最后，将预测的动词-名词对格式化为文本提示，输入微调后的大型语言模型 (LLM) 预测未来动作序列。我们的框架在 CVPR 2025 的该挑战中摘得桂冠，树立了长期动作预测的新标杆。我们的代码将在 https://github.com/CorrineQiu/Ego4D-LTA-Challenge-2025 上开源。

> In this report, we present a novel three-stage framework developed for the Ego4D Long-Term Action Anticipation (LTA) task. Inspired by recent advances in foundation models, our method consists of three stages: feature extraction, action recognition, and long-term action anticipation. First, visual features are extracted using a high-performance visual encoder. The features are then fed into a Transformer to predict verbs and nouns, with a verb-noun co-occurrence matrix incorporated to enhance recognition accuracy. Finally, the predicted verb-noun pairs are formatted as textual prompts and input into a fine-tuned large language model (LLM) to anticipate future action sequences. Our framework achieves first place in this challenge at CVPR 2025, establishing a new state-of-the-art in long-term action prediction. Our code will be released at https://github.com/CorrineQiu/Ego4D-LTA-Challenge-2025.

[Arxiv](https://arxiv.org/abs/2506.02550)