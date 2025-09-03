# FLM-Audio：自然独白双训练赋能原生全双工聊天机器人

发布时间：2025年09月02日

`LLM应用` `媒体与娱乐`

> FLM-Audio: Natural Monologues Improves Native Full-Duplex Chatbots via Dual Training

# 摘要

> 全双工对话模型旨在实现边听边说，能对快速变化的用户输入迅速做出反应。在现有方案中，原生全双工模型可在单个时间步长内融合听、说等不同通道，克服了时分复用（TDM）方案固有的高响应延迟问题。然而，一个核心挑战仍未解决：如何将文本独白与不同比特率的音频流进行对齐。目前主流解决方案采用词级对齐，但这可能会削弱大型预训练模型的语言能力。此外，这种方法还需要为每个标记提供高精度时间戳，不仅会引发级联错误，还会增加预处理成本。为此，本文提出了连续标记序列形式的文本独白，即“自然独白”，其模拟了对话中的类人认知行为。在时间对齐方面，我们在不同训练阶段交替调整自然独白的位置——使其领先于音频或滞后于音频。这种“双轨”训练范式在构建FLM-Audio（我们研发的70亿参数口语对话模型）时被证明极为有效，实验结果显示该模型在响应速度、双工性能和聊天体验上均表现卓越。

> Full-duplex dialog models are designed to listen and speak simultaneously with rapid responses to fast-changing user input. Among existing approaches, native full-duplex models merges different channels (e.g. listen and speak) in a single time step, overcoming the high response latency inherent to time-division multiplexing time-division multiplexing (TDM) alternatives. Yet, a key challenge remains: aligning textual monologues with audio streams that operate at different bitrates. The prevailing solution relies on word-level alignment, but this can degrade the language ability of large pre-trained models. Moreover, it requires highly accurate timestamps for every token, which introduces cascading errors and increases pre-processing costs. In this paper, we propose textual monologues in continuous tokens sequence, namely "natural" monologues, which mimics humanoid cognitive behavior in dialogs. For temporal alignment, we alternate the position of the natural monologue - leading or trailing the audio - across different training stages. This "dual" training paradigm proves highly effective in building FLM-Audio, our 7B spoken dialog model that demonstrates superior responsiveness, duplexity, and chatting experiences, as confirmed by experimental results.

[Arxiv](https://arxiv.org/abs/2509.02521)