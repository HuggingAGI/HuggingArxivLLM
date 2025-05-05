# 深入探讨Transformer如何学习正则语言识别：一项关于训练动力学与隐式偏差的理论研究

发布时间：2025年05月01日

`LLM理论` `模型机制`

> How Transformers Learn Regular Language Recognition: A Theoretical Study on Training Dynamics and Implicit Bias

# 摘要

> 语言识别任务是自然语言处理（NLP）领域的基石，广泛用于评估大型语言模型（LLMs）的性能，同时在揭示Transformer工作机制方面具有重要意义。本研究聚焦于两类典型任务：`even pairs'（偶数对）和`parity check'（奇偶校验），旨在通过梯度下降下的理论分析，探究由注意力层与线性层组成的单层Transformer如何学习解决这些任务。虽然单层Transformer可直接解决偶数对任务，但奇偶校验任务需通过链式思维（CoT）来辅助，既可将其整合到已针对偶数对任务优化的Transformer推理阶段，也可直接融入单层Transformer的训练过程。针对这两个问题，我们的研究发现，注意力层与线性层的联合训练呈现两个显著阶段：第一阶段，注意力层快速增长，将数据序列映射为可分向量；第二阶段，注意力层趋于稳定，线性层则以对数速度增长，其方向逐步趋近于一个正确划分注意力层输出为正负样本的最大间隔超平面，且损失以$O(1/t)$速率下降。实验结果充分验证了这些理论发现。


> Language recognition tasks are fundamental in natural language processing (NLP) and have been widely used to benchmark the performance of large language models (LLMs). These tasks also play a crucial role in explaining the working mechanisms of transformers. In this work, we focus on two representative tasks in the category of regular language recognition, known as `even pairs' and `parity check', the aim of which is to determine whether the occurrences of certain subsequences in a given sequence are even. Our goal is to explore how a one-layer transformer, consisting of an attention layer followed by a linear layer, learns to solve these tasks by theoretically analyzing its training dynamics under gradient descent. While even pairs can be solved directly by a one-layer transformer, parity check need to be solved by integrating Chain-of-Thought (CoT), either into the inference stage of a transformer well-trained for the even pairs task, or into the training of a one-layer transformer. For both problems, our analysis shows that the joint training of attention and linear layers exhibits two distinct phases. In the first phase, the attention layer grows rapidly, mapping data sequences into separable vectors. In the second phase, the attention layer becomes stable, while the linear layer grows logarithmically and approaches in direction to a max-margin hyperplane that correctly separates the attention layer outputs into positive and negative samples, and the loss decreases at a rate of $O(1/t)$. Our experiments validate those theoretical results.

[Arxiv](https://arxiv.org/abs/2505.00926)