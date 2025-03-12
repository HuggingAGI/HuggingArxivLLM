# 位置感知深度衰减解码 ($D^3$)：提升大语言模型推理效率

发布时间：2025年03月11日

`LLM应用

摘要讨论了优化大型语言模型推理阶段的资源消耗，提出了一种动态计算方法，无需重新训练，通过位置感知的分层跳过框架节省计算量。这种方法属于LLM的应用层面优化，因此归类为LLM应用。` `模型优化` `自然语言生成`

> Position-Aware Depth Decay Decoding ($D^3$): Boosting Large Language Model Inference Efficiency

# 摘要

> 大型语言模型（LLMs）由于参数数量庞大，推理阶段需要大量资源。与需要重新训练的传统模型压缩方法不同，最近的动态计算方法表明，并非所有组件在推理时都必需，从而实现了无训练的流水线。本文专注于LLM生成的动态深度。我们提出了一种基于位置感知的分层跳过框架，能够在保持性能的同时，高效地节省1.5倍的计算量。我们发现，预测时间较晚的tokens具有较低的困惑度，因此需要的计算量较少。基于此，我们提出了一种名为位置感知深度衰减解码（$D^3$）的无训练算法，该算法利用幂律衰减函数【数学公式】来确定生成第$i$个token时需要保留的层数。无需任何重新训练，$D^3$首次在广泛的生成任务中取得了成功。在70亿参数规模的大模型（如Llama）上的实验表明，与完整的推理流水线相比，$D^3$可以实现平均1.5倍的加速，同时在GSM8K和BBH基准测试中保持几乎无性能下降（<1%）的优异表现。

> Due to the large number of parameters, the inference phase of Large Language Models (LLMs) is resource-intensive. Unlike traditional model compression, which needs retraining, recent dynamic computation methods show that not all components are required for inference, enabling a training-free pipeline. In this paper, we focus on the dynamic depth of LLM generation. A token-position aware layer skipping framework is proposed to save 1.5x times operations efficiently while maintaining performance. We first observed that tokens predicted later have lower perplexity and thus require less computation. Then, we propose a training-free algorithm called Position-Aware Depth Decay Decoding ($D^3$), which leverages a power-law decay function, $\left\lfloor L \times (α^i) \right\rfloor$, to determine the number of layers to retain when generating token $T_i$. Remarkably, without any retraining, the $D^3$ achieves success across a wide range of generation tasks for the first time. Experiments on large language models (\ie the Llama) with $7 \sim 70$ billion parameters show that $D^3$ can achieve an average 1.5x speedup compared with the full-inference pipeline while maintaining comparable performance with nearly no performance drop ($<1\%$) on the GSM8K and BBH benchmarks.

[Arxiv](https://arxiv.org/abs/2503.08524)