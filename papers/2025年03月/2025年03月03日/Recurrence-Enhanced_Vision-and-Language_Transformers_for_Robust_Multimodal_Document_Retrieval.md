# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月03日

`LLM应用` `计算机视觉` `信息检索`

> Recurrence-Enhanced Vision-and-Language Transformers for Robust Multimodal Document Retrieval

# 摘要

> 跨模态检索正逐渐展现出强大的效果和吸引力，这得益于大规模训练、新颖的架构设计与学习策略，以及其在大语言模型（LLMs）和多模态 LLMs 中的应用。本文更进一步，设计了一种支持多模态查询的方法，查询由图像和文本共同组成，能够在包含图像和文本相互交织的多模态文档集合中进行搜索。我们的模型 ReT 从视觉和文本主干的不同层中提取多级表示，应用于查询和文档两侧。为了实现多级和跨模态的理解与特征提取，ReT 采用了一种基于 Transformer 的新型递归单元，整合了不同层的文本和视觉特征，并借鉴 LSTM 的经典设计引入了 sigmoid 门控机制。在 M2KR 和 M-BEIR 基准测试上的大量实验表明，ReT 在各种设置下均达到了最先进的性能。我们的源代码和训练好的模型已在 https://github.com/aimagelab/ReT 上公开发布。


> Cross-modal retrieval is gaining increasing efficacy and interest from the research community, thanks to large-scale training, novel architectural and learning designs, and its application in LLMs and multimodal LLMs. In this paper, we move a step forward and design an approach that allows for multimodal queries, composed of both an image and a text, and can search within collections of multimodal documents, where images and text are interleaved. Our model, ReT, employs multi-level representations extracted from different layers of both visual and textual backbones, both at the query and document side. To allow for multi-level and cross-modal understanding and feature extraction, ReT employs a novel Transformer-based recurrent cell that integrates both textual and visual features at different layers, and leverages sigmoidal gates inspired by the classical design of LSTMs. Extensive experiments on M2KR and M-BEIR benchmarks show that ReT achieves state-of-the-art performance across diverse settings. Our source code and trained models are publicly available at https://github.com/aimagelab/ReT.

[Arxiv](https://arxiv.org/abs/2503.01980)