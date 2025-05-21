# 日志增强生成技术：利用可重用计算提升测试时推理能力

发布时间：2025年05月20日

`Agent` `智能体系统` `知识密集型领域`

> Log-Augmented Generation: Scaling Test-Time Reasoning with Reusable Computation

# 摘要

> 尽管人类能够自然地从过去的经验中学习和适应，但大型语言模型（LLMs）及其智能体版本在保留先前任务推理能力并将其应用到未来上下文中时却显得力不从心。为了解决这一问题，我们提出了一种名为基于日志增强生成（LAG）的新型框架。该框架能够在测试时直接复用过去日志中的先前计算和推理，从而增强模型从以往任务中学习的能力，并在新的、未见过的挑战上表现得更好，同时保持系统的高效性和可扩展性。具体而言，我们的系统使用键值（KV）缓存来表示任务日志，完整编码了先前任务的推理上下文，同时仅存储选定子集的KV缓存。当出现新任务时，LAG从相关日志中检索KV值以增强生成。与基于反思的记忆机制不同，我们的方法无需额外的知识提取或蒸馏步骤，而是直接复用先前的推理和计算。我们的方法还超越了现有的KV缓存技术，这些技术主要侧重于提高效率，而非提升准确性。在知识和推理密集型数据集上的实验表明，我们的方法显著优于不利用日志的标准智能体系统，同时也超越了基于反思和KV缓存技术的现有解决方案。

> While humans naturally learn and adapt from past experiences, large language models (LLMs) and their agentic counterparts struggle to retain reasoning from previous tasks and apply them in future contexts. To address this limitation, we propose a novel framework, log-augmented generation (LAG) that directly reuses prior computation and reasoning from past logs at test time to enhance model's ability to learn from previous tasks and perform better on new, unseen challenges, all while keeping the system efficient and scalable. Specifically, our system represents task logs using key-value (KV) caches, encoding the full reasoning context of prior tasks while storing KV caches for only a selected subset of tokens. When a new task arises, LAG retrieves the KV values from relevant logs to augment generation. Our approach differs from reflection-based memory mechanisms by directly reusing prior reasoning and computations without requiring additional steps for knowledge extraction or distillation. Our method also goes beyond existing KV caching techniques, which primarily target efficiency gains rather than improving accuracy. Experiments on knowledge- and reasoning-intensive datasets demonstrate that our method significantly outperforms standard agentic systems that do not utilize logs, as well as existing solutions based on reflection and KV cache techniques.

[Arxiv](https://arxiv.org/abs/2505.14398)