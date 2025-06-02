# AMSbench：全面评估MLLM在模拟混合信号电路中能力的基准测试工具

发布时间：2025年05月29日

`LLM应用` `集成电路设计` `电路设计`

> AMSbench: A Comprehensive Benchmark for Evaluating MLLM Capabilities in AMS Circuits

# 摘要

> 模拟/混合信号（AMS）电路在集成电路（IC）行业中扮演着至关重要的角色。然而，由于其复杂性和难度，自动化AMS电路设计长期以来一直是行业难题。近期，多模态大语言模型（MLLMs）的进步为AMS电路分析和设计带来了新的可能性。然而，现有研究往往局限于领域内孤立任务的评估，缺乏一个全面的基准来系统性地评估模型在各种AMS相关挑战中的能力。

为了解决这一空白，我们推出了 AMSbench，这是一个专为评估MLLM在关键任务中性能而设计的基准测试套件，涵盖电路原理图感知、电路分析和电路设计等领域。AMSbench 包含约8000个测试问题，涵盖多个难度级别，并对包括开源和专有解决方案在内的八个突出模型进行了评估，例如Qwen 2.5-VL和Gemini 2.5 Pro。

我们的评估结果揭示了当前MLLMs在复杂多模态推理和复杂电路设计任务中的显著局限性。这些发现强调了推进MLLMs对电路特定知识的理解和有效应用的必要性，从而缩小与人类专业知识的差距，并迈向完全自动化的AMS电路设计工作流程。我们的数据集已发布在 https://huggingface.co/datasets/wwhhyy/AMSBench

> Analog/Mixed-Signal (AMS) circuits play a critical role in the integrated circuit (IC) industry. However, automating Analog/Mixed-Signal (AMS) circuit design has remained a longstanding challenge due to its difficulty and complexity. Recent advances in Multi-modal Large Language Models (MLLMs) offer promising potential for supporting AMS circuit analysis and design. However, current research typically evaluates MLLMs on isolated tasks within the domain, lacking a comprehensive benchmark that systematically assesses model capabilities across diverse AMS-related challenges. To address this gap, we introduce AMSbench, a benchmark suite designed to evaluate MLLM performance across critical tasks including circuit schematic perception, circuit analysis, and circuit design. AMSbench comprises approximately 8000 test questions spanning multiple difficulty levels and assesses eight prominent models, encompassing both open-source and proprietary solutions such as Qwen 2.5-VL and Gemini 2.5 Pro. Our evaluation highlights significant limitations in current MLLMs, particularly in complex multi-modal reasoning and sophisticated circuit design tasks. These results underscore the necessity of advancing MLLMs' understanding and effective application of circuit-specific knowledge, thereby narrowing the existing performance gap relative to human expertise and moving toward fully automated AMS circuit design workflows. Our data is released at https://huggingface.co/datasets/wwhhyy/AMSBench

[Arxiv](https://arxiv.org/abs/2505.24138)