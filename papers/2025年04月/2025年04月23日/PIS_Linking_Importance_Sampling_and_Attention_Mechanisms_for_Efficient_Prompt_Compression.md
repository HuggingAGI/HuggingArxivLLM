# PIS：结合重要性采样与注意力机制实现高效提示压缩

发布时间：2025年04月23日

`LLM应用` `上下文管理`

> PIS: Linking Importance Sampling and Attention Mechanisms for Efficient Prompt Compression

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中取得了突破性进展，展现出强大的能力。然而，其高昂的使用成本限制了广泛应用，提示压缩技术应运而生。现有方法多依赖启发式截断或摘要技术，忽视了LLMs的内在机制，缺乏对令牌重要性的系统评估。本研究提出了一种全新的提示重要性采样（PIS）框架，通过分析隐藏状态的注意力分数实现动态压缩。PIS采用双层机制：1）令牌级别，利用LLMs的注意力分数量化重要性，通过轻量级9层强化学习网络实现自适应压缩；2）语义级别，提出俄罗斯轮盘采样策略进行句子级别的重要采样。在多个领域基准测试中，PIS展现了卓越的压缩性能。值得注意的是，通过优化上下文结构，PIS意外地提升了推理效率。这项工作为提示工程提供了理论基础和实用效率，推动了LLMs的上下文管理技术。

> Large language models (LLMs) have achieved remarkable progress, demonstrating unprecedented capabilities across various natural language processing tasks. However, the high costs associated with such exceptional performance limit the widespread adoption of LLMs, highlighting the need for prompt compression. Existing prompt compression methods primarily rely on heuristic truncation or abstractive summarization techniques, which fundamentally overlook the intrinsic mechanisms of LLMs and lack a systematic evaluation of token importance for generation. In this work, we introduce Prompt Importance Sampling (PIS), a novel compression framework that dynamically compresses prompts by sampling important tokens based on the analysis of attention scores of hidden states. PIS employs a dual-level compression mechanism: 1) at the token level, we quantify saliency using LLM-native attention scores and implement adaptive compression through a lightweight 9-layer reinforcement learning (RL) network; 2) at the semantic level, we propose a Russian roulette sampling strategy for sentence-level importance sampling. Comprehensive evaluations across multiple domain benchmarks demonstrate that our method achieves state-of-the-art compression performance. Notably, our framework serendipitously enhances reasoning efficiency through optimized context structuring. This work advances prompt engineering by offering both theoretical grounding and practical efficiency in context management for LLMs.

[Arxiv](https://arxiv.org/abs/2504.16574)