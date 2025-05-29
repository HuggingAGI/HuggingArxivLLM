# 在单纯形框架下评估大型语言模型的能力

发布时间：2025年05月28日

`LLM应用` `人工智能` `统计学`

> Judging LLMs on a Simplex

# 摘要

> 大型语言模型（LLMs）的自由形式输出自动化评估面临挑战，因为许多不同的答案可能同样有效。通常的做法是使用LLMs本身作为裁判，但这种方法的理论性质尚未被充分理解。我们提出了一种几何框架，将裁判和候选答案表示为概率单形上的点，这为理解LLM裁判的可识别性提供了新视角。理论分析揭示了排名可识别性的“相变”：对于二元评分系统，真实排名在温和假设下即使使用较弱裁判也仍可识别；但对于三个或更多评分等级，即使有无限数据，排名也会变得不可识别，除非有额外先验知识。这种不可识别性表明，排名中的不确定性不仅源于数据的固有随机性（偶然不确定性），还源于对假设成立性的认识不确定性，这一方面此前未被充分关注。我们通过贝叶斯推理将假设编码为先验，并对排名估计和置信区间进行敏感性分析，整合了这两种不确定性。实证评估显示，贝叶斯推理能够生成更准确的排名，并显著提高覆盖率。这些结果强调了在使用LLMs作为裁判时，采取更全面的不确定性量化方法的重要性。


> Automated evaluation of free-form outputs from large language models (LLMs) is challenging because many distinct answers can be equally valid. A common practice is to use LLMs themselves as judges, but the theoretical properties of this approach are not yet well understood. We show that a geometric framework that represents both judges and candidates as points on a probability simplex can provide helpful insight on what is or is not identifiable using LLM judges. Our theoretical analysis uncovers a "phase transition" in ranking identifiability: for binary scoring systems, true rankings are identifiable even with weak judges under mild assumptions, while rankings become non-identifiable for three or more scoring levels even with infinite data, absent additional prior knowledge. This non-identifiability highlights how uncertainty in rankings stems from not only aleatoric uncertainty (i.e., inherent stochasticity in the data) but also epistemic uncertainty regarding which assumptions hold, an aspect that has received limited attention until now. To integrate both types of uncertainty, we use Bayesian inference to encode assumptions as priors and conduct sensitivity analysis of ranking estimates and credible intervals. Empirical evaluations across multiple benchmarks demonstrate that Bayesian inference yields more accurate rankings and substantially improves coverage rates. These results underscore the importance of taking a more holistic approach to uncertainty quantification when using LLMs as judges.

[Arxiv](https://arxiv.org/abs/2505.21972)