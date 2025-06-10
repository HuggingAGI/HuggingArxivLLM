# 基于神经音频编解码器与标签延迟训练的流式对话结束检测器

发布时间：2025年06月08日

`LLM应用` `语音对话系统` `语音处理`

> Streaming Endpointer for Spoken Dialogue using Neural Audio Codecs and Label-Delayed Training

# 摘要

> 精准且低延迟的端点检测是有效语音对话系统的基石。传统端点检测方法通常依赖于基于频谱的音频特征，而本研究提出了一种基于流式、低比特率神经音频编解码器（NAC）特征的多轮对话实时语音端点检测方案，该方案充分利用了近期在神经音频编解码器领域的最新进展。为了进一步降低切分错误率，我们创新性地引入了一种标签延迟训练方案。在固定中位延迟为160毫秒的情况下，我们的NAC与标签延迟结合的方法取得了显著的成果：单流端点检测器的错误率降低了42.7%，双流配置的错误率降低了37.5%，相较于基线方法。最后，我们成功实现了与基于编解码器的预训练语音大语言模型的高效集成，使其中位响应时间提升了1200毫秒，并将切分错误率降低了35%。

> Accurate, low-latency endpointing is crucial for effective spoken dialogue systems. While traditional endpointers often rely on spectrum-based audio features, this work proposes real-time speech endpointing for multi-turn dialogues using streaming, low-bitrate Neural Audio Codec (NAC) features, building upon recent advancements in neural audio codecs. To further reduce cutoff errors, we introduce a novel label delay training scheme. At a fixed median latency of 160 ms, our combined NAC and label delay approach achieves significant relative cutoff error reductions: 42.7% for a single-stream endpointer and 37.5% for a two-stream configuration, compared to baseline methods. Finally, we demonstrate efficient integration with a codec-based pretrained speech large language model, improving its median response time by 1200 ms and reducing its cutoff error by 35%.

[Arxiv](https://arxiv.org/abs/2506.07081)