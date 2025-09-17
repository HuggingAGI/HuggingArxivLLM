# 偏好约束推理：多对一匹配市场的语言模型基准

发布时间：2025年09月16日

`LLM应用` `教育科技`

> Reasoning with Preference Constraints: A Benchmark for Language Models in Many-to-One Matching Markets

# 摘要

> 大型语言模型（LLMs）在推理领域的最新进展，已让其在复杂数学任务（包括组合优化）中展现出卓越性能。思维链（Chain-of-Thought）与上下文学习（In-Context Learning）等技术进一步强化了这一能力，使LLMs成为包括非专家在内的广大用户手中既强大又易用的工具。然而，将LLMs应用于匹配问题（需在偏好与结构约束下推理）的研究仍较为匮乏。为此，我们构建了一个包含369个大学录取问题实例的全新基准——大学录取问题是带偏好匹配问题的经典案例，旨在从可行性、稳定性和最优性三个关键维度评估LLMs。我们利用该基准对多个开源LLMs展开评估，结果发现：尽管LLMs能满足部分约束条件，却难以持续符合所有评估标准；推理型LLMs（如QwQ和GPT-oss）显著优于传统模型（如Llama、Qwen、Mistral，此处定义为未配备专用推理机制的模型）；LLMs对测试的多种提示策略（包括思维链、上下文学习和基于角色的提示）反应各异，没有一种策略能始终保持最佳性能；带自动生成反馈的迭代提示性能并非单调变化——可能在早期达到峰值，随后在后续尝试中显著下降。总体而言，这项研究为模型推理性能及提示策略在带偏好约束的组合优化问题中的有效性提供了新见解。

> Recent advances in reasoning with large language models (LLMs) have demonstrated strong performance on complex mathematical tasks, including combinatorial optimization. Techniques such as Chain-of-Thought and In-Context Learning have further enhanced this capability, making LLMs both powerful and accessible tools for a wide range of users, including non-experts. However, applying LLMs to matching problems, which require reasoning under preferential and structural constraints, remains underexplored. To address this gap, we introduce a novel benchmark of 369 instances of the College Admission Problem, a canonical example of a matching problem with preferences, to evaluate LLMs across key dimensions: feasibility, stability, and optimality. We employ this benchmark to assess the performance of several open-weight LLMs. Our results first reveal that while LLMs can satisfy certain constraints, they struggle to meet all evaluation criteria consistently. They also show that reasoning LLMs, like QwQ and GPT-oss, significantly outperform traditional models such as Llama, Qwen or Mistral, defined here as models used without any dedicated reasoning mechanisms. Moreover, we observed that LLMs reacted differently to the various prompting strategies tested, which include Chain-of-Thought, In-Context Learning and role-based prompting, with no prompt consistently offering the best performance. Finally, we report the performances from iterative prompting with auto-generated feedback and show that they are not monotonic; they can peak early and then significantly decline in later attempts. Overall, this work offers a new perspective on model reasoning performance and the effectiveness of prompting strategies in combinatorial optimization problems with preferential constraints.

[Arxiv](https://arxiv.org/abs/2509.13131)