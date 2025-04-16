# 任务向量何时有效？对非线性Transformer的泛化能力分析

发布时间：2025年04月15日

`LLM理论` `机器学习`

> When is Task Vector Provably Effective for Model Editing? A Generalization Analysis of Nonlinear Transformers

# 摘要

> 任务算术是一种通过向预训练模型添加任务向量的加权和来进行模型编辑的方法。每个任务向量代表从预训练模型到特定任务微调模型的权重更新。这一方法近期因其高效计算特性而备受关注，尤其在多任务学习、遗忘机制和领域外泛化能力方面展现出潜力。然而，由于训练基于Transformer模型的高度非凸性，我们对任务向量为何能执行各种概念操作的理论理解仍然有限。本文首次为非线性Transformer上任务向量方法的泛化保证提供了理论表征。我们基于判别模式构建了一个概念学习框架，其中每个任务均被建模为二分类问题。理论证明显示，任务加法在同时学习不相关或对齐任务时表现优异，而任务否定则能有效从不相关或矛盾任务中实现遗忘。此外，我们证明了通过合理选择任务算术中的线性系数，可以确保模型对领域外任务的泛化能力。我们的理论成果不仅适用于密集权重参数，也适用于其低秩近似。尽管这些理论是在概念框架下建立的，但我们在大型语言模型Phi-1.5（13亿参数）的实际机器学习任务中验证了这些发现。

> Task arithmetic refers to editing the pre-trained model by adding a weighted sum of task vectors, each of which is the weight update from the pre-trained model to fine-tuned models for certain tasks. This approach recently gained attention as a computationally efficient inference method for model editing, e.g., multi-task learning, forgetting, and out-of-domain generalization capabilities. However, the theoretical understanding of why task vectors can execute various conceptual operations remains limited, due to the highly non-convexity of training Transformer-based models. To the best of our knowledge, this paper provides the first theoretical characterization of the generalization guarantees of task vector methods on nonlinear Transformers. We consider a conceptual learning setting, where each task is a binary classification problem based on a discriminative pattern. We theoretically prove the effectiveness of task addition in simultaneously learning a set of irrelevant or aligned tasks, as well as the success of task negation in unlearning one task from irrelevant or contradictory tasks. Moreover, we prove the proper selection of linear coefficients for task arithmetic to achieve guaranteed generalization to out-of-domain tasks. All of our theoretical results hold for both dense-weight parameters and their low-rank approximations. Although established in a conceptual setting, our theoretical findings were validated on a practical machine unlearning task using the large language model Phi-1.5 (1.3B).

[Arxiv](https://arxiv.org/abs/2504.10957)