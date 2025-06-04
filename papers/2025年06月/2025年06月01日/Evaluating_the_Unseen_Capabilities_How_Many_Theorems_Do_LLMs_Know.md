# 评估未见能力：LLMs 知晓多少定理？

发布时间：2025年06月01日

`LLM理论

理由：这篇论文探讨了大型语言模型的评估方法，提出了一种新的统计框架来更全面地评估模型的能力，特别是通过量化未见知识。这属于对LLM内在机制和评估方法的理论研究，因此归类为LLM理论。` `人工智能` `模型评估`

> Evaluating the Unseen Capabilities: How Many Theorems Do LLMs Know?

# 摘要

> 准确评估大型语言模型（LLMs）的能力对于理解其潜力并指导其发展至关重要。然而，现有的评估方法往往未能准确反映这些模型的真实能力。本文揭示了导致当前	extit{评估危机}的一个关键因素：忽视了模型内部的未见知识——即LLMs编码但未在评估中直接观察到的信息。为此，我们提出了一个名为KnowSum的统计框架，通过量化未见知识，为一类评估任务提供更全面的评估。KnowSum通过分析已观察知识实例的频率分布，推断出未被观察的部分。我们通过三个关键应用场景验证了KnowSum的有效性和实用性：估算模型总知识量、评估信息检索效果以及衡量输出多样性。实验结果表明，仅依赖观察到的LLM性能会导致大量知识被遗漏。尤为重要的是，KnowSum基于不同LLMs内部知识的差异，产生了显著不同的比较排名，这一发现对多种常见LLMs具有重要意义。

> Accurate evaluation of large language models (LLMs) is crucial for understanding their capabilities and guiding their development. However, current evaluations often inconsistently reflect the actual capacities of these models. In this paper, we demonstrate that one of many contributing factors to this \textit{evaluation crisis} is the oversight of unseen knowledge -- information encoded by LLMs but not directly observed or not yet observed during evaluations. We introduce KnowSum, a statistical framework designed to provide a more comprehensive assessment by quantifying the unseen knowledge for a class of evaluation tasks. KnowSum estimates the unobserved portion by extrapolating from the appearance frequencies of observed knowledge instances. We demonstrate the effectiveness and utility of KnowSum across three critical applications: estimating total knowledge, evaluating information retrieval effectiveness, and measuring output diversity. Our experiments reveal that a substantial volume of knowledge is omitted when relying solely on observed LLM performance. Importantly, KnowSum yields significantly different comparative rankings for several common LLMs based on their internal knowledge.

[Arxiv](https://arxiv.org/abs/2506.02058)