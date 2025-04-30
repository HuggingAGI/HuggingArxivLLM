# 思路追踪：通过将大型语言模型的推理能力蒸馏至小型模型，提升算术问题求解效果

发布时间：2025年04月29日

`LLM应用` `计算语言学`

> Trace-of-Thought: Enhanced Arithmetic Problem Solving via Reasoning Distillation From Large to Small Language Models

# 摘要

> 随着大型语言模型（LLMs）在日常任务中的广泛应用，提示工程一直是计算语言学中的一个热门研究领域，尤其是在需要专业知识的领域，如算术推理。尽管这些LLMs针对多种任务进行了优化，但它们的广泛应用可能对小型团队来说计算和财务成本过高。此外，完全依赖专有闭源模型通常会限制定制化和适应性，这对研究和应用的可扩展性提出了重大挑战。相反，通过利用参数量在70亿以下的开源模型，我们可以在保持资源使用效率的同时，相较于标准提示方法获得显著的改进。为了进一步发展这一理念，我们引入了Trace-of-Thought提示方法，这是一种简单、零样本的提示工程方法，它指导LLMs利用关键问题解决方法创建可观察的子问题，特别设计用于增强算术推理能力。当将这种方法与GPT-4一同应用于开源模型时，我们发现，Trace-of-Thought不仅为问题解决过程提供了新的见解，还在参数量在70亿以下的语言模型中带来了高达125%的性能提升。这一方法凸显了开源倡议在促进人工智能研究民主化和提高高质量计算语言学应用的可访问性方面的潜力。

> As Large Language Models (LLMs) continue to be leveraged for daily tasks, prompt engineering remains an active field of contribution within computational linguistics, particularly in domains requiring specialized knowledge such as arithmetic reasoning. While these LLMs are optimized for a variety of tasks, their exhaustive employment may become computationally or financially cumbersome for small teams. Additionally, complete reliance on proprietary, closed-source models often limits customization and adaptability, posing significant challenges in research and application scalability. Instead, by leveraging open-source models at or below 7 billion parameters, we can optimize our resource usage while still observing remarkable gains over standard prompting approaches. To cultivate this notion, we introduce Trace-of-Thought Prompting, a simple, zero-shot prompt engineering method that instructs LLMs to create observable subproblems using critical problem-solving, specifically designed to enhance arithmetic reasoning capabilities. When applied to open-source models in tandem with GPT-4, we observe that Trace-of-Thought not only allows novel insight into the problem-solving process but also introduces performance gains as large as 125% on language models at or below 7 billion parameters. This approach underscores the potential of open-source initiatives in democratizing AI research and improving the accessibility of high-quality computational linguistics applications.

[Arxiv](https://arxiv.org/abs/2504.20946)