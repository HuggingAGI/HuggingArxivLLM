# 基于张量-列分解的LLMs压缩技术在群向量脉动加速器上的实现

发布时间：2025年01月31日

`LLM应用

**解释**：这篇论文主要讨论了如何通过张量-训练分解（TTD）方法来优化大型语言模型（LLMs）的资源消耗，并在FPGA上实现硬件加速。这属于LLM在实际应用中的优化和部署问题，因此归类为LLM应用。` `硬件加速` `模型压缩`

> A Tensor-Train Decomposition based Compression of LLMs on Group Vector Systolic Accelerator

# 摘要

> 大型语言模型（LLMs）在存储和计算上均需求巨大，给资源受限的硬件部署带来了严峻挑战。本文针对LLMs中资源消耗大户——线性层，提出了张量-训练分解（TTD）方法，并在FPGA上实现了硬件加速。TTD压缩应用于ChatGLM3-6B和LLaMA2-7B模型，整体网络压缩比分别达到1.94$	imes$和1.60$	imes$。压缩后的模型在FPGA上采用高效组向量脉动阵列（GVSA）架构运行，该架构具备DSP共享并行向量PEs以支持TTD推理，并优化了加速器内部的数据通信。实验显示，基于TTD的LLM加速器在FPGA上运行后，ChatGLM3-6B和LLaMA2-7B模型的首个token延迟分别降低了1.45$	imes$和1.57$	imes$。

> Large language models (LLMs) are both storage-intensive and computation-intensive, posing significant challenges when deployed on resource-constrained hardware. As linear layers in LLMs are mainly resource consuming parts, this paper develops a tensor-train decomposition (TTD) for LLMs with a further hardware implementation on FPGA. TTD compression is applied to the linear layers in ChatGLM3-6B and LLaMA2-7B models with compression ratios (CRs) for the whole network 1.94$\times$ and 1.60$\times$, respectively. The compressed LLMs are further implemented on FPGA hardware within a highly efficient group vector systolic array (GVSA) architecture, which has DSP-shared parallel vector PEs for TTD inference, as well as optimized data communication in the accelerator. Experimental results show that the corresponding TTD based LLM accelerator implemented on FPGA achieves 1.45$\times$ and 1.57$\times$ reduction in first token delay for ChatGLM3-6B and LLaMA2-7B models, respectively.

[Arxiv](https://arxiv.org/abs/2501.19135)