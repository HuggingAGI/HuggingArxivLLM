# MicroMix: 面向大型语言模型的高效混合精度量化方法，采用微缩格式实现

发布时间：2025年08月04日

`LLM应用` `计算机科学` `人工智能`

> MicroMix: Efficient Mixed-Precision Quantization with Microscaling Formats for Large Language Models

# 摘要

> 量化技术通过以低精度矩阵替代高精度矩阵，显著提升了大型语言模型（LLMs）的推理速度。近期权重-激活量化研究主要集中在将权重与激活同时转换为INT4格式。尽管NVIDIA Blackwell架构中的新FP4 Tensor Cores相比FP16实现了最高4倍的加速，但现有基于INT4的内核因数据格式不匹配而未能充分发挥这一优势。为填补这一空白，我们推出了MicroMix——一个基于Microscaling（MX）数据格式的协同设计混合精度量化算法和矩阵乘法内核。针对Blackwell架构优化，MicroMix内核支持MXFP4、MXFP6与MXFP8通道的任意组合，并输出BFloat16结果。为了在每个线性层中实现精度与效率的完美平衡，我们引入了量化阈值，用于识别使用较低精度格式（MXFP4或MXFP6）会导致过大量化误差的激活元素。我们的算法通过选择性分配更高精度通道，在保持计算效率的同时确保了模型精度。MicroMix在零-shot与few-shot学习、语言建模、代码生成和数学推理等多种任务中展现了卓越性能。在消费级（RTX 5070Ti 笔记本）和服务器级（RTX 5090）GPU上，MicroMix内核相比TensorRT-FP8实现了至少20%的性能提升。此外，应用于Llama与Qwen模型时，MicroMix在不同批量大小下均显著优于TensorRT基线，提升了预填延迟与内存效率。我们的代码已开源，地址为https://github.com/lwy2020/MicroMix。

> Quantization significantly accelerates inference in large language models (LLMs) by replacing original high-precision matrices with low-precision counterparts. Recent advances in weight-activation quantization have primarily focused on mapping both weights and activations to the INT4 format. Although the new FP4 Tensor Cores in NVIDIA's Blackwell architecture offer up to 4x speedup over FP16, existing INT4-based kernels fail to fully exploit this capability due to mismatched data formats. To bridge this gap, we propose MicroMix, a co-designed mixed-precision quantization algorithm and matrix multiplication kernel based on Microscaling (MX) data formats. Tailored for the Blackwell architecture, the MicroMix kernel supports arbitrary combinations of MXFP4, MXFP6, and MXFP8 channels, and produces BFloat16 outputs. To achieve a favorable trade-off between accuracy and efficiency for each linear layer, we introduce quantization thresholds that identify activation elements where lower-precision formats (MXFP4 or MXFP6) incur excessive quantization error. Our algorithm selectively allocates higher-precision channels to preserve accuracy while maintaining compute efficiency. MicroMix achieves competitive or superior performance across diverse downstream tasks, including zero-shot and few-shot learning, language modeling, code generation, and mathematical reasoning. On both consumer-grade (RTX 5070Ti laptop) and server-grade (RTX 5090) GPUs, our kernel delivers at least 20% faster execution than TensorRT-FP8. Furthermore, when applied to various Llama and Qwen models, MicroMix consistently improves prefill latency and memory efficiency across a range of batch sizes compared to TensorRT baselines. Our code is available at https://github.com/lwy2020/MicroMix.

[Arxiv](https://arxiv.org/abs/2508.02343)