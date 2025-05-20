# Graph-Reward-SQL: 基于图匹配与逐步奖励的文本到SQL无需执行强化学习

发布时间：2025年05月18日

`Agent` `数据库`

> Graph-Reward-SQL: Execution-Free Reinforcement Learning for Text-to-SQL via Graph Matching and Stepwise Reward

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）的Text-to-SQL任务性能方面被广泛应用。然而，现有方法主要依赖于执行或LLM基Bradley-Terry奖励模型，前者因数据库反复调用导致延迟高，后者则占用大量GPU内存，严重制约了RL流水线的效率和扩展性。为此，我们提出了Graph-Reward-SQL框架，采用GMNScore结果奖励模型，利用SQL图表示提供精准奖励信号，显著降低推理时间和GPU内存占用。此外，我们引入StepRTM分步奖励模型，对公共表表达式（CTE）子查询进行中间监督，促进SQL的功能准确性和结构清晰度。在Spider和BIRD等标准基准上的广泛实验表明，我们的方法在现有奖励模型中表现最优。


> Reinforcement learning (RL) has been widely adopted to enhance the performance of large language models (LLMs) on Text-to-SQL tasks. However, existing methods often rely on execution-based or LLM-based Bradley-Terry reward models. The former suffers from high execution latency caused by repeated database calls, whereas the latter imposes substantial GPU memory overhead, both of which significantly hinder the efficiency and scalability of RL pipelines. To this end, we propose a novel Text-to-SQL RL fine-tuning framework named Graph-Reward-SQL, which employs the GMNScore outcome reward model. We leverage SQL graph representations to provide accurate reward signals while significantly reducing inference time and GPU memory usage. Building on this foundation, we further introduce StepRTM, a stepwise reward model that provides intermediate supervision over Common Table Expression (CTE) subqueries. This encourages both functional correctness and structural clarity of SQL. Extensive comparative and ablation experiments on standard benchmarks, including Spider and BIRD, demonstrate that our method consistently outperforms existing reward models.

[Arxiv](https://arxiv.org/abs/2505.12380)