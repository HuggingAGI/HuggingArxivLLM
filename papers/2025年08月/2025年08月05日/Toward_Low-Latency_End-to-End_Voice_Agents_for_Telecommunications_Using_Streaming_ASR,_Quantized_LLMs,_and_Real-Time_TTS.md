# 构建面向通信领域的低延迟端到端语音代理：基于流式语音识别、量化大型语言模型与实时语音合成技术

发布时间：2025年08月05日

`LLM应用`

> Toward Low-Latency End-to-End Voice Agents for Telecommunications Using Streaming ASR, Quantized LLMs, and Real-Time TTS

# 摘要

> 我们推出了一款专为实时互动电信场景设计的低延迟AI语音代理解决方案，助力实现呼叫中心自动化、智能IVR以及AI驱动的客户支持。该方案由NetoAI开发，整合了四款专用模型：4位量化电信专用大型语言模型TSLAM、电信专用嵌入模型T-VEC、电信专用自动语音识别模型TTE，以及电信专用文本到语音模型T-Synth。这些模型协同工作，支持高响应、领域适配的语音AI代理，实现基于知识的语音交互，且延迟极低。该方案集成了流式ASR（TTE）、对话智能（TSLAM）、基于电信文档的检索增强生成（RAG），以及实时TTS（T-Synth），树立了电信语音助手的新标杆。为评估系统性能，我们构建了一个包含500个基于RFC的人工录制电信问题的 dataset，模拟真实电信代理查询。该框架可全面分析技术栈的延迟、领域相关性和实时性能。测试结果显示，TSLAM、TTE和T-Synth的实时因子（RTF）均低于1.0，支持企业级低延迟电信部署。这些由TSLAM、TTE和T-Synth驱动的AI代理为下一代电信AI奠定了基础，实现了自动化客户支持、诊断等功能。

> We introduce a low-latency telecom AI voice agent pipeline for real-time, interactive telecommunications use, enabling advanced voice AI for call center automation, intelligent IVR (Interactive Voice Response), and AI-driven customer support. The solution is built for telecom, combining four specialized models by NetoAI: TSLAM, a 4-bit quantized Telecom-Specific Large Language Model (LLM); T-VEC, a Telecom-Specific Embedding Model; TTE, a Telecom-Specific Automatic Speech Recognition (ASR) model; and T-Synth, a Telecom-Specific Text-to-Speech (TTS) model. These models enable highly responsive, domain-adapted voice AI agents supporting knowledge-grounded spoken interactions with low latency. The pipeline integrates streaming ASR (TTE), conversational intelligence (TSLAM), retrieval augmented generation (RAG) over telecom documents, and real-time TTS (T-Synth), setting a new benchmark for telecom voice assistants. To evaluate the system, we built a dataset of 500 human-recorded telecom questions from RFCs, simulating real telecom agent queries. This framework allows analysis of latency, domain relevance, and real-time performance across the stack. Results show that TSLAM, TTE, and T-Synth deliver real-time factors (RTF) below 1.0, supporting enterprise, low-latency telecom deployments. These AI agents -- powered by TSLAM, TTE, and T-Synth -- provide a foundation for next-generation telecom AI, enabling automated customer support, diagnostics, and more.

[Arxiv](https://arxiv.org/abs/2508.04721)