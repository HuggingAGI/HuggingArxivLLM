# ConfClip：面向大型语言模型（LLMs）强化学习的置信度加权与截断奖励

发布时间：2025年09月22日

`强化学习` `基础理论`

> ConfClip: Confidence-Weighted and Clipped Reward for Reinforcement Learning in LLMs

# 摘要

> 强化学习（RL）已成为在预训练与指令微调之外优化大型语言模型（LLMs）的标准范式。其中，带可验证奖励的强化学习（RLVR）是一个重要分支——它借助自动可验证结果（如正确性、可执行性）生成奖励信号。尽管高效，该框架却存在两个关键局限：一是二元反馈过于稀疏，难以捕捉推理过程的质量细节；二是粗粒度奖励可能引发梯度消失问题。受人类学习机制的启发，我们提出一种强化学习技术，将可验证结果与模型自身的置信度估计相融合。这种联合设计丰富了奖励信号，不仅提供更细粒度的反馈，还能隐式监督推理过程。实验结果显示，我们提出的方法在多个数据集上均提升了强化学习性能，减少了推理阶段的token消耗，且额外训练成本微乎其微。此外，它还可作为插件模块，增强其他最先进的强化学习方法。

> Reinforcement learning (RL) has become a standard paradigm for refining large language models (LLMs) beyond pre-training and instruction tuning. A prominent line of work is RL with verifiable rewards (RLVR), which leverages automatically verifiable outcomes (e.g., correctness or executability) to generate reward signals. While efficient, this framework faces two key limitations: First, its binary feedback is too sparse to capture the quality of the reasoning process. Second, its coarse-grained rewards potentially lead to vanishing gradients. Inspired by observations from human learning, we introduce a RL technique that integrates verifiable outcomes with the model's own confidence estimates. This joint design enriches the reward signal, providing finer-grained feedback and implicitly supervising the reasoning process. Experimental results demonstrate that our proposed method enhances RL performance across multiple datasets and reduces token consumption during inference, while incurring negligible additional training cost. Moreover, it can be used as a plug-in module to enhance other state-of-the-art RL methods.

[Arxiv](https://arxiv.org/abs/2509.17730)