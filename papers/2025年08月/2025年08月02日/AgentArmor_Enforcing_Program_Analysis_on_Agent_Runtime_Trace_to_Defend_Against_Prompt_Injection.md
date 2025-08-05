# AgentArmor：通过分析代理运行时轨迹强制执行程序分析，防御提示注入攻击

发布时间：2025年08月02日

`Agent` `人工智能安全` `程序分析`

> AgentArmor: Enforcing Program Analysis on Agent Runtime Trace to Defend Against Prompt Injection

# 摘要

> 大型语言模型（LLM）代理通过结合自然语言推理与外部工具执行，为解决各种问题提供了强大新范式。然而，其动态且不透明的行为带来了关键安全风险，尤其在提示注入攻击面前。我们提出了一种新颖见解，将代理运行时跟踪视为具有可分析语义的结构化程序。由此，我们推出了AgentArmor——一个程序分析框架，它将代理跟踪转换为基于图的中间表示的结构化程序依赖表示（如CFG、DFG和PDG），并通过类型系统强制执行安全策略。AgentArmor包含三个关键组件：(1) 图构造器，将代理工作跟踪重建为基于图的中间表示，完整描述控制流和数据流；(2) 属性注册表，记录交互工具与数据的安全相关元数据；(3) 类型系统，在中间表示上执行静态推断与检查。通过将代理行为结构化，AgentArmor实现了对敏感数据流、信任边界和策略违规的程序分析。我们在AgentDojo基准测试中，AgentArmor达到95.75%的TPR，仅3.66%的FPR。这证明了AgentArmor在检测提示注入漏洞和执行细粒度安全约束方面的强大能力。

> Large Language Model (LLM) agents offer a powerful new paradigm for solving various problems by combining natural language reasoning with the execution of external tools. However, their dynamic and non-transparent behavior introduces critical security risks, particularly in the presence of prompt injection attacks. In this work, we propose a novel insight that treats the agent runtime traces as structured programs with analyzable semantics. Thus, we present AgentArmor, a program analysis framework that converts agent traces into graph intermediate representation-based structured program dependency representations (e.g., CFG, DFG, and PDG) and enforces security policies via a type system. AgentArmor consists of three key components: (1) a graph constructor that reconstructs the agent's working traces as graph-based intermediate representations with control flow and data flow described within; (2) a property registry that attaches security-relevant metadata of interacted tools & data, and (3) a type system that performs static inference and checking over the intermediate representation. By representing agent behavior as structured programs, AgentArmor enables program analysis over sensitive data flow, trust boundaries, and policy violations. We evaluate AgentArmor on the AgentDojo benchmark, the results show that AgentArmor can achieve 95.75% of TPR, with only 3.66% of FPR. Our results demonstrate AgentArmor's ability to detect prompt injection vulnerabilities and enforce fine-grained security constraints.

[Arxiv](https://arxiv.org/abs/2508.01249)