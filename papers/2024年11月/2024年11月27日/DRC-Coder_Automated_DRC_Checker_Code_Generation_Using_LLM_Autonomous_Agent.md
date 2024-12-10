# DRC-Coder：利用 LLM 自主代理实现自动 DRC 检查器代码生成

发布时间：2024年11月27日

`Agent` `集成电路` `电路设计`

> DRC-Coder: Automated DRC Checker Code Generation Using LLM Autonomous Agent

# 摘要

> 在先进的技术节点里，集成设计规则检查器（DRC）常被用于布局布线工具中，以实现功率-性能-面积的快速优化循环。要实现集成 DRC 检查器并达到商业 DRC 工具的标准，需要大量专业人力来解读代工厂规格、分析布局以及反复调试代码。然而，这一劳动密集型过程，每逢技术节点更新就得重复，延长了电路设计的周转时间。在本文中，我们推出了 DRC-Coder，这是一个具备视觉能力的多智能体框架，用于自动生成 DRC 代码。通过融合视觉语言模型和大型语言模型（LLM），DRC-Coder 能够有效处理文本、视觉和布局信息，由两个专门的 LLM 进行规则解读和编码。我们还为 LLM 设计了自动评估功能，用于 DRC 代码调试。实验结果显示，针对最先进的标准单元布局工具的 3 纳米以下技术节点，DRC-Coder 在生成符合商业 DRC 工具标准的 DRC 代码方面，F1 分数达到了完美的 1.000，大幅优于标准提示技术（F1 = 0.631）。DRC-Coder 平均能在四分钟内为每个设计规则生成代码，显著加快了技术进步，降低了工程成本。

> In the advanced technology nodes, the integrated design rule checker (DRC) is often utilized in place and route tools for fast optimization loops for power-performance-area. Implementing integrated DRC checkers to meet the standard of commercial DRC tools demands extensive human expertise to interpret foundry specifications, analyze layouts, and debug code iteratively. However, this labor-intensive process, requiring to be repeated by every update of technology nodes, prolongs the turnaround time of designing circuits. In this paper, we present DRC-Coder, a multi-agent framework with vision capabilities for automated DRC code generation. By incorporating vision language models and large language models (LLM), DRC-Coder can effectively process textual, visual, and layout information to perform rule interpretation and coding by two specialized LLMs. We also design an auto-evaluation function for LLMs to enable DRC code debugging. Experimental results show that targeting on a sub-3nm technology node for a state-of-the-art standard cell layout tool, DRC-Coder achieves perfect F1 score 1.000 in generating DRC codes for meeting the standard of a commercial DRC tool, highly outperforming standard prompting techniques (F1=0.631). DRC-Coder can generate code for each design rule within four minutes on average, which significantly accelerates technology advancement and reduces engineering costs.

[Arxiv](https://arxiv.org/abs/2412.05311)