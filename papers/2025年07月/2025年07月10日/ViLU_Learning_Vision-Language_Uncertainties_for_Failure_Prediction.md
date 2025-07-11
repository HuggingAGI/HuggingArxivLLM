# # 摘要  
ViLU: 学习视觉语言不确定性用于故障预测  
ViLU: 学习视觉语言不确定性用于故障预测

发布时间：2025年07月10日

`LLM应用` `计算机视觉` `视觉语言模型`

> ViLU: Learning Vision-Language Uncertainties for Failure Prediction

# 摘要

> 可靠的不确定性量化（UQ）和故障预测是视觉语言模型（VLMs）领域尚未解决的关键挑战。我们推出ViLU——一个全新的视觉语言不确定性量化框架，它通过整合所有与任务相关的文本表示来实现更精准的不确定性估计。ViLU采用交叉注意力机制，将视觉嵌入、预测的文本嵌入和基于图像条件的文本表示相结合，构建了一个具备不确定性感知的多模态表示。与传统基于损失预测的UQ方法不同，ViLU创新性地将不确定性预测器训练为一个二元分类器，通过加权二元交叉熵损失来区分正确与错误预测，从而实现了损失不可知性。特别值得一提的是，我们的方法非常适合后验场景，即仅在拥有视觉和文本嵌入的情况下使用，而无需直接访问模型本身。在ImageNet-1k等标准分类数据集以及CC12M和LAION-400M等大规模图像-文本数据集上的广泛实验表明，我们的方法相较于现有最先进的故障预测方法具有显著优势。通过消融实验，我们进一步验证了我们的架构和训练方法在实现有效不确定性量化中的关键作用。我们的代码已开源，并可在此处获取：https://github.com/ykrmm/ViLU。

> Reliable Uncertainty Quantification (UQ) and failure prediction remain open challenges for Vision-Language Models (VLMs). We introduce ViLU, a new Vision-Language Uncertainty quantification framework that contextualizes uncertainty estimates by leveraging all task-relevant textual representations. ViLU constructs an uncertainty-aware multi-modal representation by integrating the visual embedding, the predicted textual embedding, and an image-conditioned textual representation via cross-attention. Unlike traditional UQ methods based on loss prediction, ViLU trains an uncertainty predictor as a binary classifier to distinguish correct from incorrect predictions using a weighted binary cross-entropy loss, making it loss-agnostic. In particular, our proposed approach is well-suited for post-hoc settings, where only vision and text embeddings are available without direct access to the model itself. Extensive experiments on diverse datasets show the significant gains of our method compared to state-of-the-art failure prediction methods. We apply our method to standard classification datasets, such as ImageNet-1k, as well as large-scale image-caption datasets like CC12M and LAION-400M. Ablation studies highlight the critical role of our architecture and training in achieving effective uncertainty quantification. Our code is publicly available and can be found here: https://github.com/ykrmm/ViLU.

[Arxiv](https://arxiv.org/abs/2507.07620)