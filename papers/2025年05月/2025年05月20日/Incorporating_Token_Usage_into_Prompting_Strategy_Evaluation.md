# 将Token使用融入提示策略评估

发布时间：2025年05月20日

`LLM理论` `机器学习` `人工智能`

> Incorporating Token Usage into Prompting Strategy Evaluation

# 摘要

> 近年来，大型语言模型在多种任务中展现了卓越的表现。然而，其任务效果高度依赖于提示策略，这些策略在性能和token使用上差异显著。尽管任务性能常被用来衡量提示策略的成功，但我们主张效率——即在性能和token使用之间取得平衡——可以作为更具实用价值的现实世界指标。为此，我们提出了Big-$O_{tok}$，这是一个用于描述提示策略token使用增长的理论框架，并分析了Token Cost，这是一个衡量每单位性能所用token的实证指标。我们将这些方法应用于几种常见的提示策略，并发现增加token使用会导致性能回报急剧下降。我们的结果验证了Big-$O_{tok}$分析，并进一步强调了需要进行效率意识的评估。

> In recent years, large language models have demonstrated remarkable performance across diverse tasks. However, their task effectiveness is heavily dependent on the prompting strategy used to elicit output, which can vary widely in both performance and token usage. While task performance is often used to determine prompting strategy success, we argue that efficiency--balancing performance and token usage--can be a more practical metric for real-world utility. To enable this, we propose Big-$O_{tok}$, a theoretical framework for describing the token usage growth of prompting strategies, and analyze Token Cost, an empirical measure of tokens per performance. We apply these to several common prompting strategies and find that increased token usage leads to drastically diminishing performance returns. Our results validate the Big-$O_{tok}$ analyses and reinforce the need for efficiency-aware evaluations.

[Arxiv](https://arxiv.org/abs/2505.14880)