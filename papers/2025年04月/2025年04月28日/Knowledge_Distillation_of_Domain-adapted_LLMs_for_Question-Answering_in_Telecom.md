# # 针对电信领域问答任务的领域适配大型语言模型知识蒸馏研究

发布时间：2025年04月28日

`LLM应用

理由：这篇论文探讨了知识蒸馏在压缩大型语言模型规模中的应用，特别是在特定领域任务中的表现。它通过实验研究了不同监督微调策略和蒸馏算法对模型性能的影响，属于模型压缩和领域适应的应用层面研究，因此归类为LLM应用。` `问答系统`

> Knowledge Distillation of Domain-adapted LLMs for Question-Answering in Telecom

# 摘要

> 知识蒸馏（KD）是一种用于压缩大型语言模型（LLMs）规模的有效方法。通过训练一个参数量较少的LLM（学生模型），使其模仿一个规模更大的LLM（教师模型）在特定任务上的表现。然而，在特定领域任务中，是否需要对教师模型、学生模型或两者进行领域适应尚不明确。本研究以电信领域问答（QA）任务为切入点，系统性地探讨了这一问题。

我们设计了三组实验：仅对教师模型进行监督微调（SFT）、仅对学生模型进行SFT，以及在知识蒸馏前对两者同时进行SFT。通过实验研究了词汇（相同与不同）和蒸馏算法（普通KD与双空间KD，DSKD）对蒸馏模型性能的影响。采用14种多维度指标（包括N-gram、嵌入和基于LLM的指标）对蒸馏效果进行全面评估。

实验结果表明，当教师模型与学生模型拥有相同词汇时，仅对教师模型进行SFT能够显著提升蒸馏模型的性能，这一效果在不同算法和指标下均表现一致。总体而言，同时对教师模型和学生模型进行SFT能带来更优的性能表现，尽管统计显著性会因教师模型的词汇而有所不同。

> Knowledge Distillation (KD) is one of the approaches to reduce the size of Large Language Models (LLMs). A LLM with smaller number of model parameters (student) is trained to mimic the performance of a LLM of a larger size (teacher model) on a specific task. For domain-specific tasks, it is not clear if teacher or student model, or both, must be considered for domain adaptation. In this work, we study this problem from perspective of telecom domain Question-Answering (QA) task. We systematically experiment with Supervised Fine-tuning (SFT) of teacher only, SFT of student only and SFT of both prior to KD. We design experiments to study the impact of vocabulary (same and different) and KD algorithms (vanilla KD and Dual Space KD, DSKD) on the distilled model. Multi-faceted evaluation of the distillation using 14 different metrics (N-gram, embedding and LLM-based metrics) is considered. Experimental results show that SFT of teacher improves performance of distilled model when both models have same vocabulary, irrespective of algorithm and metrics. Overall, SFT of both teacher and student results in better performance across all metrics, although the statistical significance of the same depends on the vocabulary of the teacher models.

[Arxiv](https://arxiv.org/abs/2504.20000)