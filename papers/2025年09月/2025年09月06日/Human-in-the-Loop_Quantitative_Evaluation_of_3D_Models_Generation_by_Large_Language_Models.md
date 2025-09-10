# 人在回路中：大型语言模型生成3D模型的定量评估

发布时间：2025年09月06日

`LLM应用` `工业与制造`

> Human-in-the-Loop: Quantitative Evaluation of 3D Models Generation by Large Language Models

# 摘要

> 大型语言模型（LLMs）解读多模态输入生成复杂3D形状的能力持续提升，然而评估几何与结构保真度的可靠方法却仍显滞后。本文提出了一种人机协作框架，用于对LLM生成的3D模型进行定量评估，可支持计算机辅助设计（CAD）民主化、遗留设计逆向工程及快速原型制作等场景。我们设计了一套全面的相似性与复杂性指标体系，涵盖体积精度、表面对齐度、尺寸保真度及拓扑复杂度，以此将生成模型与真实CAD参考模型进行基准比对。通过L型支架部件的案例研究，我们系统对比了LLM在四种输入模态下的表现：2D正投影视图、等轴测草图、几何结构树及基于代码的修正提示。研究发现，语义越丰富，生成保真度越高；其中，代码级提示在所有指标上均实现了完美重建。本研究的核心价值在于：所提出的定量评估方法能显著加快向真实值的收敛，尤其相较于仅依赖视觉检查与人类直觉的传统定性方法。该工作不仅深化了对AI辅助形状合成的认知，还为验证和优化适用于多场景CAD应用的生成模型提供了可扩展方案。

> Large Language Models are increasingly capable of interpreting multimodal inputs to generate complex 3D shapes, yet robust methods to evaluate geometric and structural fidelity remain underdeveloped. This paper introduces a human in the loop framework for the quantitative evaluation of LLM generated 3D models, supporting applications such as democratization of CAD design, reverse engineering of legacy designs, and rapid prototyping. We propose a comprehensive suite of similarity and complexity metrics, including volumetric accuracy, surface alignment, dimensional fidelity, and topological intricacy, to benchmark generated models against ground truth CAD references. Using an L bracket component as a case study, we systematically compare LLM performance across four input modalities: 2D orthographic views, isometric sketches, geometric structure trees, and code based correction prompts. Our findings demonstrate improved generation fidelity with increased semantic richness, with code level prompts achieving perfect reconstruction across all metrics. A key contribution of this work is demonstrating that our proposed quantitative evaluation approach enables significantly faster convergence toward the ground truth, especially compared to traditional qualitative methods based solely on visual inspection and human intuition. This work not only advances the understanding of AI assisted shape synthesis but also provides a scalable methodology to validate and refine generative models for diverse CAD applications.

[Arxiv](https://arxiv.org/abs/2509.07010)