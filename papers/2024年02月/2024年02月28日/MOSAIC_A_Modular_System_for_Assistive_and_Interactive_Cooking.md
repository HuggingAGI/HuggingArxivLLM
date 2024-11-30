# MOSAIC——一款模块化设计的智能烹饪系统，旨在提供辅助与互动式的烹饪体验。

发布时间：2024年02月28日

`Agent`

> MOSAIC: A Modular System for Assistive and Interactive Cooking

# 摘要

> MOSAIC 是一款专为家庭机器人打造的模块化架构，旨在协助完成如与普通用户共同烹饪等复杂协作任务。它能无缝与人协同工作，运用自然语言与用户交流，调配多台机器人，并掌握大量日常物体词汇。在内核设计上，MOSAIC 独具匠心，结合大规模预训练模型以应对语言和图像识别等一般任务，同时采用针对特定任务优化的精简模块。我们通过 60 场双机器人与真人用户携手制作 6 种菜谱的端到端试验，全方位验证了 MOSAIC 的效能。此外，通过 180 轮视觉操控拾取、60 轮人体动作预测以及 46 次在线用户对任务计划器的实际评估，对各模块功能进行了深入测试。实验结果显示，MOSAIC 在与真人用户的实际端到端协作中表现出色，成功完成了 6 种不同菜谱的 68.3%（即 41/60）协作烹饪任务，子任务完成率高达 91.6%。最后，我们探讨了当前系统存在的局限以及这一领域所面临的激动人心的挑战，项目官网为 https://portal-cornell.github.io/MOSAIC/。

> We present MOSAIC, a modular architecture for home robots to perform complex collaborative tasks, such as cooking with everyday users. MOSAIC tightly collaborates with humans, interacts with users using natural language, coordinates multiple robots, and manages an open vocabulary of everyday objects. At its core, MOSAIC employs modularity: it leverages multiple large-scale pre-trained models for general tasks like language and image recognition, while using streamlined modules designed for task-specific control. We extensively evaluate MOSAIC on 60 end-to-end trials where two robots collaborate with a human user to cook a combination of 6 recipes. We also extensively test individual modules with 180 episodes of visuomotor picking, 60 episodes of human motion forecasting, and 46 online user evaluations of the task planner. We show that MOSAIC is able to efficiently collaborate with humans by running the overall system end-to-end with a real human user, completing 68.3% (41/60) collaborative cooking trials of 6 different recipes with a subtask completion rate of 91.6%. Finally, we discuss the limitations of the current system and exciting open challenges in this domain. The project's website is at https://portal-cornell.github.io/MOSAIC/

[Arxiv](https://arxiv.org/abs/2402.18796)