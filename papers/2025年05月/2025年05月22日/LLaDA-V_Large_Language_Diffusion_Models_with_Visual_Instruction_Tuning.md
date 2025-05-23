# # LLaDA-V：视觉指令微调的大型语言扩散模型

发布时间：2025年05月22日

`LLM应用` `人工智能`

> LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning

# 摘要

> 我们提出了 LLaDA-V，一个纯粹基于扩散的多模态大语言模型（MLLM），它结合了视觉指令调优与掩码扩散模型，与当前主流的自回归范式有所不同。LLaDA-V 基于 LLaDA（一种大型语言扩散模型）构建，通过视觉编码器和 MLP 连接器将视觉特征投影到语言嵌入空间，实现多模态对齐。我们的研究发现：尽管 LLaDA-V 在纯文本任务上的表现弱于 LLaMA3-8B 和 Qwen2-7B，但在多模态任务中表现出色。在相同指令数据训练下，LLaDA-V 与 LLaMA3-V 具有高度竞争力，且在数据扩展性上更优，性能差距缩小，证明了其架构的有效性。此外，LLaDA-V 在多模态理解方面达到当前最优水平，优于现有混合自回归-扩散和纯粹基于扩散的 MLLM。这表明大型语言扩散模型在多模态领域具有潜力，值得进一步研究。项目页面和代码：https://ml-gsai.github.io/LLaDA-V-demo/。

> In this work, we introduce LLaDA-V, a purely diffusion-based Multimodal Large Language Model (MLLM) that integrates visual instruction tuning with masked diffusion models, representing a departure from the autoregressive paradigms dominant in current multimodal approaches. Built upon LLaDA, a representative large language diffusion model, LLaDA-V incorporates a vision encoder and MLP connector that projects visual features into the language embedding space, enabling effective multimodal alignment. Our empirical investigation reveals several intriguing results: First, LLaDA-V demonstrates promising multimodal performance despite its language model being weaker on purely textual tasks than counterparts like LLaMA3-8B and Qwen2-7B. When trained on the same instruction data, LLaDA-V is highly competitive to LLaMA3-V across multimodal tasks with better data scalability. It also narrows the performance gap to Qwen2-VL, suggesting the effectiveness of its architecture for multimodal tasks. Second, LLaDA-V achieves state-of-the-art performance in multimodal understanding compared to existing hybrid autoregressive-diffusion and purely diffusion-based MLLMs. Our findings suggest that large language diffusion models show promise in multimodal contexts and warrant further investigation in future research. Project page and codes: https://ml-gsai.github.io/LLaDA-V-demo/.

[Arxiv](https://arxiv.org/abs/2505.16933)