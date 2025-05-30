# # 思感：工具增强型智能体在遥感任务中的评估

发布时间：2025年05月29日

`LLM应用` `城市规划`

> ThinkGeo: Evaluating Tool-Augmented Agents for Remote Sensing Tasks

# 摘要

> 大型语言模型（LLMs）的最新进展催生了工具增强型代理，使其能够通过逐步推理解决复杂的现实任务。然而，现有评估多集中在通用或跨模态场景，缺乏针对复杂遥感用例中工具使用能力的领域特定基准。我们推出ThinkGeo，这是一个专为评估LLM驱动的代理在遥感任务中能力而设计的基准测试，通过结构化工具使用和多步规划实现。

受工具交互范式的启发，ThinkGeo包含了广泛实际应用领域的人工策划查询，涵盖城市规划、灾害评估与变化分析、环境监测、交通分析、航空监测、休闲基础设施和工业场地分析等。每个查询均基于卫星或航空影像，并要求代理利用多样化的工具集进行推理。我们实现了ReAct风格的交互循环，并在436个结构化的代理任务上评估了开源和闭源的LLMs（如GPT-4o，Qwen2.5）。基准测试不仅报告了逐步执行指标，还提供了最终答案的正确性评估。

分析结果揭示了不同模型在工具准确性和规划一致性方面的显著差异。ThinkGeo为评估工具增强型LLM如何处理遥感中的空间推理提供了首个全面的测试床。我们的代码和数据集现已公开可用。


> Recent progress in large language models (LLMs) has enabled tool-augmented agents capable of solving complex real-world tasks through step-by-step reasoning. However, existing evaluations often focus on general-purpose or multimodal scenarios, leaving a gap in domain-specific benchmarks that assess tool-use capabilities in complex remote sensing use cases. We present ThinkGeo, an agentic benchmark designed to evaluate LLM-driven agents on remote sensing tasks via structured tool use and multi-step planning. Inspired by tool-interaction paradigms, ThinkGeo includes human-curated queries spanning a wide range of real-world applications such as urban planning, disaster assessment and change analysis, environmental monitoring, transportation analysis, aviation monitoring, recreational infrastructure, and industrial site analysis. Each query is grounded in satellite or aerial imagery and requires agents to reason through a diverse toolset. We implement a ReAct-style interaction loop and evaluate both open and closed-source LLMs (e.g., GPT-4o, Qwen2.5) on 436 structured agentic tasks. The benchmark reports both step-wise execution metrics and final answer correctness. Our analysis reveals notable disparities in tool accuracy and planning consistency across models. ThinkGeo provides the first extensive testbed for evaluating how tool-enabled LLMs handle spatial reasoning in remote sensing. Our code and dataset are publicly available

[Arxiv](https://arxiv.org/abs/2505.23752)