# EasyRef：通过多模态 LLM 实现的用于扩散模型的全方位通用组图像参考

发布时间：2024年12月12日

`LLM应用` `图像生成` `多模态`

> EasyRef: Omni-Generalized Group Image Reference for Diffusion Models via Multimodal LLM

# 摘要

> 在扩散模型个性化方面已取得显著成果。传统的免调优方法通常将多个参考图像的图像嵌入进行平均编码作为注入条件，但这种与图像无关的操作无法实现图像间的交互，难以捕获多个参考中的一致视觉元素。虽然基于调优的低秩自适应（LoRA）能通过训练从多个图像中有效提取一致元素，但其需要针对每个不同的图像组进行特定微调。本文推出了 EasyRef，这一新颖的即插即用自适应方法，让扩散模型能以多个参考图像和文本提示为条件。为有效利用多个图像中的一致视觉元素，我们借助多模态大型语言模型（MLLM）的多图像理解和指令遵循能力，促使其依据指令捕获一致视觉元素。此外，通过适配器将 MLLM 的表示注入扩散过程，能轻松推广到未见过的领域，挖掘未见过数据中的一致视觉元素。为降低计算成本并增强细粒度细节保留，我们引入了高效的参考聚合策略和渐进式训练方案。最后，我们推出了 MRBench，这是新的多参考图像生成基准。实验结果显示，EasyRef 优于像 IP-Adapter 这样的免调优方法和像 LoRA 这样的基于调优的方法，在不同领域实现了出色的美学质量和强大的零样本泛化能力。

> Significant achievements in personalization of diffusion models have been witnessed. Conventional tuning-free methods mostly encode multiple reference images by averaging their image embeddings as the injection condition, but such an image-independent operation cannot perform interaction among images to capture consistent visual elements within multiple references. Although the tuning-based Low-Rank Adaptation (LoRA) can effectively extract consistent elements within multiple images through the training process, it necessitates specific finetuning for each distinct image group. This paper introduces EasyRef, a novel plug-and-play adaptation method that enables diffusion models to be conditioned on multiple reference images and the text prompt. To effectively exploit consistent visual elements within multiple images, we leverage the multi-image comprehension and instruction-following capabilities of the multimodal large language model (MLLM), prompting it to capture consistent visual elements based on the instruction. Besides, injecting the MLLM's representations into the diffusion process through adapters can easily generalize to unseen domains, mining the consistent visual elements within unseen data. To mitigate computational costs and enhance fine-grained detail preservation, we introduce an efficient reference aggregation strategy and a progressive training scheme. Finally, we introduce MRBench, a new multi-reference image generation benchmark. Experimental results demonstrate EasyRef surpasses both tuning-free methods like IP-Adapter and tuning-based methods like LoRA, achieving superior aesthetic quality and robust zero-shot generalization across diverse domains.

[Arxiv](https://arxiv.org/abs/2412.09618)