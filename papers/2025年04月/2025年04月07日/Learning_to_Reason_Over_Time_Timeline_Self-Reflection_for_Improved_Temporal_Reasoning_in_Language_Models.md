# 时间推理新突破：时间轴自我反思助力语言模型提升时序理解能力

发布时间：2025年04月07日

`LLM应用` `问答系统` `调度系统`

> Learning to Reason Over Time: Timeline Self-Reflection for Improved Temporal Reasoning in Language Models

# 摘要

> 大型语言模型（LLMs）在生成连贯文本、理解上下文和执行推理任务方面表现出色。然而，它们在处理时间推理任务时仍面临挑战，这需要处理事件顺序、持续时间和跨时间关系等时间相关的信息。这些能力对于问答、调度和历史分析等应用场景至关重要。本文中，我们提出了TISER框架，通过结合时间轴构建与迭代自我反思的多阶段方法，显著提升了LLMs的时间推理能力。我们的方法利用测试时缩放技术，延长推理轨迹的长度，从而更有效地捕捉复杂的时间依赖关系。这一创新不仅提升了推理精度，还增强了推理过程的可追溯性。实验结果表明，TISER在多个基准测试中展现了顶尖性能，甚至在分布外测试集中也表现优异。更重要的是，TISER使小型开源模型在具有挑战性的时间推理任务中超越了大型闭源模型，展现了其强大的潜力。

> Large Language Models (LLMs) have emerged as powerful tools for generating coherent text, understanding context, and performing reasoning tasks. However, they struggle with temporal reasoning, which requires processing time-related information such as event sequencing, durations, and inter-temporal relationships. These capabilities are critical for applications including question answering, scheduling, and historical analysis. In this paper, we introduce TISER, a novel framework that enhances the temporal reasoning abilities of LLMs through a multi-stage process that combines timeline construction with iterative self-reflection. Our approach leverages test-time scaling to extend the length of reasoning traces, enabling models to capture complex temporal dependencies more effectively. This strategy not only boosts reasoning accuracy but also improves the traceability of the inference process. Experimental results demonstrate state-of-the-art performance across multiple benchmarks, including out-of-distribution test sets, and reveal that TISER enables smaller open-source models to surpass larger closed-weight models on challenging temporal reasoning tasks.

[Arxiv](https://arxiv.org/abs/2504.05258)