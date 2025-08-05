# LiveMCPBench：智能体能否在浩瀚的 MCP 工具海洋中成功导航？

发布时间：2025年08月03日

`LLM应用` `自动化` `代理评估`

> LiveMCPBench: Can Agents Navigate an Ocean of MCP Tools?

# 摘要

> 模型上下文协议（MCP）的快速发展使得MCP服务器数量突破10,000个。然而，现有的MCP基准测试仅限于工具种类有限的单服务器环境，难以有效评估大规模真实场景中的代理能力。为了解决这一问题，我们推出了LiveMCPBench，这是首个全面的基准测试，包含95个基于MCP生态系统的实际任务，旨在大规模跨不同服务器评估LLM代理的能力。

为了支持在大规模MCP环境中实现可扩展且可重复的评估流程，我们整理了LiveMCPTool，这是一个多样且易于部署的工具集合，包含70个MCP服务器和527个工具。此外，我们引入了LiveMCPEval，这是一个基于LLM的评估框架，能够在动态且时间变化的任务环境中实现自动化和自适应评估，与人工评审者的意见一致率达到81%。最后，我们提出了MCP Copilot Agent，一个多步骤代理，能够在整个LiveMCPTool套件中动态规划并执行工具，以实现API交互。

我们的评估涵盖了10个领先的模型，其中表现最佳的模型（Claude-Sonnet-4）达到了78.95%的成功率。然而，我们观察到不同模型之间的性能存在显著差异，且一些广泛使用的模型在LiveMCPBench的复杂、工具丰富的环境中表现不佳。总体而言，LiveMCPBench为在现实、工具丰富且动态变化的MCP环境中评估LLM代理提供了一个首个统一的框架，为代理能力的可扩展和可重复研究奠定了坚实的基础。我们的代码和数据将在https://icip-cas.github.io/LiveMCPBench公开发布。

> With the rapid development of Model Context Protocol (MCP), the number of MCP servers has surpassed 10,000. However, existing MCP benchmarks are limited to single-server settings with only a few tools, hindering effective evaluation of agent capabilities in large-scale, real-world scenarios. To address this limitation, we present LiveMCPBench, the first comprehensive benchmark comprising 95 real-world tasks grounded in the MCP ecosystem, designed to evaluate LLM agents at scale across diverse servers. To support a scalable and reproducible evaluation pipeline in large-scale MCP environments, we curate LiveMCPTool, a diverse and readily deployable collection of 70 MCP servers and 527 tools. Furthermore, we introduce LiveMCPEval, an LLM-as-a-Judge framework that enables automated and adaptive evaluation in dynamic, time-varying task environments, achieving 81% agreement with human reviewers. Finally, we propose the MCP Copilot Agent, a multi-step agent that routes tools for dynamic planning and executes tools for API interaction across the entire LiveMCPTool suite. Our evaluation covers 10 leading models, with the best-performing model (Claude-Sonnet-4) reaching a 78.95% success rate. However, we observe large performance variance across models, and several widely-used models perform poorly in LiveMCPBench's complex, tool-rich environments. Overall, LiveMCPBench offers the first unified framework for benchmarking LLM agents in realistic, tool-rich, and dynamic MCP environments, laying a solid foundation for scalable and reproducible research on agent capabilities. Our code and data will be publicly available at https://icip-cas.github.io/LiveMCPBench.

[Arxiv](https://arxiv.org/abs/2508.01780)