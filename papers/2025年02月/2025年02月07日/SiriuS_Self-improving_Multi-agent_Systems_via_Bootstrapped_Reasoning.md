# SiriuS：通过自举式推理实现自我提升的多智能体系统

发布时间：2025年02月07日

`LLM应用` `人工智能`

> SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning

# 摘要

> 大型语言模型 (LLMs) 驱动的多智能体 AI 系统正被广泛应用于解决复杂任务。然而，这些系统往往依赖脆弱的手工设计提示和启发式方法，使得优化困难重重。优化多智能体系统的一大挑战在于为专门智能体获取合适的训练数据。为此，我们推出了 SiriuS，一个自我改进、推理驱动的多智能体系统优化框架。我们的核心方法是构建一个经验库：一个存储高质量推理轨迹的仓库。通过保留导致成功结果的推理步骤，经验库为优化多智能体系统提供了强大的训练集。此外，我们还引入了库增强过程，用于完善不成功的轨迹，进一步丰富了经验库。SiriuS 在推理和生物医学问答任务上实现了 2.86\% 到 21.88\% 的性能提升，并增强了智能体在竞争环境中的谈判能力。实验结果表明，SiriuS 不仅提升了多智能体的性能，还生成了可用于未来自我修正和自我强化的可重用数据。

> Multi-agent AI systems powered by large language models (LLMs) are increasingly applied to solve complex tasks. However, these systems often rely on fragile, manually designed prompts and heuristics, making optimization difficult. A key challenge in optimizing multi-agent systems is acquiring suitable training data for specialized agents. We introduce SiriuS, a self-improving, reasoning-driven optimization framework for multi-agent systems. Central to our approach is the construction of an experience library: a repository of high-quality reasoning trajectories. The library is built by retaining reasoning steps that lead to successful outcomes, providing a robust training set for optimizing multi-agent system. Additionally, we introduce a library augmentation procedure that refines unsuccessful trajectories, further enriching the library. SiriuS boosts performance by 2.86\% to 21.88\% on reasoning and biomedical QA and enhances agent negotiation in competitive settings. Our results show that SiriuS enhances multi-agent performance while generating reusable data for self-correction and self-play enhancement in the future.

[Arxiv](https://arxiv.org/abs/2502.04780)