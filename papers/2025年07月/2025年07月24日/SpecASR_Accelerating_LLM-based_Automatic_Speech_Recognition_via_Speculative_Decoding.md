# # SpecASR：加速基于LLM的自动语音识别
SpecASR: 通过推测式解码加速基于LLM的自动语音识别

发布时间：2025年07月24日

`LLM应用` `语音识别`

> SpecASR: Accelerating LLM-based Automatic Speech Recognition via Speculative Decoding

# 摘要

> 基于大型语言模型（LLM）的自动语音识别（ASR）因其高识别准确率和多方言支持而备受关注。然而，LLM的高解码延迟对实时ASR造成了挑战。尽管推测式解码被研究以提高效率，但它们通常忽略了ASR任务的关键特性，导致加速有限。为了解决这一问题，我们提出了一种专为ASR设计的新型推测式解码框架——SpecASR。SpecASR基于我们的观察：ASR解码基于音频，即使中间步骤存在不匹配，小模型和大模型的输出对齐度依然很高。因此，SpecASR采用自适应草稿序列生成，动态调整长度以最大化令牌接受。此外，SpecASR还提出了草稿序列回收策略，重复利用之前生成的草稿以减少延迟。我们还设计了一种两阶段稀疏令牌树生成算法，以平衡草稿和目标模型的延迟。实验结果表明，SpecASR在基线自回归解码和推测式解码的基础上分别实现了3.04倍至3.79倍和1.25倍至1.84倍的加速，且识别准确率保持不变。

> Large language model (LLM)-based automatic speech recognition (ASR) has recently attracted a lot of attention due to its high recognition accuracy and enhanced multi-dialect support. However, the high decoding latency of LLMs challenges the real-time ASR requirements. Although speculative decoding has been explored for better decoding efficiency, they usually ignore the key characteristics of the ASR task and achieve limited speedup. To further reduce the real-time ASR latency, in this paper, we propose a novel speculative decoding framework specialized for ASR, dubbed SpecASR. SpecASR is developed based on our core observation that ASR decoding is audio-conditioned, which results in high output alignment between small and large ASR models, even given output mismatches in intermediate decoding steps. Therefore, SpecASR features an adaptive draft sequence generation process that dynamically modifies the draft sequence length to maximize the token acceptance length. SpecASR further proposes a draft sequence recycling strategy that reuses the previously generated draft sequence to reduce the draft ASR model latency. Moreover, a two-pass sparse token tree generation algorithm is also proposed to balance the latency of draft and target ASR models. With extensive experimental results, we demonstrate SpecASR achieves 3.04x-3.79x and 1.25x-1.84x speedup over the baseline autoregressive decoding and speculative decoding, respectively, without any loss in recognition accuracy.

[Arxiv](https://arxiv.org/abs/2507.18181)