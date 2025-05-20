# 提取开放权重语言模型中 memorized 的书籍片段，特别是受版权保护的书籍。

发布时间：2025年05月18日

`LLM应用` `生成式AI` `版权法`

> Extracting memorized pieces of (copyrighted) books from open-weight language models

# 摘要

> 在涉及生成式 AI 的版权诉讼中，原告和被告往往就大型语言模型 (LLMs) 对原告受版权保护的表达记忆的程度提出截然相反的主张。我们结合对抗性机器学习 (ML) 和版权法，揭示这些极端立场极大地简化了记忆与版权之间的关系。为此，我们利用一种最新的概率提取技术，从 13 个开源权重的 LLM 中提取了 Books3 数据集的部分内容。通过大量实验，我们发现从不同 LLM 中提取至少部分书籍内容是可行的，这表明这些模型确实记忆了提取的文本；这些记忆内容被嵌入到模型参数中。但结果并不简单：记忆的程度因模型和书籍而异。通过我们的具体实验，我们发现最大的 LLM 并没有记忆大多数书籍——无论是整体还是部分。然而，我们也发现 Llama 3.1 70B 几乎完全记忆了某些书籍，如《哈利·波特》和《1984》。我们讨论了这些结果为何对版权案件具有重大影响，尽管并非明确有利于任何一方。

> Plaintiffs and defendants in copyright lawsuits over generative AI often make sweeping, opposing claims about the extent to which large language models (LLMs) have memorized plaintiffs' protected expression. Drawing on adversarial ML and copyright law, we show that these polarized positions dramatically oversimplify the relationship between memorization and copyright. To do so, we leverage a recent probabilistic extraction technique to extract pieces of the Books3 dataset from 13 open-weight LLMs. Through numerous experiments, we show that it's possible to extract substantial parts of at least some books from different LLMs. This is evidence that the LLMs have memorized the extracted text; this memorized content is copied inside the model parameters. But the results are complicated: the extent of memorization varies both by model and by book. With our specific experiments, we find that the largest LLMs don't memorize most books -- either in whole or in part. However, we also find that Llama 3.1 70B memorizes some books, like Harry Potter and 1984, almost entirely. We discuss why our results have significant implications for copyright cases, though not ones that unambiguously favor either side.

[Arxiv](https://arxiv.org/abs/2505.12546)