# MPBench：全面的多模态推理基准，针对流程错误识别

发布时间：2025年03月16日

`LLM应用` `人工智能`

> MPBench: A Comprehensive Multimodal Reasoning Benchmark for Process Errors Identification

# 摘要

> 推理能力是大型语言模型（LLMs）处理复杂任务的核心，而识别过程中的错误对于提升这一能力至关重要。最近，过程级奖励模型（PRMs）被提出，旨在通过分步奖励促进强化学习和数据生成，同时在推理过程中引导模型走向正确步骤，从而提高推理准确性。然而，现有的PRMs基准测试主要基于文本并专注于错误检测，忽略了推理搜索等其他场景。为弥补这一空白，我们提出了MPBench——一个全面、多任务、多模态的基准测试，旨在系统评估PRMs在不同场景下的有效性。MPBench采用三个评估范式，分别针对PRMs在推理过程中的不同作用：（1）步骤正确性，评估每个中间推理步骤的正确性；（2）答案聚合，聚合多个解决方案并选择最优答案；（3）推理过程搜索，在推理过程中引导寻找最优推理步骤。通过这些范式，MPBench进行了全面评估，并为多模态PRMs的发展提供了重要见解。

> Reasoning is an essential capacity for large language models (LLMs) to address complex tasks, where the identification of process errors is vital for improving this ability. Recently, process-level reward models (PRMs) were proposed to provide step-wise rewards that facilitate reinforcement learning and data production during training and guide LLMs toward correct steps during inference, thereby improving reasoning accuracy. However, existing benchmarks of PRMs are text-based and focus on error detection, neglecting other scenarios like reasoning search. To address this gap, we introduce MPBench, a comprehensive, multi-task, multimodal benchmark designed to systematically assess the effectiveness of PRMs in diverse scenarios. MPBench employs three evaluation paradigms, each targeting a specific role of PRMs in the reasoning process: (1) Step Correctness, which assesses the correctness of each intermediate reasoning step; (2) Answer Aggregation, which aggregates multiple solutions and selects the best one; and (3) Reasoning Process Search, which guides the search for optimal reasoning steps during inference. Through these paradigms, MPBench makes comprehensive evaluations and provides insights into the development of multimodal PRMs.

[Arxiv](https://arxiv.org/abs/2503.12505)