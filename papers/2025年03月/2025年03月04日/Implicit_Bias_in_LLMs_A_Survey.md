# # 隐性偏见在大型语言模型中的综述

发布时间：2025年03月04日

`LLM理论` `人工智能`

> Implicit Bias in LLMs: A Survey

# 摘要

> 由于开发人员实施了护栏机制，大型语言模型（LLMs）在显式偏见测试中表现出色。然而，LLMs中的偏见不仅可能显式存在，也可能隐式存在，就像人类有意识地追求公平，却仍然存在隐性偏见一样。隐式偏见的无意识和自动性质使其特别难以研究。本文对LLMs中隐式偏见的现有文献进行了全面综述。我们首先介绍了心理学中与隐式偏见相关的关键概念、理论和方法，并将其从人类扩展到LLMs。基于隐性联想测试（IAT）和其他心理学框架，我们将检测方法分为三种主要方法：单词联想、任务导向的文本生成和决策。我们将隐式偏见的评估指标分类为两类：基于单值的指标和基于比较值的指标。我们将数据集分为两类：带有屏蔽标记的句子和完整句子，并整合了来自各个领域的数据集，以反映LLMs的广泛应用。尽管关于缓解LLMs中隐式偏见的研究仍然有限，但我们总结了现有的努力，并对未来挑战提供了见解。我们希望这项工作能够为研究人员提供清晰的指南，并激发创新想法，以推动在此任务中的进一步探索。

> Due to the implement of guardrails by developers, Large language models (LLMs) have demonstrated exceptional performance in explicit bias tests. However, bias in LLMs may occur not only explicitly, but also implicitly, much like humans who consciously strive for impartiality yet still harbor implicit bias. The unconscious and automatic nature of implicit bias makes it particularly challenging to study. This paper provides a comprehensive review of the existing literature on implicit bias in LLMs. We begin by introducing key concepts, theories and methods related to implicit bias in psychology, extending them from humans to LLMs. Drawing on the Implicit Association Test (IAT) and other psychological frameworks, we categorize detection methods into three primary approaches: word association, task-oriented text generation and decision-making. We divide our taxonomy of evaluation metrics for implicit bias into two categories: single-value-based metrics and comparison-value-based metrics. We classify datasets into two types: sentences with masked tokens and complete sentences, incorporating datasets from various domains to reflect the broad application of LLMs. Although research on mitigating implicit bias in LLMs is still limited, we summarize existing efforts and offer insights on future challenges. We aim for this work to serve as a clear guide for researchers and inspire innovative ideas to advance exploration in this task.

[Arxiv](https://arxiv.org/abs/2503.02776)