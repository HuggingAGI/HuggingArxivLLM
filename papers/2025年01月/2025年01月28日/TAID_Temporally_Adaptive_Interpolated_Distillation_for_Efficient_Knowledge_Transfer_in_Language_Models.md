# TAID: 时间自适应插值蒸馏，助力语言模型高效知识迁移

发布时间：2025年01月28日

`LLM理论

理由：这篇论文主要讨论了因果语言模型的压缩技术，特别是通过知识蒸馏的方法来减少模型规模，同时保持性能。论文提出了一个新的蒸馏方法（TAID），并通过理论分析和实验验证了其有效性。这些内容涉及到大型语言模型（LLM）的理论基础和改进方法，因此应归类为“LLM理论”。` `人工智能` `模型压缩`

> TAID: Temporally Adaptive Interpolated Distillation for Efficient Knowledge Transfer in Language Models

# 摘要

> 因果语言模型虽然能力出众，但其庞大的规模在资源有限的环境中部署时面临巨大挑战。知识蒸馏作为一种广泛应用的模型压缩技术，能够将大型教师模型的知识迁移到小型学生模型中。然而，教师模型与学生模型之间的显著差异，如容量差距、模式平均和模式崩溃，成为蒸馏过程中的主要障碍。为此，我们提出了$	extit{时间自适应插值蒸馏（TAID）}$，这是一种创新的蒸馏方法，通过自适应中间分布动态调整学生和教师的分布，逐步从学生的初始分布过渡到教师的分布。我们通过理论分析证明TAID能够有效防止模式崩溃，并通过实验验证其在解决容量差距的同时平衡模式平均和模式崩溃的能力。广泛的实验表明，TAID在指令微调和预训练场景中，无论模型大小或架构如何，均表现出色。此外，我们还开发了两个顶尖的紧凑基础模型：用于语言任务的$	exttt{TAID-LLM-1.5B}$和用于视觉语言任务的$	exttt{TAID-VLM-2B}$，进一步展示了TAID的实际应用价值。这些成果表明，TAID在构建高性能、高效模型方面具有显著优势，推动了AI技术的普及化发展。

> Causal language models have demonstrated remarkable capabilities, but their size poses significant challenges for deployment in resource-constrained environments. Knowledge distillation, a widely-used technique for transferring knowledge from a large teacher model to a small student model, presents a promising approach for model compression. A significant remaining issue lies in the major differences between teacher and student models, namely the substantial capacity gap, mode averaging, and mode collapse, which pose barriers during distillation. To address these issues, we introduce $\textit{Temporally Adaptive Interpolated Distillation (TAID)}$, a novel knowledge distillation approach that dynamically interpolates student and teacher distributions through an adaptive intermediate distribution, gradually shifting from the student's initial distribution towards the teacher's distribution. We provide a theoretical analysis demonstrating TAID's ability to prevent mode collapse and empirically show its effectiveness in addressing the capacity gap while balancing mode averaging and mode collapse. Our comprehensive experiments demonstrate TAID's superior performance across various model sizes and architectures in both instruction tuning and pre-training scenarios. Furthermore, we showcase TAID's practical impact by developing two state-of-the-art compact foundation models: $\texttt{TAID-LLM-1.5B}$ for language tasks and $\texttt{TAID-VLM-2B}$ for vision-language tasks. These results demonstrate TAID's effectiveness in creating high-performing and efficient models, advancing the development of more accessible AI technologies.

[Arxiv](https://arxiv.org/abs/2501.16937)