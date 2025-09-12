# 边际效益递减的错觉：评估大型语言模型的长程执行能力

发布时间：2025年09月11日

`LLM理论` `基础理论`

> The Illusion of Diminishing Returns: Measuring Long Horizon Execution in LLMs

# 摘要

> 大型语言模型（LLMs）的持续扩展是否会导致边际收益递减？现实价值往往取决于智能体能够完成的任务长度。我们的研究从一个简单却反直觉的发现切入：单步准确性的边际增益，会复合成模型可成功完成任务长度的指数级增长。接着我们提出，当简单任务被拉长时LLMs的失败，并非因为推理能力不足，而是执行过程中的失误。为此，我们建议通过明确提供解决长程任务所需的知识和计划，来对执行能力进行单独评估。结果显示，即便小型模型的单轮准确率达到100%，更大的模型仍能正确执行显著更多的轮次。我们还观察到，模型的每步准确率会随着步骤增多而下降。这不仅是长上下文限制的问题——更有趣的是，我们发现了一种自条件效应：当上下文中包含模型先前轮次的错误时，其后续犯错概率会升高。而单纯扩大模型规模并不能缓解这种自条件效应。相比之下，近期的思维模型不会产生自条件效应，且能在单轮中执行长得多的任务。最后，我们通过测试前沿思维模型在单轮中可执行的任务长度来进行基准评估。总体而言，通过聚焦执行能力，我们希望厘清关于LLMs为何能解决复杂推理问题，却在简单任务变长时屡屡失手的争议，并强调扩大模型规模和增加顺序测试时计算量对长程任务的巨大价值。

> Does continued scaling of large language models (LLMs) yield diminishing returns? Real-world value often stems from the length of task an agent can complete. We start this work by observing the simple but counterintuitive fact that marginal gains in single-step accuracy can compound into exponential improvements in the length of a task a model can successfully complete. Then, we argue that failures of LLMs when simple tasks are made longer arise from mistakes in execution, rather than an inability to reason. We propose isolating execution capability, by explicitly providing the knowledge and plan needed to solve a long-horizon task. We find that larger models can correctly execute significantly more turns even when small models have 100\% single-turn accuracy. We observe that the per-step accuracy of models degrades as the number of steps increases. This is not just due to long-context limitations -- curiously, we observe a self-conditioning effect -- models become more likely to make mistakes when the context contains their errors from prior turns. Self-conditioning does not reduce by just scaling the model size. In contrast, recent thinking models do not self-condition, and can also execute much longer tasks in a single turn. We conclude by benchmarking frontier thinking models on the length of task they can execute in a single turn. Overall, by focusing on the ability to execute, we hope to reconcile debates on how LLMs can solve complex reasoning problems yet fail at simple tasks when made longer, and highlight the massive benefits of scaling model size and sequential test-time compute for long-horizon tasks.

[Arxiv](https://arxiv.org/abs/2509.09677)