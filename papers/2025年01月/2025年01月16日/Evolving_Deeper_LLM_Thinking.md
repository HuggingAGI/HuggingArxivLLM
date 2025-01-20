# 深入演化LLM的思考能力

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论了如何通过进化搜索策略（Mind Evolution方法）来扩展大型语言模型（LLM）在推理时间内的计算能力。该方法利用LLM生成、重组和优化候选响应，从而在自然语言规划任务中取得了显著的效果。虽然涉及到推理策略的优化，但其核心仍然是基于LLM的应用，因此归类为“LLM应用”更为合适。` `规划系统`

> Evolving Deeper LLM Thinking

# 摘要

> 我们研究了一种进化搜索策略，用于扩展大型语言模型的推理时间计算。提出的Mind Evolution方法利用语言模型生成、重组和优化候选响应，避免了在解决方案评估器可用时形式化底层推理问题的需求。在控制推理成本的前提下，Mind Evolution在自然语言规划任务中显著优于Best-of-N和Sequential Revision等推理策略。在TravelPlanner和Natural Plan基准测试中，Mind Evolution使用Gemini 1.5 Pro成功解决了超过98%的问题实例，且无需形式化求解器。

> We explore an evolutionary search strategy for scaling inference time compute in Large Language Models. The proposed approach, Mind Evolution, uses a language model to generate, recombine and refine candidate responses. The proposed approach avoids the need to formalize the underlying inference problem whenever a solution evaluator is available. Controlling for inference cost, we find that Mind Evolution significantly outperforms other inference strategies such as Best-of-N and Sequential Revision in natural language planning tasks. In the TravelPlanner and Natural Plan benchmarks, Mind Evolution solves more than 98% of the problem instances using Gemini 1.5 Pro without the use of a formal solver.

[Arxiv](https://arxiv.org/abs/2501.09891)