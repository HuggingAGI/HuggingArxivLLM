# 针对特定任务的大语言模型，采用逐步自适应的方法整合监督微调与强化学习

发布时间：2025年05月19日

`LLM理论` `学术研究`

> Step-wise Adaptive Integration of Supervised Fine-tuning and Reinforcement Learning for Task-Specific LLMs

# 摘要

> 大型语言模型（LLMs）在数学推理和逻辑问题解决方面表现出色，尤其擅长数学推理和逻辑问题解决。当前流行的训练范式主要通过监督微调（SFT）和强化学习（RL）来提升模型的推理能力。然而，单独使用SFT或RL时，各自面临不同的挑战：SFT可能过拟合，而RL容易模式坍塌。

为应对这些挑战，我们受到人类推理培养中课程学习-测验机制的启发，提出了SASR，这是一种分步自适应混合训练框架。SASR理论上统一了SFT和RL，并在整个优化过程中动态平衡两者。具体来说，SASR首先通过SFT预热，建立基础推理能力，然后基于梯度范数和相对于原始分布的散度，使用自适应动态调整算法，将SFT与在线RL方法GRPO无缝结合。通过监控LLMs的训练状态并按顺序调整训练过程，SASR确保了训练方案之间的平滑过渡，在保持核心推理能力的同时探索不同的路径。

实验结果表明，SASR在性能上显著优于SFT、RL和静态混合训练方法。

> Large language models (LLMs) excel at mathematical reasoning and logical problem-solving. The current popular training paradigms primarily use supervised fine-tuning (SFT) and reinforcement learning (RL) to enhance the models' reasoning abilities. However, when using SFT or RL alone, there are respective challenges: SFT may suffer from overfitting, while RL is prone to mode collapse. The state-of-the-art methods have proposed hybrid training schemes. However, static switching faces challenges such as poor generalization across different tasks and high dependence on data quality. In response to these challenges, inspired by the curriculum learning-quiz mechanism in human reasoning cultivation, We propose SASR, a step-wise adaptive hybrid training framework that theoretically unifies SFT and RL and dynamically balances the two throughout optimization. SASR uses SFT for initial warm-up to establish basic reasoning skills, and then uses an adaptive dynamic adjustment algorithm based on gradient norm and divergence relative to the original distribution to seamlessly integrate SFT with the online RL method GRPO. By monitoring the training status of LLMs and adjusting the training process in sequence, SASR ensures a smooth transition between training schemes, maintaining core reasoning abilities while exploring different paths. Experimental results demonstrate that SASR outperforms SFT, RL, and static hybrid training methods.

[Arxiv](https://arxiv.org/abs/2505.13026)