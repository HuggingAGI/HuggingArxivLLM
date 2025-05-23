# Circle-RoPE：一种专为大型视觉-语言模型设计的锥形解耦旋转位置编码。

发布时间：2025年05月22日

`LLM理论` `语言模型`

> Circle-RoPE: Cone-like Decoupled Rotary Positional Embedding for Large Vision-Language Models

# 摘要

> 旋转位置编码（RoPE）是大型语言模型（LLMs）中广泛使用的一种编码相对位置信息的技术。然而，当将其扩展到大型视觉语言模型（LVLMs）时，其变体引入了意外的跨模态位置偏置。具体来说，它们强制在文本令牌索引与图像令牌之间建立相对位置依赖关系，导致错误的对齐。这一问题源于图像令牌在表示相同内容但位于不同空间位置时被赋予不同的位置偏置，从而导致跨模态关联的不一致性。为了解决这一问题，我们提出了Per-Token Distance（PTD）——一种衡量跨模态位置编码独立性的简单而有效的指标。基于这一分析，我们引入了Circle-RoPE，这是一种新型编码方案，将图像令牌索引映射到与文本令牌索引线性路径正交的圆形轨迹上，形成类似锥体的结构。这种配置确保了每个文本令牌与所有图像令牌保持等距，从而在减少人工跨模态偏置的同时保留了图像内部的空间信息。为了进一步提升性能，我们提出了一种交错层策略，该策略在不同层中应用不同的RoPE变体。此设计充分利用了每种RoPE变体的互补优势，从而提升了模型的整体性能。我们的实验结果表明，我们的方法在有效保留图像空间信息的同时减少了相对位置偏置，为LVLMs提供了一个更加健壮和灵活的位置编码框架。代码可在[https://github.com/lose4578/CircleRoPE](https://github.com/lose4578/CircleRoPE)获取。

> Rotary Position Embedding (RoPE) is a widely adopted technique for encoding relative positional information in large language models (LLMs). However, when extended to large vision-language models (LVLMs), its variants introduce unintended cross-modal positional biases. Specifically, they enforce relative positional dependencies between text token indices and image tokens, causing spurious alignments. This issue arises because image tokens representing the same content but located at different spatial positions are assigned distinct positional biases, leading to inconsistent cross-modal associations. To address this, we propose Per-Token Distance (PTD) - a simple yet effective metric for quantifying the independence of positional encodings across modalities. Informed by this analysis, we introduce Circle-RoPE, a novel encoding scheme that maps image token indices onto a circular trajectory orthogonal to the linear path of text token indices, forming a cone-like structure. This configuration ensures that each text token maintains an equal distance to all image tokens, reducing artificial cross-modal biases while preserving intra-image spatial information. To further enhance performance, we propose a staggered layer strategy that applies different RoPE variants across layers. This design leverages the complementary strengths of each RoPE variant, thereby enhancing the model's overall performance. Our experimental results demonstrate that our method effectively preserves spatial information from images while reducing relative positional bias, offering a more robust and flexible positional encoding framework for LVLMs. The code is available at [https://github.com/lose4578/CircleRoPE](https://github.com/lose4578/CircleRoPE).

[Arxiv](https://arxiv.org/abs/2505.16416)