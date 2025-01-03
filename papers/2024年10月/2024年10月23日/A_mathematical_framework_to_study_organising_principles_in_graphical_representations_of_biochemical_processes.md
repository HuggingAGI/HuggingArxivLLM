# 研究生物化学过程图形表示中组织原则的数学框架

发布时间：2024年10月23日

`其他

理由：这篇论文主要讨论的是系统生物学图形符号（SBGN）的范畴论形式主义，以及如何利用这些形式主义来组合和分析生物化学网络。虽然论文涉及数学和计算机科学的概念，但其核心内容与Agent、RAG、LLM应用、LLM理论等分类无关。因此，将其归类为其他更为合适。` `系统生物学` `生物化学`

> A mathematical framework to study organising principles in graphical representations of biochemical processes

# 摘要

> # 摘要
系统生物学图形符号（SBGN）是一种标准化符号系统，用于将生物化学过程可视化为网络。然而，这些可视化缺乏正式框架，导致通过建模和模拟分析这些网络成为一项独立任务，依赖于所选建模框架（如微分方程、Petri网、随机过程、图）。此外，目前还缺乏一个数学框架来组合网络表示。分子和细胞过程的复杂性使得实验研究通常聚焦于子系统。为了研究生物系统在结构和功能组织层次上的功能，我们需要工具来组合和组织具有不同细节和抽象层次的网络。
  我们通过引入一种基于SBGN过程描述（SBGN-PD）语言的范畴论形式主义来解决这些挑战。利用结构化共跨理论，我们构建了一个对称幺半群双范畴，并将其水平1-态射展示为SBGN过程描述。我们定义了诸如“组合性”（从较小的SBGN-PD构建更大的SBGN-PD）和“缩小”（在生物化学过程中抽象掉细节）等组织原则，这些原则均以范畴论术语表达。我们还正式探讨了生物化学网络的特定部分如何影响网络的其余部分，反之亦然。在整篇论文中，我们通过标准SBGN-PD示例展示了这些发现。

> Systems Biology Graphical Notation (SBGN) is a standardised notational system that visualises biochemical processes as networks. These visualizations lack a formal framework, so that the analysis of such networks through modelling and simulation is an entirely separate task, determined by a chosen modelling framework (e.g. differential equations, Petri nets, stochastic processes, graphs). A second research gap is the lack of a mathematical framework to compose network representations. The complexity of molecular and cellular processes forces experimental studies to focus on subsystems. To study the functioning of biological systems across levels of structural and functional organisation, we require tools to compose and organise networks with different levels of detail and abstraction.
  We address these challenges by introducing a category-theoretic formalism for biochemical processes visualised using SBGN Process Description (SBGN-PD) language. Using the theory of structured cospans, we construct a symmetric monoidal double category and demonstrate its horizontal 1-morphisms as SBGN Process Descriptions. We obtain organisational principles such as 'compositionality' (building a large SBGN-PD from smaller ones) and 'zooming-out' (abstracting away details in biochemical processes) defined in category-theoretic terms. We also formally investigate how a particular portion of a biochemical network influences the remaining portion of the network and vice versa. Throughout the paper, we illustrate our findings using standard SBGN-PD examples.

[Arxiv](https://arxiv.org/abs/2410.18024)