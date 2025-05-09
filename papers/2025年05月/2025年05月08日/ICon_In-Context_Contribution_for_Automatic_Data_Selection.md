# ICon: 自动数据选择中的上下文贡献

发布时间：2025年05月08日

`LLM应用` `人工智能` `机器学习`

> ICon: In-Context Contribution for Automatic Data Selection

# 摘要

> 指令微调中的数据选择对于提升大型语言模型（LLMs）的性能和降低训练成本至关重要。然而，现有自动化选择方法要么依赖计算成本高昂的基于梯度的指标，要么依赖人工设计的启发式规则，这些方法可能无法充分利用数据的内在属性。本文中，我们提出了基于上下文学习的贡献度测量方法（ICon），这是一种无需计算梯度的新型方法，它利用了上下文学习（ICL）的隐式微调特性，无需梯度计算或人工指标设计，即可测量样本的贡献度。ICon为基于梯度的方法提供了一种计算高效的替代方案，并减少了基于启发式方法的人为归纳偏见。ICon包含三个组成部分，通过评估隐式学习过程中的性能变化，识别出高贡献度的数据。我们在三个LLMs上进行了广泛的实验，覆盖了12个基准测试和5个成对评估集，结果证明了ICon的有效性。值得注意的是，在LLaMA3.1-8B模型上，仅使用ICon选择数据的15%进行训练的模型，性能比完整数据集高出5.42个百分点，并且超过了广泛使用的选择方法的最佳性能2.06个百分点。我们进一步分析了ICon所选的高贡献样本，发现这些样本不仅涵盖了多样化的任务，还具有适当的难度水平，而不仅仅是难度最大的样本。


> Data selection for instruction tuning is essential for improving the performance of Large Language Models (LLMs) and reducing training cost. However, existing automated selection methods either depend on computationally expensive gradient-based measures or manually designed heuristics, which may fail to fully exploit the intrinsic attributes of data. In this paper, we propose In-context Learning for Contribution Measurement (ICon), a novel gradient-free method that takes advantage of the implicit fine-tuning nature of in-context learning (ICL) to measure sample contribution without gradient computation or manual indicators engineering. ICon offers a computationally efficient alternative to gradient-based methods and reduces human inductive bias inherent in heuristic-based approaches. ICon comprises three components and identifies high-contribution data by assessing performance shifts under implicit learning through ICL. Extensive experiments on three LLMs across 12 benchmarks and 5 pairwise evaluation sets demonstrate the effectiveness of ICon. Remarkably, on LLaMA3.1-8B, models trained on 15% of ICon-selected data outperform full datasets by 5.42% points and exceed the best performance of widely used selection methods by 2.06% points. We further analyze high-contribution samples selected by ICon, which show both diverse tasks and appropriate difficulty levels, rather than just the hardest ones.

[Arxiv](https://arxiv.org/abs/2505.05327)