# (P)rior(D)yna(F)low：基于多智能体协作的先验动态工作流构建

发布时间：2025年09月17日

`Agent` `基础理论`

> (P)rior(D)yna(F)low: A Priori Dynamic Workflow Construction via Multi-Agent Collaboration

# 摘要

> 近期研究表明，通过精心设计协调大型语言模型（LLMs）的工作流，其任务解决能力显著优于单一模型。尽管越来越多的研究聚焦自主工作流构建，但现有方法大多仅依赖历史经验，导致效率与适应性受限。我们认为，历史经验虽有价值，工作流构建更需灵活适配各任务的独特属性。为此，我们提出一种用于自动化工作流构建的先验动态框架：该框架首先借助Q表学习优化决策空间，指导智能体决策并高效利用历史经验；同时，智能体评估当前任务进展，对下一个执行的智能体做出先验决策，从而主动为每个任务选择更适配的工作流结构。此外，我们还融入冷启动初始化、早停和剪枝等机制，进一步提升系统效率。在四个基准数据集上的实验评估验证了该方法的可行性与有效性：与最先进的基线方法相比，平均提升4.05%，同时将工作流构建及推理成本降至现有方法的30.68%-48.31%。

> Recent studies have shown that carefully designed workflows coordinating large language models(LLMs) significantly enhance task-solving capabilities compared to using a single model. While an increasing number of works focus on autonomous workflow construction, most existing approaches rely solely on historical experience, leading to limitations in efficiency and adaptability. We argue that while historical experience is valuable, workflow construction should also flexibly respond to the unique characteristics of each task. To this end, we propose an a priori dynamic framework for automated workflow construction. Our framework first leverages Q-table learning to optimize the decision space, guiding agent decisions and enabling effective use of historical experience. At the same time, agents evaluate the current task progress and make a priori decisions regarding the next executing agent, allowing the system to proactively select the more suitable workflow structure for each given task. Additionally, we incorporate mechanisms such as cold-start initialization, early stopping, and pruning to further improve system efficiency. Experimental evaluations on four benchmark datasets demonstrate the feasibility and effectiveness of our approach. Compared to state-of-the-art baselines, our method achieves an average improvement of 4.05%, while reducing workflow construction and inference costs to only 30.68%-48.31% of those required by existing methods.

[Arxiv](https://arxiv.org/abs/2509.14547)