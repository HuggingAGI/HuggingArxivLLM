# 以人为中心的自动驾驶：一种整合大型语言模型引导与强化学习的快慢架构

发布时间：2025年05月11日

`LLM应用` `自动驾驶` `智能交通`

> Towards Human-Centric Autonomous Driving: A Fast-Slow Architecture Integrating Large Language Model Guidance with Reinforcement Learning

# 摘要

> 自动驾驶借助数据驱动技术取得了显著进展，在标准化任务中展现出稳健性能。然而，现有方法往往忽视用户的个性化偏好，与用户的交互和适应范围十分有限。为解决这些问题，我们提出了一种“快慢”决策框架，结合大型语言模型（LLM）进行高层次指令解析，以及强化学习（RL）代理进行低层次实时决策。在此双系统中，LLM作为“慢”模块，将用户指令转化为结构化指导，而RL代理则作为“快”模块，在严格延迟约束下执行时间关键的操作。通过将高层次决策与快速控制解耦，我们的框架实现了以用户为中心的个性化操作，同时保持了稳健的安全裕度。跨多种驾驶场景的实验评估证明了我们的方法有效性。与基线算法相比，所提出的架构不仅降低了碰撞率，还使驾驶行为更贴近用户偏好，从而实现了以人为中心的驾驶模式。通过在决策层面整合用户指导并结合实时控制进行优化，我们的框架弥合了乘客个体需求与复杂交通环境中安全可靠驾驶所需严谨性的差距。

> Autonomous driving has made significant strides through data-driven techniques, achieving robust performance in standardized tasks. However, existing methods frequently overlook user-specific preferences, offering limited scope for interaction and adaptation with users. To address these challenges, we propose a "fast-slow" decision-making framework that integrates a Large Language Model (LLM) for high-level instruction parsing with a Reinforcement Learning (RL) agent for low-level real-time decision. In this dual system, the LLM operates as the "slow" module, translating user directives into structured guidance, while the RL agent functions as the "fast" module, making time-critical maneuvers under stringent latency constraints. By decoupling high-level decision making from rapid control, our framework enables personalized user-centric operation while maintaining robust safety margins. Experimental evaluations across various driving scenarios demonstrate the effectiveness of our method. Compared to baseline algorithms, the proposed architecture not only reduces collision rates but also aligns driving behaviors more closely with user preferences, thereby achieving a human-centric mode. By integrating user guidance at the decision level and refining it with real-time control, our framework bridges the gap between individual passenger needs and the rigor required for safe, reliable driving in complex traffic environments.

[Arxiv](https://arxiv.org/abs/2505.06875)