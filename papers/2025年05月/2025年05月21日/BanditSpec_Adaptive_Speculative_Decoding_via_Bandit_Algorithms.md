# BanditSpec：自适应推测解码器，通过贝叶斯算法实现

发布时间：2025年05月21日

`LLM应用` `云计算`

> BanditSpec: Adaptive Speculative Decoding via Bandit Algorithms

# 摘要

> Speculative解码作为一种流行方法，能够在保持大型语言模型（LLMs）优越文本生成性能的同时加速推理过程。先前的方法要么采用固定不变的Speculative解码配置，不管前缀tokens如何，要么通过离线或在线方式训练草稿模型，以使其与上下文对齐。本文提出了一种无需训练的在线学习框架，能够在文本生成过程中自适应地选择Speculative解码的超参数配置。我们首先将这一超参数选择问题建模为多臂老虎机问题，并提供了一个通用的Speculative解码框架BanditSpec。此外，我们设计了两种基于老虎机的超参数选择算法UCBSpec和EXP3Spec，并从一个新的指标——停止时间遗憾（stopping time regret）——来分析它们的性能。我们分别在随机和对抗奖励设置下对这一遗憾进行了上界分析。通过推导一个信息论上的不可能结果，我们证明了UCBSpec的遗憾性能在常数因子内是最优的。最后，通过与LLaMA3和Qwen2进行的大量实证实验表明，与现有方法相比，我们的算法是有效的，并且在模拟的真实生活LLM服务场景中，吞吐量接近oracle最佳超参数，这些场景具有多种输入提示。


> Speculative decoding has emerged as a popular method to accelerate the inference of Large Language Models (LLMs) while retaining their superior text generation performance. Previous methods either adopt a fixed speculative decoding configuration regardless of the prefix tokens, or train draft models in an offline or online manner to align them with the context. This paper proposes a training-free online learning framework to adaptively choose the configuration of the hyperparameters for speculative decoding as text is being generated. We first formulate this hyperparameter selection problem as a Multi-Armed Bandit problem and provide a general speculative decoding framework BanditSpec. Furthermore, two bandit-based hyperparameter selection algorithms, UCBSpec and EXP3Spec, are designed and analyzed in terms of a novel quantity, the stopping time regret. We upper bound this regret under both stochastic and adversarial reward settings. By deriving an information-theoretic impossibility result, it is shown that the regret performance of UCBSpec is optimal up to universal constants. Finally, extensive empirical experiments with LLaMA3 and Qwen2 demonstrate that our algorithms are effective compared to existing methods, and the throughput is close to the oracle best hyperparameter in simulated real-life LLM serving scenarios with diverse input prompts.

[Arxiv](https://arxiv.org/abs/2505.15141)