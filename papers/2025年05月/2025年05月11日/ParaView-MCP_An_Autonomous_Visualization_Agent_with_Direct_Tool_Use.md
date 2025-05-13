# ParaView-MCP: 自主的可视化智能体，能够直接使用工具

发布时间：2025年05月11日

`Agent` `科学可视化` `人机交互`

> ParaView-MCP: An Autonomous Visualization Agent with Direct Tool Use

# 摘要

> 尽管功能强大且应用广泛，但像ParaView这样的工具因学习曲线陡峭而让许多潜在用户却步。本研究推出ParaView-MCP，这是一个结合现代多模态大语言模型（MLLMs）与ParaView的自主代理工具，不仅降低了使用门槛，还为ParaView增添了智能决策支持功能。通过利用MLLMs在推理、命令执行和视觉能力方面的最新进展，ParaView-MCP让用户能够通过自然语言和视觉输入与ParaView进行交互。具体而言，我们的系统采用了模型上下文协议（MCP）——一个用于模型与应用程序间通信的标准接口——这使得MLLMs可以直接与ParaView的Python API互动，从而实现用户、语言模型与可视化工具之间的无缝信息交换。此外，通过实现一种允许代理观察视口的视觉反馈机制，我们解锁了一系列新功能，包括从示例中重建可视化、基于用户定义目标的闭环可视化参数更新，甚至跨应用协作，涉及多种工具。总体而言，我们认为这种基于代理的可视化范式能够深刻改变我们与可视化工具的交互方式。我们预计这种可视化工具的开发将迅速普及，在可视化研究和行业中都将迎来显著发展。

> While powerful and well-established, tools like ParaView present a steep learning curve that discourages many potential users. This work introduces ParaView-MCP, an autonomous agent that integrates modern multimodal large language models (MLLMs) with ParaView to not only lower the barrier to entry but also augment ParaView with intelligent decision support. By leveraging the state-of-the-art reasoning, command execution, and vision capabilities of MLLMs, ParaView-MCP enables users to interact with ParaView through natural language and visual inputs. Specifically, our system adopted the Model Context Protocol (MCP) - a standardized interface for model-application communication - that facilitates direct interaction between MLLMs with ParaView's Python API to allow seamless information exchange between the user, the language model, and the visualization tool itself. Furthermore, by implementing a visual feedback mechanism that allows the agent to observe the viewport, we unlock a range of new capabilities, including recreating visualizations from examples, closed-loop visualization parameter updates based on user-defined goals, and even cross-application collaboration involving multiple tools. Broadly, we believe such an agent-driven visualization paradigm can profoundly change the way we interact with visualization tools. We expect a significant uptake in the development of such visualization tools, in both visualization research and industry.

[Arxiv](https://arxiv.org/abs/2505.07064)