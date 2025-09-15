# 借助结构保持机器学习实现基于物理的传感器覆盖

发布时间：2025年09月12日

`其他` `工业与制造`

> Physics-informed sensor coverage through structure preserving machine learning

# 摘要

> 我们提出了一种自适应源定位机器学习框架，其中智能体利用耦合流体动力学-传输系统的结构保持数字孪生，实现实时轨迹规划与数据同化。该数字孪生基于条件神经Whitney形式（CNWF）构建，融合了有限元外微积分（FEEC）的数值保证与基于Transformer的算子学习。所得模型不仅保持离散守恒性，还能实时适配流式传感器数据。它通过条件注意力机制识别：降维Whitney形式基、降维积分平衡方程及源场，且每一项均与给定传感器测量数据兼容。由此构建的降阶环境模型保留了标准有限元模拟的稳定性与一致性，可从传感器数据到源场形成物理可实现的正则映射。我们提出一种交错方案，交替执行数字孪生评估与Lloyd算法传感器放置引导，并通过分析给出覆盖泛函单调改进的条件。在最优恢复方案中，我们将预测源场作为重要性函数，验证了连续性假设下点源的恢复效果，并强调正则性是定位的充分条件。实验对比物理无关的Transformer架构表明，施加物理约束后，复杂几何场景下的精度显著提升，说明结构保持为源识别提供了有效的归纳偏置。

> We present a machine learning framework for adaptive source localization in which agents use a structure-preserving digital twin of a coupled hydrodynamic-transport system for real-time trajectory planning and data assimilation. The twin is constructed with conditional neural Whitney forms (CNWF), coupling the numerical guarantees of finite element exterior calculus (FEEC) with transformer-based operator learning. The resulting model preserves discrete conservation, and adapts in real time to streaming sensor data. It employs a conditional attention mechanism to identify: a reduced Whitney-form basis; reduced integral balance equations; and a source field, each compatible with given sensor measurements. The induced reduced-order environmental model retains the stability and consistency of standard finite-element simulation, yielding a physically realizable, regular mapping from sensor data to the source field. We propose a staggered scheme that alternates between evaluating the digital twin and applying Lloyd's algorithm to guide sensor placement, with analysis providing conditions for monotone improvement of a coverage functional. Using the predicted source field as an importance function within an optimal-recovery scheme, we demonstrate recovery of point sources under continuity assumptions, highlighting the role of regularity as a sufficient condition for localization. Experimental comparisons with physics-agnostic transformer architectures show improved accuracy in complex geometries when physical constraints are enforced, indicating that structure preservation provides an effective inductive bias for source identification.

[Arxiv](https://arxiv.org/abs/2509.10363)