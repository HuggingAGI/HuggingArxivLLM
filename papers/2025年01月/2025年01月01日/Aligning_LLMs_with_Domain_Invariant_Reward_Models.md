# 大型语言模型与领域不变奖励模型的对齐

发布时间：2025年01月01日

`LLM理论

理由：这篇论文主要讨论了如何通过利用从简单源领域收集的反馈来训练领域不变的奖励模型，以解决在缺乏偏好数据的领域中与人类偏好对齐的问题。这涉及到对大型语言模型（LLMs）的理论研究，特别是如何在不同领域之间迁移和优化奖励模型。因此，这篇论文更适合归类为“LLM理论”。` `机器学习`

> Aligning LLMs with Domain Invariant Reward Models

# 摘要

> # 摘要
在缺乏偏好数据的领域中，将大型语言模型（LLMs）与人类偏好对齐颇具挑战。我们通过利用从更简单的源领域收集的反馈，解决了为目标领域学习奖励模型的问题。我们的核心观点是，尽管领域差异显著，但人类偏好蕴含的领域无关概念可以被奖励模型有效捕捉。我们提出了\method框架，通过优化双重损失来训练领域不变奖励模型：领域损失最小化源与目标分布间的差异，源损失优化源领域的偏好。我们在四种不同设置中评估并分析了\method的通用性：（1）跨语言迁移（准确率：$0.621 ightarrow 0.661$），（2）从干净到嘈杂（准确率：$0.671 ightarrow 0.703$），（3）从少样本到全样本迁移（准确率：$0.845 ightarrow 0.920$），以及（4）从简单到复杂任务迁移（相关性：$0.508 ightarrow 0.556$）。代码、模型和数据可在url{https://github.com/portal-cornell/dial}获取。

> Aligning large language models (LLMs) to human preferences is challenging in domains where preference data is unavailable. We address the problem of learning reward models for such target domains by leveraging feedback collected from simpler source domains, where human preferences are easier to obtain. Our key insight is that, while domains may differ significantly, human preferences convey \emph{domain-agnostic} concepts that can be effectively captured by a reward model. We propose \method, a framework that trains domain-invariant reward models by optimizing a dual loss: a domain loss that minimizes the divergence between source and target distribution, and a source loss that optimizes preferences on the source domain. We show \method is a general approach that we evaluate and analyze across 4 distinct settings: (1) Cross-lingual transfer (accuracy: $0.621 \rightarrow 0.661$), (2) Clean-to-noisy (accuracy: $0.671 \rightarrow 0.703$), (3) Few-shot-to-full transfer (accuracy: $0.845 \rightarrow 0.920$), and (4) Simple-to-complex tasks transfer (correlation: $0.508 \rightarrow 0.556$). Our code, models and data are available at url{https://github.com/portal-cornell/dial}.

[Arxiv](https://arxiv.org/abs/2501.00911)