# 结合EGNN与持久同调的活性粒子悬浮液力预测拓扑正则化

发布时间：2025年09月08日

`其他` `基础理论`

> Topological Regularization for Force Prediction in Active Particle Suspension with EGNN and Persistent Homology

# 摘要

> 捕捉活性粒子的动力学——即那些既能自身形变又会被所处流体改变形态的小型自驱动个体——是个极具挑战的难题，因其需要将微观流体力学与宏观集体效应紧密耦合。为此，我们提出一种多尺度框架，融合三种学习驱动工具，在单一流程中协同发挥作用。该学习流程以周期性空间内流体速度与粒子应力的高分辨率格子玻尔兹曼快照为输入。第二步则借助粒子的形态、位置和取向信息，通过一个严格遵循平面对称性的E(2)等变图神经网络，预测粒子间的成对相互作用力。接着，物理知情神经网络结合应力数据对这些局部估计值求和更新，过程中采用傅里叶特征映射与残差块，并通过拓扑项（由持久同调引入）进行额外正则化，以抑制不真实的缠绕或虚假连接。这些阶段协同运作，最终实现了一个整体的、高度数据驱动的全力网络预测，既凸显物理本质，又涵盖活性物质特有的涌现多尺度结构。

> Capturing the dynamics of active particles, i.e., small self-propelled agents that both deform and are deformed by a fluid in which they move is a formidable problem as it requires coupling fine scale hydrodynamics with large scale collective effects. So we present a multi-scale framework that combines the three learning-driven tools to learn in concert within one pipeline. We use high-resolution Lattice Boltzmann snapshots of fluid velocity and particle stresses in a periodic box as input to the learning pipeline. the second step takes the morphology and positions orientations of particles to predict pairwise interaction forces between them with a E(2)-equivariant graph neural network that necessarily respect flat symmetries. Then, a physics-informed neural network further updates these local estimates by summing over them with a stress data using Fourier feature mappings and residual blocks that is additionally regularized with a topological term (introduced by persistent homology) to penalize unrealistically tangled or spurious connections. In concert, these stages deliver an holistic highly-data driven full force network prediction empathizing on the physical underpinnings together with emerging multi-scale structure typical for active matter.

[Arxiv](https://arxiv.org/abs/2509.06574)