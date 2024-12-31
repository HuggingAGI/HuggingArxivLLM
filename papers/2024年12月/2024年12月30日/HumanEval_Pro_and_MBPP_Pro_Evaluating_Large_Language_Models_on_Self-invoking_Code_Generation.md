# HumanEval Pro 与 MBPP Pro：针对自调用代码生成对大型语言模型进行评估

发布时间：2024年12月30日

`LLM应用` `代码生成` `语言模型`

> HumanEval Pro and MBPP Pro: Evaluating Large Language Models on Self-invoking Code Generation

# 摘要

> 我们引入了自调用代码生成这一新任务，旨在测评大型语言模型（LLMs）的渐进推理和问题解决能力。在该任务中，模型会遭遇一个基础问题和一个相关且更复杂的问题。它们得先解决基础问题，再利用其解决方案去处理更复杂的问题。此工作有三大关键贡献。其一，我们给出了生成现有基准更具挑战性版本的通用办法，由此产生了三个新基准：HumanEval Pro、MBPP Pro 以及 BigCodeBench-Lite Pro，专门用于评估 LLMs 在自调用代码生成方面的水平。其二，通过对二十个 LLMs 在我们基准上的实验结果加以分析，我们有两个重要发现：（i）大多数 LLMs 在诸如 HumanEval 和 MBPP 这类传统代码生成基准中表现优异，但在自调用任务中的表现欠佳。比如，o1-mini 在 HumanEval 上的 pass@1 达到 96.2％，但在 HumanEval Pro 上仅为 76.2％。（ii）在自调用代码生成任务中，指令调整模型相较于基础模型仅呈现出微小的改进。其三，我们揭示了在我们的评估结果中存在的失败模式类型。所有这些结果都凸显了自调用代码生成任务需要进一步推进，并为未来增强 LLMs 的代码推理能力的研究指明了新方向。

> We introduce self-invoking code generation, a new task designed to evaluate the progressive reasoning and problem-solving capabilities of LLMs. In this task, models are presented with a base problem and a related, more complex problem. They must solve the base problem and then utilize its solution to address the more complex one. This work features three key contributions. First, we propose a general recipe for generating more challenging versions of existing benchmarks, resulting in three new benchmarks: HumanEval Pro, MBPP Pro, and BigCodeBench-Lite Pro, specifically designed to assess LLMs on self-invoking code generation. Second, from the analysis of experimental results over twenty LLMs on our benchmarks, we have two important observations: (i) Most LLMs excel in traditional code generation benchmarks like HumanEval and MBPP, but their performance declines on self-invoking tasks. For example, o1-mini achieves 96.2% pass@1 on HumanEval but only 76.2% on HumanEval Pro. (ii) On self-invoking code generation task, the instruction-tuned models demonstrate only marginal improvements compared to the base models. Third, we disclose the types of failure modes that exist in our evaluation results. All these results underscore the need for further advancements in self-invoking code generation tasks and provide a new direction for future research on enhancing LLMs' code reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2412.21199)