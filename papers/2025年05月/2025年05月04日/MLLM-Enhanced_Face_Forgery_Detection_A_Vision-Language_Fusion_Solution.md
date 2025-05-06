# MLLM增强的面部伪造检测：一种视觉与语言融合的解决方案

发布时间：2025年05月04日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在面部伪造检测中的应用，提出了一种新的视觉语言融合解决方案，并展示了其在实际任务中的有效性。因此，它属于LLM应用类别。` `计算机视觉` `深度伪造`

> MLLM-Enhanced Face Forgery Detection: A Vision-Language Fusion Solution

# 摘要

> # 摘要
面部伪造检测算法在抵御深度伪造技术带来的虚假信息威胁中至关重要。研究发现，多模态大型语言模型（MLLMs）在识别面部篡改方面具有潜力。然而，现有方法往往仅依赖大型语言模型（LLM）或外部检测器，导致视觉与文本模态整合效果不佳。本研究提出了一种名为VLF-FFD的新型视觉语言融合解决方案，旨在提升MLLM的面部伪造检测能力。

我们的主要贡献包括：
1. 推出了EFF++，这是在FaceForensics++（FF++）数据集上的帧级扩展版本。每个篡改视频帧都配有描述伪造痕迹和篡改技术的文本注释，为MLLM训练提供了更丰富、更有信息量的数据。
2. 设计了视觉语言融合网络（VLF-Net），通过三阶段训练管道实现了视觉与文本特征的双向互动，充分发挥模型潜力。

实验结果表明，VLF-FFD在跨数据集和数据集内部评估中均达到了最先进（SOTA）水平，充分证明了其在面部伪造检测中的卓越效果。


> Reliable face forgery detection algorithms are crucial for countering the growing threat of deepfake-driven disinformation. Previous research has demonstrated the potential of Multimodal Large Language Models (MLLMs) in identifying manipulated faces. However, existing methods typically depend on either the Large Language Model (LLM) alone or an external detector to generate classification results, which often leads to sub-optimal integration of visual and textual modalities. In this paper, we propose VLF-FFD, a novel Vision-Language Fusion solution for MLLM-enhanced Face Forgery Detection. Our key contributions are twofold. First, we present EFF++, a frame-level, explainability-driven extension of the widely used FaceForensics++ (FF++) dataset. In EFF++, each manipulated video frame is paired with a textual annotation that describes both the forgery artifacts and the specific manipulation technique applied, enabling more effective and informative MLLM training. Second, we design a Vision-Language Fusion Network (VLF-Net) that promotes bidirectional interaction between visual and textual features, supported by a three-stage training pipeline to fully leverage its potential. VLF-FFD achieves state-of-the-art (SOTA) performance in both cross-dataset and intra-dataset evaluations, underscoring its exceptional effectiveness in face forgery detection.

[Arxiv](https://arxiv.org/abs/2505.02013)