# CE-GPPO：强化学习中基于梯度保持裁剪策略优化的熵控制

发布时间：2025年09月24日

`强化学习` `基础理论`

> CE-GPPO: Controlling Entropy via Gradient-Preserving Clipping Policy Optimization in Reinforcement Learning

# 摘要

> 强化学习（RL）是优化大型语言模型（LLMs）处理复杂推理任务的有力工具，但其核心挑战在于策略熵的管理——它反映了训练时探索与利用的平衡。现有方法（如近端策略优化（PPO）及其变体）因裁剪机制会丢弃低概率token的宝贵梯度信号。我们通过系统分析熵动态发现，这些被裁剪的token在调节熵演化中扮演着关键却被忽略的角色。为此，我们提出	extbf{C}ontrolling 	extbf{E}ntropy via 	extbf{G}radient-	extbf{P}reserving 	extbf{P}olicy 	extbf{O}ptimization（CE-GPPO）——一种新算法，能以温和且有界的方式重新引入原生PPO中裁剪token的梯度。通过控制裁剪区间外token的梯度幅度，CE-GPPO得以平衡探索与利用。理论推导与实验结果均表明，CE-GPPO能有效缓解熵的不稳定性。在数学推理基准上的大量实验显示，CE-GPPO在不同模型规模下均持续优于性能强劲的基线方法。

> Reinforcement learning (RL) has become a powerful paradigm for optimizing large language models (LLMs) to handle complex reasoning tasks. A core challenge in this process lies in managing policy entropy, which reflects the balance between exploration and exploitation during training. Existing methods, such as proximal policy optimization (PPO) and its variants, discard valuable gradient signals from low-probability tokens due to the clipping mechanism. We systematically analyze the entropy dynamics and reveal that these clipped tokens play a critical yet overlooked role in regulating entropy evolution. We propose \textbf{C}ontrolling \textbf{E}ntropy via \textbf{G}radient-\textbf{P}reserving \textbf{P}olicy \textbf{O}ptimization (CE-GPPO), a novel algorithm that reintroduces gradients from clipped tokens in native PPO in a gentle and bounded manner. By controlling the magnitude of gradients from tokens outside the clipping interval, CE-GPPO is able to achieve an exploration-exploitation trade-off. We provide theoretical justification and empirical evidence showing that CE-GPPO effectively mitigates entropy instability. Extensive experiments on mathematical reasoning benchmarks show that CE-GPPO consistently outperforms strong baselines across different model scales.

[Arxiv](https://arxiv.org/abs/2509.20712)