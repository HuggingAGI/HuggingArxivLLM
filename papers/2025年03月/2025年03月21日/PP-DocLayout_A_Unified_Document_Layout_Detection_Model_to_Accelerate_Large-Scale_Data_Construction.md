# PP-DocLayout：统一文档布局检测模型，助力大规模数据高效构建

发布时间：2025年03月21日

`其他` `文档智能` `办公自动化`

> PP-DocLayout: A Unified Document Layout Detection Model to Accelerate Large-Scale Data Construction

# 摘要

> 文档布局分析是文档智能中的重要环节，能够精准识别标题、文本块、表格和公式等结构元素。尽管如此，现有布局检测模型在跨文档类型泛化、处理复杂布局以及实现大规模数据实时处理方面仍存在诸多挑战。为此，我们推出了PP-DocLayout，该模型在多种文档格式下实现了对23种布局区域的高精度和高效识别。为了满足不同需求，我们提供了三款不同规模的模型。PP-DocLayout-L是一款基于RT-DETR-L检测器的高精度模型，在T4 GPU上实现了90.4%的mAP@0.5和每页仅13.4毫秒的端到端推理速度。PP-DocLayout-M则是平衡性能与速度的全能型选手，在T4 GPU上实现了75.2%的mAP@0.5和每页12.7毫秒的推理时间。而PP-DocLayout-S则是专为资源受限环境和实时应用打造的高效模型，在T4 GPU上每页只需8.1毫秒，在CPU上也仅需14.5毫秒。这项研究不仅推动了文档布局分析技术的前沿发展，还为构建高质量训练数据提供了强大解决方案，从而助力文档智能和多模态AI系统的进一步突破。相关代码和模型已开源，访问https://github.com/PaddlePaddle/PaddleX即可获取。

> Document layout analysis is a critical preprocessing step in document intelligence, enabling the detection and localization of structural elements such as titles, text blocks, tables, and formulas. Despite its importance, existing layout detection models face significant challenges in generalizing across diverse document types, handling complex layouts, and achieving real-time performance for large-scale data processing. To address these limitations, we present PP-DocLayout, which achieves high precision and efficiency in recognizing 23 types of layout regions across diverse document formats. To meet different needs, we offer three models of varying scales. PP-DocLayout-L is a high-precision model based on the RT-DETR-L detector, achieving 90.4% mAP@0.5 and an end-to-end inference time of 13.4 ms per page on a T4 GPU. PP-DocLayout-M is a balanced model, offering 75.2% mAP@0.5 with an inference time of 12.7 ms per page on a T4 GPU. PP-DocLayout-S is a high-efficiency model designed for resource-constrained environments and real-time applications, with an inference time of 8.1 ms per page on a T4 GPU and 14.5 ms on a CPU. This work not only advances the state of the art in document layout analysis but also provides a robust solution for constructing high-quality training data, enabling advancements in document intelligence and multimodal AI systems. Code and models are available at https://github.com/PaddlePaddle/PaddleX .

[Arxiv](https://arxiv.org/abs/2503.17213)