# 图结构规划：探索可并行化的LLM代理调度方法

发布时间：2025年02月20日

`LLM应用` `任务规划` `并行调度`

> Plan-over-Graph: Towards Parallelable LLM Agent Schedule

# 摘要

> 大型语言模型 (LLMs) 在任务规划推理方面表现卓越，但在并行调度领域的挑战仍有待深入探索。本文提出了一种全新的 plan-over-graph 范式：模型首先将现实文本任务分解为可执行子任务并构建抽象任务图，随后理解任务图并生成并行执行计划。为提升处理复杂可扩展任务图的能力，我们设计了自动化可控管道生成合成图，并提出两阶段训练方案。实验结果表明，plan-over-graph 方法显著提升了基于 API 和开源 LLM 的任务性能。通过将复杂任务规范化为图结构，该方法自然支持并行执行，展现了全局效率。代码和数据已开源：https://github.com/zsq259/Plan-over-Graph。

> Large Language Models (LLMs) have demonstrated exceptional abilities in reasoning for task planning. However, challenges remain under-explored for parallel schedules. This paper introduces a novel paradigm, plan-over-graph, in which the model first decomposes a real-life textual task into executable subtasks and constructs an abstract task graph. The model then understands this task graph as input and generates a plan for parallel execution. To enhance the planning capability of complex, scalable graphs, we design an automated and controllable pipeline to generate synthetic graphs and propose a two-stage training scheme. Experimental results show that our plan-over-graph method significantly improves task performance on both API-based LLMs and trainable open-sourced LLMs. By normalizing complex tasks as graphs, our method naturally supports parallel execution, demonstrating global efficiency. The code and data are available at https://github.com/zsq259/Plan-over-Graph.

[Arxiv](https://arxiv.org/abs/2502.14563)