# 基于多模态大型语言模型的双向似然估计，实现文本与视频的高效检索

发布时间：2025年07月31日

`LLM应用` `信息检索` `多模态`

> Bidirectional Likelihood Estimation with Multi-Modal Large Language Models for Text-Video Retrieval

# 摘要

> 文本-视频检索的目标是从大规模在线数据库中，为给定的视频或文本查询找到最相关的文本或视频候选。近期研究通过多模态大型语言模型（MLLMs）提升检索效果，尤其在处理长或复杂查询-候选对时表现突出。然而，我们发现直接使用MLLMs进行基于候选似然的检索，会导致候选先验偏差，偏好那些具有更高内在先验但与查询相关性较低的候选。为此，我们提出了一种新颖的检索框架——基于MLLM的双向似然估计（BLiM）。该框架通过训练模型从视频生成文本以及从文本生成视频特征，同时利用查询和候选似然。此外，我们引入了候选先验归一化（CPN），这是一个简单而有效的无需训练的评分校准模块，旨在缓解候选似然中的候选先验偏差。在四个文本-视频检索基准数据集上，配备CPN的BLiM平均比之前最先进的模型在R@1指标上高出6.4，有效缓解了候选先验偏差并突出了查询-候选相关性。我们对检索以外的多种多模态任务的深入分析表明，CPN具有广泛适用性，通过减少对文本先验的依赖来增强视觉理解。代码可在https://github.com/mlvlab/BLiM获取。

> Text-Video Retrieval aims to find the most relevant text (or video) candidate given a video (or text) query from large-scale online databases. Recent work leverages multi-modal large language models (MLLMs) to improve retrieval, especially for long or complex query-candidate pairs. However, we observe that the naive application of MLLMs, i.e., retrieval based on candidate likelihood, introduces candidate prior bias, favoring candidates with inherently higher priors over those more relevant to the query. To this end, we propose a novel retrieval framework, Bidirectional Likelihood Estimation with MLLM (BLiM), which leverages both query and candidate likelihoods by training the model to generate text from a given video as well as video features from a given text. Furthermore, we introduce Candidate Prior Normalization (CPN), a simple yet effective training-free score calibration module designed to mitigate candidate prior bias in candidate likelihood. On four Text-Video Retrieval benchmarks, our BLiM equipped with CPN outperforms previous state-of-the-art models by 6.4 R@1 on average, effectively alleviating candidate prior bias and emphasizing query-candidate relevance. Our in-depth analysis across various multi-modal tasks beyond retrieval highlights the broad applicability of CPN which enhances visual understanding by reducing reliance on textual priors. Code is available at https://github.com/mlvlab/BLiM.

[Arxiv](https://arxiv.org/abs/2507.23284)