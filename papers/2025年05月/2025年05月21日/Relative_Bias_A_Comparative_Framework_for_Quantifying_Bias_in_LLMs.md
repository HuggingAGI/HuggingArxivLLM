# 相对偏见：量化 LLMs 偏见的比较框架

发布时间：2025年05月21日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的公平性、安全性和社会影响，特别是偏见的量化问题。作者提出了一种相对偏见框架，并引入了两种方法来评估LLMs的行为偏差。这些内容属于对LLM本身的理论探讨和方法论改进，因此归类为LLM理论。` `社会影响` `伦理分析`

> Relative Bias: A Comparative Framework for Quantifying Bias in LLMs

# 摘要

> 大型语言模型（LLMs）的广泛应用引发了对其公平性、安全性和社会影响的更多担忧。然而，量化LLM偏见仍然面临根本性挑战，这一挑战因“偏见”定义的模糊性而更加复杂。随着新模型的迅速普及，潜在偏见问题日益突出，而这些偏见尚未经过系统评估。本文提出了一种相对偏见框架，用于评估LLM在特定领域内的行为偏差。我们还引入了两种互补方法：(1) 嵌入变换分析，通过句子在嵌入空间中的表示捕捉偏见模式；(2) LLM作为评判者，利用语言模型对输出进行比较评估。通过案例研究和统计验证，我们发现两种评分方法高度一致，为LLM的比较偏见分析提供了一种系统化、可扩展且基于统计的方法。

> The growing deployment of large language models (LLMs) has amplified concerns regarding their inherent biases, raising critical questions about their fairness, safety, and societal impact. However, quantifying LLM bias remains a fundamental challenge, complicated by the ambiguity of what "bias" entails. This challenge grows as new models emerge rapidly and gain widespread use, while introducing potential biases that have not been systematically assessed. In this paper, we propose the Relative Bias framework, a method designed to assess how an LLM's behavior deviates from other LLMs within a specified target domain. We introduce two complementary methodologies: (1) Embedding Transformation analysis, which captures relative bias patterns through sentence representations over the embedding space, and (2) LLM-as-a-Judge, which employs a language model to evaluate outputs comparatively. Applying our framework to several case studies on bias and alignment scenarios following by statistical tests for validation, we find strong alignment between the two scoring methods, offering a systematic, scalable, and statistically grounded approach for comparative bias analysis in LLMs.

[Arxiv](https://arxiv.org/abs/2505.17131)