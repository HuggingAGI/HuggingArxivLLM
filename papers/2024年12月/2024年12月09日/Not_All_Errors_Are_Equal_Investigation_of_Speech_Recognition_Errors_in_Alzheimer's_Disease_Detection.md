# 并非所有错误都一概而论：关于阿尔茨海默病检测中语音识别错误的探究

发布时间：2024年12月09日

`LLM应用` `语音识别`

> Not All Errors Are Equal: Investigation of Speech Recognition Errors in Alzheimer's Disease Detection

# 摘要

> 自动语音识别（ASR）在基于语音的阿尔茨海默病（AD）自动检测中起着关键作用。然而，识别错误可能向下游蔓延，对检测决策可能产生潜在影响。近期研究表明，单词错误率（WER）与 AD 检测性能之间存在非线性关系，即存在明显错误的 ASR 转录仍可能实现与基于手动转录相同的 AD 检测准确率。本工作展开了一系列分析，旨在探究 ASR 转录错误在基于 BERT 的 AD 检测系统中的作用。我们的调研发现，并非所有 ASR 错误对检测性能的影响都相同。某些词，比如停用词，尽管错误占比大，但在区分 AD 时作用有限。相反，与诊断任务相关的关键词相比其他词重要性显著更高。这些发现为 ASR 错误与下游检测模型的相互作用提供了深刻见解。

> Automatic Speech Recognition (ASR) plays an important role in speech-based automatic detection of Alzheimer's disease (AD). However, recognition errors could propagate downstream, potentially impacting the detection decisions. Recent studies have revealed a non-linear relationship between word error rates (WER) and AD detection performance, where ASR transcriptions with notable errors could still yield AD detection accuracy equivalent to that based on manual transcriptions. This work presents a series of analyses to explore the effect of ASR transcription errors in BERT-based AD detection systems. Our investigation reveals that not all ASR errors contribute equally to detection performance. Certain words, such as stopwords, despite constituting a large proportion of errors, are shown to play a limited role in distinguishing AD. In contrast, the keywords related to diagnosis tasks exhibit significantly greater importance relative to other words. These findings provide insights into the interplay between ASR errors and the downstream detection model.

[Arxiv](https://arxiv.org/abs/2412.06332)