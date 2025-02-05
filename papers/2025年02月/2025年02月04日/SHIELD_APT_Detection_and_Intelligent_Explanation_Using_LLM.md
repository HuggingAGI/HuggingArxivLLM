# <翻译失败>

发布时间：2025年02月04日

`LLM应用

理由：这篇论文提出了一种名为SHIELD的方法，结合了统计异常检测、图分析和大型语言模型（LLMs）的上下文分析能力，用于检测高级持续性威胁（APTs）。SHIELD利用LLMs的隐含知识来揭示溯源数据中的隐藏攻击模式，减少误报并提供清晰、可解释的攻击描述。这表明LLMs在该方法中起到了关键作用，用于增强检测系统的性能和可解释性。因此，这篇论文应归类为LLM应用。` `网络安全` `威胁检测`

> SHIELD: APT Detection and Intelligent Explanation Using LLM

# 摘要

> # 摘要
高级持续性威胁（APTs）是一种复杂的网络攻击，能够在长时间内潜伏而不被发现，因此其防御尤为困难。由于APTs的持续性，检测和应对这些威胁需要大量努力。现有的基于溯源数据的攻击检测方法往往缺乏可解释性，且误报率较高，而调查方法要么依赖监督学习，要么仅限于已知攻击。为应对这些挑战，我们提出了SHIELD，一种结合统计异常检测、图分析和大型语言模型（LLMs）上下文分析能力的新方法。SHIELD利用LLMs的隐含知识，揭示溯源数据中的隐藏攻击模式，减少误报并提供清晰、可解释的攻击描述，从而减轻分析师的警报疲劳，帮助他们更好地理解威胁态势。通过广泛的评估，我们证明了SHIELD在实际场景中的高效性和计算效率。SHIELD在精确度和召回率上均优于现有方法，并通过整合异常检测、LLM驱动的上下文分析和先进的图相关性分析，为APT检测设立了新标杆。

> Advanced persistent threats (APTs) are sophisticated cyber attacks that can remain undetected for extended periods, making their mitigation particularly challenging. Given their persistence, significant effort is required to detect them and respond effectively. Existing provenance-based attack detection methods often lack interpretability and suffer from high false positive rates, while investigation approaches are either supervised or limited to known attacks. To address these challenges, we introduce SHIELD, a novel approach that combines statistical anomaly detection and graph-based analysis with the contextual analysis capabilities of large language models (LLMs). SHIELD leverages the implicit knowledge of LLMs to uncover hidden attack patterns in provenance data, while reducing false positives and providing clear, interpretable attack descriptions. This reduces analysts' alert fatigue and makes it easier for them to understand the threat landscape. Our extensive evaluation demonstrates SHIELD's effectiveness and computational efficiency in real-world scenarios. SHIELD was shown to outperform state-of-the-art methods, achieving higher precision and recall. SHIELD's integration of anomaly detection, LLM-driven contextual analysis, and advanced graph-based correlation establishes a new benchmark for APT detection.

[Arxiv](https://arxiv.org/abs/2502.02342)