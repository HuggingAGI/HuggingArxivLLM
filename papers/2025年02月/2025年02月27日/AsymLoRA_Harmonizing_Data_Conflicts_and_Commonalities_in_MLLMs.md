# # AsymLoRA：调和多语言大模型中的数据冲突与共性

发布时间：2025年02月27日

`LLM应用` `人工智能`

> AsymLoRA: Harmonizing Data Conflicts and Commonalities in MLLMs

# 摘要

> 在多样化的图像-文本数据集上进行有效的指令微调，对于开发多功能的多模态大语言模型（MLLM）至关重要。数据集的构成直接影响模型在多模态任务中的适应能力。然而，复杂的多模态数据集通常包含源于模态特定优化目标的内在冲突，以及能够实现跨任务迁移的潜在共性。现有方法大多分别处理这些冲突和共性。为了解决这一问题，我们提出了AsymLoRA，一个参数高效的调优框架。通过非对称LoRA，AsymLoRA统一了知识模块化和跨模态协调：任务特定的低秩投影（矩阵B）保留了冲突目标的独特适应路径，而共享投影（矩阵A）则整合了跨模态共性。大量评估表明，AsymLoRA在多样化的基准测试中始终超越了仅捕捉共性的普通LoRA，以及仅关注冲突的LoRA-MoE，实现了更优的模型性能和系统效率。代码链接：\href{代码}{https://github.com/Clin0212/HydraLoRA/blob/main/MLLM-HydraLoRA/README.md}。

> Effective instruction fine-tuning on diverse image-text datasets is crucial for developing a versatile Multimodal Large Language Model (MLLM), where dataset composition dictates the model's adaptability across multimodal tasks. However, complex datasets often contain inherent conflicts -- stemming from modality-specific optimization objectives -- and latent commonalities that enable cross-task transfer, which most existing approaches handle separately. To bridge this gap, we introduce AsymLoRA, a parameter-efficient tuning framework that unifies knowledge modularization and cross-modal coordination via asymmetric LoRA: task-specific low-rank projections (matrix B) that preserve distinct adaptation pathways for conflicting objectives, and a shared projection (matrix A) that consolidates cross-modal commonalities. Extensive evaluations demonstrate that AsymLoRA consistently surpasses both vanilla LoRA, which captures only commonalities, and LoRA-MoE, which focuses solely on conflicts, achieving superior model performance and system efficiency across diverse benchmarks.\href{Code}{https://github.com/Clin0212/HydraLoRA/blob/main/MLLM-HydraLoRA/README.md}.

[Arxiv](https://arxiv.org/abs/2502.20035)