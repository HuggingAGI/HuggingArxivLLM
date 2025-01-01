# ST$^3$: 借助时空视觉标记修剪加快多模态大型语言模型的速度

发布时间：2024年12月28日

`LLM应用` `计算机视觉`

> ST$^3$: Accelerating Multimodal Large Language Model by Spatial-Temporal Visual Token Trimming

# 摘要

> 多模态大型语言模型（MLLMs）通过融合视觉与文本信息来提升感知能力。但处理海量的视觉标记会带来极高的计算成本。现有的对 MLLM 注意力机制的分析尚浅，致使粗粒度的标记修剪策略难以有效平衡速度与准确性。在本文中，我们借助 LLaVA 对 MLLM 注意力机制展开了全面探究。我们发现，在解码过程中，众多视觉标记和部分注意力计算是多余的。基于此，我们提出了时空视觉标记修剪（$	extbf{ST}^{3}$），这是一个无需重新训练就能加快 MLLM 推理的框架。$	extbf{ST}^{3}$包含两个主要部分：1）渐进式视觉标记修剪（	extbf{PVTP}），它能去除跨层的不被关注的视觉标记；2）视觉标记退火（	extbf{VTA}），它会随着生成标记的增多动态减少每层的视觉标记数量。这些技术协同作用，相比原始的 LLaVA，推理速度约快$\mathbf{2	imes}$，KV 缓存内存仅约为$\mathbf{30\%}$，同时在各类数据集中保持性能一致。关键在于，$	extbf{ST}^{3}$能够无缝融入现有的预训练 MLLM，为高效推理提供即插即用的解决方案。

> Multimodal large language models (MLLMs) enhance their perceptual capabilities by integrating visual and textual information. However, processing the massive number of visual tokens incurs a significant computational cost. Existing analysis of the MLLM attention mechanisms remains shallow, leading to coarse-grain token pruning strategies that fail to effectively balance speed and accuracy. In this paper, we conduct a comprehensive investigation of MLLM attention mechanisms with LLaVA. We find that numerous visual tokens and partial attention computations are redundant during the decoding process. Based on this insight, we propose Spatial-Temporal Visual Token Trimming ($\textbf{ST}^{3}$), a framework designed to accelerate MLLM inference without retraining. $\textbf{ST}^{3}$ consists of two primary components: 1) Progressive Visual Token Pruning (\textbf{PVTP}), which eliminates inattentive visual tokens across layers, and 2) Visual Token Annealing (\textbf{VTA}), which dynamically reduces the number of visual tokens in each layer as the generated tokens grow. Together, these techniques deliver around $\mathbf{2\times}$ faster inference with only about $\mathbf{30\%}$ KV cache memory compared to the original LLaVA, while maintaining consistent performance across various datasets. Crucially, $\textbf{ST}^{3}$ can be seamlessly integrated into existing pre-trained MLLMs, providing a plug-and-play solution for efficient inference.

[Arxiv](https://arxiv.org/abs/2412.20105)