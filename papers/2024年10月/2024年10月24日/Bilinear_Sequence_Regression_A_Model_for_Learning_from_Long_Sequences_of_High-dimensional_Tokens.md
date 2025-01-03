# 双线性序列回归：高维标记长序列学习模型

发布时间：2024年10月24日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）的理论基础，特别是通过统计物理学的方法来研究神经网络的学习机制。论文提出了双线性序列回归（BSR）作为token序列的基础模型，并计算了高维token长序列极限下的贝叶斯最优泛化误差。这些内容属于对LLM的理论分析和模型构建，因此归类为LLM理论。` `人工智能` `统计物理学`

> Bilinear Sequence Regression: A Model for Learning from Long Sequences of High-dimensional Tokens

# 摘要

> 当前人工智能的进展主要围绕大型语言模型展开，这些模型通过神经网络处理长序列的高维向量（称为token）。统计物理学为研究神经网络的学习机制提供了强大工具，并在现代机器学习的发展中发挥了重要作用。统计物理学方法依赖于简化的、可分析处理的数据模型，但对于长序列高维token的简单模型仍缺乏深入探索。受单层教师-学生感知器（广义线性回归）在全连接神经网络理论中的关键作用启发，本文提出并研究了双线性序列回归（BSR）作为token序列的基础模型。我们注意到，现代架构因跳跃连接的存在自然包含了BSR模型。基于最新方法论进展，我们计算了高维token长序列极限下模型的贝叶斯最优泛化误差，并设计了一种匹配该性能的消息传递算法。我们量化了最优学习相对于简单线性回归的改进，并揭示了BSR模型中梯度下降算法的独特性质。

> Current progress in artificial intelligence is centered around so-called large language models that consist of neural networks processing long sequences of high-dimensional vectors called tokens. Statistical physics provides powerful tools to study the functioning of learning with neural networks and has played a recognized role in the development of modern machine learning. The statistical physics approach relies on simplified and analytically tractable models of data. However, simple tractable models for long sequences of high-dimensional tokens are largely underexplored. Inspired by the crucial role models such as the single-layer teacher-student perceptron (aka generalized linear regression) played in the theory of fully connected neural networks, in this paper, we introduce and study the bilinear sequence regression (BSR) as one of the most basic models for sequences of tokens. We note that modern architectures naturally subsume the BSR model due to the skip connections. Building on recent methodological progress, we compute the Bayes-optimal generalization error for the model in the limit of long sequences of high-dimensional tokens, and provide a message-passing algorithm that matches this performance. We quantify the improvement that optimal learning brings with respect to vectorizing the sequence of tokens and learning via simple linear regression. We also unveil surprising properties of the gradient descent algorithms in the BSR model.

[Arxiv](https://arxiv.org/abs/2410.18858)