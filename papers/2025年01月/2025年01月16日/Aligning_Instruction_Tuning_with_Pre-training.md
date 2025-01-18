# 指令微调与预训练的对齐

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要讨论了指令微调与预训练之间的对齐问题，提出了一种新的方法（AITP）来提升LLM的泛化能力。这涉及到LLM的训练和优化策略，属于对LLM理论的研究和改进，因此应归类为LLM理论。` `人工智能`

> Aligning Instruction Tuning with Pre-training

# 摘要

> 指令微调提升了LLMs在多样化任务中遵循人类指令的能力，但其依赖的高质量数据集往往范围狭窄，与预训练时的广泛分布不匹配，限制了LLM的泛化能力。为此，我们提出了*对齐指令微调与预训练*（AITP），通过识别指令微调数据集的覆盖不足，并将未充分代表的预训练数据重写为高质量的指令-响应对，从而弥合这一差距。AITP在保持任务目标的同时，显著提升了数据集的多样性。在三个完全开放的LLM上对八个基准的评估显示，AITP带来了持续的性能提升。消融实验进一步验证了自适应数据选择、受控重写和平衡整合的重要性，强调了指令微调与预训练分布对齐对释放LLM潜力的关键作用。

> Instruction tuning enhances large language models (LLMs) to follow human instructions across diverse tasks, relying on high-quality datasets to guide behavior. However, these datasets, whether manually curated or synthetically generated, are often narrowly focused and misaligned with the broad distributions captured during pre-training, limiting LLM generalization and effective use of pre-trained knowledge. We propose *Aligning Instruction Tuning with Pre-training* (AITP), a method that bridges this gap by identifying coverage shortfalls in instruction-tuning datasets and rewriting underrepresented pre-training data into high-quality instruction-response pairs. This approach enriches dataset diversity while preserving task-specific objectives. Evaluations on three fully open LLMs across eight benchmarks demonstrate consistent performance improvements with AITP. Ablations highlight the benefits of adaptive data selection, controlled rewriting, and balanced integration, emphasizing the importance of aligning instruction tuning with pre-training distributions to unlock the full potential of LLMs.

[Arxiv](https://arxiv.org/abs/2501.09368)