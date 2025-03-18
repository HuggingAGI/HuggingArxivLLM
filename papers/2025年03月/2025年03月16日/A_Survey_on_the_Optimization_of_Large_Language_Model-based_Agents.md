# # 基于大型语言模型的智能体优化综述
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程得以实现。

发布时间：2025年03月16日

`Agent` `代理优化` `人工智能`

> A Survey on the Optimization of Large Language Model-based Agents

# 摘要

> 大型语言模型（LLMs）的蓬勃发展推动了基于LLM代理在各领域的广泛应用，成为自主决策与交互任务中的重要力量。然而，现有研究通常依赖于对基础LLM进行提示设计或微调策略，这在复杂的代理相关环境中往往导致效果有限或表现不佳。尽管LLM优化技术能够提升模型在众多通用任务中的性能，但它们缺乏针对代理关键功能（如长期规划、动态环境交互和复杂决策）的专门优化。尽管近期诸多研究探索了优化LLM代理以应对复杂任务的多种策略，但从整体视角系统性地总结和比较这些方法的综述仍然缺失。本文综述了基于LLM的代理优化方法，将其分类为基于参数和无参数两类方法。我们首先聚焦于基于参数的优化，涵盖基于微调的优化、基于强化学习的优化以及混合策略，分析了轨迹数据构建、微调技术、奖励函数设计和优化算法等关键方面。此外，我们简要探讨了通过提示工程和外部知识检索优化代理行为的无参数策略。最后，我们总结了用于评估和调优的数据集与基准测试，回顾了基于LLM代理的关键应用，并讨论了主要挑战及未来研究方向。相关参考文献的仓库地址为：https://github.com/YoungDubbyDu/LLM-Agent-Optimization。


> With the rapid development of Large Language Models (LLMs), LLM-based agents have been widely adopted in various fields, becoming essential for autonomous decision-making and interactive tasks. However, current work typically relies on prompt design or fine-tuning strategies applied to vanilla LLMs, which often leads to limited effectiveness or suboptimal performance in complex agent-related environments. Although LLM optimization techniques can improve model performance across many general tasks, they lack specialized optimization towards critical agent functionalities such as long-term planning, dynamic environmental interaction, and complex decision-making. Although numerous recent studies have explored various strategies to optimize LLM-based agents for complex agent tasks, a systematic review summarizing and comparing these methods from a holistic perspective is still lacking. In this survey, we provide a comprehensive review of LLM-based agent optimization approaches, categorizing them into parameter-driven and parameter-free methods. We first focus on parameter-driven optimization, covering fine-tuning-based optimization, reinforcement learning-based optimization, and hybrid strategies, analyzing key aspects such as trajectory data construction, fine-tuning techniques, reward function design, and optimization algorithms. Additionally, we briefly discuss parameter-free strategies that optimize agent behavior through prompt engineering and external knowledge retrieval. Finally, we summarize the datasets and benchmarks used for evaluation and tuning, review key applications of LLM-based agents, and discuss major challenges and promising future directions. Our repository for related references is available at https://github.com/YoungDubbyDu/LLM-Agent-Optimization.

[Arxiv](https://arxiv.org/abs/2503.12434)