# 对话例程：任务型对话系统的提示工程框架

发布时间：2025年01月20日

`Agent

理由：这篇论文提出了一个基于大型语言模型（LLMs）的结构化提示工程框架，用于开发面向任务的对话系统。该框架通过自然语言规范开发对话代理系统（CAS），将任务逻辑嵌入LLM提示中，旨在设计和实现复杂对话工作流。这涉及到对话代理的设计和实现，属于Agent的范畴。` `对话系统` `业务流程自动化`

> Conversation Routines: A Prompt Engineering Framework for Task-Oriented Dialog Systems

# 摘要

> 本研究提出了对话例程（Conversation Routines, CR），这是一个基于大型语言模型（LLMs）的结构化提示工程框架，旨在开发面向任务的对话系统。尽管LLMs在自然语言理解方面表现出色，但如何可靠地执行复杂业务流程仍是一大挑战。CR框架通过自然语言规范开发对话代理系统（CAS），将任务逻辑嵌入LLM提示中，为设计和实现复杂对话工作流提供了系统化方法，同时确保行为一致性。我们通过两个概念验证展示了该框架的有效性：火车票预订系统和交互式故障排除助手。这些案例验证了CR在编码复杂行为模式和决策逻辑的同时，仍能保持对话的自然灵活性。结果表明，CR使领域专家能够用自然语言设计对话工作流，同时利用开发者构建的企业功能（工具），实现了开发者专注于API实现、领域专家负责对话设计的高效分工。尽管CR在可访问性和适应性上表现出色，但仍面临计算开销、非确定性行为和领域逻辑优化等挑战。未来研究将聚焦于增强系统鲁棒性、提升复杂多代理交互的可扩展性，并解决不同业务应用中的现有局限。

> This study introduces Conversation Routines (CR), a structured prompt engineering framework for developing task-oriented dialog systems using Large Language Models (LLMs). While LLMs demonstrate remarkable natural language understanding capabilities, engineering them to reliably execute complex business workflows remains challenging. The proposed CR framework enables the development of Conversation Agentic Systems (CAS) through natural language specifications, embedding task-oriented logic within LLM prompts. This approach provides a systematic methodology for designing and implementing complex conversational workflows while maintaining behavioral consistency. We demonstrate the framework's effectiveness through two proof of concept implementations: a Train Ticket Booking System and an Interactive Troubleshooting Copilot. These case studies validate CR's capability to encode sophisticated behavioral patterns and decision logic while preserving natural conversational flexibility. Results show that CR enables domain experts to design conversational workflows in natural language while leveraging custom enterprise functionalities (tools) developed by software engineers, creating an efficient division of responsibilities where developers focus on core API implementation and domain experts handle conversation design. While the framework shows promise in accessibility and adaptability, we identify key challenges including computational overhead, non-deterministic behavior, and domain-specific logic optimization. Future research directions include enhancing system robustness, improving scalability for complex multi-agent interactions, and addressing the identified limitations across diverse business applications.

[Arxiv](https://arxiv.org/abs/2501.11613)