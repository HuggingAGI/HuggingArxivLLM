# # Mini-o3：面向视觉搜索的推理模式与交互轮次扩展

发布时间：2025年09月09日

`强化学习` `基础理论`

> Mini-o3: Scaling Up Reasoning Patterns and Interaction Turns for Visual Search

# 摘要

> 近年来，大型多模态模型借助图像工具与强化学习技术，在视觉问题解决上取得显著进展。然而，现有开源方案推理模式单一、交互轮次受限，难以应对需试错探索的复杂任务。为此，本研究通过扩展工具交互规模突破这一限制，提出Mini-o3系统——该系统能执行深度多轮推理（长达数十步），在复杂视觉搜索任务上达到当前最优性能。我们复现OpenAI o3风格行为的方案包含三个核心组件：首先，构建视觉探针数据集（Visual Probe Dataset），涵盖数千个复杂视觉搜索问题，专为探索性推理设计；其次，开发迭代式数据收集管道，获取具有多样化推理模式（如深度优先搜索、试错法、目标维持）的冷启动轨迹；第三，提出超轮次掩码策略（over-turn masking strategy），避免强化学习中惩罚超轮次响应（即达到最大轮次的响应），从而平衡训练效率与测试扩展性。尽管训练时交互轮次上限仅6轮，模型推理时却能自然生成数十轮轨迹，且准确率随轮次增加而提升。大量实验验证，Mini-o3可产生丰富推理模式与深度思考路径，高效解决复杂视觉搜索问题。

> Recent advances in large multimodal models have leveraged image-based tools with reinforcement learning to tackle visual problems. However, existing open-source approaches often exhibit monotonous reasoning patterns and allow only a limited number of interaction turns, making them inadequate for difficult tasks that require trial-and-error exploration. In this work, we address this limitation by scaling up tool-based interactions and introduce Mini-o3, a system that executes deep, multi-turn reasoning -- spanning tens of steps -- and achieves state-of-the-art performance on challenging visual search tasks. Our recipe for reproducing OpenAI o3-style behaviors comprises three key components. First, we construct the Visual Probe Dataset, a collection of thousands of challenging visual search problems designed for exploratory reasoning. Second, we develop an iterative data collection pipeline to obtain cold-start trajectories that exhibit diverse reasoning patterns, including depth-first search, trial-and-error, and goal maintenance. Third, we propose an over-turn masking strategy that prevents penalization of over-turn responses (those that hit the maximum number of turns) during reinforcement learning, thereby balancing training-time efficiency with test-time scalability. Despite training with an upper bound of only six interaction turns, our model generates trajectories that naturally scale to tens of turns at inference time, with accuracy improving as the number of turns increases. Extensive experiments demonstrate that Mini-o3 produces rich reasoning patterns and deep thinking paths, effectively solving challenging visual search problems.

[Arxiv](https://arxiv.org/abs/2509.07969)