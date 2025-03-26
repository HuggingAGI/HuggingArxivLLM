# P3Nav：整合感知、规划与预测的具身导航统一框架

发布时间：2025年03月24日

`Agent` `机器人`

> P3Nav: A Unified Framework for Embodied Navigation Integrating Perception, Planning, and Prediction

# 摘要

> 在语言引导的视觉导航领域，智能体通过自然语言指令在未知环境中定位目标物体。为了在陌生场景中实现可靠的导航，智能体必须具备强大的感知、规划和预测能力。此外，在长期导航过程中，智能体可能会保留不相关和冗余的历史感知信息，导致次优结果。为此，我们提出了 	extbf{P3Nav}，这是一个通过导航和具身问答（EQA）任务上的 	extbf{Multitask Collaboration} 集成 	extbf{P}erception、	extbf{P}lanning 和 	extbf{P}rediction 能力的统一框架，从而显著提升导航性能。P3Nav 还采用了 	extbf{Adaptive 3D-aware History Sampling} 策略，能够高效地利用历史观察信息。借助大语言模型（LLM），P3Nav 能够准确理解多样化的指令和复杂的视觉场景，从而生成适当的导航动作。在 $\mathrm{CHORES}$-$\mathbb{S}$ 基准测试中，P3Nav 在目标物体导航任务上达到了 75\% 的成功率，树立了新的 state-of-the-art 性能标准。

> In language-guided visual navigation, agents locate target objects in unseen environments using natural language instructions. For reliable navigation in unfamiliar scenes, agents must possess strong perception, planning, and prediction capabilities. Additionally, when agents revisit previously explored areas during long-term navigation, they may retain irrelevant and redundant historical perceptions, leading to suboptimal results. In this work, we introduce \textbf{P3Nav}, a unified framework that integrates \textbf{P}erception, \textbf{P}lanning, and \textbf{P}rediction capabilities through \textbf{Multitask Collaboration} on navigation and embodied question answering (EQA) tasks, thereby enhancing navigation performance. Furthermore, P3Nav employs an \textbf{Adaptive 3D-aware History Sampling} strategy to effectively and efficiently utilize historical observations. By leveraging the large language models (LLM), P3Nav comprehends diverse commands and complex visual scenes, resulting in appropriate navigation actions. P3Nav achieves a 75\% success rate in object goal navigation on the $\mathrm{CHORES}$-$\mathbb{S}$ benchmark, setting a new state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2503.18525)