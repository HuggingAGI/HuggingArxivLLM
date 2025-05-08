# 加速长上下文LLM推理：AccLLM——算法与硬件协同设计的创新方案

发布时间：2025年04月06日

`LLM应用` `边缘计算` `硬件加速`

> AccLLM: Accelerating Long-Context LLM Inference Via Algorithm-Hardware Co-Design

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域取得了巨大成功，推动了将其部署从云端扩展到边缘设备的需求。然而，在资源受限的边缘设备上部署 LLMs 面临三大挑战：计算密集型和巨大模型规模、自回归生成过程带来的内存和带宽需求，以及处理长序列的有限扩展性。针对这些挑战，我们提出了 AccLLM，一个通过算法和硬件协同设计实现高效快速长上下文 LLM 推理的全面加速框架。在算法层面，我们采用剪枝、Λ 形注意力和创新的 W2A8KV4 量化方案，有效降低资源需求并提升长序列生成能力。在硬件层面，我们设计了基于 FPGA 的专用加速器，配备可重构计算引擎，灵活适应各种运算，充分实现算法创新的硬件效率。实验结果表明，AccLLM 在 Xilinx Alveo U280 FPGA 上实现了 4.07 倍的能效和 2.98 倍的吞吐量提升，超越现有技术。

> Recently, large language models (LLMs) have achieved huge success in the natural language processing (NLP) field, driving a growing demand to extend their deployment from the cloud to edge devices. However, deploying LLMs on resource-constrained edge devices poses significant challenges, including (1) intensive computations and huge model sizes, (2) great memory and bandwidth demands introduced by the autoregressive generation process, and (3) limited scalability for handling long sequences. To address these challenges, we propose AccLLM, a comprehensive acceleration framework that enables efficient and fast long-context LLM inference through algorithm and hardware co-design. At the algorithmic level, we integrate (1) pruning, (2) Λ-shaped attention, and (3) an innovative W2A8KV4 (2-bit weights, 8-bit activations, and 4-bit KV cache) quantization scheme, thus effectively reducing memory and bandwidth requirements while facilitating LLMs' long-sequence generation. At the hardware level, we design a dedicated FPGA-based accelerator with a reconfigurable computing engine to effectively and flexibly accommodate diverse operations arising from our compression algorithm, thereby fully translating the algorithmic innovations into tangible hardware efficiency. We validate AccLLM on the Xilinx Alveo U280 FPGA, demonstrating a 4.07x energy efficiency and a 2.98x throughput compared to the state-of-the-art work FlightLLM.

[Arxiv](https://arxiv.org/abs/2505.03745)