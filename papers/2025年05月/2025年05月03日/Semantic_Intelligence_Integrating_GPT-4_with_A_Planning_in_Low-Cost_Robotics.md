# # 语义智能：融合 GPT-4 与规划能力，探索语义智能在低成本机器人中的创新应用

发布时间：2025年05月03日

`LLM应用

分类解释：这篇论文探讨了将大型语言模型（GPT-4）应用于机器人导航系统中，具体是将其与传统的路径规划算法（如A*）结合，以提升机器人的语义理解和任务处理能力。论文的重点在于展示如何通过LLM的实际应用来增强机器人的智能行为，属于LLM的实际应用案例。` `机器人` `人工智能`

> Semantic Intelligence: Integrating GPT-4 with A Planning in Low-Cost Robotics

# 摘要

> # 摘要
传统机器人导航通常依赖固定的状态机结构和纯几何路径规划器，这限制了机器人对高层语义指令的理解能力。本文首先评估了GPT-4作为路径规划器与A*算法相比的能力，随后提出了一种在ROS2 Humble平台上运行的低成本机器人平台上将GPT-4的语义推理与A*相结合的混合规划框架。我们的方法通过基于提示的GPT-4推理来处理任务逻辑，从而避免了显式有限状态机（FSM）的编码需求，同时保留了A*算法计算的精确路径。GPT-4模块能够理解指令和环境线索的语义信息（例如，识别有毒障碍物或拥挤区域以避免，或理解需要选择备用路线的低电量情况），并通过障碍物缓冲机制动态调整机器人的占用栅格，以实施语义约束。我们展示了针对顺序任务的多步推理能力，例如首先导航到资源目标，然后安全到达最终目的地。在配备顶置摄像头和Raspberry Pi Zero 2W的Petoi Bittle机器人上进行的实验，将传统的A*算法与GPT-4辅助规划进行了对比。实验结果表明，虽然A*在基本路线生成和避障方面速度更快、更准确，但集成GPT-4的系统在纯几何规划器无法完成的语义任务上实现了96-100%的成功率。这项工作展示了如何通过利用大型语言模型的推理能力，以最小的硬件投入，使低成本机器人展现出智能且情境感知的行为，而无需进行微调。

> Classical robot navigation often relies on hardcoded state machines and purely geometric path planners, limiting a robot's ability to interpret high-level semantic instructions. In this paper, we first assess GPT-4's ability to act as a path planner compared to the A* algorithm, then present a hybrid planning framework that integrates GPT-4's semantic reasoning with A* on a low-cost robot platform operating on ROS2 Humble. Our approach eliminates explicit finite state machine (FSM) coding by using prompt-based GPT-4 reasoning to handle task logic while maintaining the accurate paths computed by A*. The GPT-4 module provides semantic understanding of instructions and environmental cues (e.g., recognizing toxic obstacles or crowded areas to avoid, or understanding low-battery situations requiring alternate route selection), and dynamically adjusts the robot's occupancy grid via obstacle buffering to enforce semantic constraints. We demonstrate multi-step reasoning for sequential tasks, such as first navigating to a resource goal and then reaching a final destination safely. Experiments on a Petoi Bittle robot with an overhead camera and Raspberry Pi Zero 2W compare classical A* against GPT-4-assisted planning. Results show that while A* is faster and more accurate for basic route generation and obstacle avoidance, the GPT-4-integrated system achieves high success rates (96-100%) on semantic tasks that are infeasible for pure geometric planners. This work highlights how affordable robots can exhibit intelligent, context-aware behaviors by leveraging large language model reasoning with minimal hardware and no fine-tuning.

[Arxiv](https://arxiv.org/abs/2505.01931)