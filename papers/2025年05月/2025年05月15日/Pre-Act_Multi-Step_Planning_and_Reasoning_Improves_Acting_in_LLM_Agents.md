# 预执行：多步骤规划与推理显著提升LLM智能体的行动能力

发布时间：2025年05月15日

`Agent` `智能体系统` `人工智能`

> Pre-Act: Multi-Step Planning and Reasoning Improves Acting in LLM Agents

# 摘要

> 大型语言模型 (LLMs) 中的 ReAct（推理+行动）能力已成为现代智能体系统的核心。近期的 LLMs，如 DeepSeek-R1 和 OpenAI o1/o3，通过生成充足的中间标记来强调推理过程，从而在生成最终输出前构建坚实的前提。本文中，我们提出了一种名为 Pre-Act 的创新方法，通过为用户输入创建详细的推理过程和多步骤执行计划，显著提升了智能体的性能。该计划在每一步执行后逐步整合先前步骤和工具输出，持续优化自身直至获得最终响应。我们的方法适用于对话型和非对话型智能体。为了全面评估任务导向型智能体的性能，我们设计了一种两级评估框架：(1) 轮次级别和 (2) 端到端。基于五种模型的平均评估结果，Pre-Act 在 Almita 数据集上的行动召回率比 ReAct 高出 70%。尽管此方法对大型模型有效，但对于实际应用中至关重要的小型模型（其中延迟和成本是关键限制因素），它们通常难以处理智能体系统所需的复杂推理任务。为了解决这一问题，我们使用提出的 Pre-Act 方法对 Llama 3.1（8B 和 70B）等较小模型进行微调。实验结果表明，在 Almita（领域外）数据集上，微调后的 70B 模型在行动准确性（轮次级别）和目标完成率（端到端）方面分别提升了 69.5% 和 28%，超越了 GPT-4 的表现。


> The ReAct (Reasoning + Action) capability in large language models (LLMs) has become the foundation of modern agentic systems. Recent LLMs, such as DeepSeek-R1 and OpenAI o1/o3, exemplify this by emphasizing reasoning through the generation of ample intermediate tokens, which help build a strong premise before producing the final output tokens. In this paper, we introduce Pre-Act, a novel approach that enhances the agent's performance by creating a multi-step execution plan along with the detailed reasoning for the given user input. This plan incrementally incorporates previous steps and tool outputs, refining itself after each step execution until the final response is obtained. Our approach is applicable to both conversational and non-conversational agents. To measure the performance of task-oriented agents comprehensively, we propose a two-level evaluation framework: (1) turn level and (2) end-to-end. Our turn-level evaluation, averaged across five models, shows that our approach, Pre-Act, outperforms ReAct by 70% in Action Recall on the Almita dataset. While this approach is effective for larger models, smaller models crucial for practical applications, where latency and cost are key constraints, often struggle with complex reasoning tasks required for agentic systems. To address this limitation, we fine-tune relatively small models such as Llama 3.1 (8B & 70B) using the proposed Pre-Act approach. Our experiments show that the fine-tuned 70B model outperforms GPT-4, achieving a 69.5% improvement in action accuracy (turn-level) and a 28% improvement in goal completion rate (end-to-end) on the Almita (out-of-domain) dataset.

[Arxiv](https://arxiv.org/abs/2505.09970)