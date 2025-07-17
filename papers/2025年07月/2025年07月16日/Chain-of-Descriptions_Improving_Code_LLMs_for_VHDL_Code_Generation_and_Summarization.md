# 描述链：提升代码LLMs的VHDL代码生成与摘要能力

发布时间：2025年07月16日

`LLM应用` `电子设计自动化` `硬件设计`

> Chain-of-Descriptions: Improving Code LLMs for VHDL Code Generation and Summarization

# 摘要

> 大型语言模型（LLMs）已在各类自然语言处理（NLP）任务和领域中得到广泛应用，展现了其强大的适应性和有效性。在电子设计自动化（EDA）领域，LLMs在寄存器传输级（RTL）代码生成和摘要等任务中展现出巨大潜力。然而，尽管LLMs在通用代码相关任务中得到了广泛应用，但针对硬件描述语言（HDLs）——尤其是VHDL——的模型评估和优化研究却寥寥无几。本研究通过多种指标和两个数据集——VHDL-Eval和VHDL-Xform，评估现有代码LLMs在VHDL代码生成和摘要任务中的性能。其中，VHDL-Xform是我们自建的数据集，旨在衡量LLMs对功能等效代码的理解能力。研究结果表明，这些模型在各项指标上表现欠佳，凸显了其在这一领域适用性上的显著差距。为应对这一挑战，我们提出了Chain-of-Descriptions（CoDes），一种全新的方法，旨在提升LLMs在VHDL代码生成和摘要任务中的性能。CoDes方法通过生成一系列中间描述步骤，基于：(i) 代码生成的问题陈述，以及(ii) VHDL代码的摘要。这些步骤随后与原始输入提示（问题陈述或代码）结合，并作为输入提供给LLMs以生成最终输出。我们的实验表明，CoDes方法在两个数据集上的各项指标上均显著超越了标准提示策略。此方法不仅提升了VHDL代码生成和摘要的质量，还为未来针对VHDL优化代码LLMs的研究提供了框架。

> Large Language Models (LLMs) have become widely used across diverse NLP tasks and domains, demonstrating their adaptability and effectiveness. In the realm of Electronic Design Automation (EDA), LLMs show promise for tasks like Register-Transfer Level (RTL) code generation and summarization. However, despite the proliferation of LLMs for general code-related tasks, there's a dearth of research focused on evaluating and refining these models for hardware description languages (HDLs), notably VHDL. In this study, we evaluate the performance of existing code LLMs for VHDL code generation and summarization using various metrics and two datasets -- VHDL-Eval and VHDL-Xform. The latter, an in-house dataset, aims to gauge LLMs' understanding of functionally equivalent code. Our findings reveal consistent underperformance of these models across different metrics, underscoring a significant gap in their suitability for this domain. To address this challenge, we propose Chain-of-Descriptions (CoDes), a novel approach to enhance the performance of LLMs for VHDL code generation and summarization tasks. CoDes involves generating a series of intermediate descriptive steps based on: (i) the problem statement for code generation, and (ii) the VHDL code for summarization. These steps are then integrated with the original input prompt (problem statement or code) and provided as input to the LLMs to generate the final output. Our experiments demonstrate that the CoDes approach significantly surpasses the standard prompting strategy across various metrics on both datasets. This method not only improves the quality of VHDL code generation and summarization but also serves as a framework for future research aimed at enhancing code LLMs for VHDL.

[Arxiv](https://arxiv.org/abs/2507.12308)