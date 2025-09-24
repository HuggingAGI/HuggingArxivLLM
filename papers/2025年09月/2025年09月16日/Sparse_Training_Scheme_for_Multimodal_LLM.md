# 多模态大型语言模型的稀疏训练方案

发布时间：2025年09月16日

`其他` `基础理论`

> Sparse Training Scheme for Multimodal LLM

# 摘要

> 多模态大型语言模型（MLLMs）在众多领域已展现出卓越性能。但训练这类模型时，多模态数据带来的超长输入序列以及层间计算利用率低的问题，常导致训练效率低下。为此，我们将目光投向训练过程本身，提出了一种基于稀疏表示的高效训练新框架——稀疏训练方案（STS）。该方案包含两大核心组件：视觉令牌压缩器，通过压缩视觉令牌降低信息负载；层动态跳过器，通过在语言模型的前向与反向传播中动态跳过冗余层，减少计算开销。该方法适用于多种MLLM架构，且在多个基准测试中经过充分验证，展现出优异的效果与效率。

> Multimodal Large Language Models (MLLMs) have demonstrated outstanding performance across a variety of domains. However, training MLLMs is often inefficient due to the significantly longer input sequences introduced by multimodal data and the low utilization of inter-layer computations. To address this challenge, we shift the focus to the training process itself and propose a novel training-efficient framework based on sparse representations, termed the Sparse Training Scheme (STS). This scheme consists of two key components: the Visual Token Compressor, which reduces the information load by compressing visual tokens, and the Layer Dynamic Skipper, which mitigates the computational overhead by dynamically skipping unnecessary layers in the language model during both forward and backward passes. Our approach is broadly applicable to diverse MLLM architectures and has been extensively evaluated on multiple benchmarks, demonstrating its effectiveness and efficiency.

[Arxiv](https://arxiv.org/abs/2509.18150)