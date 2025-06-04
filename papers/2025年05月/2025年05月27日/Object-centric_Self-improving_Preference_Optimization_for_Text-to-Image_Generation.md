# 面向文本到图像生成的以对象为中心的自我改进偏好优化

发布时间：2025年05月27日

`LLM应用` `内容生成` `计算机视觉`

> Object-centric Self-improving Preference Optimization for Text-to-Image Generation

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在图像理解和生成能力上取得了显著提升。然而，在文本到图像生成任务中，MLLMs仍面临细粒度视觉理解的挑战。虽然偏好优化方法已在图像理解任务中被探索用于改善这一状况，但其在图像生成领域的应用仍鲜有研究。为解决这一问题，我们提出了一种面向MLLMs文本到图像生成任务的对象中心自我改进偏好优化（OSPO）框架。OSPO无需任何外部数据集或模型，仅依赖MLLMs的内在推理能力。该框架强调高质量偏好对数据的重要性，并通过一种自我改进机制，利用基于对象中心的提示扰动、密集化和VQA评分，自主构建对象级别的对比偏好对。这一机制有效消除了传统偏好对中常见的模糊或不成比例的变化，从而显著提升了偏好优化的效果。我们在三个具有代表性的组合文本到图像基准测试中验证了OSPO框架，结果显示其性能比基线模型有显著提升。

> Recent advancements in Multimodal Large Language Models (MLLMs) have significantly improved both image understanding and generation capabilities. Despite these improvements, MLLMs still struggle with fine-grained visual comprehension, particularly in text-to-image generation tasks. While preference optimization methods have been explored to address these limitations in image understanding tasks, their application to image generation remains largely underexplored. To address this gap, we propose an Object-centric Self-improving Preference Optimization (OSPO) framework designed for text-to-image generation by MLLMs. OSPO leverages the intrinsic reasoning abilities of MLLMs without requiring any external datasets or models. OSPO emphasizes the importance of high-quality preference pair data, which is critical for effective preference optimization. To achieve this, it introduces a self-improving mechanism that autonomously constructs object-level contrastive preference pairs through object-centric prompt perturbation, densification and VQA scoring. This process eliminates ambiguous or disproportionate variations commonly found in naively generated preference pairs, thereby enhancing the effectiveness of preference optimization. We validate OSPO on three representative compositional text-to-image benchmarks, demonstrating substantial performance gains over baseline models.

[Arxiv](https://arxiv.org/abs/2506.02015)