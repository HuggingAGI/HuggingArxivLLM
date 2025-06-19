# # PredGen: 通过输入时推测加速大型语言模型推理，实现实时语音交互

发布时间：2025年06月18日

`LLM应用` `语音助手` `实时语音聊天`

> PredGen: Accelerated Inference of Large Language Models through Input-Time Speculation for Real-Time Speech Interaction

# 摘要

> 大型语言模型（LLMs）广泛应用于实时语音聊天，通常与文本转语音（TTS）系统结合生成音频响应。然而，由于模型规模庞大，用户输入结束与音频输出开始之间常出现明显延迟，影响用户体验。这种延迟在LLMs作为消费级设备上的单用户语音助手时尤为突出。我们发现，延迟主要源于LLMs生成首个句子所需时间，而TTS系统需逐句处理这些输入。为解决这一问题，我们提出了一种名为预测生成（PredGen）的新框架，通过在输入时进行推测性解码，显著减少甚至消除延迟。PredGen在用户说话时即可生成候选响应，使系统能够以最小延迟启动TTS处理。在Lmsys和MT-Bench数据集上的模拟实验表明，与传统方法相比，PredGen在广泛场景中可将延迟降低约2倍，同时仅在输入时产生极小额外计算开销，这些计算原本可能被闲置。

> Large Language Models (LLMs) are widely used in real-time voice chat applications, typically in combination with text-to-speech (TTS) systems to generate audio responses. However, their large size often leads to noticeable latency between the end of user input and the start of audio output, resulting in suboptimal user experiences. This latency is particularly evident when LLMs are deployed as single-user voice assistants on consumer-grade hardware with limited computing capacity. We discovered that this latency is primarily dominated by the time it takes for the LLMs to generate the first sentence, which is required as input by the TTS systems that synthesize audio responses on a sentence-by-sentence basis. To address this bottleneck, we propose Predictive Generation (PredGen), a novel framework that mitigates-or even eliminates-this delay through speculative decoding at input time. PredGen generates candidate responses while the user is still speaking, enabling the system to begin TTS processing with minimal delay. Simulated experiments on the Lmsys and MT-Bench datasets show that the proposed method can effectively reduce the latency by around 2x across a wide range of use cases, while incurring only minimal additional computation cost at input time-computation that would otherwise go unused.

[Arxiv](https://arxiv.org/abs/2506.15556)