# Eval3D: 三维生成的可解释且细致入微的评估

发布时间：2025年04月25日

`其他

理由：这篇论文主要讨论的是3D生成模型的评估工具Eval3D，它专注于如何更全面、更精确地评估生成3D资产的质量，而不是直接涉及大型语言模型的应用或理论，因此归类为“其他”。` `3D生成` `计算机图形学`

> Eval3D: Interpretable and Fine-grained Evaluation for 3D Generation

# 摘要

> 尽管3D生成领域取得了突破性进展，现有的系统仍难以生成高质量的3D资产，这些资产需在多个视角下兼具视觉吸引力、几何和语义一致性。为了有效评估生成的3D数据质量，亟需一个可靠的3D评估工具。然而，现有3D评估指标要么忽视几何质量，要么仅依赖黑盒多模态大型语言模型进行粗略评估。本文中，我们推出Eval3D——一款细致、可解释的评估工具，能基于多样且互补的标准，精准评估生成3D资产的质量。我们发现，3D生成的关键特性如语义和几何一致性，可通过测量基础模型和工具间的一致性有效捕捉。因此，我们采用多样化的模型和工具作为探针，评估生成3D资产在不同维度的不一致性。与现有工作相比，Eval3D不仅提供像素级测量，还能实现精准3D空间反馈，并更贴近人类判断。通过Eval3D，我们全面评估了现有3D生成模型，揭示了当前模型的局限与挑战。

> Despite the unprecedented progress in the field of 3D generation, current systems still often fail to produce high-quality 3D assets that are visually appealing and geometrically and semantically consistent across multiple viewpoints. To effectively assess the quality of the generated 3D data, there is a need for a reliable 3D evaluation tool. Unfortunately, existing 3D evaluation metrics often overlook the geometric quality of generated assets or merely rely on black-box multimodal large language models for coarse assessment. In this paper, we introduce Eval3D, a fine-grained, interpretable evaluation tool that can faithfully evaluate the quality of generated 3D assets based on various distinct yet complementary criteria. Our key observation is that many desired properties of 3D generation, such as semantic and geometric consistency, can be effectively captured by measuring the consistency among various foundation models and tools. We thus leverage a diverse set of models and tools as probes to evaluate the inconsistency of generated 3D assets across different aspects. Compared to prior work, Eval3D provides pixel-wise measurement, enables accurate 3D spatial feedback, and aligns more closely with human judgments. We comprehensively evaluate existing 3D generation models using Eval3D and highlight the limitations and challenges of current models.

[Arxiv](https://arxiv.org/abs/2504.18509)