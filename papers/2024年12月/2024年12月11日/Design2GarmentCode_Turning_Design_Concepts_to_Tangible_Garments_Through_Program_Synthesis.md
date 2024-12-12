# Design2GarmentCode：借由程序合成把设计概念变为有形的服装

发布时间：2024年12月11日

`其他`

> Design2GarmentCode: Turning Design Concepts to Tangible Garments Through Program Synthesis

# 摘要

> 缝纫图案，乃是布料裁剪与裁缝的关键蓝图，在设计理念和可制服装之间架起了重要桥梁。然而，现有的单模态缝纫图案生成模型难以有效编码具有多模态特性的复杂设计概念，也难以将其与具备精确几何结构和复杂缝纫关系的矢量化缝纫图案建立关联。在本研究中，我们基于大型多模态模型（LMMs）提出了一种新颖的缝纫图案生成方法——Design2GarmentCode，旨在从多模态设计概念生成参数化制衣程序。LMM 为解读各类设计输入提供了直观界面，而制衣程序可作为缝纫图案结构良好且语义丰富的呈现形式，成为连接 LMM 中跨领域制衣知识与矢量化缝纫图案的有力桥梁。实验结果显示，我们的方法能够灵活应对各种复杂的设计表述，如图片、文字描述、设计师草图或它们的组合，并将其转化为尺寸精准、针脚无误的缝纫图案。相较于以往方法，我们的方法大幅提升了训练效率、生成质量和创作灵活性。我们的代码和数据将会公开。

> Sewing patterns, the essential blueprints for fabric cutting and tailoring, act as a crucial bridge between design concepts and producible garments. However, existing uni-modal sewing pattern generation models struggle to effectively encode complex design concepts with a multi-modal nature and correlate them with vectorized sewing patterns that possess precise geometric structures and intricate sewing relations. In this work, we propose a novel sewing pattern generation approach Design2GarmentCode based on Large Multimodal Models (LMMs), to generate parametric pattern-making programs from multi-modal design concepts. LMM offers an intuitive interface for interpreting diverse design inputs, while pattern-making programs could serve as well-structured and semantically meaningful representations of sewing patterns, and act as a robust bridge connecting the cross-domain pattern-making knowledge embedded in LMMs with vectorized sewing patterns. Experimental results demonstrate that our method can flexibly handle various complex design expressions such as images, textual descriptions, designer sketches, or their combinations, and convert them into size-precise sewing patterns with correct stitches. Compared to previous methods, our approach significantly enhances training efficiency, generation quality, and authoring flexibility. Our code and data will be publicly available.

[Arxiv](https://arxiv.org/abs/2412.08603)