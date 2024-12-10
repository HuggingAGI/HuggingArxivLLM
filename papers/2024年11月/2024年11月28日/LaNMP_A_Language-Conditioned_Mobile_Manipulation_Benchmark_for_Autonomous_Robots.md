# LaNMP：专为自主机器人打造的语言条件移动操作基准

发布时间：2024年11月28日

`Agent` `机器人`

> LaNMP: A Language-Conditioned Mobile Manipulation Benchmark for Autonomous Robots

# 摘要

> 随着遵循自然语言的机器人能力更强、应用更广，我们需要一个基准来全面开发和评估它们在大型、多样化环境中解决长期移动操作任务的能力。要应对这一挑战，机器人得运用视觉和语言理解、导航及操作等能力。现有的数据集未整合所有这些方面，这限制了其作为基准的有效性。为弥补这一差距，我们推出了语言、导航、操作、感知（LaNMP，读音为 Lamp）数据集，并展示了整合这四种能力和各种模式的益处。LaNMP 涵盖了在八个模拟和真实世界环境中、由自然语言指定的长期房间到房间的取放任务的 574 条轨迹。每条轨迹包含超过 20 个属性，比如 RGB-D 图像、分割以及机器人身体、末端执行器和抓取物体的姿态。我们在模拟中对两个模型进行了微调与测试，并在物理机器人上评估了第三个模型，以证明该基准在开发和评估中的适用性，同时让模型更具样本效率。与人类相比，这些模型表现欠佳；不过，在提升模型样本效率方面展现出潜力，这表明利用我们的基准开发更具样本效率的多模态移动操作模型有很大的发展空间。

> As robots that follow natural language become more capable and prevalent, we need a benchmark to holistically develop and evaluate their ability to solve long-horizon mobile manipulation tasks in large, diverse environments. To tackle this challenge, robots must use visual and language understanding, navigation, and manipulation capabilities. Existing datasets do not integrate all these aspects, restricting their efficacy as benchmarks. To address this gap, we present the Language, Navigation, Manipulation, Perception (LaNMP, pronounced Lamp) dataset and demonstrate the benefits of integrating these four capabilities and various modalities. LaNMP comprises 574 trajectories across eight simulated and real-world environments for long-horizon room-to-room pick-and-place tasks specified by natural language. Every trajectory consists of over 20 attributes, including RGB-D images, segmentations, and the poses of the robot body, end-effector, and grasped objects. We fine-tuned and tested two models in simulation, and evaluated a third on a physical robot, to demonstrate the benchmark's applicability in development and evaluation, as well as making models more sample efficient. The models performed suboptimally compared to humans; however, showed promise in increasing model sample efficiency, indicating significant room for developing more sample efficient multimodal mobile manipulation models using our benchmark.

[Arxiv](https://arxiv.org/abs/2412.05313)