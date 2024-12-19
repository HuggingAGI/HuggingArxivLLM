# Vivar：一个用于直观展示多模态传感器数据的生成式增强现实系统

发布时间：2024年12月18日

`其他` `传感器` `增强现实`

> Vivar: A Generative AR System for Intuitive Multi-Modal Sensor Data Presentation

# 摘要

> 对于非专家而言，理解传感器数据颇具难度，原因在于传感器模式的复杂性及其独特的语义。这就需要直观有效的方法来展示传感器信息。然而，创建直观的传感器数据可视化面临三大关键挑战：传感器读数的多变性、领域理解的缺口以及传感器数据的动态特性。为应对这些问题，我们研发了 Vivar 这一新颖的增强现实（AR）系统，它整合了多模态传感器数据，并展示 3D 体积内容用于可视化。具体而言，我们引入了一种跨模态嵌入方法，通过重心插值将传感器数据映射到预先训练的视觉嵌入空间，从而实现多模态传感器信息的精准且连续整合。Vivar 还结合了运用基础模型和 3D 高斯喷溅（3DGS）的传感器感知 AR 场景生成，无需领域专业知识。此外，Vivar 借助潜在的重用和缓存策略来加快 2D 和 AR 内容的生成。我们大量的实验表明，我们的系统在不影响质量的情况下，实现了 11 倍的延迟降低。一项涵盖超过 485 名参与者（包括领域专家）的用户研究显示，Vivar 在准确性、一致性和现实世界适用性方面成效显著，为更直观的传感器数据可视化开辟了道路。

> Understanding sensor data can be challenging for non-experts because of the complexity and unique semantic meanings of sensor modalities. This calls for intuitive and effective methods to present sensor information. However, creating intuitive sensor data visualizations presents three key challenges: the variability of sensor readings, gaps in domain comprehension, and the dynamic nature of sensor data. To address these issues, we develop Vivar, a novel AR system that integrates multi-modal sensor data and presents 3D volumetric content for visualization. In particular, we introduce a cross-modal embedding approach that maps sensor data into a pre-trained visual embedding space through barycentric interpolation. This allows for accurate and continuous integration of multi-modal sensor information. Vivar also incorporates sensor-aware AR scene generation using foundation models and 3D Gaussian Splatting (3DGS) without requiring domain expertise. In addition, Vivar leverages latent reuse and caching strategies to accelerate 2D and AR content generation. Our extensive experiments demonstrate that our system achieves 11$\times$ latency reduction without compromising quality. A user study involving over 485 participants, including domain experts, demonstrates Vivar's effectiveness in accuracy, consistency, and real-world applicability, paving the way for more intuitive sensor data visualization.

[Arxiv](https://arxiv.org/abs/2412.13509)