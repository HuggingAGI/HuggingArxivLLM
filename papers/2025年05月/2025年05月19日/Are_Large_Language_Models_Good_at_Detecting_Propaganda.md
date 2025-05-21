# 大型语言模型能否有效识别宣传？

发布时间：2025年05月19日

`LLM应用` `媒体传播`

> Are Large Language Models Good at Detecting Propaganda?

# 摘要

> 宣传者通过逻辑谬误和情感诉求的修辞手法来推进议程。识别这些技巧对明智决策至关重要。得益于自然语言处理（NLP）的最新进展，我们能够开发出检测操纵性内容的系统。本研究聚焦于几种大型语言模型（LLMs），评估它们在新闻文章中识别宣传技巧的能力。我们将这些模型的表现与基于变压器的模型进行了对比。研究发现，尽管GPT-4在F1分数上（F1=0.16）领先于GPT-3.5和Claude 3 Opus，但其表现仍不及RoBERTa-CRF基准模型（F1=0.67）。此外，所有三种LLMs在检测六种宣传技巧中的一种（名称攻击）时优于多粒度网络（MGN）基准模型，而GPT-3.5和GPT-4在检测恐惧诉求和爱国主义诉求方面也优于MGN基准模型。

> Propagandists use rhetorical devices that rely on logical fallacies and emotional appeals to advance their agendas. Recognizing these techniques is key to making informed decisions. Recent advances in Natural Language Processing (NLP) have enabled the development of systems capable of detecting manipulative content. In this study, we look at several Large Language Models and their performance in detecting propaganda techniques in news articles. We compare the performance of these LLMs with transformer-based models. We find that, while GPT-4 demonstrates superior F1 scores (F1=0.16) compared to GPT-3.5 and Claude 3 Opus, it does not outperform a RoBERTa-CRF baseline (F1=0.67). Additionally, we find that all three LLMs outperform a MultiGranularity Network (MGN) baseline in detecting instances of one out of six propaganda techniques (name-calling), with GPT-3.5 and GPT-4 also outperforming the MGN baseline in detecting instances of appeal to fear and flag-waving.

[Arxiv](https://arxiv.org/abs/2505.13706)