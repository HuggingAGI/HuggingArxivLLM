# MMD-Flagger：通过最大均值差异检测幻觉

发布时间：2025年06月02日

`LLM应用` `内容安全`

> MMD-Flagger: Leveraging Maximum Mean Discrepancy to Detect Hallucinations

# 摘要

> 大型语言模型（LLMs）已经渗透到我们的日常生活中，但它们在生成与现实脱节的流畅内容方面存在根本性问题，这限制了它们在关键应用中的使用。因此，检测这种幻觉内容至关重要。我们提出了一种新方法——MMD-Flagger，用于标记幻觉内容。该方法基于最大均值差异（MMD），一种衡量分布之间差异的非参数距离。从宏观上看，MMD-Flagger通过追踪生成文档与使用不同温度参数生成的文档之间的MMD来工作。我们通过实验证明，观察这一轨迹的形状足以检测到大部分幻觉内容。这一新方法在两个机器翻译数据集上进行了基准测试，并且在这些数据集上优于自然竞争对手。

> Large language models (LLMs) have become pervasive in our everyday life. Yet, a fundamental obstacle prevents their use in many critical applications: their propensity to generate fluent, human-quality content that is not grounded in reality. The detection of such hallucinations is thus of the highest importance. In this work, we propose a new method to flag hallucinated content, MMD-Flagger. It relies on Maximum Mean Discrepancy (MMD), a non-parametric distance between distributions. On a high-level perspective, MMD-Flagger tracks the MMD between the generated documents and documents generated with various temperature parameters. We show empirically that inspecting the shape of this trajectory is sufficient to detect most hallucinations. This novel method is benchmarked on two machine translation datasets, on which it outperforms natural competitors.

[Arxiv](https://arxiv.org/abs/2506.01367)