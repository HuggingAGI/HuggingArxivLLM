# 基于子句频率优化大语言模型的文本到SQL解析能力

发布时间：2025年05月26日

`LLM应用` `数据库`

> Calibrating LLMs for Text-to-SQL Parsing by Leveraging Sub-clause Frequencies

# 摘要

> 尽管大型语言模型（LLMs）在文本到SQL解析方面表现出色，但有时会出现令人意外的错误，且对错误结果充满信心。构建可靠文本到SQL系统需要从LLM中提取可靠的不确定性度量，这正是我们研究的核心问题。本文首次为基于LLM的文本到SQL解析的后验校准建立了基准。我们发现，作为经典校准方法的Platt缩放相比直接使用原始模型输出概率，能显著提升置信分数的可靠性。我们还提出了一种利用SQL结构特性的文本到SQL校准方法，名为'子句频率'(SCF)评分，提供更精细的正确性信号。通过我们对经典Platt缩放技术的扩展——多变量Platt缩放（MPS），我们将单个SCF评分结合成一个整体准确且校准良好的评分。在两个流行数据集上的实证评估表明，与传统Platt缩放相比，我们的结合MPS和SCF的方法在校准和错误检测任务上进一步提升了性能。

> While large language models (LLMs) achieve strong performance on text-to-SQL parsing, they sometimes exhibit unexpected failures in which they are confidently incorrect. Building trustworthy text-to-SQL systems thus requires eliciting reliable uncertainty measures from the LLM. In this paper, we study the problem of providing a calibrated confidence score that conveys the likelihood of an output query being correct. Our work is the first to establish a benchmark for post-hoc calibration of LLM-based text-to-SQL parsing. In particular, we show that Platt scaling, a canonical method for calibration, provides substantial improvements over directly using raw model output probabilities as confidence scores. Furthermore, we propose a method for text-to-SQL calibration that leverages the structured nature of SQL queries to provide more granular signals of correctness, named "sub-clause frequency" (SCF) scores. Using multivariate Platt scaling (MPS), our extension of the canonical Platt scaling technique, we combine individual SCF scores into an overall accurate and calibrated score. Empirical evaluation on two popular text-to-SQL datasets shows that our approach of combining MPS and SCF yields further improvements in calibration and the related task of error detection over traditional Platt scaling.

[Arxiv](https://arxiv.org/abs/2505.23804)