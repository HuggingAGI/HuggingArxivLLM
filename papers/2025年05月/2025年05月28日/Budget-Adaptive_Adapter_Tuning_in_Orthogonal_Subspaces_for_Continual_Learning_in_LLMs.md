# 预算自适应正交子空间适配器微调，用于LLM的持续学习

发布时间：2025年05月28日

`LLM理论

摘要讨论了大语言模型在持续学习中的优化方法，提出了一种新的参数适应方法，属于模型理论层面的改进。` `人工智能` `机器学习`

> Budget-Adaptive Adapter Tuning in Orthogonal Subspaces for Continual Learning in LLMs

# 摘要

> 大语言模型（LLMs）在持续学习（CL）场景中常常面临灾难性遗忘问题，即在顺序训练新任务时，模型对先前学习任务的性能会出现严重下降。尽管基于正交子空间的开创性持续学习方法能够缓解任务干扰问题，但这些方法通常采用固定预算分配策略，忽视了不同任务和不同网络层之间复杂性的差异。此外，近期针对LLMs的自适应预算调整方法往往采用多阶段范式，将优化和预算分配过程解耦。这种解耦可能导致潜在的不匹配问题，从而限制了这些方法在持续学习场景中的实际应用效果。为了解决上述问题，我们提出了一种名为OA-Adapter的高效参数持续学习方法，该方法在单一端到端训练阶段实现了动态预算适应与正交子空间学习的有机统一。具体而言，OA-Adapter引入了一种动态瓶颈维度自适应机制，能够在实现高效参数预算分配的同时，优化任务目标而无偏差。为了有效保存先前获得的知识并协调动态预算分配，我们在当前任务的参数子空间与历史任务的动态分配参数子空间之间施加了正交约束。在持续学习基准测试中的实验结果表明，与现有最优方法相比，OA-Adapter在准确性和参数效率方面均表现更优。具体而言，OA-Adapter在标准CL基准上使用了少58.5%的参数，却实现了更高的平均准确率。

> Large language models (LLMs) often suffer from catastrophic forgetting in continual learning (CL) scenarios, where performance on previously learned tasks degrades severely while training on sequentially arriving tasks. Although pioneering CL approaches using orthogonal subspaces can mitigate task interference, they typically employ fixed budget allocation, neglecting the varying complexity across tasks and layers. Besides, recent budget-adaptive tuning methods for LLMs often adopt multi-stage paradigms that decouple optimization and budget allocation. Such decoupling results in potential misalignment, which hinders those approaches' practical application in CL scenarios. To address these limitations, we propose OA-Adapter, a novel parameter-efficient approach for continual learning in LLMs that unifies dynamic budget adaptation with orthogonal subspace learning in a single end-to-end training stage. Specifically, OA-Adapter introduces a dynamic bottleneck dimension adaptation mechanism that simultaneously allocates an efficient parameter budget and optimizes task objectives without misalignment. To effectively preserve previously acquired knowledge while coordinating with the dynamic budget allocation, orthogonal constraints are applied specifically between the parameter subspace of the current task and the dynamically allocated parameter subspaces of historical tasks. Experimental results on continual learning benchmarks demonstrate that OA-Adapter outperforms state-of-the-art methods in both accuracy and parameter efficiency, achieving higher average accuracy while using 58.5% fewer parameters on the standard CL benchmark.

[Arxiv](https://arxiv.org/abs/2505.22358)