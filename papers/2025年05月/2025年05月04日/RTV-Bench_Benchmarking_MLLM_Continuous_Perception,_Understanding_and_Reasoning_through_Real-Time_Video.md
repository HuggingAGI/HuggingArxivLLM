# RTV-Bench: 通过实时视频基准测试多语言大模型的持续感知、理解和推理能力

发布时间：2025年05月04日

`LLM应用` `视频分析` `多模态学习`

> RTV-Bench: Benchmarking MLLM Continuous Perception, Understanding and Reasoning through Real-Time Video

# 摘要

> 多模态大型语言模型（MLLMs）在感知、理解和推理方面表现日益出色，然而现有基准测试未能充分评估它们在动态、真实环境中持续执行任务的能力。为此，我们推出了RTV-Bench——一个多模态大语言模型实时视频分析的细粒度基准测试。RTV-Bench基于三大核心原则：（1）多时间戳问答（MTQA），答案随场景变化而演变；（2）层次化问题结构，结合基础与高级查询；（3）多维度评估，衡量持续感知、理解与推理能力。该基准测试包含552个多样化视频（167.2小时）和4,631对高质量问答。我们评估了包括专有模型（GPT-4o，Gemini 2.0）、开源离线模型（Qwen2.5-VL，VideoLLaMA3）以及开源实时模型（VITA-1.5，InternLM-XComposer2.5-OmniLive）在内的领先MLLM。实验结果显示，开源实时模型整体表现优于离线模型，但尚未追上顶尖专有模型。进一步分析表明，模型规模或帧采样率的提升并不显著改善RTV-Bench的表现，有时甚至可能带来轻微下降。这凸显了优化视频流处理与长序列处理模型架构的重要性，以推动MLLM在实时视频分析中的应用。我们的基准测试工具包现已开源，访问地址为：https://github.com/LJungang/RTV-Bench。

> Multimodal Large Language Models (MLLMs) increasingly excel at perception, understanding, and reasoning. However, current benchmarks inadequately evaluate their ability to perform these tasks continuously in dynamic, real-world environments. To bridge this gap, we introduce RTV-Bench, a fine-grained benchmark for MLLM real-time video analysis. RTV-Bench uses three key principles: (1) Multi-Timestamp Question Answering (MTQA), where answers evolve with scene changes; (2) Hierarchical Question Structure, combining basic and advanced queries; and (3) Multi-dimensional Evaluation, assessing the ability of continuous perception, understanding, and reasoning. RTV-Bench contains 552 diverse videos (167.2 hours) and 4,631 high-quality QA pairs. We evaluated leading MLLMs, including proprietary (GPT-4o, Gemini 2.0), open-source offline (Qwen2.5-VL, VideoLLaMA3), and open-source real-time (VITA-1.5, InternLM-XComposer2.5-OmniLive) models. Experiment results show open-source real-time models largely outperform offline ones but still trail top proprietary models. Our analysis also reveals that larger model size or higher frame sampling rates do not significantly boost RTV-Bench performance, sometimes causing slight decreases. This underscores the need for better model architectures optimized for video stream processing and long sequences to advance real-time video analysis with MLLMs. Our benchmark toolkit is available at: https://github.com/LJungang/RTV-Bench.

[Arxiv](https://arxiv.org/abs/2505.02064)