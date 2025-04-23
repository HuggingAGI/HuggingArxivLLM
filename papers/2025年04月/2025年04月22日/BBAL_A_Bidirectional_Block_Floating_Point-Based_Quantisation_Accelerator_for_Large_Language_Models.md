# # BBAL：基于双向块浮点的大型语言模型量化加速器

发布时间：2025年04月22日

`LLM应用` `人工智能` `边缘计算`

> BBAL: A Bidirectional Block Floating Point-Based Quantisation Accelerator for Large Language Models

# 摘要

> 大型语言模型（LLMs）的数十亿参数使其在边缘设备上的部署面临巨大挑战，对内存和计算资源造成巨大压力。块浮点（BFP）量化通过将高开销的浮点运算转换为低比特定点运算，降低了内存和计算的开销。然而，BFP需要将所有数据对齐到最大指数，这导致了小值和中等值的丢失，从而引发了量化误差并降低了LLMs的准确性。为了解决这一问题，我们提出了一种双向块浮点（BBFP）数据格式，降低了选择最大指数作为共享指数的概率，从而减少了量化误差。通过利用BBFP的特性，我们为LLMs开发了一个完整的双向块浮点量化加速器（BBAL），主要由基于BBFP的处理元件阵列和提出的高性价比非线性计算单元组成。实验结果表明，与同类效率的异常感知加速器相比，BBAL的准确性提高了22%；而在相似的准确性下，效率提升了40%。

> Large language models (LLMs), with their billions of parameters, pose substantial challenges for deployment on edge devices, straining both memory capacity and computational resources. Block Floating Point (BFP) quantisation reduces memory and computational overhead by converting high-overhead floating point operations into low-bit fixed point operations. However, BFP requires aligning all data to the maximum exponent, which causes loss of small and moderate values, resulting in quantisation error and degradation in the accuracy of LLMs. To address this issue, we propose a Bidirectional Block Floating Point (BBFP) data format, which reduces the probability of selecting the maximum as shared exponent, thereby reducing quantisation error. By utilizing the features in BBFP, we present a full-stack Bidirectional Block Floating Point-Based Quantisation Accelerator for LLMs (BBAL), primarily comprising a processing element array based on BBFP, paired with proposed cost-effective nonlinear computation unit. Experimental results show BBAL achieves a 22% improvement in accuracy compared to an outlier-aware accelerator at similar efficiency, and a 40% efficiency improvement over a BFP-based accelerator at similar accuracy.

[Arxiv](https://arxiv.org/abs/2504.15721)