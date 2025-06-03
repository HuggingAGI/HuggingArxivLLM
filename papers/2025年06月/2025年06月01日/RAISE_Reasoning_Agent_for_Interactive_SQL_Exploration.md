# # RAISE：助力交互式SQL探索的推理助手

发布时间：2025年06月01日

`Agent` `数据库`

> RAISE: Reasoning Agent for Interactive SQL Exploration

# 摘要

> 近年来，大型语言模型（LLMs）的突破性进展极大地推动了自然语言接口到数据库的研究。然而，当前最先进的文本到SQL系统大多依赖复杂繁琐的多阶段流水线。我们提出了一种创新的智能体框架，首次将模式链接、查询生成和迭代优化整合到一个统一的端到端组件中。通过模拟人类处理不熟悉数据库时的思维方式，我们的方法让模型能够像人类一样：通过提出假设理解数据，通过动态查询验证假设，基于结果推理分析，并根据反馈优化输出。特别值得一提的是，我们开创性地提出了扩展文本到SQL测试时间计算的新策略：通过增加交互式数据库探索和反思的深度，使模型能够更智能地分配计算资源，尤其是在处理模糊和欠指定场景时表现出色。实验结果表明，使用DeepSeek-R1-Distill-Llama-70B模型，在极具挑战性的BIRD数据集上，我们的方法将执行准确率（EX）从44.8%显著提升至56.5%。更令人振奋的是，通过增加答案多样性，我们的智能体在8轮候选生成中达到了81.8%的最佳N准确率，几乎与最优已发布解决方案的82.79%持平，同时大幅降低了实现复杂度。这些成果充分证明了我们的统一框架在构建自然语言数据库接口方面的巨大潜力。

> Recent advances in large language models (LLMs) have propelled research in natural language interfaces to databases. However, most state-of-the-art text-to-SQL systems still depend on complex, multi-stage pipelines. This work proposes a novel agentic framework that unifies schema linking, query generation, and iterative refinement within a single, end-to-end component. By leveraging the intrinsic reasoning abilities of LLMs, our method emulates how humans answer questions when working with unfamiliar databases: understanding the data by formulating hypotheses, running dynamic queries to validate them, reasoning over the results, and revising outputs based on observed results. Crucially, our approach introduces a new strategy for scaling test-time computation in text-to-SQL: we scale the depth of interactive database exploration and reflection. This shift enables the model to allocate computation dynamically to better understand the data, especially useful in ambiguous and underspecified scenarios. Our experiments show that it improved the Execution Accuracy (EX) from 44.8% to 56.5% on the challenging BIRD dataset using DeepSeek-R1-Distill-Llama-70B. Furthermore, when equipped with steps to add more diversity to the answers, our agent achieves a Best-of-N accuracy of 81.8% with 8 rounds of candidate generation, rivaling the 82.79% achieved by the top-ranked published solution, while reducing engineering complexity. These findings position our unified framework as a promising alternative for building natural language interfaces to databases.

[Arxiv](https://arxiv.org/abs/2506.01273)