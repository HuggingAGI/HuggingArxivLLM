# <翻译失败>

发布时间：2025年08月29日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> Democratizing Agentic AI with Fast Test-Time Scaling on the Edge

# 摘要

> <翻译失败>

> Deploying agentic AI on edge devices is crucial for privacy and responsiveness, but memory constraints typically relegate these systems to smaller Large Language Models (LLMs) with inferior reasoning capabilities. Test-Time Scaling (TTS) can bridge this reasoning gap by dedicating more compute during inference, but existing methods incur prohibitive overhead on edge hardware. To overcome this, we introduce FlashTTS, a serving system that makes TTS practical for memory-constrained LLM reasoning. FlashTTS introduces three synergistic optimizations: (i) Speculative Beam Extension to mitigate system stragglers from irregular reasoning paths; (ii) Asymmetric Multi-Model Memory Allocation to dynamically balance memory between generation and verification; and (iii) Dynamic Prefix-Aware Scheduling to maximize KV-cache reuse. Built as a plug-and-play library for vLLM, FlashTTS enables edge LLMs on a single consumer GPU (24 GB) to match the accuracy and latency of large cloud models. Our evaluation demonstrates that FlashTTS achieves an average 2.2x higher goodput and reduces latency by 38%-68% compared to a vLLM baseline, paving the way for democratized, high-performance agentic AI on edge devices.

[Arxiv](https://arxiv.org/abs/2509.00195)