# # 见证：通过专家序列的持续微调（SEE: Continual Fine-tuning with Sequential Ensemble of Experts）

发布时间：2025年04月09日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在持续微调过程中面临的灾难性遗忘问题，并提出了一种新的框架（SEE）来解决这一问题。该框架涉及到模型的架构设计、训练策略以及持续学习的理论，属于对LLM本身的理论研究。因此，这篇论文应归类到LLM理论类别中。` `人工智能` `机器学习`

> SEE: Continual Fine-tuning with Sequential Ensemble of Experts

# 摘要

> 大型语言模型（LLMs）的持续微调面临灾难性遗忘问题。基于复习的方法通过保留少量旧数据来缓解这一问题。然而，性能下降仍不可避免。虽然为每个任务训练独立的专家有助于防止遗忘，但如何有效整合这些专家仍是一个挑战。一些方法使用路由器将任务分配给专家，但在持续学习中，它们通常需要重新训练以实现最优性能。

为了解决这些挑战，我们引入了专家序列集成框架（SEE）。SEE无需额外的路由机制，使每个专家能够独立决定是否处理某个查询。该框架采用分布式路由策略，在持续微调过程中，SEE仅需为新任务训练新的专家，而无需重新训练整个系统。

实验表明，SEE在持续微调中优于先前的方法，包括多任务学习。它还展示了出色的泛化能力，因为专家能够有效识别出分布外的查询，这些查询可以被引导至更通用的模型进行处理。这项工作突显了在每个专家中整合路由和响应机制的潜在价值，为未来分布式模型集成的发展铺平了道路。

> Continual fine-tuning of large language models (LLMs) suffers from catastrophic forgetting. Rehearsal-based methods mitigate this problem by retaining a small set of old data. Nevertheless, they still suffer inevitable performance loss. Although training separate experts for each task can help prevent forgetting, effectively assembling them remains a challenge. Some approaches use routers to assign tasks to experts, but in continual learning, they often require retraining for optimal performance. To address these challenges, we introduce the Sequential Ensemble of Experts (SEE) framework. SEE removes the need for an additional router, allowing each expert to independently decide whether a query should be handled. The framework employs distributed routing, and during continual fine-tuning, SEE only requires the training of new experts for incoming tasks rather than retraining the entire system. Experiments reveal that the SEE outperforms prior approaches, including multi-task learning, in continual fine-tuning. It also demonstrates remarkable generalization ability, as the expert can effectively identify out-of-distribution queries, which can then be directed to a more generalized model for resolution. This work highlights the promising potential of integrating routing and response mechanisms within each expert, paving the way for the future of distributed model ensembling.

[Arxiv](https://arxiv.org/abs/2504.06664)