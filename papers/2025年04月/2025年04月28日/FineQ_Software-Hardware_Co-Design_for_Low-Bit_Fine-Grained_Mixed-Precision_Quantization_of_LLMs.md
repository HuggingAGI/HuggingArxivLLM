# FineQ：面向 LLMs 的低比特细粒度混合精度量化软硬件协同设计方案

发布时间：2025年04月28日

`其他` `计算机体系结构`

> FineQ: Software-Hardware Co-Design for Low-Bit Fine-Grained Mixed-Precision Quantization of LLMs

# 摘要

> 大型语言模型（LLMs）推动了自然语言处理领域的重大进展，但其对内存和计算资源的需求也大幅增加。量化是降低LLMs内存消耗的有效手段，但现有方法面临精度与效率的平衡难题。针对这一挑战，我们提出了FineQ，这是一种软硬件协同设计的低比特细粒度混合精度量化方案。通过将权重划分成更细粒度的簇，并引入异常值保护机制，FineQ在保持模型精度的同时优化了内存使用。此外，我们设计了一种基于时序编码的加速器，不仅提升了量化算法的支持能力，还显著降低了硬件面积和能耗。实验结果表明，FineQ在接近平均位宽的情况下，模型精度超越现有最优算法，同时实现了1.79倍的能效提升和61.2%的面积缩减。

> Large language models (LLMs) have significantly advanced the natural language processing paradigm but impose substantial demands on memory and computational resources. Quantization is one of the most effective ways to reduce memory consumption of LLMs. However, advanced single-precision quantization methods experience significant accuracy degradation when quantizing to ultra-low bits. Existing mixed-precision quantization methods are quantized by groups with coarse granularity. Employing high precision for group data leads to substantial memory overhead, whereas low precision severely impacts model accuracy. To address this issue, we propose FineQ, software-hardware co-design for low-bit fine-grained mixed-precision quantization of LLMs. First, FineQ partitions the weights into finer-grained clusters and considers the distribution of outliers within these clusters, thus achieving a balance between model accuracy and memory overhead. Then, we propose an outlier protection mechanism within clusters that uses 3 bits to represent outliers and introduce an encoding scheme for index and data concatenation to enable aligned memory access. Finally, we introduce an accelerator utilizing temporal coding that effectively supports the quantization algorithm while simplifying the multipliers in the systolic array. FineQ achieves higher model accuracy compared to the SOTA mixed-precision quantization algorithm at a close average bit-width. Meanwhile, the accelerator achieves up to 1.79x energy efficiency and reduces the area of the systolic array by 61.2%.

[Arxiv](https://arxiv.org/abs/2504.19746)