# Vidi：面向视频理解和编辑的大规模多模态模型

发布时间：2025年04月24日

`LLM应用` `视频处理` `视频编辑`

> Vidi: Large Multimodal Models for Video Understanding and Editing

# 摘要

> 人类天生就会与自己连接的人分享信息，而视频已经成为互联网上沟通和表达的主要方式之一。为了支持高质量大规模视频内容的创作，现代视频处理流程需要对原始素材（如未经剪辑的相机拍摄片段）和编辑组件（如视觉效果）有全面的理解。在视频编辑场景中，模型需要处理多种模态（如视觉、音频、文本）并结合强大的背景知识，同时还要应对灵活多变的输入长度（如长达数小时的原始视频），这对传统模型提出了巨大挑战。

本文中，我们介绍了Vidi——一个专注于广泛视频理解和编辑场景的大规模多模态模型（LMMs）家族。此次发布的版本专注于时间范围检索，即根据给定的文本查询在输入视频中识别对应的时间段，这对智能编辑至关重要。该模型具备强大的时间理解能力，能够处理长达数小时的视频，例如根据特定查询检索相应的时间段。

为了支持在真实场景中进行全面评估，我们还推出了VUE-TR基准测试，它带来了五大关键改进：
1）视频时长显著长于现有时间检索数据集；
2）支持音频查询；
3）多样化查询长度和格式；
4）标注质量：人工标注真实时间范围；
5）评估指标：采用优化后的IoU指标支持多时间段评估。

值得注意的是，Vidi在时间检索任务中显著超越了GPT-4o和Gemini等领先专用模型，展现了其在视频编辑场景中的卓越性能。


> Humans naturally share information with those they are connected to, and video has become one of the dominant mediums for communication and expression on the Internet. To support the creation of high-quality large-scale video content, a modern pipeline requires a comprehensive understanding of both the raw input materials (e.g., the unedited footage captured by cameras) and the editing components (e.g., visual effects). In video editing scenarios, models must process multiple modalities (e.g., vision, audio, text) with strong background knowledge and handle flexible input lengths (e.g., hour-long raw videos), which poses significant challenges for traditional models. In this report, we introduce Vidi, a family of Large Multimodal Models (LMMs) for a wide range of video understand editing scenarios. The first release focuses on temporal retrieval, i.e., identifying the time ranges within the input videos corresponding to a given text query, which plays a critical role in intelligent editing. The model is capable of processing hour-long videos with strong temporal understanding capability, e.g., retrieve time ranges for certain queries. To support a comprehensive evaluation in real-world scenarios, we also present the VUE-TR benchmark, which introduces five key advancements. 1) Video duration: significantly longer than videos of existing temporal retrival datasets, 2) Audio support: includes audio-based queries, 3) Query format: diverse query lengths/formats, 4) Annotation quality: ground-truth time ranges are manually annotated. 5) Evaluation metric: a refined IoU metric to support evaluation over multiple time ranges. Remarkably, Vidi significantly outperforms leading proprietary models, e.g., GPT-4o and Gemini, on the temporal retrieval task, indicating its superiority in video editing scenarios.

[Arxiv](https://arxiv.org/abs/2504.15681)