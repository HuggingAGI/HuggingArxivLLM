# 从偏见到改进提示：克隆检测模型偏见缓解的案例分析

发布时间：2025年05月08日

`LLM应用` `软件工程` `代码检测`

> From Bias To Improved Prompts: A Case Study of Bias Mitigation of Clone Detection Models

# 摘要

> 克隆代码一直是软件工程中的顽疾，主要源于开发者常复制粘贴代码段。这一普遍现象使得克隆代码检测的重要性愈发凸显，吸引了软件工程研究者和行业从业者的广泛关注。这种关注源于克隆代码可能对软件质量产生的负面影响。生成式大语言模型（LLMs）的崛起，如 ChatGPT，使克隆代码问题更加棘手。这些模型的代码生成能力可能无意中生成代码克隆。因此，检测克隆代码的需求比以往任何时候都更加迫切。在本研究中，我们评估了 LLMs 在克隆代码检测方面的适用性。结果显示，Palm 模型在 avatar 数据集上达到了 89.30 的高 F1 分数，在 poolC 数据集上达到了 86.41。LLMs 的一个已知问题是容易受到提示偏见的影响，这些模型的性能会因输入提示的不同而有所波动。在我们的研究中，我们深入探讨了这些波动背后的原因，并提出了一种框架，以缓解克隆检测中的提示偏见。我们的分析识别出了八种不同的提示偏见类别，而我们基于这些偏见设计的方法，使 F1 分数显著提升了 10.81%。这些发现凸显了提示偏见对 LLMs 性能的重大影响，并强调了利用模型错误来缓解这种偏见的潜力。

> The issue of clone code has persisted in software engineering, primarily because developers often copy and paste code segments. This common practice has elevated the importance of clone code detection, garnering attention from both software engineering researchers and industry professionals. Their collective concern arises from the potential negative impacts that clone code can have on software quality. The emergence of powerful Generative Large Language Models (LLMs) like ChatGPT has exacerbated the clone code problem. These advanced models possess code generation capabilities that can inadvertently create code clones. As a result, the need to detect clone code has become more critical than ever before. In this study, we assess the suitability of LLMs for clone code detection. Our results demonstrate that the Palm model achieved a high F1 score of 89.30 for the avatar dataset and 86.41 for the poolC dataset. A known issue with LLMs is their susceptibility to prompt bias, where the performance of these models fluctuates based on the input prompt provided. In our research, we delve deeper into the reasons behind these fluctuations and propose a framework to mitigate prompt bias for clone detection. Our analysis identifies eight distinct categories of prompt bias, and our devised approach leveraging these biases yields a significant improvement of up to 10.81% in the F1 score. These findings underscore the substantial impact of prompt bias on the performance of LLMs and highlight the potential for leveraging model errors to alleviate this bias.

[Arxiv](https://arxiv.org/abs/2505.05679)