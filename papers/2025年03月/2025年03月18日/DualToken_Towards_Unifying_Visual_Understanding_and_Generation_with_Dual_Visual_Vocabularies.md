# DualToken：探索基于双视觉词汇表统一视觉理解和生成的方法

发布时间：2025年03月18日

`其他

这篇论文主要探讨了视觉tokenizer在大型语言模型中的设计与优化，属于多模态模型的技术实现，而非直接涉及LLM的应用或理论，因此归类为“其他”。` `计算机视觉`

> DualToken: Towards Unifying Visual Understanding and Generation with Dual Visual Vocabularies

# 摘要

> 视觉理解和生成在大型语言模型的自回归范式中统一表示面临挑战。用于重建的视觉tokenizer在捕捉低级感知细节方面表现出色，适合视觉生成，但在理解任务中缺乏高级语义表示。相比之下，通过对比学习训练的视觉编码器与语言高度对齐，但在生成任务中难以解码回像素空间。为了解决这一问题，我们提出了DualToken，一种在单一tokenizer中统一理解和生成表示的方法。然而，直接在单一tokenizer中整合重建和语义目标会产生冲突，影响性能。DualToken通过为高低级特征引入分离的代码本，将冲突转化为协同关系。因此，DualToken在重建和语义任务中都达到了最先进的水平，并在下游多模态语言模型的理解和生成任务中表现出色。值得注意的是，DualToken作为统一的tokenizer，超越了两种不同视觉编码器的简单组合，在统一的多模态语言模型中提供更优越的性能。

> The differing representation spaces required for visual understanding and generation pose a challenge in unifying them within the autoregressive paradigm of large language models. A vision tokenizer trained for reconstruction excels at capturing low-level perceptual details, making it well-suited for visual generation but lacking high-level semantic representations for understanding tasks. Conversely, a vision encoder trained via contrastive learning aligns well with language but struggles to decode back into the pixel space for generation tasks. To bridge this gap, we propose DualToken, a method that unifies representations for both understanding and generation within a single tokenizer. However, directly integrating reconstruction and semantic objectives in a single tokenizer creates conflicts, leading to degraded performance in both reconstruction quality and semantic performance. Instead of forcing a single codebook to handle both semantic and perceptual information, DualToken disentangles them by introducing separate codebooks for high and low-level features, effectively transforming their inherent conflict into a synergistic relationship. As a result, DualToken achieves state-of-the-art performance in both reconstruction and semantic tasks while demonstrating remarkable effectiveness in downstream MLLM understanding and generation tasks. Notably, we also show that DualToken, as a unified tokenizer, surpasses the naive combination of two distinct types vision encoders, providing superior performance within a unified MLLM.

[Arxiv](https://arxiv.org/abs/2503.14324)