# PhysVarMix: 基于物理知识的变分混合模型，用于多模态轨迹预测

发布时间：2025年07月25日

`Agent` `自动驾驶` `轨迹预测`

> PhysVarMix: Physics-Informed Variational Mixture Model for Multi-Modal Trajectory Prediction

# 摘要

> 未来智能体轨迹的精准预测是确保安全高效自主导航的关键挑战，尤其在复杂的城市环境中，这种环境以多种可能的未来场景为特点。本文中，我们提出了一种新颖的混合方法，将学习与物理约束相结合，以解决轨迹预测中的多模态问题。我们的方法采用变分贝叶斯混合模型，有效捕捉潜在未来行为的多样性，超越了传统单一模态的假设。与以往主要将轨迹预测视为数据驱动回归任务的方法不同，我们的框架通过行业特定的边界条件和基于模型预测控制（MPC）的平滑处理，融入了物理现实。这些约束确保了预测轨迹不仅符合数据，而且在物理上合理，遵循运动学和动力学原理。此外，我们的方法生成可解释且多样化的轨迹预测，增强了自动驾驶系统中的下游决策和规划能力。我们在两个基准数据集上评估了我们的方法，展示了优于现有方法的性能。全面的消融研究验证了每个组件的贡献，并突显了它们对预测准确性和可靠性的协同影响。通过平衡数据驱动的见解与物理约束，我们的方法为应对现实世界城市环境中不确定性提供了一个稳健且可扩展的解决方案。

> Accurate prediction of future agent trajectories is a critical challenge for ensuring safe and efficient autonomous navigation, particularly in complex urban environments characterized by multiple plausible future scenarios. In this paper, we present a novel hybrid approach that integrates learning-based with physics-based constraints to address the multi-modality inherent in trajectory prediction. Our method employs a variational Bayesian mixture model to effectively capture the diverse range of potential future behaviors, moving beyond traditional unimodal assumptions. Unlike prior approaches that predominantly treat trajectory prediction as a data-driven regression task, our framework incorporates physical realism through sector-specific boundary conditions and Model Predictive Control (MPC)-based smoothing. These constraints ensure that predicted trajectories are not only data-consistent but also physically plausible, adhering to kinematic and dynamic principles. Furthermore, our method produces interpretable and diverse trajectory predictions, enabling enhanced downstream decision-making and planning in autonomous driving systems. We evaluate our approach on two benchmark datasets, demonstrating superior performance compared to existing methods. Comprehensive ablation studies validate the contributions of each component and highlight their synergistic impact on prediction accuracy and reliability. By balancing data-driven insights with physics-informed constraints, our approach offers a robust and scalable solution for navigating the uncertainties of real-world urban environments.

[Arxiv](https://arxiv.org/abs/2507.19701)