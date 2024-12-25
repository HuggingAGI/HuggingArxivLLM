# 大型语言模型引导的深度强化学习用于自动驾驶决策

发布时间：2024年12月24日

`LLM应用` `自动驾驶` `深度强化学习`

> Large Language Model guided Deep Reinforcement Learning for Decision Making in Autonomous Driving

# 摘要

> 深度强化学习（DRL）在自动驾驶决策领域展现出可观的潜力。然而，因其学习效率不高，DRL 在复杂驾驶场景中获取合格策略时，需要耗费大量计算资源。而且，借助人类专家的指导来提升 DRL 性能，会带来极高的人力成本，这限制了其实际应用。在本研究中，我们提出了一种全新的大型语言模型（LLM）引导的深度强化学习（LGDRL）框架，以解决自动驾驶车辆的决策难题。在此框架中，将基于 LLM 的驾驶专家融入 DRL，为 DRL 的学习过程给予智能引导。接着，为有效利用 LLM 专家的指导来增强 DRL 决策策略的性能，通过创新的专家策略约束算法和新颖的 LLM 介入交互机制，强化了 DRL 的学习与交互过程。实验结果显示，我们的方法不仅达成了出色的驾驶性能，任务成功率达 90%，而且与前沿的基线算法相比，大幅提高了学习效率和专家指导利用效率。此外，所提出的方法让 DRL 代理在没有 LLM 专家指导的情况下，也能保持稳定可靠的性能。代码和补充视频可在 https://bitmobility.github.io/LGDRL/ 获取。

> Deep reinforcement learning (DRL) shows promising potential for autonomous driving decision-making. However, DRL demands extensive computational resources to achieve a qualified policy in complex driving scenarios due to its low learning efficiency. Moreover, leveraging expert guidance from human to enhance DRL performance incurs prohibitively high labor costs, which limits its practical application. In this study, we propose a novel large language model (LLM) guided deep reinforcement learning (LGDRL) framework for addressing the decision-making problem of autonomous vehicles. Within this framework, an LLM-based driving expert is integrated into the DRL to provide intelligent guidance for the learning process of DRL. Subsequently, in order to efficiently utilize the guidance of the LLM expert to enhance the performance of DRL decision-making policies, the learning and interaction process of DRL is enhanced through an innovative expert policy constrained algorithm and a novel LLM-intervened interaction mechanism. Experimental results demonstrate that our method not only achieves superior driving performance with a 90\% task success rate but also significantly improves the learning efficiency and expert guidance utilization efficiency compared to state-of-the-art baseline algorithms. Moreover, the proposed method enables the DRL agent to maintain consistent and reliable performance in the absence of LLM expert guidance. The code and supplementary videos are available at https://bitmobility.github.io/LGDRL/.

[Arxiv](https://arxiv.org/abs/2412.18511)