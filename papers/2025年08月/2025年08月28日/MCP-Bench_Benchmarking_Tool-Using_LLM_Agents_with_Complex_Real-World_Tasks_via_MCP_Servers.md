# MCP-Bench：基于MCP服务器的工具型LLM智能体复杂现实任务基准测试

发布时间：2025年08月28日

`Agent` `金融科技` `基础理论`

> MCP-Bench: Benchmarking Tool-Using LLM Agents with Complex Real-World Tasks via MCP Servers

# 摘要

> 我们推出MCP-Bench基准测试集，用于评估大型语言模型（LLMs）在真实多步骤任务中的表现——这类任务需借助工具使用、跨工具协作、精确参数控制及规划推理来完成。MCP-Bench基于模型上下文协议（MCP）构建，将LLMs接入28个代表性实时MCP服务器，覆盖金融、旅游、科学计算、学术搜索等领域的250个工具。与以往基于API的基准测试集不同，每个MCP服务器均配备协同工作的互补工具集，可构建输入输出高度耦合的真实多步骤任务。MCP-Bench的任务旨在测试智能体的多项核心能力：从无明确工具名称的模糊指令中检索相关工具、为复杂目标规划多跳执行路径、基于工具中间输出生成响应，以及编排跨领域工作流。这些能力恰是现有基准测试集的短板——它们依赖明确工具说明、浅层少步骤工作流及孤立领域操作，无法充分评估上述能力。我们提出多维度评估框架，涵盖工具级模式理解与使用、路径级规划及任务完成度。对20个先进LLM的实验表明，MCP-Bench仍存在诸多待攻克的挑战。代码与数据：https://github.com/Accenture/mcp-bench。

> We introduce MCP-Bench, a benchmark for evaluating large language models (LLMs) on realistic, multi-step tasks that demand tool use, cross-tool coordination, precise parameter control, and planning/reasoning for solving tasks. Built on the Model Context Protocol (MCP), MCP-Bench connects LLMs to 28 representative live MCP servers spanning 250 tools across domains such as finance, traveling, scientific computing, and academic search. Unlike prior API-based benchmarks, each MCP server provides a set of complementary tools designed to work together, enabling the construction of authentic, multi-step tasks with rich input-output coupling. Tasks in MCP-Bench test agents' ability to retrieve relevant tools from fuzzy instructions without explicit tool names, plan multi-hop execution trajectories for complex objectives, ground responses in intermediate tool outputs, and orchestrate cross-domain workflows - capabilities not adequately evaluated by existing benchmarks that rely on explicit tool specifications, shallow few-step workflows, and isolated domain operations. We propose a multi-faceted evaluation framework covering tool-level schema understanding and usage, trajectory-level planning, and task completion. Experiments on 20 advanced LLMs reveal persistent challenges in MCP-Bench. Code and data: https://github.com/Accenture/mcp-bench.

[Arxiv](https://arxiv.org/abs/2508.20453)