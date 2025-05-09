# 开发保障：一种提升隐私的多智能体协作系统开发范式

发布时间：2025年05月07日

`Agent` `供应链优化`

> Safeguard-by-Development: A Privacy-Enhanced Development Paradigm for Multi-Agent Collaboration Systems

# 摘要

> 多智能体协作系统（MACS）借助大型语言模型（LLMs），通过智能体的专业化能力和高效协作解决复杂问题。然而，智能体间的信息交互及其与外部环境的互动，如LLM、工具和用户，不可避免地带来敏感数据泄露风险，包括易受注入攻击和侦察攻击等威胁。现有的MACS缺乏隐私控制机制，难以安全地管理敏感信息。本文提出增强隐私的开发范式Maris，从系统开发层面应对MACS的数据泄露威胁。Maris通过在关键的多智能体对话组件中嵌入参考监控器，实现对MACS内部消息流的严格控制。我们已将Maris作为开源多智能体开发框架AutoGen的核心部分实现。随后，我们在医疗、供应链优化和个性化推荐系统的隐私关键MACS用例中评估Maris的效果和性能。结果显示，Maris在效能、性能和实用性方面均表现出令人满意的水平，具备实际应用价值。

> Multi-agent collaboration systems (MACS), powered by large language models (LLMs), solve complex problems efficiently by leveraging each agent's specialization and communication between agents. However, the inherent exchange of information between agents and their interaction with external environments, such as LLM, tools, and users, inevitably introduces significant risks of sensitive data leakage, including vulnerabilities to attacks like prompt injection and reconnaissance. Existing MACS fail to enable privacy controls, making it challenging to manage sensitive information securely. In this paper, we take the first step to address the MACS's data leakage threat at the system development level through a privacy-enhanced development paradigm, Maris. Maris enables rigorous message flow control within MACS by embedding reference monitors into key multi-agent conversation components. We implemented Maris as an integral part of AutoGen, a widely adopted open-source multi-agent development framework. Then, we evaluate Maris for its effectiveness and performance overhead on privacy-critical MACS use cases, including healthcare, supply chain optimization, and personalized recommendation system. The result shows that Maris achieves satisfactory effectiveness, performance overhead and practicability for adoption.

[Arxiv](https://arxiv.org/abs/2505.04799)