# 错误驱动的高效数据大型多模态模型调优

发布时间：2024年12月20日

`LLM应用` `多模态模型` `数据调优`

> Error-driven Data-efficient Large Multimodal Model Tuning

# 摘要

> 大型多模态模型（LMMs）在众多学术基准测试中表现抢眼。然而，要在下游任务中获得满意效果，微调依旧必不可少，可特定任务的调优样本往往难以获取，要么获取成本高、耗时久。为应对此难题，我们提出了一种错误驱动的高效数据调优框架，旨在无需任何特定任务的训练样本，就能让通用 LMMs 有效适配新出现的任务。在我们的方法里，充当学生模型的通用 LMM 先在目标任务的小验证集上接受评估，接着更强大的模型充当教师模型，找出学生模型推理步骤中的错误，并分析其在完全解决目标任务时的能力差距。基于这些差距，从现有的与任务无关的数据集中进一步获取有针对性的训练样本，来调整学生模型并使其契合目标任务。我们在三种不同的训练数据规模和七个任务上开展了大量实验，结果表明我们的训练模式显著且有效地提升了 LMM 在下游任务中的性能，平均性能提高了 7.01%。

> Large Multimodal Models (LMMs) have demonstrated impressive performance across numerous academic benchmarks. However, fine-tuning still remains essential to achieve satisfactory performance on downstream tasks, while the task-specific tuning samples are usually not readily available or expensive and time-consuming to obtain. To address this, we propose an error-driven data-efficient tuning framework that aims to efficiently adapt generic LMMs to newly emerging tasks without requiring any task-specific training samples. In our approach, a generic LMM, acting as a student model, is first evaluated on a small validation set of the target task, and then a more powerful model, acting as a teacher model, identifies the erroneous steps within the student model's reasoning steps and analyzes its capability gaps from fully addressing the target task. Based on these gaps, targeted training samples are further retrieved from existing task-agnostic datasets to tune the student model and tailor it to the target task. We perform extensive experiments across three different training data scales and seven tasks, demonstrating that our training paradigm significantly and efficiently improves LMM's performance on downstream tasks, achieving an average performance boost of 7.01%.

[Arxiv](https://arxiv.org/abs/2412.15652)