# STRAP：用于强化策略学习的机器人子轨迹检索

发布时间：2024年12月19日

`Agent` `机器人` `机器学习`

> STRAP: Robot Sub-Trajectory Retrieval for Augmented Policy Learning

# 摘要

> 机器人学习中，预先收集的数据集在规模、多样性和复杂性上大幅增长，这与自然语言处理和计算机视觉等领域的趋势相似。许多机器人学习方法把这类数据集当作多任务专家数据，通过广泛训练来学习多任务、通才策略。需注意的是，这些通才策略虽能提升众多任务的平均性能，但和特定任务的专家策略相比，由于数据分区间存在负迁移，在任何一项任务上，其性能往往并非最优。在本研究中，鉴于所遇场景，我们提倡在部署时训练策略的模式：并非以零样本方式将预训练策略部署到未知问题上，而是在测试时直接于相关数据上进行非参数式的检索与训练模型。另外，我们发现许多机器人任务有着大量的低级行为共享，“子”轨迹粒度的检索能显著提升数据利用率、泛化能力和策略适应新问题的鲁棒性。相比之下，现有的全轨迹检索方法往往数据利用不充分，且错过共享的跨任务内容。本工作提出了 STRAP，这是一种利用预先训练的视觉基础模型和动态时间规整，以稳健方式从大型训练语料库中检索轨迹子序列的技术。STRAP 在模拟和真实实验中都超越了先前的检索算法和多任务学习方法，展现出在现实世界中扩展至更大离线数据集的能力，以及仅通过少量真实世界的演示就能学习稳健控制策略的能力。

> Robot learning is witnessing a significant increase in the size, diversity, and complexity of pre-collected datasets, mirroring trends in domains such as natural language processing and computer vision. Many robot learning methods treat such datasets as multi-task expert data and learn a multi-task, generalist policy by training broadly across them. Notably, while these generalist policies can improve the average performance across many tasks, the performance of generalist policies on any one task is often suboptimal due to negative transfer between partitions of the data, compared to task-specific specialist policies. In this work, we argue for the paradigm of training policies during deployment given the scenarios they encounter: rather than deploying pre-trained policies to unseen problems in a zero-shot manner, we non-parametrically retrieve and train models directly on relevant data at test time. Furthermore, we show that many robotics tasks share considerable amounts of low-level behaviors and that retrieval at the "sub"-trajectory granularity enables significantly improved data utilization, generalization, and robustness in adapting policies to novel problems. In contrast, existing full-trajectory retrieval methods tend to underutilize the data and miss out on shared cross-task content. This work proposes STRAP, a technique for leveraging pre-trained vision foundation models and dynamic time warping to retrieve sub-sequences of trajectories from large training corpora in a robust fashion. STRAP outperforms both prior retrieval algorithms and multi-task learning methods in simulated and real experiments, showing the ability to scale to much larger offline datasets in the real world as well as the ability to learn robust control policies with just a handful of real-world demonstrations.

[Arxiv](https://arxiv.org/abs/2412.15182)