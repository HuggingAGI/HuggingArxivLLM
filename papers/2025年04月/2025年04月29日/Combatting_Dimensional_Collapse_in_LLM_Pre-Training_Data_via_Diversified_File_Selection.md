# 对抗大语言模型预训练数据维度坍塌的多样化文件选择方法

发布时间：2025年04月29日

`LLM应用` `机器学习`

> Combatting Dimensional Collapse in LLM Pre-Training Data via Diversified File Selection

# 摘要

> 为大型语言模型选择优质预训练数据，对于在有限计算预算下提升性能至关重要，同时能显著提高训练效率和样本效率。近期在文件选择领域的进展，主要依赖于使用现有的或已训练好的代理模型，来评估样本与目标领域的相似性，例如高质量的来源如BookCorpus和维基百科。然而，重新审视这些方法后发现，领域相似性选择标准存在多样性困境，即特征空间中的维度坍缩，虽然提升了领域相关任务的性能，却导致了通用性能的严重下降。为了解决这一问题，我们提出了一种多样化文件选择算法（DiSF），该算法在特征空间中选择去相关性最强的文本文件。我们采用经典的贪心算法，使所选文本的特征协方差矩阵的特征值分布更加均匀，并分析了其在【数学公式】下的近似最优解。在实验部分，我们基于TinyLlama架构，使用从1.2亿到11亿参数规模的模型，建立基准并进行了广泛实验。通过 Harness 框架下的九项任务评估，DiSF在整体性能上展现了显著提升。具体而言，在SlimPajama中，DiSF节省了59亿训练文件中的98.5%，在500亿训练预算下超越了全数据预训练，实现了约1.5倍的训练效率和5倍的数据效率提升。

> Selecting high-quality pre-training data for large language models (LLMs) is crucial for enhancing their overall performance under limited computation budget, improving both training and sample efficiency. Recent advancements in file selection primarily rely on using an existing or trained proxy model to assess the similarity of samples to a target domain, such as high quality sources BookCorpus and Wikipedia. However, upon revisiting these methods, the domain-similarity selection criteria demonstrates a diversity dilemma, i.e.dimensional collapse in the feature space, improving performance on the domain-related tasks but causing severe degradation on generic performance. To prevent collapse and enhance diversity, we propose a DiverSified File selection algorithm (DiSF), which selects the most decorrelated text files in the feature space. We approach this with a classical greedy algorithm to achieve more uniform eigenvalues in the feature covariance matrix of the selected texts, analyzing its approximation to the optimal solution under a formulation of $γ$-weakly submodular optimization problem. Empirically, we establish a benchmark and conduct extensive experiments on the TinyLlama architecture with models from 120M to 1.1B parameters. Evaluating across nine tasks from the Harness framework, DiSF demonstrates a significant improvement on overall performance. Specifically, DiSF saves 98.5% of 590M training files in SlimPajama, outperforming the full-data pre-training within a 50B training budget, and achieving about 1.5x training efficiency and 5x data efficiency.

[Arxiv](https://arxiv.org/abs/2504.20644)