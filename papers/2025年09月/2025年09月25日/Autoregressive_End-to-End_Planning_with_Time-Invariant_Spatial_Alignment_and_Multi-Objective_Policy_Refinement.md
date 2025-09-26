# 结合时不变空间对齐与多目标策略精化的自回归端到端规划

发布时间：2025年09月25日

`Agent` `交通运输`

> Autoregressive End-to-End Planning with Time-Invariant Spatial Alignment and Multi-Objective Policy Refinement

# 摘要

> 自回归模型凭借其固有的序列建模能力，成为自动驾驶端到端规划的强大基线。然而，其性能受限于时空错位问题：规划器需以过去的感知数据为依据来生成未来动作，这进而形成不一致的认知视角，限制了这种本应强大方法的性能上限。为此，我们提出时间不变空间对齐（TISA）模块：通过学习将初始环境特征投影到每个未来时间步的一致 ego 中心坐标系中，无需显式预测未来场景即可有效修正智能体的认知视角。此外，我们设计了运动学动作预测头（即预测加速度和横摆角速度），以确保生成符合物理规律的轨迹。最后，我们还引入基于直接偏好优化（DPO）的多目标后训练阶段，从而突破单纯模仿学习的局限。我们的方法能针对特定驾驶行为提供精准反馈，相比标准DPO中单一的整体目标，可提供更细粒度的学习信号。在NAVSIM数据集上，我们的模型在自回归模型中实现了89.8 PDMS的性能，达到当前最优水平。相关视频资料可访问https://tisa-dpo-e2e.github.io/查看。

> The inherent sequential modeling capabilities of autoregressive models make them a formidable baseline for end-to-end planning in autonomous driving. Nevertheless, their performance is constrained by a spatio-temporal misalignment, as the planner must condition future actions on past sensory data. This creates an inconsistent worldview, limiting the upper bound of performance for an otherwise powerful approach. To address this, we propose a Time-Invariant Spatial Alignment (TISA) module that learns to project initial environmental features into a consistent ego-centric frame for each future time step, effectively correcting the agent's worldview without explicit future scene prediction. In addition, we employ a kinematic action prediction head (i.e., acceleration and yaw rate) to ensure physically feasible trajectories. Finally, we introduce a multi-objective post-training stage using Direct Preference Optimization (DPO) to move beyond pure imitation. Our approach provides targeted feedback on specific driving behaviors, offering a more fine-grained learning signal than the single, overall objective used in standard DPO. Our model achieves a state-of-the-art 89.8 PDMS on the NAVSIM dataset among autoregressive models. The video document is available at https://tisa-dpo-e2e.github.io/.

[Arxiv](https://arxiv.org/abs/2509.20938)