# SAMA：探索多轮基于参考的视频对话的大型语言模型

发布时间：2025年05月24日

`LLM应用` `视频分析` `大模态模型`

> SAMA: Towards Multi-Turn Referential Grounded Video Chat with Large Language Models

# 摘要

> 实现视频中的细粒度时空理解仍是当前视频大模态模型（Video LMMs）面临的主要挑战。为了解决这一问题，需要掌握两大核心能力：视频指代理解（捕捉视频区域的语义）与视频定位（根据自然语言描述分割目标区域）。然而，现有方法大多孤立地处理这些任务，限制了在统一的、基于指代的视频交互方面取得进展。我们发现，缺乏高质量、统一的视频指令数据和全面的基准用于评估基于指代的视频对话是一个关键瓶颈。为了解决这些挑战，我们在数据集、模型和基准三个核心方面做出了贡献。首先，我们推出了SAMA-239K，这是一个包含1.5万条视频的大型数据集，专门用于联合学习视频指代理解、定位和多轮视频对话。其次，我们提出了SAMA模型，该模型集成了多功能时空上下文聚合器和Segment Anything Model，以共同提升细粒度视频理解与精准定位能力。最后，我们建立了SAMA-Bench，这是一个包含522个视频的5,067个问题的精心设计基准，用于全面评估Video LMMs在多轮、时空指代理解与基于定位对话中的综合能力。实验和基准测试结果表明，SAMA不仅在SAMA-Bench上表现出色，还在通用定位基准上达到了新的最先进水平，同时在标准视觉理解基准上保持了极具竞争力的性能。

> Achieving fine-grained spatio-temporal understanding in videos remains a major challenge for current Video Large Multimodal Models (Video LMMs). Addressing this challenge requires mastering two core capabilities: video referring understanding, which captures the semantics of video regions, and video grounding, which segments object regions based on natural language descriptions. However, most existing approaches tackle these tasks in isolation, limiting progress toward unified, referentially grounded video interaction. We identify a key bottleneck in the lack of high-quality, unified video instruction data and a comprehensive benchmark for evaluating referentially grounded video chat. To address these challenges, we contribute in three core aspects: dataset, model, and benchmark. First, we introduce SAMA-239K, a large-scale dataset comprising 15K videos specifically curated to enable joint learning of video referring understanding, grounding, and multi-turn video chat. Second, we propose the SAMA model, which incorporates a versatile spatio-temporal context aggregator and a Segment Anything Model to jointly enhance fine-grained video comprehension and precise grounding capabilities. Finally, we establish SAMA-Bench, a meticulously designed benchmark consisting of 5,067 questions from 522 videos, to comprehensively evaluate the integrated capabilities of Video LMMs in multi-turn, spatio-temporal referring understanding and grounded dialogue. Extensive experiments and benchmarking results show that SAMA not only achieves strong performance on SAMA-Bench but also sets a new state-of-the-art on general grounding benchmarks, while maintaining highly competitive performance on standard visual understanding benchmarks.

[Arxiv](https://arxiv.org/abs/2505.18812)