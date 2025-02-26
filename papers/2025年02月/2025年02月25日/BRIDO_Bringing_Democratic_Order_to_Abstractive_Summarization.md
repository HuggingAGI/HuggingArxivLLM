# BRIDO：为生成式摘要注入民主秩序

发布时间：2025年02月25日

`LLM应用` `文本摘要`

> BRIDO: Bringing Democratic Order to Abstractive Summarization

# 摘要

> 幻觉（Hallucination）指的是大型语言模型（LLMs）生成的不准确、不相关且不一致的文本。尽管LLMs在多种任务中展现出巨大潜力，但幻觉问题仍然是许多实际应用中的主要挑战。本文针对摘要文本总结中的幻觉问题，通过缓解曝光偏差来应对这一挑战。现有缓解曝光偏差的模型如BRIO，旨在通过提升ROUGE分数改善总结质量。我们提出了一种采用类似策略但目标更聚焦于减少幻觉的模型。我们推测，在一组候选输出中，存在幻觉的输出将占据少数。也就是说，与其他候选输出相似度较低的候选更有可能包含幻觉内容。我们的方法利用了这一特点，并采用对比学习，激励具有较高候选间ROUGE分数的候选。我们在XSum和CNN/DM摘要数据集上进行了实验，与BRIO相比，我们的方法在一致性G-Eval分数上分别提高了6.25%和3.82%。

> Hallucination refers to the inaccurate, irrelevant, and inconsistent text generated from large language models (LLMs). While the LLMs have shown great promise in a variety of tasks, the issue of hallucination still remains a major challenge for many practical uses. In this paper, we tackle the issue of hallucination in abstract text summarization by mitigating exposure bias. Existing models targeted for exposure bias mitigation, namely BRIO, aim for better summarization quality in the ROUGE score. We propose a model that uses a similar exposure bias mitigation strategy but with a goal that is aligned with less hallucination. We conjecture that among a group of candidate outputs, ones with hallucinations will comprise the minority of the whole group. That is, candidates with less similarity with others will have a higher chance of containing hallucinated content. Our method uses this aspect and utilizes contrastive learning, incentivizing candidates with high inter-candidate ROUGE scores. We performed experiments on the XSum and CNN/DM summarization datasets, and our method showed 6.25% and 3.82% improvement, respectively, on the consistency G-Eval score over BRIO.

[Arxiv](https://arxiv.org/abs/2502.18342)