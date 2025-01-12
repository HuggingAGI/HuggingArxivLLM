# ThriftLLM: 分类查询中经济高效的大型语言模型选择

发布时间：2025年01月08日

`LLM应用

理由：这篇论文主要讨论了如何通过集成多个大型语言模型（LLMs）来提升性能并降低成本，提出了具体的算法（ThriftLLM）来解决这一问题。这属于LLM在实际应用中的优化和集成策略，因此应归类为LLM应用。` `成本优化`

> ThriftLLM: On Cost-Effective Selection of Large Language Models for Classification Queries

# 摘要

> # 摘要
大型语言模型（LLMs）在理解和生成自然语言内容方面表现出色，近年来在工业界和学术界广受欢迎。越来越多的服务通过API提供LLMs用于各种任务，不同LLMs在不同领域（如文本分类）各有所长，且定价因规模、复杂性和性能而异。基于此，越来越多的研究者开始探索LLM集成策略，旨在降低成本的同时提升性能。然而，现有研究尚未解决如何在成本预算内选择LLM集成以最大化性能的问题。
本文通过定义预测准确性，形式化了LLM集成的性能。我们提出了一种聚合多个LLMs响应的方法，以提升集成性能。在此基础上，我们将集成选择问题形式化为在成本预算内选择一组LLMs，以最大化预测准确性。我们理论证明了预测准确性函数的非递减和非子模性质，并提供了最优集成选择问题可能是NP难的证据。随后，我们应用动态规划，提出了名为ThriftLLM的算法，并证明其具有接近最优的近似保证。在广泛的实验评估中，ThriftLLM在多个真实数据集上实现了最先进的查询性能，充分证明了我们方法的有效性和优越性。

> Large language models (LLMs) have demonstrated remarkable capabilities in comprehending and generating natural language content, attracting widespread popularity in both industry and academia in recent years. An increasing number of services have sprung up which offer LLMs for various tasks via APIs. Different LLMs demonstrate expertise in different domains of queries (e.g., text classification queries). Meanwhile, LLMs of different scales, complexity, and performance are priced diversely. Driven by this observation, a growing number of researchers are investigating the LLM ensemble strategy with a focus on cost-effectiveness, aiming to decrease overall usage costs while enhancing performance. However, to the best of our knowledge, none of the existing works addresses the problem, i.e., how to find an LLM ensemble subject to a cost budget, which maximizes the ensemble performance.
  In this paper, we formalize the performance of an ensemble of models (LLMs) using the notion of prediction accuracy which we formally define. We develop an approach for aggregating responses from multiple LLMs to enhance ensemble performance. Building on this, we formulate the ensemble selection problem as that of selecting a set of LLMs subject to a cost budget such that the overall prediction accuracy is maximized. We theoretically establish the non-decreasing and non-submodular properties of the prediction accuracy function and provide evidence that the Optimal Ensemble Selection problem is likely to be NP-hard. Subsequently, we apply dynamic programming and propose an algorithm called ThriftLLM. We prove that ThriftLLM achieves a near-optimal approximation guarantee. In addition, it achieves state-of-the-art query performance on multiple real-world datasets against 3 competitors in our extensive experimental evaluation, strongly supporting the effectiveness and superiority of our method.

[Arxiv](https://arxiv.org/abs/2501.04901)