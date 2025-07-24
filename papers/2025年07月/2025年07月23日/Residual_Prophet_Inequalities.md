# # 残差先知不等式
残差先知不等式是优化与决策理论中的重要数学工具，用于量化不确定环境下最优决策与实际决策之间的差距。

发布时间：2025年07月23日

`其他` `运筹学` `计算机科学`

> Residual Prophet Inequalities

# 摘要

> 我们提出了一种经典先知不等式的变体，称为残差先知不等式（RPI）。在RPI问题中，我们考虑一个由$n$个非负独立随机变量组成的有限序列，这些变量具有已知分布，以及一个已知的整数$0 \leq k \leq n-1$。在赌徒观察序列之前，前$k$个最大值已被移除，而剩下的$n-k$个值则按顺序流式传输给赌徒。例如，可以假设前$k$个最大值已经被分配给一个优先级更高的代理。当赌徒观察到一个值时，他必须不可撤销地决定接受或拒绝它，且无法回顾之前看到的值。

我们研究了RPI的两个变体，分别对应赌徒是否能够在线得知所见变量的身份（FI模型）或无法得知（NI模型）。我们的主要结果是在FI模型中提出了一种随机化算法，其竞争比至少为$1/(k+2)$，并且我们证明了这一结果是紧的。我们的算法是数据驱动的，仅需访问从$n$个输入分布中抽取的一个样本中的$k+1$个最大值。在NI模型中，我们提供了一个类似的算法，保证的竞争比为$1/(2k+2)$。我们还进一步分析了当$k=1$时的独立同分布实例。我们构建了一个单阈值算法，其竞争比至少为0.4901，并证明没有任何单阈值策略能够获得超过0.5464的竞争比。

> We introduce a variant of the classic prophet inequality, called \emph{residual prophet inequality} (RPI). In the RPI problem, we consider a finite sequence of $n$ nonnegative independent random values with known distributions, and a known integer $0\leq k\leq n-1$. Before the gambler observes the sequence, the top $k$ values are removed, whereas the remaining $n-k$ values are streamed sequentially to the gambler. For example, one can assume that the top $k$ values have already been allocated to a higher-priority agent. Upon observing a value, the gambler must decide irrevocably whether to accept or reject it, without the possibility of revisiting past values.
  We study two variants of RPI, according to whether the gambler learns online of the identity of the variable that he sees (FI model) or not (NI model). Our main result is a randomized algorithm in the FI model with \emph{competitive ratio} of at least $1/(k+2)$, which we show is tight. Our algorithm is data-driven and requires access only to the $k+1$ largest values of a single sample from the $n$ input distributions. In the NI model, we provide a similar algorithm that guarantees a competitive ratio of $1/(2k+2)$. We further analyze independent and identically distributed instances when $k=1$. We build a single-threshold algorithm with a competitive ratio of at least 0.4901, and show that no single-threshold strategy can get a competitive ratio greater than 0.5464.

[Arxiv](https://arxiv.org/abs/2507.17391)