# P3：提示语推动提示工程的发展

发布时间：2025年07月21日

`LLM理论`

> P3: Prompts Promote Prompting

# 摘要

> 当前大型语言模型（LLM）应用通常采用多组件提示词，包括系统提示和用户提示，来引导模型行为。尽管近期研究已展示单独优化系统或用户提示的有效性，但这些单方面方法常因组件间的相互依赖性导致次优结果。本研究中，我们提出了一种名为P3的新自改进框架，通过迭代过程同时优化系统和用户提示。进一步利用离线优化后的提示进行基于查询依赖的提示优化，以促进在线提示。在通用任务（如Arena-hard和Alpaca-eval）及推理任务（如GSM8K和GPQA）上的广泛实验表明，P3在自动提示优化领域实现了卓越性能。我们的结果突显了整体优化策略在提升LLM跨领域性能中的有效性。


> Current large language model (LLM) applications often employ multi-component prompts, comprising both system and user prompts, to guide model behaviors. While recent advancements have demonstrated the efficacy of automatically optimizing either the system or user prompt to boost performance, such unilateral approaches often yield suboptimal outcomes due to the interdependent nature of these components. In this work, we introduce P3, a novel self-improvement framework that concurrently optimizes both system and user prompts through an iterative process. The offline optimized prompts are further leveraged to promote online prompting by performing query-dependent prompt optimization. Extensive experiments on general tasks (e.g., Arena-hard and Alpaca-eval) and reasoning tasks (e.g., GSM8K and GPQA) demonstrate that P3 achieves superior performance in the realm of automatic prompt optimization. Our results highlight the effectiveness of a holistic optimization strategy in enhancing LLM performance across diverse domains.

[Arxiv](https://arxiv.org/abs/2507.15675)