# HiDe-LLaVA：通过层次解耦实现多模态大语言模型的持续指令优化

发布时间：2025年03月17日

`LLM应用`

> HiDe-LLaVA: Hierarchical Decoupling for Continual Instruction Tuning of Multimodal Large Language Model

# 摘要

> 指令调优是一种通过在精选的任务特定数据集上训练来改进多模态大语言模型 (MLLM) 的方法，能够显著提升模型对人类指令的理解能力。然而，在现实场景中，同时收集所有可能的指令数据集是不现实的。因此，为 MLLM 实现持续指令调优对于保持其适应性至关重要。然而，现有方法通常以牺牲内存效率为代价来换取性能提升，这极大地影响了整体效率。本文中，我们提出了一种基于不同模型层在多样化数据集上训练时中心核对齐 (CKA) 相似性变化的任务特定扩展与任务通用融合框架。此外，我们分析了现有基准中存在的信息泄露问题，并提出了一种更具挑战性的新基准，以合理评估不同方法的性能。通过全面的实验，我们展示了与现有最先进方法相比，我们的方法在性能上有显著提升。我们的代码将公开可用。

> Instruction tuning is widely used to improve a pre-trained Multimodal Large Language Model (MLLM) by training it on curated task-specific datasets, enabling better comprehension of human instructions. However, it is infeasible to collect all possible instruction datasets simultaneously in real-world scenarios. Thus, enabling MLLM with continual instruction tuning is essential for maintaining their adaptability. However, existing methods often trade off memory efficiency for performance gains, significantly compromising overall efficiency. In this paper, we propose a task-specific expansion and task-general fusion framework based on the variations in Centered Kernel Alignment (CKA) similarity across different model layers when trained on diverse datasets. Furthermore, we analyze the information leakage present in the existing benchmark and propose a new and more challenging benchmark to rationally evaluate the performance of different methods. Comprehensive experiments showcase a significant performance improvement of our method compared to existing state-of-the-art methods. Our code will be public available.

[Arxiv](https://arxiv.org/abs/2503.12941)