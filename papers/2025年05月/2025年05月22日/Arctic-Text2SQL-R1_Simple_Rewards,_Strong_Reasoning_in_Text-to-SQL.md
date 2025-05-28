# # Arctic-Text2SQL-R1：简单奖励机制助力文本到SQL的强大推理能力

发布时间：2025年05月22日

`LLM应用` `数据库`

> Arctic-Text2SQL-R1: Simple Rewards, Strong Reasoning in Text-to-SQL

# 摘要

> 将自然语言转换为SQL（Test2SQL）是自然语言理解与结构化数据访问交叉领域中的一个长期挑战。虽然大型语言模型（LLMs）显著提升了SQL生成的流畅性，但生成正确且可执行的SQL——尤其是复杂查询——仍然是一个瓶颈。我们提出了Arctic-Text2SQL-R1，这是一个强化学习（RL）框架和模型家族，利用仅基于执行正确性的轻量级奖励信号生成准确且可执行的SQL。我们的方法避免了脆弱的中间监督和复杂的奖励塑造，从而促进了稳定训练并使模型与最终任务保持一致。结合精心整理的数据、强大的监督式初始化以及有效的训练实践，Arctic-Text2SQL-R1在六个多样化的Test2SQL基准测试中实现了最先进的执行精度，包括在BIRD排行榜上位居榜首。值得注意的是，我们的70亿参数模型超越了之前700亿规模的系统，凸显了该框架的可扩展性和效率。我们进一步通过简单的扩展（如值检索和多数投票）展示了推理时的鲁棒性。广泛的实验和消融研究提供了积极和消极的见解，为未来的Test2SQL研究提供了实用的指导。


> Translating natural language into SQL (Test2SQL) is a longstanding challenge at the intersection of natural language understanding and structured data access. While large language models (LLMs) have significantly improved fluency in SQL generation, producing correct and executable SQL--particularly for complex queries--remains a bottleneck. We present Arctic-Text2SQL-R1, a reinforcement learning (RL) framework and model family designed to generate accurate, executable SQL using a lightweight reward signal based solely on execution correctness. Our approach avoids brittle intermediate supervision and complex reward shaping, promoting stable training and alignment with the end task. Combined with carefully curated data, strong supervised initialization, and effective training practices, Arctic-Text2SQL-R1 achieves state-of-the-art execution accuracy across six diverse Test2SQL benchmarks, including the top position on the BIRD leaderboard. Notably, our 7B model outperforms prior 70B-class systems, highlighting the framework's scalability and efficiency. We further demonstrate inference-time robustness through simple extensions like value retrieval and majority voting. Extensive experiments and ablation studies offer both positive and negative insights, providing practical guidance for future Test2SQL research.

[Arxiv](https://arxiv.org/abs/2505.20315)