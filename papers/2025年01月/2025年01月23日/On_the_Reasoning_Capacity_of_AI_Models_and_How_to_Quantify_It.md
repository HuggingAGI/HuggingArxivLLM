# AI模型的推理能力及其量化方法

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的推理能力及其内在机制，提出了新的评估方法和理论框架（如概率混合模型和信息论一致性分析），以深入理解模型的行为和决策过程。这些内容属于对LLM的理论分析和理解，因此归类为LLM理论。` `人工智能` `认知科学`

> On the Reasoning Capacity of AI Models and How to Quantify It

# 摘要

> # 摘要
最近大型语言模型（LLMs）的进展引发了关于其推理能力本质的激烈讨论。尽管在GPQA和MMLU等基准测试中表现优异，这些模型在复杂推理任务中仍显不足，凸显了更严格评估方法的必要性。我们提出了一种新颖的现象学方法，超越传统准确性指标，深入探究模型行为的潜在机制，建立了一个可能广泛影响AI系统分析与理解的框架。以多项选择推理任务中的位置偏差为例，我们展示了系统扰动如何揭示模型决策的核心机制。为分析这些行为，我们开发了两个互补的现象学模型：概率混合模型（PMM），将模型响应分解为推理、记忆和猜测成分；以及信息论一致性（ITC）分析，量化模型置信度与策略选择的关系。通过在推理基准上的受控实验，我们发现当前模型在真正推理方面仍面临挑战，表面的成功往往依赖于记忆与模式匹配的复杂组合，而非真正的逻辑推理。更重要的是，我们证明准确性往往夸大了模型的推理能力，模型行为可通过认知策略相空间中的潜在机制来表征，揭示了模型在响应查询时如何动态平衡不同策略。这一框架为实际部署提供了定量标准，允许应用程序基于策略分布而非总体性能指标设定可靠性阈值。

> Recent advances in Large Language Models (LLMs) have intensified the debate surrounding the fundamental nature of their reasoning capabilities. While achieving high performance on benchmarks such as GPQA and MMLU, these models exhibit limitations in more complex reasoning tasks, highlighting the need for more rigorous evaluation methodologies. We propose a novel phenomenological approach that goes beyond traditional accuracy metrics to probe the underlying mechanisms of model behavior, establishing a framework that could broadly impact how we analyze and understand AI systems. Using positional bias in multiple-choice reasoning tasks as a case study, we demonstrate how systematic perturbations can reveal fundamental aspects of model decision-making. To analyze these behaviors, we develop two complementary phenomenological models: a Probabilistic Mixture Model (PMM) that decomposes model responses into reasoning, memorization, and guessing components and an Information-Theoretic Consistency (ITC) analysis that quantifies the relationship between model confidence and strategy selection. Through controlled experiments on reasoning benchmarks, we show that true reasoning remains challenging for current models, with apparent success often relying on sophisticated combinations of memorization and pattern matching rather than genuine logical deduction. More fundamentally, we demonstrate that accuracy alone often overstates a model's reasoning abilities, as model behavior can be characterized through underlying mechanisms in the phase space of cognitive strategies, revealing how models dynamically balance different approaches when responding to queries. This framework enables quantitative criteria for real-world deployments, allowing applications to specify reliability thresholds based on strategy distributions rather than aggregate performance metrics.

[Arxiv](https://arxiv.org/abs/2501.13833)