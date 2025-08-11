# 大型语言模型中的隐私保护自适应回溯方法

发布时间：2025年08月08日

`RAG`

> Adaptive Backtracking for Privacy Protection in Large Language Models

# 摘要

> 隐私保护在人工智能时代已成为关键议题。然而，当前研究主要关注用户隐私，却忽视了由检索增强生成范式（Retrieval-Augmented Generation）加剧的企业数据泄露风险。为填补这一空白，我们的研究提出了一种新的目标：企业导向的隐私问题。为实现这一目标，我们需克服两大核心挑战：现有方法（如数据净化）严重损害模型性能，以及领域内缺乏公开的评估数据集。

我们通过多项创新方案应对这些挑战。第一，为防止性能下降，我们提出了无需训练的ABack机制。该机制利用隐藏状态模型精确定位泄露意图的来源，并安全地重写输出。第二，为解决数据集缺失问题，我们构建了PriGenQA，这是一个针对医疗和金融领域企业隐私场景的新基准测试。

为确保严格的评估，我们超越简单的静态攻击，开发了一种强大的自适应攻击者，采用组相对策略优化方法。实验结果表明，相较于强基线方法，ABack在面对这一更强大的对手时，将整体隐私效用评分提升了高达15%，成功避免了以往方法的性能权衡。

> The preservation of privacy has emerged as a critical topic in the era of artificial intelligence. However, current work focuses on user-oriented privacy, overlooking severe enterprise data leakage risks exacerbated by the Retrieval-Augmented Generation paradigm. To address this gap, our paper introduces a novel objective: enterprise-oriented privacy concerns. Achieving this objective requires overcoming two fundamental challenges: existing methods such as data sanitization severely degrade model performance, and the field lacks public datasets for evaluation. We address these challenges with several solutions. (1) To prevent performance degradation, we propose ABack, a training-free mechanism that leverages a Hidden State Model to pinpoint the origin of a leakage intention and rewrite the output safely. (2) To solve the lack of datasets, we construct PriGenQA, a new benchmark for enterprise privacy scenarios in healthcare and finance. To ensure a rigorous evaluation, we move beyond simple static attacks by developing a powerful adaptive attacker with Group Relative Policy Optimization. Experiments show that against this superior adversary, ABack improves the overall privacy utility score by up to 15\% over strong baselines, avoiding the performance trade-offs of prior methods.

[Arxiv](https://arxiv.org/abs/2508.06087)