# # 基于大规模人类视频的视觉-语言-动作预训练模型 Being-H0

发布时间：2025年07月21日

`其他` `机器人` `计算机视觉`

> Being-H0: Vision-Language-Action Pretraining from Large-Scale Human Videos

# 摘要

> # Being-H0：基于大规模人类视频的灵巧视觉语言动作模型

我们推出 Being-H0，一个基于大规模人类视频训练的灵巧视觉语言动作模型 (VLA)。现有 VLAs 在复杂操作任务中表现乏力，主要因为它们依赖仿真数据或远程操作演示，存在显著的仿真到现实差距，且缺乏规模和多样性。

为突破这一数据瓶颈，我们提出将人类双手作为基础操作器，充分利用网络数据的丰富灵巧性和可扩展性。我们的方法以物理指令微调为核心，这是一种创新的训练范式，整合了基于人类视频的大规模 VLA 预训练、三维推理的物理空间对齐以及针对机器人任务的后训练适应。

此外，我们引入了基于部件的动作分词方法，实现毫米级重建精度，精准建模手部轨迹以优化动作学习。为支持这一范式，我们开发了一个全面的数据整理流水线，整合动作捕捉、VR 和仅 RGB 视频等异构数据源，构建了一个包含数百万基于动作的指令实例的大型数据集。

实验结果表明，Being-H0 在手部动作生成和指令遵循方面表现出色，且性能随模型和数据规模的增加而良好扩展。更重要的是，应用物理指令微调后，Being-H0 在现实世界机器人操作中取得了显著提升。更多细节请访问 https://beingbeyond.github.io/Being-H0。


> We introduce Being-H0, a dexterous Vision-Language-Action model (VLA) trained on large-scale human videos. Existing VLAs struggle with complex manipulation tasks requiring high dexterity and generalize poorly to novel scenarios and tasks, primarily due to their reliance on synthetic data with significant sim-to-real gaps or teleoperated demonstrations lacking scale and diversity. To address this data bottleneck, we propose leveraging human hands as a foundation manipulator, capitalizing on the rich dexterity and scalability present in web data. Our approach centers on physical instruction tuning, a novel training paradigm that combines large-scale VLA pretraining from human videos, physical space alignment for 3D reasoning, and post-training adaptation for robotic tasks. Additionally, we introduce a part-level motion tokenization method which achieves millimeter-level reconstruction accuracy to model precise hand trajectories for action learning. To support our proposed paradigm, we further develop a comprehensive data curation pipeline that integrates heterogeneous sources -- including motion capture, VR, and RGB-only videos -- into a large-scale dataset with millions of motion-based instructional instances. We empirically show the excellence of Being-H0 in hand motion generation and instruction following, and it also scales well with model and data sizes. Importantly, we observe the expected gains of Being-H0 in real-world robotic manipulation as physical instruction tuning is applied. More details are available at https://beingbeyond.github.io/Being-H0.

[Arxiv](https://arxiv.org/abs/2507.15597)