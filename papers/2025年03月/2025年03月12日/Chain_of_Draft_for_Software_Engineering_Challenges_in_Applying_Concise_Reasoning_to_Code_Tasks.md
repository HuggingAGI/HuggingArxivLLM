# 软件工程草案链：在代码任务中运用简洁推理的挑战

发布时间：2025年03月12日

`LLM应用` `软件工程` `开发工具`

> Chain of Draft for Software Engineering: Challenges in Applying Concise Reasoning to Code Tasks

# 摘要

> 大型语言模型（LLMs）已成为软件开发的重要工具，但处理复杂代码任务时往往面临高延迟和高昂成本的挑战。本研究将“草案链”（Chain of Draft, CoD）方法引入软件工程领域，设计并评估了多种专为代码任务优化的CoD变体。通过对SWE-bench基准测试中的全部300个样本进行综合实验，我们发现所有CoD变体的token使用量均显著低于“思考链”（Chain of Thought, CoT），其中基线CoD最为高效，仅使用了CoT 55.4%的token。这一改进带来了约45%的处理时间及API成本降低，但与原CoD论文中数学推理任务所报告的7.6%相比仍存在差距。这种差异源于软件任务的复杂性和上下文依赖性，需要更详细的推理以保持解决方案质量。我们的多维度质量评估显示，CoD变体在正确性、兼容性和可维护性等关键指标上保持了CoT 90%以上的代码质量，使其成为在效率至关重要的真实开发场景中切实可行的替代方案。本研究不仅展示了领域特定特征对提示策略有效性的影响，还为软件工程应用中平衡效率与解决方案质量提供了框架。我们的发现为基于LLM的开发工作流优化提供了实用指导，建议根据项目需求选择合适的提示策略。

> Large language models (LLMs) have become vital tools for software development, but they often require verbose intermediate reasoning for complex code tasks, leading to high latency and costs. This research extends the Chain of Draft (CoD) method to software engineering, designing and evaluating multiple CoD variants tailored for code tasks. Through comprehensive experiments on all 300 samples from the SWE-bench benchmark, we found that all CoD variants used significantly fewer tokens than Chain of Thought (CoT), with Baseline CoD being most efficient at 55.4% of CoT's tokens. While this represents substantial efficiency gains - translating to approximately 45% reduction in processing time and API costs - it differs from the extreme 7.6% reported in the original CoD paper for mathematical reasoning. This difference stems from the inherent complexity and context-dependency of software tasks, which require more detailed reasoning to maintain solution quality. Our multi-dimensional quality assessment revealed that CoD variants maintain over 90% of CoT's code quality across key metrics including correctness, compatibility, and maintainability, making them practical alternatives for real-world development scenarios where efficiency matters. This research demonstrates how domain-specific characteristics influence prompting strategy effectiveness and provides a framework for balancing efficiency with solution quality in software engineering applications. Our findings offer practical guidance for optimizing LLM-based development workflows through appropriate prompting strategy selection based on project requirements.

[Arxiv](https://arxiv.org/abs/2506.10987)