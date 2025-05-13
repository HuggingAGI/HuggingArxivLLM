# 分心效应：解析 RAG 中的无关段落

发布时间：2025年05月11日

`RAG`

> The Distracting Effect: Understanding Irrelevant Passages in RAG

# 摘要

> 检索增强生成 (RAG) 中一个众所周知的问题是，与查询无关的检索片段有时会干扰回答生成的 LLM，导致其提供错误的回答。本文聚焦于这一核心问题，针对查询（以及 LLM）定义了片段的干扰效应。我们提供了一个可量化衡量片段干扰效应的指标，并验证了其在不同 LLM 中的稳健性。

    本研究引入了识别和利用高干扰片段以提升 RAG 系统的新方法。通过使用这些精心挑选的干扰片段对 LLM 进行微调，与基于传统 RAG 数据集微调的模型相比，我们的方法使回答准确率提高了 7.5%。我们的贡献体现在两个方面：首先，我们突破了将无关片段简单划分为完全不相关或干扰的二元分类，其次，我们开发并分析了多种用于发现高干扰片段的方法。据我们所知，目前尚无其他研究提供如此全面的框架来识别和利用高干扰片段。

> A well-known issue with Retrieval Augmented Generation (RAG) is that retrieved passages that are irrelevant to the query sometimes distract the answer-generating LLM, causing it to provide an incorrect response. In this paper, we shed light on this core issue and formulate the distracting effect of a passage w.r.t. a query (and an LLM). We provide a quantifiable measure of the distracting effect of a passage and demonstrate its robustness across LLMs.
  Our research introduces novel methods for identifying and using hard distracting passages to improve RAG systems. By fine-tuning LLMs with these carefully selected distracting passages, we achieve up to a 7.5% increase in answering accuracy compared to counterparts fine-tuned on conventional RAG datasets. Our contribution is two-fold: first, we move beyond the simple binary classification of irrelevant passages as either completely unrelated vs. distracting, and second, we develop and analyze multiple methods for finding hard distracting passages. To our knowledge, no other research has provided such a comprehensive framework for identifying and utilizing hard distracting passages.

[Arxiv](https://arxiv.org/abs/2505.06914)