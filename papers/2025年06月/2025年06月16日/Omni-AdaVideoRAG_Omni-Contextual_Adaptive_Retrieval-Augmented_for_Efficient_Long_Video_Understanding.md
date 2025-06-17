# # Omni-AdaVideoRAG: 全场景上下文自适应检索增强方法，用于高效长视频理解

发布时间：2025年06月16日

`RAG` `视频分析` `数据检索`

> Omni-AdaVideoRAG: Omni-Contextual Adaptive Retrieval-Augmented for Efficient Long Video Understanding

# 摘要

> 多模态大语言模型（MLLMs）在处理长视频时面临挑战，原因在于固定上下文窗口和较弱的长距离依赖建模能力。现有视频检索增强生成（RAG）方法采用静态检索策略，导致简单查询效率低下和复杂任务信息丢失。为解决这一问题，我们提出了AdaVideoRAG，一个基于轻量级意图分类器动态调整检索粒度的新型框架。通过Omni-Knowledge Indexing模块，我们利用文本（字幕、ASR、OCR）、视觉特征和语义图构建层次化数据库，实现跨任务资源的最优分配。同时，我们引入HiVU基准用于全面评估。实验表明，AdaVideoRAG在长视频理解方面显著提升了效率和准确度，并能无缝集成到现有MLLMs中。AdaVideoRAG为视频分析中的自适应检索确立了新范式。代码将在https://github.com/xzc-zju/AdaVideoRAG开源。

> Multimodal Large Language Models (MLLMs) struggle with long videos due to fixed context windows and weak long-term dependency modeling. Existing Retrieval-Augmented Generation (RAG) methods for videos use static retrieval strategies, leading to inefficiencies for simple queries and information loss for complex tasks. To address this, we propose AdaVideoRAG, a novel framework that dynamically adapts retrieval granularity based on query complexity using a lightweight intent classifier. Our framework employs an Omni-Knowledge Indexing module to build hierarchical databases from text (captions, ASR, OCR), visual features, and semantic graphs, enabling optimal resource allocation across tasks. We also introduce the HiVU benchmark for comprehensive evaluation. Experiments demonstrate improved efficiency and accuracy for long-video understanding, with seamless integration into existing MLLMs. AdaVideoRAG establishes a new paradigm for adaptive retrieval in video analysis. Codes will be open-sourced at https://github.com/xzc-zju/AdaVideoRAG.

[Arxiv](https://arxiv.org/abs/2506.13589)