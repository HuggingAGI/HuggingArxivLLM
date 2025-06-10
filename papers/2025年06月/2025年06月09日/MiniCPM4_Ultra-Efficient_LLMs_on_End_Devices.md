# # MiniCPM4：专为终端设备打造的超高效大语言模型

发布时间：2025年06月09日

`LLM应用` `可信调查生成` `工具使用`

> MiniCPM4: Ultra-Efficient LLMs on End Devices

# 摘要

> 本文介绍了 MiniCPM4，一款专为终端设备设计的高效大型语言模型（LLM）。我们通过在模型架构、训练数据、训练算法和推理系统四个维度上的系统性创新，实现了其高效性。在模型架构方面，我们提出了 InfLLM v2，一种可训练的稀疏注意力机制，显著提升了长上下文处理的预填和解码速度。在训练数据方面，我们开发了 UltraClean 数据过滤策略和 UltraChat v2 微调数据集，仅需 8 万亿训练代词即可实现优秀性能。在训练算法方面，我们推出了 ModelTunnel v2 用于高效策略搜索，并通过引入分块式展开的强化学习和数据高效三元 LLM（BitCPM）优化了现有方法。在推理系统方面，CPM.cu 集成了稀疏注意力、模型量化和推测采样技术，进一步提升了推理效率。为了满足不同终端设备的需求，MiniCPM4 提供了 0.5B 和 8B 两个参数版本。大量实验结果表明，MiniCPM4 在多个基准测试中显著优于同规模开源模型，展现了其卓越的效率与效果。特别地，MiniCPM4-8B 在长序列处理速度上超越了 Qwen3-8B。通过进一步优化，MiniCPM4 已成功应用于可信调查生成和工具使用等多个场景，充分证明了其广泛的适用性。

> This paper introduces MiniCPM4, a highly efficient large language model (LLM) designed explicitly for end-side devices. We achieve this efficiency through systematic innovation in four key dimensions: model architecture, training data, training algorithms, and inference systems. Specifically, in terms of model architecture, we propose InfLLM v2, a trainable sparse attention mechanism that accelerates both prefilling and decoding phases for long-context processing. Regarding training data, we propose UltraClean, an efficient and accurate pre-training data filtering and generation strategy, and UltraChat v2, a comprehensive supervised fine-tuning dataset. These datasets enable satisfactory model performance to be achieved using just 8 trillion training tokens. Regarding training algorithms, we propose ModelTunnel v2 for efficient pre-training strategy search, and improve existing post-training methods by introducing chunk-wise rollout for load-balanced reinforcement learning and data-efficient tenary LLM, BitCPM. Regarding inference systems, we propose CPM.cu that integrates sparse attention, model quantization, and speculative sampling to achieve efficient prefilling and decoding. To meet diverse on-device requirements, MiniCPM4 is available in two versions, with 0.5B and 8B parameters, respectively. Sufficient evaluation results show that MiniCPM4 outperforms open-source models of similar size across multiple benchmarks, highlighting both its efficiency and effectiveness. Notably, MiniCPM4-8B demonstrates significant speed improvements over Qwen3-8B when processing long sequences. Through further adaptation, MiniCPM4 successfully powers diverse applications, including trustworthy survey generation and tool use with model context protocol, clearly showcasing its broad usability.

[Arxiv](https://arxiv.org/abs/2506.07900)