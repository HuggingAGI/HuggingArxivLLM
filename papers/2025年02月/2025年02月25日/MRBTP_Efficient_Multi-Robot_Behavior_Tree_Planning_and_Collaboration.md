# **MRBTP：多机器人行为树的高效规划与协作**

发布时间：2025年02月25日

`Agent` `仓库管理` `日常服务`

> MRBTP: Efficient Multi-Robot Behavior Tree Planning and Collaboration

# 摘要

> 多机器人任务规划与协作是机器人领域的核心挑战。尽管行为树（BTs）作为流行的控制架构已能实现单机器人规划，但多机器人BT规划算法的开发仍具挑战性，主要源于协调异构动作空间的复杂性。我们提出了具有完备性和正确性理论保证的多机器人行为树规划（MRBTP）算法。MRBTP通过跨树扩展协调不同BTs中的异构动作以达成团队目标。对于同构动作，我们保留BTs间的备用结构，通过共享意图确保鲁棒性并避免冗余执行。虽然MRBTP支持同构和异构机器人团队的BT生成，但其效率仍有提升空间。因此，我们提出了一种可选插件，当大型语言模型（LLMs）可用时，用于为每个机器人推理与目标相关的动作。这些相关动作可预先规划形成长时域子树，显著提升MRBTP的规划速度和协作效率。我们在仓库管理和日常服务场景中对我们的算法进行了评估。结果表明，MRBTP在不同设置下的鲁棒性和执行效率，以及预训练LLM为MRBTP生成有效任务特定子树的能力。

> Multi-robot task planning and collaboration are critical challenges in robotics. While Behavior Trees (BTs) have been established as a popular control architecture and are plannable for a single robot, the development of effective multi-robot BT planning algorithms remains challenging due to the complexity of coordinating diverse action spaces. We propose the Multi-Robot Behavior Tree Planning (MRBTP) algorithm, with theoretical guarantees of both soundness and completeness. MRBTP features cross-tree expansion to coordinate heterogeneous actions across different BTs to achieve the team's goal. For homogeneous actions, we retain backup structures among BTs to ensure robustness and prevent redundant execution through intention sharing. While MRBTP is capable of generating BTs for both homogeneous and heterogeneous robot teams, its efficiency can be further improved. We then propose an optional plugin for MRBTP when Large Language Models (LLMs) are available to reason goal-related actions for each robot. These relevant actions can be pre-planned to form long-horizon subtrees, significantly enhancing the planning speed and collaboration efficiency of MRBTP. We evaluate our algorithm in warehouse management and everyday service scenarios. Results demonstrate MRBTP's robustness and execution efficiency under varying settings, as well as the ability of the pre-trained LLM to generate effective task-specific subtrees for MRBTP.

[Arxiv](https://arxiv.org/abs/2502.18072)