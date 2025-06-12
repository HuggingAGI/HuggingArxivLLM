# TRACE：时间序列在上下文中的嵌入，用于多模态检索与表示

发布时间：2025年06月10日

`RAG` `跨领域` `跨模态`

> TRACE: Grounding Time Series in Context for Multimodal Embedding and Retrieval

# 摘要

> 动态数据在天气、医疗和能源等领域的普遍存在凸显了对时间序列数据有效解释和检索的迫切需求。这些数据与特定领域背景密切相关，例如临床笔记或天气叙述，因此跨模态检索不仅对下游任务至关重要，还对通过检索增强生成（RAG）构建稳健的时间序列基础模型不可或缺。尽管需求日益增长，时间序列检索仍鲜有探索。现有方法通常缺乏语义基础，难以对齐异构模态，且处理多通道信号的能力有限。为填补这一空白，我们提出TRACE，一个通用的多模态检索器，将时间序列嵌入与对齐的文本上下文相结合。TRACE支持精细的通道级别对齐，并采用硬负挖掘以促进语义有意义的检索。它支持灵活的跨模态检索模式，包括文本到时间序列和时间序列到文本，有效连接语言描述与复杂的时间模式。通过检索语义相关的配对，TRACE为下游模型提供丰富的上下文，从而提升预测准确性和可解释性。除了静态检索引擎，TRACE还作为强大的独立编码器，通过轻量级任务特定调整，优化上下文感知表示，同时保持强大的跨模态对齐。这些表示在下游预测和分类任务中达到最先进水平。跨多领域的大规模实验凸显了其双重实用性，既是下游应用的有效编码器，又是增强时间序列模型的通用检索器。

> The ubiquity of dynamic data in domains such as weather, healthcare, and energy underscores a growing need for effective interpretation and retrieval of time-series data. These data are inherently tied to domain-specific contexts, such as clinical notes or weather narratives, making cross-modal retrieval essential not only for downstream tasks but also for developing robust time-series foundation models by retrieval-augmented generation (RAG). Despite the increasing demand, time-series retrieval remains largely underexplored. Existing methods often lack semantic grounding, struggle to align heterogeneous modalities, and have limited capacity for handling multi-channel signals. To address this gap, we propose TRACE, a generic multimodal retriever that grounds time-series embeddings in aligned textual context. TRACE enables fine-grained channel-level alignment and employs hard negative mining to facilitate semantically meaningful retrieval. It supports flexible cross-modal retrieval modes, including Text-to-Timeseries and Timeseries-to-Text, effectively linking linguistic descriptions with complex temporal patterns. By retrieving semantically relevant pairs, TRACE enriches downstream models with informative context, leading to improved predictive accuracy and interpretability. Beyond a static retrieval engine, TRACE also serves as a powerful standalone encoder, with lightweight task-specific tuning that refines context-aware representations while maintaining strong cross-modal alignment. These representations achieve state-of-the-art performance on downstream forecasting and classification tasks. Extensive experiments across multiple domains highlight its dual utility, as both an effective encoder for downstream applications and a general-purpose retriever to enhance time-series models.

[Arxiv](https://arxiv.org/abs/2506.09114)