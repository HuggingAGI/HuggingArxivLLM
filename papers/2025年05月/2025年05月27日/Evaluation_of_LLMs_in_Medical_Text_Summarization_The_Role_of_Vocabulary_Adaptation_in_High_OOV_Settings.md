# # 大型语言模型在医学文本摘要中的表现评估：词汇适应在高OOV环境中的作用

发布时间：2025年05月27日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在医学文本摘要任务中的应用，特别是针对词汇不匹配问题提出了一种词汇适应策略。通过实验和人工评估，论文展示了该策略在提升模型性能方面的有效性。因此，它属于LLM应用类别。` `文本摘要`

> Evaluation of LLMs in Medical Text Summarization: The Role of Vocabulary Adaptation in High OOV Settings

# 摘要

> 大型语言模型（LLMs）近期在医学文本摘要任务中取得了巨大成功，但这些成功主要依赖于简单的上下文学习（in-context learning）。然而，现有研究并未在可能导致模型失效的困难场景下进行细致评估，通常仅报告整体数据集的性能。通过我们的基准测试研究发现，当数据点中含有大量未登录词（OOV）或具有高度新颖性时，LLMs的性能会出现显著下降。针对这一词汇不匹配问题，我们提出了一种直观的解决方案——词汇适应，即通过更新LLMs的词汇表，加入医学领域的特定词汇或子词。有趣的是，即使Llama-3.1的词汇量达到了约128K tokens，它在处理医学词汇时仍面临过度碎片化的问题。我们的实验表明，词汇适应策略能够在困难场景下显著提升LLMs的摘要性能。通过针对多个词汇适应策略、两种持续预训练策略以及三个基准医学摘要数据集的广泛实验，我们深入探讨了词汇适应策略在将LLMs定制到医学领域中的作用。此外，我们还与医学专家进行了人工评估研究，结果显示，采用词汇适应策略生成的摘要更加相关和忠实。我们的代码库已公开发布在https://github.com/gb-kgp/LLM-MedicalSummarization-Benchmark。

> Large Language Models (LLMs) recently achieved great success in medical text summarization by simply using in-context learning. However, these recent efforts do not perform fine-grained evaluations under difficult settings where LLMs might fail. They typically report performance scores over the entire dataset. Through our benchmarking study, we show that LLMs show a significant performance drop for data points with high concentration of out-of-vocabulary (OOV) words or with high novelty. Vocabulary adaptation is an intuitive solution to this vocabulary mismatch issue where the LLM vocabulary gets updated with certain expert domain (here, medical) words or subwords. An interesting finding from our study is that Llama-3.1, even with a vocabulary size of around 128K tokens, still faces over-fragmentation issue with medical words. To that end, we show vocabulary adaptation helps improve the LLM summarization performance even in difficult settings. Through extensive experimentation of multiple vocabulary adaptation strategies, two continual pretraining strategies, and three benchmark medical summarization datasets, we gain valuable insights into the role of vocabulary adaptation strategies for customizing LLMs to the medical domain. We also performed a human evaluation study with medical experts where they found that vocabulary adaptation results in more relevant and faithful summaries. Our codebase is made publicly available at https://github.com/gb-kgp/LLM-MedicalSummarization-Benchmark.

[Arxiv](https://arxiv.org/abs/2505.21242)