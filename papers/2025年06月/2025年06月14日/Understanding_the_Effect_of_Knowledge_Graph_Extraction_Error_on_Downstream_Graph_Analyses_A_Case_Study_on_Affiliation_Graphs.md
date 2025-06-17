# 研究知识图谱抽取错误对下游分析的影响：以隶属图作为案例研究

发布时间：2025年06月14日

`LLM应用

摘要分析：论文探讨了大型语言模型在知识图谱提取中的应用，评估其性能对下游分析的影响，属于LLM的具体应用研究。` `知识图谱` `社会学`

> Understanding the Effect of Knowledge Graph Extraction Error on Downstream Graph Analyses: A Case Study on Affiliation Graphs

# 摘要

> 知识图谱在分析社会结构、社区动态、机构隶属关系等跨领域复杂关系方面发挥着重要作用，涵盖从社会学到公共卫生的多个学科。尽管大型语言模型（LLMs）的最新进展提升了从大规模文本语料库中自动提取知识图谱的可扩展性和可访问性，但提取错误对下游分析的影响却鲜为人知，尤其是对于依赖准确知识图谱获取现实世界洞察的应用科学家而言。为填补这一空白，我们在两个层面进行了首次知识图谱提取性能评估：（1）微观层面的边准确性，与标准自然语言处理评估保持一致，并通过人工识别常见错误来源；（2）宏观层面的图指标，评估社区检测和连通性等结构特性，这些特性与现实世界应用相关。聚焦于从社会登记簿中提取的组织人员隶属关系图，我们的研究揭示了提取性能的广泛范围，其中大多数下游图分析指标的偏差接近零。然而，随着提取性能的下降，我们发现许多指标表现出越来越显著的偏差，每个指标倾向于过度或低估的一致方向。通过模拟，我们进一步表明，文献中常用的错误模型未能捕捉这些偏差模式，凸显了知识图谱提取中更现实的错误建模需求。我们的发现为实践者提供了可操作的见解，并强调了改进提取方法和错误建模的重要性，以确保下游分析的可靠性和实际意义。

> Knowledge graphs (KGs) are useful for analyzing social structures, community dynamics, institutional memberships, and other complex relationships across domains from sociology to public health. While recent advances in large language models (LLMs) have improved the scalability and accessibility of automated KG extraction from large text corpora, the impacts of extraction errors on downstream analyses are poorly understood, especially for applied scientists who depend on accurate KGs for real-world insights. To address this gap, we conducted the first evaluation of KG extraction performance at two levels: (1) micro-level edge accuracy, which is consistent with standard NLP evaluations, and manual identification of common error sources; (2) macro-level graph metrics that assess structural properties such as community detection and connectivity, which are relevant to real-world applications. Focusing on affiliation graphs of person membership in organizations extracted from social register books, our study identifies a range of extraction performance where biases across most downstream graph analysis metrics are near zero. However, as extraction performance declines, we find that many metrics exhibit increasingly pronounced biases, with each metric tending toward a consistent direction of either over- or under-estimation. Through simulations, we further show that error models commonly used in the literature do not capture these bias patterns, indicating the need for more realistic error models for KG extraction. Our findings provide actionable insights for practitioners and underscores the importance of advancing extraction methods and error modeling to ensure reliable and meaningful downstream analyses.

[Arxiv](https://arxiv.org/abs/2506.12367)