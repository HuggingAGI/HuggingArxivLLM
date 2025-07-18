# 探索低困惑度LLM生成序列的奥秘与发现方法

发布时间：2025年07月02日

`LLM理论` `大型语言模型` `数据隐私`

> Low-Perplexity LLM-Generated Sequences and Where To Find Them

# 摘要

> 随着大型语言模型 (LLMs) 的广泛应用，理解训练数据对模型输出的影响变得至关重要，这关系到模型的透明度、问责制、隐私和公平性。为了深入研究 LLMs 如何利用和复制训练数据，我们提出了一种基于分析“低困惑度序列”的系统化方法，即模型生成的高概率文本片段。我们的方法能够可靠地提取跨不同主题的长序列，同时避免模型退化，并将这些序列追溯到其在训练数据中的来源。令人惊讶的是，我们发现这些低困惑度片段中相当一部分无法在语料库中找到对应来源。对于那些确实匹配的部分，我们量化了它们在来源文档中的分布，揭示了模型逐字记忆的范围和性质，从而为理解训练数据如何影响 LLMs 的行为提供了新视角。

> As Large Language Models (LLMs) become increasingly widespread, understanding how specific training data shapes their outputs is crucial for transparency, accountability, privacy, and fairness. To explore how LLMs leverage and replicate their training data, we introduce a systematic approach centered on analyzing low-perplexity sequences - high-probability text spans generated by the model. Our pipeline reliably extracts such long sequences across diverse topics while avoiding degeneration, then traces them back to their sources in the training data. Surprisingly, we find that a substantial portion of these low-perplexity spans cannot be mapped to the corpus. For those that do match, we quantify the distribution of occurrences across source documents, highlighting the scope and nature of verbatim recall and paving a way toward better understanding of how LLMs training data impacts their behavior.

[Arxiv](https://arxiv.org/abs/2507.01844)