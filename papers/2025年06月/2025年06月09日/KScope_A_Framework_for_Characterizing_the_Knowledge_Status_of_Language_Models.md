# KScope：刻画语言模型知识状态的框架

发布时间：2025年06月09日

`LLM理论

摘要中的论文专注于大型语言模型（LLM）的知识表征和分类，提出了一种新的知识状态分类法，并开发了一个分析框架。这属于对模型内部机制的理论研究，因此归类为LLM理论。` `人工智能`

> KScope: A Framework for Characterizing the Knowledge Status of Language Models

# 摘要

> 大型语言模型（LLM）对问题知识的表征充满挑战。先前研究多聚焦于模型在知识冲突时的行为，即其内部参数记忆与外部上下文信息相悖的情况。然而，这并未全面反映模型对问题答案的掌握程度。本文首先基于LLM知识模式的一致性和正确性，提出五种知识状态分类法。随后，我们开发了KScope框架，这是一个分层统计测试体系，逐步细化知识模式假设，并将LLM知识归类至五种状态。通过在四个数据集上的九种LLM应用KScope，我们系统性发现：支持性上下文能有效缩小模型间知识差距；难度、相关性和熟悉度等上下文特征是成功知识更新的关键；模型在部分正确或冲突时特征偏好相似，但在持续错误时则差异显著；基于特征分析的上下文摘要，结合增强可信度，可进一步提升更新效果并实现跨模型泛化。

> Characterizing a large language model's (LLM's) knowledge of a given question is challenging. As a result, prior work has primarily examined LLM behavior under knowledge conflicts, where the model's internal parametric memory contradicts information in the external context. However, this does not fully reflect how well the model knows the answer to the question. In this paper, we first introduce a taxonomy of five knowledge statuses based on the consistency and correctness of LLM knowledge modes. We then propose KScope, a hierarchical framework of statistical tests that progressively refines hypotheses about knowledge modes and characterizes LLM knowledge into one of these five statuses. We apply KScope to nine LLMs across four datasets and systematically establish: (1) Supporting context narrows knowledge gaps across models. (2) Context features related to difficulty, relevance, and familiarity drive successful knowledge updates. (3) LLMs exhibit similar feature preferences when partially correct or conflicted, but diverge sharply when consistently wrong. (4) Context summarization constrained by our feature analysis, together with enhanced credibility, further improves update effectiveness and generalizes across LLMs.

[Arxiv](https://arxiv.org/abs/2506.07458)