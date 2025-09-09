# Text4Seg++：借助生成式语言建模进阶图像分割

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Text4Seg++: Advancing Image Segmentation via Generative Language Modeling

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-语言任务中表现卓越，但如何将图像分割有效融入这类模型仍是一大难题。本研究提出全新的“文本即掩码”范式，将图像分割转化为文本生成任务，不仅省去了额外解码器的需求，还大幅简化了分割流程。核心创新点在于“语义描述符”——一种全新的分割掩码文本表示方式，每个图像块都会被映射到对应的文本标签。我们首先引入“图像级语义描述符”，这种与图像块对齐的分割掩码文本表示能自然融入语言建模流程。为提升效率，我们提出“行-wise游程编码（R-RLE）”，该编码能压缩冗余文本序列，将语义描述符长度缩短74%，推理速度提升【数学公式】，且性能不受影响。基于此构建的初始框架Text4Seg，在各类视觉任务中都展现出优异的分割性能。为进一步优化粒度与紧凑性，我们又提出“框级语义描述符”：通过边界框定位感兴趣区域，并借助名为“语义块”的结构化掩码令牌来表示区域掩码。这一改进催生了模型Text4Seg++，它将分割任务转化为“下一块预测”任务，兼具精度、可扩展性与生成效率。在自然和遥感数据集上的大量实验显示，Text4Seg++在各类基准测试中均持续优于当前最先进模型，且无需任何特定任务微调，同时还能与现有MLLM骨干网络兼容。本研究证实了在MLLM框架下，文本驱动图像分割具备高效性、可扩展性与普适性。

> Multimodal Large Language Models (MLLMs) have shown exceptional capabilities in vision-language tasks. However, effectively integrating image segmentation into these models remains a significant challenge. In this work, we propose a novel text-as-mask paradigm that casts image segmentation as a text generation problem, eliminating the need for additional decoders and significantly simplifying the segmentation process. Our key innovation is semantic descriptors, a new textual representation of segmentation masks where each image patch is mapped to its corresponding text label. We first introduce image-wise semantic descriptors, a patch-aligned textual representation of segmentation masks that integrates naturally into the language modeling pipeline. To enhance efficiency, we introduce the Row-wise Run-Length Encoding (R-RLE), which compresses redundant text sequences, reducing the length of semantic descriptors by 74% and accelerating inference by $3\times$, without compromising performance. Building upon this, our initial framework Text4Seg achieves strong segmentation performance across a wide range of vision tasks. To further improve granularity and compactness, we propose box-wise semantic descriptors, which localizes regions of interest using bounding boxes and represents region masks via structured mask tokens called semantic bricks. This leads to our refined model, Text4Seg++, which formulates segmentation as a next-brick prediction task, combining precision, scalability, and generative efficiency. Comprehensive experiments on natural and remote sensing datasets show that Text4Seg++ consistently outperforms state-of-the-art models across diverse benchmarks without any task-specific fine-tuning, while remaining compatible with existing MLLM backbones. Our work highlights the effectiveness, scalability, and generalizability of text-driven image segmentation within the MLLM framework.

[Arxiv](https://arxiv.org/abs/2509.06321)