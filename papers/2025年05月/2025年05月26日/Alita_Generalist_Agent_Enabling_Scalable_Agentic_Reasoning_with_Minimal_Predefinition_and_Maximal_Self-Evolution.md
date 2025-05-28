# Alita：通用智能体，实现大规模智能体推理能力，仅需极简预定义，赋予自我进化最大潜力

发布时间：2025年05月26日

`Agent` `智能体` `跨领域`

> Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution

# 摘要

> 大型语言模型 (LLMs) 的突破让智能体能够自主执行复杂、开放性的任务。然而，现有框架往往严重依赖手动预定义的工具和流程，这限制了它们在跨领域中的适应性和扩展性。我们提出了 Alita——一款遵循“大道至简”原则设计的通用型智能体，通过最小的预定义和最大的自我进化，实现可扩展的智能体推理能力。在最小预定义方面，Alita 仅配备了一个直接解决问题的组件，比依赖复杂工具和流程的传统方法简单得多。这种简洁设计使其在解决难题时更具通用性，不受工具限制。在最大化自我进化方面，我们通过提供通用组件使 Alita 具备创造力，使其能够从开源资源中自动生成与任务相关的模型上下文协议 (MCP)，从而自主构建、优化和重用外部能力，助力可扩展的智能体推理。值得注意的是，Alita 在 GAIA 基准验证数据集上实现了 75.15% 的 pass@1 准确率和 87.27% 的 pass@3 准确率，位居通用型智能体之首；在 Mathvista 和 PathVQA 上分别达到了 74.00% 和 52.00% 的 pass@1 准确率，超越了众多复杂度远超自身的智能体系统。更多详情请访问 $\href{https://github.com/CharlesQ9/Alita}{https://github.com/CharlesQ9/Alita}$。

> Recent advances in large language models (LLMs) have enabled agents to autonomously perform complex, open-ended tasks. However, many existing frameworks depend heavily on manually predefined tools and workflows, which hinder their adaptability, scalability, and generalization across domains. In this work, we introduce Alita--a generalist agent designed with the principle of "Simplicity is the ultimate sophistication," enabling scalable agentic reasoning through minimal predefinition and maximal self-evolution. For minimal predefinition, Alita is equipped with only one component for direct problem-solving, making it much simpler and neater than previous approaches that relied heavily on hand-crafted, elaborate tools and workflows. This clean design enhances its potential to generalize to challenging questions, without being limited by tools. For Maximal self-evolution, we enable the creativity of Alita by providing a suite of general-purpose components to autonomously construct, refine, and reuse external capabilities by generating task-related model context protocols (MCPs) from open source, which contributes to scalable agentic reasoning. Notably, Alita achieves 75.15% pass@1 and 87.27% pass@3 accuracy, which is top-ranking among general-purpose agents, on the GAIA benchmark validation dataset, 74.00% and 52.00% pass@1, respectively, on Mathvista and PathVQA, outperforming many agent systems with far greater complexity. More details will be updated at $\href{https://github.com/CharlesQ9/Alita}{https://github.com/CharlesQ9/Alita}$.

[Arxiv](https://arxiv.org/abs/2505.20286)