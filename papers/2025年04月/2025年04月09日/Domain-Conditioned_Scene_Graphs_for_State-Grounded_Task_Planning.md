# # 基于领域条件的场景图助力基于状态的任务规划

发布时间：2025年04月09日

`Agent` `机器人` `人工智能`

> Domain-Conditioned Scene Graphs for State-Grounded Task Planning

# 摘要

> 近期的机器人任务规划框架已整合了大型多模态模型（LMMs），例如GPT-4V。为解决这些模型的 grounding 问题，有人建议将管道拆分为感知状态 grounding 和后续基于状态的规划。然而，如我们在本工作中所示，基于 LMM 的方法在细粒度、结构化、特定领域场景理解方面仍存在弱点，这限制了其状态 grounding 能力。为解决这一不足，我们开发了一个更结构化的状态 grounding 框架，其场景表示采用了基于领域条件的场景图。这种表示本质上是可操作的，因为它可以直接映射到经典规划语言（如 PDDL）中的符号状态。我们提供了一个状态 grounding 框架的实例，其中基于领域条件的场景图生成通过一种轻量级的视觉语言方法实现，该方法在与领域相关的物体检测基础上分类领域特定的谓词。在三个不同领域进行评估，我们的方法在状态估计准确性和任务规划成功率方面均显著优于之前的 LMM 基础方法。

> Recent robotic task planning frameworks have integrated large multimodal models (LMMs) such as GPT-4V. To address grounding issues of such models, it has been suggested to split the pipeline into perceptional state grounding and subsequent state-based planning. As we show in this work, the state grounding ability of LMM-based approaches is still limited by weaknesses in granular, structured, domain-specific scene understanding. To address this shortcoming, we develop a more structured state grounding framework that features a domain-conditioned scene graph as its scene representation. We show that such representation is actionable in nature as it is directly mappable to a symbolic state in classical planning languages such as PDDL. We provide an instantiation of our state grounding framework where the domain-conditioned scene graph generation is implemented with a lightweight vision-language approach that classifies domain-specific predicates on top of domain-relevant object detections. Evaluated across three domains, our approach achieves significantly higher state estimation accuracy and task planning success rates compared to the previous LMM-based approaches.

[Arxiv](https://arxiv.org/abs/2504.06661)