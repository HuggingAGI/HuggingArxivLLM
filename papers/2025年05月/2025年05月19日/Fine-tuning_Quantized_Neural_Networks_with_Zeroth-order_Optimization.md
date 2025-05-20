# 通过零阶优化方法微调量化神经网络

发布时间：2025年05月19日

`LLM应用

论文摘要：随着大型语言模型规模的指数级增长，GPU内存已成为限制模型适应下游任务的瓶颈。本文提出了一种统一框架，通过最小化模型权重、梯度和优化器状态的内存占用，重新定义内存高效训练的极限。我们采用零阶优化方法，通过在前向传播中扰动权重来近似梯度方向，从而消除梯度和优化器状态。为了减少权重的内存占用，我们引入模型量化技术，例如将bfloat16转换为int4。然而，直接将零阶优化应用于量化权重面临精度差距的挑战，需要复杂的去量化和重新量化过程。为解决这一难题，我们提出了量化零阶优化（QZO），该方法通过扰动连续量化尺度进行梯度估计，并采用方向导数剪裁策略稳定训练过程。QZO与现有的基于标量和基于代码本的后训练量化方法相互兼容。与bfloat16的全参数微调相比，QZO使4位LLM的总内存成本降低超过18$	imes$，并成功实现了在单个24GB GPU上微调Llama-2-13B和Stable Diffusion 3.5 Large。

LLM应用` `人工智能`

> Fine-tuning Quantized Neural Networks with Zeroth-order Optimization

# 摘要

> 随着大型语言模型规模的指数级增长，GPU内存已成为限制模型适应下游任务的瓶颈。本文提出了一种统一框架，通过最小化模型权重、梯度和优化器状态的内存占用，重新定义内存高效训练的极限。我们采用零阶优化方法，通过在前向传播中扰动权重来近似梯度方向，从而消除梯度和优化器状态。为了减少权重的内存占用，我们引入模型量化技术，例如将bfloat16转换为int4。然而，直接将零阶优化应用于量化权重面临精度差距的挑战，需要复杂的去量化和重新量化过程。为解决这一难题，我们提出了量化零阶优化（QZO），该方法通过扰动连续量化尺度进行梯度估计，并采用方向导数剪裁策略稳定训练过程。QZO与现有的基于标量和基于代码本的后训练量化方法相互兼容。与bfloat16的全参数微调相比，QZO使4位LLM的总内存成本降低超过18$	imes$，并成功实现了在单个24GB GPU上微调Llama-2-13B和Stable Diffusion 3.5 Large。

> As the size of large language models grows exponentially, GPU memory has become a bottleneck for adapting these models to downstream tasks. In this paper, we aim to push the limits of memory-efficient training by minimizing memory usage on model weights, gradients, and optimizer states, within a unified framework. Our idea is to eliminate both gradients and optimizer states using zeroth-order optimization, which approximates gradients by perturbing weights during forward passes to identify gradient directions. To minimize memory usage on weights, we employ model quantization, e.g., converting from bfloat16 to int4. However, directly applying zeroth-order optimization to quantized weights is infeasible due to the precision gap between discrete weights and continuous gradients, which would otherwise require de-quantization and re-quantization. To overcome this challenge, we propose Quantized Zeroth-order Optimization (QZO), a novel approach that perturbs the continuous quantization scale for gradient estimation and uses a directional derivative clipping method to stabilize training. QZO is orthogonal to both scalar-based and codebook-based post-training quantization methods. Compared to full-parameter fine-tuning in bfloat16, QZO can reduce the total memory cost by more than 18$\times$ for 4-bit LLMs, and enables fine-tuning Llama-2-13B and Stable Diffusion 3.5 Large within a single 24GB GPU.

[Arxiv](https://arxiv.org/abs/2505.13430)