# DriveMoE：视觉-语言-动作模型的MoE方案，应用于端到端自动驾驶

发布时间：2025年05月22日

`Agent` `自动驾驶` `人工智能`

> DriveMoE: Mixture-of-Experts for Vision-Language-Action Model in End-to-End Autonomous Driving

# 摘要

> 端到端自动驾驶（E2E-AD）需要有效处理多视图传感器数据，并稳健应对复杂多样的驾驶场景，尤其是像急转弯这样的罕见操作。大型语言模型（LLMs）中专家混合模型（MoE）架构的成功表明，参数专用化能够实现强大的可扩展性。我们提出了 DriveMoE，一个基于 MoE 的新型 E2E-AD 框架，包含场景专用视觉 MoE 和技能专用动作 MoE。DriveMoE 基于我们的 $π_0$ 视觉-语言-动作（VLA）基线（源自具身智能领域），称为 Drive-$π_0$。具体而言，我们通过训练路由器动态选择与驾驶上下文相关的摄像头，将视觉 MoE 添加到 Drive-$π_0$ 中。这种设计模仿了人类驾驶认知，驾驶员会关注关键视觉线索，而非穷尽处理所有视觉信息。此外，我们通过训练另一个路由器激活不同驾驶行为的专用专家模块，添加了动作 MoE。通过显式的驾驶行为专用化，DriveMoE 能够处理多样化场景，而不会受到模式平均化的影响。在 Bench2Drive 的闭环评估实验中，DriveMoE 达到了 state-of-the-art（SOTA）性能，证明了视觉和动作 MoE 在自动驾驶任务中的有效性。我们将会发布 DriveMoE 和 Drive-$π_0$ 的代码和模型。


> End-to-end autonomous driving (E2E-AD) demands effective processing of multi-view sensory data and robust handling of diverse and complex driving scenarios, particularly rare maneuvers such as aggressive turns. Recent success of Mixture-of-Experts (MoE) architecture in Large Language Models (LLMs) demonstrates that specialization of parameters enables strong scalability. In this work, we propose DriveMoE, a novel MoE-based E2E-AD framework, with a Scene-Specialized Vision MoE and a Skill-Specialized Action MoE. DriveMoE is built upon our $π_0$ Vision-Language-Action (VLA) baseline (originally from the embodied AI field), called Drive-$π_0$. Specifically, we add Vision MoE to Drive-$π_0$ by training a router to select relevant cameras according to the driving context dynamically. This design mirrors human driving cognition, where drivers selectively attend to crucial visual cues rather than exhaustively processing all visual information. In addition, we add Action MoE by training another router to activate specialized expert modules for different driving behaviors. Through explicit behavioral specialization, DriveMoE is able to handle diverse scenarios without suffering from modes averaging like existing models. In Bench2Drive closed-loop evaluation experiments, DriveMoE achieves state-of-the-art (SOTA) performance, demonstrating the effectiveness of combining vision and action MoE in autonomous driving tasks. We will release our code and models of DriveMoE and Drive-$π_0$.

[Arxiv](https://arxiv.org/abs/2505.16278)