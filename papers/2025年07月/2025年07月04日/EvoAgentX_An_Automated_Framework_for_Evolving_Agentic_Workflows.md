# EvoAgentX：一个自动化的智能体工作流演进框架

发布时间：2025年07月04日

`Agent` `人工智能` `自动化`

> EvoAgentX: An Automated Framework for Evolving Agentic Workflows

# 摘要

> # 摘要  
多智能体系统（MAS）已成为一种强大的范式，用于编排大型语言模型（LLMs）和专用工具，以协作解决复杂任务。然而，现有的MAS框架通常需要手动配置工作流程，缺乏对动态演进和性能优化的本机支持。此外，许多MAS优化算法未能集成到统一的框架中。在本文中，我们介绍了EvoAgentX，一个开源平台，旨在自动化多智能体工作流的生成、执行和进化优化。EvoAgentX采用模块化架构，由五个核心层组成：基本组件层、智能体层、工作流层、进化层和评估层。具体而言，在进化层中，EvoAgentX集成了三个MAS优化算法，TextGrad、AFlow和MIPRO，用于迭代优化智能体提示、工具配置和工作流拓扑结构。我们在HotPotQA、MBPP和MATH数据集上分别对EvoAgentX进行评估，测试其在多跳推理、代码生成和数学问题解决方面的能力，并进一步通过GAIA平台评估其在实际任务中的表现。实验结果表明，EvoAgentX在各项任务中均实现了显著的性能提升，包括HotPotQA F1值提升了7.44%，MBPP的pass@1指标提高了10.00%，MATH的解答准确率提升了10.00%，以及在GAIA上的整体准确率提升了高达20.00%。源代码可在以下链接获取：https://github.com/EvoAgentX/EvoAgentX

> Multi-agent systems (MAS) have emerged as a powerful paradigm for orchestrating large language models (LLMs) and specialized tools to collaboratively address complex tasks. However, existing MAS frameworks often require manual workflow configuration and lack native support for dynamic evolution and performance optimization. In addition, many MAS optimization algorithms are not integrated into a unified framework. In this paper, we present EvoAgentX, an open-source platform that automates the generation, execution, and evolutionary optimization of multi-agent workflows. EvoAgentX employs a modular architecture consisting of five core layers: the basic components, agent, workflow, evolving, and evaluation layers. Specifically, within the evolving layer, EvoAgentX integrates three MAS optimization algorithms, TextGrad, AFlow, and MIPRO, to iteratively refine agent prompts, tool configurations, and workflow topologies. We evaluate EvoAgentX on HotPotQA, MBPP, and MATH for multi-hop reasoning, code generation, and mathematical problem solving, respectively, and further assess it on real-world tasks using GAIA. Experimental results show that EvoAgentX consistently achieves significant performance improvements, including a 7.44% increase in HotPotQA F1, a 10.00% improvement in MBPP pass@1, a 10.00% gain in MATH solve accuracy, and an overall accuracy improvement of up to 20.00% on GAIA. The source code is available at: https://github.com/EvoAgentX/EvoAgentX

[Arxiv](https://arxiv.org/abs/2507.03616)