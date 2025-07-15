# # 人机对话新境界：实时视频通话从人类到 AI 的惊人转变

发布时间：2025年07月14日

`LLM应用` `实时通信` `视频流传输`

> Chat with AI: The Surprising Turn of Real-time Video Communication from Human to AI

# 摘要

> # AI视频聊天：实时通信的新范式
AI视频聊天正在开创实时通信（RTC）领域的一种全新范式——一方不再是人类，而是一个多模态大型语言模型（MLLM）。这种创新使人类与AI的交互更加直观自然，仿佛在与真人面对面聊天。然而，这也带来了巨大的技术挑战：MLLM推理占据了大部分响应时间，留给视频流传输的时间所剩无几。而网络的不确定性和不稳定性，使得传输延迟成为阻碍AI表现得像真人的关键瓶颈。

为了解决这一难题，我们提出了Artic——一个面向AI的实时通信框架，推动网络需求从“人类观看视频”向“AI理解视频”转变。为了在保持MLLM准确性的同时大幅降低比特率，我们开发了情境感知视频流传输技术，该技术能够识别视频中各区域对聊天的重要性，并几乎将比特率专用于对聊天重要的区域。为了避免数据包重传带来的额外延迟，我们设计了抗丢包自适应帧率技术，巧妙利用之前帧来替代丢失或延迟的帧，同时避免比特率浪费。

为了评估视频流质量对MLLM准确性的影响，我们构建了首个基准测试——降质视频理解基准（DeViBench）。最后，我们探讨了AI视频聊天领域的一些开放问题和正在进行的解决方案。

> AI Video Chat emerges as a new paradigm for Real-time Communication (RTC), where one peer is not a human, but a Multimodal Large Language Model (MLLM). This makes interaction between humans and AI more intuitive, as if chatting face-to-face with a real person. However, this poses significant challenges to latency, because the MLLM inference takes up most of the response time, leaving very little time for video streaming. Due to network uncertainty and instability, transmission latency becomes a critical bottleneck preventing AI from being like a real person. To address this, we propose Artic, an AI-oriented Real-time Communication framework, exploring the network requirement shift from "humans watching video" to "AI understanding video". To reduce bitrate dramatically while maintaining MLLM accuracy, we propose Context-Aware Video Streaming that recognizes the importance of each video region for chat and allocates bitrate almost exclusively to chat-important regions. To avoid packet retransmission, we propose Loss-Resilient Adaptive Frame Rate that leverages previous frames to substitute for lost/delayed frames while avoiding bitrate waste. To evaluate the impact of video streaming quality on MLLM accuracy, we build the first benchmark, named Degraded Video Understanding Benchmark (DeViBench). Finally, we discuss some open questions and ongoing solutions for AI Video Chat.

[Arxiv](https://arxiv.org/abs/2507.10510)