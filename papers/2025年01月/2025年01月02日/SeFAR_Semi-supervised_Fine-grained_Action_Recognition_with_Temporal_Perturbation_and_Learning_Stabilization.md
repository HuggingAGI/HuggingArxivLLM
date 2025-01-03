# SeFAR: 时间扰动与学习稳定相结合的半监督细粒度动作识别

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要讨论了如何利用半监督学习（SSL）框架SeFAR来改进细粒度动作识别（FAR），特别是在多模态系统中使用LLMs（大型语言模型）来理解和处理细粒度动作标签。虽然论文的核心是动作识别，但其方法和框架的设计是为了增强LLMs在细粒度动作识别中的应用能力，因此可以归类为LLM应用。` `行为理解` `动作识别`

> SeFAR: Semi-supervised Fine-grained Action Recognition with Temporal Perturbation and Learning Stabilization

# 摘要

> # 摘要
人类行为理解对多模态系统的进步至关重要。尽管近期由强大LLMs驱动的发展旨在覆盖广泛类别，但它们往往忽视了更具体能力的需求。本文聚焦于更具挑战性的细粒度动作识别（FAR），该任务专注于短时间内的详细语义标签（如“向后翻腾一周半”）。鉴于细粒度标签注释的高成本和微调LLMs所需的大量数据，我们提出采用半监督学习（SSL）。我们的框架SeFAR包含多项创新设计以应对这些挑战。具体而言，为捕捉足够的视觉细节，我们构建了双级时间元素作为更有效的表示，并基于此设计了一种新的强增强策略，通过引入适度时间扰动实现教师-学生学习范式。此外，为应对教师模型在FAR预测中的高不确定性，我们提出了自适应调节以稳定学习过程。实验表明，SeFAR在两个FAR数据集FineGym和FineDiving上实现了最先进的性能，并在各种数据范围内表现出色。它还在两个经典粗粒度数据集UCF101和HMDB51上优于其他半监督方法。进一步分析和消融研究验证了我们设计的有效性。此外，我们展示了SeFAR提取的特征可显著提升多模态基础模型理解细粒度和领域特定语义的能力。

> Human action understanding is crucial for the advancement of multimodal systems. While recent developments, driven by powerful large language models (LLMs), aim to be general enough to cover a wide range of categories, they often overlook the need for more specific capabilities. In this work, we address the more challenging task of Fine-grained Action Recognition (FAR), which focuses on detailed semantic labels within shorter temporal duration (e.g., "salto backward tucked with 1 turn"). Given the high costs of annotating fine-grained labels and the substantial data needed for fine-tuning LLMs, we propose to adopt semi-supervised learning (SSL). Our framework, SeFAR, incorporates several innovative designs to tackle these challenges. Specifically, to capture sufficient visual details, we construct Dual-level temporal elements as more effective representations, based on which we design a new strong augmentation strategy for the Teacher-Student learning paradigm through involving moderate temporal perturbation. Furthermore, to handle the high uncertainty within the teacher model's predictions for FAR, we propose the Adaptive Regulation to stabilize the learning process. Experiments show that SeFAR achieves state-of-the-art performance on two FAR datasets, FineGym and FineDiving, across various data scopes. It also outperforms other semi-supervised methods on two classical coarse-grained datasets, UCF101 and HMDB51. Further analysis and ablation studies validate the effectiveness of our designs. Additionally, we show that the features extracted by our SeFAR could largely promote the ability of multimodal foundation models to understand fine-grained and domain-specific semantics.

[Arxiv](https://arxiv.org/abs/2501.01245)