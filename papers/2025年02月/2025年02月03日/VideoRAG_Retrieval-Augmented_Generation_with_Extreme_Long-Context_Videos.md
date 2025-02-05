# VideoRAG: 检索增强生成技术在超长上下文视频中的应用

发布时间：2025年02月03日

`RAG

理由：这篇论文介绍了VideoRAG，一个专门为处理和理解超长视频设计的检索增强生成框架。该框架通过整合外部知识（特别是多模态视频知识）来提升大型语言模型的性能，属于检索增强生成（RAG）的应用范畴。因此，将其分类为RAG是合适的。` `视频处理` `多模态学习`

> VideoRAG: Retrieval-Augmented Generation with Extreme Long-Context Videos

# 摘要

> 检索增强生成（RAG）通过整合外部知识显著提升了大型语言模型（LLMs）的性能，但其应用多局限于文本领域，多模态视频知识的潜力尚未被充分挖掘。本文推出VideoRAG，首个专为处理和理解超长视频设计的检索增强生成框架。其核心创新在于双通道架构，无缝融合了（i）基于图的文本知识基础，捕捉跨视频语义关系，以及（ii）多模态上下文编码，高效保留视觉特征。这一设计使VideoRAG能够通过构建跨视频的精确知识图谱处理无限长度视频，同时通过多模态检索范式保持语义连贯。在我们提出的LongerVideos基准（包含160+视频，总计134+小时，涵盖讲座、纪录片和娱乐类别）上的全面评估显示，VideoRAG在性能上大幅超越现有RAG方案和长视频理解方法。VideoRAG的源代码和基准数据集已开源，详见：https://github.com/HKUDS/VideoRAG。

> Retrieval-Augmented Generation (RAG) has demonstrated remarkable success in enhancing Large Language Models (LLMs) through external knowledge integration, yet its application has primarily focused on textual content, leaving the rich domain of multi-modal video knowledge predominantly unexplored. This paper introduces VideoRAG, the first retrieval-augmented generation framework specifically designed for processing and understanding extremely long-context videos. Our core innovation lies in its dual-channel architecture that seamlessly integrates (i) graph-based textual knowledge grounding for capturing cross-video semantic relationships, and (ii) multi-modal context encoding for efficiently preserving visual features. This novel design empowers VideoRAG to process unlimited-length videos by constructing precise knowledge graphs that span multiple videos while maintaining semantic dependencies through specialized multi-modal retrieval paradigms. Through comprehensive empirical evaluation on our proposed LongerVideos benchmark-comprising over 160 videos totaling 134+ hours across lecture, documentary, and entertainment categories-VideoRAG demonstrates substantial performance compared to existing RAG alternatives and long video understanding methods. The source code of VideoRAG implementation and the benchmark dataset are openly available at: https://github.com/HKUDS/VideoRAG.

[Arxiv](https://arxiv.org/abs/2502.01549)