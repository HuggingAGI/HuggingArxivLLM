# 像素编程：计算机应用与软件工程的交汇

发布时间：2025年02月24日

`Agent` `软件工程` `软件开发工具`

> Programming with Pixels: Computer-Use Meets Software Engineering

# 摘要

> 软件工程 (SWE) 代理的发展主要基于一种 $	extit{工具范式}$，即代理通过与人工设计的工具API交互来完成特定任务。尽管这些方法在专门任务上表现出色，但它们缺乏通用性，需要为每个任务预定义工具，并且难以跨编程语言和领域扩展。我们推出了 $	exttt{Programming with Pixels}$ (PwP)，一个统一软件开发任务的代理环境，让 $	extit{计算机使用代理}$ 能够通过视觉感知、打字和点击直接在IDE中操作，而非依赖预定义工具API。为了系统评估这些代理，我们提出了 $	exttt{PwP-Bench}$，一个基准测试，它在任务无关的状态和动作空间下统一了现有跨越多种编程语言、模式和领域的SWE基准测试。实验表明，通用的计算机使用代理可以在各种SWE任务上接近甚至超越专门的工具范式代理，而无需人工设计工具。然而，分析显示，当前模型在视觉定位方面存在局限性，未能充分利用许多可以简化任务的IDE工具。当代理可以直接访问IDE工具而无需视觉交互时，性能显著提升，凸显了利用内置IDE功能的巨大潜力。我们的结果确立了PwP作为构建和评估下一代软件工程代理的可扩展测试床。我们已发布代码和数据集，详情请访问 https://programmingwithpixels.com

> Recent advancements in software engineering (SWE) agents have largely followed a $\textit{tool-based paradigm}$, where agents interact with hand-engineered tool APIs to perform specific tasks. While effective for specialized tasks, these methods fundamentally lack generalization, as they require predefined tools for each task and do not scale across programming languages and domains. We introduce $\texttt{Programming with Pixels}$ (PwP), an agent environment that unifies software development tasks by enabling $\textit{computer-use agents}$-agents that operate directly within an IDE through visual perception, typing, and clicking, rather than relying on predefined tool APIs. To systematically evaluate these agents, we propose $\texttt{PwP-Bench}$, a benchmark that unifies existing SWE benchmarks spanning tasks across multiple programming languages, modalities, and domains under a task-agnostic state and action space. Our experiments demonstrate that general-purpose computer-use agents can approach or even surpass specialized tool-based agents on a variety of SWE tasks without the need for hand-engineered tools. However, our analysis shows that current models suffer from limited visual grounding and fail to exploit many IDE tools that could simplify their tasks. When agents can directly access IDE tools, without visual interaction, they show significant performance improvements, highlighting the untapped potential of leveraging built-in IDE capabilities. Our results establish PwP as a scalable testbed for building and evaluating the next wave of software engineering agents. We release code and data at https://programmingwithpixels.com

[Arxiv](https://arxiv.org/abs/2502.18525)