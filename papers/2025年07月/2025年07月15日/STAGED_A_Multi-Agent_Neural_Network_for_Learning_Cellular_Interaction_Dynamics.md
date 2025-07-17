# STAGED: 多智能体神经网络在细胞间相互作用动力学中的学习应用

发布时间：2025年07月15日

`Agent` `生物医学` `细胞动力学`

> STAGED: A Multi-Agent Neural Network for Learning Cellular Interaction Dynamics

# 摘要

> 单细胞技术的出现显著提升了我们对正常和疾病状态下各种组织中细胞状态和亚群的理解，通过聚类和轨迹推断等数据驱动的方法。然而，这些方法将细胞视为群体分布中的独立数据点。借助空间转录组学，我们可以揭示细胞组织及其动态的细胞间相互作用，这些相互作用导致细胞状态的变化。然而，要实现对这种复杂互动细胞动力学的数据驱动学习，仍需关键的计算进展。虽然基于智能体的建模（ABM）提供了一个强大的框架，但传统方法依赖于从领域知识中得出的手工规则，而非数据驱动的方法。为了解决这一问题，我们引入了时空智能体基图演化动力学（STAGED），它结合了ABM和深度学习，以建模细胞间通讯及其对细胞内基因调控网络的影响。利用每个细胞类型共享权重的图ODE网络（GDEs），我们的方法将基因表示为顶点，将相互作用表示为有向边，并通过设计的注意力机制动态学习其强度。该模型经过训练，以匹配模拟的连续轨迹以及从空间转录组学数据推断出的轨迹，捕捉到细胞间和细胞内的相互作用，从而实现对细胞动力学的更适应性和精确的表示。

> The advent of single-cell technology has significantly improved our understanding of cellular states and subpopulations in various tissues under normal and diseased conditions by employing data-driven approaches such as clustering and trajectory inference. However, these methods consider cells as independent data points of population distributions. With spatial transcriptomics, we can represent cellular organization, along with dynamic cell-cell interactions that lead to changes in cell state. Still, key computational advances are necessary to enable the data-driven learning of such complex interactive cellular dynamics. While agent-based modeling (ABM) provides a powerful framework, traditional approaches rely on handcrafted rules derived from domain knowledge rather than data-driven approaches. To address this, we introduce Spatio Temporal Agent-Based Graph Evolution Dynamics(STAGED) integrating ABM with deep learning to model intercellular communication, and its effect on the intracellular gene regulatory network. Using graph ODE networks (GDEs) with shared weights per cell type, our approach represents genes as vertices and interactions as directed edges, dynamically learning their strengths through a designed attention mechanism. Trained to match continuous trajectories of simulated as well as inferred trajectories from spatial transcriptomics data, the model captures both intercellular and intracellular interactions, enabling a more adaptive and accurate representation of cellular dynamics.

[Arxiv](https://arxiv.org/abs/2507.11660)