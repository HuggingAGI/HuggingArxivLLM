# CoP：基于原则组合的大型语言模型智能体红队测试方法（CoP）

发布时间：2025年05月31日

`LLM应用` `AI安全` `红队测试`

> CoP: Agentic Red-teaming for Large Language Models using Composition of Principles

# 摘要

> 大型语言模型（LLMs）的最新进展在从开源到专有模型的各个领域催生了众多变革性应用。然而，旨在通过欺骗目标LLMs生成有害和高风险回答来破坏安全对齐和用户合规性的越狱攻击，正成为一个亟待解决的问题。对LLMs的红队测试实践旨在在前沿AI技术发布前主动探索潜在风险和易出错的实例。本文提出了一种基于原则组合（CoP）框架的代理工作流，通过人类用户提供的红队测试原则作为指令，由AI代理自动编排有效的红队测试策略并生成越狱提示。与现有方法不同，我们的CoP框架提供了一个统一且可扩展的框架，能够整合和编排人类提供的红队测试原则，从而实现新红队测试策略的自动化发现。在针对领先LLMs的测试中，CoP通过发现新型越狱提示，揭示了前所未有的安全风险，并将最佳已知单轮攻击的成功率提高了高达19.0倍。

> Recent advances in Large Language Models (LLMs) have spurred transformative applications in various domains, ranging from open-source to proprietary LLMs. However, jailbreak attacks, which aim to break safety alignment and user compliance by tricking the target LLMs into answering harmful and risky responses, are becoming an urgent concern. The practice of red-teaming for LLMs is to proactively explore potential risks and error-prone instances before the release of frontier AI technology. This paper proposes an agentic workflow to automate and scale the red-teaming process of LLMs through the Composition-of-Principles (CoP) framework, where human users provide a set of red-teaming principles as instructions to an AI agent to automatically orchestrate effective red-teaming strategies and generate jailbreak prompts. Distinct from existing red-teaming methods, our CoP framework provides a unified and extensible framework to encompass and orchestrate human-provided red-teaming principles to enable the automated discovery of new red-teaming strategies. When tested against leading LLMs, CoP reveals unprecedented safety risks by finding novel jailbreak prompts and improving the best-known single-turn attack success rate by up to 19.0 times.

[Arxiv](https://arxiv.org/abs/2506.00781)