# ClusComp：模型压缩与高效微调的简易范式

发布时间：2025年03月17日

`LLM应用` `模型压缩` `边缘计算`

> ClusComp: A Simple Paradigm for Model Compression and Efficient Finetuning

# 摘要

> 随着大型语言模型（LLMs）的扩展，模型压缩在边缘部署和应用中至关重要。仅通过权重量化虽能减小模型体积，但低位宽时性能下降明显。此外，标准微调难以直接应用于量化模型，替代方法也常无法达到完整微调的效果。本文提出ClusComp，一种简单而有效的压缩方法，通过将权重矩阵聚类为代码本并逐块微调，实现高效压缩与优化。ClusComp具备三大优势：（1）在2-4位量化中表现优异，（2）压缩至1位时仍超越现有超低位方法，且仅需少量微调，（3）微调效率显著，甚至超越现有量化方法，与完整FP16微调相媲美。值得注意的是，ClusComp能在单张A6000-48GB GPU上实现700亿参数模型的压缩与微调。

> As large language models (LLMs) scale, model compression is crucial for edge deployment and accessibility. Weight-only quantization reduces model size but suffers from performance degradation at lower bit widths. Moreover, standard finetuning is incompatible with quantized models, and alternative methods often fall short of full finetuning. In this paper, we propose ClusComp, a simple yet effective compression paradigm that clusters weight matrices into codebooks and finetunes them block-by-block. ClusComp (1) achieves superior performance in 2-4 bit quantization, (2) pushes compression to 1-bit while outperforming ultra-low-bit methods with minimal finetuning, and (3) enables efficient finetuning, even surpassing existing quantization-based approaches and rivaling full FP16 finetuning. Notably, ClusComp supports compression and finetuning of 70B LLMs on a single A6000-48GB GPU.

[Arxiv](https://arxiv.org/abs/2503.13089)