# 提升语言引导的机器人操作泛化能力

发布时间：2025年08月04日

`Agent` `机器人` `自动化`

> Improving Generalization of Language-Conditioned Robot Manipulation

# 摘要

> 机器人在操作任务中的控制通常依赖于视觉输入。视觉语言模型（VLMs）的最新进展使得可以通过自然语言指令来调节视觉输入，从而在更广泛的环境中实现对机器人的控制。然而，现有方法需要大量数据来微调VLMs，以便在未见过的环境中运行。本文提出了一种仅需少量演示即可学习物体排列任务的框架。我们提出了一种两阶段框架，将物体排列任务划分为目标定位阶段（用于选择物体）和区域确定阶段（用于放置物体）。我们介绍了一种实例级语义融合模块，该模块将实例级图像裁剪与文本嵌入对齐，使模型能够识别自然语言指令中定义的目标物体。我们在仿真和真实世界的机器人环境中验证了我们的方法。我们的方法在仅需少量演示的情况下进行了微调，提高了泛化能力，并在真实机器人操作场景中展示了零样本学习能力。

> The control of robots for manipulation tasks generally relies on visual input. Recent advances in vision-language models (VLMs) enable the use of natural language instructions to condition visual input and control robots in a wider range of environments. However, existing methods require a large amount of data to fine-tune VLMs for operating in unseen environments. In this paper, we present a framework that learns object-arrangement tasks from just a few demonstrations. We propose a two-stage framework that divides object-arrangement tasks into a target localization stage, for picking the object, and a region determination stage for placing the object. We present an instance-level semantic fusion module that aligns the instance-level image crops with the text embedding, enabling the model to identify the target objects defined by the natural language instructions. We validate our method on both simulation and real-world robotic environments. Our method, fine-tuned with a few demonstrations, improves generalization capability and demonstrates zero-shot ability in real-robot manipulation scenarios.

[Arxiv](https://arxiv.org/abs/2508.02405)