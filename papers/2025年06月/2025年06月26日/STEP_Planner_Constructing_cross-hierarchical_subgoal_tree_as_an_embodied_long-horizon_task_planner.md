# # STEP 规划器：一种通过构建跨层次子目标树实现的具身长视距任务规划器

发布时间：2025年06月26日

`Agent` `机器人` `任务规划`

> STEP Planner: Constructing cross-hierarchical subgoal tree as an embodied long-horizon task planner

# 摘要

> 在现实环境中部署机器人，具备可靠的长期任务规划能力至关重要。然而，直接使用大型语言模型（LLMs）作为动作序列生成器，往往由于其对长期具身任务的推理能力有限，导致成功率较低。在STEP框架中，我们通过一对闭环模型构建子目标树：子目标分解模型和叶节点终止模型。在此框架下，我们开发了一种从粗到细的层次树结构。子目标分解模型利用基础LLM将复杂目标分解为可管理的子目标，从而扩展子目标树。叶节点终止模型根据环境状态提供实时反馈，决定何时终止树的扩展，确保每个叶节点可以直接转换为基本动作。在VirtualHome WAH-NL基准和真实机器人上的实验表明，STEP实现了长期具身任务的完成，成功率分别达到34%（WAH-NL）和25%（真实机器人），优于现有最优方法。

> The ability to perform reliable long-horizon task planning is crucial for deploying robots in real-world environments. However, directly employing Large Language Models (LLMs) as action sequence generators often results in low success rates due to their limited reasoning ability for long-horizon embodied tasks. In the STEP framework, we construct a subgoal tree through a pair of closed-loop models: a subgoal decomposition model and a leaf node termination model. Within this framework, we develop a hierarchical tree structure that spans from coarse to fine resolutions. The subgoal decomposition model leverages a foundation LLM to break down complex goals into manageable subgoals, thereby spanning the subgoal tree. The leaf node termination model provides real-time feedback based on environmental states, determining when to terminate the tree spanning and ensuring each leaf node can be directly converted into a primitive action. Experiments conducted in both the VirtualHome WAH-NL benchmark and on real robots demonstrate that STEP achieves long-horizon embodied task completion with success rates up to 34% (WAH-NL) and 25% (real robot) outperforming SOTA methods.

[Arxiv](https://arxiv.org/abs/2506.21030)