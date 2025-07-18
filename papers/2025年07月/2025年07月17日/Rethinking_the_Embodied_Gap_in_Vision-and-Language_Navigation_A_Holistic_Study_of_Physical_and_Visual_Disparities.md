# 从物理与视觉差异的视角重新审视视觉-语言导航中的具身差距问题

发布时间：2025年07月17日

`LLM应用` `机器人` `视觉语言导航`

> Rethinking the Embodied Gap in Vision-and-Language Navigation: A Holistic Study of Physical and Visual Disparities

# 摘要

> 视觉语言导航（VLN）领域虽有诸多突破，但现有方法在机器人运动与控制上的理想假设与实际物理部署中的挑战仍有不小差距。为解决这一难题，我们推出了VLN-PE——一个支持人形、四足及轮式机器人的物理真实感VLN平台。首次，我们在物理机器人环境中全面评估了多种基于第一人称视角的VLN方法，涵盖分类模型（用于单步离散动作预测）、扩散模型（用于密集路点预测）以及无需训练、基于地图的大型语言模型（LLM）与路径规划的集成方案。实验结果表明，受限于机器人观察范围、光照变化及碰撞跌落等物理因素，现有方法性能显著下降，同时揭示了腿部机器人在复杂环境中的运动局限。VLN-PE具有高度扩展性，支持在MP3D之外的场景中无缝集成，从而实现更全面的VLN评估。尽管当前模型在物理部署中泛化能力尚显不足，但VLN-PE为提升跨具身适应性提供了新思路。我们期待本研究发现与工具能激发社区重新审视VLN的局限性，并推动稳健、实用VLN模型的发展。代码已开放获取，详情请访问https://crystalsixone.github.io/vln_pe.github.io/。

> Recent Vision-and-Language Navigation (VLN) advancements are promising, but their idealized assumptions about robot movement and control fail to reflect physically embodied deployment challenges. To bridge this gap, we introduce VLN-PE, a physically realistic VLN platform supporting humanoid, quadruped, and wheeled robots. For the first time, we systematically evaluate several ego-centric VLN methods in physical robotic settings across different technical pipelines, including classification models for single-step discrete action prediction, a diffusion model for dense waypoint prediction, and a train-free, map-based large language model (LLM) integrated with path planning. Our results reveal significant performance degradation due to limited robot observation space, environmental lighting variations, and physical challenges like collisions and falls. This also exposes locomotion constraints for legged robots in complex environments. VLN-PE is highly extensible, allowing seamless integration of new scenes beyond MP3D, thereby enabling more comprehensive VLN evaluation. Despite the weak generalization of current models in physical deployment, VLN-PE provides a new pathway for improving cross-embodiment's overall adaptability. We hope our findings and tools inspire the community to rethink VLN limitations and advance robust, practical VLN models. The code is available at https://crystalsixone.github.io/vln_pe.github.io/.

[Arxiv](https://arxiv.org/abs/2507.13019)