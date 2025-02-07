# 谁是MVP？LLM代理模块归因的博弈论评估基准

发布时间：2025年02月01日

`Agent

理由：这篇论文主要讨论了大型语言模型（LLM）代理框架的模块化架构及其性能评估方法。论文提出了一个名为 CapaBench 的评估框架，用于量化各个模块对整体系统性能的贡献。这涉及到代理的规划、推理、动作执行和反思等组件，这些都是 Agent 领域的核心内容。因此，这篇论文应被分类为Agent。` `人工智能` `评估框架`

> Who's the MVP? A Game-Theoretic Evaluation Benchmark for Modular Attribution in LLM Agents

# 摘要

> # 摘要
大型语言模型（LLM）代理框架通常采用模块化架构，包含规划、推理、动作执行和反思等组件，以应对复杂任务。然而，量化每个模块对整体系统性能的贡献仍然是一个重大挑战，阻碍了优化和可解释性。为此，我们推出了 CapaBench（能力级别评估基准），这是一个基于合作博弈论中 Shapley 值的评估框架，能够系统地衡量单个模块及其在代理架构中相互作用的边际影响。通过在所有可能的组合中用测试变体替换默认模块，CapaBench 提供了一种原则性的性能贡献归因方法。主要贡献包括：（1）我们首次提出了一种基于 Shapley 值的方法来量化 LLM 代理中能力的贡献；（2）具有高 Shapley 值的模块在组合时始终能带来可预测的性能提升，从而实现有针对性的优化；（3）我们构建了一个包含 1,000 多个条目的多轮数据集，涵盖多个领域和实际任务场景，能够全面评估代理能力。CapaBench 弥合了组件级评估与整体系统评估之间的差距，为优化模块化 LLM 代理并推动其在复杂现实场景中的部署提供了可操作的见解。

> Large Language Model (LLM) agents frameworks often employ modular architectures, incorporating components such as planning, reasoning, action execution, and reflection to tackle complex tasks. However, quantifying the contribution of each module to overall system performance remains a significant challenge, impeding optimization and interpretability. To address this, we introduce CapaBench (Capability-level Assessment Benchmark), an evaluation framework grounded in cooperative game theory's Shapley Value, which systematically measures the marginal impact of individual modules and their interactions within an agent's architecture. By replacing default modules with test variants across all possible combinations, CapaBench provides a principle method for attributing performance contributions. Key contributions include: (1) We are the first to propose a Shapley Value-based methodology for quantifying the contributions of capabilities in LLM agents; (2) Modules with high Shapley Values consistently lead to predictable performance gains when combined, enabling targeted optimization; and (3) We build a multi-round dataset of over 1,000 entries spanning diverse domains and practical task scenarios, enabling comprehensive evaluation of agent capabilities. CapaBench bridges the gap between component-level evaluation and holistic system assessment, providing actionable insights for optimizing modular LLM agents and advancing their deployment in complex, real-world scenarios.

[Arxiv](https://arxiv.org/abs/2502.00510)