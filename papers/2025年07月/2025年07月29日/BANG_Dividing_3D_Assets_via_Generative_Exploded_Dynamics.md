# BANG：基于生成爆炸动力学的三维资产分割方法

发布时间：2025年07月29日

`其他

理由：这篇论文主要探讨了3D生成和分解方法，虽然使用了生成模型，但并未直接涉及LLM的应用或理论，而是属于计算机图形学和生成模型的应用，因此归类为其他。` `3D设计` `3D打印`

> BANG: Dividing 3D Assets via Generative Exploded Dynamics

# 摘要

> 3D创作一直是人类的独特优势，源于我们通过双眼、大脑和双手对物体进行解构与重组的能力。然而，当前的3D设计工具难以复制这一自然过程，需要大量艺术专业知识和手工劳动。本文介绍了一种全新的生成方法——BANG，它连接3D生成与推理，实现了对3D物体的直观灵活的部件级分解。

BANG的核心是“生成式爆炸动力学”，它为输入的几何体创建一系列平滑的爆炸状态，逐步分离部件同时保持其几何和语义连贯性。BANG采用预训练的大规模潜在扩散模型，并通过轻量级爆炸视图适配器针对爆炸动力学进行微调，实现对分解过程的精准控制。它还引入时间注意力模块，确保时间上的平滑过渡和一致性。

通过空间提示（如边界框和表面区域），BANG增强了控制能力，让用户能够指定要分解的部件及其方式。这种交互可以扩展到多模态模型（如GPT-4），支持从2D到3D的操作，带来更直观和富有创造力的工作流程。BANG的能力涵盖生成详细部件级几何、关联部件与功能描述，以及支持组件感知的3D创作和制造流程。

此外，BANG在3D打印领域也有应用，可生成可分离部件，便于打印和重新组装。简而言之，BANG实现了从创意概念到详细3D资产的无缝转变，提供了一种与人类直觉相契合的全新创作视角。

> 3D creation has always been a unique human strength, driven by our ability to deconstruct and reassemble objects using our eyes, mind and hand. However, current 3D design tools struggle to replicate this natural process, requiring considerable artistic expertise and manual labor. This paper introduces BANG, a novel generative approach that bridges 3D generation and reasoning, allowing for intuitive and flexible part-level decomposition of 3D objects. At the heart of BANG is "Generative Exploded Dynamics", which creates a smooth sequence of exploded states for an input geometry, progressively separating parts while preserving their geometric and semantic coherence.
  BANG utilizes a pre-trained large-scale latent diffusion model, fine-tuned for exploded dynamics with a lightweight exploded view adapter, allowing precise control over the decomposition process. It also incorporates a temporal attention module to ensure smooth transitions and consistency across time. BANG enhances control with spatial prompts, such as bounding boxes and surface regions, enabling users to specify which parts to decompose and how. This interaction can be extended with multimodal models like GPT-4, enabling 2D-to-3D manipulations for more intuitive and creative workflows.
  The capabilities of BANG extend to generating detailed part-level geometry, associating parts with functional descriptions, and facilitating component-aware 3D creation and manufacturing workflows. Additionally, BANG offers applications in 3D printing, where separable parts are generated for easy printing and reassembly. In essence, BANG enables seamless transformation from imaginative concepts to detailed 3D assets, offering a new perspective on creation that resonates with human intuition.

[Arxiv](https://arxiv.org/abs/2507.21493)