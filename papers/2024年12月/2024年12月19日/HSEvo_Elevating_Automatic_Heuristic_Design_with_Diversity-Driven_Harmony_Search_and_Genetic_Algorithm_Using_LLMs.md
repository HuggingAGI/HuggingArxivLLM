# HSEvo：借助多样性驱动的和谐搜索与遗传算法以及 LLMs 来提升自动启发式设计

发布时间：2024年12月19日

`LLM应用` `搜索优化` `程序设计`

> HSEvo: Elevating Automatic Heuristic Design with Diversity-Driven Harmony Search and Genetic Algorithm Using LLMs

# 摘要

> 自动启发式设计（AHD）是一个活跃的研究领域，因其在解决现实世界中的复杂搜索及NP难组合优化问题时大有用处。大型语言模型（LLMs）的最新进展带来了新可能，即将LLMs与进化计算相结合，自动生成启发式算法，即基于LLM的进化程序搜索（LLM-EPS）。此前的LLM-EPS研究在各类任务中表现出色，但在理解启发式搜索空间的特性以及实现探索与利用的平衡方面仍存差距，这在大型启发式搜索空间中是关键因素。本研究中，我们通过提出两个多样性度量指标来填补这一差距，并对FunSearch、EoH和ReEvo等先前的LLM-EPS方法进行分析。针对黑箱AHD问题的结果显示，虽然EoH比FunSearch和ReEvo的多样性更高，但其目标得分不稳定。相反，ReEvo的反射机制能产生良好的目标得分，却无法有效优化多样性。鉴于此，我们引入了HSEvo，这是一个自适应的LLM-EPS框架，借助和谐搜索算法在多样性和收敛之间保持平衡。通过实验，我们发现HSEvo在保持成本效益的同时，实现了高多样性指数和良好的目标得分。这些结果凸显了在LLM-EPS中设计框架时平衡探索与利用以及理解启发式搜索空间的重要性。

> Automatic Heuristic Design (AHD) is an active research area due to its utility in solving complex search and NP-hard combinatorial optimization problems in the real world. The recent advancements in Large Language Models (LLMs) introduce new possibilities by coupling LLMs with evolutionary computation to automatically generate heuristics, known as LLM-based Evolutionary Program Search (LLM-EPS). While previous LLM-EPS studies obtained great performance on various tasks, there is still a gap in understanding the properties of heuristic search spaces and achieving a balance between exploration and exploitation, which is a critical factor in large heuristic search spaces. In this study, we address this gap by proposing two diversity measurement metrics and perform an analysis on previous LLM-EPS approaches, including FunSearch, EoH, and ReEvo. Results on black-box AHD problems reveal that while EoH demonstrates higher diversity than FunSearch and ReEvo, its objective score is unstable. Conversely, ReEvo's reflection mechanism yields good objective scores but fails to optimize diversity effectively. With this finding in mind, we introduce HSEvo, an adaptive LLM-EPS framework that maintains a balance between diversity and convergence with a harmony search algorithm. Through experimentation, we find that HSEvo achieved high diversity indices and good objective scores while remaining cost-effective. These results underscore the importance of balancing exploration and exploitation and understanding heuristic search spaces in designing frameworks in LLM-EPS.

[Arxiv](https://arxiv.org/abs/2412.14995)