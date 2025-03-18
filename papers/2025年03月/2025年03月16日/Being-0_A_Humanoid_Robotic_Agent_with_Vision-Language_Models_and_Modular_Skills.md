# Being-0：集成视觉-语言模型与模块化技能组件的人形机器人

发布时间：2025年03月16日

`Agent` `机器人` `自主系统`

> Being-0: A Humanoid Robotic Agent with Vision-Language Models and Modular Skills

# 摘要

> 构建能够在现实世界具身任务中达到人类级别表现的自主机器人代理，是人形机器人研究的终极目标。近期研究在基础模型（FMs）的高层认知能力和人形机器人低层技能开发方面取得了显著进展。然而，直接将这些组件结合往往会导致在长时任务中因累积错误而产生的鲁棒性差和效率低的问题，同时不同模块的延迟差异也加剧了这一现象。我们引入了Being-0，一个将基础模型（FM）与模块化技能库相结合的分层代理框架。FM负责高层认知任务，如指令理解、任务规划和推理，而技能库则为低层控制提供稳定的运动和灵巧的操作能力。为了弥合这两个层级之间的差距，我们提出了一种由轻量级视觉-语言模型（VLM）驱动的新型Connector模块。Connector通过将语言规划转化为可执行的技能指令，并动态协调运动和操作，从而增强FM的具身能力，提升任务成功率。除了FM外，Being-0的所有组件均可部署在低成本的车载计算设备上，使得配备灵巧双手和主动视觉的全尺寸人形机器人能够实现高效、实时的性能表现。在大型室内环境中的大量实验表明，Being-0在解决需要复杂导航和操作子任务的复杂、长时任务方面具有显著效果。更多细节和视频，请访问https://beingbeyond.github.io/being-0。

> Building autonomous robotic agents capable of achieving human-level performance in real-world embodied tasks is an ultimate goal in humanoid robot research. Recent advances have made significant progress in high-level cognition with Foundation Models (FMs) and low-level skill development for humanoid robots. However, directly combining these components often results in poor robustness and efficiency due to compounding errors in long-horizon tasks and the varied latency of different modules. We introduce Being-0, a hierarchical agent framework that integrates an FM with a modular skill library. The FM handles high-level cognitive tasks such as instruction understanding, task planning, and reasoning, while the skill library provides stable locomotion and dexterous manipulation for low-level control. To bridge the gap between these levels, we propose a novel Connector module, powered by a lightweight vision-language model (VLM). The Connector enhances the FM's embodied capabilities by translating language-based plans into actionable skill commands and dynamically coordinating locomotion and manipulation to improve task success. With all components, except the FM, deployable on low-cost onboard computation devices, Being-0 achieves efficient, real-time performance on a full-sized humanoid robot equipped with dexterous hands and active vision. Extensive experiments in large indoor environments demonstrate Being-0's effectiveness in solving complex, long-horizon tasks that require challenging navigation and manipulation subtasks. For further details and videos, visit https://beingbeyond.github.io/being-0.

[Arxiv](https://arxiv.org/abs/2503.12533)