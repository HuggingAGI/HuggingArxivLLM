# EVALOOP：从自洽性视角评估 LLM 编程能力的鲁棒性

发布时间：2025年05月17日

`LLM应用` `软件工程`

> EVALOOP: Assessing LLM Robustness in Programming from a Self-consistency Perspective

# 摘要

> 评估大型语言模型（LLMs）的编程能力对于其在软件工程中的有效应用至关重要。然而，当前的评估方法主要侧重于在静态基准上生成代码的准确性，忽视了模型在编程任务中的鲁棒性这一关键方面。尽管对抗性攻击为模型鲁棒性提供了见解，但其有效性有限，且评估可能受到限制。目前针对鲁棒性评估的对抗性攻击方法结果不一致，难以在不同LLMs之间提供统一的评估。

我们引入了EVALOOP，一个新颖的评估框架，从自洽性角度评估鲁棒性，即利用流行软件工程任务中固有的自然二重性，例如代码生成和代码总结。EVALOOP启动了一个自我包含的反馈循环：LLM从输入（例如自然语言规范）生成输出（例如代码），然后将生成的输出作为输入来生成新的输出（例如将代码总结为新的规范）。EVALOOP重复此过程以评估每个循环中EVALOOP的有效性。这种循环策略内在地评估了鲁棒性，无需依赖任何外部攻击设置，并提供了一个统一的指标来评估LLMs在编程中的鲁棒性。

我们对16个著名的LLMs（例如GPT-4.1，O4-mini）进行了EVALOOP评估，发现EVALOOP通常在十次循环内使pass@1性能绝对下降5.01%-19.31%。有趣的是，鲁棒性并不总是与初始性能（即一次性查询）一致；例如，GPT-3.5-Turbo尽管在代码生成方面优于DeepSeek-V2，但在重复评估循环中表现出较低的鲁棒性。


> Assessing the programming capabilities of Large Language Models (LLMs) is crucial for their effective use in software engineering. Current evaluations, however, predominantly measure the accuracy of generated code on static benchmarks, neglecting the critical aspect of model robustness during programming tasks. While adversarial attacks offer insights on model robustness, their effectiveness is limited and evaluation could be constrained. Current adversarial attack methods for robustness evaluation yield inconsistent results, struggling to provide a unified evaluation across different LLMs. We introduce EVALOOP, a novel assessment framework that evaluate the robustness from a self-consistency perspective, i.e., leveraging the natural duality inherent in popular software engineering tasks, e.g., code generation and code summarization. EVALOOP initiates a self-contained feedback loop: an LLM generates output (e.g., code) from an input (e.g., natural language specification), and then use the generated output as the input to produce a new output (e.g., summarizes that code into a new specification). EVALOOP repeats the process to assess the effectiveness of EVALOOP in each loop. This cyclical strategy intrinsically evaluates robustness without rely on any external attack setups, providing a unified metric to evaluate LLMs' robustness in programming. We evaluate 16 prominent LLMs (e.g., GPT-4.1, O4-mini) on EVALOOP and found that EVALOOP typically induces a 5.01%-19.31% absolute drop in pass@1 performance within ten loops. Intriguingly, robustness does not always align with initial performance (i.e., one-time query); for instance, GPT-3.5-Turbo, despite superior initial code generation compared to DeepSeek-V2, demonstrated lower robustness over repeated evaluation loop.

[Arxiv](https://arxiv.org/abs/2505.12185)