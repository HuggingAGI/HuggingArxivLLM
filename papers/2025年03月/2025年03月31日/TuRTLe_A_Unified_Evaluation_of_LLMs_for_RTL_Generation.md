# TuRTLe：针对 RTL 生成任务的 LLM 统一评估框架

发布时间：2025年03月31日

`LLM应用` `EDA` `半导体`

> TuRTLe: A Unified Evaluation of LLMs for RTL Generation

# 摘要

> 大型语言模型（LLMs）的快速发展推动了生成式AI在各领域的广泛应用，其中就包括电子设计自动化（EDA）。与传统的软件开发不同，EDA领域面临着独特的挑战：生成的RTL代码不仅要语法正确、功能准确，还需要能够被硬件生成器进行综合，同时满足性能、功耗和面积的约束条件。这些额外的要求带来了复杂性，而现有的代码生成基准测试往往无法全面捕捉这些复杂性，这限制了它们在评估RTL生成任务中对LLMs的有效性。为了解决这一问题，我们提出了TuRTLe，这是一个统一的评估框架，旨在系统性地评估LLMs在关键RTL生成任务中的表现。TuRTLe整合了多个现有的基准测试，并自动化了评估过程，从而能够全面评估LLMs在语法正确性、功能正确性、综合能力、PPA优化以及精确行完成等方面的表现。通过这一框架，我们对多种开源的LLMs进行了基准测试，并分析了它们在EDA特定任务中的优势与不足。我们的结果显示，基于推理的模型，如DeepSeek R1，在多个评估标准下表现始终优于其他模型，但代价是计算开销和推理延迟的增加。此外，基础模型在模块完成任务中表现更佳，而经过指令微调的模型在规格到RTL的任务中表现更为出色。

> The rapid advancements in LLMs have driven the adoption of generative AI in various domains, including Electronic Design Automation (EDA). Unlike traditional software development, EDA presents unique challenges, as generated RTL code must not only be syntactically correct and functionally accurate but also synthesizable by hardware generators while meeting performance, power, and area constraints. These additional requirements introduce complexities that existing code-generation benchmarks often fail to capture, limiting their effectiveness in evaluating LLMs for RTL generation. To address this gap, we propose TuRTLe, a unified evaluation framework designed to systematically assess LLMs across key RTL generation tasks. TuRTLe integrates multiple existing benchmarks and automates the evaluation process, enabling a comprehensive assessment of LLM performance in syntax correctness, functional correctness, synthesis, PPA optimization, and exact line completion. Using this framework, we benchmark a diverse set of open LLMs and analyze their strengths and weaknesses in EDA-specific tasks. Our results show that reasoning-based models, such as DeepSeek R1, consistently outperform others across multiple evaluation criteria, but at the cost of increased computational overhead and inference latency. Additionally, base models are better suited in module completion tasks, while instruct-tuned models perform better in specification-to-RTL tasks.

[Arxiv](https://arxiv.org/abs/2504.01986)