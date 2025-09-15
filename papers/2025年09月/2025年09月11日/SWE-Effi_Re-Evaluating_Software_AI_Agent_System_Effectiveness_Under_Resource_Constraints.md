# SWE-Effi：资源约束下软件AI智能体系统有效性的再评估

发布时间：2025年09月11日

`Agent` `工业与制造`

> SWE-Effi: Re-Evaluating Software AI Agent System Effectiveness Under Resource Constraints

# 摘要

> 大型语言模型（LLMs）与代码智能体的快速发展，展现出辅助软件工程（SWE）任务的巨大潜力，例如自主解决问题和添加新功能。然而现有软件工程AI评估基准（如SWE-bench）仅关注解决方案的准确性，却忽略了资源受限现实世界中至关重要的有效性因素。这一问题具有普遍性，并非软件工程领域独有：任何AI系统都不应仅追求正确性，还需具备成本效益。为此，我们提出SWE-Effi——一套全新指标，旨在通过整体有效性评分重新评估AI系统。我们将有效性定义为结果准确性（如问题解决率）与资源消耗（如token和时间）之间的平衡。本文聚焦软件工程场景，利用这套多维指标在SWE-bench基准的子集上，对主流AI系统的问题解决能力进行了重新排名。研究发现，AI系统的有效性不仅取决于其框架本身，还取决于与基础模型的集成效果——这是以资源高效方式实现卓越性能的关键。我们还识别出系统性挑战，例如“token滚雪球”效应，更值得注意的是“昂贵失败”模式：智能体在处理无法解决的任务时会消耗过多资源，这不仅限制实际部署，还会增加强化学习训练中失败推广的成本。最后，我们观察到token预算与时间预算下的有效性存在明显权衡，这在项目预算管理和可扩展强化学习（快速响应在此类学习中至关重要）中发挥着关键作用。

> The advancement of large language models (LLMs) and code agents has demonstrated significant potential to assist software engineering (SWE) tasks, such as autonomous issue resolution and feature addition. Existing AI for software engineering leaderboards (e.g., SWE-bench) focus solely on solution accuracy, ignoring the crucial factor of effectiveness in a resource-constrained world. This is a universal problem that also exists beyond software engineering tasks: any AI system should be more than correct - it must also be cost-effective. To address this gap, we introduce SWE-Effi, a set of new metrics to re-evaluate AI systems in terms of holistic effectiveness scores. We define effectiveness as the balance between the accuracy of outcome (e.g., issue resolve rate) and the resources consumed (e.g., token and time). In this paper, we specifically focus on the software engineering scenario by re-ranking popular AI systems for issue resolution on a subset of the SWE-bench benchmark using our new multi-dimensional metrics. We found that AI system's effectiveness depends not just on the scaffold itself, but on how well it integrates with the base model, which is key to achieving strong performance in a resource-efficient manner. We also identified systematic challenges such as the "token snowball" effect and, more significantly, a pattern of "expensive failures". In these cases, agents consume excessive resources while stuck on unsolvable tasks - an issue that not only limits practical deployment but also drives up the cost of failed rollouts during RL training. Lastly, we observed a clear trade-off between effectiveness under the token budget and effectiveness under the time budget, which plays a crucial role in managing project budgets and enabling scalable reinforcement learning, where fast responses are essential.

[Arxiv](https://arxiv.org/abs/2509.09853)