# # KisMATH: LLMs 是否掌握了数学推理中的隐含结构？

发布时间：2025年07月15日

`LLM理论`

> KisMATH: Do LLMs Have Knowledge of Implicit Structures in Mathematical Reasoning?

# 摘要

> 思维链轨迹在提升大型语言模型推理能力方面表现显著，但其具体作用机制仍待探索。为此，我们提出因果CoT图（CCGs），一种从推理轨迹中提取的有向无环图，用于建模语言模型输出中的细致因果依赖关系。我们从MATH500、GSM8K和AIME中精选了$1671$个数学推理问题及其对应的CCGs，构建了数据集——	extbf{KisMATH}。基于15个开源LLM的实证分析表明：（i）CCG中的推理节点是推理过程的中介，是推理成立的必要条件；（ii）LLMs倾向于使用CCG提供的推理路径，表明模型内部形成了与我们的图结构相似的机制。KisMATH为基于图的可控干预提供了支持，并为深入探究思维链在LLM推理中的作用开辟了新路径。

> Chain-of-thought traces have been shown to improve performance of large language models in a plethora of reasoning tasks, yet there is no consensus on the mechanism through which this performance boost is achieved. To shed more light on this, we introduce Causal CoT Graphs (CCGs), which are directed acyclic graphs automatically extracted from reasoning traces that model fine-grained causal dependencies in the language model output. A collection of $1671$ mathematical reasoning problems from MATH500, GSM8K and AIME, and their associated CCGs are compiled into our dataset -- \textbf{KisMATH}. Our detailed empirical analysis with 15 open-weight LLMs shows that (i) reasoning nodes in the CCG are mediators for the final answer, a condition necessary for reasoning; and (ii) LLMs emphasise reasoning paths given by the CCG, indicating that models internally realise structures akin to our graphs. KisMATH enables controlled, graph-aligned interventions and opens up avenues for further investigation into the role of chain-of-thought in LLM reasoning.

[Arxiv](https://arxiv.org/abs/2507.11408)