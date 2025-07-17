# 通过目标导向的强化学习结合真实物体检测实现灵活且通用的操作能力。

发布时间：2025年07月14日

`Agent` `机器人技术` `人工智能`

> Versatile and Generalizable Manipulation via Goal-Conditioned Reinforcement Learning with Grounded Object Detection

# 摘要

> 通用机器人操作（如抓取任务）对于部署到多样化且动态变化的家庭和工作环境至关重要。近期研究提出采用大规模预训练模型（如大型语言模型和目标检测模型）来增强强化学习中的机器人感知能力。这些通过自监督学习在大型数据集上训练的模型能够处理文本提示并识别场景中的多样化物体，这对强化学习（RL）至关重要，因为在RL中，学习物体交互是一项资源密集型任务。本研究展示了如何将此类模型整合到目标条件强化学习中，以实现通用且多用途的机器人抓取能力。我们采用预训练的目标检测模型，使智能体能够根据文本提示识别物体，并生成用于目标条件的目标掩膜。基于掩膜的目标条件提供了与物体无关的提示，从而提升了特征共享和泛化能力。我们在模拟抓取任务中验证了所提框架的有效性，其中基于掩膜的目标条件在抓取分布内和分布外物体时，始终维持约【数学公式】的成功率，同时确保更快收敛至更高回报。

> General-purpose robotic manipulation, including reach and grasp, is essential for deployment into households and workspaces involving diverse and evolving tasks. Recent advances propose using large pre-trained models, such as Large Language Models and object detectors, to boost robotic perception in reinforcement learning. These models, trained on large datasets via self-supervised learning, can process text prompts and identify diverse objects in scenes, an invaluable skill in RL where learning object interaction is resource-intensive. This study demonstrates how to integrate such models into Goal-Conditioned Reinforcement Learning to enable general and versatile robotic reach and grasp capabilities. We use a pre-trained object detection model to enable the agent to identify the object from a text prompt and generate a mask for goal conditioning. Mask-based goal conditioning provides object-agnostic cues, improving feature sharing and generalization. The effectiveness of the proposed framework is demonstrated in a simulated reach-and-grasp task, where the mask-based goal conditioning consistently maintains a $\sim$90\% success rate in grasping both in and out-of-distribution objects, while also ensuring faster convergence to higher returns.

[Arxiv](https://arxiv.org/abs/2507.10814)