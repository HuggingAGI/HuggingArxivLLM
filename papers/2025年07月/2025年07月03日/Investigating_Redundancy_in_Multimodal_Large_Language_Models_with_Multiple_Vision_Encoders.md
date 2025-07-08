# 探究多模态大模型中多视觉编码器的冗余机制

发布时间：2025年07月03日

`LLM理论` `计算机视觉` `人工智能`

> Investigating Redundancy in Multimodal Large Language Models with Multiple Vision Encoders

# 摘要

> 多模态大型语言模型（MLLMs）正在越来越多地采用多个视觉编码器，以捕捉从粗略语义到精细细节的多样化视觉信息。虽然这一方法旨在提升视觉理解能力，但我们发现，增加编码器带来的性能提升往往会减弱，甚至导致性能下降，这一现象我们称之为“编码器冗余”。本文系统性地研究了这一问题。通过在先进多编码器 MLLMs 上进行全面的消融实验，我们实证表明，编码器冗余现象确实存在。为了量化每个编码器的独特贡献，我们提出了一种基于原则的指标：条件利用率（CUR）。在此基础上，我们引入了信息差距（IG），以衡量模型中各编码器效用的整体差异。实验发现，某些视觉编码器对整体性能贡献甚微，甚至产生负面影响，这证实了冗余现象的普遍存在。这些发现突显了当前多编码器设计中的关键低效问题，并证明了我们提出的指标可作为开发更高效、更有效的多模态架构的宝贵诊断工具。

> Multimodal Large Language Models (MLLMs) increasingly adopt multiple vision encoders to capture diverse visual information, ranging from coarse semantics to fine grained details. While this approach is intended to enhance visual understanding capability, we observe that the performance gains from adding encoders often diminish and can even lead to performance degradation, a phenomenon we term encoder redundancy. This paper presents a systematic investigation into this issue. Through comprehensive ablation studies on state of the art multi encoder MLLMs, we empirically demonstrate that significant redundancy exists. To quantify each encoder's unique contribution, we propose a principled metric: the Conditional Utilization Rate (CUR). Building on CUR, we introduce the Information Gap (IG) to capture the overall disparity in encoder utility within a model.Our experiments reveal that certain vision encoders contribute little, or even negatively, to overall performance, confirming substantial redundancy. Our experiments reveal that certain vision encoders contribute minimally, or even negatively, to the model's performance, confirming the prevalence of redundancy. These findings highlight critical inefficiencies in current multi encoder designs and establish that our proposed metrics can serve as valuable diagnostic tools for developing more efficient and effective multimodal architectures.

[Arxiv](https://arxiv.org/abs/2507.03262)