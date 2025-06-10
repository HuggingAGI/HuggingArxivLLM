# MCPWorld: 一个支持 API、GUI 以及混合型计算机使用代理的统一基准测试平台

发布时间：2025年06月09日

`Agent` `软件工程` `自动化测试`

> MCPWorld: A Unified Benchmarking Testbed for API, GUI, and Hybrid Computer Use Agents

# 摘要

> (M)LLM驱动的计算机使用代理（CUA）正在成为自动化人机交互的革命性技术。然而，现有的CUA基准主要集中在GUI代理上，其评估方法易受UI变化影响，且忽略了应用程序API公开的功能交互，例如模型上下文协议（MCP）。为此，我们推出了MCPWorld——首个针对API、GUI及混合接口代理的自动CUA测试平台。MCPWorld的核心理念是采用‘白盒应用’，即具备开放源代码且可根据需求进行修改或重新编译的应用程序（如支持MCP），这带来了两大显著优势：首先，它极大地拓展了CUA的设计空间，涵盖功能公开方式及API调用机制；其次，通过动态代码插桩等技术，MCPWorld可直接监控应用行为，实现任务完成的程序化验证，从而提供独立于特定代理实现或UI状态的精准评估。目前，MCPWorld拥有201个精心设计和标注的用户任务，覆盖多种使用场景和难度级别。此外，MCPWorld实现了容器化部署，并支持GPU加速，确保在不同操作系统和硬件环境下的灵活应用。我们的初步实验采用了一款代表性的LLM驱动CUA框架，取得了75.12%的任务完成准确率，同时验证了基于MCP的代理自动化在实际应用中的有效性。我们期待MCPWorld能够推动下一代计算机使用代理的标准化评估，助力其充分发挥外部工具潜力。相关代码和数据集已开源，详情请访问https://github.com/SAAgent/MCPWorld。

> (M)LLM-powered computer use agents (CUA) are emerging as a transformative technique to automate human-computer interaction. However, existing CUA benchmarks predominantly target GUI agents, whose evaluation methods are susceptible to UI changes and ignore function interactions exposed by application APIs, e.g., Model Context Protocol (MCP). To this end, we propose MCPWorld, the first automatic CUA testbed for API, GUI, and API-GUI hybrid agents. A key principle of MCPWorld is the use of "white-box apps", i.e., those with source code availability and can be revised/re-compiled as needed (e.g., adding MCP support), with two notable advantages:
  (1) It greatly broadens the design space of CUA, such as what and how the app features to be exposed/extracted as CUA-callable APIs.
  (2) It allows MCPWorld to programmatically verify task completion by directly monitoring application behavior through techniques like dynamic code instrumentation, offering robust, accurate CUA evaluation decoupled from specific agent implementations or UI states.
  Currently, MCPWorld includes 201 well curated and annotated user tasks, covering diversified use cases and difficulty levels. MCPWorld is also fully containerized with GPU acceleration support for flexible adoption on different OS/hardware environments. Our preliminary experiments, using a representative LLM-powered CUA framework, achieve 75.12% task completion accuracy, simultaneously providing initial evidence on the practical effectiveness of agent automation leveraging MCP. Overall, we anticipate MCPWorld to facilitate and standardize the benchmarking of next-generation computer use agents that can leverage rich external tools. Our code and dataset are publicly available at https://github.com/SAAgent/MCPWorld.

[Arxiv](https://arxiv.org/abs/2506.07672)