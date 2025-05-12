# AgentXploit：针对黑盒AI代理的端到端红队测试方法

发布时间：2025年05月09日

`Agent

论文摘要讨论了大型语言模型（LLMs）在基于代理的系统中的应用，特别是这些系统如何利用外部工具与复杂环境交互。然而，论文的重点在于这些系统面临的安全风险，即间接提示注入攻击。这种攻击方式不是通过直接修改用户提示，而是通过操纵上下文信息来破坏代理的核心LLM。

接下来，论文介绍了一种名为AgentXploit的通用黑盒模糊测试框架，用于自动发现和利用LLM代理中的间接提示注入漏洞。研究方法包括构建高质量的初始种子语料库，并使用基于蒙特卡洛树搜索（MCTS）的种子选择算法，迭代优化输入以提高发现代理弱点的可能性。实验结果表明，该框架在基准测试中表现出色，成功率高达70%，并且在现实环境中成功误导代理导航到恶意网站。

论文主要关注的是基于代理的系统中的安全问题，特别是如何通过间接提示注入攻击来破坏这些系统。虽然涉及LLM，但核心在于代理系统的安全性和漏洞利用，因此更偏向于Agent类别。论文的重点不是LLM的应用或理论，而是代理系统的安全性，因此不属于LLM应用或LLM理论。此外，它也没有涉及RAG（检索增强生成）的内容，因此排除RAG类别。综上所述，这篇论文应归类为Agent。` `智能系统`

> AgentXploit: End-to-End Redteaming of Black-Box AI Agents

# 摘要

> 大型语言模型（LLMs）的规划和推理能力推动了基于代理的系统发展，这些系统能够利用外部工具并与复杂环境交互。然而，这种强大的能力也带来了一个关键安全风险：间接提示注入。这种攻击通过操纵上下文信息而非直接用户提示，破坏代理的核心——LLM。本文提出了一种通用黑盒模糊测试框架AgentXploit，用于自动发现和利用各种LLM代理中的间接提示注入漏洞。我们的方法首先构建高质量初始种子语料库，然后采用基于蒙特卡洛树搜索（MCTS）的种子选择算法，迭代优化输入，以提高发现代理弱点的可能性。我们在AgentDojo和VWA-adv两个基准测试中评估AgentXploit，分别针对o3-mini和GPT-4o代理，成功率高达71%和70%，几乎将基线攻击性能提升了一倍。此外，AgentXploit在未见过的任务和内部LLM上表现出良好迁移能力，并对防御措施显示出有前景的结果。除了基准测试，我们还将攻击应用于现实环境，成功误导代理导航到任意URL，包括恶意网站。

> The strong planning and reasoning capabilities of Large Language Models (LLMs) have fostered the development of agent-based systems capable of leveraging external tools and interacting with increasingly complex environments. However, these powerful features also introduce a critical security risk: indirect prompt injection, a sophisticated attack vector that compromises the core of these agents, the LLM, by manipulating contextual information rather than direct user prompts. In this work, we propose a generic black-box fuzzing framework, AgentXploit, designed to automatically discover and exploit indirect prompt injection vulnerabilities across diverse LLM agents. Our approach starts by constructing a high-quality initial seed corpus, then employs a seed selection algorithm based on Monte Carlo Tree Search (MCTS) to iteratively refine inputs, thereby maximizing the likelihood of uncovering agent weaknesses. We evaluate AgentXploit on two public benchmarks, AgentDojo and VWA-adv, where it achieves 71% and 70% success rates against agents based on o3-mini and GPT-4o, respectively, nearly doubling the performance of baseline attacks. Moreover, AgentXploit exhibits strong transferability across unseen tasks and internal LLMs, as well as promising results against defenses. Beyond benchmark evaluations, we apply our attacks in real-world environments, successfully misleading agents to navigate to arbitrary URLs, including malicious sites.

[Arxiv](https://arxiv.org/abs/2505.05849)