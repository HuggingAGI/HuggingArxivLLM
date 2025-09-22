# MANZANO：一种简单可扩展的统一多模态模型，采用混合视觉分词器

发布时间：2025年09月19日

`LLM应用` `基础理论`

> MANZANO: A Simple and Scalable Unified Multimodal Model with a Hybrid Vision Tokenizer

# 摘要

> 能同时理解和生成视觉内容的统一多模态大型语言模型（LLMs）潜力巨大。但现有开源模型常面临这两种能力间的性能取舍难题。为此，我们提出Manzano——一个简洁高效且易于扩展的统一框架。它通过融合混合图像分词器与精心设计的训练方案，显著缓解了这一矛盾。该框架采用单个共享视觉编码器，为两个轻量级适配器提供输入；这两个适配器在同一语义空间内，分别生成图文理解所需的连续嵌入和文图生成所需的离散标记。统一自回归LLM负责以文本和图像标记的形式预测高层语义，辅助扩散解码器则将图像标记进一步转化为像素。这一架构配合针对理解与生成数据的统一训练方案，实现了两种能力的高效可扩展联合学习。实验表明，Manzano在统一模型中性能达到当前最优，且与专业模型相比也颇具竞争力，尤其在文本密集型评估任务中表现突出。研究还发现，Manzano的任务冲突极小，且模型规模扩大时性能稳步提升，充分验证了混合图像分词器的设计合理性。

> Unified multimodal Large Language Models (LLMs) that can both understand and generate visual content hold immense potential. However, existing open-source models often suffer from a performance trade-off between these capabilities. We present Manzano, a simple and scalable unified framework that substantially reduces this tension by coupling a hybrid image tokenizer with a well-curated training recipe. A single shared vision encoder feeds two lightweight adapters that produce continuous embeddings for image-to-text understanding and discrete tokens for text-to-image generation within a common semantic space. A unified autoregressive LLM predicts high-level semantics in the form of text and image tokens, with an auxiliary diffusion decoder subsequently translating the image tokens into pixels. The architecture, together with a unified training recipe over understanding and generation data, enables scalable joint learning of both capabilities. Manzano achieves state-of-the-art results among unified models, and is competitive with specialist models, particularly on text-rich evaluation. Our studies show minimal task conflicts and consistent gains from scaling model size, validating our design choice of a hybrid tokenizer.

[Arxiv](https://arxiv.org/abs/2509.16197)