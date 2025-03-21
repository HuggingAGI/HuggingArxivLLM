# # 语言的灯塔：通过基于反馈的改进优化LLM智能体

发布时间：2025年03月20日

`Agent` `智能代理` `反馈机制`

> The Lighthouse of Language: Enhancing LLM Agents via Critique-Guided Improvement

# 摘要

> 大型语言模型（LLMs）已从简单的文本助手演变为具备规划、推理和自我优化能力的智能代理。尽管数值奖励信号和验证器能有效评估动作，但它们提供的上下文指导有限。相比之下，自然语言反馈更能发挥LLMs的生成优势，提供更丰富、更具操作性的建议。然而，基于LLM的代理在解析和应用这些反馈时仍面临挑战。为此，我们提出了一种名为“基于反馈的改进框架”（CGI）的创新双模型架构，包含一个探索环境的演员模型和一个生成详细自然语言反馈的评论模型。通过训练评论模型生成细致入微的评估和可操作的改进建议，并指导演员模型有效利用这些反馈，我们的方法不仅能够更稳健地探索替代策略，还能有效避免陷入局部最优。在三个交互式环境中的实验表明，CGI显著超越现有基准模型。值得注意的是，即使是一个小型评论模型，其反馈质量也超越了GPT-4。最终，我们的演员模型达到了当前最优的性能水平，充分展现了明确迭代指导在提升基于LLM的代理决策能力方面的强大潜力。

> Large language models (LLMs) have recently transformed from text-based assistants to autonomous agents capable of planning, reasoning, and iteratively improving their actions. While numerical reward signals and verifiers can effectively rank candidate actions, they often provide limited contextual guidance. In contrast, natural language feedback better aligns with the generative capabilities of LLMs, providing richer and more actionable suggestions. However, parsing and implementing this feedback effectively can be challenging for LLM-based agents. In this work, we introduce Critique-Guided Improvement (CGI), a novel two-player framework, comprising an actor model that explores an environment and a critic model that generates detailed nature language feedback. By training the critic to produce fine-grained assessments and actionable revisions, and the actor to utilize these critiques, our approach promotes more robust exploration of alternative strategies while avoiding local optima. Experiments in three interactive environments show that CGI outperforms existing baselines by a substantial margin. Notably, even a small critic model surpasses GPT-4 in feedback quality. The resulting actor achieves state-of-the-art performance, demonstrating the power of explicit iterative guidance to enhance decision-making in LLM-based agents.

[Arxiv](https://arxiv.org/abs/2503.16024)