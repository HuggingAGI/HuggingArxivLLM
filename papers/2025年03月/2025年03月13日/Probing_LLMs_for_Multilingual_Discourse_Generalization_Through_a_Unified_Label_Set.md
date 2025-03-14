# # 探究 LLMs 的多语言话语泛化能力：通过统一标签集的方法
我们通过统一标签集深入探究大型语言模型的多语言话语泛化能力，揭示其跨语言理解与生成的潜力。

发布时间：2025年03月13日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在跨语言和跨框架话语理解中的能力，分析了模型的内在机制和泛化能力，属于对LLM理论的深入研究。` `人工智能`

> Probing LLMs for Multilingual Discourse Generalization Through a Unified Label Set

# 摘要

> 话语理解在自然语言处理（NLP）任务中扮演着关键角色，但现有研究大多受限于依赖特定框架的话语表示方法。本研究旨在探索大型语言模型（LLMs）是否能捕捉到跨语言和跨框架通用的话语知识。我们从两个维度展开研究：(1) 开发统一的话语关系标签集，以促进跨语言和跨框架的话语分析；(2) 探究LLMs是否编码了可通用化的话语抽象。通过多语言话语关系分类作为实验平台，我们评估了涵盖不同规模和多语言能力的23种LLMs。研究结果表明，LLMs，尤其是使用多语言训练语料库的模型，能够在跨语言和跨框架的场景下有效泛化话语信息。分层分析进一步显示，话语层面的泛化能力在中间层最为显著。最后，我们的错误分析深入探讨了具有挑战性的关系类别，为模型优化提供了有价值的见解。

> Discourse understanding is essential for many NLP tasks, yet most existing work remains constrained by framework-dependent discourse representations. This work investigates whether large language models (LLMs) capture discourse knowledge that generalizes across languages and frameworks. We address this question along two dimensions: (1) developing a unified discourse relation label set to facilitate cross-lingual and cross-framework discourse analysis, and (2) probing LLMs to assess whether they encode generalizable discourse abstractions. Using multilingual discourse relation classification as a testbed, we examine a comprehensive set of 23 LLMs of varying sizes and multilingual capabilities. Our results show that LLMs, especially those with multilingual training corpora, can generalize discourse information across languages and frameworks. Further layer-wise analyses reveal that language generalization at the discourse level is most salient in the intermediate layers. Lastly, our error analysis provides an account of challenging relation classes.

[Arxiv](https://arxiv.org/abs/2503.10515)