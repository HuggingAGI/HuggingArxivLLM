# 质量胜于数量？LLM驱动的内容精选，构建数据高效型的音视频基础模型

发布时间：2025年03月12日

`LLM应用` `媒体处理` `机器学习`

> Quality Over Quantity? LLM-Based Curation for a Data-Efficient Audio-Video Foundation Model

# 摘要

> 在多模态基础模型的训练中，整合音频与视觉数据仍是一项具有挑战性的任务。我们提出了一种名为音频-视频向量对齐（AVVA）的方法，该方法通过基于大型语言模型（LLM）的数据整理管道，实现了对视听场景内容的深度对齐，超越了简单的时序同步。具体而言，AVVA在双编码器对比学习框架下，利用Whisper（基于语音的音频基础模型）处理音频，以及DINOv2处理视频，对训练片段进行评分和筛选。在AudioCaps、VALOR和VGGSound上的评估表明，与未经整理的数据相比，AVVA能够以大幅减少的数据量实现显著的准确率提升。例如，在VGGSound上，AVVA在音频到视频检索的top-1准确率上比ImageBind提升了7.6%，尽管其训练数据仅为192小时经过精心筛选的数据（相比之下ImageBind使用了5800+小时的数据）。此外，通过消融研究发现，用数据质量换取数据数量能够显著提升性能，在AudioCaps、VALOR和VGGSound上分别比未经整理的基线模型提升了47.8、48.4和58.0的top-3准确率百分点。虽然这些结果凸显了AVVA的数据高效性，但我们同时也探讨了LLM驱动的数据整理带来的额外开销，以及如何在更大规模的数据集上进行扩展或近似。总体而言，AVVA为实现更强大、无需文本的视听学习提供了一条可行路径，同时显著提升了检索准确性。


> Integrating audio and visual data for training multimodal foundational models remains challenging. We present Audio-Video Vector Alignment (AVVA), which aligns audiovisual (AV) scene content beyond mere temporal synchronization via a Large Language Model (LLM)-based data curation pipeline. Specifically, AVVA scores and selects high-quality training clips using Whisper (speech-based audio foundation model) for audio and DINOv2 for video within a dual-encoder contrastive learning framework. Evaluations on AudioCaps, VALOR, and VGGSound demonstrate that this approach can achieve significant accuracy gains with substantially less curated data. For instance, AVVA yields a 7.6% improvement in top-1 accuracy for audio-to-video retrieval on VGGSound compared to ImageBind, despite training on only 192 hours of carefully filtered data (vs. 5800+ hours). Moreover, an ablation study highlights that trading data quantity for data quality improves performance, yielding respective top-3 accuracy increases of 47.8, 48.4, and 58.0 percentage points on AudioCaps, VALOR, and VGGSound over uncurated baselines. While these results underscore AVVA's data efficiency, we also discuss the overhead of LLM-driven curation and how it may be scaled or approximated in larger domains. Overall, AVVA provides a viable path toward more robust, text-free audiovisual learning with improved retrieval accuracy.

[Arxiv](https://arxiv.org/abs/2503.09205)