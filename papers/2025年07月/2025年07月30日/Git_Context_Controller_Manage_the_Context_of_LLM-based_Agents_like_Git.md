# Git风格的上下文管理器：像Git一样管控LLM代理

发布时间：2025年07月30日

`Agent` `软件开发` `软件工程`

> Git Context Controller: Manage the Context of LLM-based Agents like Git

# 摘要

> 基于大型语言模型（LLM）的代理通过将内部推理与外部工具使用相结合，展现出了令人印象深刻的的能力。然而，当这些代理被部署到长期任务的工作流程中，例如为大型长期项目编写代码时，上下文管理成为了关键瓶颈。我们引入了Git-Context-Controller（GCC），一个受到软件版本控制系统启发的结构化上下文管理框架。GCC将上下文管理提升为像Git一样的版本化记忆层级，将代理记忆结构化为一个带有明确操作的持久文件系统：COMMIT、BRANCH、MERGE 和 CONTEXT。这使得代理能够实现基于里程碑的检查点、对替代计划的探索以及结构化的反思。我们的方法赋予了代理管理长期目标、隔离架构实验以及在不同会话和代理之间恢复或移交记忆的能力。实证结果显示，配备GCC的代理在SWE-Bench-Lite基准测试中达到了最先进的性能，解决了48.00个软件错误，超过了26个竞争系统。在一个自我复制案例研究中，一个增强GCC的代理从零开始构建了一个新的CLI代理，实现了40.7的任务解决率，而没有GCC的情况下仅为11.7。代码已发布在：https://github.com/theworldofagents/GCC

> Large language model (LLM) based agents have shown impressive capabilities by interleaving internal reasoning with external tool use. However, as these agents are deployed in long-horizon workflows, such as coding for a big, long-term project, context management becomes a critical bottleneck. We introduce Git-Context-Controller (GCC), a structured context management framework inspired by software version control systems. GCC elevates context as versioned memory hierarchy like Git. It structures agent memory as a persistent file system with explicit operations: COMMIT, BRANCH, MERGE, and CONTEXT, enabling milestone-based checkpointing, exploration of alternative plans, and structured reflection. Our approach empowers agents to manage long-term goals, isolate architectural experiments, and recover or hand off memory across sessions and agents. Empirically, agents equipped with GCC achieve state-of-the-art performance on the SWE-Bench-Lite benchmark, resolving 48.00 of software bugs, outperforming 26 competitive systems. In a self-replication case study, a GCC-augmented agent builds a new CLI agent from scratch, achieving 40.7 task resolution, compared to only 11.7 without GCC. The code is released at: https://github.com/theworldofagents/GCC

[Arxiv](https://arxiv.org/abs/2508.00031)