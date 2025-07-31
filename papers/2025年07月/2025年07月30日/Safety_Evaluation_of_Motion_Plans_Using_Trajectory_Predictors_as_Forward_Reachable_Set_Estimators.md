# # 安全性评估：基于轨迹预测器的前向可达集估计运动规划安全评估

发布时间：2025年07月30日

`Agent` `自动驾驶` `安全监控`

> Safety Evaluation of Motion Plans Using Trajectory Predictors as Forward Reachable Set Estimators

# 摘要

> 随着端到端自动驾驶系统（end-to-end autonomy stacks）的普及，由于其通常缺乏可解释的中间模块，确保最终输出——即运动规划——的安全性变得尤为重要，以验证整个系统的安全性。为此，我们需要一个既完整（能够检测所有不安全的规划）又可靠（不误报安全的规划）的安全监控器。在本研究中，我们提出了一种基于现代多模态轨迹预测器的原理化安全监控器，用于近似周围代理的可达集（FRS）。通过构建凸优化程序，我们能够直接从预测的状态分布中高效提取这些数据驱动的FRS，同时考虑场景上下文，如车道拓扑和代理历史。为了确保完整性，我们利用符合性预测来校准FRS，并以高概率保证对真实轨迹的覆盖。为了在分布外（OOD）场景或预测器故障情况下保持可靠性，我们引入了一种贝叶斯滤波器，根据预测器的性能动态调整FRS的保守程度。然后，我们通过检查这些校准后的FRS与 ego 车辆运动规划的交集来评估规划的安全性，确保在其他车辆可能的未来行为下规划保持无碰撞。在nuScenes数据集上的大量实验表明，我们的方法在保持完整性的前提下显著提高了可靠性，为学习型自动驾驶系统提供了一种实用且可靠的安全监控方案。

> The advent of end-to-end autonomy stacks - often lacking interpretable intermediate modules - has placed an increased burden on ensuring that the final output, i.e., the motion plan, is safe in order to validate the safety of the entire stack. This requires a safety monitor that is both complete (able to detect all unsafe plans) and sound (does not flag safe plans). In this work, we propose a principled safety monitor that leverages modern multi-modal trajectory predictors to approximate forward reachable sets (FRS) of surrounding agents. By formulating a convex program, we efficiently extract these data-driven FRSs directly from the predicted state distributions, conditioned on scene context such as lane topology and agent history. To ensure completeness, we leverage conformal prediction to calibrate the FRS and guarantee coverage of ground-truth trajectories with high probability. To preserve soundness in out-of-distribution (OOD) scenarios or under predictor failure, we introduce a Bayesian filter that dynamically adjusts the FRS conservativeness based on the predictor's observed performance. We then assess the safety of the ego vehicle's motion plan by checking for intersections with these calibrated FRSs, ensuring the plan remains collision-free under plausible future behaviors of others. Extensive experiments on the nuScenes dataset show our approach significantly improves soundness while maintaining completeness, offering a practical and reliable safety monitor for learned autonomy stacks.

[Arxiv](https://arxiv.org/abs/2507.22389)