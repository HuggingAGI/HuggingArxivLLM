# 表示学习你需要的全部，就是 NdLinear

发布时间：2025年03月21日

`LLM应用` `知识图谱`

> NdLinear Is All You Need for Representation Learning

# 摘要

> <翻译失败>

> Many high-impact machine learning tasks involve multi-dimensional data (e.g., images, volumetric medical scans, multivariate time-series). Yet, most neural architectures flatten inputs, discarding critical cross-dimension information. We introduce NdLinear, a novel linear transformation that preserves these structures without extra overhead. By operating separately along each dimension, NdLinear captures dependencies that standard fully connected layers overlook. Extensive experiments across convolutional, recurrent, and transformer-based networks show significant improvements in representational power and parameter efficiency. Crucially, NdLinear serves as a foundational building block for large-scale foundation models by operating on any unimodal or multimodal data in its native form. This removes the need for flattening or modality-specific preprocessing. Ndlinear rethinks core architectural priorities beyond attention, enabling more expressive, context-aware models at scale. We propose NdLinear as a drop-in replacement for standard linear layers -- marking an important step toward next-generation neural architectures.

[Arxiv](https://arxiv.org/abs/2503.17353)