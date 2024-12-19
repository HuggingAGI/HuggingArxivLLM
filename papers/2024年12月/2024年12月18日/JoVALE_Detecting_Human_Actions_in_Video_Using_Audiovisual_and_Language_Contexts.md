# JoVALE：借助视听和语言情境检测视频中的人类行为

发布时间：2024年12月18日

`其他` `视频处理` `动作检测`

> JoVALE: Detecting Human Actions in Video Using Audiovisual and Language Contexts

# 摘要

> 视频动作检测（VAD）旨在对视频中的动作实例进行定位和分类。视频天然蕴含着多种信息源，像音频、视觉线索以及周边场景的上下文等。要有效地利用这种多模态信息来进行 VAD 颇具挑战，因为模型得精准聚焦于与动作相关的线索。在本研究中，我们推出了一种新颖的多模态 VAD 架构，名为以演员为中心的联合视觉、音频、语言编码器（JoVALE）。JoVALE 是首个将音频和视觉特征与源自大型图像字幕模型的场景描述上下文相融合的 VAD 方法。JoVALE 的核心在于以演员为中心对音频、视觉和场景描述上下文进行聚合，从中识别并自适应组合来自每种模态的动作相关线索。我们提出了一个名为以演员为中心的多模态融合网络的专门模块，旨在通过 Transformer 架构捕捉演员与多模态上下文之间的联合交互。我们在三个热门的 VAD 基准——AVA、UCF101-24 和 JHMDB51-21 上开展的评估表明，融入多模态信息能带来显著的性能提升。JoVALE 达到了最先进的性能水平。代码将在 	exttt{https://github.com/taeiin/AAAI2025-JoVALE} 上提供。

> Video Action Detection (VAD) involves localizing and categorizing action instances in videos. Videos inherently contain various information sources, including audio, visual cues, and surrounding scene contexts. Effectively leveraging this multi-modal information for VAD is challenging, as the model must accurately focus on action-relevant cues. In this study, we introduce a novel multi-modal VAD architecture called the Joint Actor-centric Visual, Audio, Language Encoder (JoVALE). JoVALE is the first VAD method to integrate audio and visual features with scene descriptive context derived from large image captioning models. The core principle of JoVALE is the actor-centric aggregation of audio, visual, and scene descriptive contexts, where action-related cues from each modality are identified and adaptively combined. We propose a specialized module called the Actor-centric Multi-modal Fusion Network, designed to capture the joint interactions among actors and multi-modal contexts through Transformer architecture. Our evaluation conducted on three popular VAD benchmarks, AVA, UCF101-24, and JHMDB51-21, demonstrates that incorporating multi-modal information leads to significant performance gains. JoVALE achieves state-of-the-art performances. The code will be available at \texttt{https://github.com/taeiin/AAAI2025-JoVALE}.

[Arxiv](https://arxiv.org/abs/2412.13708)