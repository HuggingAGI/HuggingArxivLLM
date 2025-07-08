# MultiGen：通过模拟中的多模态生成学习真实环境下的多模态策略

发布时间：2025年07月03日

`Agent` `机器人` `多模态`

> MultiGen: Using Multimodal Generation in Simulation to Learn Multimodal Policies in Real

# 摘要

> 要在现实世界中有效行动，机器人必须整合多种感官模态。然而，大规模学习多模态策略仍具挑战性。仿真提供了解决方案，尽管视觉得益于高保真仿真器，但声音等其他模态却难以仿真。因此，仿真到现实的迁移主要在视觉任务中成功，而多模态迁移尚未实现。本研究引入MultiGen框架，将大规模生成模型与传统物理仿真器结合，实现多感官仿真。我们以机器人倾倒任务为例，该任务依赖多模态反馈。通过根据仿真视频生成现实音频，我们的方法可在不使用真实机器人数据的情况下，利用视听轨迹进行训练。我们成功实现了零样本迁移至现实世界倾倒任务，涉及新型容器和液体，展示了生成建模在模拟难以建模模态及弥合多模态仿真到现实差距方面的潜力。

> Robots must integrate multiple sensory modalities to act effectively in the real world. Yet, learning such multimodal policies at scale remains challenging. Simulation offers a viable solution, but while vision has benefited from high-fidelity simulators, other modalities (e.g. sound) can be notoriously difficult to simulate. As a result, sim-to-real transfer has succeeded primarily in vision-based tasks, with multimodal transfer still largely unrealized. In this work, we tackle these challenges by introducing MultiGen, a framework that integrates large-scale generative models into traditional physics simulators, enabling multisensory simulation. We showcase our framework on the dynamic task of robot pouring, which inherently relies on multimodal feedback. By synthesizing realistic audio conditioned on simulation video, our method enables training on rich audiovisual trajectories -- without any real robot data. We demonstrate effective zero-shot transfer to real-world pouring with novel containers and liquids, highlighting the potential of generative modeling to both simulate hard-to-model modalities and close the multimodal sim-to-real gap.

[Arxiv](https://arxiv.org/abs/2507.02864)