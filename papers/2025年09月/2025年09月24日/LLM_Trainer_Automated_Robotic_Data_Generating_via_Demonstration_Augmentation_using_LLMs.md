# LLM Trainer：基于LLMs演示增强的自动化机器人数据生成

发布时间：2025年09月24日

`LLM应用` `工业与制造`

> LLM Trainer: Automated Robotic Data Generating via Demonstration Augmentation using LLMs

# 摘要

> 我们提出了LLM Trainer——一种全自动流程，它借助大型语言模型（LLMs）的世界知识，能将少量人类演示（甚至仅需一个）转化为用于模仿学习的大规模机器人数据集。该方法将演示生成分解为两个关键步骤：（1）离线演示标注，用于提取关键帧、显著对象及姿态-对象关系；（2）在线关键姿态重定向，结合初始观察将这些关键帧适配到新场景。基于这些调整后的关键点，系统通过变形原始演示生成新轨迹并执行，成功的演示会被保存。由于标注可跨场景复用，我们采用汤普森采样优化标注过程，大幅提升了生成成功率。在多任务评估中，我们的数据标注方法性能持续优于专家设计的基线方法。此外，我们还提出了一种集成策略框架，将优化后的LLM前馈规划与学习到的反馈模仿学习控制器相融合。最后，我们在Franka Emika Panda机器人上验证了硬件可行性。更多资料与演示视频详见项目网站：https://sites.google.com/andrew.cmu.edu/llm-trainer

> We present LLM Trainer, a fully automated pipeline that leverages the world knowledge of Large Language Models (LLMs) to transform a small number of human demonstrations (as few as one) into a large robot dataset for imitation learning. Our approach decomposes demonstration generation into two steps: (1) offline demonstration annotation that extracts keyframes, salient objects, and pose-object relations; and (2) online keypose retargeting that adapts those keyframes to a new scene, given an initial observation. Using these modified keypoints, our system warps the original demonstration to generate a new trajectory, which is then executed, and the resulting demo, if successful, is saved. Because the annotation is reusable across scenes, we use Thompson sampling to optimize the annotation, significantly improving generation success rate. We evaluate our method on a range of tasks, and find that our data annotation method consistently outperforms expert-engineered baselines. We further show an ensemble policy that combines the optimized LLM feed-forward plan with a learned feedback imitation learning controller. Finally, we demonstrate hardware feasibility on a Franka Emika Panda robot. For additional materials and demonstration videos, please see the project website: https://sites.google.com/andrew.cmu.edu/llm-trainer

[Arxiv](https://arxiv.org/abs/2509.20070)