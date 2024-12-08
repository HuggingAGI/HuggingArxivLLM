# 交错模态的思维链条

发布时间：2024年11月29日

`LLM应用` `视觉语言模型` `多模态推理`

> Interleaved-Modal Chain-of-Thought

# 摘要

> 链思维（CoT）提示能让大型语言模型（LLMs）在得出最终答案前生成一系列中间推理步骤。然而，在转向视觉语言模型（VLMs）时，其纯文本的推理依据难以表达与原始图像的细粒度关联。本文中，我们提出了一种融入图像的多模态链思维，称作【交错模态链思维（ICoT）】，它生成由成对的视觉和文本推理依据组成的顺序推理步骤来推断最终答案。直观来看，新颖的 ICoT 要求 VLMs 能够生成细粒度的交错模态内容，这对当下的 VLMs 而言很难做到。鉴于所需的视觉信息通常是输入图像的一部分，我们提出【注意力驱动选择（ADS）】来在现有 VLMs 上实现 ICoT。ADS 能智能地插入输入图像的区域，生成交错模态推理步骤，且附加延迟可忽略不计。ADS 仅依赖 VLMs 的注意力图，无需参数化，所以它是一种即插即用的策略，能推广到一系列 VLMs。我们将 ADS 应用于两种不同架构的热门 VLMs 来实现 ICoT。对三个基准的广泛评估显示，与现有的多模态 CoT 提示方法相比，ICoT 提示实现了显著的性能提升（高达 14%）和可解释性改进。

> Chain-of-Thought (CoT) prompting elicits large language models (LLMs) to produce a series of intermediate reasoning steps before arriving at the final answer. However, when transitioning to vision-language models (VLMs), their text-only rationales struggle to express the fine-grained associations with the original image. In this paper, we propose an image-incorporated multimodal Chain-of-Thought, named \textbf{Interleaved-modal Chain-of-Thought (ICoT)}, which generates sequential reasoning steps consisting of paired visual and textual rationales to infer the final answer. Intuitively, the novel ICoT requires VLMs to enable the generation of fine-grained interleaved-modal content, which is hard for current VLMs to fulfill. Considering that the required visual information is usually part of the input image, we propose \textbf{Attention-driven Selection (ADS)} to realize ICoT over existing VLMs. ADS intelligently inserts regions of the input image to generate the interleaved-modal reasoning steps with ignorable additional latency. ADS relies solely on the attention map of VLMs without the need for parameterization, and therefore it is a plug-and-play strategy that can be generalized to a spectrum of VLMs. We apply ADS to realize ICoT on two popular VLMs of different architectures. Extensive evaluations of three benchmarks have shown that ICoT prompting achieves substantial performance (up to 14\%) and interpretability improvements compared to existing multimodal CoT prompting methods.

[Arxiv](https://arxiv.org/abs/2411.19488)