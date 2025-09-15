# MatSKRAFT：从科学表格中大规模提取材料知识的框架

发布时间：2025年09月12日

`其他` `工业与制造`

> MatSKRAFT: A framework for large-scale materials knowledge extraction from scientific tables

# 摘要

> 科学进步日益依赖于对海量文献知识的整合，但大多数实验数据仍被困在半结构化格式中，无法进行系统提取与分析。为此，我们提出了MatSKRAFT——一个能以前所未有的规模从表格数据中自动提取并整合材料科学知识的计算框架。该方法将表格转化为基于图的表示，再通过约束驱动的图神经网络（GNNs）进行处理，这些网络将科学原理直接嵌入模型架构。MatSKRAFT的性能远超最先进的大型语言模型，在属性提取和成分提取任务上F1分数分别达到88.68和71.35；同时，其数据处理速度比这些模型快【数学公式】（分别对应最慢和最快模型），且硬件需求较低。我们将MatSKRAFT应用于47,000多篇研究论文中的近69,000个表格，构建了一个包含535,000多个条目的综合数据库，其中104,000种成分扩展了现有主流数据库的覆盖范围（尚待人工验证）。这种系统方法不仅发现了以往被忽略的、具有独特属性组合的材料，还实现了数据驱动的成分-属性关系挖掘——这正是材料科学发现的核心所在。

> Scientific progress increasingly depends on synthesizing knowledge across vast literature, yet most experimental data remains trapped in semi-structured formats that resist systematic extraction and analysis. Here, we present MatSKRAFT, a computational framework that automatically extracts and integrates materials science knowledge from tabular data at unprecedented scale. Our approach transforms tables into graph-based representations processed by constraint-driven GNNs that encode scientific principles directly into model architecture. MatSKRAFT significantly outperforms state-of-the-art large language models, achieving F1 scores of 88.68 for property extraction and 71.35 for composition extraction, while processing data $19$-$496\times$ faster than them (compared to the slowest and the fastest models, respectively) with modest hardware requirements. Applied to nearly 69,000 tables from more than 47,000 research publications, we construct a comprehensive database containing over 535,000 entries, including 104,000 compositions that expand coverage beyond major existing databases, pending manual validation. This systematic approach reveals previously overlooked materials with distinct property combinations and enables data-driven discovery of composition-property relationships forming the cornerstone of materials and scientific discovery.

[Arxiv](https://arxiv.org/abs/2509.10448)