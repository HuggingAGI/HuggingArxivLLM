# MVDRAM: 创新性地在原生DRAM中实现张量矩阵乘法执行，专为低比特LLM加速而设计

发布时间：2025年03月31日

`LLM应用` `人工智能` `计算机硬件`

> MVDRAM: Enabling GeMV Execution in Unmodified DRAM for Low-Bit LLM Acceleration

# 摘要

> 通用矩阵向量乘法（GeMV）仍是大语言模型（LLM）推理中的关键瓶颈，即使在量化低比特模型中也不例外。基于DRAM的处理技术（PUD）作为一种内DRAM计算方法，能够将设备上的DRAM转变为GeMV引擎，为未修改DRAM的消费设备提供高吞吐量处理能力。然而，在LLM推理管道中应用PUD进行GeMV操作时，前后会产生显著的开销，削弱了其高吞吐量的优势。

    本文提出MVDRAM，首个利用未修改DRAM加速低比特LLM推理中GeMV操作的实际系统。通过挖掘GeMV操作中的数据共享模式和数学线性特性，MVDRAM协调处理器与DRAM，消除了传统PUD方法中预排列输入和输出位转置的开销。实验结果表明，在低比特（低于4比特）LLM的GeMV操作中，MVDRAM的推理速度优于基于处理器的实现。具体而言，MVDRAM在低比特GeMV操作中实现了最高7.29×的速度提升和30.5×的能效提升。对于端到端LLM推理，MVDRAM分别实现了2.18×和1.31×的吞吐量提升，以及3.04×和2.35×的能效提升，适用于2比特和4比特量化低比特模型。MVDRAM展示了标准DRAM作为LLM加速器的潜力，有望重新定义AI硬件的未来格局。
    

> General matrix-vector multiplication (GeMV) remains a critical latency bottleneck in large language model (LLM) inference, even with quantized low-bit models. Processing-Using-DRAM (PUD), an analog in-DRAM computing technique, has the potential to repurpose on-device DRAM as a GeMV engine, offering additional high-throughput processing capabilities to widespread consumer devices without DRAM modifications. However, applying PUD to GeMV operations in the LLM inference pipeline incurs significant overheads $\textit{before}$ and $\textit{after}$ in-DRAM computation, diminishing the benefits of its high-throughput processing capabilities.
  This paper presents MVDRAM, the first practical system to accelerate GeMV operations for low-bit LLM inference using unmodified DRAM. By leveraging the data sharing patterns and mathematical linearity in GeMV operations, MVDRAM orchestrates the processor and DRAM to eliminate the costs associated with pre-arranging inputs and bit-transposition of outputs required in conventional PUD approaches. Our experimental evaluation with four DDR4 DRAM modules shows that MVDRAM achieves comparable or even better inference speed than the processor-based implementation for GeMV operations in low-bit (under 4-bit) LLM. In particular, MVDRAM achieves up to 7.29$\times$ speedup and 30.5$\times$ energy efficiency for low-bit GeMV operations. For end-to-end LLM inference, MVDRAM achieves 2.18$\times$ and 1.31$\times$ throughput improvements, along with 3.04$\times$ and 2.35$\times$ energy efficiency, for 2-bit and 4-bit quantized low-bit models, respectively. MVDRAM has the potential to redefine the AI hardware landscape by demonstrating the feasibility of standard DRAM as an LLM accelerator.

[Arxiv](https://arxiv.org/abs/2503.23817)