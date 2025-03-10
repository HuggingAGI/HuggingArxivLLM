# TinyR1-32B-Preview：分支合并蒸馏提升模型精度

发布时间：2025年03月06日

`LLM应用` `人工智能` `机器学习`

> TinyR1-32B-Preview: Boosting Accuracy with Branch-Merge Distillation

# 摘要

> 如何在保持性能的同时减少大型语言模型（LLMs）的规模已成为研究热点。现有方法如模型蒸馏和迁移学习往往难以实现高精度。为解决这一问题，我们提出了一种创新的Branch-Merge蒸馏方法，通过两阶段提升模型压缩效果：首先在Branch阶段，通过领域特定的监督微调（SFT），有选择性地将大型教师模型的知识蒸馏到专门的学生模型中；然后在Merge阶段，将这些学生模型合并，实现跨领域知识转移并提升模型的泛化能力。我们采用DeepSeek-R1作为教师模型，DeepSeek-R1-Distill-Qwen-32B作为学生模型进行验证。实验结果显示，最终合并得到的模型TinyR1-32B-Preview在数学（+5.5分）、编码（+4.4分）和科学（+2.9分）等多个基准测试中均优于其对应模型DeepSeek-R1-Distill-Qwen-32B，同时在AIME 2024上几乎与DeepSeek-R1达到同等性能。Branch-Merge蒸馏方法为创建更小、高性能的LLMs提供了一种可扩展的解决方案，同时显著降低了计算成本和训练时间。

> The challenge of reducing the size of Large Language Models (LLMs) while maintaining their performance has gained significant attention. However, existing methods, such as model distillation and transfer learning, often fail to achieve high accuracy. To address this limitation, we introduce the Branch-Merge distillation approach, which enhances model compression through two phases: (1) the Branch Phase, where knowledge from a large teacher model is \textit{selectively distilled} into specialized student models via domain-specific supervised fine-tuning (SFT); And (2) the Merge Phase, where these student models are merged to enable cross-domain knowledge transfer and improve generalization. We validate our distillation approach using DeepSeek-R1 as the teacher and DeepSeek-R1-Distill-Qwen-32B as the student. The resulting merged model, TinyR1-32B-Preview, outperforms its counterpart DeepSeek-R1-Distill-Qwen-32B across multiple benchmarks, including Mathematics (+5.5 points), Coding (+4.4 points) and Science (+2.9 points), while achieving near-equal performance to DeepSeek-R1 on AIME 2024. The Branch-Merge distillation approach provides a scalable solution for creating smaller, high-performing LLMs with reduced computational cost and time.

[Arxiv](https://arxiv.org/abs/2503.04872)