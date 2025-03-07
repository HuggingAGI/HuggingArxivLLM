# ToFu：面向多模态、多块、多图像任务的视觉标记融合优化

发布时间：2025年03月06日

`LLM应用` `多模态` `计算机视觉`

> ToFu: Visual Tokens Reduction via Fusion for Multi-modal, Multi-patch, Multi-image Task

# 摘要

> 大规模多模态模型（LMMs）不仅能处理文本和语言，还能理解和推理多模态信息，功能强大。然而，与单模态模型相比，LMMs的发展面临更高的计算需求，尤其是在处理多图任务时，需要大量tokens来编码视觉输入。现有的减少视觉tokens的方法依赖于特定的视觉编码器架构，需要对LLM进行微调以保持性能，并且仅适用于单图场景。为了解决这些问题，我们提出了ToFu——一种视觉编码器无关且无需训练的Token融合策略，专门针对高分辨率多图任务设计。我们的方法的核心理念是：保留独特的视觉tokens，同时合并相似的tokens。通过依次检查视觉tokens并决定是与其他tokens合并还是保持独立，我们实现了这一目标。我们在LLaVA-Interleave Bench基准上验证了我们的方法，该基准涵盖了多项具有挑战性的多图任务。此外，我们还创建了一个专注于多图比较的新基准ComPairs，通过输入大量图像和视觉tokens对LMMs进行极限测试。通过对多种LMM架构的全面分析，我们证明了我们的方法在效率和性能提升方面都具有显著优势。

> Large Multimodal Models (LMMs) are powerful tools that are capable of reasoning and understanding multimodal information beyond text and language. Despite their entrenched impact, the development of LMMs is hindered by the higher computational requirements compared to their unimodal counterparts. One of the main causes of this is the large amount of tokens needed to encode the visual input, which is especially evident for multi-image multimodal tasks. Recent approaches to reduce visual tokens depend on the visual encoder architecture, require fine-tuning the LLM to maintain the performance, and only consider single-image scenarios. To address these limitations, we propose ToFu, a visual encoder-agnostic, training-free Token Fusion strategy that combines redundant visual tokens of LMMs for high-resolution, multi-image, tasks. The core intuition behind our method is straightforward yet effective: preserve distinctive tokens while combining similar ones. We achieve this by sequentially examining visual tokens and deciding whether to merge them with others or keep them as separate entities. We validate our approach on the well-established LLaVA-Interleave Bench, which covers challenging multi-image tasks. In addition, we push to the extreme our method by testing it on a newly-created benchmark, ComPairs, focused on multi-image comparisons where a larger amount of images and visual tokens are inputted to the LMMs. Our extensive analysis, considering several LMM architectures, demonstrates the benefits of our approach both in terms of efficiency and performance gain.

[Arxiv](https://arxiv.org/abs/2503.04444)