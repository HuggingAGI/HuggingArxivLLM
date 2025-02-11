# PiKE：适用于低梯度冲突场景的多任务学习自适应数据混合方法

发布时间：2025年02月10日

`LLM理论

理由：这篇论文主要探讨了多任务学习中的数据混合与采样策略优化，提出了一种自适应的数据混合算法PiKE。该研究集中在模型训练策略和优化方法上，属于理论层面的探讨，旨在提升模型的训练效率和性能。因此，它被归类为LLM理论。` `机器学习`

> PiKE: Adaptive Data Mixing for Multi-Task Learning Under Low Gradient Conflicts

# 摘要

> 现代机器学习模型通过在多样化的数据集和任务上进行训练，以提升模型的泛化能力。在多任务学习中，如何在不同数据源之间优化数据混合与采样策略是一个关键挑战。尽管先前的研究主要集中在缓解任务间的梯度冲突，但我们发现许多实际场景——如大规模基础模型中的多语言训练和多领域学习——通常表现出积极的任务交互，而梯度冲突则微乎其微或完全不存在。基于这一观察，我们提出了PiKE（基于正向梯度交互的K任务权重估计器），这是一种自适应的数据混合算法，能够在训练过程中动态调整各任务的贡献。通过优化任务采样来最小化总体损失，PiKE几乎无需额外的计算开销，就能有效利用正向梯度交互。我们为PiKE提供了理论上的收敛性保证，并证明了其相较于静态和非自适应混合策略的优越性。此外，我们将PiKE扩展到促进任务间的公平学习，确保各任务的均衡进展并防止任务欠代表。在大规模语言模型预训练的实证评估中，PiKE始终优于现有的启发式和静态混合策略，实现了更快的收敛速度和更优的下游任务性能。

> Modern machine learning models are trained on diverse datasets and tasks to improve generalization. A key challenge in multitask learning is determining the optimal data mixing and sampling strategy across different data sources. Prior research in this multi-task learning setting has primarily focused on mitigating gradient conflicts between tasks. However, we observe that many real-world multitask learning scenarios-such as multilingual training and multi-domain learning in large foundation models-exhibit predominantly positive task interactions with minimal or no gradient conflict. Building on this insight, we introduce PiKE (Positive gradient interaction-based K-task weights Estimator), an adaptive data mixing algorithm that dynamically adjusts task contributions throughout training. PiKE optimizes task sampling to minimize overall loss, effectively leveraging positive gradient interactions with almost no additional computational overhead. We establish theoretical convergence guarantees for PiKE and demonstrate its superiority over static and non-adaptive mixing strategies. Additionally, we extend PiKE to promote fair learning across tasks, ensuring balanced progress and preventing task underrepresentation. Empirical evaluations on large-scale language model pretraining show that PiKE consistently outperforms existing heuristic and static mixing strategies, leading to faster convergence and improved downstream task performance.

[Arxiv](https://arxiv.org/abs/2502.06244)