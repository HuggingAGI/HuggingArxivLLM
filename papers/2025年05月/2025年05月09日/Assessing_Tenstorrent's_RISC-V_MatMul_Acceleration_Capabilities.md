# 评估Tenstorrent RISC-V矩阵乘法加速能力

发布时间：2025年05月09日

`LLM应用

摘要讨论了生成式AI对LLM服务的需求以及硬件架构的优化，属于LLM的应用层面。` `人工智能` `硬件架构`

> Assessing Tenstorrent's RISC-V MatMul Acceleration Capabilities

# 摘要

> 生成式 AI 的需求激增推动了对大型语言模型 (LLM) 服务的支持，同时也促使专用硬件架构的发展以优化计算效率和能源消耗。本文研究了 Tenstorrent Grayskull e75 RISC-V 加速器在低精度计算下的性能表现，这是 LLM 运算中的核心环节。通过深入分析 Grayskull 的执行机制、矩阵规模、数据格式及其精度对效率的影响，我们揭示了其独特优势。与 Intel Sapphire Rapids 处理器和 NVIDIA V100/A100 GPU 等顶尖架构对比，尽管 NVIDIA GPU 在 raw 性能上更胜一筹，但 Grayskull 在能效比方面表现出色，峰值达到 1.55 TFLOPs/Watt（BF16 精度），展现出强大的竞争力。

> The increasing demand for generative AI as Large Language Models (LLMs) services has driven the need for specialized hardware architectures that optimize computational efficiency and energy consumption. This paper evaluates the performance of the Tenstorrent Grayskull e75 RISC-V accelerator for basic linear algebra kernels at reduced numerical precision, a fundamental operation in LLM computations. We present a detailed characterization of Grayskull's execution model, gridsize, matrix dimensions, data formats, and numerical precision impact computational efficiency. Furthermore, we compare Grayskull's performance against state-of-the-art architectures with tensor acceleration, including Intel Sapphire Rapids processors and two NVIDIA GPUs (V100 and A100). Whilst NVIDIA GPUs dominate raw performance, Grayskull demonstrates a competitive trade-off between power consumption and computational throughput, reaching a peak of 1.55 TFLOPs/Watt with BF16.

[Arxiv](https://arxiv.org/abs/2505.06085)