# FunAudio-ASR 技术报告

发布时间：2025年09月17日

`LLM应用` `媒体与娱乐`

> FunAudio-ASR Technical Report

# 摘要

> 近年来，自动语音识别（ASR）在三大互补范式的推动下实现了变革性突破：数据规模扩展、模型尺寸升级以及与大型语言模型（LLMs）的深度融合。然而，LLMs存在幻觉问题，这会显著影响实际ASR应用的用户体验。为此，本文提出FunAudio-ASR——一个大规模基于LLM的ASR系统。该系统融合海量数据、大模型容量、LLM集成与强化学习技术，在各类复杂语音识别场景中均达到了最先进水平。此外，FunAudio-ASR针对实际部署场景进行了专项优化，重点提升了流式处理能力、噪声鲁棒性、代码切换和热词定制功能，同时满足了其他实际应用需求。实验结果显示，多数基于LLM的ASR系统虽在开源基准数据集上性能优异，却在实际行业评估集上表现欠佳。得益于面向生产环境的优化，FunAudio-ASR在实际应用数据集上实现了SOTA性能，充分验证了其在真实场景中的有效性与鲁棒性。

> In recent years, automatic speech recognition (ASR) has witnessed transformative advancements driven by three complementary paradigms: data scaling, model size scaling, and deep integration with large language models (LLMs). However, LLMs are prone to hallucination, which can significantly degrade user experience in real-world ASR applications. In this paper, we present FunAudio-ASR, a large-scale, LLM-based ASR system that synergistically combines massive data, large model capacity, LLM integration, and reinforcement learning to achieve state-of-the-art performance across diverse and complex speech recognition scenarios. Moreover, FunAudio-ASR is specifically optimized for practical deployment, with enhancements in streaming capability, noise robustness, code-switching, hotword customization, and satisfying other real-world application requirements. Experimental results show that while most LLM-based ASR systems achieve strong performance on open-source benchmarks, they often underperform on real industry evaluation sets. Thanks to production-oriented optimizations, FunAudio-ASR achieves SOTA performance on real application datasets, demonstrating its effectiveness and robustness in practical settings.

[Arxiv](https://arxiv.org/abs/2509.12508)