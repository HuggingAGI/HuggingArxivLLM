# 老鼠对决AI：视觉鲁棒性与神经对齐的神经行为学基准

发布时间：2025年09月17日

`强化学习` `基础理论`

> Mouse vs. AI: A Neuroethological Benchmark for Visual Robustness and Neural Alignment

# 摘要

> 在现实环境中，视觉鲁棒性仍是现代强化学习智能体的核心瓶颈。相比之下，老鼠等生物系统对环境变化展现出惊人的适应力——即便视觉输入质量下降且接触时间极短，仍能保持稳定表现。受这种差距的启发，我们提出“老鼠 vs. AI：鲁棒觅食竞赛”（Mouse vs. AI: Robust Foraging Competition）：一个全新的生物启发式视觉鲁棒性基准，用于测试强化学习（RL）智能体的泛化能力——这些智能体经过训练，能在虚拟环境中导航至视觉提示的目标。参与者需训练智能体在自然主义3D Unity环境中完成视觉引导的觅食任务，并根据其泛化至未见过的、生态真实的视觉扰动的能力进行评估。该竞赛的独特之处在于其生物学基础：真实老鼠会执行相同任务，参与者将获得行为表现数据和大规模神经记录（覆盖视觉皮层的19,000多个神经元）用于基准测试。竞赛设有两个赛道：（1）视觉鲁棒性赛道：评估对预留视觉扰动的泛化能力；（2）神经对齐赛道：通过线性读出评估智能体的内部表征对老鼠视觉皮层活动的预测能力。我们提供完整的Unity环境、用于验证的雾扰动训练条件、基线近端策略优化（PPO）智能体，以及丰富的多模态数据集。通过基于共享的、行为驱动的任务，该竞赛架起了强化学习、计算机视觉与神经科学之间的桥梁，推动鲁棒、可泛化且受生物启发的AI的发展。

> Visual robustness under real-world conditions remains a critical bottleneck for modern reinforcement learning agents. In contrast, biological systems such as mice show remarkable resilience to environmental changes, maintaining stable performance even under degraded visual input with minimal exposure. Inspired by this gap, we propose the Mouse vs. AI: Robust Foraging Competition, a novel bioinspired visual robustness benchmark to test generalization in reinforcement learning (RL) agents trained to navigate a virtual environment toward a visually cued target. Participants train agents to perform a visually guided foraging task in a naturalistic 3D Unity environment and are evaluated on their ability to generalize to unseen, ecologically realistic visual perturbations. What sets this challenge apart is its biological grounding: real mice performed the same task, and participants receive both behavioral performance data and large-scale neural recordings (over 19,000 neurons across visual cortex) for benchmarking. The competition features two tracks: (1) Visual Robustness, assessing generalization across held-out visual perturbations; and (2) Neural Alignment, evaluating how well agents' internal representations predict mouse visual cortical activity via a linear readout. We provide the full Unity environment, a fog-perturbed training condition for validation, baseline proximal policy optimization (PPO) agents, and a rich multimodal dataset. By bridging reinforcement learning, computer vision, and neuroscience through a shared, behaviorally grounded task, this challenge advances the development of robust, generalizable, and biologically inspired AI.

[Arxiv](https://arxiv.org/abs/2509.14446)