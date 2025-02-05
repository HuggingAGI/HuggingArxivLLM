# EasySpec: 层并行推测解码，提升多GPU利用效率

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了推测解码方法在多GPU系统中的优化应用，特别是通过EasySpec策略来提高LLM推理的效率和速度。虽然涉及到一些技术细节和理论背景，但其核心是LLM在实际应用中的性能优化，因此归类为“LLM应用”。` `人工智能` `并行计算`

> EasySpec: Layer-Parallel Speculative Decoding for Efficient Multi-GPU Utilization

# 摘要

> 推测解码是一种高效无损的LLM推理加速方法，通过小模型生成草稿标记序列，再由基础模型验证。在多GPU系统中，张量并行（TP）可进一步降低推理延迟，但草稿模型的最佳TP大小通常小于基础模型，导致草稿阶段GPU闲置。为此，我们提出EasySpec，一种层并行推测策略，优化多GPU利用率。EasySpec打破草稿模型的层顺序执行，实现跨设备多层并行化，尽管会引入少量近似误差。每次草稿和验证迭代后，草稿模型的KV缓存会在一次前向传递中校准，防止长期误差积累，且额外延迟最小。我们在多个主流开源LLM上评估EasySpec，使用同一系列的小模型作为草稿模型。结果显示，EasySpec相比普通解码最高可加速4.17倍，同时保持基础LLM的原始分布。草稿阶段加速可达1.62倍，最大准确率下降仅7%，且无需对草稿模型进行训练或微调。

> Speculative decoding is an effective and lossless method for Large Language Model (LLM) inference acceleration. It employs a smaller model to generate a draft token sequence, which is then verified by the original base model. In multi-GPU systems, inference latency can be further reduced through tensor parallelism (TP), while the optimal TP size of the draft model is typically smaller than that of the base model, leading to GPU idling during the drafting stage. To solve this problem, we propose EasySpec, a layer-parallel speculation strategy that optimizes the efficiency of multi-GPU utilization.EasySpec breaks the sequential execution order of layers in the drafting model, enabling multi-layer parallelization across devices, albeit with some induced approximation errors. After each drafting-and-verification iteration, the draft model's key-value (KV) cache is calibrated in a single forward pass, preventing long-term error accumulation at minimal additional latency. We evaluated EasySpec on several mainstream open-source LLMs, using smaller versions of models from the same series as drafters. The results demonstrate that EasySpec can achieve a peak speedup of 4.17x compared to vanilla decoding, while preserving the original distribution of the base LLMs. Specifically, the drafting stage can be accelerated by up to 1.62x with a maximum accuracy drop of only 7%, requiring no training or fine-tuning on the draft models.

[Arxiv](https://arxiv.org/abs/2502.02493)