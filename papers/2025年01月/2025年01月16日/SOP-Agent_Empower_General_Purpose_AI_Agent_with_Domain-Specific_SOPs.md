# SOP-Agent：用领域专属SOPs武装通用AI代理

发布时间：2025年01月16日

`Agent

理由：这篇论文主要讨论了一种基于自然语言编写的伪代码风格标准操作程序（SOPs）的领域特定智能体框架——SOP-agent。该框架通过遍历决策图来指导智能体完成任务，并在多个领域进行了实验。论文的核心内容围绕智能体的设计和应用展开，因此应归类为Agent。` `客户服务` `智能体`

> SOP-Agent: Empower General Purpose AI Agent with Domain-Specific SOPs

# 摘要

> 尽管通用AI智能体取得了显著进展，但在实际应用中仍面临挑战。首先，LLM的规划能力有限，难以应对需要长期规划的复杂任务。其次，通用AI智能体难以高效利用领域知识和人类经验。本文提出了一种基于自然语言编写的伪代码风格标准操作程序（SOPs）的领域特定智能体框架——SOP-agent。我们将SOP表示为决策图，通过遍历该图指导智能体完成任务。我们在多个领域（如决策制定、搜索推理、代码生成、数据清洗和客户服务）进行了广泛实验。SOP-agent展现了卓越的通用性，性能优于通用智能体框架，并与领域特定系统相当。此外，我们推出了首个基于SOPs的客户服务场景决策能力评估基准——Grounded Customer Service Benchmark。

> Despite significant advancements in general-purpose AI agents, several challenges still hinder their practical application in real-world scenarios. First, the limited planning capabilities of Large Language Models (LLM) restrict AI agents from effectively solving complex tasks that require long-horizon planning. Second, general-purpose AI agents struggle to efficiently utilize domain-specific knowledge and human expertise. In this paper, we introduce the Standard Operational Procedure-guided Agent (SOP-agent), a novel framework for constructing domain-specific agents through pseudocode-style Standard Operational Procedures (SOPs) written in natural language. Formally, we represent a SOP as a decision graph, which is traversed to guide the agent in completing tasks specified by the SOP. We conduct extensive experiments across tasks in multiple domains, including decision-making, search and reasoning, code generation, data cleaning, and grounded customer service. The SOP-agent demonstrates excellent versatility, achieving performance superior to general-purpose agent frameworks and comparable to domain-specific agent systems. Additionally, we introduce the Grounded Customer Service Benchmark, the first benchmark designed to evaluate the grounded decision-making capabilities of AI agents in customer service scenarios based on SOPs.

[Arxiv](https://arxiv.org/abs/2501.09316)