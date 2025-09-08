# ProST：小型语言模型驱动的帕累托最优多智能体系统渐进式子任务训练

发布时间：2025年09月02日

`Agent` `基础理论`

> ProST: Progressive Sub-task Training for Pareto-Optimal Multi-agent Systems Using Small Language Models

# 摘要

> 采用较小语言模型（SLMs）的多智能体系统，为解决复杂问题提供了可行方案，可替代由大型语言模型（LLMs）驱动的单智能体系统。本研究旨在对比这些方案在有效性与效率上的表现。为探究这一权衡，我们在AppWorld环境中针对复杂问题，采用不同规模的语言模型构建了单智能体与多智能体系统实例。
  研究发现，较小语言模型（SLMs）在长轨迹学习中存在瓶颈，导致性能受限。即便针对特定角色训练，SLMs仍难以有效掌握所有子任务。为此，我们提出一种简洁的渐进式子任务训练策略：在每个训练轮次中逐步引入新子任务。该策略类似实例级课程学习，实验表明其在所有配置下均能稳定提升多智能体的有效性。帕累托分析显示，微调后的多智能体系统在有效性与效率的权衡上更具优势。进一步的消融实验与分析证实，渐进式训练策略不仅关键，还能有效降低子任务错误率。

> Multi-agent systems with smaller language models (SLMs) present a viable alternative to single agent systems powered by large language models (LLMs) for addressing complex problems. In this work, we study how these alternatives compare in terms of both effectiveness and efficiency. To study this trade-off, we instantiate single and multi-agent systems for the complex problems in the AppWorld environment using different sized language models.
  We find that difficulties with long-trajectory learning in smaller language models (SLMs) limit their performance. Even when trained for specialized roles, SLMs fail to learn all subtasks effectively. To address this issue, we introduce a simple progressive sub-task training strategy, which introduces new sub-tasks progressively in each training epoch. We find that this novel strategy, analogous to instance level curriculum learning, consistently improves the effectiveness of multi-agents at all configurations. Our Pareto analysis shows that fine-tuned multi-agent systems yield better effectiveness-efficiency trade-offs. Additional ablations and analyses shows the importance of our progressive training strategy and its ability to reduce subtask error rates.

[Arxiv](https://arxiv.org/abs/2509.04508)