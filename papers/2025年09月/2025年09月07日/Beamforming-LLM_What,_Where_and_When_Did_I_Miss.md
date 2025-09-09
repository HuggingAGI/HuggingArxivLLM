# Beamforming-LLM：我遗漏了什么、何处与何时？

发布时间：2025年09月07日

`RAG` `媒体与娱乐`

> Beamforming-LLM: What, Where and When Did I Miss?

# 摘要

> 我们提出了Beamforming-LLM系统，它能帮助用户在多说话人场景中语义回溯可能错过的对话内容。该系统结合麦克风阵列的空间音频采集与检索增强生成（RAG）技术，支持自然语言查询，例如“我刚才关注狗狗相关对话时错过了什么内容？”其工作流程如下：通过波束成形分离定向音频流，借助Whisper模型转录文本，再通过句子编码器嵌入向量数据库；当接收到用户查询时，系统会检索语义相关片段，与未关注的部分进行时间对齐，然后通过轻量级大语言模型（GPT-4o-mini）生成摘要。最终呈现的用户友好界面可提供对比摘要、空间上下文及带时间戳的音频回放功能。这项研究为智能听觉记忆系统奠定了基础，在辅助技术、会议总结及上下文感知个人空间计算等领域具有广泛应用前景。

> We present Beamforming-LLM, a system that enables users to semantically recall conversations they may have missed in multi-speaker environments. The system combines spatial audio capture using a microphone array with retrieval-augmented generation (RAG) to support natural language queries such as, "What did I miss when I was following the conversation on dogs?" Directional audio streams are separated using beamforming, transcribed with Whisper, and embedded into a vector database using sentence encoders. Upon receiving a user query, semantically relevant segments are retrieved, temporally aligned with non-attended segments, and summarized using a lightweight large language model (GPT-4o-mini). The result is a user-friendly interface that provides contrastive summaries, spatial context, and timestamped audio playback. This work lays the foundation for intelligent auditory memory systems and has broad applications in assistive technology, meeting summarization, and context-aware personal spatial computing.

[Arxiv](https://arxiv.org/abs/2509.06221)