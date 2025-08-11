# SpeakerLM：基于多模态大语言模型的端到端说话人分离与识别

发布时间：2025年08月08日

`LLM应用` `语音处理` `对话系统`

> SpeakerLM: End-to-End Versatile Speaker Diarization and Recognition with Multimodal Large Language Models

# 摘要

> 说话人分离与识别（SDR）任务专注于解决音频片段中的“谁在何时说了什么”问题，在会议记录和对话系统等多说话人场景中具有重要意义。传统SDR系统通常采用级联架构，整合了说话人分离（SD）和自动语音识别（ASR）等多个模块。然而，这种架构存在错误传播、难以处理重叠语音以及缺乏SD与ASR任务协同优化等局限性。为突破这些限制，我们推出了SpeakerLM——一个统一的多模态大型语言模型，可在端到端框架下同时实现SD和ASR。此外，为了适应多样化的实际应用需求，我们在SpeakerLM中引入了灵活的说话人注册机制，使其能够应对不同注册条件下的SDR任务。SpeakerLM通过多阶段训练策略在大规模真实数据上逐步优化而成。实验结果表明，SpeakerLM不仅具备强大的数据扩展能力，还展现了卓越的泛化性能，在内部和外部公开SDR基准测试中均显著优于现有的级联基线系统。进一步的实验验证了，我们的说话人注册机制有效确保了SpeakerLM在各种说话人注册条件和不同注册人数下的稳健性能。

> The Speaker Diarization and Recognition (SDR) task aims to predict "who spoke when and what" within an audio clip, which is a crucial task in various real-world multi-speaker scenarios such as meeting transcription and dialogue systems. Existing SDR systems typically adopt a cascaded framework, combining multiple modules such as speaker diarization (SD) and automatic speech recognition (ASR). The cascaded systems suffer from several limitations, such as error propagation, difficulty in handling overlapping speech, and lack of joint optimization for exploring the synergy between SD and ASR tasks. To address these limitations, we introduce SpeakerLM, a unified multimodal large language model for SDR that jointly performs SD and ASR in an end-to-end manner. Moreover, to facilitate diverse real-world scenarios, we incorporate a flexible speaker registration mechanism into SpeakerLM, enabling SDR under different speaker registration settings. SpeakerLM is progressively developed with a multi-stage training strategy on large-scale real data. Extensive experiments show that SpeakerLM demonstrates strong data scaling capability and generalizability, outperforming state-of-the-art cascaded baselines on both in-domain and out-of-domain public SDR benchmarks. Furthermore, experimental results show that the proposed speaker registration mechanism effectively ensures robust SDR performance of SpeakerLM across diverse speaker registration conditions and varying numbers of registered speakers.

[Arxiv](https://arxiv.org/abs/2508.06372)