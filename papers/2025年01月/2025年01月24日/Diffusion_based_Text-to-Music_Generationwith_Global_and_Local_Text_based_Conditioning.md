# 基于扩散的文本到音乐生成：全局与局部文本条件

发布时间：2025年01月24日

`LLM应用

**理由**：这篇论文主要讨论了基于扩散的文本到音乐（TTM）模型，该模型依赖于预训练的大型语言模型（如T5）和跨模态音频-语言表示模型（如CLAP）来生成音乐。虽然论文涉及了扩散模型和跨模态表示，但其核心在于利用LLM（如T5）来生成文本嵌入，并将其应用于音乐生成任务。因此，这篇论文应归类为LLM应用。` `音乐生成`

> Diffusion based Text-to-Music Generationwith Global and Local Text based Conditioning

# 摘要

> 基于扩散的文本到音乐（TTM）模型能够根据文本描述生成音乐。通常，基于UNet的扩散模型依赖于预训练的大型语言模型或跨模态音频-语言表示模型生成的文本嵌入。本文提出了一种基于扩散的TTM模型，其中UNet同时以单模态语言模型（如T5）和跨模态音频-语言表示模型（如CLAP）为条件，分别通过交叉注意力和特征线性调制（FiLM）实现。扩散模型通过训练，能够同时利用T5提供的局部文本表示和CLAP提供的全局表示。此外，我们提出了一种改进方法，通过均值池化和自注意力池化机制从T5中提取全局和局部表示，从而减少了对额外编码器（如CLAP）的需求，降低了模型参数数量。实验结果表明，与仅依赖T5局部嵌入的基线模型（KL=1.54）相比，结合CLAP全局嵌入和T5局部嵌入的模型在文本一致性上表现更优（KL=1.47）。而通过均值池化方法直接从T5局部嵌入中提取全局文本嵌入的模型，在生成质量上更胜一筹（FAD=1.89），尽管在文本一致性上略逊于同时使用CLAP和T5嵌入的模型（FAD=1.94和KL=1.47）。我们的方案不仅在效率上表现出色，而且在参数数量上也更为精简。

> Diffusion based Text-To-Music (TTM) models generate music corresponding to text descriptions. Typically UNet based diffusion models condition on text embeddings generated from a pre-trained large language model or from a cross-modality audio-language representation model. This work proposes a diffusion based TTM, in which the UNet is conditioned on both (i) a uni-modal language model (e.g., T5) via cross-attention and (ii) a cross-modal audio-language representation model (e.g., CLAP) via Feature-wise Linear Modulation (FiLM). The diffusion model is trained to exploit both a local text representation from the T5 and a global representation from the CLAP. Furthermore, we propose modifications that extract both global and local representations from the T5 through pooling mechanisms that we call mean pooling and self-attention pooling. This approach mitigates the need for an additional encoder (e.g., CLAP) to extract a global representation, thereby reducing the number of model parameters. Our results show that incorporating the CLAP global embeddings to the T5 local embeddings enhances text adherence (KL=1.47) compared to a baseline model solely relying on the T5 local embeddings (KL=1.54). Alternatively, extracting global text embeddings directly from the T5 local embeddings through the proposed mean pooling approach yields superior generation quality (FAD=1.89) while exhibiting marginally inferior text adherence (KL=1.51) against the model conditioned on both CLAP and T5 text embeddings (FAD=1.94 and KL=1.47). Our proposed solution is not only efficient but also compact in terms of the number of parameters required.

[Arxiv](https://arxiv.org/abs/2501.14680)