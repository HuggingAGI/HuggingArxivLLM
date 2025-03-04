# 观点：当评估数据不足数百条时，建议不要在LLM评估中使用CLT

发布时间：2025年03月03日

`LLM理论` `机器学习` `统计学`

> Position: Don't use the CLT in LLM evals with fewer than a few hundred datapoints

# 摘要

> 评估大型语言模型（LLMs）的性能，离不开严谨的统计分析，包括准确的误差范围和显著性检验。当前，这类评估通常依赖于中心极限定理（CLT）。然而，我们认为，尽管CLT在处理大规模数据时表现良好，但对于依赖于小型、高度专业化的基准测试的LLM评估，它却力不从心，往往低估了不确定性，导致误差范围过窄。我们建议采用更合适的频率学派和贝叶斯方法，这些方法不仅易于实施，而且在当今常见的小样本场景中更为适用。为了方便大家使用，我们开发了一个简单的Python库，地址是https://github.com/sambowyer/bayes_evals 。


> Rigorous statistical evaluations of large language models (LLMs), including valid error bars and significance testing, are essential for meaningful and reliable performance assessment. Currently, when such statistical measures are reported, they typically rely on the Central Limit Theorem (CLT). In this position paper, we argue that while CLT-based methods for uncertainty quantification are appropriate when benchmarks consist of thousands of examples, they fail to provide adequate uncertainty estimates for LLM evaluations that rely on smaller, highly specialized benchmarks. In these small-data settings, we demonstrate that CLT-based methods perform very poorly, usually dramatically underestimating uncertainty (i.e. producing error bars that are too small). We give recommendations for alternative frequentist and Bayesian methods that are both easy to implement and more appropriate in these increasingly common scenarios. We provide a simple Python library for these Bayesian methods at https://github.com/sambowyer/bayes_evals .

[Arxiv](https://arxiv.org/abs/2503.01747)