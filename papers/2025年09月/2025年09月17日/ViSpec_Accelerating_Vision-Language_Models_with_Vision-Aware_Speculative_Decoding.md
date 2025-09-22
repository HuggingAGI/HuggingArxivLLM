# ViSpec：基于视觉感知推测性解码加速视觉-语言模型

发布时间：2025年09月17日

`LLM应用` `基础理论`

> ViSpec: Accelerating Vision-Language Models with Vision-Aware Speculative Decoding

# 摘要

> 投机解码是大型语言模型（LLMs）中广泛使用的推理加速技术，但其在视觉语言模型（VLMs）中的应用尚未得到充分研究，现有方法的加速效果有限（<1.5倍）。随着多模态能力成为大规模模型的核心，这一差距愈发明显。我们假设，大型VLMs能够逐层高效过滤冗余图像信息，同时不损害文本理解能力，而较小的草稿模型则难以实现这一点。为解决这一问题，我们提出了视觉感知投机解码（ViSpec）——一种专为VLMs打造的新型框架。ViSpec引入轻量级视觉适配模块，将图像令牌压缩为紧凑表示，该表示无缝融入草稿模型的注意力机制，同时保留原始图像的位置信息。此外，我们为每个输入图像提取全局特征向量，并用该特征对所有后续文本令牌进行增强，从而提升多模态一致性。针对具有长助手回复的多模态数据集稀缺的问题，我们通过重新利用现有数据集并借助目标VLM生成扩展输出，构建了专用训练数据集。我们的训练策略还降低了草稿模型直接利用目标模型隐藏状态的风险——若仅基于目标模型输出训练，这种风险可能导致捷径学习。大量实验验证了ViSpec的有效性，据我们所知，它首次在VLM投机解码中实现了显著加速。

> Speculative decoding is a widely adopted technique for accelerating inference in large language models (LLMs), yet its application to vision-language models (VLMs) remains underexplored, with existing methods achieving only modest speedups (<1.5x). This gap is increasingly significant as multimodal capabilities become central to large-scale models. We hypothesize that large VLMs can effectively filter redundant image information layer by layer without compromising textual comprehension, whereas smaller draft models struggle to do so. To address this, we introduce Vision-Aware Speculative Decoding (ViSpec), a novel framework tailored for VLMs. ViSpec employs a lightweight vision adaptor module to compress image tokens into a compact representation, which is seamlessly integrated into the draft model's attention mechanism while preserving original image positional information. Additionally, we extract a global feature vector for each input image and augment all subsequent text tokens with this feature to enhance multimodal coherence. To overcome the scarcity of multimodal datasets with long assistant responses, we curate a specialized training dataset by repurposing existing datasets and generating extended outputs using the target VLM with modified prompts. Our training strategy mitigates the risk of the draft model exploiting direct access to the target model's hidden states, which could otherwise lead to shortcut learning when training solely on target model outputs. Extensive experiments validate ViSpec, achieving, to our knowledge, the first substantial speedup in VLM speculative decoding.

[Arxiv](https://arxiv.org/abs/2509.15235)