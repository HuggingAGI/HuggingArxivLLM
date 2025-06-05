# 基于固定文本编码器的语言-图像对齐

发布时间：2025年06月04日

`LLM应用` `计算机视觉`

> Language-Image Alignment with Fixed Text Encoders

# 摘要

> 当前，建立语言与图像对齐的主流方法是通过对比学习（如CLIP及其变体）同时预训练文本和图像编码器。本研究质疑这种高成本的联合训练是否必要。具体来说，我们探讨能否利用预训练好的固定大型语言模型（LLM）作为优秀的文本编码器来指导视觉表示学习。为此，我们提出了一种仅训练图像编码器、从LLM中学习语言-图像对齐（LIFT）的方法。令人惊喜的是，通过全面的基准测试和消融研究，我们发现这种大幅简化的框架LIFT表现优异。在涉及组合理解和长描述的大多数场景中，LIFT优于CLIP，同时计算效率显著提升。本研究首次系统探索了LLM文本嵌入如何指导视觉学习，并为学习语言对齐的视觉表示提供了新的设计思路。

> Currently, the most dominant approach to establishing language-image alignment is to pre-train text and image encoders jointly through contrastive learning, such as CLIP and its variants. In this work, we question whether such a costly joint training is necessary. In particular, we investigate if a pre-trained fixed large language model (LLM) offers a good enough text encoder to guide visual representation learning. That is, we propose to learn Language-Image alignment with a Fixed Text encoder (LIFT) from an LLM by training only the image encoder. Somewhat surprisingly, through comprehensive benchmarking and ablation studies, we find that this much simplified framework LIFT is highly effective and it outperforms CLIP in most scenarios that involve compositional understanding and long captions, while achieving considerable gains in computational efficiency. Our work takes a first step towards systematically exploring how text embeddings from LLMs can guide visual learning and suggests an alternative design choice for learning language-aligned visual representations.

[Arxiv](https://arxiv.org/abs/2506.04209)