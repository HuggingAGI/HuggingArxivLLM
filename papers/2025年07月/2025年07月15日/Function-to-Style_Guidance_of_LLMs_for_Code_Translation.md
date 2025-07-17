# LLMs 的函数到风格指导用于代码翻译

发布时间：2025年07月15日

`LLM应用

理由：论文主要讨论了大型语言模型在代码翻译中的应用，提出了新的方法和基准测试，并通过实验验证了其效果。这属于LLM的具体应用领域，因此归类为LLM应用。` `软件开发`

> Function-to-Style Guidance of LLMs for Code Translation

# 摘要

> 大型语言模型 (LLMs) 在代码翻译领域取得了显著进展。然而，翻译代码的正确性和可读性问题仍然制约着其在实际软件开发中的广泛应用。为此，我们提出了 F2STrans，一种函数到风格引导范式，旨在逐步提升 LLMs 的代码翻译能力。我们的方法包含两个关键阶段：首先通过功能学习，利用从在线编程平台挖掘的高质量源目标代码对优化翻译正确性；其次通过风格学习，整合正向和反向风格示例提升翻译可读性。此外，我们还引入了一个全新的代码翻译基准，包含最新的源代码、丰富的测试用例以及人工标注的 ground-truth 翻译，支持全面的功能和风格评估。实验结果表明，我们的方法显著提升了代码翻译性能。特别地，在 20 种多样化的代码翻译场景中，我们的方法使 Qwen-1.5B 的表现平均超越了增强提示的 Qwen-32B 和 GPT-4。

> Large language models (LLMs) have made significant strides in code translation tasks. However, ensuring both the correctness and readability of translated code remains a challenge, limiting their effective adoption in real-world software development. In this work, we propose F2STrans, a function-to-style guiding paradigm designed to progressively improve the performance of LLMs in code translation. Our approach comprises two key stages: (1) Functional learning, which optimizes translation correctness using high-quality source-target code pairs mined from online programming platforms, and (2) Style learning, which improves translation readability by incorporating both positive and negative style examples. Additionally, we introduce a novel code translation benchmark that includes up-to-date source code, extensive test cases, and manually annotated ground-truth translations, enabling comprehensive functional and stylistic evaluations. Experiments on both our new benchmark and existing datasets demonstrate that our approach significantly improves code translation performance. Notably, our approach enables Qwen-1.5B to outperform prompt-enhanced Qwen-32B and GPT-4 on average across 20 diverse code translation scenarios.

[Arxiv](https://arxiv.org/abs/2507.11083)