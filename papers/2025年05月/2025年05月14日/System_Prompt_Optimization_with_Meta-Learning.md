# # 基于元学习的系统提示优化

发布时间：2025年05月14日

`LLM理论` `人工智能` `跨领域应用`

> System Prompt Optimization with Meta-Learning

# 摘要

> 大型语言模型 (LLMs) 展现出了非凡的能力，优化其输入提示在最大化其性能方面起着关键作用。然而，尽管 LLM 提示包含任务无关的系统提示和任务特定的用户提示，现有的提示优化工作主要集中在针对特定查询或任务的用户提示上，而对系统提示的关注较少，而优化后的系统提示可以在不同任务和领域中通用。基于此，我们提出了一个新的双层系统提示优化问题，其目标是设计出既稳健于多样化用户提示又可迁移到未见过任务的系统提示。为了解决这一问题，我们随后提出了一种元学习框架，该框架通过在多个数据集上的各种用户提示中优化系统提示，同时以迭代方式更新用户提示，以确保它们之间的协同作用。我们在跨越 5 个不同领域的 14 个未见过的数据集上进行了实验，结果表明我们的方法能够生成有效推广到多样化用户提示的系统提示。此外，我们的研究发现，优化后的系统提示即使面对未见过的任务也能实现快速适应，同时在测试时用户提示上需要更少的优化步骤，同时性能得到提升.

> Large Language Models (LLMs) have shown remarkable capabilities, with optimizing their input prompts playing a pivotal role in maximizing their performance. However, while LLM prompts consist of both the task-agnostic system prompts and task-specific user prompts, existing work on prompt optimization has focused on user prompts specific to individual queries or tasks, and largely overlooked the system prompt that is, once optimized, applicable across different tasks and domains. Motivated by this, we introduce the novel problem of bilevel system prompt optimization, whose objective is to design system prompts that are robust to diverse user prompts and transferable to unseen tasks. To tackle this problem, we then propose a meta-learning framework, which meta-learns the system prompt by optimizing it over various user prompts across multiple datasets, while simultaneously updating the user prompts in an iterative manner to ensure synergy between them. We conduct experiments on 14 unseen datasets spanning 5 different domains, on which we show that our approach produces system prompts that generalize effectively to diverse user prompts. Also, our findings reveal that the optimized system prompt enables rapid adaptation even to unseen tasks, requiring fewer optimization steps for test-time user prompts while achieving improved performance.

[Arxiv](https://arxiv.org/abs/2505.09666)