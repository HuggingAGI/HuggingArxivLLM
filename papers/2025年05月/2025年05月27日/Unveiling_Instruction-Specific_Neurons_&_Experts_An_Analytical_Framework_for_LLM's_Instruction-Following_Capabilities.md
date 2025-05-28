# 揭示特定指令神经元与专家：大型语言模型指令遵循能力的分析框架

发布时间：2025年05月27日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在微调过程中如何通过稀疏组件的重新配置来提升指令遵循能力。研究重点在于理解微调对模型内部计算机制的影响，特别是稀疏组件的作用，属于对LLM内在工作原理的理论分析。因此，归类为LLM理论。` `可信人工智能` `人工智能`

> Unveiling Instruction-Specific Neurons & Experts: An Analytical Framework for LLM's Instruction-Following Capabilities

# 摘要

> 尽管大型语言模型（LLMs）的微调显著提升了它们的指令遵循能力，但驱动这一改进的底层计算机制仍不为人知。本研究通过分离并分析特定于指令的稀疏组件（包括密集模型中的神经元以及专家混合（MoE）架构中的神经元和专家），系统性地探究了微调如何重新配置LLM的计算过程。我们引入了HexaInst（涵盖六个独特类别的精心策划和平衡的指令数据集），并提出了SPARCOM框架，该框架包含三个关键创新：(1) 稀疏组件的识别方法，(2) 功能通用性和独特性的评估，(3) 组件改变的系统性比较。实验结果表明，这些组件不仅具有功能通用性和独特性，还在指令执行中发挥着关键作用。通过揭示微调诱导的适应与稀疏计算基质之间的关系，本研究为可信的LLM社区提供了更深入的理解，阐明了LLMs如何内化指令遵循行为。

> The finetuning of Large Language Models (LLMs) has significantly advanced their instruction-following capabilities, yet the underlying computational mechanisms driving these improvements remain poorly understood. This study systematically examines how fine-tuning reconfigures LLM computations by isolating and analyzing instruction-specific sparse components, i.e., neurons in dense models and both neurons and experts in Mixture-of-Experts (MoE) architectures. In particular, we introduce HexaInst, a carefully curated and balanced instructional dataset spanning six distinct categories, and propose SPARCOM, a novel analytical framework comprising three key contributions: (1) a method for identifying these sparse components, (2) an evaluation of their functional generality and uniqueness, and (3) a systematic comparison of their alterations. Through experiments, we demonstrate functional generality, uniqueness, and the critical role of these components in instruction execution. By elucidating the relationship between fine-tuning-induced adaptations and sparse computational substrates, this work provides deeper insights into how LLMs internalize instruction-following behavior for the trustworthy LLM community.

[Arxiv](https://arxiv.org/abs/2505.21191)