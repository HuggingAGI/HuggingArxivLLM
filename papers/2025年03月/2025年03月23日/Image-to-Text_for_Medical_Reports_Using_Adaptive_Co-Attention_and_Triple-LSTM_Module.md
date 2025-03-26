# # 标题  
基于自适应协同注意力与三重LSTM模块的医学报告图像转文本方法

发布时间：2025年03月23日

`LLM应用` `多模态`

> Image-to-Text for Medical Reports Using Adaptive Co-Attention and Triple-LSTM Module

# 摘要

> 医学报告生成需要专业的专业知识，而通用大型模型往往难以准确捕捉。此外，医学数据中固有的重复性和相似性使得模型难以提取有意义的特征，容易导致过拟合。因此，在本文中，我们提出了一种多模态模型——协同注意力三重LSTM网络（CA-TriNet）。该模型结合了Transformer架构和多LSTM网络，通过协同注意力模块将视觉Transformer与文本Transformer协同工作，以更好地区分具有相似性的医学图像。借助自适应权重操作符，该模块能够捕捉并放大具有微小相似性的图像标签。此外，其三重LSTM模块利用目标图像对象来优化生成的句子。在三个公共数据集上的广泛评估表明，CA-TriNet在综合能力上优于最先进的模型，甚至在某些指标上优于预训练的大型语言模型。

> Medical report generation requires specialized expertise that general large models often fail to accurately capture. Moreover, the inherent repetition and similarity in medical data make it difficult for models to extract meaningful features, resulting in a tendency to overfit. So in this paper, we propose a multimodal model, Co-Attention Triple-LSTM Network (CA-TriNet), a deep learning model that combines transformer architectures with a Multi-LSTM network. Its Co-Attention module synergistically links a vision transformer with a text transformer to better differentiate medical images with similarities, augmented by an adaptive weight operator to catch and amplify image labels with minor similarities. Furthermore, its Triple-LSTM module refines generated sentences using targeted image objects. Extensive evaluations over three public datasets have demonstrated that CA-TriNet outperforms state-of-the-art models in terms of comprehensive ability, even pre-trained large language models on some metrics.

[Arxiv](https://arxiv.org/abs/2503.18297)