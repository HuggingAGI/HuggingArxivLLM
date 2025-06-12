# OmniDRCA: 基于双分辨率语音表示和对比对齐的并行语音文本基础模型

发布时间：2025年06月10日

`LLM应用` `问答系统` `对话系统`

> OmniDRCA: Parallel Speech-Text Foundation Model via Dual-Resolution Speech Representations and Contrastive Alignment

# 摘要

> 近期，基于大型语言模型（LLMs）的端到端语音生成研究引发了广泛关注。已有多种方法将文本基LLM扩展为生成离散语音标记的能力。现有方法主要分为两类：（1）独立生成离散语音标记而不将其纳入LLM自回归过程的方法，导致文本生成过程对同时进行的语音合成毫不知情。（2）通过联合自回归建模生成交错或并行的语音-文本标记，使生成过程中能够实现模态间的相互感知。本文提出OmniDRCA，这是一种基于联合自回归建模的并行语音-文本基础模型，具备双分辨率语音表征和对比跨模态对齐能力。我们的方法在处理语音和文本表征时采用并行方式，同时通过对比对齐提升音频理解能力。在语音问答基准测试中的实验结果表明，OmniDRCA在基于并行联合语音-文本建模的基础模型中达到了新的最先进（SOTA）水平，并与交错模型相比取得了具有竞争力的表现。此外，我们还探索了将该框架扩展至全双工对话场景的潜力。

> Recent studies on end-to-end speech generation with large language models (LLMs) have attracted significant community attention, with multiple works extending text-based LLMs to generate discrete speech tokens. Existing approaches primarily fall into two categories: (1) Methods that generate discrete speech tokens independently without incorporating them into the LLM's autoregressive process, resulting in text generation being unaware of concurrent speech synthesis. (2) Models that generate interleaved or parallel speech-text tokens through joint autoregressive modeling, enabling mutual modality awareness during generation. This paper presents OmniDRCA, a parallel speech-text foundation model based on joint autoregressive modeling, featuring dual-resolution speech representations and contrastive cross-modal alignment. Our approach processes speech and text representations in parallel while enhancing audio comprehension through contrastive alignment. Experimental results on Spoken Question Answering benchmarks demonstrate that OmniDRCA establishes new state-of-the-art (SOTA) performance among parallel joint speech-text modeling based foundation models, and achieves competitive performance compared to interleaved models. Additionally, we explore the potential of extending the framework to full-duplex conversational scenarios.

[Arxiv](https://arxiv.org/abs/2506.09349)