# MMPerspective：多模态大型语言模型是否具备视角理解能力？一项涵盖视角感知、推理及鲁棒性的全面基准测试

发布时间：2025年05月26日

`LLM应用` `计算机视觉` `多模态模型`

> MMPerspective: Do MLLMs Understand Perspective? A Comprehensive Benchmark for Perspective Perception, Reasoning, and Robustness

# 摘要

> 透视理解是人类视觉感知的核心，但多模态大型语言模型（MLLMs）对透视几何的理解程度尚不明确。我们推出MMPerspective，这是首个专为系统评估MLLMs透视理解能力而设计的基准测试。它涵盖了三个维度的10个任务：透视感知、推理和鲁棒性。基准测试包含2,711个图像实例和5,083个问题-答案对，考察了从消失点感知到三维空间线关系理解等多种能力。通过对43个先进MLLMs的评估，我们发现模型在表面感知任务上表现良好，但在组合推理和空间一致性维护方面存在明显不足。我们的分析揭示了模型架构、规模与透视能力之间的关联，指出了鲁棒性瓶颈并强调了链式思维提示的作用。MMPerspective为提升视觉-语言系统空间理解提供了重要研究工具。了解更多：https://yunlong10.github.io/MMPerspective/

> Understanding perspective is fundamental to human visual perception, yet the extent to which multimodal large language models (MLLMs) internalize perspective geometry remains unclear. We introduce MMPerspective, the first benchmark specifically designed to systematically evaluate MLLMs' understanding of perspective through 10 carefully crafted tasks across three complementary dimensions: Perspective Perception, Reasoning, and Robustness. Our benchmark comprises 2,711 real-world and synthetic image instances with 5,083 question-answer pairs that probe key capabilities, such as vanishing point perception and counting, perspective type reasoning, line relationship understanding in 3D space, invariance to perspective-preserving transformations, etc. Through a comprehensive evaluation of 43 state-of-the-art MLLMs, we uncover significant limitations: while models demonstrate competence on surface-level perceptual tasks, they struggle with compositional reasoning and maintaining spatial consistency under perturbations. Our analysis further reveals intriguing patterns between model architecture, scale, and perspective capabilities, highlighting both robustness bottlenecks and the benefits of chain-of-thought prompting. MMPerspective establishes a valuable testbed for diagnosing and advancing spatial understanding in vision-language systems. Resources available at: https://yunlong10.github.io/MMPerspective/

[Arxiv](https://arxiv.org/abs/2505.20426)