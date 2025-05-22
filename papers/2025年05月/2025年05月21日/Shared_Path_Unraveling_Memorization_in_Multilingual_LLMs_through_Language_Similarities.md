# 共享路径：通过语言相似性揭秘多语言LLMs的记忆机制

发布时间：2025年05月21日

`LLM理论` `多语言模型`

> Shared Path: Unraveling Memorization in Multilingual LLMs through Language Similarities

# 摘要

> 我们首次全面研究了多语言大语言模型（MLLMs）中的记忆机制，分析了95种语言，使用了不同规模、架构和记忆定义的模型。随着MLLMs的广泛应用，理解其记忆行为变得至关重要。然而，先前的研究主要集中在单语模型上，对多语言记忆机制的探索较少，尽管训练语料库本身具有长尾性质。我们发现，普遍认为记忆与训练数据可用性高度相关的假设，并不能完全解释MLLMs中的记忆模式。我们假设，孤立地对待语言——忽略它们之间的相似性——会掩盖记忆的真实模式。为了解决这一问题，我们提出了一种基于图的相关性度量方法，该方法结合了语言相似性来分析跨语言记忆。我们的分析表明，在相似语言中，训练标记较少的语言往往表现出更高的记忆水平，这一趋势只有在显式建模跨语言关系时才会显现。这些发现强调了在评估和缓解MLLMs记忆漏洞时，采用语言敏感视角的重要性。这也为语言相似性提供了实证证据，它既能解释MLLMs中的记忆，又能支撑跨语言迁移性，这对多语言NLP具有广泛的影响。

> We present the first comprehensive study of Memorization in Multilingual Large Language Models (MLLMs), analyzing 95 languages using models across diverse model scales, architectures, and memorization definitions. As MLLMs are increasingly deployed, understanding their memorization behavior has become critical. Yet prior work has focused primarily on monolingual models, leaving multilingual memorization underexplored, despite the inherently long-tailed nature of training corpora. We find that the prevailing assumption, that memorization is highly correlated with training data availability, fails to fully explain memorization patterns in MLLMs. We hypothesize that treating languages in isolation - ignoring their similarities - obscures the true patterns of memorization. To address this, we propose a novel graph-based correlation metric that incorporates language similarity to analyze cross-lingual memorization. Our analysis reveals that among similar languages, those with fewer training tokens tend to exhibit higher memorization, a trend that only emerges when cross-lingual relationships are explicitly modeled. These findings underscore the importance of a language-aware perspective in evaluating and mitigating memorization vulnerabilities in MLLMs. This also constitutes empirical evidence that language similarity both explains Memorization in MLLMs and underpins Cross-lingual Transferability, with broad implications for multilingual NLP.

[Arxiv](https://arxiv.org/abs/2505.15722)