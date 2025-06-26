# **非线性注意力机制中的上下文记忆：随机矩阵分析**

发布时间：2025年06月23日

`LLM理论` `机器学习`

> A Random Matrix Analysis of In-context Memorization for Nonlinear Attention

# 摘要

> 注意力机制彻底革新了机器学习领域，实现了输入间全局依赖关系的高效建模。其固有的并行结构使其能够高效扩展，即使面对指数级增长的预训练数据和模型参数规模。然而，尽管注意力机制作为现代大型语言模型（LLMs）的核心计算框架，我们对其理论理解，尤其是在非线性设置下，仍然有限。

    本文在高维比例体制下，对非线性注意力的\emph{上下文记忆误差}进行了深入研究，其中输入令牌数量$n$及其嵌入维度$p$均较大且相近。借助大型核随机矩阵理论的最新进展，我们发现非线性注意力在随机输入上的记忆误差通常高于线性岭回归。然而，当输入呈现统计结构，特别是当注意力权重与输入信号方向对齐时，这一差距会消失，甚至反转。我们的研究揭示了非线性与输入结构如何相互作用，共同决定非线性注意力的记忆性能。这些理论见解得到了数值实验的支持。

> Attention mechanisms have revolutionized machine learning (ML) by enabling efficient modeling of global dependencies across inputs. Their inherently parallelizable structures allow for efficient scaling with the exponentially increasing size of both pretrained data and model parameters. Yet, despite their central role as the computational backbone of modern large language models (LLMs), the theoretical understanding of Attentions, especially in the nonlinear setting, remains limited.
  In this paper, we provide a precise characterization of the \emph{in-context memorization error} of \emph{nonlinear Attention}, in the high-dimensional proportional regime where the number of input tokens $n$ and their embedding dimension $p$ are both large and comparable. Leveraging recent advances in the theory of large kernel random matrices, we show that nonlinear Attention typically incurs higher memorization error than linear ridge regression on random inputs. However, this gap vanishes, and can even be reversed, when the input exhibits statistical structure, particularly when the Attention weights align with the input signal direction. Our results reveal how nonlinearity and input structure interact with each other to govern the memorization performance of nonlinear Attention. The theoretical insights are supported by numerical experiments.

[Arxiv](https://arxiv.org/abs/2506.18656)