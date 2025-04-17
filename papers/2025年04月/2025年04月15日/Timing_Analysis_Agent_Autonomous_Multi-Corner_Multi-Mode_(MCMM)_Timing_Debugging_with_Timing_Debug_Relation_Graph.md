# 时序分析代理：基于时序调试关系图的多角多模式 (MCMM) 时序调试

发布时间：2025年04月15日

`RAG` `半导体` `电子设计自动化`

> Timing Analysis Agent: Autonomous Multi-Corner Multi-Mode (MCMM) Timing Debugging with Timing Debug Relation Graph

# 摘要

> 时序分析是超大规模集成电路（VLSI）设计与优化中不可或缺且要求严格的验证方法，同时也是决定芯片是否可以送交半导体代工厂进行制造的关键环节。近年来，随着技术的不断进步，金属间距的缩小和器件数量的增加，使得从多角多模式（MCMM）时序报告中调试时序问题变得更加困难，导致经验丰富的人类设计者的周转时间更长。因此，一种高效且智能的调试方法对于解决时序问题和缩短周转时间至关重要。最近，大型语言模型（LLMs）在语言理解和交互式决策制定方面展现了巨大的潜力，尤其在结合推理和行动能力方面。在这项工作中，我们提出了一种基于多语言模型任务解决的时序分析代理，并采用了一种新颖的分层规划与求解流程，以实现对商业工具生成的时序报告的自动化分析。此外，我们构建了一个时序调试关系图（TDRG），将报告与经验丰富的时序工程师的调试轨迹之间的关系连接起来。该时序分析代理采用了一种新颖的智能检索增强生成（RAG）方法，结合代理和编码功能，在开发的TDRG上准确检索数据。在我们的研究中，所提出的时序分析代理在单报告基准测试中达到了平均98%的通过率，并在来自工业设计的多报告基准测试中达到了90%的通过率，这充分证明了其有效性和适应性。

> Timing analysis is an essential and demanding verification method for Very Large Scale Integrated (VLSI) circuit design and optimization. In addition, it also serves as the cornerstone of the final sign-off, determining whether the chip is ready to be sent to the semiconductor foundry for fabrication. Recently, as the technology advance relentlessly, smaller metal pitches and the increasing number of devices have led to greater challenges and longer turn-around-time for experienced human designers to debug timing issues from the Multi-Corner Multi-Mode (MCMM) timing reports. As a result, an efficient and intelligent methodology is highly necessary and essential for debugging timing issues and reduce the turnaround times. Recently, Large Language Models (LLMs) have shown great promise across various tasks in language understanding and interactive decision-making, incorporating reasoning and actions. In this work, we propose a timing analysis agent, that is empowered by multi-LLMs task solving, and incorporates a novel hierarchical planning and solving flow to automate the analysis of timing reports from commercial tool. In addition, we build a Timing Debug Relation Graph (TDRG) that connects the reports with the relationships of debug traces from experienced timing engineers. The timing analysis agent employs the novel Agentic Retrieval Augmented Generation (RAG) approach, that includes agent and coding to retrieve data accurately, on the developed TDRG. In our studies, the proposed timing analysis agent achieves an average 98% pass-rate on a single-report benchmark and a 90% pass-rate for multi-report benchmark from industrial designs, demonstrating its effectiveness and adaptability.

[Arxiv](https://arxiv.org/abs/2504.11502)