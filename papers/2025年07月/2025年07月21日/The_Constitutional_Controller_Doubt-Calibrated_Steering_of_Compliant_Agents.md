# 宪章型控制器：以合规代理为目标的怀疑校准引导

发布时间：2025年07月21日

`Agent` `机器人学` `人工智能`

> The Constitutional Controller: Doubt-Calibrated Steering of Compliant Agents

# 摘要

> 在现代机器人学中，确保自主代理在不确定环境中的可靠且符合规则行为仍然是一个核心挑战。我们的研究展示了神经符号系统如何提供一个强大的解决方案——通过将概率符号白盒推理模型与深度学习方法相结合，同时兼顾显式规则和噪声数据训练的神经模型，实现了结构化推理与灵活表示的完美融合。

我们提出了一种名为宪法控制器（CoCo）的新框架，它通过推理深度概率逻辑程序（如共享交通空间中的约束）来提升代理的安全性和可靠性。此外，我们引入了“自我质疑”概念，通过基于旅行速度、使用的传感器或健康因素等怀疑特征的条件概率密度，赋予系统质疑自身决策的能力。

在一项真实世界中的空中移动研究中，我们验证了CoCo的优势：它不仅使智能自主系统能够学习适当的质疑，还确保了它们在复杂和不确定环境中安全合规地导航。

> Ensuring reliable and rule-compliant behavior of autonomous agents in uncertain environments remains a fundamental challenge in modern robotics. Our work shows how neuro-symbolic systems, which integrate probabilistic, symbolic white-box reasoning models with deep learning methods, offer a powerful solution to this challenge. This enables the simultaneous consideration of explicit rules and neural models trained on noisy data, combining the strength of structured reasoning with flexible representations. To this end, we introduce the Constitutional Controller (CoCo), a novel framework designed to enhance the safety and reliability of agents by reasoning over deep probabilistic logic programs representing constraints such as those found in shared traffic spaces. Furthermore, we propose the concept of self-doubt, implemented as a probability density conditioned on doubt features such as travel velocity, employed sensors, or health factors. In a real-world aerial mobility study, we demonstrate CoCo's advantages for intelligent autonomous systems to learn appropriate doubts and navigate complex and uncertain environments safely and compliantly.

[Arxiv](https://arxiv.org/abs/2507.15478)