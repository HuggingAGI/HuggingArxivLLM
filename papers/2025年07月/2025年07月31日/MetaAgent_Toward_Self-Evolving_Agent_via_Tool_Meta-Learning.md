# 元代理：通过工具元学习，致力于实现自我进化的智能体

发布时间：2025年07月31日

`Agent` `智能体系统`

> MetaAgent: Toward Self-Evolving Agent via Tool Meta-Learning

# 摘要

> 本研究提出了一种名为MetaAgent的智能体范式，它基于“学习-实践-改进”的原则，通过动手实践和持续自我改进来发展专业知识。MetaAgent从一个极简的工作流程开始，仅具备基础推理和自适应求助能力。当遇到知识缺口时，它会生成自然语言的帮助请求，并通过专用工具路由器将其路由到最合适的外部工具。在解决问题的过程中，MetaAgent持续进行自我反思和答案验证，将可操作的经验提炼成简洁的文字，并动态整合到未来的任务上下文中。此外，MetaAgent自主构建内部工具和持久知识库，通过整理其工具使用历史，进一步提升其检索和整合相关信息的能力。我们称这一持续的数据驱动过程为	extit{元工具学习}，通过这一过程，MetaAgent逐步优化其推理和工具使用策略，无需更改模型参数或进行进一步的后训练。在包括GAIA、WebWalkerQA和BrowseCamp在内的具有挑战性的知识发现基准测试中，MetaAgent始终超越基于工作流的基线，并达到或超过端到端训练的代理，展示了自我演化的智能体系统在稳健、通用知识发现方面的潜力。我们的源代码可在https://github.com/qhjqhj00/MetaAgent获取。

> In this work, we propose MetaAgent, an agentic paradigm inspired by the principle of learning-by-doing, where expertise is developed through hands-on practice and continual self-improvement. MetaAgent starts with a minimal workflow, equipped only with basic reasoning and adaptive help-seeking abilities. When a knowledge gap is encountered, MetaAgent generates natural language help requests, which are routed to the most suitable external tool by a dedicated tool router. As MetaAgent solves tasks, it continually conducts self-reflection and answer verification, distilling actionable experience into concise texts that are dynamically incorporated into future task contexts. Besides, MetaAgent autonomously builds in-house tools and a persistent knowledge base by organizing its tool-use history, further enhancing its ability to retrieve and integrate relevant information We term this continual, data-driven process as \textit{meta tool learning}, through which MetaAgent incrementally refines its reasoning and tool-use strategies, without changing model parameters or requiring further post-training. Evaluated on challenging knowledge discovery benchmarks, including GAIA, WebWalkerQA, and BrowseCamp, MetaAgent consistently outperforms workflow-based baselines and matches or exceeds end-to-end trained agents, demonstrating the promise of self-evolving agentic systems for robust, general-purpose knowledge discovery. We provide our source codes in https://github.com/qhjqhj00/MetaAgent.

[Arxiv](https://arxiv.org/abs/2508.00271)