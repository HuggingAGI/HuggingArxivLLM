# 多元道德差距：解析人类与AI模型在道德判断与价值观上的差异

发布时间：2025年07月23日

`LLM应用

摘要分析：论文探讨了大型语言模型在道德判断中的应用，评估了模型与人类判断的契合度，并提出了改进方法，属于应用层面的研究。` `伦理学` `道德困境`

> The Pluralistic Moral Gap: Understanding Judgment and Value Differences between Humans and Large Language Models

# 摘要

> 人们越来越依赖大型语言模型（LLMs）获取道德建议，这可能影响人类决策。然而，我们对LLMs与人类道德判断的契合程度知之甚少。为此，我们推出了道德困境数据集——一个包含1,618个现实道德困境的基准，每个困境都配有人类道德判断的分布，包括二元评估和自由文本理由。我们将此视为多元分布对齐任务，比较了LLM与人类在不同困境中的判断分布。发现显示，仅在高度共识下，模型才会复制人类判断；而当人类意见分歧增加时，对齐急剧下降。同时，我们利用从理由中提取的3,783个价值表达构建的60个价值分类法，发现LLMs依赖的价值比人类更狭窄。这些发现揭示了多元道德差距：价值分布与多样性均存在不匹配。为缩小这一差距，我们推出了动态道德画像（DMP），一种基于Dirichlet的采样方法，根据人类价值画像条件化模型输出。DMP使对齐提升了64.3%，并增强了价值多样性，为实现更多元和人性化的LLM道德指导迈出了重要一步。

> People increasingly rely on Large Language Models (LLMs) for moral advice, which may influence humans' decisions. Yet, little is known about how closely LLMs align with human moral judgments. To address this, we introduce the Moral Dilemma Dataset, a benchmark of 1,618 real-world moral dilemmas paired with a distribution of human moral judgments consisting of a binary evaluation and a free-text rationale. We treat this problem as a pluralistic distributional alignment task, comparing the distributions of LLM and human judgments across dilemmas. We find that models reproduce human judgments only under high consensus; alignment deteriorates sharply when human disagreement increases. In parallel, using a 60-value taxonomy built from 3,783 value expressions extracted from rationales, we show that LLMs rely on a narrower set of moral values than humans. These findings reveal a pluralistic moral gap: a mismatch in both the distribution and diversity of values expressed. To close this gap, we introduce Dynamic Moral Profiling (DMP), a Dirichlet-based sampling method that conditions model outputs on human-derived value profiles. DMP improves alignment by 64.3% and enhances value diversity, offering a step toward more pluralistic and human-aligned moral guidance from LLMs.

[Arxiv](https://arxiv.org/abs/2507.17216)