# # 基于大型语言模型的符号图形编程

发布时间：2025年09月05日

`强化学习` `基础理论`

> Symbolic Graphics Programming with Large Language Models

# 摘要

> 大型语言模型（LLMs）在程序合成方面表现卓越，但在生成能渲染出精确视觉内容的符号图形程序（SGPs）上，其能力尚未得到充分研究。我们聚焦符号图形编程任务，旨在根据自然语言描述生成SGP。通过让LLMs生成由SGPs渲染的图像，该任务也为探究LLMs对视觉世界的理解提供了独特视角。在众多SGPs中，本文选择研究可缩放矢量图形（SVGs）。我们首先考察LLMs生成SGPs的能力边界，并为此构建了SGP-GenBench综合基准，该基准涵盖对象保真度、场景保真度和组合性（包括属性绑定、空间关系、数量关系）。在SGP-GenBench上的实验表明，前沿专有模型的性能显著优于开源模型，且其表现与通用编码能力密切相关。为弥合这一差距，我们提出一种带可验证奖励的强化学习（RL）方法：通过格式有效性检查门确保生成可渲染的SVG，并利用强大的视觉编码器（如用于文本-图像对齐的SigLIP和用于图像-图像匹配的DINO）构建跨模态奖励，以对齐文本描述与渲染图像。将该方法应用于Qwen-2.5-7B后，SVG生成的质量和语义准确性得到显著提升，性能达到了与前沿系统相当的水平。我们进一步分析训练动态，发现强化学习带来了两方面改进：（i）将对象更精细地分解为可控制的图元；（ii）生成有助于提升场景连贯性的上下文细节。研究结果表明，符号图形编程为跨模态接地提供了一个精确且可解释的研究视角。

> Large language models (LLMs) excel at program synthesis, yet their ability to produce symbolic graphics programs (SGPs) that render into precise visual content remains underexplored. We study symbolic graphics programming, where the goal is to generate an SGP from a natural-language description. This task also serves as a lens into how LLMs understand the visual world by prompting them to generate images rendered from SGPs. Among various SGPs, our paper sticks to scalable vector graphics (SVGs). We begin by examining the extent to which LLMs can generate SGPs. To this end, we introduce SGP-GenBench, a comprehensive benchmark covering object fidelity, scene fidelity, and compositionality (attribute binding, spatial relations, numeracy). On SGP-GenBench, we discover that frontier proprietary models substantially outperform open-source models, and performance correlates well with general coding capabilities. Motivated by this gap, we aim to improve LLMs' ability to generate SGPs. We propose a reinforcement learning (RL) with verifiable rewards approach, where a format-validity gate ensures renderable SVG, and a cross-modal reward aligns text and the rendered image via strong vision encoders (e.g., SigLIP for text-image and DINO for image-image). Applied to Qwen-2.5-7B, our method substantially improves SVG generation quality and semantics, achieving performance on par with frontier systems. We further analyze training dynamics, showing that RL induces (i) finer decomposition of objects into controllable primitives and (ii) contextual details that improve scene coherence. Our results demonstrate that symbolic graphics programming offers a precise and interpretable lens on cross-modal grounding.

[Arxiv](https://arxiv.org/abs/2509.05208)