# 大型语言模型的块循环移位适配器

发布时间：2025年05月01日

`LLM理论

论文摘要讨论了微调大型语言模型的方法，提出了一种基于块循环矩阵和频域方法的新技术，以降低存储和计算成本。这属于对大型语言模型训练机制的理论研究，因此归类为LLM理论。` `计算机科学` `算法优化`

> Block Circulant Adapter for Large Language Models

# 摘要

> 微调大型语言模型（LLMs）因模型规模庞大而困难重重。近期频域方法展现出降低微调成本的潜力。我们提出了一种基于块循环矩阵的微调方法，结合稳定训练策略，利用循环矩阵和一维傅里叶变换特性，有效降低存储和计算成本。实验表明，与VeRA相比，我们的方法参数量减少$14	imes$，与LoRA相比减少$16	imes$，与FourierFT相比FLOPs减少$32	imes$，同时保持相近或更优的任务性能。这为在频域对大模型进行下游任务微调提供了有前景的新途径。

> Fine-tuning large language models (LLMs) is difficult due to their huge model size. Recent Fourier domain-based methods show potential for reducing fine-tuning costs. We propose a block circulant matrix-based fine-tuning method with a stable training heuristic to leverage the properties of circulant matrices and one-dimensional Fourier transforms to reduce storage and computation costs. Experiments show that our method uses $14\times$ less number of parameters than VeRA, $16\times$ smaller than LoRA and $32\times$ less FLOPs than FourierFT, while maintaining close or better task performance. Our approach presents a promising way in frequency domain to fine-tune large models on downstream tasks.

[Arxiv](https://arxiv.org/abs/2505.00582)