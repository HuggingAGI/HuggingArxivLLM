# 诱骗元数据攻击：诱导 LLM 智能体调用恶意工具

发布时间：2025年08月04日

`Agent` `网络安全` `人工智能`

> Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools

# 摘要

> 大型语言模型（LLM）代理在利用外部工具进行复杂推理和决策时表现卓越。然而，这种以工具为中心的范式引入了一个新的、隐蔽的威胁面：攻击者可操纵工具元数据（如名称、描述和参数架构）来影响代理行为。我们发现，恶意工具可被LLM代理优先选择，且无需提示注入或访问模型内部。为验证并利用这一漏洞，我们提出了有吸引力的元数据攻击（AMA），这是一种黑盒上下文学习框架，通过迭代优化生成高度吸引人但语法和语义上有效的工具元数据。该攻击无缝集成到标准工具生态系统中，无需修改代理执行框架。在十个现实的模拟工具使用场景和一系列流行LLM代理上的实验显示，攻击成功率高达81%-95%，且对主要任务执行影响微乎其微，同时导致严重隐私泄露。即使在提示级别防御和结构化工具选择协议（如模型上下文协议）下，攻击仍有效，揭示了当前代理架构中的系统性漏洞。这些发现表明，元数据操纵构成了一种强大且隐蔽的攻击面，凸显了需要超越提示级别防御的执行级别安全机制的重要性。


> Large language model (LLM) agents have demonstrated remarkable capabilities in complex reasoning and decision-making by leveraging external tools. However, this tool-centric paradigm introduces a previously underexplored attack surface: adversaries can manipulate tool metadata -- such as names, descriptions, and parameter schemas -- to influence agent behavior. We identify this as a new and stealthy threat surface that allows malicious tools to be preferentially selected by LLM agents, without requiring prompt injection or access to model internals. To demonstrate and exploit this vulnerability, we propose the Attractive Metadata Attack (AMA), a black-box in-context learning framework that generates highly attractive but syntactically and semantically valid tool metadata through iterative optimization. Our attack integrates seamlessly into standard tool ecosystems and requires no modification to the agent's execution framework. Extensive experiments across ten realistic, simulated tool-use scenarios and a range of popular LLM agents demonstrate consistently high attack success rates (81\%-95\%) and significant privacy leakage, with negligible impact on primary task execution. Moreover, the attack remains effective even under prompt-level defenses and structured tool-selection protocols such as the Model Context Protocol, revealing systemic vulnerabilities in current agent architectures. These findings reveal that metadata manipulation constitutes a potent and stealthy attack surface, highlighting the need for execution-level security mechanisms that go beyond prompt-level defenses.

[Arxiv](https://arxiv.org/abs/2508.02110)