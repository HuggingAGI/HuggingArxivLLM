# # FirePlace：基于几何优化的大型语言模型常识推理在三维物体放置中的应用

发布时间：2025年03月06日

`LLM应用

摘要讨论了如何利用多模态大语言模型（MLLMs）在3D场景生成中的应用，特别是物体放置任务。FirePlace框架结合了MLLMs的语义理解和几何推理，属于应用层面的创新。因此，归类为LLM应用。` `3D建模` `场景生成`

> FirePlace: Geometric Refinements of LLM Common Sense Reasoning for 3D Object Placement

# 摘要

> 基于3D资产的场景生成是一项复杂的挑战，需要兼顾高层次的语义理解和低层次的几何推理。虽然多模态大语言模型（MLLMs）在语义任务上表现出色，但它们在三维几何方面的有限基础限制了其在3D场景生成中的应用。本文探讨了如何在物体放置任务中最好地利用MLLMs。为此，我们引入了一个全新的框架FirePlace，该框架将现有MLLMs应用于以下方面：（1）三维几何推理以及从3D场景中提取相关几何细节，（2）构建并解决提取的低层次几何约束，（3）筛选符合常识的最终放置方案。通过将几何推理与MLLMs对现实世界的理解相结合，我们的方法能够提出同时满足几何约束和高层次语义常识考量的物体放置方案。实验表明，这些能力使我们的方法能够更有效地在复杂且几何结构复杂的场景中放置物体，超越了以往工作的质量。

> Scene generation with 3D assets presents a complex challenge, requiring both high-level semantic understanding and low-level geometric reasoning. While Multimodal Large Language Models (MLLMs) excel at semantic tasks, their application to 3D scene generation is hindered by their limited grounding on 3D geometry. In this paper, we investigate how to best work with MLLMs in an object placement task. Towards this goal, we introduce a novel framework, FirePlace, that applies existing MLLMs in (1) 3D geometric reasoning and the extraction of relevant geometric details from the 3D scene, (2) constructing and solving geometric constraints on the extracted low-level geometry, and (3) pruning for final placements that conform to common sense. By combining geometric reasoning with real-world understanding of MLLMs, our method can propose object placements that satisfy both geometric constraints as well as high-level semantic common-sense considerations. Our experiments show that these capabilities allow our method to place objects more effectively in complex scenes with intricate geometry, surpassing the quality of prior work.

[Arxiv](https://arxiv.org/abs/2503.04919)