# WSI-Agents：专为多模态全切片图像分析设计的协作多智能体系统

发布时间：2025年07月19日

`Agent` `病理学`

> WSI-Agents: A Collaborative Multi-Agent System for Multi-Modal Whole Slide Image Analysis

# 摘要

> 全幻灯片图像（WSIs）在数字病理学中具有重要意义，支持十亿像素级的组织分析，覆盖多种病理任务。尽管多模态大语言模型（MLLMs）的进步使得通过自然语言实现多任务WSI分析成为可能，但其表现往往逊色于专门模型。协作式多智能体系统在医疗领域通用性和准确性的平衡中展现出潜力，但在病理学领域尚未得到充分探索。

为解决这些问题，我们提出WSI-Agents，一种全新的协作式多智能体系统，专为多模态WSI分析设计。该系统通过整合专业功能智能体，并结合强大的任务分配与验证机制，从以下三方面优化了特定任务的准确性和多任务的通用性：

1. **任务分配模块**：利用包含基于补丁和全幻灯片级别的MLLMs模型集合，将任务精准分配给专家智能体。
2. **验证机制**：通过内部一致性检查以及基于病理知识库和领域特定模型的外部验证，确保结果的准确性。
3. **汇总模块**：生成最终总结并附带可视化解释图，便于结果的直观理解。

在多模态WSI基准测试中的广泛实验表明，WSI-Agents在各类任务中均优于当前的WSI MLLMs和医疗智能体框架，展现了其显著的优越性。

> Whole slide images (WSIs) are vital in digital pathology, enabling gigapixel tissue analysis across various pathological tasks. While recent advancements in multi-modal large language models (MLLMs) allow multi-task WSI analysis through natural language, they often underperform compared to task-specific models. Collaborative multi-agent systems have emerged as a promising solution to balance versatility and accuracy in healthcare, yet their potential remains underexplored in pathology-specific domains. To address these issues, we propose WSI-Agents, a novel collaborative multi-agent system for multi-modal WSI analysis. WSI-Agents integrates specialized functional agents with robust task allocation and verification mechanisms to enhance both task-specific accuracy and multi-task versatility through three components: (1) a task allocation module assigning tasks to expert agents using a model zoo of patch and WSI level MLLMs, (2) a verification mechanism ensuring accuracy through internal consistency checks and external validation using pathology knowledge bases and domain-specific models, and (3) a summary module synthesizing the final summary with visual interpretation maps. Extensive experiments on multi-modal WSI benchmarks show WSI-Agents's superiority to current WSI MLLMs and medical agent frameworks across diverse tasks.

[Arxiv](https://arxiv.org/abs/2507.14680)