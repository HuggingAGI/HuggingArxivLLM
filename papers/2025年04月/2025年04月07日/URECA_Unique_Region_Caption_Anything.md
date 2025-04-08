# URECA: 独特区域，描述一切

发布时间：2025年04月07日

`LLM应用

理由：这篇论文主要探讨了如何将多模态大型语言模型（MLLMs）应用于图像区域描述生成任务，特别是在多粒度层次上的应用。通过引入新的数据集和模型，研究集中在提升模型的描述能力和应用效果，属于大型语言模型的实际应用范畴。` `计算机视觉`

> URECA: Unique Region Caption Anything

# 摘要

> 区域级描述生成旨在为图像特定区域生成自然语言描述，突出其显著特征。然而，现有方法在多粒度层次上难以生成独特描述，限制了实际应用。为满足对区域级详细理解的需求，我们推出了URECA数据集，专为多粒度区域描述生成设计。与传统数据集主要关注显著物体不同，URECA通过纳入多样化物体、部件和背景元素，确保区域与描述间独特且一致的映射。我们的核心是分阶段数据整理流水线，每个阶段逐步优化区域选择和描述生成。借助多模态大型语言模型（MLLMs）在各阶段的支持，我们的流水线生成独特且语境化的描述，显著提升了准确性和语义多样性。基于此数据集，我们推出URECA模型，专注于有效编码多粒度区域。通过在现有MLLMs上进行简单却有力的修改，URECA保留了位置和形状等关键空间属性，实现细粒度且语义丰富的区域描述。我们的方法引入动态掩膜建模和高分辨率掩膜编码器，进一步增强描述的独特性。实验结果表明，URECA在自身数据集上达到最先进水平，并且在现有区域级描述生成基准上表现出良好泛化能力。

> Region-level captioning aims to generate natural language descriptions for specific image regions while highlighting their distinguishing features. However, existing methods struggle to produce unique captions across multi-granularity, limiting their real-world applicability. To address the need for detailed region-level understanding, we introduce URECA dataset, a large-scale dataset tailored for multi-granularity region captioning. Unlike prior datasets that focus primarily on salient objects, URECA dataset ensures a unique and consistent mapping between regions and captions by incorporating a diverse set of objects, parts, and background elements. Central to this is a stage-wise data curation pipeline, where each stage incrementally refines region selection and caption generation. By leveraging Multimodal Large Language Models (MLLMs) at each stage, our pipeline produces distinctive and contextually grounded captions with improved accuracy and semantic diversity. Building upon this dataset, we present URECA, a novel captioning model designed to effectively encode multi-granularity regions. URECA maintains essential spatial properties such as position and shape through simple yet impactful modifications to existing MLLMs, enabling fine-grained and semantically rich region descriptions. Our approach introduces dynamic mask modeling and a high-resolution mask encoder to enhance caption uniqueness. Experiments show that URECA achieves state-of-the-art performance on URECA dataset and generalizes well to existing region-level captioning benchmarks.

[Arxiv](https://arxiv.org/abs/2504.05305)