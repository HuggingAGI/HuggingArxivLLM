# 基于跨域技能扩散的上下文内策略适应

发布时间：2025年09月04日

`强化学习` `工业与制造` `交通运输`

> In-Context Policy Adaptation via Cross-Domain Skill Diffusion

# 摘要

> 本文提出了一种面向长周期多任务环境的上下文策略适应（ICPAD）框架，旨在跨域场景中探索基于扩散的技能学习技术。该框架能够让基于技能的强化学习策略快速适应多样的目标域，尤其适用于禁止模型更新且目标域数据有限的严苛场景。具体而言，框架采用跨域技能扩散方案：通过跨域一致的扩散过程，从离线数据中联合高效学习领域无关的原型技能与领域接地的技能适配器。其中，原型技能作为长周期策略通用行为表示的基础单元，可充当连接不同域的“通用语”。此外，为提升上下文适应性能，我们还设计了动态域提示方案，引导基于扩散的技能适配器更好地与目标域对齐。通过Metaworld机器人操作与CARLA自动驾驶场景的实验验证，我们的【数学公式】框架在目标域数据有限的情况下，针对环境动态、智能体形态及任务周期存在差异的各类跨域配置，均实现了优异的策略适应性能。

> In this work, we present an in-context policy adaptation (ICPAD) framework designed for long-horizon multi-task environments, exploring diffusion-based skill learning techniques in cross-domain settings. The framework enables rapid adaptation of skill-based reinforcement learning policies to diverse target domains, especially under stringent constraints on no model updates and only limited target domain data. Specifically, the framework employs a cross-domain skill diffusion scheme, where domain-agnostic prototype skills and a domain-grounded skill adapter are learned jointly and effectively from an offline dataset through cross-domain consistent diffusion processes. The prototype skills act as primitives for common behavior representations of long-horizon policies, serving as a lingua franca to bridge different domains. Furthermore, to enhance the in-context adaptation performance, we develop a dynamic domain prompting scheme that guides the diffusion-based skill adapter toward better alignment with the target domain. Through experiments with robotic manipulation in Metaworld and autonomous driving in CARLA, we show that our $\oursol$ framework achieves superior policy adaptation performance under limited target domain data conditions for various cross-domain configurations including differences in environment dynamics, agent embodiment, and task horizon.

[Arxiv](https://arxiv.org/abs/2509.04535)