# MCP-RADAR: 一个评估大型语言模型工具使用能力的多维度基准测试工具

发布时间：2025年05月22日

`Agent` `软件工程` `工具集成`

> MCP-RADAR: A Multi-Dimensional Benchmark for Evaluating Tool Use Capabilities in Large Language Models

# 摘要

> 大型语言模型（LLMs）正从被动的文本生成器演变为能够与工具交互的主动推理代理。在此背景下，模型上下文协议（MCP）作为一种标准化框架应运而生，用于工具的动态发现与编排。尽管MCP在行业中得到了广泛应用，但现有的评估方法未能充分评估在这一新范式下工具利用的能力。本文介绍了MCP-RADAR，这是首个专门设计用于在MCP框架下评估LLMs性能的全面基准测试。通过创新的五维度评估方法，MCP-RADAR衡量了：答案准确性、工具选择效率、计算资源效率、参数构建准确性和执行速度。与传统的依赖人工主观评估或二元成功指标的基准测试不同，MCP-RADAR采用了多任务领域的客观量化测量方法，涵盖软件工程、数学推理和通用问题解决等领域。我们对领先商业和开源LLMs的评估揭示了其能力概况中的显著权衡，涉及准确性、效率和速度，这挑战了传统的单一指标性能排名。此外，我们为开发者提供了宝贵指导，帮助他们优化工具以实现最大模型兼容性和有效性。尽管我们专注于MCP，因其标准化方法，我们的方法论仍适用于所有LLM代理工具集成框架，为LLM开发者和工具创建者提供了优化整个LLM-工具交互生态系统的宝贵见解。我们的评估所使用的实现、配置和数据集均可在https://anonymous.4open.science/r/MCPRadar-B143公开获取。

> As Large Language Models (LLMs) evolve from passive text generators to active reasoning agents capable of tool interaction, the Model Context Protocol (MCP) has emerged as a standardized framework for dynamic tool discovery and orchestration. Despite widespread industry adoption, existing evaluation methodologies fail to adequately assess tool utilization capabilities within this new paradigm. This paper introduces MCP-RADAR, the first comprehensive benchmark specifically designed to evaluate LLM performance in the MCP framework through a novel five-dimensional approach measuring: answer accuracy, tool selection efficiency, computational resource efficiency, parameter construction accuracy, and execution speed. Unlike conventional benchmarks that rely on subjective human evaluations or binary success metrics, MCP-RADAR employs objective, quantifiable measurements across multiple task domains including software engineering, mathematical reasoning, and general problem-solving. Our evaluations of leading commercial and open-source LLMs reveal distinctive capability profiles with significant trade-offs between accuracy, efficiency, and speed, challenging traditional single-metric performance rankings. Besides, we provide valuable guidance for developers to optimize their tools for maximum model compatibility and effectiveness. While focused on MCP due to its standardized approach, our methodology remains applicable across all LLM agent tool integration frameworks, providing valuable insights for both LLM developers and tool creators to optimize the entire LLM-tool interaction ecosystem. The implementation, configurations, and datasets used in our evaluation are publicly available at https://anonymous.4open.science/r/MCPRadar-B143.

[Arxiv](https://arxiv.org/abs/2505.16700)