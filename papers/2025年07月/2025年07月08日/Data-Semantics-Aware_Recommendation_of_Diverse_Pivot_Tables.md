# 数据语义感知型多样化透视表推荐

发布时间：2025年07月08日

`LLM应用

理由：这篇论文主要讨论了数据透视表的推荐系统，提出了SAGE系统，并在商业软件和大型语言模型（LLMs）上展示了其有效性。虽然论文的核心是数据分析工具的优化，但其应用部分涉及到了LLMs，因此归类为LLM应用。` `数据分析` `商业智能`

> Data-Semantics-Aware Recommendation of Diverse Pivot Tables

# 摘要

> 数据汇总是发现大型数据集见解的关键。在电子表格中，数据透视表提供了一种便捷的方式，通过计算某些属性的聚合值并按其他属性分组来汇总表格数据。然而，识别能够生成有用数据透视表的属性组合仍然是一项挑战，尤其是在处理高维数据集时。我们提出了一种自动推荐有见解且可解释的数据透视表的方法，以消除繁琐的手动过程。推荐一组数据透视表的关键在于使它们多样化。传统方法未能充分解决表格多样化的问题，这促使我们深入研究数据透视表多样化的挑战。

我们提出了 SAGE，一个数据语义感知系统，用于推荐 k 预算的多样化数据透视表，克服了先前工作中在 top-k 推荐中存在的冗余问题。SAGE 确保每个数据透视表都具有见解性、可解释性，并能够适应用户的操作和偏好，同时保证一组数据透视表彼此不同，提供多样化的推荐。我们在技术上做出了两个关键贡献：(1) 一个数据语义感知模型，用于衡量单个数据透视表的效用以及一组数据透视表的多样性；(2) 一个可扩展的贪心算法，能够通过利用数据语义显著减少组合搜索空间，高效地选择一组高效用且多样化的数据透视表。我们在三个真实世界数据集上的广泛实验表明，SAGE 在性能上优于替代方法，并且能够高效扩展以处理高维数据集。此外，我们还展示了几个案例研究，以突出 SAGE 在商业软件和大型语言模型 (LLMs) 上的定性有效性。


> Data summarization is essential to discover insights from large datasets. In a spreadsheets, pivot tables offer a convenient way to summarize tabular data by computing aggregates over some attributes, grouped by others. However, identifying attribute combinations that will result in useful pivot tables remains a challenge, especially for high-dimensional datasets. We formalize the problem of automatically recommending insightful and interpretable pivot tables, eliminating the tedious manual process. A crucial aspect of recommending a set of pivot tables is to diversify them. Traditional works inadequately address the table-diversification problem, which leads us to consider the problem of pivot table diversification.
  We present SAGE, a data-semantics-aware system for recommending k-budgeted diverse pivot tables, overcoming the shortcomings of prior work for top-k recommendations that cause redundancy. SAGE ensures that each pivot table is insightful, interpretable, and adaptive to the user's actions and preferences, while also guaranteeing that the set of pivot tables are different from each other, offering a diverse recommendation. We make two key technical contributions: (1) a data-semantics-aware model to measure the utility of a single pivot table and the diversity of a set of pivot tables, and (2) a scalable greedy algorithm that can efficiently select a set of diverse pivot tables of high utility, by leveraging data semantics to significantly reduce the combinatorial search space. Our extensive experiments on three real-world datasets show that SAGE outperforms alternative approaches, and efficiently scales to accommodate high-dimensional datasets. Additionally, we present several case studies to highlight SAGE's qualitative effectiveness over commercial software and Large Language Models (LLMs).

[Arxiv](https://arxiv.org/abs/2507.06171)