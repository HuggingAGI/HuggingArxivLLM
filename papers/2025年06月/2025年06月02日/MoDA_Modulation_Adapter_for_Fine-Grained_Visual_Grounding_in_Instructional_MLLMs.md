# MoDA：面向多语言大语言模型的细粒度视觉定位调制适配器

发布时间：2025年06月02日

`LLM应用` `视觉理解` `多模态`

> MoDA: Modulation Adapter for Fine-Grained Visual Grounding in Instructional MLLMs

# 摘要

> 近年来，多模态大型语言模型（MLLMs）通过结合预训练视觉编码器与大型语言模型（LLMs），在指令遵循任务中展现了卓越性能。然而，现有方法往往难以在复杂场景中准确捕捉细粒度视觉概念。本文提出了一种名为MoDA（调制适配器）的轻量级且有效的模块，旨在通过指令引导的调制优化预先对齐的视觉特征。我们的方法遵循标准的LLaVA训练协议，包括两个阶段：首先，通过冻结的视觉编码器和适配器层将图像特征与LLMs的输入空间对齐；其次，在指令微调阶段利用MoDA适配器优化这些特征。MoDA采用基于Transformer的交叉注意力机制，在对齐的视觉令牌上生成调制掩码，从而根据语言指令强调语义相关的嵌入维度。调制后的特征随后传递给LLM进行自回归语言生成。实验结果表明，MoDA不仅提升了视觉定位的准确性，还生成了更具语境关联性的响应，证明了其作为图像基MLLMs通用增强方案的有效性。

> Recently, Multimodal Large Language Models (MLLMs) have demonstrated impressive performance on instruction-following tasks by integrating pretrained visual encoders with large language models (LLMs). However, existing approaches often struggle to ground fine-grained visual concepts in complex scenes. In this paper, we propose MoDA (Modulation Adapter), a lightweight yet effective module designed to refine pre-aligned visual features through instruction-guided modulation. Our approach follows the standard LLaVA training protocol, consisting of a two-stage process: (1) aligning image features to the LLMs input space via a frozen vision encoder and adapter layers, and (2) refining those features using the MoDA adapter during the instructional tuning stage. MoDA employs a Transformer-based cross-attention mechanism to generate a modulation mask over the aligned visual tokens, thereby emphasizing semantically relevant embedding dimensions based on the language instruction. The modulated features are then passed to the LLM for autoregressive language generation. Our experimental evaluation shows that MoDA improves visual grounding and generates more contextually appropriate responses, demonstrating its effectiveness as a general-purpose enhancement for image-based MLLMs.

[Arxiv](https://arxiv.org/abs/2506.01850)