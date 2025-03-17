# 智能体场景下的大推理模型：探析推理能力的必要性

发布时间：2025年03月14日

`LLM应用` `人工智能` `机器学习`

> Large Reasoning Models in Agent Scenarios: Exploring the Necessity of Reasoning Capabilities

# 摘要

> 大型推理模型（LRMs）的崛起标志着计算推理领域的重要转折。这一进展打破了传统以执行为导向的大型语言模型（LLMs）为基础的代理框架。为了深入理解这一变革，我们提出了LaRMA框架，该框架涵盖了工具使用、计划设计和问题解决三大领域的九项任务，并通过三个顶级LLMs（如Claude3.5-sonnet）和五个领先LRMs（如DeepSeek-R1）进行了全面评估。我们的研究解答了四个核心问题：在计划设计等需要深度推理的任务中，LRMs超越了LLMs，通过迭代反思实现更优结果；在工具使用等以执行为导向的任务中，LLMs表现更佳，注重效率；将LLMs作为执行者与LRMs作为反思者的混合配置（如LLM-LRM组合）能够优化代理性能，将执行速度与推理深度相结合；同时，LRMs增强的推理能力带来了更高的计算成本、更长的处理时间以及行为上的挑战，包括过度思考和忽视事实的倾向。这项研究不仅揭示了LRMs在深度思考与过度思考之间平衡的内在机制，更为未来代理设计的改进奠定了关键基础，推动了人工智能技术的持续进步。

> The rise of Large Reasoning Models (LRMs) signifies a paradigm shift toward advanced computational reasoning. Yet, this progress disrupts traditional agent frameworks, traditionally anchored by execution-oriented Large Language Models (LLMs). To explore this transformation, we propose the LaRMA framework, encompassing nine tasks across Tool Usage, Plan Design, and Problem Solving, assessed with three top LLMs (e.g., Claude3.5-sonnet) and five leading LRMs (e.g., DeepSeek-R1). Our findings address four research questions: LRMs surpass LLMs in reasoning-intensive tasks like Plan Design, leveraging iterative reflection for superior outcomes; LLMs excel in execution-driven tasks such as Tool Usage, prioritizing efficiency; hybrid LLM-LRM configurations, pairing LLMs as actors with LRMs as reflectors, optimize agent performance by blending execution speed with reasoning depth; and LRMs' enhanced reasoning incurs higher computational costs, prolonged processing, and behavioral challenges, including overthinking and fact-ignoring tendencies. This study fosters deeper inquiry into LRMs' balance of deep thinking and overthinking, laying a critical foundation for future agent design advancements.

[Arxiv](https://arxiv.org/abs/2503.11074)