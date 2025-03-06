# SafeVLA：迈向视觉语言动作模型的安全对齐之路

发布时间：2025年03月05日

`Agent` `机器人`

> SafeVLA: Towards Safety Alignment of Vision-Language-Action Model via Safe Reinforcement Learning

# 摘要

> 视觉-语言-动作模型（VLAs）在通用型机器人策略方面展现出了巨大潜力。然而，这些模型在部署过程中面临紧迫的安全挑战，包括对环境、机器人和人类的潜在物理伤害风险。如何将安全性融入VLAs？我们提出了一种名为SafeVLA的新型算法，旨在将安全性整合到VLAs中，确保在真实世界环境中保护环境、机器人硬件和人类的安全。通过在模拟环境中采用大规模约束学习，SafeVLA在安全性和任务性能之间实现了有效平衡。实验表明，SafeVLA在安全性和任务性能方面均优于当前最先进方法，在模拟中分别实现了83.58%和3.85%的平均提升。通过优先考虑安全性，我们的方法消除了高风险行为，将不安全行为的上限降低到当前最先进方法的1/35，从而显著缓解了长尾风险。此外，学习到的安全约束能够推广到各种未见场景，包括多种分布外的扰动和任务。我们的数据、模型和新提出的基准环境可在https://sites.google.com/view/pku-safevla获取。

> Vision-language-action models (VLAs) have shown great potential as generalist robot policies. However, these models pose urgent safety challenges during deployment, including the risk of physical harm to the environment, the robot itself, and humans. How can safety be explicitly incorporated into VLAs? In this work, we propose SafeVLA, a novel algorithm designed to integrate safety into VLAs, ensuring the protection of the environment, robot hardware and humans in real-world settings. SafeVLA effectively balances safety and task performance by employing large-scale constrained learning within simulated environments. We demonstrate that SafeVLA outperforms the current state-of-the-art method in both safety and task performance, achieving average improvements of 83.58% and 3.85%, respectively, in simulation. By prioritizing safety, our approach eliminates high-risk behaviors and reduces the upper bound of unsafe behaviors to 1/35 of that in the current state-of-the-art, thereby significantly mitigating long-tail risks. Furthermore, the learned safety constraints generalize to diverse, unseen scenarios, including multiple out-of-distribution perturbations and tasks. Our data, models and newly proposed benchmark environment are available at https://sites.google.com/view/pku-safevla.

[Arxiv](https://arxiv.org/abs/2503.03480)