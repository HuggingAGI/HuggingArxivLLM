# BREEN: 桥接高效无编码器多模态学习与可学习查询

发布时间：2025年03月16日

`LLM理论` `计算机视觉` `多模态学习`

> BREEN: Bridge Data-Efficient Encoder-Free Multimodal Learning with Learnable Queries

# 摘要

> 无编码器的多模态大规模语言模型（MLLMs）通过直接处理图像令牌，省去了训练视觉编码器的必要。虽然这降低了计算开销和模型复杂度，但也需要大量数据来捕捉视觉模型（如CLIP）通常编码的视觉知识。缺乏视觉编码器意味着模型可能需要依赖大量数据来学习视觉-语义对齐。我们提出了BREEN，一种数据高效的无编码器多模态架构，有效解决了这一问题。BREEN通过可学习查询和图像专家，以显著减少的训练数据实现与现有方法相当的性能。可学习查询位于图像令牌和文本令牌之间，通过预训练的CLIP模型输出进行监督，蒸馏视觉知识，弥合视觉和文本模态之间的差距。图像专家独立处理图像令牌和可学习查询，提高了效率，减少了对LLM文本能力的干扰。BREEN仅使用1300万张文本-图像配对进行训练，约为现有方法所需数据量的百分之一，即可达到与先前无编码器最先进模型（如Mono-InternVL）相当的性能。我们的工作展示了数据高效无编码器多模态学习的有前景方向，为传统的编码器方法提供了替代方案。

> Encoder-free multimodal large language models(MLLMs) eliminate the need for a well-trained vision encoder by directly processing image tokens before the language model. While this approach reduces computational overhead and model complexity, it often requires large amounts of training data to effectively capture the visual knowledge typically encoded by vision models like CLIP. The absence of a vision encoder implies that the model is likely to rely on substantial data to learn the necessary visual-semantic alignments. In this work, we present BREEN, a data-efficient encoder-free multimodal architecture that mitigates this issue. BREEN leverages a learnable query and image experts to achieve comparable performance with significantly less training data. The learnable query, positioned between image and text tokens, is supervised by the output of a pretrained CLIP model to distill visual knowledge, bridging the gap between visual and textual modalities. Additionally, the image expert processes image tokens and learnable queries independently, improving efficiency and reducing interference with the LLM's textual capabilities. BREEN achieves comparable performance to prior encoder-free state-of-the-art models like Mono-InternVL, using only 13 million text-image pairs in training about one percent of the data required by existing methods. Our work highlights a promising direction for data-efficient encoder-free multimodal learning, offering an alternative to traditional encoder-based approaches.

[Arxiv](https://arxiv.org/abs/2503.12446)