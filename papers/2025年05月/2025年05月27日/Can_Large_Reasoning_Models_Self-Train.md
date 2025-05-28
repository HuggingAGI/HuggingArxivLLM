# <翻译失败>

发布时间：2025年05月27日

`LLM理论` `数学推理`

> Can Large Reasoning Models Self-Train?

# 摘要

> 提升大型语言模型（LLMs）的性能日益依赖于减少对人工监督的方法。基于自动化验证的强化学习提供了一种替代方案，但这种方法由于依赖人工设计的验证器而存在可扩展性限制。自我训练，即模型自身的判断提供监督信号，展现了一个极具吸引力的方向。

我们提出了一种在线自训练强化学习算法，该算法利用模型的自洽性推断正确性信号，并在没有任何真实标注监督的情况下进行训练。我们将该算法应用于具有挑战性的数学推理任务，结果显示它能迅速达到与基于金标准答案显式训练的强化学习方法相媲美的性能水平。

此外，我们分析了该算法的内在局限性，强调了自动生成的代理奖励如何最初与正确性相关联，但可能激励奖励欺骗，即过于自信的错误输出被优先选择。我们的结果展示了自监督改进如何在无需外部标签的情况下实现显著的性能提升，同时也揭示了其根本挑战。

> Scaling the performance of large language models (LLMs) increasingly depends on methods that reduce reliance on human supervision. Reinforcement learning from automated verification offers an alternative, but it incurs scalability limitations due to dependency upon human-designed verifiers. Self-training, where the model's own judgment provides the supervisory signal, presents a compelling direction. We propose an online self-training reinforcement learning algorithm that leverages the model's self-consistency to infer correctness signals and train without any ground-truth supervision. We apply the algorithm to challenging mathematical reasoning tasks and show that it quickly reaches performance levels rivaling reinforcement-learning methods trained explicitly on gold-standard answers. Additionally, we analyze inherent limitations of the algorithm, highlighting how the self-generated proxy reward initially correlated with correctness can incentivize reward hacking, where confidently incorrect outputs are favored. Our results illustrate how self-supervised improvement can achieve significant performance gains without external labels, while also revealing its fundamental challenges.

[Arxiv](https://arxiv.org/abs/2505.21444)