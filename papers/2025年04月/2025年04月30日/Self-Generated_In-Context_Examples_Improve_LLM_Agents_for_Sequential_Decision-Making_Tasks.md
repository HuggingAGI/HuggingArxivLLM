# 自动生成的上下文示例优化LLM代理在序列决策任务中的表现

发布时间：2025年04月30日

`Agent` `人工智能` `自动化决策`

> Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks

# 摘要

> 改进大型语言模型（LLM）代理在序列决策任务中的许多方法依赖于任务特定的知识工程，例如提示调优、精选的上下文示例，或定制化的观察与动作空间。通过这些方法，代理性能随着投入的知识工程质量和数量的提升而提高。然而，我们研究了LLM代理如何通过从自身在相似任务中的成功经验中学习，自动提升其性能。我们不再依赖任务特定的知识工程，而是专注于构建和优化一个自动生成的例子数据库。我们证明，即使是在训练任务中对成功轨迹进行简单的累积，也能在三个基准测试中提升测试性能：ALFWorld（从73%提升到89%）、Wordcraft（从55%提升到64%）和InterCode-SQL（从75%提升到79%）——这一表现与初始代理在每项任务中被允许尝试两到三次时的性能相当。随后，我们引入了两个扩展：（1）通过基于种群的训练在数据库级别选择高性能的例子集合；（2）在示例级别选择保留个体轨迹，基于它们作为上下文示例的实际效用。这些扩展进一步提升了性能，在ALFWorld中达到了91%——与采用任务特定组件和提示的更复杂方法相媲美。我们的结果表明，自动轨迹数据库的构建为劳动密集型知识工程提供了一个有吸引力的替代方案。

> Many methods for improving Large Language Model (LLM) agents for sequential decision-making tasks depend on task-specific knowledge engineering--such as prompt tuning, curated in-context examples, or customized observation and action spaces. Using these approaches, agent performance improves with the quality or amount of knowledge engineering invested. Instead, we investigate how LLM agents can automatically improve their performance by learning in-context from their own successful experiences on similar tasks. Rather than relying on task-specific knowledge engineering, we focus on constructing and refining a database of self-generated examples. We demonstrate that even a naive accumulation of successful trajectories across training tasks boosts test performance on three benchmarks: ALFWorld (73% to 89%), Wordcraft (55% to 64%), and InterCode-SQL (75% to 79%)--matching the performance the initial agent achieves if allowed two to three attempts per task. We then introduce two extensions: (1) database-level selection through population-based training to identify high-performing example collections, and (2) exemplar-level selection that retains individual trajectories based on their empirical utility as in-context examples. These extensions further enhance performance, achieving 91% on ALFWorld--matching more complex approaches that employ task-specific components and prompts. Our results demonstrate that automatic trajectory database construction offers a compelling alternative to labor-intensive knowledge engineering.

[Arxiv](https://arxiv.org/abs/2505.00234)