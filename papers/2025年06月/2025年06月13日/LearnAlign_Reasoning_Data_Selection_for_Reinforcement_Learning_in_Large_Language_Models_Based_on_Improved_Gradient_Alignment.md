# LearnAlign：基于改进梯度对齐的大型语言模型强化学习推理数据选择

发布时间：2025年06月13日

`LLM应用

摘要讨论了强化学习在提升大语言模型推理能力中的应用，并提出了一种新的数据高效方法LearnAlign，专注于优化训练数据的选择和使用。这属于LLM的应用研究。` `人工智能`

> LearnAlign: Reasoning Data Selection for Reinforcement Learning in Large Language Models Based on Improved Gradient Alignment

# 摘要

> 强化学习（RL）在提升大语言模型（LLMs）推理能力方面发挥着关键作用，但其数据低效性仍是主要瓶颈。针对这一关键且具挑战性的问题，我们提出了一种名为LearnAlign的新型基于梯度对齐的方法，该方法在RL微调过程中智能选择可学习且具代表性的推理训练数据。为克服梯度范数中响应长度偏见这一难题，我们引入了基于成功率的数据可学习性指标，用于评估每个数据点的学习潜力。在三个数学推理基准测试中，实验结果表明，与全数据训练相比，我们的方法在显著减少训练数据需求的同时，实现了性能的轻微下降甚至提升。例如，在GSM8K基准测试中，数据需求减少了多达1,000个数据点，且性能更优（77.53%），优于全数据集上的性能（77.04%）。此外，我们在分阶段RL设置中也验证了其有效性。这项研究为数据高效的RL微调提供了宝贵的见解，并为未来在优化推理数据选择方面的研究奠定了基础。为了促进未来工作，我们将开源代码。

> Reinforcement learning (RL) has become a key technique for enhancing LLMs' reasoning abilities, yet its data inefficiency remains a major bottleneck. To address this critical yet challenging issue, we present a novel gradient-alignment-based method, named LearnAlign, which intelligently selects the learnable and representative training reasoning data for RL post-training. To overcome the well-known issue of response-length bias in gradient norms, we introduce the data learnability based on the success rate, which can indicate the learning potential of each data point. Experiments across three mathematical reasoning benchmarks demonstrate that our method significantly reduces training data requirements while achieving minor performance degradation or even improving performance compared to full-data training. For example, it reduces data requirements by up to 1,000 data points with better performance (77.53%) than that on the full dataset on GSM8K benchmark (77.04%). Furthermore, we show its effectiveness in the staged RL setting. This work provides valuable insights into data-efficient RL post-training and establishes a foundation for future research in optimizing reasoning data selection.To facilitate future work, we will release code.

[Arxiv](https://arxiv.org/abs/2506.11480)