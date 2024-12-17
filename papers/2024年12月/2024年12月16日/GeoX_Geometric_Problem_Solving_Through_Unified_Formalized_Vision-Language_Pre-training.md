# GeoX：借助统一形式化的视觉语言预训练攻克几何问题

发布时间：2024年12月16日

`LLM应用` `自动问题求解`

> GeoX: Geometric Problem Solving Through Unified Formalized Vision-Language Pre-training

# 摘要

> 尽管多模态大型语言模型（MLLMs）在常规任务中表现出色，然而在自动几何问题求解（GPS）上却举步维艰，因为这需要理解图表、解读符号以及进行复杂推理。这种局限源于其在自然图像和文本上的预训练，以及在解题过程中缺乏自动验证。另外，当前的几何专家受特定任务设计所限，在应对更广泛的几何问题时效果欠佳。为此，我们推出了 GeoX，这是一个专注于几何理解与推理任务的多模态大型模型。鉴于几何图表符号和自然图像文本存在显著差异，我们引入单模态预训练来开发图表编码器和符号解码器，以增强对几何图像和语料的理解。此外，我们引入几何语言对齐这一有效预训练范式，来弥合单模态几何专家之间的模态差距。我们提出生成器与采样器变压器（GS-Former），用于生成有区分度的查询，并从分布不均的几何信号中剔除无价值的表示。最后，GeoX 得益于视觉指令调整，能够将几何图像和问题作为输入，并生成可验证的解决方案。实验表明，在诸如 GeoQA、UniGeo、Geometry3K 和 PGPS9k 等公开认可的基准测试中，GeoX 比通才和几何专家表现更优。

> Despite their proficiency in general tasks, Multi-modal Large Language Models (MLLMs) struggle with automatic Geometry Problem Solving (GPS), which demands understanding diagrams, interpreting symbols, and performing complex reasoning. This limitation arises from their pre-training on natural images and texts, along with the lack of automated verification in the problem-solving process. Besides, current geometric specialists are limited by their task-specific designs, making them less effective for broader geometric problems. To this end, we present GeoX, a multi-modal large model focusing on geometric understanding and reasoning tasks. Given the significant differences between geometric diagram-symbol and natural image-text, we introduce unimodal pre-training to develop a diagram encoder and symbol decoder, enhancing the understanding of geometric images and corpora. Furthermore, we introduce geometry-language alignment, an effective pre-training paradigm that bridges the modality gap between unimodal geometric experts. We propose a Generator-And-Sampler Transformer (GS-Former) to generate discriminative queries and eliminate uninformative representations from unevenly distributed geometric signals. Finally, GeoX benefits from visual instruction tuning, empowering it to take geometric images and questions as input and generate verifiable solutions. Experiments show that GeoX outperforms both generalists and geometric specialists on publicly recognized benchmarks, such as GeoQA, UniGeo, Geometry3K, and PGPS9k.

[Arxiv](https://arxiv.org/abs/2412.11863)