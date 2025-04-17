# # 摘要
实现人类与机器人动作协调一致：基于多模态示教学习

发布时间：2025年04月14日

`Agent

理由：这篇论文探讨了人类与机器人之间的动作对应性，特别是在非结构化环境下的协作和模仿学习。它提出了一种多模态演示学习框架，结合了视觉和机器人动作数据，以提高人机协作的对齐性。虽然涉及视觉模型和Transformer，但主要关注点是机器人行为和协作，因此归类为Agent。` `机器人协作` `模仿学习`

> Toward Aligning Human and Robot Actions via Multi-Modal Demonstration Learning

# 摘要

> 理解人类与机器人间的动作对应性，对评估决策过程中的对齐性至关重要，尤其在非结构化环境下的人机协作与模仿学习中。我们提出了一种多模态演示学习框架，将人类演示（基于RGB视频）与机器人演示（基于体素化RGB-D空间）进行显式建模。以RH20T数据集中的“抓取与放置”任务为例，我们利用了5名用户在10个不同场景中的数据。我们的方法结合了基于ResNet的视觉编码建模人类意图，以及基于Perceiver Transformer的体素化机器人动作预测。经过2000个训练周期，人类模型准确率达到71.67%，机器人模型达到71.8%，这表明该框架在复杂多模态操作任务中对齐人机行为方面具有潜力。

> Understanding action correspondence between humans and robots is essential for evaluating alignment in decision-making, particularly in human-robot collaboration and imitation learning within unstructured environments. We propose a multimodal demonstration learning framework that explicitly models human demonstrations from RGB video with robot demonstrations in voxelized RGB-D space. Focusing on the "pick and place" task from the RH20T dataset, we utilize data from 5 users across 10 diverse scenes. Our approach combines ResNet-based visual encoding for human intention modeling and a Perceiver Transformer for voxel-based robot action prediction. After 2000 training epochs, the human model reaches 71.67% accuracy, and the robot model achieves 71.8% accuracy, demonstrating the framework's potential for aligning complex, multimodal human and robot behaviors in manipulation tasks.

[Arxiv](https://arxiv.org/abs/2504.11493)