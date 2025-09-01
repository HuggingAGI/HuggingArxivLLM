# Re:Frame——从联想记忆中提取经验

发布时间：2025年08月26日

`强化学习` `工业与制造`

> Re:Frame -- Retrieving Experience From Associative Memory

# 摘要

> 当难以获取或收集大型专家数据集不切实际时，离线强化学习（RL）往往需要处理次优数据。这种限制导致智能体难以泛化并达到高性能，因为它们主要依赖不完善或不一致的轨迹进行学习。因此，核心难题在于如何充分利用稀缺的专家演示和海量低质量数据。我们发现，即使仅融入少量专家经验，也能大幅提升RL智能体的性能。为此，我们提出Re:Frame（从关联记忆中检索经验）——一个插件模块，它为标准离线RL策略（如决策Transformer）配备小型外部关联记忆缓冲区（AMB），该缓冲区由从独立数据集中提取的专家轨迹填充。在低质量数据训练阶段，该策略通过基于内容的关联从AMB中检索专家数据并整合到决策过程中；评估时则查询同一个AMB。整个过程无需环境交互，也无需修改骨干架构。在D4RL MuJoCo任务中，仅使用60条专家轨迹（占6000条轨迹数据集的0.1%），Re:Frame就在四个设置中的三个上持续优于强大的决策Transformer基线，性能提升高达10.7个标准化点。这些结果表明，Re:Frame为注入稀缺专家知识提供了一种简单高效的数据利用方式，能显著改善基于低质量数据集的离线RL性能。

> Offline reinforcement learning (RL) often deals with suboptimal data when collecting large expert datasets is unavailable or impractical. This limitation makes it difficult for agents to generalize and achieve high performance, as they must learn primarily from imperfect or inconsistent trajectories. A central challenge is therefore how to best leverage scarce expert demonstrations alongside abundant but lower-quality data. We demonstrate that incorporating even a tiny amount of expert experience can substantially improve RL agent performance. We introduce Re:Frame (Retrieving Experience From Associative Memory), a plug-in module that augments a standard offline RL policy (e.g., Decision Transformer) with a small external Associative Memory Buffer (AMB) populated by expert trajectories drawn from a separate dataset. During training on low-quality data, the policy learns to retrieve expert data from the Associative Memory Buffer (AMB) via content-based associations and integrate them into decision-making; the same AMB is queried at evaluation. This requires no environment interaction and no modifications to the backbone architecture. On D4RL MuJoCo tasks, using as few as 60 expert trajectories (0.1% of a 6000-trajectory dataset), Re:Frame consistently improves over a strong Decision Transformer baseline in three of four settings, with gains up to +10.7 normalized points. These results show that Re:Frame offers a simple and data-efficient way to inject scarce expert knowledge and substantially improve offline RL from low-quality datasets.

[Arxiv](https://arxiv.org/abs/2508.19344)