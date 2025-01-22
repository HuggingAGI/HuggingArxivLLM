# 基于LLM效用估计的预训练数据混合优化

发布时间：2025年01月20日

`LLM理论` `机器学习`

> Optimizing Pretraining Data Mixtures with LLM-Estimated Utility

# 摘要

> 大型语言模型的性能随着高质量训练数据的增加而提升。然而，使用更大数据集时，需在质量、数量和多样性之间找到平衡。在计算和数据受限的场景下，我们评估了九种基线方法，发现基于词频的启发式方法优于手动和学习的混合方法，这表明简单考虑数据集大小和多样性的方法效果出奇地好。基于此，我们提出了两种互补方法：UtiliMax，通过结合小规模消融实验的效用估计，扩展了基于词频的启发式方法，相比手动基线实现了高达10.6倍的加速；以及模型估计数据效用（MEDU），利用大型语言模型从小样本中估计数据效用，在减少计算需求约200倍的同时，性能与消融实验相当。这些方法共同构建了一个自动化、计算高效的数据混合框架，适用于多种训练场景。

> Large Language Models improve with increasing amounts of high-quality training data. However, leveraging larger datasets requires balancing quality, quantity, and diversity across sources. After evaluating nine baseline methods under both compute- and data-constrained scenarios, we find token-count heuristics outperform manual and learned mixes, indicating that simple approaches accounting for dataset size and diversity are surprisingly effective. Building on this insight, we propose two complementary approaches: UtiliMax, which extends token-based heuristics by incorporating utility estimates from reduced-scale ablations, achieving up to a 10.6x speedup over manual baselines; and Model Estimated Data Utility (MEDU), which leverages LLMs to estimate data utility from small samples, matching ablation-based performance while reducing computational requirements by $\sim$200x. Together, these approaches establish a new framework for automated, compute-efficient data mixing that is robust across training regimes.

[Arxiv](https://arxiv.org/abs/2501.11747)