# RefineCoder：通过自适应评估优化迭代优化大型语言模型的代码生成能力

发布时间：2025年02月13日

`LLM应用` `代码生成` `软件工程`

> RefineCoder: Iterative Improving of Large Language Models via Adaptive Critique Refinement for Code Generation

# 摘要

> 代码生成随着大型语言模型（LLMs）的兴起引发了越来越多的关注。许多研究通过合成与代码相关的指令数据并应用监督微调，开发出了强大的代码 LLM。然而，这些方法受限于教师模型蒸馏，并忽视了通过自动生成的代码进行迭代改进的潜力。本文中，我们提出了自适应批判性优化（ACR），使模型能够通过自动生成的代码和外部批判进行自我改进，而非直接模仿教师模型的代码响应。具体而言，ACR 包括一个由 LLM 作为评估者的综合评分系统，用于评估代码响应的质量，以及一个由 LLM 作为批判者的有选择性批判策略，用于批判自动生成的低质量代码响应。我们通过迭代应用 ACR 开发了 RefineCoder 系列，在多个代码生成基准上实现了持续的性能提升。与相同规模的基线模型相比，我们提出的 RefineCoder 系列能够利用更少的数据实现可比甚至更优的性能。

> Code generation has attracted increasing attention with the rise of Large Language Models (LLMs). Many studies have developed powerful code LLMs by synthesizing code-related instruction data and applying supervised fine-tuning. However, these methods are limited by teacher model distillation and ignore the potential of iterative refinement by self-generated code. In this paper, we propose Adaptive Critique Refinement (ACR), which enables the model to refine itself by self-generated code and external critique, rather than directly imitating the code responses of the teacher model. Concretely, ACR includes a composite scoring system with LLM-as-a-Judge to evaluate the quality of code responses and a selective critique strategy with LLM-as-a-Critic to critique self-generated low-quality code responses. We develop the RefineCoder series by iteratively applying ACR, achieving continuous performance improvement on multiple code generation benchmarks. Compared to the baselines of the same size, our proposed RefineCoder series can achieve comparable or even superior performance using less data.

[Arxiv](https://arxiv.org/abs/2502.09183)