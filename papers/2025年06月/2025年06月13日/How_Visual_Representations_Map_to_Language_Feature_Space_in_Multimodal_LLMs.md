# 多模态大语言模型中的视觉表示如何映射到语言特征空间

发布时间：2025年06月13日

`LLM理论`

> How Visual Representations Map to Language Feature Space in Multimodal LLMs

# 摘要

> 多模态推理的有效性取决于视觉与语言表示的一致性，但视觉语言模型 (VLMs) 实现这种一致性的机制尚不明确。我们提出了一种创新的方法框架：保持大型语言模型 (LLM) 和视觉变换器 (ViT) 的冻结状态，仅通过训练线性适配器进行视觉指令微调。这种设计确保语言模型保留其原始表示，避免视觉数据的干扰。线性适配器需将视觉特征直接映射至 LLM 的现有空间，而非通过微调发展视觉理解。我们的实验巧妙运用了 LLM 的预训练稀疏自动编码器 (SAEs) 作为分析工具，这些 SAE 与语言模型完美对齐，记录了语言特征的表示。通过分析 SAE 的重构误差、稀疏模式及特征描述，我们揭示了视觉表示逐步与语言特征对齐的分层过程，最终在中后层实现融合。这一发现表明 ViT 输出与 LLM 早期层存在根本性不对齐，引发深思：现有基于适配器的架构是否最优地支持跨模态学习？

> Effective multimodal reasoning depends on the alignment of visual and linguistic representations, yet the mechanisms by which vision-language models (VLMs) achieve this alignment remain poorly understood. We introduce a methodological framework that deliberately maintains a frozen large language model (LLM) and a frozen vision transformer (ViT), connected solely by training a linear adapter during visual instruction tuning. This design is fundamental to our approach: by keeping the language model frozen, we ensure it maintains its original language representations without adaptation to visual data. Consequently, the linear adapter must map visual features directly into the LLM's existing representational space rather than allowing the language model to develop specialized visual understanding through fine-tuning. Our experimental design uniquely enables the use of pre-trained sparse autoencoders (SAEs) of the LLM as analytical probes. These SAEs remain perfectly aligned with the unchanged language model and serve as a snapshot of the learned language feature-representations. Through systematic analysis of SAE reconstruction error, sparsity patterns, and feature SAE descriptions, we reveal the layer-wise progression through which visual representations gradually align with language feature representations, converging in middle-to-later layers. This suggests a fundamental misalignment between ViT outputs and early LLM layers, raising important questions about whether current adapter-based architectures optimally facilitate cross-modal representation learning.

[Arxiv](https://arxiv.org/abs/2506.11976)