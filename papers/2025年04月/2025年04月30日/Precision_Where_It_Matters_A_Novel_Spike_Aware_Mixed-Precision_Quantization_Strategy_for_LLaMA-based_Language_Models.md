# 在关键处的精度：一种针对 LLaMA 基础语言模型的新型 Spike 感知混合精度量化策略

发布时间：2025年04月30日

`LLM理论

摘要讨论了大型语言模型（LLMs）的量化方法，提出了针对LLaMA架构的混合精度量化策略，属于模型优化和理论研究。` `模型部署`

> Precision Where It Matters: A Novel Spike Aware Mixed-Precision Quantization Strategy for LLaMA-based Language Models

# 摘要

> 大型语言模型 (LLMs) 在自然语言处理任务中表现卓越，但其规模庞大，为实际部署和推理带来了挑战。本文聚焦于 LLaMA 架构及其衍生模型的量化研究，挑战现有对 LLMs 激活异常的假设，并提出了一种专为 LLaMA 类模型设计的混合精度量化方法。基于 LLaMA 架构中激活峰值主要集中在特定投影层的观察，我们采用更高精度（FP16 或 FP8）处理这些关键层，同时将模型其余部分量化为更低位宽。实验结果表明，与现有量化技术相比，我们的方法在困惑度和零样本准确率方面显著提升，尤其在 8 位张量量化中表现突出。与通用方法不同，我们的架构特定量化策略在所有架构类型上均表现更优，为 LLMs 的高效部署提供了新思路， potentially enabling their use in resource-constrained environments. 本研究强调了在开发量化流水线时考虑模型特定特征的重要性，以应对最先进的语言模型。


> Large Language Models (LLMs) have demonstrated remarkable capabilities in various natural language processing tasks. However, their size presents significant challenges for deployment and inference. This paper investigates the quantization of LLMs, focusing on the LLaMA architecture and its derivatives. We challenge existing assumptions about activation outliers in LLMs and propose a novel mixed-precision quantization approach tailored for LLaMA-like models. Our method leverages the observation that activation spikes in LLaMA architectures are predominantly concentrated in specific projection layers. By applying higher precision (FP16 or FP8) to these layers while quantizing the rest of the model to lower bit-widths, we achieve superior performance compared to existing quantization techniques. Experimental results on LLaMA2, LLaMA3, and Mistral models demonstrate significant improvements in perplexity and zero-shot accuracy, particularly for 8-bit per-tensor quantization. Our approach outperforms general-purpose methods designed to handle outliers across all architecture types, highlighting the benefits of architecture-specific quantization strategies. This research contributes to the ongoing efforts to make LLMs more efficient and deployable, potentially enabling their use in resource-constrained environments. Our findings emphasize the importance of considering model-specific characteristics in developing effective quantization pipelines for state-of-the-art language models by identifying and targeting a small number of projections that concentrate activation spikes.

[Arxiv](https://arxiv.org/abs/2504.21553)