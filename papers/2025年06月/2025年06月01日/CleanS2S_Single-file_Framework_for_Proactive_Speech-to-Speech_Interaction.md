# CleanS2S：主动语音交互的单文件框架

发布时间：2025年06月01日

`Agent` `人工智能` `语音交互`

> CleanS2S: Single-file Framework for Proactive Speech-to-Speech Interaction

# 摘要

> # CleanS2S：类人语音交互新框架  
CleanS2S 是一个专注于实现类人语音交互的创新框架，它通过单文件实现和主动对话功能重新定义了对话式AI。我们的系统将自动语音识别、大型语言模型和语音合成技术无缝集成，构建了一个支持实时中断处理的统一管道。借助全双工 websocket 连接和非阻塞 I/O 技术，系统实现了超低延迟的交互体验。  

与传统聊天机器人不同，CleanS2S 首创了一种主动交互机制，结合记忆系统和主观行动判断模块，能够灵活运用五种类人响应策略：打断、拒绝、转移、沉默和标准响应。记忆模块实时聚合历史和上下文信息，为对话决策提供智能支持。这种设计打破了传统的基于回合的 rigid 模式，赋予系统主动控制对话的能力，并可根据上下文智能选择响应。  

为优化交互流程，我们提出了行动判断 SFT，用于实时评估输入流以动态调整响应策略。CleanS2S 的单文件实现和原子化配置设计为研究者提供了前所未有的透明度和可扩展性，助力交互式代理的创新开发。  

立即访问 \https://github.com/opendilab/CleanS2S，获取完整代码，探索更多可能！


> CleanS2S is a framework for human-like speech-to-speech interaction that advances conversational AI through single-file implementation and proactive dialogue capabilities. Our system integrates automatic speech recognition, large language models, and text-to-speech synthesis into a unified pipeline with real-time interruption handling, achieving low transition latency through full-duplex websocket connections and non-blocking I/O. Beyond conventional chatbot paradigms, we pioneer a proactive interaction mechanism, which combines memory systems with Subjective Action Judgement module, enabling five human-like response strategies: interruption, refusal, deflection, silence, and standard response. The memory module dynamically aggregates historical, and contextual data to inform interaction decisions. This approach breaks the rigid turn-based convention by allowing system-initiated dialog control and context-aware response selection. And we propose Action Judgement SFT that assesses input streams for responses strategies. The framework's single-file implementation with atomic configurations offers researchers unprecedented transparency and extensibility for interaction agents. The code of CleanS2S is released at \https://github.com/opendilab/CleanS2S.

[Arxiv](https://arxiv.org/abs/2506.01268)