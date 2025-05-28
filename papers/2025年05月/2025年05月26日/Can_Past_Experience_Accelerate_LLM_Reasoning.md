# # 经验能否助力LLM推理加速？

发布时间：2025年05月26日

`LLM理论` `人工智能` `计算机科学`

> Can Past Experience Accelerate LLM Reasoning?

# 摘要

> 通常而言，增加计算资源可以提升大型语言模型（LLMs）的推理效果，但也带来了推理时间的增加。然而，人类却能通过经验积累和不断接触任务来实现更快、更好的表现。因此，本研究提出了一个关键问题：大型语言模型是否也能通过反复接触相关任务来实现推理加速？如果可以，又该如何实现？为了解答这一问题，我们首先系统性地从任务相关性和计算预算两个维度对LLM推理加速问题进行了形式化定义。随后，我们提出了SpeedupLLM框架，这一基于自适应计算分配和内存机制的理论保证框架，用于实现和评估这种推理加速行为。我们进一步通过全面实验，评估了在不同问题相似性水平、内存方法和推理方法下的推理加速表现。实验结果表明，大型语言模型通常能够利用历史经验加快推理速度，当配备合适的内存和推理方法时，计算成本最多可降低56%。

> Allocating more compute to large language models (LLMs) reasoning has generally been demonstrated to improve their effectiveness, but also results in increased inference time. In contrast, humans can perform tasks faster and better with increased experience and exposure. Hence, this paper aims to investigate the question: Can LLMs also become faster at reasoning through recurrent exposure on relevant tasks, and if so, how can it be achieved? To address these questions, we first formalize the problem setting of LLM reasoning speedup systematically in the dimensions of task relevancy and compute budget calculation. We then propose SpeedupLLM, a theoretically guaranteed framework to implement and benchmark such reasoning speedup behaviour based on adaptive compute allocation and memory mechanisms. We further conduct comprehensive experiments to benchmark such behaviour across different question similarity levels, memory methods, and reasoning methods. Results show that LLMs can generally reason faster with past experience, achieving up to a 56% reduction in compute cost when equipped with appropriate memory and reasoning methods.

[Arxiv](https://arxiv.org/abs/2505.20643)