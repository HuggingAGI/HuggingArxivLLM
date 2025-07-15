# 双轨配音：视频到配乐生成的联合语音与背景音频合成方法

发布时间：2025年07月14日

`LLM应用

摘要中提到的DualDub框架基于多模态语言模型，展示了大语言模型在视频处理任务中的具体应用，属于LLM的应用场景。` `视频处理` `音频处理`

> DualDub: Video-to-Soundtrack Generation via Joint Speech and Background Audio Synthesis

# 摘要

> 近期的视频到音频（V2A）模型虽然能从视觉输入生成逼真的背景音频，却忽视了语音这一视频音轨中的关键元素。为此，我们提出了视频到音轨（V2ST）生成这一新任务，旨在通过统一框架同步生成背景音频和语音。针对V2ST任务，我们开发了DualDub框架，基于多模态语言模型，整合了多模态编码器、跨模态对齐器及双解码头，实现背景音频与语音的同时生成。我们的跨模态对齐器采用了因果与非因果注意力机制，显著提升了同步效果和音频和谐性。此外，为解决数据不足问题，我们设计了一种渐进式课程学习策略，逐步增强多模态处理能力。最后，我们推出了DualBench，这是首个V2ST评估基准，包含精心挑选的测试集和全面的评估指标。实验结果表明，DualDub表现卓越，能够生成高质量且与视频完美同步的音轨，包含语音和背景音频。

> While recent video-to-audio (V2A) models can generate realistic background audio from visual input, they largely overlook speech, an essential part of many video soundtracks. This paper proposes a new task, video-to-soundtrack (V2ST) generation, which aims to jointly produce synchronized background audio and speech within a unified framework. To tackle V2ST, we introduce DualDub, a unified framework built on a multimodal language model that integrates a multimodal encoder, a cross-modal aligner, and dual decoding heads for simultaneous background audio and speech generation. Specifically, our proposed cross-modal aligner employs causal and non-causal attention mechanisms to improve synchronization and acoustic harmony. Besides, to handle data scarcity, we design a curriculum learning strategy that progressively builds the multimodal capability. Finally, we introduce DualBench, the first benchmark for V2ST evaluation with a carefully curated test set and comprehensive metrics. Experimental results demonstrate that DualDub achieves state-of-the-art performance, generating high-quality and well-synchronized soundtracks with both speech and background audio.

[Arxiv](https://arxiv.org/abs/2507.10109)