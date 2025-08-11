# Uni-cot：统一文本与视觉的链式推理探索

发布时间：2025年08月07日

`LLM应用

理由：这篇论文探讨了大型语言模型在视觉语言推理任务中的应用，提出了一种新的框架Uni-CoT，用于增强模型的多模态推理能力。这属于将LLM应用于特定任务的范畴，因此归类为LLM应用。` `视觉推理` `图像生成`

> Uni-cot: Towards Unified Chain-of-Thought Reasoning Across Text and Vision

# 摘要

> 链式思维（CoT）推理通过将复杂任务分解为简单有序的子任务，被广泛用于增强大型语言模型（LLMs）。然而，将 CoT 扩展到视觉语言推理任务仍然充满挑战，原因在于需要解释视觉状态的转换以支持推理，而现有方法往往受限于视觉状态转换建模能力不足或架构碎片化导致的视觉轨迹不连贯。

    为了解决这些问题，我们提出了 Uni-CoT，一个统一的链式思维框架，能够在单一模型中实现连贯且基于多模态的推理。其核心思想是利用一个既能理解又能生成图像的模型，对视觉内容进行推理，并对不断演变的视觉状态进行建模。然而，赋予一个统一模型实现这一点并非易事，因为这需要高昂的计算成本和繁重的训练负担。为了解决这一问题，Uni-CoT引入了创新的两级推理范式：宏观层面的 CoT 用于高层任务规划，微观层面的 CoT 用于子任务执行。这种设计显著降低了计算开销。此外，我们还引入了一种结构化的训练范式，将用于宏观层面 CoT 的交错图像-文本监督与用于微观层面 CoT 的多任务目标相结合。这些创新使 Uni-CoT 能够实现可扩展且连贯的多模态推理。此外，得益于我们的设计，所有实验仅需使用 8 块配备 80GB 显存的 A100 GPU 即可高效完成。在推理驱动的图像生成基准测试（WISE）和编辑基准测试（RISE 和 KRIS）上的实验结果表明，Uni-CoT 展现了 SOTA 性能和强大的泛化能力，确立了其作为多模态推理有前途的解决方案的地位。项目页面和代码：https://sais-fuxi.github.io/projects/uni-cot/

> Chain-of-Thought (CoT) reasoning has been widely adopted to enhance Large Language Models (LLMs) by decomposing complex tasks into simpler, sequential subtasks. However, extending CoT to vision-language reasoning tasks remains challenging, as it often requires interpreting transitions of visual states to support reasoning. Existing methods often struggle with this due to limited capacity of modeling visual state transitions or incoherent visual trajectories caused by fragmented architectures.
  To overcome these limitations, we propose Uni-CoT, a Unified Chain-of-Thought framework that enables coherent and grounded multimodal reasoning within a single unified model. The key idea is to leverage a model capable of both image understanding and generation to reason over visual content and model evolving visual states. However, empowering a unified model to achieve that is non-trivial, given the high computational cost and the burden of training. To address this, Uni-CoT introduces a novel two-level reasoning paradigm: A Macro-Level CoT for high-level task planning and A Micro-Level CoT for subtask execution. This design significantly reduces the computational overhead. Furthermore, we introduce a structured training paradigm that combines interleaved image-text supervision for macro-level CoT with multi-task objectives for micro-level CoT. Together, these innovations allow Uni-CoT to perform scalable and coherent multi-modal reasoning. Furthermore, thanks to our design, all experiments can be efficiently completed using only 8 A100 GPUs with 80GB VRAM each. Experimental results on reasoning-driven image generation benchmark (WISE) and editing benchmarks (RISE and KRIS) indicates that Uni-CoT demonstrates SOTA performance and strong generalization, establishing Uni-CoT as a promising solution for multi-modal reasoning. Project Page and Code: https://sais-fuxi.github.io/projects/uni-cot/

[Arxiv](https://arxiv.org/abs/2508.05606)