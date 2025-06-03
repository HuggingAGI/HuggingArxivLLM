# # 简单的提示注入攻击可能导致LLM代理在任务执行中泄露个人数据

发布时间：2025年06月01日

`Agent

摘要讨论了大语言模型（LLMs）中的提示注入攻击如何导致工具调用代理在任务执行过程中泄露个人数据。研究集中在智能体（Agent）的安全性，特别是在AgentDojo基准测试中的表现，分析了攻击对智能体效用和数据泄露的影响。因此，这篇论文属于Agent类别。` `人工智能安全`

> Simple Prompt Injection Attacks Can Leak Personal Data Observed by LLM Agents During Task Execution

# 摘要

> # 摘要
此前关于大语言模型（LLMs）中提示注入的研究主要集中在通用任务和攻击上，对数据外泄等更复杂威胁的探讨较为有限。本文研究了提示注入如何导致工具调用代理在任务执行过程中泄露个人数据。通过一个虚构的银行代理，我们在AgentDojo（近期推出的智能体安全基准测试）中开发并集成了基于数据流的攻击，并为此创建了一个更丰富的合成数据集，模拟人类与AI的银行对话。在AgentDojo的16个用户任务中，LLMs在攻击下的效用平均下降15-50个百分点，平均攻击成功率（ASR）约为20%；部分防御措施可将ASR降至零。多数LLMs即便被成功攻击，仍避免泄露高度敏感数据（如密码），这可能得益于安全对齐机制，但它们仍可能泄露其他个人信息。当攻击同时索要密码和一至两个额外个人信息时，密码泄露的可能性显著增加。在扩展至48个任务的评估中，平均ASR约为15%，且无内置防御机制能完全阻止数据泄露。涉及数据提取或授权流程的任务表现出最高ASR，这些任务结构与数据外泄攻击相似，凸显了任务类型、智能体性能与防御效果之间的交互作用。


> Previous benchmarks on prompt injection in large language models (LLMs) have primarily focused on generic tasks and attacks, offering limited insights into more complex threats like data exfiltration. This paper examines how prompt injection can cause tool-calling agents to leak personal data observed during task execution. Using a fictitious banking agent, we develop data flow-based attacks and integrate them into AgentDojo, a recent benchmark for agentic security. To enhance its scope, we also create a richer synthetic dataset of human-AI banking conversations. In 16 user tasks from AgentDojo, LLMs show a 15-50 percentage point drop in utility under attack, with average attack success rates (ASR) around 20 percent; some defenses reduce ASR to zero. Most LLMs, even when successfully tricked by the attack, avoid leaking highly sensitive data like passwords, likely due to safety alignments, but they remain vulnerable to disclosing other personal data. The likelihood of password leakage increases when a password is requested along with one or two additional personal details. In an extended evaluation across 48 tasks, the average ASR is around 15 percent, with no built-in AgentDojo defense fully preventing leakage. Tasks involving data extraction or authorization workflows, which closely resemble the structure of exfiltration attacks, exhibit the highest ASRs, highlighting the interaction between task type, agent performance, and defense efficacy.

[Arxiv](https://arxiv.org/abs/2506.01055)