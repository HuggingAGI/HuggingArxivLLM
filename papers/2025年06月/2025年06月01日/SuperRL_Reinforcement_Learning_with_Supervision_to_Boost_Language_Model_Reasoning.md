# SuperRL：强化监督学习，助力语言模型推理能力提升

发布时间：2025年06月01日

`LLM应用

理由：这篇论文讨论了如何在强化学习框架中结合离线监督数据来提升大型语言模型在复杂推理任务中的表现，属于LLM的应用层面研究。` `教育技术` `学术研究`

> SuperRL: Reinforcement Learning with Supervision to Boost Language Model Reasoning

# 摘要

> 大型语言模型在复杂推理任务中大显身手，这些任务常依赖专家标注的解决方案和提炼的推理轨迹等高质量离线数据。然而，在稀疏奖励环境中，强化学习采样成功轨迹困难重重，学习效率大打折扣。更可惜的是，这些代表正确推理路径的离线轨迹并未被标准在线策略强化学习方法善加利用。为突破这一限制，我们提出了SuperRL，一个将离线监督自适应融入强化学习的统一训练框架。SuperRL配备了自适应开关，能敏锐捕捉稀疏奖励条件，必要时激活混合Actor。混合Actor巧妙地在损失层面融合策略梯度和监督学习目标，让模型既能汲取离线推理信号的精准指导，又不失强化学习的探索天性。在多个推理基准测试中，SuperRL在稀疏奖励条件下表现出色，通过提升采样效率、泛化能力和鲁棒性，轻松超越标准强化学习方法。

> Large language models are increasingly used for complex reasoning tasks where high-quality offline data such as expert-annotated solutions and distilled reasoning traces are often available. However, in environments with sparse rewards, reinforcement learning struggles to sample successful trajectories, leading to inefficient learning. At the same time, these offline trajectories that represent correct reasoning paths are not utilized by standard on-policy reinforcement learning methods. To address this limitation, we propose SuperRL, a unified training framework that adaptively incorporates offline supervision into reinforcement learning. SuperRL introduces an Adaptive Switch to detect sparse reward conditions and activates a Hybrid Actor when necessary. The Hybrid Actor integrates policy gradient and supervised learning objectives at the loss level, enabling the model to benefit from accurate offline reasoning signals while maintaining the exploratory capacity of reinforcement learning. Experiments on a range of reasoning benchmarks show that SuperRL consistently outperforms standard reinforcement learning by improving sample efficiency, generalization, and robustness under sparse rewards.

[Arxiv](https://arxiv.org/abs/2506.01096)