# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年02月17日

`LLM应用` `高性能计算` `科学计算`

> Connecting Large Language Model Agent to High Performance Computing Resource

# 摘要

> 大型语言模型（LLM）代理工作流使 LLM 能够调用工具函数，从而在特定科学领域问题上提升性能。为了处理大规模科学研究，需要访问计算资源和并行计算环境。在本研究中，我们实现了Parsl与LangChain/LangGraph工具调用的集成，以填补LLM代理与计算资源之间的鸿沟。我们在本地工作站和Polaris/ALCF的HPC环境中设置了两种工具调用实现并进行了测试。第一种实现方式利用Parsl增强的LangChain工具节点，将工具函数并发排队到Parsl工作者进行并行执行。第二种配置通过将工具函数转换为Parsl集成函数实现，更适合超级计算机环境中的大规模任务。我们还提示LLM代理工作流运行分子动力学模拟，采用不同的蛋白质结构和模拟条件。结果表明，LLM代理工具能够被Parsl有效管理和并发执行，在可用的计算资源上完成任务。

> The Large Language Model agent workflow enables the LLM to invoke tool functions to increase the performance on specific scientific domain questions. To tackle large scale of scientific research, it requires access to computing resource and parallel computing setup. In this work, we implemented Parsl to the LangChain/LangGraph tool call setup, to bridge the gap between the LLM agent to the computing resource. Two tool call implementations were set up and tested on both local workstation and HPC environment on Polaris/ALCF. The first implementation with Parsl-enabled LangChain tool node queues the tool functions concurrently to the Parsl workers for parallel execution. The second configuration is implemented by converting the tool functions into Parsl ensemble functions, and is more suitable for large task on super computer environment. The LLM agent workflow was prompted to run molecular dynamics simulations, with different protein structure and simulation conditions. These results showed the LLM agent tools were managed and executed concurrently by Parsl on the available computing resource.

[Arxiv](https://arxiv.org/abs/2502.12280)