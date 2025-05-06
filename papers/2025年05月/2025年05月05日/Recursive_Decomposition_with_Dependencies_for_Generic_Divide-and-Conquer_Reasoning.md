# # 递归分解结合依赖关系，助力通用分而治之推理

发布时间：2025年05月05日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在推理任务中的应用，并提出了一种新的方法（RDD）来改进其性能和效率。该方法减少了对额外监督的需求，并提升了处理复杂问题的能力，属于LLM的应用层面。`

> Recursive Decomposition with Dependencies for Generic Divide-and-Conquer Reasoning

# 摘要

> 推理任务在科学和工程领域具有重要地位。尽管大型语言模型（LLMs）借助思维链和从简到繁的提示策略在推理任务中取得了一定进展，但这些方法在处理复杂问题时仍存在性能和执行时间上的局限。此外，这些方法通常需要为每个新任务提供额外监督，例如上下文示例。在本研究中，我们提出了基于依赖关系的递归分解（RDD），这是一种比传统方法所需监督更少的可扩展分而治之方法，能够直接应用于新的问题类别，即使缺乏特定任务指导。RDD支持子任务依赖，可按顺序执行子任务，并具备错误恢复机制，能够修正之前步骤中的错误。我们在两个包含六个难度级别的基准数据集上进行了评估，并在两种上下文设置下测试：一种包含任务特定示例，另一种不包含。实验结果表明，随着任务复杂度的增加，RDD在计算资源相当的设置下优于其他方法，同时计算效率也更高。


> Reasoning tasks are crucial in many domains, especially in science and engineering. Although large language models (LLMs) have made progress in reasoning tasks using techniques such as chain-of-thought and least-to-most prompting, these approaches still do not effectively scale to complex problems in either their performance or execution time. Moreover, they often require additional supervision for each new task, such as in-context examples. In this work, we introduce Recursive Decomposition with Dependencies (RDD), a scalable divide-and-conquer method for solving reasoning problems that requires less supervision than prior approaches. Our method can be directly applied to a new problem class even in the absence of any task-specific guidance. Furthermore, RDD supports sub-task dependencies, allowing for ordered execution of sub-tasks, as well as an error recovery mechanism that can correct mistakes made in previous steps. We evaluate our approach on two benchmarks with six difficulty levels each and in two in-context settings: one with task-specific examples and one without. Our results demonstrate that RDD outperforms other methods in a compute-matched setting as task complexity increases, while also being more computationally efficient.

[Arxiv](https://arxiv.org/abs/2505.02576)