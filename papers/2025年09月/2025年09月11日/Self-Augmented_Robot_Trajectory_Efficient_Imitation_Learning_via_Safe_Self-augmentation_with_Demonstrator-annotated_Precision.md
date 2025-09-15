# 自增强机器人轨迹：基于演示者标注精度的安全自增强高效模仿学习

发布时间：2025年09月11日

`Agent` `工业与制造`

> Self-Augmented Robot Trajectory: Efficient Imitation Learning via Safe Self-augmentation with Demonstrator-annotated Precision

# 摘要

> 模仿学习是训练机器人智能体的理想范式，但标准方法通常需要大量数据采集（通过多次演示或随机探索）来保证性能可靠。尽管探索能减少人力投入，却无法保证安全性，还常导致频繁碰撞——尤其在间隙受限任务（如 peg-in-hole）中——因此需要人工重置环境，反而增加了人力负担。本研究提出自增强机器人轨迹（SART）框架，只需单个人类演示即可训练策略，并通过自主增强安全扩展数据集。SART包含两个阶段：（1）人类仅需教学一次，提供单次演示并标注精度边界（表示为关键路点周围的球体），随后进行一次环境重置；（2）机器人自增强，在这些边界内生成多样化、无碰撞的轨迹，并与原始演示衔接。该设计通过最小化人力投入并确保安全性，提升了数据收集效率。模拟与真实世界操作任务的大量评估显示，SART的成功率显著高于仅基于人类演示训练的策略。视频结果详见https://sites.google.com/view/sart-il。

> Imitation learning is a promising paradigm for training robot agents; however, standard approaches typically require substantial data acquisition -- via numerous demonstrations or random exploration -- to ensure reliable performance. Although exploration reduces human effort, it lacks safety guarantees and often results in frequent collisions -- particularly in clearance-limited tasks (e.g., peg-in-hole) -- thereby, necessitating manual environmental resets and imposing additional human burden. This study proposes Self-Augmented Robot Trajectory (SART), a framework that enables policy learning from a single human demonstration, while safely expanding the dataset through autonomous augmentation. SART consists of two stages: (1) human teaching only once, where a single demonstration is provided and precision boundaries -- represented as spheres around key waypoints -- are annotated, followed by one environment reset; (2) robot self-augmentation, where the robot generates diverse, collision-free trajectories within these boundaries and reconnects to the original demonstration. This design improves the data collection efficiency by minimizing human effort while ensuring safety. Extensive evaluations in simulation and real-world manipulation tasks show that SART achieves substantially higher success rates than policies trained solely on human-collected demonstrations. Video results available at https://sites.google.com/view/sart-il .

[Arxiv](https://arxiv.org/abs/2509.09893)