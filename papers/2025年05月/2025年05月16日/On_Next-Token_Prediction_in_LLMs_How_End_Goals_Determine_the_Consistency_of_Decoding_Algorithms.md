# LLM中的下一个词预测：最终目标如何影响解码算法的一致性

发布时间：2025年05月16日

`LLM理论

论文摘要：基于交叉熵损失训练的、用于预测下一个令牌的概率模型，构成了大多数大型语言模型的基础。给定一个由先前值组成的序列，下一个令牌预测为词汇表中每个可能的下一个值分配一个概率。使用下一个令牌预测生成令牌序列的方法有很多种。本文研究了其中几种算法（贪婪算法、前瞻算法、随机采样和温度缩放随机采样），并研究了它们与编码为损失函数的各种目标的一致性。

尽管替代损失函数与目标损失函数的一致性是一个研究充分的话题，但据我们所知，我们是第一个在大型语言模型（LLMs）背景下研究这一问题的。我们发现，只要下一个令牌预测收敛到其真实的概率分布，随机采样就与输出模拟从真实概率分布中采样的序列是一致的。对于其他目标，如在整个序列上最小化0-1损失，我们证明没有多项式时间算法对所有概率分布都是最优的，而我们研究的所有解码算法仅对概率分布的一个子集最优。

在分析这些结果时，我们发现解码算法在信息检索和创造性生成这两个目标之间产生了一种二分法。这表明，根据所需目标选择正确的解码算法极为重要，而许多现有方法在众多场景中缺乏理论依据。` `文本生成`

> On Next-Token Prediction in LLMs: How End Goals Determine the Consistency of Decoding Algorithms

# 摘要

> 基于交叉熵损失训练的、用于预测下一个令牌的概率模型，构成了大多数大型语言模型的基础。给定一个由先前值组成的序列，下一个令牌预测为词汇表中每个可能的下一个值分配一个概率。使用下一个令牌预测生成令牌序列的方法有很多种。本文研究了其中几种算法（贪婪算法、前瞻算法、随机采样和温度缩放随机采样），并研究了它们与编码为损失函数的各种目标的一致性。

尽管替代损失函数与目标损失函数的一致性是一个研究充分的话题，但据我们所知，我们是第一个在大型语言模型（LLMs）背景下研究这一问题的。我们发现，只要下一个令牌预测收敛到其真实的概率分布，随机采样就与输出模拟从真实概率分布中采样的序列是一致的。对于其他目标，如在整个序列上最小化0-1损失，我们证明没有多项式时间算法对所有概率分布都是最优的，而我们研究的所有解码算法仅对概率分布的一个子集最优。

在分析这些结果时，我们发现解码算法在信息检索和创造性生成这两个目标之间产生了一种二分法。这表明，根据所需目标选择正确的解码算法极为重要，而许多现有方法在众多场景中缺乏理论依据。


> Probabilistic next-token prediction trained using cross-entropy loss is the basis of most large language models. Given a sequence of previous values, next-token prediction assigns a probability to each possible next value in the vocabulary. There are many ways to use next-token prediction to output token sequences. This paper examines a few of these algorithms (greedy, lookahead, random sampling, and temperature-scaled random sampling) and studies their consistency with respect to various goals encoded as loss functions. Although consistency of surrogate losses with respect to a target loss function is a well researched topic, we are the first to study it in the context of LLMs (to the best of our knowledge). We find that, so long as next-token prediction converges to its true probability distribution, random sampling is consistent with outputting sequences that mimic sampling from the true probability distribution. For the other goals, such as minimizing the 0-1 loss on the entire sequence, we show no polynomial-time algorithm is optimal for all probability distributions and all decoding algorithms studied are only optimal for a subset of probability distributions. When analyzing these results, we see that there is a dichotomy created between the goals of information retrieval and creative generation for the decoding algorithms. This shows that choosing the correct decoding algorithm based on the desired goal is extremely important and many of the ones used are lacking theoretical grounding in numerous scenarios.

[Arxiv](https://arxiv.org/abs/2505.11183)