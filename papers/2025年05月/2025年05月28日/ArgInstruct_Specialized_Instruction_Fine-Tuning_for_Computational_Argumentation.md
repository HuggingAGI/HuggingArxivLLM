# ArgInstruct：面向计算论证的专用指令微调

发布时间：2025年05月28日

`LLM应用

摘要中提到，论文针对计算论证（CA）领域提出了一种专门的指令微调方法，使大型语言模型（LLMs）能够更有效地处理CA任务。这属于将LLM应用于特定领域的任务，因此归类为LLM应用。` `计算论证`

> ArgInstruct: Specialized Instruction Fine-Tuning for Computational Argumentation

# 摘要

> 让大型语言模型 (LLMs) 学会遵循指令，显著提升了它们应对未知任务的能力。然而，尽管这些指令遵循型 LLM 具备强大的泛化能力，但面对需要专业知识的任务时仍会遇到瓶颈。本研究针对计算论证 (CA) 领域提出了一种专门化的指令微调方法，旨在使 LLM 能够有效应对任何未知的 CA 任务，同时保持其泛化能力。通过对现有 CA 研究的深入分析，我们制定了 105 个自然语言指令，以实现这一目标。在此基础上，我们开发了一个专门针对 CA 的基准测试，用于全面评估 LLM 在解决各种 CA 任务方面的能力。通过整合 52,000 个与 CA 相关的指令，并将自我指令过程应用于训练，我们成功打造了一个专门针对 CA 的指令遵循型 LLM。实验结果表明，这种 CA 专门化的指令微调显著提升了 LLM 在已知和未知 CA 任务上的表现。同时，在 SuperNI 基准测试的一般 NLP 任务上，性能保持稳定。

> Training large language models (LLMs) to follow instructions has significantly enhanced their ability to tackle unseen tasks. However, despite their strong generalization capabilities, instruction-following LLMs encounter difficulties when dealing with tasks that require domain knowledge. This work introduces a specialized instruction fine-tuning for the domain of computational argumentation (CA). The goal is to enable an LLM to effectively tackle any unseen CA tasks while preserving its generalization capabilities. Reviewing existing CA research, we crafted natural language instructions for 105 CA tasks to this end. On this basis, we developed a CA-specific benchmark for LLMs that allows for a comprehensive evaluation of LLMs' capabilities in solving various CA tasks. We synthesized 52k CA-related instructions, adapting the self-instruct process to train a CA-specialized instruction-following LLM. Our experiments suggest that CA-specialized instruction fine-tuning significantly enhances the LLM on both seen and unseen CA tasks. At the same time, performance on the general NLP tasks of the SuperNI benchmark remains stable.

[Arxiv](https://arxiv.org/abs/2505.22076)