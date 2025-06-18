# 统一软件工程代理，打造AI软件工程师

发布时间：2025年06月17日

`Agent` `软件工程`

> Unified Software Engineering agent as AI Software Engineer

# 摘要

> 大型语言模型（LLM）技术的快速发展让人们对自动化编码充满期待。然而，软件工程远不止编码，还包括项目维护与演进等活动。在此背景下，LLM代理的概念逐渐兴起，它们利用LLMs作为推理引擎，自主调用外部工具。但LLM代理是否等同于AI软件工程师呢？本文旨在通过开发一个统一的软件工程代理——USEagent，来探讨这一问题。与现有专注于特定任务（如测试、调试和修复）的专用代理不同，我们的目标是构建一个能够协调并处理多种能力的统一代理。这使得代理有望应对软件开发中的复杂场景，例如修复不完整的补丁、添加新功能或接管他人编写的代码。我们设想USEagent是未来AI软件工程师的第一个版本，未来它可能成为包含AI和人类成员的软件开发团队的一员。为了评估USEagent的效果，我们构建了统一软件工程基准测试（USEbench），包含编码、测试和补丁修复等众多任务。USEbench是从现有基准测试（如SWE-bench、SWT-bench和REPOCOD）中精选任务的合理组合。在包含1,271个仓库级别的软件工程任务的USEbench评估中，USEagent相较于现有的通用代理（如OpenHands CodeActAgent）表现出更优的效能。然而，USEagent在某些编码任务上的能力仍存在差距，这为未来开发更强大的AI软件工程师提供了方向。

> The growth of Large Language Model (LLM) technology has raised expectations for automated coding. However, software engineering is more than coding and is concerned with activities including maintenance and evolution of a project. In this context, the concept of LLM agents has gained traction, which utilize LLMs as reasoning engines to invoke external tools autonomously. But is an LLM agent the same as an AI software engineer? In this paper, we seek to understand this question by developing a Unified Software Engineering agent or USEagent. Unlike existing work which builds specialized agents for specific software tasks such as testing, debugging, and repair, our goal is to build a unified agent which can orchestrate and handle multiple capabilities. This gives the agent the promise of handling complex scenarios in software development such as fixing an incomplete patch, adding new features, or taking over code written by others. We envision USEagent as the first draft of a future AI Software Engineer which can be a team member in future software development teams involving both AI and humans. To evaluate the efficacy of USEagent, we build a Unified Software Engineering bench (USEbench) comprising of myriad tasks such as coding, testing, and patching. USEbench is a judicious mixture of tasks from existing benchmarks such as SWE-bench, SWT-bench, and REPOCOD. In an evaluation on USEbench consisting of 1,271 repository-level software engineering tasks, USEagent shows improved efficacy compared to existing general agents such as OpenHands CodeActAgent. There exist gaps in the capabilities of USEagent for certain coding tasks, which provides hints on further developing the AI Software Engineer of the future.

[Arxiv](https://arxiv.org/abs/2506.14683)