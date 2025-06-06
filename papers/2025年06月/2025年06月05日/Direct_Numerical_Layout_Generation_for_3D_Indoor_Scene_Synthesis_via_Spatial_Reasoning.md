# 基于空间推理的三维室内场景直接数值布局生成

发布时间：2025年06月05日

`其他` `知识图谱`

> Direct Numerical Layout Generation for 3D Indoor Scene Synthesis via Spatial Reasoning

# 摘要

> <翻译失败>

> Realistic 3D indoor scene synthesis is vital for embodied AI and digital content creation. It can be naturally divided into two subtasks: object generation and layout generation. While recent generative models have significantly advanced object-level quality and controllability, layout generation remains challenging due to limited datasets. Existing methods either overfit to these datasets or rely on predefined constraints to optimize numerical layout that sacrifice flexibility. As a result, they fail to generate scenes that are both open-vocabulary and aligned with fine-grained user instructions. We introduce DirectLayout, a framework that directly generates numerical 3D layouts from text descriptions using generalizable spatial reasoning of large language models (LLMs). DirectLayout decomposes the generation into three stages: producing a Bird's-Eye View (BEV) layout, lifting it into 3D space, and refining object placements. To enable explicit spatial reasoning and help the model grasp basic principles of object placement, we employ Chain-of-Thought (CoT) Activation based on the 3D-Front dataset. Additionally, we design CoT-Grounded Generative Layout Reward to enhance generalization and spatial planning. During inference, DirectLayout addresses asset-layout mismatches via Iterative Asset-Layout Alignment through in-context learning. Extensive experiments demonstrate that DirectLayout achieves impressive semantic consistency, generalization and physical plausibility.

[Arxiv](https://arxiv.org/abs/2506.05341)