# SWIRL：移动GUI控制中交错强化学习的分阶段工作流

发布时间：2025年08月27日

`Agent` `基础理论`

> SWIRL: A Staged Workflow for Interleaved Reinforcement Learning in Mobile GUI Control

# 摘要

> 随着大型视觉语言模型（LVLMs）和智能体系统的飞速发展，人们对能够可靠将自然语言转化为界面操作的移动GUI智能体愈发关注。然而，现有的单智能体方法仍受结构限制。尽管多智能体系统能自然解耦不同能力，但多智能体强化学习（MARL）的最新进展却常因效率问题受阻，且与现有LVLM架构不兼容。为应对这些挑战，我们提出了SWIRL——一种专为多智能体系统设计的分阶段交错强化学习工作流。SWIRL将MARL转化为一系列单智能体强化学习任务，每次仅更新一个智能体，其余保持固定。这种设计不仅实现了稳定训练，还能促进智能体间的高效协作。理论上，我们提出了逐步安全边界、跨轮次单调改进定理及回报收敛保证，确保优化过程稳健且有章可循。在移动GUI控制应用中，SWIRL实例化为两个智能体：Navigator（将语言和屏幕上下文转化为结构化计划）和Interactor（将计划落地为可执行的原子操作）。大量实验显示，SWIRL在高级和低级GUI基准测试中均表现卓越。除GUI任务外，SWIRL在多智能体数学推理中也展现出强大能力，凸显了其作为开发高效稳健多智能体系统通用框架的潜力。

> The rapid advancement of large vision language models (LVLMs) and agent systems has heightened interest in mobile GUI agents that can reliably translate natural language into interface operations. Existing single-agent approaches, however, remain limited by structural constraints. Although multi-agent systems naturally decouple different competencies, recent progress in multi-agent reinforcement learning (MARL) has often been hindered by inefficiency and remains incompatible with current LVLM architectures. To address these challenges, we introduce SWIRL, a staged workflow for interleaved reinforcement learning designed for multi-agent systems. SWIRL reformulates MARL into a sequence of single-agent reinforcement learning tasks, updating one agent at a time while keeping the others fixed. This formulation enables stable training and promotes efficient coordination across agents. Theoretically, we provide a stepwise safety bound, a cross-round monotonic improvement theorem, and convergence guarantees on return, ensuring robust and principled optimization. In application to mobile GUI control, SWIRL instantiates a Navigator that converts language and screen context into structured plans, and an Interactor that grounds these plans into executable atomic actions. Extensive experiments demonstrate superior performance on both high-level and low-level GUI benchmarks. Beyond GUI tasks, SWIRL also demonstrates strong capability in multi-agent mathematical reasoning, underscoring its potential as a general framework for developing efficient and robust multi-agent systems.

[Arxiv](https://arxiv.org/abs/2508.20018)