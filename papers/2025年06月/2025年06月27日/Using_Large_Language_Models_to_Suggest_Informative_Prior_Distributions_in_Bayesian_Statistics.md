# # 使用大型语言模型为贝叶斯统计建议信息先验分布
如何利用大型语言模型为贝叶斯统计提供信息先验分布

发布时间：2025年06月27日

`LLM应用` `统计学` `数据分析`

> Using Large Language Models to Suggest Informative Prior Distributions in Bayesian Statistics

# 摘要

> 在贝叶斯统计学中，选择先验分布是一项既具挑战性又耗费资源且主观性较强的任务。我们探索了利用大型语言模型（LLMs）来建议合适且基于知识的先验分布的可能性。为此，我们设计了一个详尽的提示，要求LLMs不仅能够建议先验分布，还能验证并反思其选择。

我们对Claude Opus、Gemini 2.5 Pro和ChatGPT-4o-mini进行了评估，使用了两个真实数据集：心脏病风险和混凝土强度。所有LLMs均准确识别了所有关联的方向（例如，男性患心脏病的风险更高）。我们通过计算建议的先验分布与最大似然估计器分布之间的Kullback-Leibler散度来评估先验分布的质量。

LLMs建议了中度和弱度的先验分布。中度先验分布往往过于自信，导致分布与数据不一致。在实验中，Claude和Gemini的表现优于ChatGPT。对于弱度先验分布，出现了一个关键性能差异：ChatGPT和Gemini默认使用一个“不必要模糊”的均值0，而Claude则没有这种倾向，显示出显著优势。

LLMs识别正确关联的能力表明，它们作为高效、客观的方法来开发先验分布具有巨大潜力。然而，如何校准这些先验分布的宽度以避免过度或欠自信仍然是主要的挑战。


> Selecting prior distributions in Bayesian statistics is challenging, resource-intensive, and subjective. We analyze using large-language models (LLMs) to suggest suitable, knowledge-based informative priors. We developed an extensive prompt asking LLMs not only to suggest priors but also to verify and reflect on their choices.
  We evaluated Claude Opus, Gemini 2.5 Pro, and ChatGPT-4o-mini on two real datasets: heart disease risk and concrete strength. All LLMs correctly identified the direction for all associations (e.g., that heart disease risk is higher for males). The quality of suggested priors was measured by their Kullback-Leibler divergence from the maximum likelihood estimator's distribution.
  The LLMs suggested both moderately and weakly informative priors. The moderate priors were often overconfident, resulting in distributions misaligned with the data. In our experiments, Claude and Gemini provided better priors than ChatGPT. For weakly informative priors, a key performance difference emerged: ChatGPT and Gemini defaulted to an "unnecessarily vague" mean of 0, while Claude did not, demonstrating a significant advantage.
  The ability of LLMs to identify correct associations shows their great potential as an efficient, objective method for developing informative priors. However, the primary challenge remains in calibrating the width of these priors to avoid over- and under-confidence.

[Arxiv](https://arxiv.org/abs/2506.21964)