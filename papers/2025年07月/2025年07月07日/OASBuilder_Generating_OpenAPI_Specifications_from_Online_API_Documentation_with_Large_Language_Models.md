# OASBuilder：利用大型语言模型从在线 API 文档生成 OpenAPI 规范

发布时间：2025年07月07日

`LLM应用

论文摘要：AI代理和企业自动化工具与外部网络服务交互时，需要以API规范形式获取标准化、机器可读的API相关信息。然而，网上的API信息通常以无结构的自由格式HTML文档呈现，导致用户需花费大量时间手动转换为结构化格式。为解决这一问题，我们引入了OASBuilder，一个能将冗长多样化的API文档转化为一致且机器可读规范的框架。通过整合大型语言模型和基于规则算法，并结合文档网页结构的领域知识，我们实现了这一目标。实验表明，OASBuilder在数百个API上表现优异，生成有效的OpenAPI规范，涵盖原始文档大部分信息。OASBuilder已在企业环境中成功应用，节省数千小时人工 effort，并使数百个复杂企业API成为LLM工具。

LLM应用` `软件工程` `企业自动化`

> OASBuilder: Generating OpenAPI Specifications from Online API Documentation with Large Language Models

# 摘要

> AI代理和企业自动化工具与外部网络服务交互时，需要以API规范形式获取标准化、机器可读的API相关信息。然而，网上的API信息通常以无结构的自由格式HTML文档呈现，导致用户需花费大量时间手动转换为结构化格式。为解决这一问题，我们引入了OASBuilder，一个能将冗长多样化的API文档转化为一致且机器可读规范的框架。通过整合大型语言模型和基于规则算法，并结合文档网页结构的领域知识，我们实现了这一目标。实验表明，OASBuilder在数百个API上表现优异，生成有效的OpenAPI规范，涵盖原始文档大部分信息。OASBuilder已在企业环境中成功应用，节省数千小时人工 effort，并使数百个复杂企业API成为LLM工具。

> AI agents and business automation tools interacting with external web services require standardized, machine-readable information about their APIs in the form of API specifications. However, the information about APIs available online is often presented as unstructured, free-form HTML documentation, requiring external users to spend significant time manually converting it into a structured format. To address this, we introduce OASBuilder, a novel framework that transforms long and diverse API documentation pages into consistent, machine-readable API specifications. This is achieved through a carefully crafted pipeline that integrates large language models and rule-based algorithms which are guided by domain knowledge of the structure of documentation webpages. Our experiments demonstrate that OASBuilder generalizes well across hundreds of APIs, and produces valid OpenAPI specifications that encapsulate most of the information from the original documentation. OASBuilder has been successfully implemented in an enterprise environment, saving thousands of hours of manual effort and making hundreds of complex enterprise APIs accessible as tools for LLMs.

[Arxiv](https://arxiv.org/abs/2507.05316)