# # 多智能体系统中的完整性攻击实例

发布时间：2025年06月04日

`Agent

摘要讨论了多智能体系统（MAS）中的攻击问题，特别是恶意智能体如何通过提示操作影响系统，属于智能体安全性的研究。` `人工智能` `网络安全`

> Demonstrations of Integrity Attacks in Multi-Agent Systems

# 摘要

> 大型语言模型（LLMs）在自然语言理解、代码生成和复杂规划领域表现卓越。与此同时，多智能体系统（MAS）因其促进分布式智能体协作的潜力而备受关注。然而，从多方视角来看，MAS可能易受恶意智能体的攻击，这些恶意智能体会利用系统以实现自身利益，同时不破坏其核心功能。本研究探讨了完整性攻击，其中恶意智能体通过微妙的提示操作来偏颇MAS的运行并获得各种利益。我们考察了四种类型的攻击：	extit{Scapegoater}，误导系统监视器低估其他智能体的贡献；	extit{Boaster}，误导系统监视器高估自身表现；	extit{Self-Dealer}，操纵其他智能体采用特定工具；以及	extit{Free-Rider}，将自身任务转嫁给他人。我们证明，精心设计的提示可以引入MAS行为和可执行指令中的系统性偏见，使恶意智能体能够有效误导评估系统并操控协作智能体。此外，我们的攻击能够绕过基于先进LLMs的监视器，如GPT-4o-mini和o3-mini，凸显了当前检测机制的局限性。我们的研究发现强调了构建具备强健安全协议和内容验证机制的MAS架构，以及能够全面评估风险场景的监视系统的紧迫需求。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in natural language understanding, code generation, and complex planning. Simultaneously, Multi-Agent Systems (MAS) have garnered attention for their potential to enable cooperation among distributed agents. However, from a multi-party perspective, MAS could be vulnerable to malicious agents that exploit the system to serve self-interests without disrupting its core functionality. This work explores integrity attacks where malicious agents employ subtle prompt manipulation to bias MAS operations and gain various benefits. Four types of attacks are examined: \textit{Scapegoater}, who misleads the system monitor to underestimate other agents' contributions; \textit{Boaster}, who misleads the system monitor to overestimate their own performance; \textit{Self-Dealer}, who manipulates other agents to adopt certain tools; and \textit{Free-Rider}, who hands off its own task to others. We demonstrate that strategically crafted prompts can introduce systematic biases in MAS behavior and executable instructions, enabling malicious agents to effectively mislead evaluation systems and manipulate collaborative agents. Furthermore, our attacks can bypass advanced LLM-based monitors, such as GPT-4o-mini and o3-mini, highlighting the limitations of current detection mechanisms. Our findings underscore the critical need for MAS architectures with robust security protocols and content validation mechanisms, alongside monitoring systems capable of comprehensive risk scenario assessment.

[Arxiv](https://arxiv.org/abs/2506.04572)