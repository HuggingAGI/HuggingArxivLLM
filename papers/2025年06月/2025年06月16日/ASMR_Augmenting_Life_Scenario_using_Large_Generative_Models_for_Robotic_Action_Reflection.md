# ASMR: 利用大型生成模型提升生活场景，实现机器人动作反思

发布时间：2025年06月16日

`LLM应用

摘要讨论了利用大型语言模型进行数据增强，以提升机器人在多模态任务中的性能，属于LLM的应用层面。` `机器人` `计算机视觉`

> ASMR: Augmenting Life Scenario using Large Generative Models for Robotic Action Reflection

# 摘要

> 设计协助日常活动的机器人时，通过增强用户的请求信息并结合环境中的视觉线索，对于提升意图理解至关重要。这一过程属于多模态分类任务。然而，收集包含视觉和语言元素的大规模数据集用于模型训练，既具挑战性又耗时。为解决此问题，本文提出一种全新的框架，专注于机器人辅助场景下的数据增强，涵盖对话和相关环境图像。该方法利用先进大型语言模型模拟潜在对话和环境背景，随后使用稳定扩散模型生成环境图像。额外生成的数据优化了多模态模型，使其能更准确地根据用户与有限目标数据的交互选择行动。基于真实场景数据集的实验结果表明，我们的方法显著提升了机器人选择行动的能力，并达到当前最先进的性能。

> When designing robots to assist in everyday human activities, it is crucial to enhance user requests with visual cues from their surroundings for improved intent understanding. This process is defined as a multimodal classification task. However, gathering a large-scale dataset encompassing both visual and linguistic elements for model training is challenging and time-consuming. To address this issue, our paper introduces a novel framework focusing on data augmentation in robotic assistance scenarios, encompassing both dialogues and related environmental imagery. This approach involves leveraging a sophisticated large language model to simulate potential conversations and environmental contexts, followed by the use of a stable diffusion model to create images depicting these environments. The additionally generated data serves to refine the latest multimodal models, enabling them to more accurately determine appropriate actions in response to user interactions with the limited target data. Our experimental results, based on a dataset collected from real-world scenarios, demonstrate that our methodology significantly enhances the robot's action selection capabilities, achieving the state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2506.13956)