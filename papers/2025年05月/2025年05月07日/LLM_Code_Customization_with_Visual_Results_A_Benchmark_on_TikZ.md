# LLM代码定制与可视化结果：基于TikZ的基准测试

发布时间：2025年05月07日

`LLM应用` `视觉设计` `图像处理`

> LLM Code Customization with Visual Results: A Benchmark on TikZ

# 摘要

> AI代码生成的兴起使得根据自然语言指令定制代码以修改视觉结果（如图表或图像）成为可能，从而减少了对深度编程知识的需求。然而，即使是经验丰富的开发者，也可能在这个任务上遇到困难，因为它需要识别相关代码区域、生成有效的代码变体，并确保修改可靠地与用户意图保持一致。本文中，我们介绍了vTikZ，这是首个评估大型语言模型（LLMs）在保持连贯视觉效果的同时定制代码能力的基准。我们的基准包括精心策划的vTikZ编辑场景、参数化的标准答案以及一个利用视觉反馈评估正确性的审查工具。通过使用最先进的LLMs进行实证评估，我们发现现有解决方案在与视觉意图对齐的代码修改方面表现不佳，这凸显了当前AI辅助代码编辑方法的不足。我们主张，vTikZ为将LLMs与视觉反馈机制相结合提供了新的研究方向，从而在TikZ之外的多个领域（包括图像处理、艺术创作、Web设计和3D建模）提升代码定制任务的效果。

> With the rise of AI-based code generation, customizing existing code out of natural language instructions to modify visual results -such as figures or images -has become possible, promising to reduce the need for deep programming expertise. However, even experienced developers can struggle with this task, as it requires identifying relevant code regions (feature location), generating valid code variants, and ensuring the modifications reliably align with user intent. In this paper, we introduce vTikZ, the first benchmark designed to evaluate the ability of Large Language Models (LLMs) to customize code while preserving coherent visual outcomes. Our benchmark consists of carefully curated vTikZ editing scenarios, parameterized ground truths, and a reviewing tool that leverages visual feedback to assess correctness. Empirical evaluation with stateof-the-art LLMs shows that existing solutions struggle to reliably modify code in alignment with visual intent, highlighting a gap in current AI-assisted code editing approaches. We argue that vTikZ opens new research directions for integrating LLMs with visual feedback mechanisms to improve code customization tasks in various domains beyond TikZ, including image processing, art creation, Web design, and 3D modeling.

[Arxiv](https://arxiv.org/abs/2505.04670)