# Vid-SME：针对大型视频理解模型的成员推断攻击研究

发布时间：2025年05月29日

`LLM应用` `视频数据` `隐私保护`

> Vid-SME: Membership Inference Attacks against Large Video Understanding Models

# 摘要

> 多模态大型语言模型（MLLMs）在复杂多模态任务中表现卓越，尤其在视频理解领域得到了广泛应用。然而，其快速发展引发了数据隐私问题，尤其是训练数据中可能包含个人录像和监控录像等敏感视频内容。在训练过程中识别不当使用的视频仍是一个关键且未解决的挑战。

尽管文本和图像数据的成员推断攻击（MIAs）取得了显著进展，但现有方法未能有效推广到视频领域。这些方法在处理更多帧时面临扩展性问题，并且在低假阳性率下通常只能实现微不足道的真正阳性率，这主要是因为它们未能捕捉到视频帧的时间变化，也未能考虑到帧数变化时模型行为的差异。

为了解决这些挑战，我们提出了Vid-SME，这是首个专门针对视频理解语言模型（VULLMs）的视频数据成员推断方法。Vid-SME通过模型输出置信度和自适应参数化计算视频输入的Sharma-Mittal熵（SME）。通过分析自然视频帧与时间反转视频帧之间的SME差异，Vid-SME能够生成稳健的成员评分，从而判断给定视频是否属于模型的训练集。

实验结果表明，Vid-SME在各种自训练和开源的VULLMs上表现出色，证明了其有效性。

> Multimodal large language models (MLLMs) demonstrate remarkable capabilities in handling complex multimodal tasks and are increasingly adopted in video understanding applications. However, their rapid advancement raises serious data privacy concerns, particularly given the potential inclusion of sensitive video content, such as personal recordings and surveillance footage, in their training datasets. Determining improperly used videos during training remains a critical and unresolved challenge. Despite considerable progress on membership inference attacks (MIAs) for text and image data in MLLMs, existing methods fail to generalize effectively to the video domain. These methods suffer from poor scalability as more frames are sampled and generally achieve negligible true positive rates at low false positive rates (TPR@Low FPR), mainly due to their failure to capture the inherent temporal variations of video frames and to account for model behavior differences as the number of frames varies. To address these challenges, we introduce Vid-SME, the first membership inference method tailored for video data used in video understanding LLMs (VULLMs). Vid-SME leverages the confidence of model output and integrates adaptive parameterization to compute Sharma-Mittal entropy (SME) for video inputs. By leveraging the SME difference between natural and temporally-reversed video frames, Vid-SME derives robust membership scores to determine whether a given video is part of the model's training set. Experiments on various self-trained and open-sourced VULLMs demonstrate the strong effectiveness of Vid-SME.

[Arxiv](https://arxiv.org/abs/2506.03179)