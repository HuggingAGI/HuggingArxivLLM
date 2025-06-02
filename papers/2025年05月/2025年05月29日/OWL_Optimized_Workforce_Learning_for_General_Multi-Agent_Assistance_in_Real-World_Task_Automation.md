# OWL：优化 workforce 学习，助力现实任务自动化中的多智能体通用辅助

发布时间：2025年05月29日

`Agent` `人工智能` `多智能体系统`

> OWL: Optimized Workforce Learning for General Multi-Agent Assistance in Real-World Task Automation

# 摘要

> 基于 LLM 的多智能体系统在自动化现实任务中潜力巨大，但受限于领域特定性，跨领域迁移始终是个难题。现有方法存在两大缺陷：应用于新领域时，需完全重设架构并重新训练所有组件。为此，我们推出 Workforce，一个层级化的多智能体框架，通过模块化架构将战略规划与专门化执行解耦，包含以下核心组件：(i) 一个领域无关的任务分解 Planner，(ii) 一个子任务管理 Coordinator，以及 (iii) 具备领域特定工具调用能力的专用 Worker。这种设计不仅在推理阶段实现了跨领域迁移，训练阶段同样表现出色：推理时，Workforce 可通过增删工作智能体无缝适应新领域；训练时，我们引入了优化工作力学习 (OWL)，通过强化学习优化领域无关规划器，显著提升跨领域泛化能力。我们在涵盖多种现实多领域任务的 GAIA 基准上验证了 Workforce 的效能。实验结果表明，Workforce 达到了 69.70% 的开源最先进水平，超越 OpenAI 的 Deep Research 等商用系统 2.34%。更令人振奋的是，我们的 OWL 训练的 32B 模型实现了 52.73% 的准确率，较之前提升了 16.37%，并在多项挑战性任务上展现出与 GPT-4 相当的表现。总之，Workforce 通过实现可扩展的泛化和模块化的领域迁移，为下一代通用 AI 助手的发展奠定了坚实基础。

> Large Language Model (LLM)-based multi-agent systems show promise for automating real-world tasks but struggle to transfer across domains due to their domain-specific nature. Current approaches face two critical shortcomings: they require complete architectural redesign and full retraining of all components when applied to new domains. We introduce Workforce, a hierarchical multi-agent framework that decouples strategic planning from specialized execution through a modular architecture comprising: (i) a domain-agnostic Planner for task decomposition, (ii) a Coordinator for subtask management, and (iii) specialized Workers with domain-specific tool-calling capabilities. This decoupling enables cross-domain transferability during both inference and training phases: During inference, Workforce seamlessly adapts to new domains by adding or modifying worker agents; For training, we introduce Optimized Workforce Learning (OWL), which improves generalization across domains by optimizing a domain-agnostic planner with reinforcement learning from real-world feedback. To validate our approach, we evaluate Workforce on the GAIA benchmark, covering various realistic, multi-domain agentic tasks. Experimental results demonstrate Workforce achieves open-source state-of-the-art performance (69.70%), outperforming commercial systems like OpenAI's Deep Research by 2.34%. More notably, our OWL-trained 32B model achieves 52.73% accuracy (+16.37%) and demonstrates performance comparable to GPT-4o on challenging tasks. To summarize, by enabling scalable generalization and modular domain transfer, our work establishes a foundation for the next generation of general-purpose AI assistants.

[Arxiv](https://arxiv.org/abs/2505.23885)