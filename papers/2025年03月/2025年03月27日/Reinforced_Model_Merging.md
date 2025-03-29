# # 强化模型合并
Reinforced Model Merging 是一种利用强化学习来优化模型合并过程的技术。

发布时间：2025年03月27日

`LLM应用` `视觉处理`

> Reinforced Model Merging

# 摘要

> 大型语言模型的成功引发了人们对模型合并技术的广泛关注，尤其是那些无需训练即可在参数空间内结合模型能力的方法。然而，仍然存在两大挑战：(1) 对所有参数进行统一处理会导致性能下降；(2) 基于搜索的算法通常效率低下。本文提出了一种名为强化模型合并（RMM）的创新框架，该框架包含专门针对合并任务设计的环境和智能体。这些组件相互作用以执行分层合并操作，旨在搜索最优的合并架构。值得注意的是，RMM无需对原始模型进行梯度计算，使其能够运行在边缘设备上。此外，通过在评估过程中利用数据子集，我们解决了奖励反馈阶段的瓶颈问题，从而将RMM的速度提升了高达100倍。大量实验表明，RMM在各种视觉和自然语言处理数据集上均达到了当前最优的性能水平，并有效克服了现有基线方法的局限性。我们的代码可在https://github.com/WuDiHJQ/Reinforced-Model-Merging获取。

> The success of large language models has garnered widespread attention for model merging techniques, especially training-free methods which combine model capabilities within the parameter space. However, two challenges remain: (1) uniform treatment of all parameters leads to performance degradation; (2) search-based algorithms are often inefficient. In this paper, we present an innovative framework termed Reinforced Model Merging (RMM), which encompasses an environment and agent tailored for merging tasks. These components interact to execute layer-wise merging actions, aiming to search the optimal merging architecture. Notably, RMM operates without any gradient computations on the original models, rendering it feasible for edge devices. Furthermore, by utilizing data subsets during the evaluation process, we addressed the bottleneck in the reward feedback phase, thereby accelerating RMM by up to 100 times. Extensive experiments demonstrate that RMM achieves state-of-the-art performance across various vision and NLP datasets and effectively overcomes the limitations of the existing baseline methods. Our code is available at https://github.com/WuDiHJQ/Reinforced-Model-Merging.

[Arxiv](https://arxiv.org/abs/2503.21272)