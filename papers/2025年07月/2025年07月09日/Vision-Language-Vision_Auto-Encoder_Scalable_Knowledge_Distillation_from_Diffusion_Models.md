# 视觉-语言-视觉自编码器：基于扩散模型的可扩展知识蒸馏

发布时间：2025年07月09日

`其他` `计算机视觉` `生成式AI`

> Vision-Language-Vision Auto-Encoder: Scalable Knowledge Distillation from Diffusion Models

# 摘要

> 构建具有强大图像描述能力的视觉-语言模型（VLM）通常需要在数十亿高质量图像-文本对上进行训练，耗时数百万GPU小时。本文提出了一种名为视觉-语言-视觉（VLV）的自动编码器框架，通过战略性地整合视觉编码器、文本到图像（T2I）扩散模型解码器和大型语言模型（LLM）等预训练组件，开创了一种全新方法。具体而言，我们通过正则化语言表示空间，在语言表示空间中引入了信息瓶颈，这一过程通过冻结预训练的T2I扩散解码器实现。我们的VLV框架利用连续嵌入，从文本条件扩散模型中提取知识，通过高质量的图像重建展示了全面的语义理解能力。此外，通过微调预训练的大型语言模型，将中间语言表示转换为详细描述，我们构建了一个与GPT-4和Gemini 2.0 Flash等领先模型相媲美的先进描述器。我们的方法不仅展示了卓越的成本效益，还大幅减少了数据需求。通过主要利用单模态图像进行训练，并充分挖掘现有预训练模型（包括图像编码器、T2I扩散模型和大型语言模型）的潜力，我们成功避免了对大规模图像-文本配对数据集的依赖，使总训练成本控制在1000美元以内。


> Building state-of-the-art Vision-Language Models (VLMs) with strong captioning capabilities typically necessitates training on billions of high-quality image-text pairs, requiring millions of GPU hours. This paper introduces the Vision-Language-Vision (VLV) auto-encoder framework, which strategically leverages key pretrained components: a vision encoder, the decoder of a Text-to-Image (T2I) diffusion model, and subsequently, a Large Language Model (LLM). Specifically, we establish an information bottleneck by regularizing the language representation space, achieved through freezing the pretrained T2I diffusion decoder. Our VLV pipeline effectively distills knowledge from the text-conditioned diffusion model using continuous embeddings, demonstrating comprehensive semantic understanding via high-quality reconstructions. Furthermore, by fine-tuning a pretrained LLM to decode the intermediate language representations into detailed descriptions, we construct a state-of-the-art (SoTA) captioner comparable to leading models like GPT-4o and Gemini 2.0 Flash. Our method demonstrates exceptional cost-efficiency and significantly reduces data requirements; by primarily utilizing single-modal images for training and maximizing the utility of existing pretrained models (image encoder, T2I diffusion model, and LLM), it circumvents the need for massive paired image-text datasets, keeping the total training expenditure under $1,000 USD.

[Arxiv](https://arxiv.org/abs/2507.07104)