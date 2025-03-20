# LogiAgent：基于LLM的多智能体REST系统自动化逻辑测试

发布时间：2025年03月19日

`LLM应用` `软件工程`

> LogiAgent: Automated Logical Testing for REST Systems with LLM-Based Multi-Agents

# 摘要

> REST API的自动化测试已成为确保现代Web服务正确性和可靠性的关键。现有方法虽然专注于检测服务器崩溃和错误代码，但往往忽视了因业务逻辑演变和领域特定需求而产生的逻辑问题。为此，我们提出了LogiAgent——一种基于大型语言模型（LLM）驱动的多代理框架的新型逻辑测试方法。LogiAgent通过整合测试场景生成器、API请求执行器和API响应验证器，实现了API测试场景的生成、执行和验证的协同工作。与传统方法专注于5xx等状态代码不同，LogiAgent引入了基于业务逻辑的逻辑断言，从而实现更全面的测试覆盖。此外，LogiAgent还配备了执行记忆组件，用于存储历史API执行数据，以确保上下文一致性。在12个真实世界的REST系统上的实验表明，LogiAgent能够有效识别234个逻辑问题，准确率达到66.19%。同时，它在检测服务器崩溃方面表现出色，并在测试覆盖率方面优于四种最先进的REST API测试工具。通过消融实验，我们证实了LogiAgent的记忆组件对提高测试覆盖率的显著贡献。

> Automated testing for REST APIs has become essential for ensuring the correctness and reliability of modern web services. While existing approaches primarily focus on detecting server crashes and error codes, they often overlook logical issues that arise due to evolving business logic and domain-specific requirements. To address this limitation, we propose LogiAgent, a novel approach for logical testing of REST systems. Built upon a large language model (LLM)-driven multi-agent framework, LogiAgent integrates a Test Scenario Generator, API Request Executor, and API Response Validator to collaboratively generate, execute, and validate API test scenarios. Unlike traditional testing methods that focus on status codes like 5xx, LogiAgent incorporates logical oracles that assess responses based on business logic, ensuring more comprehensive testing. The system is further enhanced by an Execution Memory component that stores historical API execution data for contextual consistency. We conduct extensive experiments across 12 real-world REST systems, demonstrating that LogiAgent effectively identifies 234 logical issues with an accuracy of 66.19%. Additionally, it basically excels in detecting server crashes and achieves superior test coverage compared to four state-of-the-art REST API testing tools. An ablation study confirms the significant contribution of LogiAgent's memory components to improving test coverage.

[Arxiv](https://arxiv.org/abs/2503.15079)