# 基于LLM的协作模型，通过显式与隐式依赖推理实现提交拆解

发布时间：2025年07月22日

`LLM应用` `软件工程` `人工智能`

> LLM-Driven Collaborative Model for Untangling Commits via Explicit and Implicit Dependency Reasoning

# 摘要

> 原子提交是软件开发中的最佳实践，每个提交都专注于解决单一的开发问题。然而，开发人员在实际开发中常常因为各种限制或边界不清晰而生成混合了不相关更改的纠结提交，这对代码审查和维护造成了负面影响。尽管先前的提交解耦方法（基于规则、特征或图的方法）已经取得了一定进展，但它们通常依赖于浅层信号，无法区分显式依赖（例如控制流/数据流）和隐式依赖（例如语义或概念关系）。在本文中，我们提出了ColaUntangle，这是一种新的协作咨询框架，用于提交解耦，能够建模代码更改之间的显式和隐式依赖关系。ColaUntangle在多智能体架构中集成了大型语言模型（LLM）驱动的智能体：一个智能体专门处理显式依赖，另一个处理隐式依赖，还有一个审查者智能体通过迭代咨询综合他们的观点。为了捕获显式和隐式的上下文信息，我们构建了多版本程序依赖图（delta-PDG），使智能体能够从符号和语义深度两个方面推理代码关系。我们在两个广泛使用的数据集（1,612个C#和14k个Java纠结提交）上评估了ColaUntangle。实验结果表明，ColaUntangle优于最佳基线模型，在C#数据集上提升了44%，在Java数据集上提升了100%。这些发现凸显了基于LLM的协作框架在推进自动化提交解耦任务方面的潜力。

> Atomic commits, each of which addresses a single development concern, are a best practice in software development. However, developers frequently produce tangled commits that mix unrelated changes due to practical constraints or unclear boundaries, negatively impacting code review and maintenance. Although prior commit untangling approaches: rule-based, feature-based, or graph-based, have made progress, they often rely on shallow signals and fail to distinguish between explicit dependencies (e.g., control/data flow) and implicit ones (e.g., semantic or conceptual relationships). In this paper, we propose ColaUntangle, a new collaborative consultation framework for commit untangling that models both explicit and implicit dependencies among code changes. ColaUntangle integrates Large Language Model (LLM)-driven agents in a multi-agent architecture: one agent specializes in explicit dependencies, another in implicit ones, and a reviewer agent synthesizes their perspectives through iterative consultation. To capture explicit and implicit contextual information, we construct multi-version Program Dependency Graphs (delta-PDG), enabling agents to reason over code relationships with both symbolic and semantic depth. We evaluate ColaUntangle on two widely-used datasets (1,612 C# and 14k Java tangled commits). Experimental results show that ColaUntangle outperforms the best-performing baseline, achieving an improvement of 44% on the C# dataset and 100% on the Java dataset. These findings highlight the potential of LLM-based collaborative frameworks for advancing automated commit untangling tasks.

[Arxiv](https://arxiv.org/abs/2507.16395)