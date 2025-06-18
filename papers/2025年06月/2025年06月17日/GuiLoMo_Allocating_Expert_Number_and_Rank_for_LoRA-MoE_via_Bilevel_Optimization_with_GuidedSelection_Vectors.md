# GuiLoMo：为LoRA-MoE智能分配专家数量与排名的双层优化策略

发布时间：2025年06月17日

`LLM理论` `机器学习`

> GuiLoMo: Allocating Expert Number and Rank for LoRA-MoE via Bilevel Optimization with GuidedSelection Vectors

# 摘要

> 参数高效的微调方法（PEFT）中的低秩适配（LoRA）以低成本实现了大型语言模型的高效适配。然而，受限于可训练参数数量，其性能仍有提升空间。近期研究提出的LoRA-MoE通过结合LoRA与专家混合模型（MoE）提升了模型容量，但仍存在两大限制：1）下游任务对专家数量分配的影响未被充分考虑，以及2）统一的秩分配限制了表达多样性。针对这些问题，我们提出GuiLoMo，这是一种基于引导选择向量（GSVs）的细粒度分层专家数量和秩分配策略。通过双层优化过程学习得到的GSVs能够捕捉模型和任务的特定需求，从而实现最优的专家数量和秩分配。在三个主干模型和多个基准测试中的实验表明，GuiLoMo始终优于或与所有基线方法相当。进一步分析揭示了专家数量和秩在各层和任务中的动态变化规律，凸显了自适应专家配置的优势。我们的代码可在https://github.com/Liar406/Gui-LoMo.git获取。


> Parameter-efficient fine-tuning (PEFT) methods, particularly Low-Rank Adaptation (LoRA), offer an efficient way to adapt large language models with reduced computational costs. However, their performance is limited by the small number of trainable parameters. Recent work combines LoRA with the Mixture-of-Experts (MoE), i.e., LoRA-MoE, to enhance capacity, but two limitations remain in hindering the full exploitation of its potential: 1) the influence of downstream tasks when assigning expert numbers, and 2) the uniform rank assignment across all LoRA experts, which restricts representational diversity. To mitigate these gaps, we propose GuiLoMo, a fine-grained layer-wise expert numbers and ranks allocation strategy with GuidedSelection Vectors (GSVs). GSVs are learned via a prior bilevel optimization process to capture both model- and task-specific needs, and are then used to allocate optimal expert numbers and ranks. Experiments on three backbone models across diverse benchmarks show that GuiLoMo consistently achieves superior or comparable performance to all baselines. Further analysis offers key insights into how expert numbers and ranks vary across layers and tasks, highlighting the benefits of adaptive expert configuration. Our code is available at https://github.com/Liar406/Gui-LoMo.git.

[Arxiv](https://arxiv.org/abs/2506.14646)