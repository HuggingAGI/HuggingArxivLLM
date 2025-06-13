# 从语言反馈中学习的可证明方法

发布时间：2025年06月12日

`LLM理论`

> Provably Learning from Language Feedback

# 摘要

> 交互式地从观察和语言反馈中学习是一个日益受到关注的领域，这一领域的发展得益于大型语言模型（LLM）代理的出现。尽管已经展示了令人印象深刻的实证演示，但到目前为止，对这些决策问题的系统化框架仍然缺乏。在本文中，我们正式定义了从语言反馈中学习（LLF）的问题，提出了足够的假设以支持即使存在潜在奖励也能进行学习，并引入了【数学公式】作为复杂度度量，用于表征LLF问题的难度。我们证明，【数学公式】捕捉了反馈中的信息会改变LLF问题学习复杂性的直觉。我们展示了在某些情况下，从丰富的语言反馈中学习可以比从奖励中学习快得多。我们开发了一个无悔算法，名为【数学公式】，它通过序列交互能够证明解决LLF问题，并且其性能保证与问题的【数学公式】成比例。在多个经验领域中，我们展示了即使在反复提示LLMs不可靠的情况下，【数学公式】仍然表现良好。我们的贡献标志着从通用语言反馈设计系统化交互式学习算法的第一步。

> Interactively learning from observation and language feedback is an increasingly studied area driven by the emergence of large language model (LLM) agents. While impressive empirical demonstrations have been shown, so far a principled framing of these decision problems remains lacking. In this paper, we formalize the Learning from Language Feedback (LLF) problem, assert sufficient assumptions to enable learning despite latent rewards, and introduce $\textit{transfer eluder dimension}$ as a complexity measure to characterize the hardness of LLF problems. We show that transfer eluder dimension captures the intuition that information in the feedback changes the learning complexity of the LLF problem. We demonstrate cases where learning from rich language feedback can be exponentially faster than learning from reward. We develop a no-regret algorithm, called $\texttt{HELiX}$, that provably solves LLF problems through sequential interactions, with performance guarantees that scale with the transfer eluder dimension of the problem. Across several empirical domains, we show that $\texttt{HELiX}$ performs well even when repeatedly prompting LLMs does not work reliably. Our contributions mark a first step towards designing principled interactive learning algorithms from generic language feedback.

[Arxiv](https://arxiv.org/abs/2506.10341)