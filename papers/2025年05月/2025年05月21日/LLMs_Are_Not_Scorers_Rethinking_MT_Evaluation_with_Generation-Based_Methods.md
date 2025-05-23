# LLMs 不是评分器：以生成式方法重新思考机器翻译评估

发布时间：2025年05月21日

`LLM应用` `机器翻译`

> LLMs Are Not Scorers: Rethinking MT Evaluation with Generation-Based Methods

# 摘要

> 近期研究将大型语言模型（LLMs）应用于机器翻译质量评估（MTQE），通过提示模型分配数值分数。然而，这些直接评分方法与人工判断的段落级别相关性较低。本文提出了一种基于生成的评估范式，利用解码器-only LLMs生成高质量参考文本，并结合句子嵌入进行语义相似度评分。我们在MTQE领域进行了迄今最全面的评估，涵盖8种LLMs和8种语言对。实证结果表明，我们的方法不仅超越了基于LLM的直接评分基线，还在性能上优于来自MTME的外部非LLM无参考指标。这些发现彰显了基于生成的评估优势，并支持采用结合流畅生成与精准语义评估的混合方法。

> Recent studies have applied large language models (LLMs) to machine translation quality estimation (MTQE) by prompting models to assign numeric scores. Nonetheless, these direct scoring methods tend to show low segment-level correlation with human judgments. In this paper, we propose a generation-based evaluation paradigm that leverages decoder-only LLMs to produce high-quality references, followed by semantic similarity scoring using sentence embeddings. We conduct the most extensive evaluation to date in MTQE, covering 8 LLMs and 8 language pairs. Empirical results show that our method outperforms both intra-LLM direct scoring baselines and external non-LLM reference-free metrics from MTME. These findings demonstrate the strength of generation-based evaluation and support a shift toward hybrid approaches that combine fluent generation with accurate semantic assessment.

[Arxiv](https://arxiv.org/abs/2505.16129)