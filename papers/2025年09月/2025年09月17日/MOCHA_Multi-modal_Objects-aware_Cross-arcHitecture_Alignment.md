# MOCHA：多模态对象感知跨架构对齐

发布时间：2025年09月17日

`其他` `工业与制造`

> MOCHA: Multi-modal Objects-aware Cross-arcHitecture Alignment

# 摘要

> 我们提出MOCHA（多模态目标感知跨架构对齐）——一种知识蒸馏方法，能够将区域级多模态语义从大型视觉语言教师模型（如LLaVa）迁移至轻量级纯视觉目标检测器学生模型（如YOLO）。翻译模块将学生特征映射到联合空间，学生与翻译器的训练则由双目标损失引导，该损失同时确保局部对齐与全局关系一致性。与先前专注于密集或全局对齐的方法不同，MOCHA在目标级别运行，可高效迁移语义，且无需修改教师模型，推理时也无需文本输入。我们在少样本场景下，基于四个个性化检测基准验证了该方法。结果表明，该方法相比基线持续提升，平均分数提高了10.1分。尽管架构紧凑，MOCHA的性能仍可与更大的多模态模型媲美，证明其适用于实际部署。

> We introduce MOCHA (Multi-modal Objects-aware Cross-arcHitecture Alignment), a knowledge distillation approach that transfers region-level multimodal semantics from a large vision-language teacher (e.g., LLaVa) into a lightweight vision-only object detector student (e.g., YOLO). A translation module maps student features into a joint space, where the training of the student and translator is guided by a dual-objective loss that enforces both local alignment and global relational consistency. Unlike prior approaches focused on dense or global alignment, MOCHA operates at the object level, enabling efficient transfer of semantics without modifying the teacher or requiring textual input at inference. We validate our method across four personalized detection benchmarks under few-shot regimes. Results show consistent gains over baselines, with a +10.1 average score improvement. Despite its compact architecture, MOCHA reaches performance on par with larger multimodal models, proving its suitability for real-world deployment.

[Arxiv](https://arxiv.org/abs/2509.14001)