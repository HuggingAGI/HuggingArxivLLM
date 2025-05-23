# LLM 智能体的内存管理机制对其性能的影响研究：基于经验跟随行为的实证分析

发布时间：2025年05月21日

`Agent` `人工智能` `代理系统`

> How Memory Management Impacts LLM Agents: An Empirical Study of Experience-Following Behavior

# 摘要

> # 摘要
记忆是大型语言模型（LLM）代理中的关键组件，使其能够存储和检索过去的执行情况，从而随着时间的推移提升任务表现。本文中，我们进行了一项实证研究，探讨记忆管理选择如何影响LLM代理的行为，尤其是它们的长期性能。

具体而言，我们关注两种在许多代理框架中广泛使用的根本性记忆操作——添加（将新经验纳入记忆库）和删除（有选择地移除过去的经历）——以系统性地研究它们对代理行为的影响。通过定量分析，我们发现LLM代理表现出一种经验跟随特性：当任务输入与检索到的记忆记录中的输入高度相似时，往往会导致代理输出的高度相似。

我们的分析进一步揭示了与这一特性相关的两大显著挑战：错误传播（过去经验中的不准确之处累积并削弱未来表现）以及经验回放不一致（过时或不相关的经验对当前任务产生负面影响）。通过控制实验，我们证明结合选择性添加和删除策略有助于缓解这些负面效果，与简单的记忆增长相比，平均绝对性能提升了10%。

此外，我们还探讨了在任务分布变化和受限记忆资源等具有挑战性的条件下，记忆管理选择如何影响代理行为。我们的发现揭示了LLM代理记忆系统的动态行为，并为设计支持稳健、长期代理性能的记忆组件提供了实用指导。我们还开源了我们的代码，以促进进一步的研究。

> Memory is a critical component in large language model (LLM)-based agents, enabling them to store and retrieve past executions to improve task performance over time. In this paper, we conduct an empirical study on how memory management choices impact the LLM agents' behavior, especially their long-term performance. Specifically, we focus on two fundamental memory operations that are widely used by many agent frameworks-addition, which incorporates new experiences into the memory base, and deletion, which selectively removes past experiences-to systematically study their impact on the agent behavior. Through our quantitative analysis, we find that LLM agents display an experience-following property: high similarity between a task input and the input in a retrieved memory record often results in highly similar agent outputs. Our analysis further reveals two significant challenges associated with this property: error propagation, where inaccuracies in past experiences compound and degrade future performance, and misaligned experience replay, where outdated or irrelevant experiences negatively influence current tasks. Through controlled experiments, we show that combining selective addition and deletion strategies can help mitigate these negative effects, yielding an average absolute performance gain of 10% compared to naive memory growth. Furthermore, we highlight how memory management choices affect agents' behavior under challenging conditions such as task distribution shifts and constrained memory resources. Our findings offer insights into the behavioral dynamics of LLM agent memory systems and provide practical guidance for designing memory components that support robust, long-term agent performance. We also release our code to facilitate further study.

[Arxiv](https://arxiv.org/abs/2505.16067)