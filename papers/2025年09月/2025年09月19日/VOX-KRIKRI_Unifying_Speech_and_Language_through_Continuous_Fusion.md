# VOX-KRIKRI：通过持续融合实现语音与语言的统一

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> VOX-KRIKRI: Unifying Speech and Language through Continuous Fusion

# 摘要

> 我们提出了一种多模态融合框架，连接基于预训练解码器的大型语言模型（LLM）与Whisper等声学编码器-解码器架构，旨在构建支持语音交互的LLM。我们没有直接采用音频嵌入，而是探索中间的音频条件文本空间作为更高效的对齐机制。该方法完全在连续文本表示空间中运行，通过跨模态注意力融合Whisper与LLM的隐藏解码器状态，同时支持离线和流式两种模式。我们推出了首个希腊语语音LLM——VoxKrikri，并通过分析证明，该方法能有效对齐跨模态表示。这些结果表明，连续空间融合是多语言和低资源语音LLM的理想发展方向，同时在希腊语自动语音识别任务上达到了最先进水平，在各基准测试中平均相对提升【数学公式】。

> We present a multimodal fusion framework that bridges pre-trained decoder-based large language models (LLM) and acoustic encoder-decoder architectures such as Whisper, with the aim of building speech-enabled LLMs. Instead of directly using audio embeddings, we explore an intermediate audio-conditioned text space as a more effective mechanism for alignment. Our method operates fully in continuous text representation spaces, fusing Whisper's hidden decoder states with those of an LLM through cross-modal attention, and supports both offline and streaming modes. We introduce \textit{VoxKrikri}, the first Greek speech LLM, and show through analysis that our approach effectively aligns representations across modalities. These results highlight continuous space fusion as a promising path for multilingual and low-resource speech LLMs, while achieving state-of-the-art results for Automatic Speech Recognition in Greek, providing an average $\sim20\%$ relative improvement across benchmarks.

[Arxiv](https://arxiv.org/abs/2509.15667)