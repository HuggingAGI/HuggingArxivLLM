# 面向文本到图像生成的基于对象自我改进偏好优化方法

发布时间：2025年05月27日

`LLM应用

这篇论文探讨了多模态大型语言模型在图像生成任务中的应用，提出了一种新的框架来改进生成效果，属于LLM的应用研究。` `图像生成` `计算机视觉`

> Object-centric Self-improving Preference Optimization for Text-to-Image Generation

# 摘要

> 多模态大型语言模型（MLLMs）的近期突破性进展显著提升了图像理解和生成能力。然而，尽管取得了这些进步，MLLMs在细粒度视觉理解方面仍存在显著挑战，尤其是在文本到图像生成任务中。虽然偏好优化方法已被探索用于改进图像理解任务，但其在图像生成任务中的应用仍鲜有研究。为解决这一问题，我们提出了一种基于对象的自我改进偏好优化（OSPO）框架，专为MLLMs的文本到图像生成任务设计。OSPO充分利用MLLMs的内在推理能力，无需任何外部数据集或模型。该框架强调高质量偏好对数据的重要性，这是有效进行偏好优化的关键。为此，OSPO引入了一种自我改进机制，通过基于对象的提示微调、密集化和视觉问答评分，自主构建对象级别的对比偏好对。这一过程消除了在简单生成的偏好对中常见的模糊或不协调变化，从而显著提升了偏好优化的效果。我们在三个具有代表性的组合文本到图像基准测试上验证了OSPO框架，结果显示其性能显著优于基线模型。

> Recent advancements in Multimodal Large Language Models (MLLMs) have significantly improved both image understanding and generation capabilities. Despite these improvements, MLLMs still struggle with fine-grained visual comprehension, particularly in text-to-image generation tasks. While preference optimization methods have been explored to address these limitations in image understanding tasks, their application to image generation remains largely underexplored. To address this gap, we propose an Object-centric Self-improving Preference Optimization (OSPO) framework designed for text-to-image generation by MLLMs. OSPO leverages the intrinsic reasoning abilities of MLLMs without requiring any external datasets or models. OSPO emphasizes the importance of high-quality preference pair data, which is critical for effective preference optimization. To achieve this, it introduces a self-improving mechanism that autonomously constructs object-level contrastive preference pairs through object-centric prompt perturbation, densification and VQA scoring. This process eliminates ambiguous or disproportionate variations commonly found in naively generated preference pairs, thereby enhancing the effectiveness of preference optimization. We validate OSPO on three representative compositional text-to-image benchmarks, demonstrating substantial performance gains over baseline models.

[Arxiv](https://arxiv.org/abs/2506.02015)