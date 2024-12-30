# xFLIE：借助可操作的分层场景表示，完成自主语义感知检查任务

发布时间：2024年12月27日

`其他` `机器人`

> xFLIE: Leveraging Actionable Hierarchical Scene Representations for Autonomous Semantic-Aware Inspection Missions

# 摘要

> 这篇文章呈现了 xFLIE，一个完全集成的基于 3D 分层场景图的自主巡检架构。具体而言，我们给出了一个紧密结合的方案，即增量 3D 分层语义图（LSG）的构建以及由多模态自主、基于初看的检查与探索（FLIE）规划器进行的实时利用，以应对在未知环境中检查先验未知的感兴趣语义目标这一任务。此工作旨在应对在大规模巡检任务中，除了体积模型外或作为其替代，保持直观场景呈现的挑战。通过其贡献，所提出的架构意在提供高级多层的抽象环境表征，同时为能够通过场景理解强化巡检规划的快速且明智的决策奠定易于处理的基础，比如应该检查什么？以及为何要检查？所提出的 LSG 框架旨在利用在多个抽象层级嵌套较低局部图的概念，抽象概念基于集成的 FLIE 规划器的功能。通过直观的场景呈现，所提出的架构为人类操作员提供了一个易于理解的环境模型，有助于提升态势感知以及他们对操作环境的理解。我们突出了分层和语义路径规划能力在 LSG 上相对于集成规划器和人类操作员提出的查询的用例优势。所提出架构的有效性在大规模模拟的户外城市场景中得到了评估，并在波士顿动力 Spot 四足机器人上进行了部署，以开展广泛的户外实地实验。

> This article presents xFLIE, a fully integrated 3D hierarchical scene graph based autonomous inspection architecture. Specifically, we present a tightly-coupled solution of incremental 3D Layered Semantic Graphs (LSG) construction and real-time exploitation by a multi-modal autonomy, First-Look based Inspection and Exploration (FLIE) planner, to address the task of inspection of apriori unknown semantic targets of interest in unknown environments. This work aims to address the challenge of maintaining, in addition to or as an alternative to volumetric models, an intuitive scene representation during large-scale inspection missions. Through its contributions, the proposed architecture aims to provide a high-level multi-tiered abstract environment representation whilst simultaneously maintaining a tractable foundation for rapid and informed decision-making capable of enhancing inspection planning through scene understanding, what should it inspect ?, and reasoning, why should it inspect ?. The proposed LSG framework is designed to leverage the concept of nesting lower local graphs, at multiple layers of abstraction, with the abstract concepts grounded on the functionality of the integrated FLIE planner. Through intuitive scene representation, the proposed architecture offers an easily digestible environment model for human operators which helps to improve situational awareness and their understanding of the operating environment. We highlight the use-case benefits of hierarchical and semantic path-planning capability over LSG to address queries, by the integrated planner as well as the human operator. The validity of the proposed architecture is evaluated in large-scale simulated outdoor urban scenarios as well as being deployed onboard a Boston Dynamics Spot quadruped robot for extensive outdoor field experiments.

[Arxiv](https://arxiv.org/abs/2412.19571)