# TQA-Bench：通过可扩展的上下文和符号扩展来评估用于多表问答的大型语言模型

发布时间：2024年11月29日

`LLM应用` `医疗保健`

> TQA-Bench: Evaluating LLMs for Multi-Table Question Answering with Scalable Context and Symbolic Extension

# 摘要

> 大型语言模型（LLMs）的问世为复杂数据管理任务创造了大量机遇，尤其在复杂多表关系数据的问答（QA）领域。尽管进步显著，但由于分析异构表结构的复杂性以及可能存在的大规模序列化关系数据，对多表 QA 中的 LLMs 进行系统评估仍是关键难题。现有的基准多聚焦于单表 QA，无法涵盖在金融、医疗保健和电子商务等现实领域中跨多个关系表推理的复杂性。为弥补这一差距，我们推出了 TQA-Bench，这是一个全新的多表 QA 基准，用于评估 LLMs 处理关系数据复杂 QA 任务的能力。我们的基准整合了来自真实世界公共数据集的各类关系数据库实例，并引入了灵活的采样机制，以创建具有不同多表上下文长度（8K 至 64K 标记）的任务。为保证稳健性和可靠性，我们将符号扩展融入评估框架，能够评估 LLMs 超越简单数据检索或概率模式匹配的推理能力。我们对一系列 LLMs（包括开源和闭源的，模型规模从 70 亿到 700 亿参数不等）进行了系统评估。大量实验揭示了 LLMs 在多表 QA 中的关键性能表现，突出了在复杂的数据驱动环境中推进其应用所面临的挑战与机遇。我们的基准实现和结果可在 https://github.com/Relaxed-System-Lab/TQA-Bench 查看。

> The advent of large language models (LLMs) has unlocked great opportunities in complex data management tasks, particularly in question answering (QA) over complicated multi-table relational data. Despite significant progress, systematically evaluating LLMs on multi-table QA remains a critical challenge due to the inherent complexity of analyzing heterogeneous table structures and potential large scale of serialized relational data. Existing benchmarks primarily focus on single-table QA, failing to capture the intricacies of reasoning across multiple relational tables, as required in real-world domains such as finance, healthcare, and e-commerce. To address this gap, we present TQA-Bench, a new multi-table QA benchmark designed to evaluate the capabilities of LLMs in tackling complex QA tasks over relational data. Our benchmark incorporates diverse relational database instances sourced from real-world public datasets and introduces a flexible sampling mechanism to create tasks with varying multi-table context lengths, ranging from 8K to 64K tokens. To ensure robustness and reliability, we integrate symbolic extensions into the evaluation framework, enabling the assessment of LLM reasoning capabilities beyond simple data retrieval or probabilistic pattern matching. We systematically evaluate a range of LLMs, both open-source and closed-source, spanning model scales from 7 billion to 70 billion parameters. Our extensive experiments reveal critical insights into the performance of LLMs in multi-table QA, highlighting both challenges and opportunities for advancing their application in complex, data-driven environments. Our benchmark implementation and results are available at https://github.com/Relaxed-System-Lab/TQA-Bench.

[Arxiv](https://arxiv.org/abs/2411.19504)