# 基于 LLM 引导的蒙特卡洛树搜索实现动态自适应推理，用于高效且智能的知识图谱问答

发布时间：2025年08月01日

`LLM应用` `知识图谱` `问答系统`

> Dynamically Adaptive Reasoning via LLM-Guided MCTS for Efficient and Context-Aware KGQA

# 摘要

> # 摘要  
知识图谱问答（KGQA）致力于通过利用知识图谱的关系和语义结构，准确解析自然语言查询并进行结构化推理以获取精确答案。当前的KGQA方法主要分为两类：一类基于GNNs或启发式规则，通过静态路径抽取实现检索-推理流程；另一类则借助提示工程，利用大型语言模型（LLMs）动态生成路径策略，实现检索与推理的联合操作。然而，前者因静态路径抽取和缺乏上下文优化而适应性有限；后者则因固定评分函数和大量LLM调用，导致计算成本高昂且路径评估不够精准。针对这些问题，本文提出了一种名为动态自适应MCTS推理（DAMR）的新颖框架，通过结合符号搜索与自适应路径评估，实现高效且上下文感知的KGQA。DAMR采用基于LLM的规划器引导的蒙特卡洛树搜索（MCTS）作为核心，每一步选择top-$k$相关关系以缩小搜索空间。为了提升路径评估的准确性，我们引入了一种轻量级的Transformer评分器，通过交叉注意力联合编码问题和关系序列，进行上下文感知的合理性估计，使模型能够在多跳推理中捕捉细微的语义变化。此外，为缓解高质量监督数据的稀缺性，DAMR集成了动态伪路径优化机制，定期从搜索过程中探索的部分路径生成训练信号，使评分器能够持续适应推理轨迹分布的演变。在多个KGQA基准上的大量实验表明，DAMR显著超越了现有最优方法。


> Knowledge Graph Question Answering (KGQA) aims to interpret natural language queries and perform structured reasoning over knowledge graphs by leveraging their relational and semantic structures to retrieve accurate answers. Recent KGQA methods primarily follow either retrieve-then-reason paradigm, relying on GNNs or heuristic rules for static paths extraction, or dynamic path generation strategies that use large language models (LLMs) with prompting to jointly perform retrieval and reasoning. However, the former suffers from limited adaptability due to static path extraction and lack of contextual refinement, while the latter incurs high computational costs and struggles with accurate path evaluation due to reliance on fixed scoring functions and extensive LLM calls. To address these issues, this paper proposes Dynamically Adaptive MCTS-based Reasoning (DAMR), a novel framework that integrates symbolic search with adaptive path evaluation for efficient and context-aware KGQA. DAMR employs a Monte Carlo Tree Search (MCTS) backbone guided by an LLM-based planner, which selects top-$k$ relevant relations at each step to reduce search space. To improve path evaluation accuracy, we introduce a lightweight Transformer-based scorer that performs context-aware plausibility estimation by jointly encoding the question and relation sequence through cross-attention, enabling the model to capture fine-grained semantic shifts during multi-hop reasoning. Furthermore, to alleviate the scarcity of high-quality supervision, DAMR incorporates a dynamic pseudo-path refinement mechanism that periodically generates training signals from partial paths explored during search, allowing the scorer to continuously adapt to the evolving distribution of reasoning trajectories. Extensive experiments on multiple KGQA benchmarks show that DAMR significantly outperforms state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2508.00719)