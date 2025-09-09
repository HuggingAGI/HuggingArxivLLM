# Code2MCP：多智能体框架——代码仓库到模型上下文协议服务的自动化转换

发布时间：2025年09月07日

`Agent` `基础理论`

> Code2MCP: A Multi-Agent Framework for Automated Transformation of Code Repositories into Model Context Protocol Services

# 摘要

> 大型语言模型（LLMs）的迅猛发展，在AI智能体生态中引发了一大集成难题——“N×M问题”：N个模型需为M个工具分别开发定制化接口。这种碎片化不仅扼杀创新，还带来沉重的开发负担。模型上下文协议（MCP）虽已成为解决该问题的标准，但要将海量现有软件改造为MCP兼容服务需耗费大量人工，这严重阻碍了MCP的普及。尤其在GitHub这一全球最大的功能性代码库中，数百万开源项目的适配工作更是难上加难。

本文提出Code2MCP——一个高度自动化的智能体框架，能以最小人工介入将任意GitHub仓库转化为可用的MCP服务。该系统通过多阶段工作流实现全流程自动化：从代码解析、环境配置，到服务生成与部署一气呵成。其核心创新在于LLM驱动的“运行-审查-修复”闭环机制，让系统能自主调试并修复生成的代码。Code2MCP不仅产出可直接部署的服务，还会生成详尽的技术文档；它如同催化剂，通过系统性盘活全球最大开源代码库、自动化工具集成的“最后一公里”，加速MCP生态的发展。项目代码已开源：https://github.com/DEFENSE-SEU/MCP-Github-Agent。

> The proliferation of Large Language Models (LLMs) has created a significant integration challenge in the AI agent ecosystem, often called the "$N \times M$ problem," where N models require custom integrations for M tools. This fragmentation stifles innovation and creates substantial development overhead. While the Model Context Protocol (MCP) has emerged as a standard to resolve this, its adoption is hindered by the manual effort required to convert the vast universe of existing software into MCP-compliant services. This is especially true for the millions of open-source repositories on GitHub, the world's largest collection of functional code. This paper introduces Code2MCP, a highly automated, agentic framework designed to transform any GitHub repository into a functional MCP service with minimal human intervention. Our system employs a multi-stage workflow that automates the entire process, from code analysis and environment configuration to service generation and deployment. A key innovation of our framework is an LLM-driven, closed-loop "Run--Review--Fix" cycle, which enables the system to autonomously debug and repair the code it generates. Code2MCP produces not only deployable services but also comprehensive technical documentation, acting as a catalyst to accelerate the MCP ecosystem by systematically unlocking the world's largest open-source code repository and automating the critical last mile of tool integration. The code is open-sourced at https://github.com/DEFENSE-SEU/MCP-Github-Agent.

[Arxiv](https://arxiv.org/abs/2509.05941)