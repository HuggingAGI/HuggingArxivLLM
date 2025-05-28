# Active-O3：借助主动感知，赋能多模态大语言模型

发布时间：2025年05月27日

`Agent` `自动驾驶`

> Active-O3: Empowering Multimodal Large Language Models with Active Perception via GRPO

# 摘要

> 主动视觉，又称主动感知，是指主动选择观察位置和方式，以获取任务相关有用信息的过程。它是人类和先进具身智能体实现高效感知与决策的关键。近期，将多模态大型语言模型（MLLMs）作为机器人系统中的核心规划与决策模块引起了广泛关注。然而，尽管主动感知在具身智能中具有重要意义，但关于如何为MLLMs装备或学习主动感知能力的研究却少之又少。本文首先对基于MLLMs的主动感知任务进行了系统性定义。我们指出，最近提出的GPT-o3模型的放大搜索策略可被视为一种特殊的主动感知形式；然而，它仍然存在搜索效率低下和区域选择不准确的问题。为了解决这些问题，我们提出了ACTIVE-O3，这是一个完全基于强化学习的训练框架，构建于GRPO之上，旨在为MLLMs配备主动感知能力。我们进一步建立了一个全面的基准测试套件，用于评估ACTIVE-O3在一般开放世界任务（如小物体和密集物体定位）以及特定领域场景（包括遥感中的小物体检测、自动驾驶，以及细粒度交互式分割）中的表现。此外，ACTIVE-O3还在V*基准测试中展示了强大的零样本推理能力，而无需依赖任何显式的推理数据。我们希望我们的工作能够提供一个简单易用的代码库和评估协议，以促进未来在MLLMs主动感知方面的研究。

> Active vision, also known as active perception, refers to the process of actively selecting where and how to look in order to gather task-relevant information. It is a critical component of efficient perception and decision-making in humans and advanced embodied agents. Recently, the use of Multimodal Large Language Models (MLLMs) as central planning and decision-making modules in robotic systems has gained extensive attention. However, despite the importance of active perception in embodied intelligence, there is little to no exploration of how MLLMs can be equipped with or learn active perception capabilities. In this paper, we first provide a systematic definition of MLLM-based active perception tasks. We point out that the recently proposed GPT-o3 model's zoom-in search strategy can be regarded as a special case of active perception; however, it still suffers from low search efficiency and inaccurate region selection. To address these issues, we propose ACTIVE-O3, a purely reinforcement learning based training framework built on top of GRPO, designed to equip MLLMs with active perception capabilities. We further establish a comprehensive benchmark suite to evaluate ACTIVE-O3 across both general open-world tasks, such as small-object and dense object grounding, and domain-specific scenarios, including small object detection in remote sensing and autonomous driving, as well as fine-grained interactive segmentation. In addition, ACTIVE-O3 also demonstrates strong zero-shot reasoning abilities on the V* Benchmark, without relying on any explicit reasoning data. We hope that our work can provide a simple codebase and evaluation protocol to facilitate future research on active perception in MLLMs.

[Arxiv](https://arxiv.org/abs/2505.21457)