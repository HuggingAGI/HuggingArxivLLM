# # 大型音频-语言模型的直接同步翻译激活

发布时间：2025年09月19日

`LLM应用` `媒体与娱乐`

> Direct Simultaneous Translation Activation for Large Audio-Language Models

# 摘要

> 同步语音转文本翻译（Simul-S2TT）的目标是实时将语音转为目标文本——在接收源语音输入的同时输出翻译，无需等待整段话语结束。以往Simul-S2TT研究常通过修改模型架构来实现读写策略。然而，随着大型音频语言模型（LALMs）的崛起，核心挑战在于如何在不额外修改架构的前提下，直接激活基础模型的Simul-S2TT能力。本文提出{f Simul}taneous {f S}elf-{f A}ugmentation（{f SimulSA}，同步自增强）策略，它借助LALMs的固有能力，通过随机截断语音并构建部分对齐的翻译来获取同步数据。将这些同步数据整合到离线SFT数据后，SimulSA能有效弥合预训练阶段离线翻译与推理阶段同步翻译之间的分布差异。

> Simultaneous speech-to-text translation (Simul-S2TT) aims to translate speech into target text in real time, outputting translations while receiving source speech input, rather than waiting for the entire utterance to be spoken. Simul-S2TT research often modifies model architectures to implement read-write strategies. However, with the rise of large audio-language models (LALMs), a key challenge is how to directly activate Simul-S2TT capabilities in base models without additional architectural changes. In this paper, we introduce {\bf Simul}taneous {\bf S}elf-{\bf A}ugmentation ({\bf SimulSA}), a strategy that utilizes LALMs' inherent capabilities to obtain simultaneous data by randomly truncating speech and constructing partially aligned translation. By incorporating them into offline SFT data, SimulSA effectively bridges the distribution gap between offline translation during pretraining and simultaneous translation during inference. Experimental results demonstrate that augmenting only about {\bf 1\%} of the simultaneous data, compared to the full offline SFT data, can significantly activate LALMs' Simul-S2TT capabilities without modifications to model architecture or decoding strategy.

[Arxiv](https://arxiv.org/abs/2509.15692)