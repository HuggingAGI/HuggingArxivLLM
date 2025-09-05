# 迈向大型语言模型后训练的统一视角

发布时间：2025年09月04日

`LLM理论` `基础理论`

> Towards a Unified View of Large Language Model Post-Training

# 摘要

> 现代语言模型的后训练数据主要有两大来源：在线（模型生成轨迹）数据与离线（人类或其他模型演示）数据。这两类数据通常分别用于强化学习（RL）和监督微调（SFT）等方法。本文提出，这些方法并非相互矛盾，而是同一优化过程的不同表现形式。我们推导出统一策略梯度估计器，并证明各类后训练方法的计算过程实则是在不同数据分布假设与偏差-方差权衡下，共同目标函数的梯度形式。该梯度估计器由四个可互换组件构成：稳定掩码、参考策略分母、优势估计及似然梯度。基于上述理论发现，我们提出混合后训练（HPT）算法，该算法能动态选择不同的训练信号。HPT旨在高效利用演示数据并实现稳定探索，同时不牺牲已习得的推理模式。我们通过大量实验和消融研究验证了统一理论框架与HPT的有效性。在六项数学推理基准测试和两组分布外任务中，HPT在不同规模与系列的模型上均持续优于性能强劲的基线模型。

> Two major sources of training data exist for post-training modern language models: online (model-generated rollouts) data, and offline (human or other-model demonstrations) data. These two types of data are typically used by approaches like Reinforcement Learning (RL) and Supervised Fine-Tuning (SFT), respectively. In this paper, we show that these approaches are not in contradiction, but are instances of a single optimization process. We derive a Unified Policy Gradient Estimator, and present the calculations of a wide spectrum of post-training approaches as the gradient of a common objective under different data distribution assumptions and various bias-variance tradeoffs. The gradient estimator is constructed with four interchangeable parts: stabilization mask, reference policy denominator, advantage estimate, and likelihood gradient. Motivated by our theoretical findings, we propose Hybrid Post-Training (HPT), an algorithm that dynamically selects different training signals. HPT is designed to yield both effective exploitation of demonstration and stable exploration without sacrificing learned reasoning patterns. We provide extensive experiments and ablation studies to verify the effectiveness of our unified theoretical framework and HPT. Across six mathematical reasoning benchmarks and two out-of-distribution suites, HPT consistently surpasses strong baselines across models of varying scales and families.

[Arxiv](https://arxiv.org/abs/2509.04419)