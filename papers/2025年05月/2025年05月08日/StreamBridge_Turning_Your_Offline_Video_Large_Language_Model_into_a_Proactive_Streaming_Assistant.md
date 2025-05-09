# # StreamBridge：将离线视频大模型打造成为主动式的流媒体助理

发布时间：2025年05月08日

`LLM应用` `视频技术` `在线视频`

> StreamBridge: Turning Your Offline Video Large Language Model into a Proactive Streaming Assistant

# 摘要

> 我们推出StreamBridge——一个简单而强大的框架，可轻松将离线Video-LLMs升级为支持流式处理的模型。针对现有模型在在线场景应用中的两大痛点：(1)多轮实时理解能力不足，(2)缺乏主动响应机制，StreamBridge给出了创新解决方案。具体而言，它通过结合内存缓冲与轮次递减压缩策略，实现了长上下文多轮交互的支持；同时配备了一个解耦的轻量级激活模型，能够无缝融入现有Video-LLMs，从而实现持续的主动响应。为了进一步支持StreamBridge，我们打造了Stream-IT——一个专为流式视频理解设计的大型数据集，包含交错的视频-文本序列和多样化的指令格式。大量实验结果表明，StreamBridge显著提升了离线Video-LLMs在各项任务中的流式理解能力，甚至超越了GPT-4o和Gemini 1.5 Pro等专有模型。同时，它在标准视频理解基准测试中也展现出了极具竞争力甚至更优的性能表现。

> We present StreamBridge, a simple yet effective framework that seamlessly transforms offline Video-LLMs into streaming-capable models. It addresses two fundamental challenges in adapting existing models into online scenarios: (1) limited capability for multi-turn real-time understanding, and (2) lack of proactive response mechanisms. Specifically, StreamBridge incorporates (1) a memory buffer combined with a round-decayed compression strategy, supporting long-context multi-turn interactions, and (2) a decoupled, lightweight activation model that can be effortlessly integrated into existing Video-LLMs, enabling continuous proactive responses. To further support StreamBridge, we construct Stream-IT, a large-scale dataset tailored for streaming video understanding, featuring interleaved video-text sequences and diverse instruction formats. Extensive experiments show that StreamBridge significantly improves the streaming understanding capabilities of offline Video-LLMs across various tasks, outperforming even proprietary models such as GPT-4o and Gemini 1.5 Pro. Simultaneously, it achieves competitive or superior performance on standard video understanding benchmarks.

[Arxiv](https://arxiv.org/abs/2505.05467)