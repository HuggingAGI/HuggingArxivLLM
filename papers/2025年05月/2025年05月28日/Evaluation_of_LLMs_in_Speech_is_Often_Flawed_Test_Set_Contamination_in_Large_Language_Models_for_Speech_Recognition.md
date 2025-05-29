# 语音领域LLM评估常有缺陷：语音识别中大型语言模型的测试集污染问题

发布时间：2025年05月28日

`LLM应用` `语音技术` `数据科学`

> Evaluation of LLMs in Speech is Often Flawed: Test Set Contamination in Large Language Models for Speech Recognition

# 摘要

> 最近的研究表明，大型语言模型（LLMs）在语音任务上的表现优于传统系统。研究者常引用LibriSpeech和Common Voice数据集的实验结果来支持这一结论。然而，本研究发现，这两个数据集中的相当一部分内容实际上出现在公开的LLM预训练语料库中，这引发了对基于这两个数据集的研究结果可靠性的质疑。通过比较受污染和不受污染的LLMs，我们发现受污染的LLM更可能生成其在训练中见过的测试句子。使用受污染LLM的语音识别器在错误率上差异不大，但在训练中见过的转录结果上分配了显著更高的概率。实验结果表明，即使数据泄露量很小，也会导致LLM输出结果产生偏差。这凸显了在评估LLM语音系统时使用独立数据集的重要性。

> Recent work suggests that large language models (LLMs) can improve performance of speech tasks compared to existing systems. To support their claims, results on LibriSpeech and Common Voice are often quoted. However, this work finds that a substantial amount of the LibriSpeech and Common Voice evaluation sets appear in public LLM pretraining corpora. This calls into question the reliability of findings drawn from these two datasets. To measure the impact of contamination, LLMs trained with or without contamination are compared, showing that a contaminated LLM is more likely to generate test sentences it has seen during training. Speech recognisers using contaminated LLMs shows only subtle differences in error rates, but assigns significantly higher probabilities to transcriptions seen during training. Results show that LLM outputs can be biased by tiny amounts of data contamination, highlighting the importance of evaluating LLM-based speech systems with held-out data.

[Arxiv](https://arxiv.org/abs/2505.22251)