# 头奖！对齐：最大彩票的奥秘

发布时间：2025年01月31日

`LLM理论

理由：这篇论文讨论了RLHF（Reinforcement Learning from Human Feedback）的局限性，并提出了一种新的方法——最大彩票（Maximum Lottery）来替代RLHF。论文的核心在于理论上的改进和证明，特别是如何通过NLHF（Natural Language Human Feedback）及其变体来近似最大彩票的结果，从而继承其有益特性。这些内容主要涉及LLM的理论改进和优化，因此应归类为LLM理论。` `人工智能` `社会选择`

> Jackpot! Alignment as a Maximal Lottery

# 摘要

> # 摘要
RLHF 作为将 LLMs 与人类价值观对齐的标准方法，却无法满足一些直观期望的特性，例如尊重多数人的偏好 \cite{ge2024axioms}。为此，我们提出用 \emph{最大彩票} 这一概率社会选择规则替代 RLHF。我们证明，NLHF 及其变体能够近似最大彩票结果，从而继承其有益特性。
实验表明，我们的方法在处理偏好时比 RLHF 更稳健，包括支持多数人偏好、处理非传递性偏好数据，以及对无关替代项的稳健性。这使得系统能更好地融入人类价值观并尊重人类意图。

> Reinforcement Learning from Human Feedback (RLHF), the standard for aligning Large Language Models (LLMs) with human values, is known to fail to satisfy properties that are intuitively desirable, such as respecting the preferences of the majority \cite{ge2024axioms}. To overcome these issues, we propose the use of a probabilistic Social Choice rule called \emph{maximal lotteries} as a replacement for RLHF. We show that a family of alignment techniques, namely Nash Learning from Human Feedback (NLHF) \cite{munos2023nash} and variants, approximate maximal lottery outcomes and thus inherit its beneficial properties.
  We confirm experimentally that our proposed methodology handles situations that arise when working with preferences more robustly than standard RLHF, including supporting the preferences of the majority, providing principled ways of handling non-transitivities in the preference data, and robustness to irrelevant alternatives. This results in systems that better incorporate human values and respect human intentions.

[Arxiv](https://arxiv.org/abs/2501.19266)