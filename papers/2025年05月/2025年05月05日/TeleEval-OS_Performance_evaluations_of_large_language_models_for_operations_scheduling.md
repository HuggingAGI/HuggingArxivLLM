# TeleEval-OS：大型语言模型在操作调度任务中的性能评估

发布时间：2025年05月05日

`LLM应用` `运营调度`

> TeleEval-OS: Performance evaluations of large language models for operations scheduling

# 摘要

> 大型语言模型 (LLMs) 的飞速发展为人工智能注入了强劲动力，其应用潜力在多个专业领域中崭露头角。在通信行业中，运营调度 (OS) 是一项至关重要且复杂的任务，涉及网络、服务、风险和人力资源的全面管理，以实现高效的生产调度和统一的服务控制。然而，由于 OS 任务的复杂性和领域特定性，加之缺乏全面的评估基准，限制了我们对 LLMs 在这一关键领域的深入探索。为填补这一研究空白，我们推出了首个通信运营调度评估基准 (TeleEval-OS)。该基准包含 13 个子任务的 15 个数据集，全面模拟了智能工单创建、处理、关闭和评估四个关键运营阶段。为了系统评估 LLMs 的能力，我们将它们在通信运营调度中的表现分为四个难度递增的层次：基础 NLP、知识问答、报告生成和报告分析。在 TeleEval-OS 上，我们采用零样本和少样本评估方法，对 10 个开源 LLM（如 DeepSeek-V3）和 4 个闭源 LLM（如 GPT-4o）进行了全面测试。实验结果表明，开源 LLMs 在特定场景下能够超越闭源 LLMs，充分展现了其在通信运营调度领域的巨大潜力和价值。

> The rapid advancement of large language models (LLMs) has significantly propelled progress in artificial intelligence, demonstrating substantial application potential across multiple specialized domains. Telecommunications operation scheduling (OS) is a critical aspect of the telecommunications industry, involving the coordinated management of networks, services, risks, and human resources to optimize production scheduling and ensure unified service control. However, the inherent complexity and domain-specific nature of OS tasks, coupled with the absence of comprehensive evaluation benchmarks, have hindered thorough exploration of LLMs' application potential in this critical field. To address this research gap, we propose the first Telecommunications Operation Scheduling Evaluation Benchmark (TeleEval-OS). Specifically, this benchmark comprises 15 datasets across 13 subtasks, comprehensively simulating four key operational stages: intelligent ticket creation, intelligent ticket handling, intelligent ticket closure, and intelligent evaluation. To systematically assess the performance of LLMs on tasks of varying complexity, we categorize their capabilities in telecommunications operation scheduling into four hierarchical levels, arranged in ascending order of difficulty: basic NLP, knowledge Q&A, report generation, and report analysis. On TeleEval-OS, we leverage zero-shot and few-shot evaluation methods to comprehensively assess 10 open-source LLMs (e.g., DeepSeek-V3) and 4 closed-source LLMs (e.g., GPT-4o) across diverse scenarios. Experimental results demonstrate that open-source LLMs can outperform closed-source LLMs in specific scenarios, highlighting their significant potential and value in the field of telecommunications operation scheduling.

[Arxiv](https://arxiv.org/abs/2506.11017)