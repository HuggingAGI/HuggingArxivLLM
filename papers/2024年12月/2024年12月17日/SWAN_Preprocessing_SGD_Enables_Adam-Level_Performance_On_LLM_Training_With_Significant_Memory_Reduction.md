# SWAN：对 SGD 进行预处理，能让 LLM 训练达到与 Adam 同等的性能水平，同时大幅降低内存占用。

发布时间：2024年12月17日

`LLM理论` `语言模型` `优化器`

> SWAN: Preprocessing SGD Enables Adam-Level Performance On LLM Training With Significant Memory Reduction

# 摘要

> 像 Adam（Kingma 与 Ba，2015）这样的自适应优化器一直是大型语言模型成功的关键所在。然而，它们在整个训练过程中会维持额外的移动平均状态，这使得内存需求比模型本身大好几倍。这种情况给可扩展性和计算效率带来了限制。另一方面，虽然随机梯度下降（SGD）在内存效率方面表现最优，但其在 LLM 训练中的能力有限（Zhao 等人，2024b）。
  为解决这一难题，我们指出对 SGD 进行预处理足以让其在 LLM 上达到 Adam 级别的性能。具体而言，我们提议用两个简单的运算符对瞬时随机梯度进行预处理：$\mathtt{GradNorm}$ 和 $\mathtt{GradWhitening}$ 。$\mathtt{GradNorm}$ 能稳定梯度分布，$\mathtt{GradWhitening}$ 可抵消损失曲面的局部曲率。由此产生了 SWAN（具有白化和归一化的 SGD），这是一种无需存储任何累积状态变量的随机优化器。经验表明，SWAN 的内存占用与 SGD 相同，与 Adam 相比，总端到端内存减少约 50％。在语言建模任务中，SWAN 表现出与 Adam 相同甚至更显著的改进。具体来说，在使用 350M 和 1.3B 参数预训练 LLaMa 模型时，SWAN 实现了 2 倍的加速，能在不到一半的令牌中达到相同的评估困惑度。

> Adaptive optimizers such as Adam (Kingma & Ba, 2015) have been central to the success of large language models. However, they maintain additional moving average states throughout training, which results in memory requirements several times greater than the model. This overhead imposes constraints on scalability and computational efficiency. On the other hand, while stochastic gradient descent (SGD) is optimal in terms of memory efficiency, their capability in LLM training is limited (Zhao et al., 2024b).
  To address this dilemma, we show that pre-processing SGD is sufficient to reach Adam-level performance on LLMs. Specifically, we propose to preprocess the instantaneous stochastic gradients with two simple operators: $\mathtt{GradNorm}$ and $\mathtt{GradWhitening}$. $\mathtt{GradNorm}$ stabilizes gradient distributions, and $\mathtt{GradWhitening}$ counteracts the local curvature of the loss landscape, respectively. This results in SWAN (SGD with Whitening And Normalization), a stochastic optimizer that eliminates the need to store any accumulative state variables. Empirically, SWAN has the same memory footprint as SGD, achieving $\approx 50\%$ reduction on total end-to-end memory compared to Adam. In language modeling tasks, SWAN demonstrates the same or even a substantial improvement over Adam. Specifically, when pre-training the LLaMa model with 350M and 1.3B parameters, SWAN achieves a 2x speedup by reaching the same evaluation perplexity in less than half tokens seen.

[Arxiv](https://arxiv.org/abs/2412.13148)