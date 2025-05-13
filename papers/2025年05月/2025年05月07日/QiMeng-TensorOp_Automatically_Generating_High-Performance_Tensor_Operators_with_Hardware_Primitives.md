# # 齐蒙-TensorOp：自动生成高性能张量操作符的硬件原语

发布时间：2025年05月07日

`LLM应用` `人工智能` `计算机体系结构`

> QiMeng-TensorOp: Automatically Generating High-Performance Tensor Operators with Hardware Primitives

# 摘要

> 计算密集型张量运算占据了大语言模型和深度神经网络中超过90%的计算任务。对于RISC-V、ARM和GPU等多样且不断演进的硬件架构，高效自动生成基于硬件原语的高性能张量运算是至关重要的。尽管LLMs擅长生成高级语言代码，但它们难以完全理解硬件特性并生成高性能张量运算。我们引入了一个基于一行用户提示的张量运算自动生成框架（QiMeng-TensorOp），它使LLMs能够自动利用硬件特性生成基于硬件原语的张量运算，并在多种硬件上调整参数以达到最佳性能。实验结果表明，与原生LLMs相比，QiMeng-TensorOp实现了高达【数学公式】倍的性能提升。即使与人类专家相比，QiMeng-TensorOp在RISC-V CPU上达到了OpenBLAS的【数学公式】%，在NVIDIA GPU上达到了cuBLAS的【数学公式】%。此外，与人类专家相比，QiMeng-TensorOp还显著降低了开发成本，减少了【数学公式】倍的开发工作量。

> Computation-intensive tensor operators constitute over 90\% of the computations in Large Language Models (LLMs) and Deep Neural Networks.Automatically and efficiently generating high-performance tensor operators with hardware primitives is crucial for diverse and ever-evolving hardware architectures like RISC-V, ARM, and GPUs, as manually optimized implementation takes at least months and lacks portability.LLMs excel at generating high-level language codes, but they struggle to fully comprehend hardware characteristics and produce high-performance tensor operators. We introduce a tensor-operator auto-generation framework with a one-line user prompt (QiMeng-TensorOp), which enables LLMs to automatically exploit hardware characteristics to generate tensor operators with hardware primitives, and tune parameters for optimal performance across diverse hardware. Experimental results on various hardware platforms, SOTA LLMs, and typical tensor operators demonstrate that QiMeng-TensorOp effectively unleashes the computing capability of various hardware platforms, and automatically generates tensor operators of superior performance. Compared with vanilla LLMs, QiMeng-TensorOp achieves up to $1291 \times$ performance improvement. Even compared with human experts, QiMeng-TensorOp could reach $251 \%$ of OpenBLAS on RISC-V CPUs, and $124 \%$ of cuBLAS on NVIDIA GPUs. Additionally, QiMeng-TensorOp also significantly reduces development costs by $200 \times$ compared with human experts.

[Arxiv](https://arxiv.org/abs/2505.06302)