# LLMDR：基于LLM的多智能体路径规划中死锁的检测与解决

发布时间：2025年03月01日

`Agent` `机器人学` `自动化`

> LLMDR: LLM-Driven Deadlock Detection and Resolution in Multi-Agent Pathfinding

# 摘要

> 多智能体路径规划（MAPF）是多智能体系统中的核心难题。现有的基于学习的MAPF方法在扩展性方面常常面临困难，尤其是在处理容易导致死锁的复杂场景时。为了解决这一难题，我们提出了LLMDR（基于LLM的死锁检测与解决方法），一种旨在解决死锁并提升学习型MAPF模型性能的方法。LLMDR将大型语言模型（LLMs）的推理能力与学习型MAPF模型以及优先级规划相结合，使其能够检测死锁并提供定制化的解决方案。我们在标准的MAPF基准地图上对LLMDR进行了评估，测试了其与多种基础模型结合时的性能表现。实验结果表明，LLMDR能够提升学习型MAPF模型的性能，尤其是在容易出现死锁的场景下，成功率有了显著的提高。这些发现表明，将LLMs与学习型MAPF方法相结合，具有提升其扩展性的潜力。LLMDR的源代码可在以下地址获取：https://github.com/ssbacc/llmdr-dhc

> Multi-Agent Pathfinding (MAPF) is a core challenge in multi-agent systems. Existing learning-based MAPF methods often struggle with scalability, particularly when addressing complex scenarios that are prone to deadlocks. To address these challenges, we introduce LLMDR (LLM-Driven Deadlock Detection and Resolution), an approach designed to resolve deadlocks and improve the performance of learnt MAPF models. LLMDR integrates the inference capabilities of large language models (LLMs) with learnt MAPF models and prioritized planning, enabling it to detect deadlocks and provide customized resolution strategies. We evaluate LLMDR on standard MAPF benchmark maps with varying agent numbers, measuring its performance when combined with several base models. The results demonstrate that LLMDR improves the performance of learnt MAPF models, particularly in deadlock-prone scenarios, with notable improvements in success rates. These findings show the potential of integrating LLMs to improve the scalability of learning-based MAPF methods.
  The source code for LLMDR is available at: https://github.com/ssbacc/llmdr-dhc

[Arxiv](https://arxiv.org/abs/2503.00717)