# FALCON：利用视觉寄存器解决高分辨率多模态大语言模型中的视觉冗余与碎片化问题

发布时间：2025年01月27日

`LLM应用

**理由**：这篇论文主要讨论了如何通过引入视觉寄存器技术来改进多模态大型语言模型（MLLMs）的视觉感知能力，特别是针对高分辨率视觉输入的处理。论文提出的FALCON模型通过减少冗余标记和确保视觉编码的连续性，显著提升了模型的性能。这些改进措施直接应用于多模态大型语言模型的视觉处理能力，属于LLM在实际应用中的优化和改进，因此分类为LLM应用。` `计算机视觉` `多模态学习`

> FALCON: Resolving Visual Redundancy and Fragmentation in High-resolution Multimodal Large Language Models via Visual Registers

# 摘要

> 高分辨率视觉输入的引入为多模态大型语言模型（MLLMs）赋予了更强的视觉感知能力，以应对现实任务。然而，现有高分辨率MLLMs大多采用基于裁剪的图像处理方法，导致视觉编码碎片化和冗余标记激增。为此，我们提出了FALCON模型。FALCON引入了一种创新的视觉寄存器技术，旨在：1）在视觉编码阶段消除冗余标记。我们提出了基于寄存器的表示压缩（ReCompact）机制，通过一组可学习的视觉寄存器自适应聚合关键信息并丢弃冗余，使编码器能以最少的输出标记生成紧凑的视觉表示，无需额外压缩模块。2）确保视觉编码的连续性。为解决碎片化输入导致的编码错误，我们开发了寄存器交互注意力（ReAtten）模块，通过寄存器间的交互实现跨子图像的高效信息交换，确保视觉语义的连续性。我们在多种场景的高分辨率基准上对FALCON进行了全面实验，结果显示其视觉标记减少了9倍和16倍，性能卓越。

> The incorporation of high-resolution visual input equips multimodal large language models (MLLMs) with enhanced visual perception capabilities for real-world tasks. However, most existing high-resolution MLLMs rely on a cropping-based approach to process images, which leads to fragmented visual encoding and a sharp increase in redundant tokens. To tackle these issues, we propose the FALCON model. FALCON introduces a novel visual register technique to simultaneously: 1) Eliminate redundant tokens at the stage of visual encoding. To directly address the visual redundancy present in the output of vision encoder, we propose a Register-based Representation Compacting (ReCompact) mechanism. This mechanism introduces a set of learnable visual registers designed to adaptively aggregate essential information while discarding redundancy. It enables the encoder to produce a more compact visual representation with a minimal number of output tokens, thus eliminating the need for an additional compression module. 2) Ensure continuity in visual encoding. To address the potential encoding errors caused by fragmented visual inputs, we develop a Register Interactive Attention (ReAtten) module. This module facilitates effective and efficient information exchange across sub-images by enabling interactions between visual registers. It ensures the continuity of visual semantics throughout the encoding. We conduct comprehensive experiments with FALCON on high-resolution benchmarks across a wide range of scenarios. FALCON demonstrates superior performance with a remarkable 9-fold and 16-fold reduction in visual tokens.

[Arxiv](https://arxiv.org/abs/2501.16297)