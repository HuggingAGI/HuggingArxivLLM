# AgentBreeder：缓解多智能体框架对AI安全的潜在风险

发布时间：2025年02月02日

`Agent

理由：这篇论文主要讨论了将LLMs（大型语言模型）融入多智能体系统，并提出了AGENTBREEDER框架来优化多智能体系统的性能和安全。论文的核心内容围绕多智能体系统的设计和优化，特别是通过进化嵌入来提升任务成功率和安全性。因此，这篇论文应归类为Agent。` `人工智能` `多智能体系统`

> AgentBreeder: Mitigating the AI Safety Impact of Multi-Agent Scaffolds

# 摘要

> 将LLMs融入多智能体系统通常能提升复杂任务的性能，但其安全影响尚未被充分研究。本文提出AGENTBREEDER框架，用于多目标进化搜索嵌入。REDAGENTBREEDER通过进化嵌入突破基础LLM的限制，同时保持高任务成功率；BLUEAGENTBREEDER则追求安全性与任务奖励的平衡。我们通过推理、数学和安全基准评估了AGENTBREEDER实例发现的系统及基线方法，揭示并缓解了多智能体嵌入的安全风险。

> Scaffolding Large Language Models (LLMs) into multi-agent systems often improves performance on complex tasks, but the safety impact of such scaffolds has not been as thoroughly explored. In this paper, we introduce AGENTBREEDER a framework for multi-objective evolutionary search over scaffolds. Our REDAGENTBREEDER evolves scaffolds towards jailbreaking the base LLM while achieving high task success, while BLUEAGENTBREEDER instead aims to combine safety with task reward. We evaluate the systems discovered by the different instances of AGENTBREEDER and popular baselines using widely recognized reasoning, mathematics, and safety benchmarks. Our work highlights and mitigates the safety risks due to multi-agent scaffolding.

[Arxiv](https://arxiv.org/abs/2502.00757)